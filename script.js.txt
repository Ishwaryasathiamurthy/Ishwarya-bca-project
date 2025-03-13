function toggleAnswer(questionNumber) {
            // Toggle the answer visibility when a question is clicked
            var answer = document.getElementById("answer" + questionNumber);
            if (answer.style.display === "none" || answer.style.display === "") {
                answer.style.display = "block"; // Show answer
            } else {
                answer.style.display = "none"; // Hide answer
            }
        }