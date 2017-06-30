- Navigate to [Google's Cloud Platform](https://console.cloud.google.com/home/dashboard?project=ayi-led){:target="_blank"} and ensure you are logged into you Google Account

- You need to create a new project to get started. If you have no existing projects then click on the **Create** button. If you have existing projects you can click on the **Select a project** drop down.

	![cloud console](images/1-cloud-console.png)

- If you clicked the drop-down, then you can  can click on the **+** symbol to create a new project.

	![name project](images/2-create-project.png)

- Give your project a name (it doesn't matter what you call it), and then click on **Create**.

	![name project](images/3-project-name.png)

- Check that your project appears in the drop down, as shown below.

	![dropdown](images/5-project-dropdown.png)

- If it doesn't then you can click on the drop down and then select **all** from the popup, to find and select your project.

	![select project](images/4-select-project.png)

- Now you need to click on the **API Manager**

	![api manager](images/6-api-manager.png)

- Then click on the **ENABLE API** link.

	![enable api](images/7-enable-api.png)

- Use the search box to find the **Google Assistant API**.

	![assistant api](images/8-assistant-api.png)

- Once you have selected the API, click on the **ENABLE** link.

	![enable assistant](images/9-assistant-enable.png)

- Now, click on the **Credentials** link in the side bar, to create some new credentials.

	![assistant credentials](images/10-assistant-credentials.png)

- Next you can create your credentials, selecting **OAuth client ID** from the drop down menu.

	![create credentials](images/11-create-credentials.png)

- You're now going to need to configure the consent screen.

	![configure consent](images/12-assistant-consent.png)

- You can type in your email address, and project name into the boxes and leave the other fields blank if you like. Then save the screen setup.

	![consent 2](images/13-assistant-consent2.png)

- On the main screen, you can now choose **Other** as your application type and give it any name you choose. Then click **Create**.

	![oauth2](images/14-assistant-oauth2.png)

- You should be presented with your **client ID** and **client secret**. You can just click on **OK** though, as you're going to just download a **json** file with these details in them.

	![secrets](images/15-assistant-secrets.png)

- Click on the **Download** icon to download your secrets to your computer, and you should be finished.

	![download secrets](images/16-assistant-download.png)
