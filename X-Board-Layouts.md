# X-Board Layouts

## Why different layouts are needed
The traditional QWERTY layout which is the base for almost all computer keyboards on the planet was created without ergonomy in mind.
For the use in different countries the language-specific were added (in disadvantage of other characters), but the main layout was mainly kept.
This led to rather clunky layouts that don’t really fit the needs for modern writing or programming.

So when talking about alternative and better keyboard types we have to take into account that there won’t be one layout that fits for all languages.
Each language has different frequencies for the occurrence of each letter. 
The same applies for bigrams which are combinations of frequently used combinations of two letters. 
And many languages use diacritics like “è”, “ä”, “æ” or “ł” which can’t all be added to a single layout (here even traditional keyboards use different layouts for different languages).

## How the different layouts are created
Instead of just using a single x-board layout we decided to optimize each supported layout (except the original 8pen layout which we keep for historical reasons) in terms of path length and flow.
For each language we used statistical methods to determine the frequency of each single letter.
This way we managed to placed the most frequently used letters on the inner layers while the less frequently used letters are placed on the outer layers.
We also switched letters inside a layer to optimize the flow for putting in the most common bigrams of the corresponding language.
