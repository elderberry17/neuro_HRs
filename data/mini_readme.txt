Here is an explaination of this repo files meanings:

Here is all the data we used and generate during the project

Firstly I got 76 messages from real HRs, clean them from emoji private information (changed it on the same patterns)

Then I trained on it, generate new datasets and calculated some metrcis:

1. Headings_wo_enoji -- is a source dataset I've cleaned from some extra information

2. GenerationPrefixes -- is a CSV-file I made from headings extracted from the source dataset

3. medium_gpt -- is an excel file with messages generated by medium_gpt model (the same with small_gpt.xlsx and unfinetuned_dungeon.xlsx files)

4. HR_metrics -- is an excel file with metrics I've calculated for original messages (the same with small_gpt_metrics.xlsx, medium_gpt_metrics.xls and unfinetuned_dungeon_metrics.xlsx files)

5. stop_words_ru -- is a txt file with a list of stop-words in russian language (it's not as volume as we'd like, but it's much better, than nothing, ha-ha) 

6. all_metrics -- is a merged excel file with metrics for every original and generated text

7. base_statistics -- is an excel file with some basic statistics for metrics I've calculated for original and generated texts
