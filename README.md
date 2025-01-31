# 🌟 Google Colab Repo for Automations 🌟

This repository contains scripts and notebooks for automating various tasks using Google Colab.

## 📑 Table of Contents
- [Installation](#installation)
- [Setup Google Search Console API](#setup-google-search-console-api)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🛠️ Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/KuyaMecky/Google-Colab-Repository-for-Automations.git
    cd google-colab-automations
    ```

2. **Install dependencies:**
    Open the `requirements.txt` file and install the necessary packages:
    ```sh
    pip install -r requirements.txt
    ```

## 🔧 Setup Google Search Console API

1. **Create a project in Google Cloud Console:**
    Go to [Google Cloud Console](https://console.cloud.google.com/) and create a new project.

2. **Enable the Google Search Console API:**
    Navigate to `APIs & Services > Library`, search for "Google Search Console API", and enable it.

3. **Create credentials:**
    Go to `APIs & Services > Credentials`, click on `Create Credentials`, and select `OAuth 2.0 Client IDs`. Follow the prompts to configure the consent screen and create the credentials.

4. **Download the credentials file:**
    Download the JSON file containing your credentials and save it as `credentials.json` in the root directory of this repository.
    ```sh
    mv path/to/downloaded/credentials.json /path/to/google-colab-automations/credentials.json
    ```

5. **Share access with your Google account:**
    Go to [Google Search Console](https://search.google.com/search-console/), select your property, and share access with the email address associated with your Google Cloud project.

## 🚀 Usage

1. **Open Google Colab:**
    Go to [Google Colab](https://colab.research.google.com/).

2. **Upload the notebook:**
    Click on `File > Upload notebook` and select the notebook from this repository.

3. **Run the notebook:**
    Follow the instructions within the notebook to execute the automation tasks.

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Create a pull request.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.