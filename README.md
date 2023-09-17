# Final-Sprint

Graduation Project for Sprints' AI &amp; ML Course, Building a LLM (Large Language Model) from scratch.

Through said transformer, it is expcted to classify the data based on labels given to it to be either *toxic* or *non-toxic* (indicated by $1$ and $0$ respectively), as to which it will be a labourous task within a timeframe of $10$ days (Starting from $13/09/2023$ and due on $23/09/2023$).

## Tasks

Checklist to show what operations have and yet to happen on the data.

- [x] Load the data
- [x] Explore data:
  - [x] Read Inside.
  - [x] Overview the data.
  - [x] Explain what is to be done.
  - [x] Define Patterns to be replaced.
- [x] Cleaning:
  - [x] Collapsing `toxic` Derivatives.
  - [x] Dropping `id` and collapsed columns.
  - [x] Remove *Newlines*.
  - [x] Remove *Special Characters*.
  - [x] Remove *URLs*.
  - [x] Remove *IPs*.
- [x] NLP Preprocessing:
  - [x] Tokenization
  - [x] Removal of Stopwords.
  - [x] Lowercasing.
  - [x] Removing Non-English words.
  - [x] Lemmatisation/Stemming.

---

- [ ] Transformer:
  - [ ] Positional Encoding.
  - [ ] Multi-Head Attention.
  - [ ] Feed-Forward Neural Network.
  - [ ] Encoder Block:
    - [ ] Source Input.
    - [ ] Embed.
    - [ ] Normalize.
    - [ ] Feed-Forward.
  - [ ] Decoder Block:
    - [ ] Target Input.
    - [ ] Masking.
    - [ ] Normalise.
    - [ ] Cross-Head.
  - [ ] Combining Blocks.

---

- [x] Functional Modularity (Preprocessing Only):
  - [x] Binarize `toxic`.
  - [x] Basic Text Preprocessing:.
    - [x] Remove *Newlines*.
    - [x] Remove *Special Characters*.
    - [x] Remove *URLs*.
    - [x] Remove *IPs*.
  - [x] NLP Functions:
    - [x] Tokenization
    - [x] Stopword.
    - [x] Lowercase.
    - [x] Non-English.
    - [x] Lemmatise/Stem.
