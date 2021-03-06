---
layout: default
---

# Information on Meetings
{: .no_toc}

* TOC
{:toc}

## Teleconferences

To accommodate the time zone differences the teleconferences alternate between two time slots:

* Every second week, starting the 11th of September 2020, the call is on _**Fridays at 10:00 US Eastern Times**_ (see the [timeanddate information for your local time](https://tinyurl.com/y24qnpgg)).
* Every second week, starting the 18th of September 2020, the call is on _**Fridays at 09:00 Japan Standard Times**_ (see the [timeanddate information for your local time](https://tinyurl.com/y28b55nq))

The group uses MIT’s Zoom Account for the calls. See [our member confidential announcement](https://lists.w3.org/Archives/Member/member-{{ site.wgname_lc }}-wg/2020Aug/0000.html) for the dial-in data (_please, keep the meeting password confidential!_). That page also links to ICS files (see attachement links at the bottom of that announcement) to help setting the entries in your personal calendars.

The Group also uses IRC for during the calls for minute taking, queue control, and general chit-chat. See the [separate page at W3C](https://www.w3.org/Project/IRC/) for further details. This Working Group uses the `#epub` channel, and makes use of two bots on IRC:

* `zakim` for queue control (see the separate [manual pages](https://www.w3.org/2001/12/zakim-irc-bot.html) for  further details.)
* `rrsagent` for scribing and minute generation (see the separate [manual pages](https://www.w3.org/2002/03/RRSAgent) on how to control the access rights and storage of the IRC logs, and the separate [`scribejs` features](https://github.com/w3c/scribejs/blob/master/features.md) for the scribe instructions).

**Joining the call is restricted to the official members of the {{ site.wgname_uc }} Working Group and, possibly, guests invited by the WG chairs**. Joining the group for representatives of W3C Members can be done via the [join form](https://www.w3.org/2004/01/pp-impl/{{ site.groupid }}/join) (this form must be filled by the AC representative of the Member organization).

## F2F meetings

* [October 22/23, 2020](./F2F/2020_October) (Virtual F2F Meeting on Zoom)

## Meeting Minutes

Meeting minutes (both for F2F and telcos) are listed [separately](./Minutes/).

### Minute taking

Minutes are taken using IRC, and is based by a collective effort: one of the participants should be the scribe for (part of) a session. The EPUB Working Group will be using a scribe rotation list to avoid relying on volunteers, if you are interested in scribing, please contact the [chairs](mailto:group-epub-wg-chairs@w3.org). The `rrsagent` bot is used to archive the IRC log at the end of the call, and a separate tool (called [`scribejs`](https://github.com/w3c/scribejs/)) is used to generate the cleaned-up minutes that are published on the Working Group’s Web site.

Minute taking and cleanup is greatly helped by:

* consistent scribing, if you are the scribe, there's a number of features in  `scribejs` to help you and the person who cleans the minutes up keep the minutes clean and easy to read
* scribing basics:
  * `scribe+` / `scribe+ nickname` to add yourself or someone else as the scribe, more than one person can be a scribe for a meeting
  * `nickname: ` to identify who is speaking, most IRC clients have a feature where typing the first letter(s) of a nickname and hitting TAB will complete the name
  * `... ` is used to continue when then speaker you've identified is still speaking, but you need a new line - it is often easier as a scribe to break up the minutes as you're typing
  * `s/[from]/[to]/` is used for correcting spelling errors or missing information, the person who cleans up the minutes can do this as well, so don't be too concerned about spelling errors
* for more commands or functionality, they are detailed in the [`scribejs` features](https://github.com/w3c/scribejs/blob/master/features.md) repository
* to help minute taking and cleaning them later, please use a consistent IRC handle; scribes should use that handle to identify the person speaking. `scribejs` automatically replaces the handle with the person’s full name, making the minutes more readable to outsiders.
    * note that in most IRC clients the `TAB` key can be used to expand to an existing irc handle

* *Each participant should type `present+ <irchandle>` (or simply `present+` for himself/herself) in the irc channel immediately upon joining the call.* (This will help the minute taker and improve the generated minutes.)

(Note that a [group specific Web interface to sceribejs](https://w3c.github.io/scribejs/BrowserView/epub-wg.html)) is also available to generate the minutes. This feature is still experimental, though.)

### Updating the minutes

The minutes themselves are stored, in Markdown (more exactly in “Kramdown”) on the WG’s core [github repository](https://github.com/w3c/{{ site.wgname_lc }}-wg) in the `_minutes` folder.

As described in the [separate page on our working mode](../WorkMode/index#telco), meeting minutes are considered as “Drafts” for at least 5 business days; participants of the call have that time ask for changes and/or rectifications on the minutes (such requests should be sent to the group’s public mailing list or via a Pull Request on the minutes themselves). After that (i.e., usually at the subsequent call) the minutes become official.
