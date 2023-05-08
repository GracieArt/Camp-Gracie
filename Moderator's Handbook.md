# The Moderator's Handbook

## General moderation procedures
The role of a moderator is to ensure that the core values of the server are respected. There are several procedures a moderator should know in order to ensure this, but keep in mind the goal is not to be overbearing. Only step in when you feel it's necessary, and use your best judgement.

### Moving a conversation
Sometimes people go off-topic or just send stuff to the wrong channel. In these instances, people are expected to moderate themselves, so no action is necessary on the moderator's part, but you can kindly encourage people to move to the correct channel if things go off topic for more than around 8 messages or so, use your best judgement.

### De-escalation
When a person becomes emotionally compromised, it is necessary to remind them to be kind and civil, but due to their vulnerable state, extra care should be taken to de-escalates the situation. Kindly acknowledge their feelings and suggest that the conversation end or be moved. Again, use your best judgement. And you're never obligated to handle these kinds of situations on your own, please reach out to the other mods for help if you need it.

Examples:
- "I get why you're frustrated, but let's leave it to rest for now."
- "I'm really sorry that's been happening to you, but maybe we can find somewhere else to vent about this."

### Uncredited artwork
Sometimes people forget that all art needs to be credited or sourced if it doesn't have a readable signature or watermark. If you come across a post like that, kindly remind the person to credit the artist. You're not obligated to source art for the people who post it, but feel free to chime in if you happen to know who made something.

### Adult content
We classify "adult content" as content that features sexual intercourse or exposed genitalia, or content that appears to be made with the intent to arouse or gratify the sexual desires of the viewer/reader.

Adult content that features exposed genitalia or sexual intercourse is not allowed anywhere in the server. Content that is merely sexually suggestive is allowed but only in the designated NSFW channels.

If somebody posts content that is EXPLICITLY adult outside the designated NSFW channels, delete the post yourself as soon as possible. This kind of thing should be handled privately, so send them a DM (if you can) and explain why you deleted their post.

Content that isn't explicit, but is merely SUGGESTIVE is a bit more of a grey area, so if you're unsure if something should be considered NSFW, post it in the moderator's channel so we can discuss it.


---


## Commands
When a moderator performs a disciplinary action, they are required to do it through Carl-bot so we can keep track of everything and be on the same page. Whenever you issue a warning or a ban through commands, a case is created. The case has details such as the case number, when it was created, who the offender is, and the reason provided. You can search for cases for a specific user with the command `/modlog from <member>`.

In the event that you wish to run any of these commands on a user that is not present in the server anymore and you can't mention them, you're going to have to copy and paste their user ID, which can be found by making sure you have "developer mode" enabled in your settings, right clicking on the user's name, and clicking "Copy ID," then paste that wherever any of these commands asks for a `member` or `member_id`.

### Warnings
You can issue a warning with the command `/moderation warn <member> <reason>`. Once a user has accumulated `3` warnings, they will be automatically banned.

Users may feel free to appeal warnings, but only through direct messaging. The appeal should be discussed by all the mods in the `#staff-meetings` channel to decide whether the warning was given in vein or not. You can repeal a warning with the command `/moderation removewarning <case_number>` and it will be removed from their name.

### Bans
Similarly, you can issue a ban with the command `/moderation ban <member> <reason>`. DO NOT USE `/ban` as this does not create a moderation case.

Appeals for bans will not be considered until 30 days following the ban, which can be found by looking at the case information with the command `/case info <case_number>`. The decision to appeal a ban should also be discussed in `#staff-meetings` just like we do with warnings. You can repeal a ban with the command `/moderation unban <member_id>` with the id of the user.


---


## Taking action
Handling things verbally is usually enough for most situations, but there are certain behaviors where disciplinary action is the most appropriate response. A violation represents a failure to comply with the server rules, and a moderator will have to take appropriate action corresponding to the severity of the violation:

### Minor Violations
Minor violations are acts of negligence, usually but not necessarily without ill intent. For a violation to be considered minor, the effects of the act must be non-serious and easily reversible or mitigable. The person should be given an official warning with `/moderation warn` and be expected to change their behavior going forward.

<dl>
  <dt>INSUBORDINATION</dt>
  <dd>Provoking, arguing with, or failing to comply with a moderator.</dd>
  <dt>SPAM</dt>
  <dd>Repetitive, obnoxious behavior that the person knows or should know will make tedious the act of participating in the server.</dd>
</dl>

### Major Violations
Major violations are acts of serious negligence or malice. For a violation to be considered major, the person must show that they have either harmful intent, or an unwillingness to abide by the rules due to repeated violations. After committing a major violation, the offender should be immediately banned with `/moderation ban`.

<dl>
  <dt>REPEATED INSUBORDINATION</dt>
  <dd>Failure to comply with moderators after multiple warnings.</dd>
  <dt>HARASSMENT</dt>
  <dd>Hostile remarks targeted at a specific user or group that a user is a part of.</dd>
  <dt>DISRUPTIVE BEHAVIOR</dt>
  <dd>Behavior that the person knows or should know will alarm, anger, disturb, or provoke others or generally disrupt the peace.</dd>
</dl>
