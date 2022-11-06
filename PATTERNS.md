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
| filebase     | Filebase Blockchain Object Storage |
| gcp          | Google's Cloud Storage             |
| ibm          | IBM Cloud Object Storage           |
| linode       | Linode Object Storage              |
| mailru       | Mail.ru Cloud Services (MCS)       |
| rackspace    | Rackspace Files                    |
| yandex       | Yandex Cloud                       |
| vultr        | Vultr Object Storage               |
| wasabi       | Wasabi Cloud Object Storage        |

# Search Patterns
These are what drives the search engine, they are entered in the "Setup" section
of the CSE control panel. Below you will find the patterns and their labels.
Any of them can be used in a Google search with the "site" operator - so for
example: "site:rackcdn.com".

|  Label       | Pattern                                    | Google Search       |
|--------------|--------------------------------------------|--------------------------------------------------------------------------------------------------------
| aws          | \*.s3.amazonaws.com/*                      | [site:s3.amazonaws.com](https://www.google.com/search?q=site%3As3.amazonaws.com)
| aws          | \*.s3-accelerate.amazonaws.com/*           | [site:s3-accelerate.amazonaws.com](https://www.google.com/search?q=site%3As3-accelerate.amazonaws.com)
| azure        | onedrive.live.com/*                        | [site:onedrive.live.com](https://www.google.com/search?q=site%3Aonedrive.live.com)
| azure        | \*.1drv.com/*                              | [site:1drv.com](https://www.google.com/search?q=site%3A1drv.com)
| azure        | \*.blob.core.windows.net/*                 | [site:blob.core.windows.net](https://www.google.com/search?q=site%3Ablob.core.windows.net)
| backblaze    | \*.backblazeb2.com/b2api/*                 | [site:backblazeb2.com/b2api/](https://www.google.com/search?q=site%3Abackblazeb2.com/b2api/)
| backblaze    | \*.backblazeb2.com/file/*                  | [site:backblazeb2.com/file/](https://www.google.com/search?q=site%3Abackblazeb2.com/file/)
| box          | \*.app.box.com/s/*                         | [site:app.box.com/s/](https://www.google.com/search?q=site%3Aapp.box.com/s/)
| box          | \*.app.box.com/v/*                         | [site:app.box.com/v/](https://www.google.com/search?q=site%3Aapp.box.com/v/)
| box          | \*.app.box.net/s/*                         | [site:app.box.net/s/](https://www.google.com/search?q=site%3Aapp.box.net/s/)
| cleverclud   | \*.cellar-c2.services.clever-cloud.com/*   | [site:cellar-c2.services.clever-cloud.com](https://www.google.com/search?q=site%3Acellar-c2.services.clever-cloud.com)
| cloudflare   | \*.r2.dev/*                                | [site:r2.dev](https://www.google.com/search?q=site%3Ar2.dev)
| digitalocean | \*.digitaloceanspaces.com/*                | [site:digitaloceanspaces.com](https://www.google.com/search?q=site%3Adigitaloceanspaces.com)
| dreamhost    | \*.objects.cdn.dream.io/*                  | [site:objects.cdn.dream.io](https://www.google.com/search?q=site%3Aobjects.cdn.dream.io)
| dreamhost    | \*.objects-us-east-1.dream.io/*            | [site:objects-us-east-1.dream.io](https://www.google.com/search?q=site%3Aobjects-us-east-1.dream.io)
| dreamhost    | \*.objects-us-west-1.dream.io/*            | [site:objects-us-west-1.dream.io](https://www.google.com/search?q=site%3Aobjects-us-west-1.dream.io)
| dropbox      | dropbox.com/s/*                            | [site:dropbox.com/s/](https://www.google.com/search?q=site%3Adropbox.com/s/)
| dropbox      | dropbox.com/sh/*                           | [site:dropbox.com/sh/](https://www.google.com/search?q=site%3Adropbox.com/sh/)
| dropbox      | dl.dropbox.com/*                           | [site:dl.dropbox.com](https://www.google.com/search?q=site%3Adl.dropbox.com)
| filebase     | \*.s3.filebase.com/*                       | [site:s3.filebase.com](https://www.google.com/search?q=site%3As3.filebase.com)
| gcp          | \*.storage.googleapis.com/*                | [site:storage.googleapis.com](https://www.google.com/search?q=site%3Astorage.googleapis.com)
| ibm          | \*.cloud-object-storage.appdomain.cloud/*  | [site:cloud-object-storage.appdomain.cloud](https://www.google.com/search?q=site%3Acloud-object-storage.appdomain.cloud)
| linode       | \*.us-east-1.linodeobjects.com/*           | [site:us-east-1.linodeobjects.com](https://www.google.com/search?q=site%3Aus-east-1.linodeobjects.com)
| mailru       | \*.hb.bizmrg.com/*                         | [site:hb.bizmrg.com](https://www.google.com/search?q=site%3Ahb.bizmrg.com)
| rackspace    | \*.clouddrive.com/*                        | [site:clouddrive.com](https://www.google.com/search?q=site%3Aclouddrive.com)
| rackspace    | \*.rackcdn.com/*                           | [site:rackcdn.com](https://www.google.com/search?q=site%3Arackcdn.com)
| yandex       | \*.storage.yandexcloud.net/*               | [site:storage.yandexcloud.net](https://www.google.com/search?q=site%3Astorage.yandexcloud.net)
| vultr        | \*.vultrobjects.com/*                      | [site:vultrobjects.com](https://www.google.com/search?q=site%3Avultrobjects.com)
| wasabi       | \*.s3.wasabisys.com/*                      | [site:s3.wasabisys.com](https://www.google.com/search?q=site%3As3.wasabisys.com)

# Feedback and changes
Feel free to use Github issues and pull requests to suggest changes or
provide feedback.
