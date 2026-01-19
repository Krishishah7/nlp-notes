# Hindi Part-of-Speech (POS) Tagging

Hindi Part-of-Speech (POS) tagging is the process of assigning grammatical roles such as noun, verb, adjective, and auxiliary to words in a Hindi sentence.

Unlike English, Hindi requires language-specific trained models for accurate POS tagging.

---

## Why POS Tagging is Important

- Helps understand sentence structure
- Improves syntactic analysis
- Used in parsing and information extraction
- Important for downstream NLP tasks

---

## Tool Used: Stanza (Stanford NLP)

Stanza is an NLP library developed by Stanford that provides pretrained models for multiple languages, including Hindi.

It is used because:
- NLTK does not support Hindi POS tagging
- Hindi requires trained language models
- Stanza provides Universal POS tags

---

## NLP Pipeline for Hindi


Tokenization and POS tagging are handled internally by Stanza using trained Hindi language models.

---

## Universal POS Tags (UPOS)

Stanza uses Universal POS tags which are consistent across languages.

| Tag | Meaning |
|-----|---------|
| NOUN | Noun |
| VERB | Verb |
| ADJ | Adjective |
| AUX | Auxiliary Verb |
| ADP | Postposition |
| PUNCT | Punctuation |

---

## Example

Sentence:

Sample tagging:
- प्राकृतिक → ADJ  
- भाषा → NOUN  
- करता → VERB  
- है → AUX  

---

## Key Learnings

- POS tagging is language-dependent
- Correct NLP tools are required for Indian languages
- Stanza enables accurate Hindi POS tagging
- Universal POS tags simplify multilingual NLP

---

## Conclusion

Hindi POS tagging should always be performed using trained language models.
Using tools like Stanza ensures accurate and linguistically valid results.
