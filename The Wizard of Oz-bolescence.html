<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Preservation Career Quiz</title>
    <!-- Use Tailwind CSS for a modern, responsive design -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
        }
        .btn-answer {
            transition: transform 0.2s, background-color 0.2s;
        }
        .btn-answer:hover {
            transform: translateY(-2px);
            background-color: #4a5568;
        }
    </style>
</head>
<body class="bg-gray-100 flex items-center justify-center min-h-screen p-4">

    <!-- Main Quiz Container -->
    <div id="quiz-container" class="bg-white shadow-xl rounded-2xl p-8 max-w-2xl w-full text-center">
        
        <h1 class="text-3xl font-bold text-gray-800 mb-4">Find Your Digital Preservation Career!</h1>
        <p class="text-gray-600 mb-6">Answer these 5 questions to see which role suits you best.</p>

        <!-- Question Section -->
        <div id="quiz-area">
            <h2 id="question-text" class="text-xl font-semibold text-gray-700 mb-6 min-h-[64px] flex items-center justify-center"></h2>
            <div id="answer-buttons" class="space-y-4">
                <!-- Answer buttons will be populated here by JavaScript -->
            </div>
        </div>

        <!-- Start Button -->
        <button id="start-button" class="btn-answer bg-blue-500 hover:bg-blue-600 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-all duration-300 transform hover:scale-105 mt-6">
            Start Quiz
        </button>

        <!-- Result Section -->
        <div id="result-area" class="hidden">
            <h2 class="text-2xl font-bold text-gray-800 mb-4">Your Perfect Match:</h2>
            <div class="bg-blue-100 p-6 rounded-lg border-2 border-blue-400">
                <h3 id="result-title" class="text-2xl font-bold text-blue-800 mb-2"></h3>
                <p id="result-description" class="text-gray-700 leading-relaxed"></p>
                <div class="mt-4 flex flex-col items-center">
                    <p class="text-sm text-gray-500 italic mb-2">How it differs from other roles:</p>
                    <p id="result-difference" class="text-gray-700 text-sm"></p>
                    <p class="text-sm text-gray-500 italic mt-4 mb-2">Key skills needed:</p>
                    <p id="result-skills" class="text-gray-700 text-sm"></p>
                </div>
            </div>

            <!-- New section for other options -->
            <div id="other-options-area" class="mt-8">
                <h3 class="text-xl font-semibold text-gray-700 mb-4">Other Possible Matches:</h3>
                <ul id="other-options-list" class="space-y-2 text-left">
                    <!-- Other matches will be listed here -->
                </ul>
            </div>

            <button id="restart-button" class="btn-answer bg-gray-500 hover:bg-gray-600 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-all duration-300 transform hover:scale-105 mt-6">
                Try Again
            </button>
        </div>
        
        <!-- Prototype text -->
        <div class="mt-6 text-sm text-gray-400">
            This is a protype made by Sean Macmillan (21.08.25), still in testing
        </div>

    </div>

    <script>
        // Data for the quiz questions, answers, and job suggestions.
        // The score object maps an answer to a job title, providing a score.
        // A higher score indicates a better fit.
        const quizData = [
            {
                question: "What is your primary interest when working with information?",
                answers: [
                    { text: "Preserving it for historical and cultural value.", scores: { 'Digital Archivist': 3, 'Digital Preservation Librarian': 2 } },
                    { text: "Ensuring it's compliant with legal and corporate rules.", scores: { 'Records Manager': 3, 'Digital Asset Manager': 1 } },
                    { text: "Managing the underlying technology and systems.", scores: { 'Digital Preservation Analyst/Technician': 3, 'Repository Manager/Administrator': 2, 'Systems Administrator/Developer': 2 } },
                    { text: "Organizing and adding context to make it useful.", scores: { 'Metadata Specialist': 3, 'Digital Curation Specialist': 2 } }
                ]
            },
            {
                question: "Which of these tasks would you enjoy most?",
                answers: [
                    { text: "Researching and writing policies for long-term preservation.", scores: { 'Digital Archivist': 2, 'Records Manager': 2, 'Digital Curation Specialist': 1 } },
                    { text: "Writing code and scripts to automate file format conversions.", scores: { 'Digital Preservation Analyst/Technician': 3, 'Systems Administrator/Developer': 3 } },
                    { text: "Collaborating with researchers and the public to provide access.", scores: { 'Digital Preservation Librarian': 3, 'Digital Archivist': 1 } },
                    { text: "Ensuring a project stays on schedule and within budget.", scores: { 'Digital Preservation Project Manager': 3 } }
                ]
            },
            {
                question: "What kind of environment do you prefer?",
                answers: [
                    { text: "A historical institution like a museum or an archive.", scores: { 'Digital Archivist': 3 } },
                    { text: "An academic or public library setting.", scores: { 'Digital Preservation Librarian': 3 } },
                    { text: "A highly technical, IT-focused department.", scores: { 'Systems Administrator/Developer': 3, 'Digital Preservation Analyst/Technician': 2, 'Repository Manager/Administrator': 2 } },
                    { text: "A project-based, fast-paced corporate environment.", scores: { 'Digital Asset Manager': 2, 'Digital Preservation Project Manager': 2, 'Records Manager': 1 } }
                ]
            },
            {
                question: "What is a core value you look for in your work?",
                answers: [
                    { text: "Ensuring the integrity and authenticity of information over time.", scores: { 'Digital Archivist': 3, 'Digital Preservation Analyst/Technician': 2 } },
                    { text: "Making knowledge accessible and easy to find for everyone.", scores: { 'Digital Preservation Librarian': 3, 'Metadata Specialist': 2, 'Digital Curation Specialist': 2 } },
                    { text: "Building and maintaining the systems that make everything work.", scores: { 'Repository Manager/Administrator': 3, 'Systems Administrator/Developer': 2 } },
                    { text: "Protecting information and managing risk for the organization.", scores: { 'Records Manager': 3, 'Digital Asset Manager': 2 } }
                ]
            },
            {
                question: "Your team is faced with a new, complex digital collection. What is your first instinct?",
                answers: [
                    { text: "Focus on the legal and administrative requirements for its handling.", scores: { 'Records Manager': 2, 'Digital Asset Manager': 1 } },
                    { text: "Analyze the file formats and technical characteristics to plan for long-term storage.", scores: { 'Digital Preservation Analyst/Technician': 3, 'Repository Manager/Administrator': 2 } },
                    { text: "Identify key information to describe and document the collection for future use.", scores: { 'Metadata Specialist': 3 } },
                    { text: "Develop a plan and coordinate the different experts needed to process it.", scores: { 'Digital Preservation Project Manager': 3, 'Digital Curation Specialist': 2 } }
                ]
            }
        ];

        // Job details, including descriptions and skills from the previous response.
        const jobDetails = {
            'Digital Archivist': {
                description: "A Digital Archivist is responsible for the acquisition, management, and long-term preservation of born-digital (created in a digital format) and digitized materials. They select, organize, and describe digital records to ensure their authenticity, integrity, and accessibility over time.",
                difference: "This role is often seen as the foundational digital preservation job. While other roles may specialize, the Digital Archivist typically has a broad scope, combining traditional archival principles with digital-specific practices.",
                skills: "Knowledge of archival theory, metadata standards (e.g., Dublin Core, PREMIS), file formats, digital forensics, and experience with digital asset management and repository systems."
            },
            'Digital Preservation Librarian': {
                description: "This role focuses on the preservation of digital collections within a library setting. A Digital Preservation Librarian manages and maintains digital repositories, develops preservation strategies for various digital formats, and works to ensure that these materials are discoverable and accessible to library users.",
                difference: "While similar to a Digital Archivist, this role is specifically situated in a library environment, with a focus on scholarly communication and user access. They may have a stronger emphasis on information literacy.",
                skills: "Knowledge of library cataloging systems, digital repository software, metadata standards, and an understanding of intellectual property and copyright law."
            },
            'Digital Curation Specialist': {
                description: "A Digital Curation Specialist is responsible for the entire lifecycle of digital assets, from creation to preservation and reuse. They manage, preserve, and add value to digital collections to make them reusable for future generations.",
                difference: "The term 'digital curation' emphasizes the active management and enhancement of data for current and future use. This role might be more involved in data modeling and preparing data for different research or public use cases.",
                skills: "Expertise in data management, knowledge of different data formats and their associated metadata, and an understanding of the research data lifecycle."
            },
            'Records Manager': {
                description: "A Records Manager is responsible for the lifecycle of an organization's records, from creation to final disposition. This includes managing both physical and digital records, ensuring compliance with legal and regulatory requirements.",
                difference: "This role is more focused on the administrative and legal aspects of information management within an organization. They are crucial for the initial stages of the digital preservation lifecycle.",
                skills: "Knowledge of records management principles and standards (e.g., ISO 15489), an understanding of legal and regulatory requirements for record-keeping, and experience with electronic records management systems."
            },
            'Digital Preservation Analyst/Technician': {
                description: "A Digital Preservation Analyst or Technician is a technically-focused role. They work to implement and maintain the technical infrastructure and processes for digital preservation, such as file format normalization and integrity checks.",
                difference: "This is a more specialized, technical role. They focus on the 'how' of digital preservation, working directly with software, scripts, and data, while other roles focus more on the 'what' and 'why.'",
                skills: "Strong technical skills in scripting (e.g., Python), command-line tools, and an understanding of operating systems and file systems. Experience with digital preservation software and digital forensics tools."
            },
            'Repository Manager/Administrator': {
                description: "This role is responsible for the management and maintenance of the digital repository system itself. The Repository Manager ensures the system is functional, secure, and meets the needs of the institution for long-term storage and access.",
                difference: "While other roles are users of the repository, the Repository Manager is the system administrator. Their focus is on the technical and operational health of the digital preservation system.",
                skills: "A mix of IT and information management skills. Experience with digital repository platforms, knowledge of database management, system administration, and security protocols."
            },
            'Metadata Specialist': {
                description: "A Metadata Specialist is a subject matter expert in the creation, management, and application of metadata for digital collections. They develop and implement metadata strategies to ensure that digital objects are well-described and discoverable.",
                difference: "This role is highly specialized. While other roles create metadata as part of their job, a Metadata Specialist focuses exclusively on the quality and consistency of that data, often working on complex projects.",
                skills: "Deep knowledge of metadata standards (e.g., MODS, EAD, PREMIS), controlled vocabularies, and linked data principles. Strong attention to detail and a methodical approach to data organization."
            },
            'Digital Asset Manager': {
                description: "A Digital Asset Manager is responsible for the overall management and organization of an organization's digital assets, often including marketing materials and media files. Their work is a key precursor to preservation.",
                difference: "This role is typically found in corporate or creative industries and is more focused on current operational use and distribution of digital content.",
                skills: "Experience with Digital Asset Management (DAM) systems, an understanding of workflows for creating and distributing digital content, and knowledge of file formats and rights management."
            },
            'Systems Administrator/Developer': {
                description: "In a large institution, a Systems Administrator or Developer may be part of the digital preservation team, providing technical expertise on a project basis. They build and maintain the IT infrastructure that supports the digital preservation program.",
                difference: "This is a pure IT role with a focus on the specific needs of digital preservation. They are not necessarily trained in archival or library science but are essential for the technical implementation of preservation strategies.",
                skills: "Expertise in programming languages (e.g., Python, Java), database management, server administration, and cloud computing. Knowledge of APIs and open-source technologies."
            },
            'Digital Preservation Project Manager': {
                description: "This role is responsible for the planning, execution, and completion of digital preservation projects. They coordinate the work of various team members to ensure that projects are delivered on time, within budget, and to the required quality.",
                difference: "This is a managerial role that focuses on the logistical and strategic aspects of digital preservation work. They don't perform the hands-on preservation tasks but are critical for making sure the work gets done effectively.",
                skills: "Strong project management skills, including the ability to create and manage project plans, budgets, and timelines. Excellent communication, leadership, and problem-solving abilities."
            }
        };

        let currentQuestionIndex = 0;
        let jobScores = {};

        const quizContainer = document.getElementById('quiz-container');
        const startButton = document.getElementById('start-button');
        const quizArea = document.getElementById('quiz-area');
        const resultArea = document.getElementById('result-area');
        const questionText = document.getElementById('question-text');
        const answerButtons = document.getElementById('answer-buttons');
        const resultTitle = document.getElementById('result-title');
        const resultDescription = document.getElementById('result-description');
        const resultDifference = document.getElementById('result-difference');
        const resultSkills = document.getElementById('result-skills');
        const restartButton = document.getElementById('restart-button');
        const otherOptionsList = document.getElementById('other-options-list');

        // Event Listeners
        startButton.addEventListener('click', startQuiz);
        restartButton.addEventListener('click', startQuiz);

        /**
         * Initializes the quiz, resetting scores and hiding results.
         */
        function startQuiz() {
            currentQuestionIndex = 0;
            // Initialize scores for all jobs to 0
            Object.keys(jobDetails).forEach(job => {
                jobScores[job] = 0;
            });

            // Hide the result area and show the quiz area
            resultArea.classList.add('hidden');
            quizArea.classList.remove('hidden');
            startButton.classList.add('hidden');
            
            showQuestion();
        }

        /**
         * Displays the current question and its answer buttons.
         */
        function showQuestion() {
            const currentQuestion = quizData[currentQuestionIndex];
            questionText.innerText = currentQuestion.question;
            answerButtons.innerHTML = ''; // Clear previous buttons

            currentQuestion.answers.forEach(answer => {
                const button = document.createElement('button');
                button.innerText = answer.text;
                button.classList.add('w-full', 'bg-gray-700', 'text-white', 'font-semibold', 'py-3', 'px-6', 'rounded-full', 'shadow-md', 'btn-answer');
                
                // Add event listener to handle answer selection
                button.addEventListener('click', () => selectAnswer(answer.scores));
                answerButtons.appendChild(button);
            });
        }

        /**
         * Processes the user's selected answer, updates scores, and moves to the next question.
         * @param {Object} scores The score object for the selected answer.
         */
        function selectAnswer(scores) {
            // Update the total scores for each job based on the selected answer
            for (const job in scores) {
                if (jobScores[job] !== undefined) {
                    jobScores[job] += scores[job];
                }
            }

            currentQuestionIndex++;
            if (currentQuestionIndex < quizData.length) {
                showQuestion();
            } else {
                showResult();
            }
        }

        /**
         * Calculates and displays the final result, including other options.
         */
        function showResult() {
            quizArea.classList.add('hidden');
            resultArea.classList.remove('hidden');
            
            // Find the job with the highest score
            let bestMatch = '';
            let maxScore = -1;

            for (const job in jobScores) {
                if (jobScores[job] > maxScore) {
                    maxScore = jobScores[job];
                    bestMatch = job;
                }
            }

            // Display the details for the best-matching job
            if (bestMatch && jobDetails[bestMatch]) {
                const details = jobDetails[bestMatch];
                resultTitle.innerText = bestMatch;
                resultDescription.innerText = details.description;
                resultDifference.innerText = details.difference;
                resultSkills.innerText = details.skills;
            } else {
                resultTitle.innerText = "No clear match found.";
                resultDescription.innerText = "Your interests align with many different aspects of digital preservation. Feel free to explore all the roles!";
                resultDifference.innerText = "";
                resultSkills.innerText = "";
            }

            // Display other possible matches
            otherOptionsList.innerHTML = ''; // Clear previous list
            const otherJobs = Object.keys(jobScores).filter(job => job !== bestMatch);
            
            // Sort other jobs by score in descending order
            otherJobs.sort((a, b) => jobScores[b] - jobScores[a]);

            otherJobs.forEach(job => {
                const listItem = document.createElement('li');
                listItem.classList.add('bg-gray-200', 'p-3', 'rounded-lg', 'shadow-sm', 'flex', 'justify-between', 'items-center');
                listItem.innerHTML = `
                    <span class="text-gray-800 font-semibold">${job}</span>
                    <span class="text-sm text-gray-500">Score: ${jobScores[job]}</span>
                `;
                otherOptionsList.appendChild(listItem);
            });
        }
    </script>
</body>
</html>
