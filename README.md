# japanese-toxic-dataset

ANLP2022 "Proposal and Evaluation of Japanese Toxicity Schema" provides a schema and dataset for toxicity in the Japanese language.

The repository is structured as follows:

- `schema_en.md`: Labeling schema.
- `data/subset.csv`: A subset of the dataset used in "Proposal and Evaluation of Japanese Toxicity Schema". Annotation details are described in `schema_en.md`.


## Dataset Details

`data/subset.csv` is composed of the following columns:

|Column Name|Description|
|:-|:----|
|id|Sentence ID|
|text|Sentence|
|Not Toxic|Toxicity Level: Not Toxic|
|Hard to Say|Toxicity Level: Hard to Say|
|Toxic|Toxicity Level: Toxic|
|Very Toxic|Toxicity Level: Very Toxic|
|category_卑語|Toxicity Category: Dignity|
|category_差別|Toxicity Category: Discrimination|
|category_迷惑行為|Toxicity Category: Harassment|
|category_猥褻|Toxicity Category: Obscenity|
|category_出会い・プライバシー侵害|Toxicity Category: Privacy|
|category_違法行為|Toxicity Category: Illegal|
|category_偏向表現|Toxicity Category: Bias|
|annotation_num|Number of Annotators|
