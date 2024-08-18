# Google Drive Organizer

This Python script is designed to help you efficiently organize files in your Google Drive, including both your personal drive and shared company drives. It uses the Google Drive API to list and manage files and folders and integrates with the OpenAI API to provide intelligent suggestions for optimal file organization.

## Features

- **Google Drive Integration**: Access and list files from your personal Google Drive and any shared drives you have access to.
- **AI-Powered Suggestions**: Utilize OpenAI's GPT model to classify files and suggest appropriate folder placements or indicate when no move is needed.
- **Comprehensive Folder Retrieval**: Fetch and display the folder structure within shared drives.
- **Progress Tracking**: Real-time progress updates using the `tqdm` library.
- **CSV Export**: Save the classification results to a CSV file in your Google Drive.

## Getting Started

### Prerequisites

- A Google account with access to Google Drive.
- An OpenAI API key.

### Setup Instructions

1. Clone this repository or copy the script into your Google Colab environment.
2. Ensure you have your OpenAI API key available.
3. Install the necessary dependencies by running the provided commands.
4. Authenticate your Google account to access Google Drive.
5. Run the script to begin organizing your files.

### Running the Script

1. **Authentication**: Authenticate with your Google account when prompted.
2. **API Key**: Input your OpenAI API key to enable AI-powered suggestions.
3. **File Organization**: The script will analyze your files and provide organization suggestions.
4. **Review Results**: Classification results are saved as a CSV file in your Google Drive.

## User Interface

The user interface provides an interactive way to review and manage file organization suggestions. It includes a table of files with options to "Accept" or "Decline" each suggestion. Here’s a screenshot of the UI:

![Accept/Decline UI](https://github.com/TensorOpsAI/DriveAIOrganizer/blob/main/resources/Accept%20decline.png)

## Open with Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TensorOpsAI/DriveAIOrganizer/blob/main/Google_Drive_File_Organizer.ipynb)

## Contributing

We welcome contributions! Feel free to fork the repository, open issues, or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Google Colab](https://colab.research.google.com/) for providing a cloud-based Python environment.
- [OpenAI](https://openai.com/) for the powerful AI models used in this project.
