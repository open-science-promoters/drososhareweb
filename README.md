

# www.drososhare.net

Facilitating peer to peer eschange of transgenic fruit flies between lab, an open source project.

After the failure to create this via a closed source software and a company (Drososhare GmbH), we are here trying to re-apply the principes with an open source philosophy.

This project is related to the www.reagents.io project, which focus on data quality, and data export for manuscripts.



## The problems in fly sharing:

- Flies absent from stock centers are difficult to source and obtain.
- Specific combinations of transgenes are not accessible. Researchers are therefore reproducing them instead of ordering them.
- Fly providers spend too much time looking in their stock list, when asked for a specific line.
- There is no automation of the order system, a lot of unnecessary emails are sent back and forth to gatherr all the informations (addresses, correct names, additional information about the lines,...)



## Our solution pack (subject to change): 

Fed from my experience with Drososhare, I propose this development line, please feel welcome to comment, criticise and correct.

### free open source software (in develoment)

- request a specific fly lines: 
    - request is filled with Flybase nomenclature, and synonyms
    - request enter a specific database/website
    - request is forwarded to twitter, FLYslack and specific email addresses (obtained from flybase: correponding authors of last publication with that construct)

- automatic flystock cleaner:
    - uplaod list as a spreadsheet
    - read FB number
    - create new columns with flybase data
    - New entries can be made via importing the orders to stock centers

- fly stock list sharing:
     - stock list sent to an open database
     - each entry gets a random id
     - the correspondance of this id and information about the lab is sent to a secured database [1].
     - request can be sent automatically to the lab if their is a hit.
- Flybase integration
    - clean entries in the open database are incorporated in flybase for one-click ordering
     

[1] Who should control and have access to this database should be discussed. Potential candidates are flybase, BDRC, or a third party company.

## Additional, manual (not free) services

(can be carried out by free-lance data managers or students)

- manual search for the lines
- stock list cleansing


## Wanna help? We are welcoming any volunteer

See the [contributing documentation](contributing.md) for information on how to
contribute. There is also the [roadmap](roadmap.md) for an overview of the goals 
and timelines. Please note that this project is released with a 
[Contributor Code of Conduct](CONDUCT.md). By participating in this project you
agree to abide by its terms.



## The current team

- Julien Colomb, biologist, fruit fly expert, intermediate R coder, https://orcid.org/0000-0002-3127-5520



## License

Since part of the project will be software, the MIT liscence was used for the repo. The content of the data folder is under a CC0 1.0 license.
