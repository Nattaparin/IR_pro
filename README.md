
- anime_data.pkl has the same information
like anime.csv but it has less size than csv file.
- ani_title.pkl and ani_synopsis are bm25 objects. 
They cannot be used like anime_data.pkl, such as
.iloc, to_markdown(), etc.
- title and synopsis in the anime_data.pkl are
lowercase.
