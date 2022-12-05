# Out of team scope requests

<small><i>
First, please understand that describing every unique case is beyond anyones capability. Therefore, when reading, try to seek patterns and similarities instead of a definitive description of every team there is. 🙏
</i></small>

If you're in a startup with a few people, out of team scope requests might not be familiar to you.
Everything is kinda in your scope. Startups are the best places to become a jack of all trades. However,
once you land a job at a more structured, growing company (one could call it simply - corporate),
the dynamics amongst teams can quickly change.

Imagine, you are in an e-commerce company and your team is responsible for
handling the order creation flow or OrdersTeam. Then, SuperTeam comes to you
and asks to implement this small 3rd party tool they need. For one reason or another, you fulfill their request.

Now, you have created a precedent where SuperSquad can ask the orders team to handle their technical needs.
Next, SuperSquad needs to handle some analytics events. They come to you but you, as expected, are skeptical
why do you need to handle this request. You do see the value in the task because your team and other teams would also
benefit from having analytics.

After some deliberation, you understand that no other team has any responsibility to deal with analytics.
Therefore, going to any other team would be just as wrong as SuperSquad coming to you. As a good teammate
that cares about the sanity of others, you oblige SuperSquad and implement the analytics platform.

Now, you have created a second instance where **SuperSquad asks -> OrdersTeam does**. What will
come next is your team is going to become an ad-hoc SuperSquad tech team. Unfortunately, at this point
your team is the only one that deals with
1) analytics platform fixes
2) that 3rd party tool support
3) helping SuperTeam employees by adding new analytics events because these events inevitably need to be sent from the codebase.

How did we get here? 🤯

## Precedents set future expectations

There is no such thing as a benign out of team scope request. Most of the time, humans will revert to
choosing the path of least resistance. For the SuperTeam the path of least resistance is to go
to the same team that once already did what they asked.

What could you do?

Explicitly state to your team and to the other team that this is a problem which affects your teams delivery capability. Your teams results are a product of the following parts:

<code>Team goals achieved = f(team capacity - team tasks - external non-adhoc requests - adhoc issue/request handling)</code>

This is how I see it based from my experience so far. The more external and adhoc requests you do, the less you have capacity for your own teams tasks. If you're not careful, you can easily get to a point where there is a resource allocation imbalance <code>adhoc + external requests > team tasks</code>.

This imbalance can be subtle. You do a bit more than adhoc, a bit more external requests. By doing this you keep creating precedents. If left unchecked, you might dig yourself so deep that the new status quo will be extremely difficult to change.

Sometimes circumstances make it so that it's temporarily impossible to solve this problem and you are forced to find ways to incorporate the adhoc + external requests into your daily life. At this point, it's easy to give up and accept that this is how it will go from now on.

This is not theoretical.

I have been (or are) in such teams that created precedents. It doesn't necessarily have anything to do with intelligence or skill or even experience. Sometimes the context might align all variables around you in such a way that its much easier to go along with request. Maybe, you're very good friends with the people that create these external requests.
Maybe they even come from top-level management. What do you do now?

Remember, that past results don't define you. Only actions matter. Therefore, here's what I would suggest someone in this situation.

- It's important to take a step back, understand the full situation and how you got there. Document that for posterity and to avoid future scenarios like these.

- Brainstorm potential ways to resolve the issues. A visualization or a text document should be used to document ideas

- Spread awareness amongst teams and senior leadership that this is affecting your team and potentially the company

- Create meetings with your managers to discuss how to resolve the problem if its bigger than you can handle alone. The previous points might be helpful to be done beforehand.

- Consider a **hard no** approach to external requests. I would suggest to do it gradually to avoid a negative sentiment about your team but also don't take too long. 1-2 sprints (2-4 weeks) should usually be enough to make such changes. Of course, it might wary depending on your situation.

- Identify signs of a potential precedent early. It's a million times easier to reject the 1st external request rather than the 10th. There's an expectation already set that now needs to be broken.


While I want you to remember that *precedents set future expectations*, I also don't want this to be taken as a manifesto to creating isolated silos in a company. Ultimately, people in a company are all working towards the same goal (at least they should). People moving as one team, should help each other grow and be better (within reason).

Hopefully this helps you and thank you for reading.
