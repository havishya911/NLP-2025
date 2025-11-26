FakeHeadline Rewriter
Complete 5-Stage Text Analysis & Headline Generation Pipeline

This project analyzes text, detects fake/sensational content, verifies facts, and rewrites clean and credible headlines using a structured 5-stage pipeline:

Pipeline Stages:-
1. Preprocessing

  -Removes unnecessary noise

  -URLs, Emails, HTML tags

  -Punctuation & Stopwords

  -Converts text to lowercase

  -Calculates word reduction %

2. Fake/Bias Detection

  -Sensationalism scoring

  -Fake-indicator & Credibility-indicator words

  -Caps-lock intensity

  -Excessive punctuation detection

  -Left/right political bias detection

  -Final fake probability score

3. Fact Verification

  -Extracts entities (names, dates, numbers, URLs)

  -Identifies claims

  -Matches known true/false facts

  -Source credibility detection (gov, edu, trusted domains)

  -Verifiability scoring

  -Verification status (Unverifiable → High)

4. Headline Rewriting

  -Automatically generates 5 rewritten headline candidates using:

  -Credible templates

  -Cautious templates

  -Neutral templates

  -Entity + Action word pairing

  -Ranking system (length, clarity, credibility, non-sensationalism)

  -Produces the top optimized headline for each record.

5. Final Output Generation

  -Creates a fully annotated summary:

  -Credibility label

  -Bias and Fake-risk label

  -Overall confidence score

  -Warning flags

  -Source references

-Quality tier (Poor / Fair / Good / Excellent)

-Final combined headline output
