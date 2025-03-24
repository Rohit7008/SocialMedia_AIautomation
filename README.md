# Social Media Automation

## Overview
This project automates social media content creation and posting using Google Sheets, OpenAI GPT, and various integrations. The automation is designed to streamline social media content generation and posting processes.

## Features
- **Google Sheets Integration**: Monitors specified cells for updates.
- **Data Extraction**: Fetches data from Google Sheets and processes it.
- **AI-Powered Content Generation**:
  - Uses OpenAI GPT-4 to generate post content.
  - Summarizes text data from sheets.
  - Extracts insights from URLs using AI.
  - Analyzes and describes images.
- **Social Media Post Formatting**:
  - Generates platform-specific posts for Facebook and LinkedIn.
  - Customizes content with emojis, hashtags, and URLs.
- **Automated Updates**:
  - Updates processed status in Google Sheets.
  - Stores AI-generated content back into the spreadsheet.

## Setup Instructions
### Prerequisites
- Python installed
- Google Sheets API access
- OpenAI API key
- Git for version control

### Installation
1. Clone this repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate into the project folder:
   ```sh
   cd social-media-automation
   ```
3. Install dependencies (if required):
   ```sh
   pip install -r requirements.txt
   ```

## Configuration
1. **Set Up Google API Credentials**
   - Create a Google Cloud project and enable Google Sheets API.
   - Generate a service account key and store the credentials JSON file.
   - Share the target Google Sheet with the service account email.

2. **Configure OpenAI API Key**
   - Sign up for OpenAI API and get an API key.
   - Store the key in an environment variable or a configuration file.

3. **Modify `config.json` (if applicable)**
   - Define spreadsheet ID, sheet name, and automation rules.

## Usage
- Ensure all credentials (Google API, OpenAI API) are correctly configured.
- Run the script to start monitoring Google Sheets and generating posts.
- Logs will be generated to track the automation process.
- View generated content in Google Sheets under specified columns.

## Contributing
Feel free to fork the repository and submit pull requests for improvements.

## License
This project is licensed under the MIT License.

