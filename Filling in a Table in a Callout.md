---
aliases:
  - how-to-enter-information-in-a-table-in-a-callout
dg-publish: true
---

# Properly Filled In:

> [!multi-column]+
>
>> [!Food]+
>>##### Yesterday's Food:
>> |🗑️ Leftovers| Removed?
>> |---|---|
>>|[[Jumbo Rat\|🐀 JR]]|Yes
>>
>>##### New Food:
>> |🚚 Food Delivery| 🍽️ Fed|
>> |---|---|
>>|[[Whole food\|🟡WF]]|🐭|
>>|[[Cut open\|🔪 Cut open]]|🐭|
>>|[[Cut up\|✂️ Cut up]]|🐭|
>>|[[Handfed\|🫱 HF]]|🐭

# Improperly Filled In:

> [!multi-column]+
>
>> [!Food]+
>>##### Yesterday's Food:
>> |🗑️ Leftovers| Removed?
>> |---|---|
>>|[[Jumbo Rat|🐀 JR]]|Yes
>>
>>##### New Food:
>> |🚚 Food Delivery| 🍽️ Fed|
>> |---|---|
>>|[[Whole food|🟡WF]]|🐭|
>>|[[Cut open|🔪 Cut open]]|🐭|
>>|[[Cut up|✂️ Cut up]]|🐭|
>>|[[Handfed|🫱 HF]]|🐭

# What is the causing the difference?

Go ahead and click into the callouts to see the markdown and see if you can spot the difference.

> [!hint]-
> - In Markdown tables, the | character means that there is a new column. However, the | character is also used to denote aliases. To prevent the alias to be separated, you need to enter a \ character.
> - Entering the \ character before the | character means that that it will be properly formatted.
>
