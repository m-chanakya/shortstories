
# README

	Created by Malireddy Chanakya & Srivenkata N Mounika Somisetty & Malireddy Chaitanya


## The dataset contains:

	- 200 short stories
	- 200 corresponding telegraphic summaries
	- 50 selected abstractive summaries
	- 50 selected extractive summaries each by SMMRY and RESOOMER
	- 45 MCQ questions for 15 stories (3 questions/story)
	- index.txt


### How to Use?

	index.txt contains a table listing out each:
    
		1.	story’s id
		2.	name
		3.	author
		4.	word count
		5.	length of the telegraphic summary
		6.	length of the abstractive summary

	Corresponding to each story an <id>.txt file is present in the stories directory, telegraphic directory and possibly in the abstractive directory


### Guidelines followed for telegraphic summaries:

	1. A segment is defined as a continuous span of words in the source, chosen as a part of the summary.
	2. A word should not be fragmented. Eg - if the word "breaking" appears in the source, the entire word should be a part of the segment and not fragments like "break".
	3. Each segment should be relevant to the plot, try to advance the story and have some continuity with the preceding and the following segment.
	4. Each segment extracted from a dialogue should be enclosed in quotes.
	5. Each segment extracted from parentheses should be enclosed in parentheses.
	6. Segments should be arranged in the same order as they appear in the story.
	7. The summary should be minimal. If multiple segments mean the same thing, pick the shortest. Adjectives, adverbs, and modifiers are not to be included if they are not 	relevant to the plot. Extraneous facts and long descriptions are to be ignored.
	8. When the segments are read in sequence the plot should be apparent and unambiguous.


### Guidelines followed for abstractive summarization:

	1. Summaries should be written from a third party perspective. Eg - "This story is about a girl..."
	2. Summaries should only discuss the plot and try to avoid inferences and opinions not immediately apparent from the story.
	3. Summaries should maintain the same order of events as they occur in the source text.