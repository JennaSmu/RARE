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
>>|[🐀 JR]({{< ref "Jumbo Rat\" >}})|Yes
>>
>>##### New Food:
>> |🚚 Food Delivery| 🍽️ Fed|
>> |---|---|
>>|[🟡WF]({{< ref "Whole food\" >}})|🐭|
>>|[🔪 Cut open]({{< ref "Cut open\" >}})|🐭|
>>|[✂️ Cut up]({{< ref "Cut up\" >}})|🐭|
>>|[🫱 HF]({{< ref "Handfed\" >}})|🐭

# Improperly Filled In:

> [!multi-column]+
>
>> [!Food]+
>>##### Yesterday's Food:
>> |🗑️ Leftovers| Removed?
>> |---|---|
>>|[🐀 JR]({{< ref "Jumbo Rat" >}})|Yes
>>
>>##### New Food:
>> |🚚 Food Delivery| 🍽️ Fed|
>> |---|---|
>>|[🟡WF]({{< ref "Whole food" >}})|🐭|
>>|[🔪 Cut open]({{< ref "Cut open" >}})|🐭|
>>|[✂️ Cut up]({{< ref "Cut up" >}})|🐭|
>>|[🫱 HF]({{< ref "Handfed" >}})|🐭

# What is the causing the difference?

Go ahead and click into the callouts to see the markdown and see if you can spot the difference.

> [!hint]-
> - In Markdown tables, the | character means that there is a new column. However, the | character is also used to denote aliases. To prevent the alias to be separated, you need to enter a \ character.
> - Entering the \ character before the | character means that that it will be properly formatted.
>
