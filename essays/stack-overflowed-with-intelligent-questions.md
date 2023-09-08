---
layout: essay
type: essay
title: "Stack Overflow(ed) with Intelligent Questions?"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Smart Questions
  - Software Engineering
  - Stack Overflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/rtfm.png">

## A Question Can Be ... Smart?

Asking questions is much like using a calculator… it is only as smart as its user. One can have the fanciest _TI-Nspire CAS II _engineering calculator, but it will only be able to perform its enhanced functions if the user knows how to use and implement them. I believe that inquiries occur and behave much in the same manner. The way in which a question is asked will decide how the output (its answer) performs. 

In general, asking questions can be difficult, yet rewarding. It’s not only one of the most fundamentally key aspects to one’s learning, but it is also an important skill to have in order to expand in the knowledge of a particular subject. By seeking help from others, one is able to view the otherwise confusing concepts from a new or fresh perspective. It is this component of collaboration that enables deeper levels of thinking and comprehension of the material. In order to get to such an extensive level, however, one must be able to “ask” their way there through smarter questions. 

## The Basics of Smart Questions

**How To Ask Questions the Smart Way** by Eric Steve Raymond describes how to generate questions that are more impactful and significant, especially within the tech community. The following summarizes the basic principles and foundations of developing “smart” questions.
Smart questions:
* Are specific, thought-provoking questions: There is generally no straightforward answer. The answer requires some deep critical thinking and profound thought. This helps the community to engage with each other and view topics from multiple approaches via everyone’s unique perspectives.
* Shows willingness to learn: The question portrays that the user has tried multiple methods and overall contributes to the development of the learning community.
* Shows effort in doing previous searching: One can’t find a direct answer from a quick Google search
* Asks for guidance to lean in the right direction: The question does not demand for a solution to the answer, but perhaps rather implies for some suggestive tips to point in the right direction toward the answer. This can possibly include asking for a conceptual explanation of how the error occurred.
* Can simply be identified or narrowed down. The question identifies a distinct, explicit problem, so that the reader can understand what actual error is. It is not too open-ended or generalized, but it can be if the question relates to material on a conceptual level.
* Is not too specific and provides sufficient context: There is enough context for others to realize how an error occurred. This mainly involves including specific descriptions of the technologies that were used. The question can be based on a personal encounter, but should also be more generalized, so that others can find the question helpful when encountering a similar situation.

## Why Does It Matter?

To put it simply, smart questions matter because it saves time. In the fast-paced environment that we live in today, the concept of time has been highly valued as something that is precious in our daily lives. Society is hyper-focused on maintaining busy lives to utilize their time efficiently. As a result, an exchange of meaningless inquiries and answers that beat around the bush, loop back in circles, and result in going nowhere will merely be deemed as a painful time-killer, or perhaps a pestering obstacle in the way of our other tasks.

### Smart Software Engineering
This is more importantly prevalent in the tech industry and the general ubiquitous scope of software engineering. The rapid and instantaneous development of new technologies will mean that we, as software developers, will not have enough time to keep up and learn how everything works. Being able to communicate effectively through cooperation will hence be the main key to our success in the field. One way in doing so is by asking these “smart” questions: the important questions that will allow us to adapt to such environments with quick intensity, expand the community of critical thinkers, understand the main aspects of new technologies, and deepen our relationship with the technologies used in our lives. The possibilities that are rooted from these “smart” questions can lead to thought-provoking ideas and extensive innovations, since all of us, in one way or another, shape the future of technology.

In a more practical sense, asking smart questions improves the overall IQ or level of thinking within a community. Smart questions can help improve the work progress of group-based software projects, so that everyone is on the same page in understanding how their role fits within the project. It can also speed up the process of debugging, since other collaborators will be able to understand what is going on in the code or system software. This will allow implementations between other aspects of the project to become more cohesive. Another possible benefit that can result from smart questions include more help and support from external developers who can deviate or make enhanced modifications to the original source code. Overall, smart questions require resourcefulness, meaning that there is more time to get things done efficiently. With every developer coming from different backgrounds and levels of expertise, smart questions help us gauge a general understanding with each other. The work flow within a software project can end up being much so much smoother with inquiries that are critically-thought out. 

## **Examples of "Smart" and "Stupid" Questions**

### Smart Questions Only!

Upon reviewing Stack Overflow, a website containing community forums relating to programming questions, I was quickly able to find some examples that represent these smart questions. The following question includes and utilizes the guidelines that Raymond mentions in How To Ask Questions the Smart Way.

### Digging Deep Into Archives

There was some difficulty in finding questions that are not best represented to be “smart.” This is mainly because authors and other contributors on Stack Overflow tend to delete these types of forum posts if the question is not relevant to the programming community, or if it doesn’t get answered after a long period of time. After deeply searching through its archives, however, I was able to find several closed threads pertaining to “bad” or “stupid” questions. The following examples include posts of issues that occurred from a very long time ago (almost a decade), which may or may not be prevalent today, but nevertheless demonstrate how to not ask a smart question.

Even though all of these situations resulted in resolved answers, the responses to such questions reflected a lack of “smartness”. A majority of these instances involved a waste of the respondent's time and mainly boiled down to simple errors that could have taken minutes or seconds to solve, had the user either provided enough context or put in some form of minimal effort in attempting to solve it themselves. Furthermore, the posts that these types of questions contain fail to provide future benefit to other readers in the community, which diminishes the expansive knowledge that a community can collectively grow in the long run. 


```
Q: python date of the previous month

I am trying to get the date of the previous month with python. Here is what i've tried:

str( time.strftime('%Y') ) + str( int(time.strftime('%m'))-1 )

However, this way is bad for 2 reasons: First it returns 20122 for the February of 2012 (instead of 201202) 
and secondly it will return 0 instead of 12 on January.

I have solved this trouble in bash with:

echo $(date -d"3 month ago" "+%G%m%d")

I think that if bash has a built-in way for this purpose, then python, much more equipped, should provide something 
better than forcing writing one's own script to achieve this goal. Of course i could do something like:

if int(time.strftime('%m')) == 1:
    return '12'
else:
    if int(time.strftime('%m')) < 10:
        return '0'+str(time.strftime('%m')-1)
    else:
        return str(time.strftime('%m') -1)
        
I have not tested this code and i don't want to use it anyway (unless I can't find any other way:/)

Thanks for your help!
```

While the heading of his question could be better, it does convey what he’s trying to figure out. Usually something as brief as “python date of previous month” is what other users would enter in as search terms on Google, making it easily found. Another good thing about the question is that it’s not just a question. The asker shows what he or she has done and that he or she has put in some effort to answer the question. And while it may not be as important as the question itself, the asker shows courtesy, which does increase the chance of getting an answer.

```
A: datetime and the datetime.timedelta classes are your friend.

1. find today
2. use that to find the first day of this month.
3. use timedelta to backup a single day, to the last day of the previous month.
4. print the YYYYMM string you're looking for.

Like this:

 >>> import datetime
 >>> today = datetime.date.today()
 >>> first = datetime.date(day=1, month=today.month, year=today.year)
 >>> lastMonth = first - datetime.timedelta(days=1)
 >>> print lastMonth.strftime("%Y%m")
 201202
 >>>

```
 
The asker received six possible answers, and he or she was successful in inciting discussion from multiple users. The answers themselves were clear and were devoid of the rumored sarcasm and hostility of “hackers.” Since I myself have referenced this page and found it useful, I can confidently say that it is a good question.

## The foolproof way to get ignored.

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, create a desktop application with Facebook.

```
Q: Facebook Desktop Notifier

I am a beginner programmer that have never used anything other than what's included in a language.

I am trying to create a desktop application that notifies me anytime I get an update onfacebook. 
How should go about doing this? Thanks in advance.

edit Sorry I was not clear. Is there any way to make a DESKTOP application with facebook?
```

A simple “yes” would have answered the question, but we know that’s not the sort of answer he or she is looking for. Fortunately, someone kindly responded with a link to Facebook’s developer website. The asker should have done more research on his or her potential project. Then further down the road, he or she could have asked more specific and detailed questions that wouldn’t require a thousand-paged response for a sufficient answer.

## A New Approach to Asking Questions

From this module, I have learned that there are many types of questions that can be formed. Within Stack Overflow, I noticed that there are questions relating to more conceptual material on software, while there are others that involve more specific cases in optimizing a software’s utilization. In any case, the determining factor that distinguishes a “good” question from a “bad” one is the value that one can individually get from the given answer. That is, the wording, phrasing, and parametrial context of the question dictates the general “thresholds” of how effective a question actually is. Ultimately, a smart question simplifies down to this: Did we get the answer we were looking for, or one that we can accept, without wasting anyone’s time? If we can comfortably confirm this is the case, and can consistently or habitually ask inquiries on this type of level, then I think we are both well on our way to a bright future in tech. The influence that we have on tech as a whole can be pushed by the boundaries of these “smart” questions.

