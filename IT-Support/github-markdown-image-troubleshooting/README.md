# GitHub Markdown Image Troubleshooting

## Overview
While completing a GitHub lab for my CyberVisionaries Institute coursework, I encountered a problem embedding an uploaded image into a Markdown document.

Although the image uploaded successfully, GitHub Preview would not display it correctly. Instead of guessing, I documented each troubleshooting step, identified the root cause, and successfully resolved the issue.

This case study documents the troubleshooting process, the final solution, and the lessons learned.


## Environment

- **Device:** HP Chromebook x360 14-da0012dx
- **Operating System:** ChromeOS
- **Browser:** Google Chrome
- **Platform:** GitHub Web Interface
- **Language:** Markdown

- ## Objective

Successfully upload a diagram to GitHub and embed it into a Markdown document so that it displays correctly in GitHub Preview and after committing the changes.


## Initial Problem

The diagram uploaded successfully to my GitHub repository, but I could not get it to display correctly in my Markdown document.

Instead of showing the image in GitHub Preview, the page displayed the image URL as plain text or showed the Markdown example itself instead of rendering the image.


## Troubleshooting Process

### Step 1 – Verified the image was uploaded

The first step was to verify that the image had uploaded successfully to the GitHub repository. I confirmed that the file existed and could be opened, which ruled out a failed upload as the cause of the problem.

*(Screenshot will be added here later.)*

### Step 2 – Attempted to copy the image link

I followed the lab instructions and attempted to copy the image link so it could be inserted into the Markdown document.

While using GitHub on my Chromebook, I discovered that the menus and options were different from the instructions I was following. This required additional troubleshooting to determine the correct method.

*(Screenshot will be added here later.)*

### Step 3 – Adapted the instructions for ChromeOS

While following the lab instructions, I discovered that the options shown in GitHub on my HP Chromebook were different from the instructions I was given.

The instructions referred to selecting **"Copy link address,"** but on ChromeOS the available option was **"Copy image address"** after performing a two-finger tap (right-click) on the image.

After confirming that this was the Chromebook equivalent, I copied the image address and continued troubleshooting.

*(Screenshot will be added here later.)*

### Step 4 – Tested and corrected the image URL

After copying the image address, I pasted it into the Markdown image syntax.

While testing the link, I noticed that the copied URL ended with **`?raw=true`**. I removed that portion of the URL because it was not needed for the Markdown image reference and tested it again.

Even after correcting the URL, GitHub Preview still did not display the image. This confirmed that the image link itself was not the root cause of the problem, so I continued troubleshooting.

*(Screenshot will be added here later.)*

### Step 5 – Verified the link and investigated the Markdown formatting

To make sure the image URL was not the problem, I copied the address directly from the browser's address bar and tested it. This confirmed that the link itself was valid.

Since the URL was working correctly, I shifted my focus to the Markdown formatting. I noticed the "```" surrounding the example, so I researched what they were and found out the image syntax was being treated as code rather than rendered content.

After understanding what the triple backticks were doing, I removed them and adjusted the Markdown.

*(Screenshot will be added here later.)*

### Step 6 – Verified the solution

After removing the triple backticks and adjusting the Markdown, I previewed the document again.

This time, the image displayed correctly in GitHub Preview. I then committed the changes and verified that the image continued to display correctly after the commit.

This confirmed that the issue had been caused by the Markdown formatting rather than the image itself or the image URL.

*(Screenshot will be added here later.)*


## Result

The diagram rendered successfully in GitHub Preview and remained visible after the changes were committed.

By troubleshooting one possible cause at a time, I was able to identify the actual problem, apply the correct solution, and verify that the issue was fully resolved.

## Skills Demonstrated

- GitHub repository navigation
- Basic Markdown formatting
- Chromebook file management
- Troubleshooting and problem solving
- Root cause analysis
- Technical documentation
- Researching unfamiliar concepts
- Testing and verification

## Lessons Learned

- A valid image URL does not guarantee that an image will display correctly in Markdown.
- Different operating systems may use different terminology or menu options for the same task.
- Researching unfamiliar concepts can help identify the real cause of a problem.
- Testing one possible solution at a time makes troubleshooting more effective.
- Verifying that a solution works after making changes is just as important as finding the solution itself.
