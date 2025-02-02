# Git & Github Workshop Hands-On Exercise

Welcome to the **Git & Github Workshop Hands-On Exercise** repository! This project is designed to help participants practice using Git and GitHub by contributing to an open-source project.

## 📌 About This Project
This is a simple directory where attendees can add their name, role, and a short bio to a JSON file. The data will be displayed dynamically on a webpage.

## 🚀 How to Contribute
Follow these steps to add yourself to the Attendees Directory:

### 1️⃣ Fork the Repository
Click the **Fork** button at the top-right corner of this repository to create a copy in your own GitHub account.

### 2️⃣ Clone Your Forked Repository
Open your terminal and run:
```bash
 git clone https://github.com/`YOUR_GITHUB_USERNAME/git_github_hands_on.git
```
Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username.

### 3️⃣ Navigate to the Repository
```bash
cd git_github_hands_on
```

### 4️⃣ Add Yourself to `attendees.json`
Open `attendees.json` in a text editor and add your details in the following format:
```json
{
  "name": "Your Name",
  "role": "Your Role (e.g., Student, Developer)",
  "bio": "A short bio about yourself."
}
```
Make sure to keep the JSON format valid and place your entry inside the array.

### 5️⃣ Stage and Commit Your Changes
```bash
git add attendees.json
git commit -m "Added my name to the directory"
```

### 6️⃣ Push Your Changes to GitHub
```bash
git push origin main
```

### 7️⃣ Create a Pull Request
1. Go to your forked repository on GitHub.
2. Click on **New Pull Request**.
3. Select the base repository (this one) and compare it with your changes.
4. Click **Create Pull Request** and submit it!

### 8️⃣ Wait for Your Contribution to be Merged 🎉
We will review your pull request and merge it if everything looks good.

## 📂 Project Structure
```
attendees-directory/
│── index.html        # Webpage displaying the attendees
│── attendees.json    # JSON file containing attendees data
│── README.md         # Instructions on how to contribute
```

## 💡 Additional Notes
- Ensure your JSON syntax is correct to avoid errors.
- Contributions must follow the format given in `attendees.json`.
- Feel free to explore and contribute beyond this workshop!

---
Happy coding! 🚀
