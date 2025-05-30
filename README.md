# komi-zyryan_literary_corpus
A corpus of 4214 preprocessed literary texts in the Komi-Zyrian language made as part of the project Spot the bot. Also includes SVD and CBoW embeddings trained on this corpus. The Python code is in the "komi-zyryan.ipynb" file.

A link to the Yandex cloud storage with embeddings and preprocessed texts: https://disk.yandex.ru/d/P41pG2iTCpfQbA. There:
* in "literary_komi-zyryan_corpus.csv" in column "text" are raw texts before lemmatization and in column "preprocessed" are preprocessed texts after lemmatization;
* "komi_fiction_text_corpus.txt" - txt file with preprocessed texts, each text on the new line;
* svd_dictionary.npy - SVD dictionary trained on preprocessed corpus texts;
* cbow_dictionary.npy - CBoW dictionary trained on preprocessed corpus texts;
* svd_dataset.npy - SVD 1grams dataset with embeddings;
* cbow_dataset.npy - CBoW 1grams dataset with embeddings.

**Texts source**: https://komikyv.org/

**Morphological analyzer utilized**: https://github.com/timarkh/uniparser-grammar-komi-zyrian
