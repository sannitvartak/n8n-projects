# LinkedIn Post Automation 🤖✨

Automate your LinkedIn content creation and posting with n8n! This workflow helps you generate, select, and publish engaging LinkedIn posts using AI, Google Sheets, and LinkedIn integration. Perfect for solopreneurs, agencies, and teams looking to scale their content with minimal effort.

---

## 🚀 Features

- 🗓️ Scheduled post generation and publishing
- 📄 Content ideas managed in Google Sheets
- 🤖 AI-powered topic selection and post writing
- 📝 Automatic post formatting with hooks, hashtags, and emojis
- ✅ Marks ideas as completed after posting

---

## 🛠️ How It Works

1. **Schedule Trigger**: Runs the workflow every 24 hours (customizable)
2. **Google Sheets Integration**: Reads pending content ideas and updates status
3. **AI Content Generation**: Selects the best idea, writes a LinkedIn post, adds hashtags and emojis
4. **LinkedIn Integration**: Publishes the post to your LinkedIn account
5. **Status Update**: Marks the posted idea as completed in Google Sheets

---

## 📦 Setup Instructions

1. **Clone this repo**
	```sh
	git clone https://github.com/<your-username>/n8n-projects.git
	```
2. **Import the workflow**
	- Open n8n
	- Go to Workflows > Import from File
	- Select `LinkedIn Post Automation.json`
3. **Configure credentials**
	- Google Sheets OAuth2
	- LinkedIn OAuth2
	- OpenRouter API (for AI)
4. **Customize Google Sheet**
	- Add your content ideas to the sheet
	- Update `documentId` and `sheetName` in the workflow
5. **Activate the workflow**

---

## 💡 Tips

- Use the Google Sheet to brainstorm and manage post ideas
- Adjust the schedule to fit your posting frequency
- Tweak the AI prompts for your brand voice

---

## 🤝 Contributing

Pull requests are welcome! Add new features, improve prompts, or share your automation tips.

---

## 📚 Resources

- [n8n Documentation](https://docs.n8n.io/)
- [LinkedIn API Docs](https://docs.microsoft.com/en-us/linkedin/)
- [Google Sheets API](https://developers.google.com/sheets/api)

