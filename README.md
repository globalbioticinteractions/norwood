[![Build Status](https://travis-ci.com/globalbioticinteractions/pocock2012.svg)](https://travis-ci.com/globalbioticinteractions/pocock2012) [![GloBI](http://api.globalbioticinteractions.org/interaction.svg?accordingTo=globi:globalbioticinteractions/pocock2012)](http://globalbioticinteractions.org/?accordingTo=globi:globalbioticinteractions/pocock2012)

Configuration to help Global Biotic Interactions (GloBI, https://globalbioticinteractions.org) index: 

Pocock, Michael J. O.; Evans, Darren M.; Memmott, Jane (2012), Data from: The robustness and restoration of a network of ecological networks, Dryad, Dataset, https://doi.org/10.5061/dryad.3s36r118

This configuration was created by:

1. autogenerating a schema mapping using [Elton](https://github.com/globalbioticinteractions/elton) and command:
```shell
$ elton init --data-url "https://datadryad.org/stash/downloads/file_stream/40842" --data-citation "Pocock, Michael J. O.; Evans, Darren M.; Memmott, Jane (2012), Data from: The robustness and restoration of a network of ecological networks, Dryad, Dataset, https://doi.org/10.5061/dryad.3s36r118" globalbioticinteractions/pocock2012
```
2. editing the [globi.json](./globi.json) to customize the schema mapping
3. defining interaction types to be mapped and/or ignored in files [interaction_types_ignored.csv](./interaction_types_ignored.csv) and [interaction_types_mapping.csv](./interaction_types_mapping.csv)
4. review the resulting configuration as applied to the datasets by using:
```shell
$ elton review --type summary
reviewId	reviewDate	reviewer	namespace	reviewCommentType	reviewComment	archiveURI	referenceUrl	institutionCode	collectionCode	collectionId	catalogNumber	occurrenceId	sourceCitation	dataContext
c99c1df6-cfdd-4ccd-aceb-b0ced35f8c4b	2021-01-20T19:15:53Z	GloBI automated reviewer (elton-0.3.5-SNAPSHOT)	local	summary	file:///media/jorrit/data/globi/data/pocock2012/./									
c99c1df6-cfdd-4ccd-aceb-b0ced35f8c4b	2021-01-20T19:15:53Z	GloBI automated reviewer (elton-0.3.5-SNAPSHOT)	local	summary	1626 interaction(s)									
c99c1df6-cfdd-4ccd-aceb-b0ced35f8c4b	2021-01-20T19:15:53Z	GloBI automated reviewer (elton-0.3.5-SNAPSHOT)	local	summary	0 note(s)									
c99c1df6-cfdd-4ccd-aceb-b0ced35f8c4b	2021-01-20T19:15:53Z	GloBI automated reviewer (elton-0.3.5-SNAPSHOT)	local	summary	1734 info(s)	    
```
