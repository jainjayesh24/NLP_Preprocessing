# INSTRUCTIONS FOR NLP COMPETITION!

## Step 1

### Download the required data using the commands below. copy them in your vscode terminal after traversing to the required dest.

```bash
curl.exe -O https://raw.githubusercontent.com/Onaga08/scrape-and-sense/refs/heads/main/text_files/123.0.txt

curl.exe -O https://raw.githubusercontent.com/Onaga08/scrape-and-sense/refs/heads/main/text_files/12129.8.txt

curl.exe -O https://raw.githubusercontent.com/Onaga08/scrape-and-sense/refs/heads/main/text_files/11206.2.txt

curl.exe -O https://raw.githubusercontent.com/Onaga08/scrape-and-sense/refs/heads/main/text_files/10744.4.txt
```

## Step 2 You need to create your own dictionaries for Stop-Words, I can give you a dict of positive and negative words

```bash
curl.exe -O https://raw.githubusercontent.com/Onaga08/scrape-and-sense/refs/heads/main/Dict/positive-words.txt

curl.exe -O https://raw.githubusercontent.com/Onaga08/scrape-and-sense/refs/heads/main/Dict/negative-words.txt
```

## Step 3 Write a code to clean this data and generate the following 
### 1. positive score, 2. negative score, 3. avg sentence length, 4. percent of complex words, 5. fog index, 6. avg no. of words, 8. complex word count, 9. total word count, and 10. personal pronoun