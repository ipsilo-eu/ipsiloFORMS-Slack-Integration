# ipsiloFORMS Slack Integration

A simple guide on how to set up our Slack integration for instant, urgent notifications.

---

## ⚙️ Setup Guide

Follow these steps to connect your form to a Slack channel:

### 1. Create the Slack Webhook

1. **Login** to your Slack workspace.
2. **Create a new channel.** (This is where you will receive your notifications.)
3. Access the Slack Apps management page: [api.slack.com/apps](https://api.slack.com/apps)
4. **Create a new app** by clicking the **Create New App** button and selecting the **From Scratch** option. Give your app a name and select the workspace it will be in.
5. In the **Features** section, click **Incoming Webhooks**.
6. **Activate** the Incoming Webhooks feature.
7. Click the **Add New Webhook to Workspace** button and select the channel you created in step 2.
8. **Copy the generated webhook URL.**

### 2. Connect to ipsiloFORMS

1. **Log in** to your [ipsiloFORMS Dashboard](https://ipsilo.eu/forms/f).
2. On the dashboard, go to your desired form and click the **Slack** button.
3. Paste the incoming webhook link into the field labeled **Slack Incoming Webhook URL**.
4. Click **Save Webhook**.

---

## ✨ How It Works

Your integration is complete!

* When a form response is submitted, the **ipsiloFORMS AI automatically checks** if the response requires immediate action.
* If the submission is **auto-flagged as urgent**, a message will be sent instantly to your selected Slack channel.
