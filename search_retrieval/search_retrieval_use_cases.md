## Submission 1 - Keyword in context (KWIC) view of full-text search results
`As a:` user of the repository

`I want to:` do a keyword search for items that match my query and know where in the item that word appears

`So that:` the search results show the contextual placement of the word within the item or its metadata

`Done looks like:` I get a results list of items with a notation of where the keyword appears
	
## Submission 2 - Machine-readable text searching (full text)
`As a:` repository user

`I want to:` search the text of objects within the repository

`So that:` if my search term is contained within the text of an object within the repository, the result will be included in the set of relevant results

`Done looks like:` when I do a search, the result set includes all objects where the search term is included within the text of an object

## Submission 3 - Discoverable through OAI harvest (or other recognized standard) for integration with external systems such as discovery layers
`As a:` metadata professional

`I want to:` get standardized and appropriate information about what is available from the repository

`So that:` I can store that information for my own use or replicate it elsewhere

`Done look like:` I go to a URL and enter parameters to define appropriateness, and I receive a standardized machine-readable response with the information

## Submission 4 - Search based on metadata (author, title, subject, series, date, etc.) or facet
`As a:` repository user

`I want to:` perform searches on specified metadata fields

`So that:` I can limit the scope of my search to a single metadata field

`Done looks like:` the user interface includes a mechanism for selecting a field and performing a search on the content of just that field, and the results of the search only include results where the specified field of each record contains a relevant term

## Submission 5 - Search based on metadata (author, title, subject, series, date, etc.) or facet
`As a:` repository user

`I want to:` limit my search by a particular facet

`So that:` I can limit an existing search to include only results with a specified, existing heading

`Done looks like:` the user interface includes a list of the contents for a field, and a mechanism for selecting that field/content combination, so that, after selecting it, the results of a search only include results where that selection applies

## Submission 6 - Comprehensive keyword search against metadata \# Early Adopter \# Addressed

*Addressed with [155](https://github.com/uclibs/scholar_uc/issues/155)*

`As a:` repository user

`I want:` to use keyword searching to search every field in all the records

`So that:` I can find stuff related to the terms I'm searching for

`Done looks like:` A keyword search in a single search box searches all the fields in all the records in the repository

## Submission 7 - Comprehensive keyword search against metadata
`As a:` repository user

`I want:` to see more relevant results for my keyword search

`So that:` I can find things that are more meaningfully related to my search

`Done looks like:` A keyword search more prominently ranks results where my keyword is used more prominently compared to other records

## Submission 8 - Linked Data
`As a:` metadata specialist

`I want:` to use URIs in some fields of my record instead of text strings

`So that:` the metadata in my record is linked to authority records

`Done looks like:` I can paste URIs into any field on the metadata input form and the links will display in the user view of the bib record. The help section has lists of where I can find URIs.

##Submission 9 - Search and Display \# Early Adopter \# Addressed

*Addressed with [282](https://github.com/uclibs/scholar_uc/issues/282) - added other facets*

`As a:` repository submitter

`I want:` to filter my search results by subject, discipline, etc.

`So that:` I can easily navigate my search results and make them more meaningful

`Done looks like:` Subject faceting on side of screen (Metadata WG will need to discuss controlled vocabulary, tags, etc) 

##Submission 10 - Link Sharing \# Early Adopter \# Addressed

*Addressed with [287](https://github.com/uclibs/scholar_uc/issues/295) - We're displaying the link in the footer - and with [286](https://github.com/uclibs/scholar_uc/issues/286) - simplified the path to remove 'concerns'*

`As a:` repository user

`I want to:` know what the best link is for sharing with other people

`So that:` I can share a stable URL to other people

`Done looks like:` the work display page clearly shows the best link for the work

##Submission 11 - Result Sorting \# Early Adopter
`As a:` repository user

`I want to:` see how search results are being sorted

`So that:` I can better understand the results of my search

`Done looks like:` the search results include information on how results are sorted

<em>Relevancy ranking is too complicated for this to be actionable (2015-03-18)</em>

##Submission 12 - Created Field \# Early Adopter
`As a:` repository user

`I want to:` see what other works were created by the creator of a work

`So that:` I can find other works created by a user

`Done looks like:` the creator field on a work is links to a search for that author's works

##Submission 13 - Previewing content \# Early Adopter
`As a:` repository user

`I want to:` see content before downloading it

`So that:` I can evaluate or read content without downloading it

`Done looks like:` and embedded viewer displays the content in the work display page

##Submission 14 - Parsing search terms \# Early Adopter
`As a:` repository user

`I want to:` search terms to be parsed

`So that:` punctuation and other related forms are treated as 
white-space or stemmed as appropriate

`Done looks like:` when I search for a compound term, the parsed term is searched

##Submission 15 - Numerical search \# Early Adopter
`As a:` repository user

`I want to:` Numerical search terms to be searched

`So that:` I can search for meaningful numerical data, such as 
Latitude-Longitude geographic subjects

`Done looks like:` when I search for a numerical terms, results with matched are ranked as more relevant

##Submission 16 - Clustered search results \# Early Adopter
`As a:` repository user

`I want to:` subject results to be clustered

`So that:` results with semantically related subjects are grouped

`Done looks like:` when I search for subjects, results are grouped by related subjects

<em>Not actionable, pending further detail (2015-03-18)</em>

##Submission 17 - Search subject fields \# Early Adopter
`As a:` repository user

`I want to:` the search interface to search subject fields

`So that:` search will be improved

`Done looks like:` when I search in the repository, results with matching terms in the subject field are included in the result set

<em>Done! (2015-03-18)</em>

##Submission 18 - File rollback \# Early Adopter
`As a:` repository submitter

`I want to:` see information about file rollback

`So that:` I can understand what it means to rollback a file

`Done looks like:` help information is displayed to help me understand what a file rollback is

##Submission 19 - File size \# Early Adopter
`As a:` repository user

`I want to:` see how big files are

`So that:` I'll know how big a file is before I download it

`Done looks like:` The file size is displayed near the download button
	
##Submission 20 - Index file name/title \# Early Adopter
`As a:` repository user

`I want:` Scholar to index file names/file titles for keyword searching

`So that:` searching by the file name returns my work in the search results

`Done looks like:` I can search Scholar for my file name
