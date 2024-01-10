# Rock-Artist-Project

## Harmonizing History with Data: A Six-Year Analysis of Student-Selected Rock Artists

As a music historian and instructor for the History of Rock Music course at a community college in the Pacific Northwest, I have overseen the end-of-term rock artist biography assignment since 2018. This role has afforded me a unique vantage point to observe the trends in artist selection and genre preferences among students. From 2018 to 2023, a diverse group of 500 students, comprising 273 females, 198 males, and 29 of undetermined gender, have written biographies. These biographies not only reveal insights into their individual choices but also provide a broader perspective on patterns in artist popularity, gender preferences, and genre classification. In this analysis, I explore these elements in depth. 
 
They call him The King for a reason; the most popular artists selected were identified, with Elvis Presley being at the top of the list, approximately one out of every ten female students (36 students chose to write about Elvis, 29 female, 7 male). Elvis was chosen more than twice as often as the second-place artist, Freddie Mercury, at 17. 

Students showed a strong preference for writing about individual artists over bands, with a notable trend of choosing a band's lead singer rather than the band itself. This was evident in the fact that students were over three times as likely to write about an individual than a band (392 to 108), even if the individual gained fame as part of a band (for example, Kurt Cobain over Nirvana; Freddie Mercury over Queen; Jim Morrison over The Doors). Although it wasn't feasible to inquire why they made such choices, some educated guesses can be made - it simplifies the narrative to focus on one individual rather than the entire band, the frontman, often seen as more charismatic, represents the face of the band, and their voice is usually the most distinctive aspect of the band's music. This choice held across both genders of students.

Male and female students alike showed a tendency to choose North American artists, being about three times more likely to select them. This preference could stem from the larger number of North American artists available, attributed to the United States' significant population and consequently, its more extensive pool of artists.

For genre classification, I utilized the Spotify API, which provided a comprehensive genre dataset. However, it's worth noting that certain genres were excluded from our analysis. Genres like mellow gold, album rock, classic rock, rock, and pop were omitted. These were either too obscure or too general to yield meaningful insights for this study's objectives. Hard rock stood out as the dominant subgenre chosen by students, highlighting a notable trend in their musical preferences. What's particularly interesting is the remarkable consistency observed between male and female students — nine of the top 10 genres selected were identical across both groups. The analysis also highlighted Elvis Presley's significant influence, especially among female students. Spotify categorized his music as rock and roll and rockabilly. Excluding Elvis's works from the dataset shifted the female students' top 10 genre preferences, resulting in metal and psychedelic rock replacing rock and roll and rockabilly on the list.

A brief discussion about Spotify's genre classifications of artists is warranted. I found some of them to be problematic and chose to include genres in the analysis after much deliberation. Some of the genre labels were obscure (e.g. Mellow Gold), and the way artists were categorized into genres was often unexpected. A striking example was the classification of Dave Grohl, known predominantly for his roots in the grunge movement with Nirvana and later the Foo Fighters. Yet, Spotify listed him under 'alternative rock' and 'rock drums', conspicuously omitting 'grunge' or even 'post-grunge'. This inconsistency in genre classification is not unique to Spotify. Take John Mayer: allmusic.com lists his styles as Adult Alternative Pop/Rock, Alternative/Indie Rock, Contemporary Pop/Rock, and Contemporary Singer/Songwriter. In contrast, Wikipedia describes his music as rock, pop, and blues, whereas Spotify identifies him as neo-mellow and singer-songwriter.

These categorizations not only confuse but also challenge established ideas about musical genres. A notable example is the classification of Buddy Holly as 'classic rock' on Spotify. Holly's career predates what is commonly recognized as the classic rock period, which typically refers to music from the late 1960s and onwards. It questions the criteria and consistency of these genre assignments.

While the Spotify API was expected to offer a standard categorization, it fell short in capturing the multifaceted nature of artists' work. Grohl's absence from the grunge category was a testament to this limitation. This journey through Spotify's genre labyrinth not only challenged established notions but also revealed the subjective and evolving nature of musical genres. It underscored the complexity of categorizing art, where the lines are often blurred, and labels can sometimes do more to obscure than to define.

Spotify API information and necessary credentials can be obtained at https://developer.spotify.com/documentation/web-api

Unless indicated otherwise, data refers to all students, both male and female.

<img width="1171" alt="Screenshot 2024-01-02 at 12 50 28 AM" src="https://github.com/funkyguitar/Rock-Artist-Project/assets/104698553/df7d3e6f-4de0-4d5a-b231-e2a03fb86e53">
<img width="1166" alt="Top Ten Artists For Males:Females" src="https://github.com/funkyguitar/Rock-Artist-Project/assets/104698553/3a304211-5704-465b-bcef-4bcedb843045">
<img width="897" alt="Screenshot 2024-01-02 at 12 50 21 AM" src="https://github.com/funkyguitar/Rock-Artist-Project/assets/104698553/3319806f-1d48-4dce-bc57-284959878269">
<img width="1099" alt="Screenshot 2024-01-02 at 12 50 06 AM" src="https://github.com/funkyguitar/Rock-Artist-Project/assets/104698553/e9b4da42-f20d-4f19-942c-1438ee233e66">
<img width="1171" alt="Screenshot 2024-01-02 at 1 42 46 AM" src="https://github.com/funkyguitar/Rock-Artist-Project/assets/104698553/77bb45c2-807e-4d3c-9858-d954240b049f">
<img width="1168" alt="top 20 genres" src="https://github.com/funkyguitar/Rock-Artist-Project/assets/104698553/61181aa0-e858-4c3c-bb80-1f38ffbe9446">
<img width="1164" alt="Genres With Elvis:Without Elvis" src="https://github.com/funkyguitar/Rock-Artist-Project/assets/104698553/18316840-b590-4f14-b34f-117fe8dc3b47">

