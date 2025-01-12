# Rhyme-Dictionary
A rhyming dictionary is a specialised dictionary where words that rhyme with each other are categorised together, often used when writing song lyrics and poetry. Due to the discrepancy between the phonologies of General American English (GenAm), Received Pronunciation (RP) and Standard Southern British English (SSBE), different sets of words rhyme with one another in each accent. Thus, different rhyming dictionaries are required for each accent. Currently, online rhyming dictionaries like Rhymezone.com and Wordhippo.com are often catered towards American English pronunciation or are inconsistent. Using Python to process the International Phonetic Alphabet (IPA) transcriptions of SSBE pronunciations from the Current British English (CUBE) pronunciation dictionary, we developed a rhyming dictionary based on SSBE and published it online via Streamlit. Our rhyming dictionary also contains certain features for users' convenience, such as an autocomplete feature for inputs, a toggle allowing the user to customise search results and formatting, downloads for search results, and additional details about the word.

By using Python to process the International Phonetic Alphabet (IPA) transcriptions of SSBE pronunciations from data we collected from the Current British English (CUBE) pronunciation dictionary, we aimed to develop a rhyming dictionary based on SSBE and published it online via Streamlit. Our rhyming dictionary contains certain features for the convenience of users, such as:

<li> An autocomplete feature that suggests possible words when the user enters a word, and no matches are found.</li>

<li>A toggle that allows the users to display the data as words (sorted by syllable count, with hyperlinks to dictionary or thesaurus entries) instead of a table view. Common words are bolded and highlighted in grey.</li>

<li>A toggle that allows the user to hide uncommon words (only available in word list view).</li>

<li>Options (in table view) to sort words by any column in ascending or descending order, download the table as a .csv file or search for specific results within the table that is built into Streamlit.</li>

<li>Additional details (in table view) like stressed/unstressed vowel patterns, syllable counts, and word frequency (web occurrence).</li>



A working link can be found here: https://ssbe-rhyming-dictionary.streamlit.app
