---
title: Half-Consonants and the Evolution of Cosyran
date: 2024-08-14T00:00:00+08:00
draft: false
toc: false
description: The first long article about Rikatisyï on this blog.
---
Over the course of the past two weeks, I've been revamping my conscript (writing system): *Isyaxé Kiryada*. While teaching the script to my friends, I realized that a fatal flaw with the script was that even after previous updates, it was unable to express certain consonant clusters, such as in the phrase *cosyran ka* (note that *c* is pronounced like *ch*, and *sy* is pronounced like *sh*). But why?
Why didn't I just design the script to support such a basic feature of the language to begin with?
{{< figure src="gospel.png" height="400" >}}
*My slave hard at work spreading the gospel.*

## The four stages of Rikatisyï
Rikatisyï was originally a submission to a ConJam (a competition where people compete to make languages around a certain theme), so I felt pretty oblidged to make a proto-language and evolve my main submission from that since that's what *basically* everyone did.
{{< figure src="rikaevo.png">}}
We're going to focus on the main four. Now, let's look at the **maximum syllable structure** for each of these languages:
{{< figure src="syllable struc.png">}}
Now, since Rikatisyï was initially made for the ConJam without 
anticipating the development of *Modern Rikatisyï* in the future, the script was made with the intention of only supporting the syllable structure of Standard Rikatisyï. Let's look at our initial example, *cosyran*:
{{< figure src="cosyran demo.png" width="400">}}
Now, I couldn't just slap the letters for *sy* and *r* and call it a day — the writing system was an **abugida**, which means that just writing a consonant presumes the vowel *a*, instead making the word *cosyaran*. Of course, this wasn't an issue for Standard Rikatisyï, where consonant clusters couldn't occur in the first place, but how about Modern? (also yes, that's a ligature for syï)

## Introducing the half-consonant
I decided to introduce conjunct forms of consonants — you may be familiar with this if you can write Devanagari. For instance, त + व = त्व. Luckily, I didn't need to introduce conjuncts for all consonants due to the limited types of clusters in the language.
- Final n and h already had diacritics thanks to Standard Rikatisyï.
- Consonant clusters involving *r* could be simplified to the cases where r came before or after the consonant.
- The remaining valid consonants that could be used in clusters were l, m, f and k.
- Newly introduced final consonants could be simply marked with a final :

An example of a half consonant:
{{< figure src="aldeva.png" width="200">}}
And now, the cosyran issue resolved:
{{< figure src="cosyran fixed.png" width="200">}}
## Wait, how did cosyïran even become cosyran?
It's time for a brief introduction into the way Rikatisyï evolved. If we go back to our previous languages, the word *cosyran* used to look like this:
{{< figure src="cosyran evo.png" width="300">}}
And one of the main reasons behind this change is one of my favourite phonological concepts to explain to people: palatalization. Simply put, that's when a consonant has a *y* (/j/) attached to it, and that eventually causes the consonant to shift as a whole.

This exists in English as well! Say the phrase "don't you" out loud casually. It often turns out as "don'tcha", doesn't it? The "ty" part becomes a "ch". How about "produce"? Do you say it as pro*dyus* or pro*jus*? The latter is the effect of palatalization. The same thing happened to our initial syllable *tyo* in Classical Rikatisyï. Over time, the consonant shifted from being pronounced as *ty* /tʰʲ/ to simply *ch* /t͡ɕʰ/.

How about the two-syllable *suhi* /su.hi/ becoming *syï* (/ɕy/, pronounced like shu)? This one was a multi-step process, first with the consonant *h* being lost. Historically, /h/-loss is extremely common across languages. For those of you who speak Spanish, note how words like *hoy* and *hambre* begin with *h*, yet it isn't pronounced. At one point, those h-s were being pronounced, but h is such a weak consonant (it's just exhaling) that it got lost over time, with its remnants existing in writing. This exists in English, too, in phrases like *should have*, where the h merges into the previous word, forming something like *should've* instead.

Now that the h has been lost, we're left with *sui* /sui/. At this stage, the diphthong monophthongizes (two vowels merging into one), with ui becoming ï (click [here](https://upload.wikimedia.org/wikipedia/commons/e/ea/Close_front_rounded_vowel.ogg) to listen to how it's pronounced). This vowels also ends up palatalizing the previous consonant, adding a y to it, forming *syï*. Palatalization continues further, and eventually, sy is pronounced *sh* (/ɕ/) — which is why /ɕ/ is spelled as sy!

## Dealing with *syr*
I managed to solve the issue of the syr cluster in writing, but now I face the issue of pronunciation; I have trouble *trilling* the r after the sy sound. As such, I'm currently considering reintroducing the -ï verb ending whenever -ran or -rö appears (as opposed to the -e- infix with -sran and -srö). The inflection table for the aspects will then become:
|  | Perfective | Imperfective | Continuative | Progressive
| --- | ----------- | ----------- | ----------- | ----------- |
| **Kawifduan** | cosyet | cosye | cosyesran | cosyesrö
| **Present** | cosyda | cosy | *cosyïran* | *cosyïrö*
| **Past** | cosyda | cosyde | cosyden | cosydö

On the other hand, the mood inflection table for the moods for the verb cosy would end up looking like:
| Mood | Verb |
| --- | ----------- |
| Active | cosy |
| Causative | cosyem |
| Hypothetical/Conditional | cosï |
| Passive | cosyá |
| Imperative | cosye |

In my next conlang-related post, I'll go over development of the four verb endings, and why the conditional depalatalizes from cosy- back to cos-! These posts also act as a good way for me to flesh out my conlang's history, so I'll probably keep writing these when inspiration strikes me.