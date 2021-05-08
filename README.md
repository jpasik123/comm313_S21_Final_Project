## What can we learn about the evolution of country music from analyzing lyrics from the 1990s and 2010s by male and female artists? 

### Background 

When thinking about this final project, I knew I wanted to combine my passion for music with the text analysis skills I have gained from COMM 313. In the beginning planning stages, I asked myself various questions: What questions should I be asking? What would my research question be? What about my hypothesis? Taking these questions into account, I decided to focus on the country genre, not only because I am a big fan of country music myself, but also because there has been a lot of criticism and spectacle around how the genre has evolved over time. For example, some believe so-called old-school, traditional country music has lowly disappeared with the surfacing of young, bold artists bringing upbeat, pop edges to their work; others critique the evolution of country music, claiming the country genre has lost its elements of uniqueness by sounding too similar to other genres. This being said, I wanted to find - through lyric analysis - how exactly the genre has changed over the years? What could I find through text analysis that could tell me more about where the genre is headed in the future and what can be expected?

### Research Question

How has the country music genre changed over time – from the 1990s to 2010s? Are there any prevalent changes between men and women both within and between these decades? What evidence can I find through lyrical analysis that could tell me more about where the country genre is headed in the future? What can be expected?

### Hypothesis 

I hypothesize that while there may be diversity in topics over the decades, the lyrical analysis will reveal great similarity in lyrics from the 1990s and 2010s; I believe any substantial lyrical differences will be more prominent between male and female artists. 

### Organization 

To better organize the ideas I had for my final project, I wanted to narrow down by units of analysis; as a result, I decided to focus on country songs from the 1990s - a decade full of success and fame for the country genre - and the 2010s. I strategically chose these two time periods so that I could distinguish any lyrical differences between the old country of the 1990s and the modern country of the 2010s. I also chose to use gender as another variable for lyrical analysis so that I could see if, in addition to temporal distinctions, there were any differences in the song lyrics of female and male artists both between and within the decades. 

Relying on an Excel chart I created of top songs from the 1990s and 2010s by male and female artists, I transformed this chart into a Pandas data frame. As a data frame, I was then able to transform the rows of the data frame into separate dictionaries. I then relied on Genius API to scrape the lyrics for every song. After I pulled the lyrics, I further separated and organized my data into various JSON files. The main corpus that will be referenced in all data analysis folders is `all_charts`; `all_charts` pulls lyrics from a combined 80 songs (40 per decade; 20 songs per gender per decade).

### Analysis

Methods of analysis used in the project:

- Tokenization
- Frequencies
- N-gram Lists
- Word Comparisons
- KWIC Concordance Analysis: useful for contextualizing the use of a word and finding stark patterns/relationships
- Collocation Analysis 
- Keyness Analysis: very helpful in evaluating whether a certain word occurs more frequently in one corpus as compared to its occurrence in a relative corpus 
- Part-of-Speech Tagging 

### Notes

In my general presentation folder, you can look through both the code notebook used to collect, organize and build my corpus as well as the notebook that contains the detailed functions heavily used for my analysis. 

These folders I have referenced above that preface later analysis are: 

You can look within the `data_analysis` folder to find separate folders with detailed lyric analysis:

`functions` - a separate notebook of the various functions used as the foundation for analysis 

`building_and_organizing_corpus` - a notebook detailing the various steps taken to find, organize and upload the data needed for analysis  

`frequency_ngram_analysis` - a notebook containing frequencies, n-gram lists, and word comparison charts

`keyness_analysis.ipynb` - this notebooks contains keyness analysis that is used to evaluate whether a particular word occurs more frequently in one corpus  compared to its occurrence in another corpus

`kwic_collocation_analysis.ipynb` - notebook containing KWIC concordance and collocation analyses; helpful for both contextualizing how each word/lyric is used and finding patterns and relationships between tokens

`partofspeech_tagging_analysis.ipynb` - notebook that distinguishes the part of speech for each lyric and the frequencies in which they occur

Also, please don't forget to take a look at my blog post for a summary of my findings and some blocks of important code!

Enjoy!