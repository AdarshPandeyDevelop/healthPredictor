AI Doctor – Intelligent Web-Based Medical Diagnosis Assistant
Tech Stack: HTML, CSS, JavaScript, RESTful API Integration, CORS-enabled Server

AI Doctor is a browser-based intelligent health assistant designed to help users identify possible diseases based on the symptoms they enter. The project uses a third-party AI-powered medical API to analyze user input in real time and suggest relevant diagnoses, offering a quick and interactive way for individuals to explore potential health concerns before consulting a professional.

The system is built with a strong focus on frontend performance and responsive design, using HTML, CSS, and vanilla JavaScript. The UI was carefully crafted to be intuitive, user-friendly, and accessible across various screen sizes. It guides users through the process of entering symptoms and immediately fetches matching conditions using JavaScript’s Fetch API for asynchronous calls.

To overcome cross-origin restrictions during API communication, a CORS-enabled server was integrated between the frontend and the external medical API. This proxy server ensures secure and compliant data transfer while maintaining low latency for real-time results. The implementation handles various API response states (loading, success, failure) gracefully to improve reliability and user experience.

Key features include:

Live API integration for real-time medical condition prediction.

Error handling and validation for more accurate and stable inputs.

Dynamic DOM manipulation to show results without reloading the page.

Custom styling and layout using CSS for an approachable, professional look.

Modular, maintainable code structure suitable for future extensions.

Through this project, I gained hands-on experience with:

Asynchronous JavaScript (Promises and Fetch)

API consumption and CORS policy handling

Client-server communication

Frontend architecture and design principles

Translating user interaction into functional features

The project serves as a practical example of how AI and frontend web technologies can combine to create intelligent tools that are both helpful and engaging for everyday users. It opens the door for future enhancements like user login systems, symptom tracking history, AI model fine-tuning, voice-input integration, and data analytics for more comprehensive health support.

