# ZenSign AI — Project Reflection

## What Worked Well
The ChromaDB knowledge base setup worked smoothly and semantic search 
returned relevant wellness practices based on user input. The Google 
Gemini integration with LangChain connected quickly and generated 
warm, personalized wellness plans for each zodiac sign.

## What Did Not Work and How I Handled It
The original plan used a Hugging Face BERT classifier for sentiment 
analysis, but the free API had limitations with casual wellness language. 
I switched to using Gemini directly for sentiment classification which 
produced better and more contextual results.

## Biggest Technical Challenge
Switching from the Anthropic Claude API to Google Gemini mid-build was 
the biggest challenge. Several LangChain imports and parameter names 
were different between the two providers. I resolved this by updating 
each code section one at a time and testing after each change.

## What I Would Build Next
With more time I would add a voice input feature so users could speak 
their check-in answers instead of typing. I would also expand the 
knowledge base to 500+ entries and add a feature that tracks the 
user's wellness progress over multiple sessions.
