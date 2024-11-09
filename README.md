Moderating Pictures Content: attended

Moderating images that are uploaded to social media websites (process images using the Google Cloud Vision API) and create a spreadsheet with its recommendations.

Using the image recognition cloud service (SafeSearch in the Google Cloud Vision API) to detect if any images being uploaded contains any explicit content.

Once a new image is uploaded, the bot reads the images and creates an Excel log with links to them.

It then loops through all the image entries in the spreadsheet and invokes SafeSearch (Google Cloud Vision API) to check the images.

The API returns an output/result: that the images contain adult, medical, violent, or racy content, and add this output to the same excel file next to their links.
