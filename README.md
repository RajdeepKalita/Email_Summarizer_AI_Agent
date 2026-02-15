1. The "Agentic" Difference
Traditional email filters use "If/Then" rules (e.g., If sender is 'Bank', mark as 'Finance'). This project uses a ReAct Agent. It thinks: "The user asked for urgent updates. I see an email from Crio about a scholarship ending in 2 days. That is mathematically urgent. I will prioritize this at the top."

2. Privacy-First Summarization
The code connects directly from your machine to Gmail. It only sends the relevant text to Gemini for summarization, ensuring your full attachments and metadata stay local.

3. Human-Readable UI
Rather than returning JSON or raw text, the project uses the Rich library to create a "Command Center" feel in the terminal, complete with emojis, bold headers, and horizontal dividers for easy scanning.

4. Configuration
Open the script and update the following variables:

EMAIL_USER: Your Gmail address.

EMAIL_PASS: Your 16-character App Password (do not use your regular password).

GEMINI_API_KEY: Your API key from Google AI Studio.

5. Usage
Run the script to see your briefing:

📸 Example Output
The agent produces a structured Markdown response like this:

📬 Inbox Intelligence Brief
🔴 URGENT / ACTION REQUIRED
Anu (Crio.in): 📅 Deadline: 2 days left for the Scholarship application. Up to ₹1 lakh available.

🟡 FYI / UPDATES
Instahyre: Your profile was viewed by Oracle and MakeMyTrip.

🟢 NO ACTION / COMPLETED
Swiggy: Marketing promotion for weekend offers.

🤝 Contributing
Feel free to fork this project and add features like:

A ReplyTool to draft responses automatically.

Integration with Google Calendar to check availability.

Support for Outlook/Microsoft Graph API.

📜 License
This project is licensed under the MIT License.
