<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Custom styles for the card flip */
        .card-container {
            perspective: 1000px;
        }
        .card {
            position: relative;
            transform-style: preserve-3d;
            transition: transform 0.6s, box-shadow 0.3s;
            cursor: pointer;
        }
        /* Add a hover effect for non-flipped cards */
        .card:not(.is-flipped):hover {
            transform: scale(1.03);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -4px rgba(0, 0, 0, 0.1);
        }
        .card.is-flipped {
            transform: rotateY(180deg);
        }
        .card-face {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
            -webkit-backface-visibility: hidden; /* Safari */
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
        }
        .card-face-front {
            background-color: #4f46e5; /* Indigo */
            color: white;
        }
        .card-face-back {
            background-color: #f3f4f6; /* Gray 100 */
            color: #1f2937; /* Gray 800 */
            transform: rotateY(180deg);
            padding: 1rem; /* Reduced padding for smaller cards */
            align-items: flex-start;
            text-align: left;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-900">

    <div class="container mx-auto p-4 sm:p-6 lg:p-8">
        <header class="text-center mb-8">
            <strong class="text-lg text-gray-600 max-w-3xl mx-auto">
                The case study demonstrated how a process model can reveal inefficiencies. What steps would you take to move from identifying issues to implementing solutions, especially if AI is being considered?
            </strong>
        </header>

        <!-- Grid for the cards -->
        <div id="answers-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-6 gap-4">
            <!-- Cards will be inserted here by JavaScript -->
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const answers = [
                { title: "Prioritise Issues", text: "Rank problems based on impact on process efficiency, customer satisfaction, and business goals." },
                { title: "Analyse Root Causes", text: "Conduct a root cause analysis to understand the underlying factors contributing to the problem." },
                { title: "Brainstorm Solutions", text: "Generate a range of possible solutions, including both AI and non-AI options. Consider the pros and cons." },
                { title: "Assess Feasibility", text: "Evaluate solutions based on time, cost, benefits, and alignment with organizational capabilities." },
                { title: "Develop a PoC", text: "For AI solutions, create a small-scale prototype or pilot to test the concept's viability (Proof of Concept)." },
                { title: "Gather Feedback", text: "Present proposed solutions to key stakeholders and incorporate their input." },
                { title: "Create a Plan", text: "Develop a detailed implementation plan with timelines, resources, and KPIs to measure success." },
                { title: "Secure Resources", text: "Obtain buy-in from leadership and secure the required budget and personnel." },
                { title: "Implement Solution", text: "Roll out the chosen solution, starting with a pilot if appropriate, and scaling up as needed." },
                { title: "Monitor & Evaluate", text: "Continuously track KPIs and gather feedback to assess the solution's effectiveness." },
                { title: "Iterate & Improve", text: "Based on evaluation results, make necessary adjustments and improvements to the solution." },
                { title: "Final Step", text: "This is a placeholder to even out the grid. You can add another step or remove this card." }
            ];

            const grid = document.getElementById('answers-grid');
            
            // This placeholder helps keep the grid even. You can remove it if you have an odd number of items.
            if (answers.length % 2 !== 0 && answers.length > 11) {
                 answers.pop();
            }


            answers.forEach((answer, index) => {
                // Create card elements
                const cardContainer = document.createElement('div');
                cardContainer.className = 'card-container h-52 rounded-lg';

                const card = document.createElement('div');
                card.className = 'card w-full h-full rounded-lg shadow-md';

                // Front of the card - now blank
                const cardFaceFront = document.createElement('div');
                cardFaceFront.className = 'card-face card-face-front rounded-lg';
                // The innerHTML is now empty to make the card front blank
                cardFaceFront.innerHTML = ``;

                // Back of the card
                const cardFaceBack = document.createElement('div');
                cardFaceBack.className = 'card-face card-face-back rounded-lg';
                cardFaceBack.innerHTML = `<h3 class="text-md font-bold text-indigo-600 mb-2">${answer.title}</h3><p class="text-sm">${answer.text}</p>`;

                // Assemble the card
                card.appendChild(cardFaceFront);
                card.appendChild(cardFaceBack);
                cardContainer.appendChild(card);
                grid.appendChild(cardContainer);

                // Add click event listener for the flip
                card.addEventListener('click', () => {
                    card.classList.toggle('is-flipped');
                });
            });
        });
    </script>

</body>
</html>
