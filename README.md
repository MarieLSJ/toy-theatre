# Toy theatre dataset about its publishers, public collections, and the experiences of Victorians who engaged with it
**By Marie Léger-St-Jean**

Created in May 2020, published in September 2026

## Contents ##
The dataset contains three tables: “[Publishers](#publishers)”, “[Experiences](#experiences)”, and “[Public collections](#public-collections)”.

- They are available both:
  - individually as three comma-separated values (.csv) files; and 
  - combined in an [OpenDocument Spreadsheet (.ods) file](Toy_theatre.ods) which incorporates its own README tab.
- They are accompanied by:
  - my analysis of the “Experiences” sample, “[Toy theatre casting Victorian boys as theatre managers](MarieLSJ_-_2026_-_Toy_theatre_casting_Victorian_boys_as_theatre_managers.pdf)”; and
  - the [relevant excerpts](toy-theatre-experiences-without-open-access.md) for the five experiences recorded in A. E. Wilson's _Penny Plain, Twopence Coloured: A History of the Juvenile Drama_ (1932), for which there is no open-access digitization.

## Purpose
I put together this dataset when I was researching toy theatre in 2019 and 2020 for an article that was never published. I published it in September 2026 to enable Erica Haugtvedt to cite my analysis in her upcoming article on the same topic. I created the .ods and .csv files from a publicly accessible [Google Spreadsheet](https://docs.google.com/spreadsheets/d/1Ql4zEN1TKlWFV1XpKA2CcUiN1Gr9kJI_HTawMMcodwU/edit?usp=sharing).

- The first and last tabs, about _publishers_ and _public collections_, expand on previous work, respectively published on a website no longer available online and in two 20th-century books.
- The second tab contains my most original work, in which I collected a sample of 21 recorded Victorian _experiences_ of toy theatre in published articles and book chapters which have been digitized.

I researched the Victorians who had recorded these experiences to fill in the gaps of their narratives through biographical details. We now know when the experiences occurred as well as how old the subjects were both at the time and when they were reminiscing. I also analyzed the experiences described to start understanding how the Victorians who engaged in toy theatre conceived of their hobby.

## README
The rest of this introduction functions as the README file for the three .csv files:
- [toy-theatre-publishers.csv](toy-theatre-publishers.csv)
- [toy-theatre-experiences.csv](toy-theatre-experiences.csv)
- [toy-theatre-public-collections.csv](toy-theatre-public-collections.csv)

### Publishers
This table is an enriched version of the publishers timeline on _Hugo’s Toy Theatre Website_, created and maintained by Hugo Brown but no longer available online. The timeline contains 35 publishers and was probably based at least in part on Appendix A, "Publishers of the juvenile drama", in George Speaight's _Juvenile drama: The history of the English toy theatre_ (1946).

Hugo Brown did not update the timeline after putting it online in 2006 but continued conducting genealogical research up until 2010. He shared it in family trees for the principal publishers, which provide more exact life dates. The website, including the [timeline](https://web.archive.org/web/20230127051441/http://toytheatre.net/FT/Publishers.htm), is still accessible thanks to the Wayback Machine.

The first four columns of this table originate from Hugo Brown's timeline. I updated name and life span data with information found respectively in the British Book Trade Index (BBTI) and in Hugo Brown's family trees. I have added the last three columns to link each publisher to information available, when applicable, in:
- an (archived cached version of) his family tree;
- the [British Book Trade Index](https://bbti.grubstreetproject.net); or
- [Wikidata](https://www.wikidata.org).
	
**Columns**

`Publisher`	Name of the publisher or publishing company

`Relationships`	Relationship to other publishers in the table, when applicable

`Life Span`	Life dates of individual publishers, if known (sometimes approximative)

`Publishing`	Period during which the publisher actively published toy theatre sheets

`Hugo Brown family tree`	URL of the archived cached web page on _Hugo’s Toy Theatre Website_ dedicated to the genealogy of the publisher or his family, when applicable

`BBTI ID`	Identifier for the publisher in the British Book Trade Index, which covers people who worked in the English and Welsh book trades up to 1851 (consult by appending the identifier to the <https://bbti.grubstreetproject.net/details_trader.php?id=> URL)

`Wikidata` ID	Wikidata Q identifier for the publisher (consult by appending the Q identifier to the <https://www.wikidata.org/wiki/> URL), when application

### Experiences	
This table contains a sample of 21 Victorian experiences of toy theatre recorded in published articles and book chapters that I could access online.

To constitute the sample, I consulted the Appendix D, "Bibliography of the juvenile drama", in George Speaight's _Juvenile drama: The history of the English toy theatre_ (1946). I further used Google Books and the Internet Archive to find other recorded experiences by searching for occurrences of the titles of the most popular toy theatre publications, such as _The Miller and his Men_.

The 28 columns of this table can be grouped into four sections:

**[Subject](#subject) (5 cols)**       	Describes the person whose experience was recorded

**[Recorded experience](#recorded-experience) (3 cols)**       	Situates the recorded experience in time and quotes its most salient form(s) of engagement

**[Topic analysis](topic-analysis) (6 cols)**       	Indicates whether a topic was addressed or not in the recorded experience

**[Bibliographic reference](bibliographic-reference) (14 cols)**	Provides the detailed bibliographic reference of the published article or book chapter
	
#### Subject	
`First name`	First name of the subject

`Last name`	Last name of the subject

`Birth`	Year of birth of the subject, when known

`Death`	Year of birth of the subject, when known

`Wikidata` ID	Wikidata Q identifier for the subject (consult by appending the Q identifier to the <https://www.wikidata.org/wiki/> URL), when applicable
	
#### Recorded experience	
`Period`	Period during which the recorded experience took place, referring sometimes in square brackets to the the "Publishing" column of the ["Publishers" table](toy-theatre-publishers.csv)

`Age`	Age of the subject at the time of the recorded experience

`Forms of engagement`	Stand-out quotations from the recorded experience describing how the subject engaged with toy theatre
	
#### Topic analysis	
These six columns indicate with an "x" if a specific topic is mentioned in the recorded experience.

`Winter holidays`	The subject enjoys toy theatre in the winter holidays.

`Property / management`	The subject is the "proprietor" or "manager" of a toy theatre.

`Purchase`	The subject purchases toy theatre sheets.

`Tinselling or preparing cardboard`	The subject tinsels toy theatre sheets or colours and cuts them to be pasted on cardboard.

`Reading play`	The subject reads the book of words (script) for toy theatre.

`Stage performance`	The subject attends or puts on a toy theatre stage performance.
	
#### Bibliographic reference	
`Author`	Author of the recorded experience, as indicated on the publication

`Title`	Title of the publication

`Publication Year`	Year when the recorded experience was published

`Publication Type`	Type of publication (article or book chapter)

`Periodical Title`	Title of the periodical in which the publication appeared if it is an article

`Book Title`	Title of the book in which the publication appeared if it is a chapter

`Place`	Location where the periodical or book was published

`Publisher`	Publisher of the periodical or book (only the first if more than one)

`Date`	Issue, volume, or book publication date, in the `YYYY[-MM[-DD]]` format, depending on the level precision required to accurately represent the date

`Volume`	Volume number in which the publication appeared, in a periodical or a multi-volume book

`Issue`	Issue number in which the publication appeared, when applicable

`Pages`	Page range of the publication in the periodical or the book

`URL`	Freely accessible URL for the publication (in five cases, it refers to [toy-theatre-experiences-without-open-access.md](toy-theatre-experiences-without-open-access.md))

`Digital Archive`	Online archive which holds a digital surrogate of the publication (only the one from `URL` when there are more than one)

### Public collections	
This table lists 30 publicly accessible collections of toy theatre, as opposed to collections held in private hands.

The table expands on Appendix C in George Speaight's _Juvenile drama: The history of the English toy theatre_ (1946) by using Peter Baldwin's appendix "Public collections of toy theatres and prints" in _Toy theatres of the world_ (1992). I myself searched for an online presence for each of these collections and added:

- the Jack Butler Yeats Archive (Dublin);
- the William Appleton Collection (New York);
- the Rosalynde Stearne Puppet Collection (Montréal); and
- the Robertson Davies Collection (Kingston, Ontario).

**Columns**

`Institution`	Museum or library holding the collection

`Named collection`	Name of the collection, when applicable (usually the name of the private collector from whom the institution acquired the collection)

`City`	City where the institution is located

`Country`	Country where the institution is located

`URL`	URL linking to the specific named collection, or to the institution when there is no named collection (empty when I found no URL describing the collection)

`Speaight (1946)`	Brief description provided by George Speaight in his Appendix C in _Juvenile drama: The history of the English toy theatre_ (London: MacDonald & Co, 1946), p. 247-248. https://n2t.net/ark:13960/t32284g97.

`Baldwin (1992)`	Brief description provided by Peter Baldwin in his appendix "Public collections of toy theatres and prints" in _Toy theatres of the world_ (London: Zwemmer, 1992), p. 171. https://books.google.ca/books?id=9VeFAAAAIAAJ.
