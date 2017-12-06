# Public Cloud Storage Search
This is a search engine for content shared publicly via cloud storage services,
built using [Google's Cloud Search Engine (CSE)](https://cse.google.com/cse/).
The tools allows searching across all content that is
indexed by Google and being served from cloud storage services such
as Amazon S3, Azure Blobs, etc.

# Purpose
The purpose of this tool is to aid security researchers who are doing open
source research.

# Disclaimer
The information that this tool reveals is being indexed by Google and not
being collected by this tool. If you want something to be removed,
please contact Google directly.

*** This tool is not affiliated with or endorsed by Google, all trademarks
remain property of their owners. Please use responsibly in accordance with
the applicable laws. We take no responsibility for your use of this tool. ***

# How it works
This tool uses Google's CSE to restrict searches against content being
served by the URLs known to be used by public cloud storage services.
It is essentially a search engine that is limited to a subet of sites. It is
build via a set of match patterns which are then imported into the CSE console
to build a working search engine. There are also some labels that allow users
to search specific cloud vendors. For more information, see [the official
CSE documentation](https://developers.google.com/custom-search/docs/overview).
While this tool is build using CSE, it can theoretically be rebuild any other
search engine tool that supports similar functionality.

A list of patterns can be found in [PATTERNS.md](PATTERNS.md) file.
A live version of the search engine is available [here](https://cse.google.com/cse/publicurl?cx=002972716746423218710:veac6ui3rio).

# Feedback
Please use Github issues and pull requests to provide suggestions and feedback.
For email contact, you can reach out to research@nightwatchcybersecurity.com.

# Wishlist
Some things we plan in the future:
   * Convert patterns to XML files so they can be imported/exported automatically
   * Add support for non-Google search engines
