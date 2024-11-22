<h1 align="center">arch-user.name</h1>

<p align="center">arch-user.name is a service that allows people to get a free subdomain for their personal websites.</p>

<div align="center">
  <a href="https://discord.gg/AdnMpTK7TS"><img alt="Discord" src="https://invidget.switchblade.xyz/AdnMpTK7TS"></a>
</div>

## Register a Subdomain

**Currently, we only support GitHub Pages.**

### Set Up Your GitHub Pages Site

First, you’ll need to create your own GitHub Pages site. Use the [official GitHub Pages guide](https://docs.github.com/en/pages/getting-started-with-github-pages) to do that.

### Add the Domain Config File

1. **Fork this Repository**

   - First, navigate to the repository where you would like to add your subdomain.
   - Click the **Fork** button at the top-right to fork the register repository.

2. **Create the JSON File**

   - In your forked repository, locate the `domains` folder.
   - Click on **Add File** → **Create new file**.
   - Name your file like `<subdomain>.json`. Example: `balls.json`. Before choosing a subdomain, check the existing JSON files in the repo to make sure it’s not already in use.
   - In the file, paste the following:
```json
{
  "owner": {
    "username": "winbo-yml-exe"
  },
  "subdomain": "winbo",
  "record": {
    "CNAME": "winbo-yml-exe.github.io"
  }
}
```
     - Replace `your-subdomain` with your desired subdomain (like `balls` or `rizz`). Before choosing a subdomain, check the existing JSON files in the repo to make sure it’s not already in use.
     - Replace `your-github-website-url` with your actual GitHub Pages Website URL.

3. **Save the File**
   - After entering the information, click **Commit** to save your changes.

### Create a Pull Request (PR)

1. Navigate to the **Pull Requests** section of your forked repo.
2. Click on **New Pull Request**.
3. Ensure you are comparing your fork against the original repository (where you want to submit your changes).
4. Title your pull request like `Add <subdomain>.json`
5. Click **Create Pull Request**.

### Wait for Approval

After you submit the pull request, the service maintainers will review it. If everything appears to be in order, they will approve and merge your changes.

### After Your Pull Request Is Merged

Once your pull request is merged, you’ll need to add your subdomain to your GitHub Pages settings.

1. Go to your GitHub Pages repository (the one where your website is hosted).
2. Click on **Settings**.
3. Scroll down to the **Pages** section.
4. In the **Custom domain** field, enter your subdomain in this format: `subdomain.arch-user.name` (Example: `rizz.arch-user.name`).
5. **Do NOT** click the "Enforce HTTPS" option.
6. Save your changes.

### Your subdomain should now be linked to your GitHub Pages site! 🎉
