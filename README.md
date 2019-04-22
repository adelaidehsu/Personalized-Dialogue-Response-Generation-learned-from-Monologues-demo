## Project Introduction

Personalized responses are essential for having an informative and human-like conversation. 
Because it is difficult to collect a large amount of dialogues involved with specific speakers, it is desirable that a dialogue generation model can learn to generate personalized responses simply from monologues of individuals. 

In this work, we proposed a novel personalized dialogue generation method which reduces the training data requirement to dialogues without speaker information and monologues of every target speaker.

## Model Structure

![Image](/model-structure.jpg)

## Excerpted Sentence Examples

- Friends

**Input Message** | I saw him talking to her.
------------ | -------------
**(seq2seq)**| Have you even seen her?
**Monica** | I told her he was killed...
**Joey** | I told you to stop.
**Chandler** | I know what the truth is.
**Phoebe** | I just saw you, you know...
**Ross** | I told you.
**Rachel** | I'm sorry.

- The Big Bang Theory

**Input Message** | Do you like him?
------------ | -------------
**(seq2seq)**| No, just stop.
**Howard** | No, I'm sorry.
**Raj** | He's a good kid.
**Leonard** | No.
**Sheldon** | He's a really good friend.
**Penny** | He's a cool kid.
**Amy** | Yeah yeah I know.
**Bernadette** | He's my man.

- Mixture of multiple datasets
*(Trump's monologues, Starwar movie scripts, Friends, Clinton's monologues, singer/song-writer's lyrics)*

**Input Message** | Forget it, man. | Where are we now? | He's so cute.
------------ | ------------- | ------------- | -------------
**Trump**| You're the one who's got my daughter! | Out on this near town. | He's...he's not a great guy.
**Starwar** | I'm not sure. | We are on the east side. | He is not a man...
**Friends** | I'm not sure one would hurt. | We are on the street to *unk*, and we both know that we will play. | He's a bad guy.
**Clinton** | I'm sorry. I'm not sure what you mean. | We are here. | He's a good man, and he's my friend.
**Singer** | I don't know, I was just thinking about him. | We want to go into town. | He is so cute!


## Notes

This website is associated with the paper "Personalized Dialogue Response Generation Learned From Monologues" by Feng-Guang Su\* and Aliyah R. Hsu\* (*\* means equal contribution*). If you're interested in knowing more, please refer to the paper for more details.
