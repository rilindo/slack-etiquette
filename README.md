# Community Slack Etiquette (or IRC Etiquette Reconsidered)

In the last 5 years, Slack has become an alternative real-time chat to IRC, as it became the preferred medium for communities dedicated to software languages, operating systems, web services, and every other technology out there. That said, community slacks does share similar social dynamics with IRC (as opposed to social dynamics with private, company slacks). This guide will help you get most of slacks when you join to ask questions and get assistance.

NOTE: While this is inspired by IRC Etiquette, there are elements of it that were fairly problematic, which we are addressing to ensure that this guide is more inclusive.

## Be kind, courteous, and respectful

People on slack channels are taking their time to help and even administer the slack channels. In many changes, they have just a few minutes out of their work day or family time to check in. Please take that into consideration when you ask.

## Review community guidelines or code of conduct

In some communities, there may be a code of conduct or community guidelines posts as pinned links. Please review them, as they will drive how you should ask your question. For example, if the community guidelines ask you to communicate in a gender neutral fashion, you should do so accordingly. 

## Go ahead and ask your question

While it is understandable that you want to be polite, in almost every case, you can simply ask your question and if people are online, they will answer. That will get more results, than just saying "May I ask a question?" or "Can anyone help me?". 

## Be precise and reasonably descriptive

In your question, you should provide enough information for people to response. Make sure you include at least this information:

- What did you try to accomplish? (I wanted to run Apache in Docker)
- What has happened (wrongly) instead? (I can't view my web site)
- What environment are you using? (I am using Docker on Ubuntu)
- What did you try to find the cause? (I checked that container is running)
- Are there error message or log files? (I am getting reads: "Connection Refused" from the command line)
- Has it ever worked? What did you change? (This is my first time running apache under Docker and I just created the Dockerfile)

If all this information is included then you will have a high chance of getting a useful reply.

## Tell what you are doing

People will only stay with you if you tell them what is going on. Remember, their time is just as valuable as yours, so if you need them to continue to give you help, if you:

* Make any changes and
* It caused a different problem now

Make sure to communicate that.

## Post to the appropriate channel

In most slacks, there are channels dedicated to a specific topic. Join channels that are most relevant to your question (For example, if you have an AWS question, go the #aws or #cloud channel). Then, if there is a topic, review that - you should find some useful information about how this channel is supposed to work and may even lists URLs for FAQs and documentation that could answer your question.

NOTE: While it is tempting to post your question in #general, it should be used very sparingly and ideally, should be used only to ask which channel to post your question. Here is an example:

`I am experiencing a problem running puppet code on a new CentOS 7 - I am trying to install mySQL, but the puppet client is returning "Could not request certificate: getaddrinfo: Name or service not known. Is this the right channel or is there someplace different I should go to?`


Understand that #general is the default channel that most people *cannot* get out. Depending on the amount of traffic, your question can get lost (or worse, deleted if there is already a relevant channel)

## Be patient

People on slack are sacrificing their time (doing so for free) to help you. They are free, though, to move on to more important things if they are challenged. You can demand if you like; you may not get the response you desired.

## Ask before you DM

You can either talk to others in a channel publicly or direct message (DM) them privately. However, avoid DM people unless they clearly communicated that it is okay. That is because:

* Asking questions publicly can bring more eyes to your question and perhaps provide a much better solution
* The person you DM may not immediately be available.
* DM from strangers or even mild acquaintances is considered rude by some people and will be ignored.
* In some cases, depending on how you communicate, it could be a form of harassment.

## Responding to Rudeness

Sometimes, you may get relatively terse to your question, such as 


`Reinstall the package. Restart the service. Read the /usr/share/doc/mysoftware/README.` 

While you can get offended by this and it could be communicated better, unless there is a clear attack on your ethnicity, gender, orientation, belief, or politics, it is not worth the time to respond adversarially. Jut make sure to address that statement in a clear, polite manner.

(Though if you have not done what you have been asked, you probably do that before you respond)


## Ask for help with documentation

If people tell you to read the documentation, it can be annoying, especially if you have read the documentation. In that case, you should communicate where you have having problems with the documentation. For example, if the documentation is too technical or you don't understand certain sections then say: "I have now read chapter 3.1 of the URL you gave me and I understand how virtual domains work in general. But how would I use both virtual and non-virtual domains together?"


## Communicate Clearly

Unclear speech (mis-spelling, bad grammar, etc) is hard to understand and can be ignored. Strive to write in clear, concise manner, with. If English is not your first language and you have problems with it, you could ask somebody to translate or find a slack channel that is tailored to your language.


## Answer the questions that you get asked

It may sometimes be hard to follow all the conversation on slack. But if people are trying to help you and need to ask you a few questions please answer them all. If you get asked three questions and only answer one or keep asking the same question time and again (showing that you don't read what you get asked) you risk to be ignored. Show some initiative and your problem will likely be fixed within a few minutes.

## Tell others about the solution

If you found a solution, go ahead and share it. It may help other people

## Careful which answers you pick

When getting responses be careful who you trust. Some people just want to feel important by giving you any answer, whether it is right or wrong. In some cases, those answers may be malicious.

(As an aside, if you are having an issue that is specific to your work environment, it may be best to reach out to worker first. Blindly following a solution given by a random person in public slack without verification can have catastrophic consequences)

## Sharing on Slack

In general, you may need to post something on slack whether it is an error or the configuration file. In most cases, you should use text, as it lets people copy and paste for review and parsing. Here are some general recommendations.

* For short text, use mark down to format
* For longer text, use gists or pastebin

Screenshots should be used sparingly.

IMPORTANT: If it is something related to work, you may need to use a scaled down version of your output and strip out identifying information such as ip address, etc as providing that info may be in conflict with your company's confidential policies.internet.

Related links
-------------

- https://github.com/fizerkhan/irc-etiquette (the original IRC etiquette)
- http://www.catb.org/~esr/faqs/smart-questions.html
- http://www.koepf.de/irc.html (german)
- https://hiverhq.com/blog/slack-etiquette/ (additional slack etiquette that is specific to private slacks)