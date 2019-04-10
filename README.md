yale-opensearch-extensions
==========================

Some search extensions for Yale-specific searching, made for OpenSearch (Fx/IE/Cr)

These were done with very little experience using OpenSearch, so there may be glaring inefficiencies or inelegancies about them. Please help improve them.


Add to Chrome
-------------

1. Paste the appropriate line below in your address bar, then type `javascript:` in front of it (Chrome strips out that part when you paste), then press enter.
1. In the popup, it's recommended to set a keyword


Add to Firefox
--------------

1. Open the Web Console (Tools => Web Developer => Web Console)
1. Paste the line in, then press enter.


Extension Installation Lines
-------

Yale Directory by Name
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/yale-opensearch-extensions/master/yale-directory-name.xml');`

Yale Directory by NetID
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/yale-opensearch-extensions/master/yale-directory.xml');`

Yale ITS Orgchart
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/yale-opensearch-extensions/master/yale-its-orgchart.xml');`

Yale Library Beinecke Digital Collections
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/yale-opensearch-extensions/master/yale-library-beinecke-digital.xml');`

Yale Library Eli Scholar
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/yale-opensearch-extensions/master/yale-library-eli-scholar.xml');`

Yale Service Now Global
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/yale-opensearch-extensions/master/yale-service-now-global.xml');`

Yale
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/yale-opensearch-extensions/master/yale.xml');`

Yale University Library Quicksearch
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/yale-opensearch-extensions/master/yale-university-quicksearch.xml');`

(NB: "New Orbis" is gone, and regular [Orbis](https://orbis.library.yale.edu/vwebv/) needs a rewritten extension)
