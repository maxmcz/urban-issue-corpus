# urban-issue-corpus
A corpus of tweets about urban issues classified manually by human volunteers.


--
-- PostgreSQL database dump - Released data: Dublin, Ireland, 2015
--

Dumped from database version 9.2.2<br/>
Dumped by pg_dump version 9.3.5<br/>
Completed on 2016-09-09 09:45:25<br/>
Format: Plain SQL<br/>
Size: 403 tweets<br/>


--
-- Tables
--

<b>annotations</b><br/>
stores the human annotations concerning urban issue type and mentioned spatial location<br/><br/>

<b>spatial_contexts</b><br/>
the LoD classes for labeling mentioned locations<br/><br/>

<b>thematic_contexts</b><br/>
the issue type classes for labeling urban issues<br/><br/>

<b>tweets</b><br/>
the tweet dataset (excluding user info for privacy issues)<br/><br/>

<b>tweets_spatial_analysis</b><br/>
data for spatial analysis among geocoded, user home and mentioned locations from the tweets<br/><br/>
