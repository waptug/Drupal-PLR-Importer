### Overview
This module makes it easy to import large libraries of text articles into Drupal quickly by uploading a .zip file, automaticly uncompressing it and parsing the text into Article content nodes; categorizing with the name of the folder.  It also removes the need for article writers to know anything about how Drupal works to create content for publication.

### Audience

PLR Importer helps writers focus on creating great articles because it allows them to use the tool they are most familiar and not have to worry about learning how to write in Drupal. Writers will simply save their articles as a plain text document that follows a simple format as explained below:

The first line of the article is the title. The rest is the article content. Just plain text no with graphics or tables or anything but the article text.

After the writer is done, they save their article into a folder that has the name of the topic or category associated with it. Then they compress the folder which includes all the other files with a common topic/category into a zip file.

They can then upload that file using the PLR Importer module and it will automatically create the articles in Drupal and tag/categorize with the name of the folder.  This saves a bunch of time because the articles are processed all at the same time. The articles are displayed using the fonts and styles of the Drupal theme that provides a consistent look and feel. This also is a big time saver for blog editors who purchase PLR Article packs from PLR sites and get hundreds of articles at a time. They can instantly upload that folder into Drupal and it will create all the Article nodes.

If the site has workflows set up then the uploaded articles will be ready for the Publisher or Content Manager to review and make any final edits in Drupal prior to publishing them. This works great for community newspaper organizations and groups that have a team of content creators and don’t want to require them to all have to log in to the Drupal site just to edit an article. They can just email their articles as zip files to the Site Manager and they can then upload the zip files into Drupal. 

Future versions of this module will allow for importing and organizing different article formats including image, document, audio and video media types. You can also allow visitors to print out your content as PDFs for simple reading, printing and sharing.

### Technical details

This application converts .txt files into .csv files.
This application uploads a .zip file with a folder containing .txt files that have a known format of the following:

## Line 1 - Contains the title of the article.
## Line 2 to EOF - Contains the body of the article.

The goal of this application is to create a combined .csv file of all the article files in a folder so that it can be uploaded into Drupal and convert them to articles.

Work is in progress to meld various article formats which can be imported to match the various PLR library article formts one can find.

Work is being done to allow the direct import of the files into Drupal Article nodes and skip the conversion of the .txt file into .csv file that then would need to be manually uploaded via a csv importer module.

Different extensible format engines are being developed to allow a number of PLR formats to be imported and converted to Article nodes in Drupal.

This project will eventually allow uploading a nested folder structure of topical folder names which contain articles that would be tagged as the name of the folder for taxonomy and catagory classification.

Eventually the application will be released into the Drupal Marketplace for Modules and the WordPress Plugin Directory as well as from here in GitHub.

Concept Developer: Michael Scott McGinn
Lead Developer: Ed Reel

This project is looking for funding. Please visit https://givesendgo.com/plrimporter to help. Support does not only have to be monetary. You can help by sharing or praying for our success too.
This project is looking for more developers to collaborate on it as well. Feel free to clone this project and submit pull requests of your contributions.
