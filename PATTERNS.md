# List of Labels / Refinements
These labels / refinements go under "Search features", "Refinements" section
in the CSE control panel and are used to label the actual patterns. They end up
being show as separate tabs in the UI.

| Name         |  Description                       |
|--------------|------------------------------------|
| aws          | Amazon's S3 service                |
| azure        | Azure Blob storage and OneDrive    |
| backblaze    | Backblaze B2 Cloud Storage         |
| box          | Box.com shared links               |
| digitalocean | DigitalOcean Spaces                |
| dreamhost    | DreamHost objects                  |
| dropbox      | Dropbox downloads and shared files |
| gcp          | Google's Cloud Storage             |
| ibm          | IBM Cloud Object Storage           |
| linode       | Linode Object Storage              |
| rackspace    | Rackspace Files                    |
| wasabi       | Wasabi Cloud Object Storage        |

# Search Patterns
These are what drives the search engine, they are entered in the "Setup" section
of the CSE control panel. Below you will find the patterns and their labels.
Any of them can be used in a Google search with the "site" operator - so for
example: "site:rackcdn.com".

|  Label       | Pattern                                    |
|--------------|--------------------------------------------|
| aws          | \*.s3.amazonaws.com/*                      |
| azure        | onedrive.live.com/*                        |
| azure        | \*.1drv.com/*                              |
| azure        | \*.blob.core.windows.net/*                 |
| backblaze    | \*.backblazeb2.com/b2api/*                 |
| backblaze    | \*.backblazeb2.com/file/*                  |
| box          | \*.app.box.com/s/*                         |
| box          | \*.app.box.com/v/*                         |
| box          | \*.app.box.net/s/*                         |
| digitalocean | \*.digitaloceanspaces.com/*                |
| dreamhost    | \*.objects.cdn.dream.io/*                  |
| dreamhost    | \*.objects-us-east-1.dream.io/*            |
| dreamhost    | \*.objects-us-west-1.dream.io/*            |
| dropbox      | dropbox.com/s/*                            |
| dropbox      | dropbox.com/sh/*                           |
| dropbox      | dl.dropbox.com/*                           |
| gcp          | \*.storage.googleapis.com/*                |
| ibm          | \*.cloud-object-storage.appdomain.cloud/*  |
| linode       | \*.us-east-1.linodeobjects.com/*           |
| rackspace    | \*.clouddrive.com/*                        |
| rackspace    | \*.rackcdn.com/*                           |
| wasabi       | \*.s3.wasabisys.com/*                      |

# Feedback and changes
Feel free to use Github issues and pull requests to suggest changes or
provide feedback.
