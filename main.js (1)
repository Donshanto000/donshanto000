// Add an array of quotes that will be displayed on the website
const quotes = [
   " ❝ What we know is a drop. What we don’t know is an ocean❞ - Dark 🎥",
    " ❝Most people are nothing but pawns on a chessboard led by an unknown hand.❞",
    " ❝ Life is what happens when you're busy making other plans. - John Lennon ❞",
    
    " ❝ The greatest glory in living lies not in never falling, but in rising every time we fall.- Nelson Mandela ❞",
    " ❝ The only thing we have to fear is fear itself.- Franklin D. Roosevelt  ❞",
   " ❝You made me a, you made me a believer❞",
   
   " ❝ Everything is over  ❞",
   
   
        
       
   
    
    // Add more quotes as needed
];

const quoteElement = document.querySelector(".quote");
const replaceButton = document.querySelector(".replace-button");

function getRandomQuote() {
    const randomIndex = Math.floor(Math.random() * quotes.length);
    return quotes[randomIndex];
}

replaceButton.addEventListener("click", function () {
    const randomQuote = getRandomQuote();
    quoteElement.textContent = randomQuote;
});

// Initial quote on page load
quoteElement.textContent = getRandomQuote();
