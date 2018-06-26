# List of Labels / Refinements
These labels / refinements go under "Search features", "Refinements" section
in the CSE control panel and are used to label the actual patterns. They end up
being show as separate tabs in the UI.

| Name         |  Description                       |
|--------------|------------------------------------|
| aws          | Amazon's S3 service                |
| azure        | Azure Blob storage and OneDrive    |
| digitalocean | DigitalOcean Spaces                |
| dreamhost    | DreamHost objects                  |
| dropbox      | Dropbox downloads and shared files |
| gcp          | Google's Cloud Storage             |
| rackspace    | Rackspace Files                    |

# Search Patterns
These are what drives the search engine, they are entered in the "Setup" section
of the CSE control panel. Below you will find the patterns and their labels.
Any of them can be used in a Google search with the "site" operator - so for
example: "site:rackcdn.com".

|  Label       | Pattern                         |
|--------------|---------------------------------|
| aws          | \*.s3.amazonaws.com/*           |
| azure        | onedrive.live.com/*             |
| azure        | \*.1drv.com/*                   |
| azure        | \*.blob.core.windows.net/*      |
| digitalocean | \*.digitaloceanspaces.com/*     |
| dreamhost    | \*.objects.cdn.dream.io/*       |
| dreamhost    | \*.objects-us-west-1.dream.io/* |
| dropbox      | dropbox.com/s/*                 |
| dropbox      | dropbox.com/sh/*                |
| dropbox      | dl.dropbox.com/*                |
| gcp          | \*.storage.googleapis.com/*     |
| rackspace    | \*.rackcdn.com/*                |

# Feedback and changes
Feel free to use Github issues and pull requests to suggest changes or
provide feedback.
