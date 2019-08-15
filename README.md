# 2019-08-swiss-abroad

### R-Script & data

The preprocessing and analysis of the data was conducted in the [R project for statistical computing](https://www.r-project.org/).

### GitHub

The code for the herein described process can also be freely downloaded from [https://github.com/koa87/2019-08-swiss-abroad](https://github.com/koa87/2019-08-swiss-abroad). 


### License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">2019-06-museums</span> von <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/koa87/2019-06-museums" property="cc:attributionName" rel="cc:attributionURL">swissinfo.ch</a> is licensed under <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)</a>.

### Disclaimer

The published information has been carefully compiled, but does not claim to be up-to-date, complete or correct. No liability is assumed for damages arising from the use of this script or the information drawn from it. This also applies to contents of third parties which are accessible via this offer.


### Original data source

### Data description `parl_swiss_abroad.csv`

| Attribute | Description |
| bill_id | Number of the bill|
| title_de | Title of the parliamentary affair in German|
| vote_id | id of the Vote|
| date | Date of the vote |
| parlyear | year of the vote|
| vote_subject| Subject of the vote|
| sign_yes| What a “yes” means in the vote |
| sign_no| What a “no” means in the vote |
| yes_votes| number of yes votes|
| no_votes| number of no votes|
| abstain_votes| number of abstain votes| 
| absent_votes| number of absent votes|
| votetype| type of the vote |
| position_ASO| position the ASO took |
| bill_type| Type of the bill|
| position_mp| position of the parliamentarian|


#### Database
 
Our original question was, which topics were relevant for the Swiss abroad and if the parliamentarians 
represented the interests of the Swiss abroad in the parliament. In response to this question, SWI swissinfo.ch, 
in collaboration with Smartvote, first collect all of the National Council's business in the ongoing legislation from 2015 up to and including the 2019 summer session. 

We looked for decisions that affect Swiss citizens living abroad. 
14 of the 16 chosen parliamentary affairs we chosen based on the agenda of the Organisation of the Swiss Abroad (ASO). 
The ASO is the political lobby of the Swiss abroad in Switzerland. Of course, not everything that 
the ASO advocates is in the interests of every single voter resident abroad. In Switzerland, however, 
there is a broad consensus that the organisation is the voice of the Swiss abroad within the country. 

What parliamentary affairs have we selected? 
We have selected five topics that we consider relevant and important for the Swiss abroad: 

1. access to a Swiss bank account on non-discriminatory terms,
2. introduction of e-voting,
3. popular initiatives in which the OSA has clearly positioned itself,
4. media services for foreign countries and
5. others. We have summarised the following topics under this heading: Data on the “Fifth Switzerland”, dual citizenship and supplementary benefits for returnees.

We have then selected all the relevant parliamentary affairs relating to the 2015-2019 legislature. 
The final list included 16 parliamentary transactions.
The original dataset compiled by Smartvote therefore includes all votes of the parliamentarians in 16 vote issues . 


#### Procedure
 

How did we proceed with the analysis? For all parliamentary affairs, 
we analysed  how the entire parliament and how the individual parliamentarians voted, 
as well as which position the ASO represented. Thus, swissinfo.ch was able to analyse 
the extent to which parties and parliamentarians were in agreement with the ASO position. 
We have calculated this for all transactions individually and broken it down by category.
