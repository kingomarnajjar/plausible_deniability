![showandtell](/wot.png)

# Plausible Deniability

*"I have no idea how that got on my website, your honour!"* 👨‍⚖️

## What is this?

A tongue-in-cheek GitHub subdomain registration system that lets people submit their GitHub repositories to be hosted as subdomains on theradicalparty.com (e.g., `your-project.theradicalparty.com`). The name "Plausible Deniability" is just for fun - we promise this is (mostly) legal!

## How It Works

1. Users fill out a simple form with their GitHub repository information
2. The form creates a GitHub issue in this repository with all the details
3. Repository maintainers review the request and set up the subdomain
4. Users get their project hosted at `[subdomain].theradicalparty.com`

## Features

- **Anonymous Submissions**: Name and email are optional
- **Simple Validation**: We check GitHub URL and subdomain format
- **No Server-Side Code**: The entire process uses GitHub issues for tracking
- **Mildly Humorous Copy**: Because tech doesn't always have to be serious

## Setup Instructions

### For Repository Owners

1. Clone this repository
2. Update the GitHub repository path in `index.html` (search for "your-username/plausible-deniability")
3. Host the HTML file anywhere (GitHub Pages works great)
4. Set up your DNS to allow for wildcard subdomains on your domain
5. Create an automation system to deploy submitted repos to subdomains (optional)

### For Subdomain Requesters

1. Visit the form
2. Fill in your details (or don't - we respect your privacy)
3. Submit your GitHub repository link
4. Choose your desired subdomain
5. Describe your project 
6. Hit submit and complete the GitHub issue that opens
7. Wait for approval from the maintainers

## Rules

Your repository must:
- Be public (unless you've discovered time travel, then please DM us)
- Have a valid index.html file in the root or docs folder (we're not magicians)
- Not contain malicious code (we draw the line at mild mischief)

## Disclaimer

We are not responsible for any FBI raids, angry emails from your boss, or sudden career changes that may result from your submission. 😉

---

Created with ❤️ and a healthy dose of paranoia.

*Remember: "I was just testing the security" is always a valid excuse.*
