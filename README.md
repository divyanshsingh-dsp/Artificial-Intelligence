Features:-

 Chat Interface – Conversational chatbot powered by Google’s Gemini API.
 Career Guidance – Provides insights into courses, exams, and Indian career paths.
 Career Quiz – Interactive multi-question quiz that suggests suitable careers.
 Chat History – Saved automatically in browser localStorage.
 Responsive Design – Built with Tailwind CSS for mobile and desktop users.
 Typing Effect – Simulated typewriter animation for a natural chatbot feel.
 Clear History Option – Erase all stored chats instantly.







Tech Stack:-

 	Frontend: HTML, CSS (TailwindCSS), JavaScript
 	AI Backend: Google Gemini 2.0 Flash API
 	Storage: Browser Local Storage







Installation & Setup:-

1.Clone this repository:
 	git clone https://github.com/yourusername/careerpath-ai.git
 		cd careerpath-ai

2.Open the project:
 	Just open the index.html file in your browser.

3.Run locally (optional):
 	You can use any live server extension (e.g., VS Code’s Live Server).







API Integration:-

The app uses Google Gemini API for responses.

If you want to use your own API key:
1.Get an API key from Google AI Studio → https://aistudio.google.com/
2.Replace the following line in the script:
 	const apiKey = "YOUR_API_KEY_HERE";
SORRY!! CANT PLACE MY API KEY

Note: Never expose real API keys in public repositories. Use environment variables or a backend proxy for production.







How It Works:-

1.The chatbot greets users and offers a “Take Career Quiz” option.

2.The quiz asks four questions about interests, skills, and goals.

3.Based on responses, it suggests career fields like:

 	Engineering / Data Science
 	Medicine / Psychology
 	Design / Fine Arts
 	Management / Entrepreneurship
 	Journalism / Law / Education

4.Users can continue chatting to get details about:

 	Entrance exams (JEE, NEET, UPSC, etc.)
 	Courses and colleges in India
 	Career guidance and skill development tips







File Structure:-

careerpath-ai/
│
├── index.html        # Main project file
├── README.md         # Documentation






Future Enhancements:-

Secure API key handling (via Node.js backend)
Save quiz analytics and user preferences
Multi-language support (English, Hindi, etc.)
Voice input/output integration





Author:-

Developed by: DIVYANSH SINGH PARMAR
💼 GitHub: divyanshsingh-dsp
📧 Email: divyanshsingh2875@gmail.com
