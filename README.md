# Lyrics Analyzer

## Description

This Python script counts the frequency of each word in a given text. It processes the text by converting it to lowercase and splitting it into words to calculate the occurrences of each word.

## Files

- `word_frequency_counter.py`: The Python script that performs word frequency counting.

## Installation

To use this script, ensure you have Python installed on your machine. This script does not require any additional libraries.

## Usage

1. **Download** the `word_frequency_counter.py` file to your local machine.

2. **Run** the script using Python.

   ```bash
   python word_frequency_counter.py
   ```

3. The script will output a dictionary where the keys are words and the values are their frequencies.

## Code

Here's the code for the word frequency counter:

```python
import string

text = """
Vinayak Damodar Savarkar, popularly known as Veer Savarkar, was a prominent Indian freedom fighter, poet, writer, and politician. Born on May 28, 1883, in Bhagur, a village near Nashik, Maharashtra, Savarkar played a significant role in the Indian independence movement.

Savarkar's political journey began during his student days in London, where he was deeply influenced by revolutionary ideas. He founded the Free India Society and was involved in organizing youth for India's independence struggle. His book "The First War of Indian Independence," written in 1909, provided a nationalist interpretation of the 1857 rebellion, which he termed as the first war for independence.

In 1909, Savarkar was arrested for his alleged involvement in a conspiracy against the British government, particularly for his role in the assassination of British official A.M.T. Jackson. He was sentenced to life imprisonment and transported to the Cellular Jail in the Andaman and Nicobar Islands, where he endured harsh conditions for nearly a decade.

Upon his release in 1924, Savarkar continued to be an influential figure in Indian politics. He became a leading advocate of Hindutva, an ideology seeking to define Indian culture in terms of Hindu values. His book "Hindutva: Who is a Hindu?" laid the foundation for the Hindu nationalist movement.

Savarkar was a controversial figure; while some praised him as a staunch patriot and a visionary, others criticized his extremist views and his alleged involvement in Mahatma Gandhi's assassination. Despite the controversies, Savarkar's contributions to the Indian independence movement and his literary works have left a lasting impact on Indian history.

He passed away on February 26, 1966, but his legacy continues to be a subject of debate and discussion in contemporary India.
"""

word_count = {}

for word in text.lower().split():
    word = word.strip(string.punctuation)
    if word in word_count:
        word_count[word] += 1
    else:
        word_count[word] = 1

print(word_count)
```

## Contact

For any questions or suggestions, please contact Nandan S - nandans123456321@gmail.com.

---

Feel free to adjust the sections or details as needed!
