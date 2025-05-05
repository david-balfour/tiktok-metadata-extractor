# tiktok-metadata-extractor
A tool to extract metadata from TikTok videos for research purposes.

Instructions
1. Open a new incognito window in Chrome (CTRL + Shift + N)
2. Either visit a TikTok hashtag page (https://www.tiktok.com/tag/yourtag) or visit https://www.tiktok.com/ and search for a term
3. Open DevTools (F12) and go to the Network tab
4. In the DevTools search filter, type in item_list (if on a tag page) or full/?WebIdLastTime (if on a search page)
5. Hit F5 to refresh the page, and an item_list or full/?WebIdLastTime should appear
6. Scroll down to the bottom of the page, until it won't continue - you should see more items appearing on the right
7. Double-click on each item_list or full/?WebIdLastTime that appeared, to open it in a new tab
8. One at a time, copy the text in each of the new tabs (CTRL + A and CTRL + C) and paste it in to the box below (CTRL + V), hitting Enter to go to a new line after each one
9. Click on "Extract Metadata"!

Disclaimer: While we believe this tool is accurate and effective as of May 2025, it may cease to work or change in unexpected ways if TikTok update their platform. Also, we cannot guarantee that there are no unknown issues that will result in inaccurate data extraction, so if you use the tool, you are using it at your own risk.

This tool was made by David Balfour in the Behavioural GEMs lab at Flinders University. Please contact david.balfour@flinders.edu.au for feedback, help, and more information. If you use the tool, please reference it using the appropriate DOI.
