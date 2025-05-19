Weather Notification Bot using n8n and Telegram

Overview:

This project is an automation workflow built using n8n that retrieves real-time weather data from the OpenWeatherMap API and sends it directly to a Telegram user via a bot. It demonstrates the integration of public APIs, automation platforms, and messaging systems for useful everyday applications.

The goal of the project is to show practical automation skills using free tools, and how such workflows can be applied in real-world use cases like alerts, notifications, or monitoring systems.

Tech Stack:

- n8n (workflow automation)
- OpenWeatherMap API
- Telegram Bot API
- Git and GitHub for version control

Workflow Description:

1. Start node: Triggers the workflow manually.
2. HTTP Request node: Connects to the OpenWeatherMap API and retrieves the current weather data for a specified city (e.g., Mumbai).
3. Telegram Node: Sends a customized weather update message to a Telegram user using a bot.

Each part uses basic authentication or API tokens set securely in n8n. The message content uses n8n’s built-in expression syntax to insert values like temperature, humidity, and weather description into the message.

Example Output:

Weather Update for Mumbai:

Temperature: 32°C  
Feels Like: 35°C  
Humidity: 60%  
Weather: clear sky

Have a great day.

Setup Instructions:

1. Clone this repository or download the workflow JSON file.
2. Open your n8n instance and import the workflow.
3. Set up your credentials:
   - OpenWeatherMap API Key
   - Telegram Bot Token (via BotFather)
   - Your Telegram Chat ID
4. Run the workflow manually or schedule it to run at regular intervals.

Learning Outcomes:

- Experience working with external APIs
- Understanding how to send dynamic messages using bots
- Practical usage of n8n for automation workflows
- Using environment variables or credentials in a secure manner

Use Cases:

- Daily weather updates sent to your phone
- Alerting systems for employees or users in specific locations
- Educational tool for learning automation and APIs

Author:

Ashley Mathias  
B.Tech CSE (AIML), IPS Academy Indore  
Interested in AI, automation, and real-world project development

LinkedIn: [https://linkedin.com/in/ashleymathia10](https://linkedin.com/in/ashleymathia10)  
GitHub: [https://github.com/AshleyMathias](https://github.com/AshleyMathias)
