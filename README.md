# News-Feed-App
NewsFeed is a dynamic and responsive web application that provides users with the latest news and updates from various sources. This application offers an intuitive and seamless browsing experience.

# screenshot
## screen without search or filter
![screencapture-localhost-5174-News-Feed-App-2024-06-28-18_19_14](https://github.com/BasemYahia402/News-Feed-App/assets/123165852/027f60c4-1084-4b7d-8472-a5203d51b7ae)
## screen with search
![image](https://github.com/BasemYahia402/News-Feed-App/assets/123165852/b624f831-56e3-4058-abcb-c1be9b0714a9)



# Instructions for Setting Up Local Development Environment

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/BasemYahia402/News-Feed-App.git
   cd News-Feed-App
   
2. **Create .env File:**
- Duplicate the .env.example file provided in the root directory of the project.
- Rename the duplicated file to .env (it should be .env without any extension).

3. **Edit .env File:**

- Open the .env file in a text editor.
- Replace placeholders (VITE_NEWS_API_KEY="Put Your Api-Key") with actual values specific to your local environment.
- Ensure to populate all necessary environment variables required by the project.

4. **Environment Variables Explanation:**

- Review the .env.example file for explanations or comments (#) that describe each environment variable and what it represents.
- Modify each environment variable according to your specific setup or integration requirements.

5. **Security Note:**

- Do not commit or push your .env file to any public repository or share it publicly. This file may contain sensitive information such as API keys, passwords, or configuration details.

6. **Start the Project:**

- Once the .env file is properly configured, you can start the project:
   ```bash
   npm install  # Install dependencies
   npm run dev  # Start the development server

