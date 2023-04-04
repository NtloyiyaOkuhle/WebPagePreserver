# WebPagePreserver
This is a Python script that can be used to preserve web pages from a given website. The user needs to provide two arguments when running the script: the domain of the website to be preserved and the output directory where the preserved web pages will be saved.

The script first accesses the website and reads the HTML of the home page. It then searches for all links on the page and follows each link, recursively preserving all linked web pages. Each web page is saved as a separate file in the output directory, and the script logs the progress and any errors encountered during the preservation process.

To use the script, you can run it in a terminal or command prompt using the following format:



python script.py DOMAIN OUTPUT_DIR [-l LOG_FILE]

Where DOMAIN is the domain of the website to be preserved, OUTPUT_DIR is the output directory where the preserved web pages will be saved, and LOG_FILE (optional) is the path to a log file where the script's output will be written.

Once the script has completed running, you should be able to find the preserved web pages in the output directory you specified.
