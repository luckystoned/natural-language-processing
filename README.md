# Text Processing and Lexical Resources

## Regular Expressions
- **Standardized language** for defining text search patterns.
- **Python library**: `re` for regular expressions.
- **Rules for writing regular expressions**: Available on Wiki.
- **Structure of the `re.search()` Function**: Checks if a search pattern is contained in a string.

## Text Normalization
### Tokenization
- Subdivides a text string into minimal linguistic units (words).

### Lemmatization
- Finds the linguistic root of a word.
- **Stemming**: A simpler form of lemmatization.

## Measure of Lexical Richness
- Calculate the measure of lexical richness: the ratio of total unique words to total words in a text.

## Calculating Word Frequency
- Calculate the percentage of text occupied by a word.
- Count the occurrences of a word in a text.

## Language Statistics
- Perform basic statistical calculations on word frequency.
- Create a dictionary in Python where keys are words and values are word frequencies.

### Fine-Grained Content Filtering
- Frequent tokens may not be the most informative.
- Build frequency distributions excluding punctuation and special characters.

## Study of Long Words
- Build a list of tuples based on pre-calculated counts from frequency distributions.
