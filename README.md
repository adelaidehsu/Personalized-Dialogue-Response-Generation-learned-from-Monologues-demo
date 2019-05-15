## Project Introduction

Personalized responses are essential for having an informative and human-like conversation. 
Because it is difficult to collect a large amount of dialogues involved with specific speakers, it is desirable that a dialogue generation model can learn to generate personalized responses simply from monologues of individuals. 

In this work, we proposed a novel personalized dialogue generation method which reduces the training data requirement to dialogues without speaker information and monologues of every target speaker.

## Model Structure

![Image](/model-structure.jpg)

## Generated Sentence Examples

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

**Input Message** | You have got to listen.
------------ | -------------
**(seq2seq)**| No! It's my plan!
**Monica** | Listening.
**Joey** | What's wrong?
**Chandler** | You listen to me!
**Phoebe** | You'll understand.
**Ross** | Listen to me.
**Rachel** | What are you doing here?

**Input Message** | We don't need the price tag.
------------ | -------------
**(seq2seq)**| The most of the hat is not true.
**Monica** | I don't think so.
**Joey** | I don't know.
**Chandler** | I know that.
**Phoebe** | I don't need that.
**Ross** | I don't care.
**Rachel** | I don't care.

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

**Input Message** | Want some coffee now?
------------ | -------------
**(seq2seq)**| Let's go.
**Howard** | Let's go.
**Raj** | Yeah.
**Leonard** | Come here, please.
**Sheldon** | No.
**Penny** | No, no, no, no...
**Amy** | Come on, I'm going to sleep.
**Bernadette** | Come on!

**Input Message** | I think we should tell her.
------------ | -------------
**(seq2seq)**| Okay. Well, I'll see the picture.
**Howard** | I think I'm going to tell her that.
**Raj** | I don't want to...
**Leonard** | No!!
**Sheldon** | I know!
**Penny** | But I don't know her.
**Amy** | I don't know...
**Bernadette** | I swear it'll be over.

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

This website is associated with the paper "Personalized Dialogue Response Generation Learned From Monologues" by Feng-Guang Su\* and Aliyah R. Hsu\* (*\* indicates equal contribution*). If you're interested in knowing more, please refer to the paper for more details.
