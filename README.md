# WhatsApp Chat Analyzer

A tool to analyze and visualize statistics from exported WhatsApp chat logs! This project provides insights into WhatsApp conversations, such as message frequency, popular words, emoji usage, active days and months, and more.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Features

The WhatsApp Chat Analyzer provides the following analytics:

### Top Statistics
- **Total Messages**: The total count of messages exchanged.
- **Total Words**: The total word count across all messages.
- **Media Shared**: Count of media files shared, such as photos and videos.
- **Links Shared**: Count of links sent in the chat.

### Timeline Analysis
- **Monthly Timeline**: Message activity per month.
- **Daily Timeline**: Daily activity trends.

### Activity Maps
- **Most Busy Day**: Identifies the day of the week with the highest message count.
- **Most Busy Month**: Identifies the month with the highest activity.
- **Weekly Activity Map**: Shows activity distribution across days of the week.

### User Analysis
- **Most Busy Users**: Identifies users who contribute the most messages.
- **Wordcloud**: Visualizes the most common words in the chat.
- **Most Common Words**: Lists frequently used words.
- **Emoji Analysis**: Analysis of the emojis used in the chat.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Jainish-Prajapati/WhatsApp-Chat-Analyzer.git
   cd WhatsApp-Chat-Analyzer
2. **Install dependencies**: You can use pip to install the required packages. For a full list, see the Dependencies section.
    ```bash
    pip install -r requirements.txt
3. **Export WhatsApp Chat**: Export your WhatsApp chat from your phone without media, and save it in .txt format. Instructions for exporting chat:

    - Open the chat you want to export in WhatsApp.
    - Tap on options > Export chat > Without media.
    - Save the file and move it to the project directory.

## Usage

- Run the analyzer by executing the main script
    ```bash
    streamlit app.py

## Contributing

- Contributions are welcome! If you have suggestions or would like to improve this project, please fork the repository and create a pull request.

    - Fork the Project
    - Create your Feature Branch (git checkout -b feature/AmazingFeature)
    - Commit your Changes (git commit -m 'Add some AmazingFeature')
    - Push to the Branch (git push origin feature/AmazingFeature)
    - Open a Pull Request

## Acknowledgments

- This project was developed using a tutorial by [CampusX](https://github.com/campusx-official/). Many thanks for their helpful resources and guidance on building a WhatsApp Chat Analyzer.

## License

- Distributed under the MIT License. See LICENSE for more information.
