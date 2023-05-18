# List GA4 Tags and Parameters
This Colab Notebook parses the Google Tag Manager JSON container export for GA4 tags, event parameters, and user properties and then saves them to a Google Sheet in a matrix format.

To use this notebook, you will need to manually export the desired container from GTM, select **Runtime** > **Run all**, open the **Choose Files** dialog when the first cell has run, upload your JSON file, and then finally log in to Google Drive when prompted.

A file will be saved to your Drive with the name *GTM GA4 Tags for container_id*.

Detailed documentation is inline in the notebook.

## Installation
This notebook uses some Google-specific Google Colab functions so it only runs in Colab.

To install this on Google Colab, 

1. Create an empty notebook
2. In the main menu, select **File** > **Upload Notebook** to open the upload dialog
3. In the upload dialog, switch to the **GitHub** tab
4. In the search box, paste the URL for this repository (https://github.com/CaretJuice/ga4-list-tags-params) and click on the search icon to populate matching notebook files
5. Click on the matching notebook and the code should load into your Colab notebook
