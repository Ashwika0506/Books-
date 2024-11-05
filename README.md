# Books-
📚 Literary Analysis Project

🎯 Project Overview

This project delves into an analysis of 64 classic literary texts, uncovering subtle patterns and similarities through an advanced text comparison algorithm. By examining connections across a diverse set of books, it offers unique insights into themes, language, and stylistic commonalities.

✨ Key Highlights

	
 •	 Extracts the 100 most impactful words within the text corpus
	•	Constructs a detailed 64x64 similarity matrix
	•	Identifies the top 10 most similar pairs of books
	•	Accurately processes and analyzes raw text data
	•	Leverages robust comparison algorithms for precise analysis

📊 Insights

The analysis yielded some intriguing relationships between the books, such as:


1.	Strong thematic and stylistic similarities between Volumes 3 and 4 of Gerard’s Herbal (91% match)
	2.	Consistent narrative elements across volumes of Memoirs of Laetitia Pilkington
	3.	Cohesive themes maintained throughout Foxe’s Book of Martyrs sections

🛠️ Technical Details

Core Components


 •	Custom Book class to efficiently handle text data
	•	Comprehensive text preprocessing pipeline
	•	Advanced similarity scoring algorithms
	•	Detailed word frequency analysis

Technology Stack

	
 •	Language: C++
	•	Data Format: Raw text files
	•	Methodology: Statistical text comparison and frequency analysis

📈 Performance Metrics

The program efficiently handles 64 books and performs:

	
 •	Frequency analysis on words across the entire corpus
	•	2,016 unique book-to-book similarity comparisons
	•	Ranking and selection of the top similar pairs

🚀 How to Use

	
 1.	Clone the project repository
	2.	Place all text files in the designated directory
	3.	Compile the C++ source code
	4.	Run the executable
	5.	Check the output files in the results directory

📝 Output Files

The program produces several output files:


 •	common_words.txt: Lists the top 100 frequent words across all books
	•	similarity_matrix.txt: Contains the full similarity matrix
	•	similar_books.txt: Shows the top 10 most similar pairs of books

🔍 Future Enhancements


	
 •	Integrate Natural Language Processing (NLP) techniques
	•	Add an interactive dashboard for visualization
	•	Expand to include semantic analysis
	•	Explore genre-based classification
	•	Support for multilingual analysis

💡 Technical Note

The current design is single-threaded for simplicity and reliability, which may slow down processing but ensures consistent, reproducible results across systems.

🤝 Acknowledgments

Thanks to:

	
 •	The professors for their support and guidance
	•	The open-source community for inspiration
	•	Project collaborators for their valuable contributions
