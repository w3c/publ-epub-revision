Chair: Markus Gylling

Scribe: Bill McCoy

Audio recording: 100915

To listen to the recording, dial in and press star 3



## Attendees ##

Takeshi, !Si-Wei, wen-hsuan, mikeidpf, DaveGunn, gc, ChoChin, DanHughes, !Kyoji, mgylling_, BradyDuga, kennyluck, matthaas, keith\_fahlgren, James\_Pritchett, BillMcCoy, marisa\_demeglio, George, KingWai, ShuTanabe, Ryoji\_Akimoto, mikew3c, SteveKotrch, mgylling, jstallent, wmanis_

## prev minutes ##

approved

## prev action item review ##

George: spoke to Board re: W3C/CSS coordination, there are members in our group who are also in W3C WG, also want to suggest task force in our group make comments/recs to W3C. Not a lot of work, we'd have responsibility of informing W3C CSS WG what we need & what our actions will be in re: their spec (to be good citizens). Borad approved moving forward on this last Thurs

Markus: we said previously this was a longer-term item, not something for this autumn's spec..

George: right, and last call for HTML5 has just been pushed until March or May vs. Dec

## rotating scribe list ##

[George](George.md) 20 people on the call now

Markus: want to set this up, it will include Bill non-exclusively ... cycle through it for remainder of calls of WG

Markus: if you can imagine yourself scribing, every 5 calls or so, please help us out - contact me off list

George: they need only add notes to IRC & script puts it into format into Wiki

Markus: script helps with it

Markus: you do need IRC access to be a scribe

## next F2F ##

Markus: agenda published (draft form)

Markus: idea is to have subgroup sessions on deliverables for first draft (Oct)

Markus: also plenaries (full WG) meeting to resolve issues

[wmanis](wmanis.md) Can you give us the address of the Adobe offices so we can book hotels nearby?

MikeIDPF: meeting place details being finalized will send out details & hotel info soon

Garth: plenaries - will that include subgroups presenting proposals to whole group?

Markus: likely one of the things we'd do

Garth: need WG to approve solutions before we go to draft

Markus: we could also be discussing things for which no solution is proposed yet

[mikeidpf](mikeidpf.md) Adobe San Fran: 601 Townsend St.

[mikeidpf](mikeidpf.md) San Francisco CA 94103

Markus: if current draft does not satisfy needs for travel approval I can fix it

## timeline clarification ##

Markus: 8th of October is not a deadline for requirements to be considered for EPUB3

Markus: now that we have F2F set, we have updated timeline to say that submissions for first draft must have proposals by end of F2F week

Markus: there are 3 opportunities to submit stuff, if something is to get it it's better to have it there sooner, but we already agreed the first draft would be incomplete

Markus: deadline for second draft not set yet

## editing process ##

Garth: volunteers for editor group have come forth, on our aggressive schedule and looking at OEBPS 1.2 (last big set of changes), we had a fairly dedicated editor, Dorothy, it seemed to make sense to take that path again w/ EPUB3

Garth: Bill McCoy has made a chunk of his time available and we've retained him to act as principal editor. this takes time pressure off people who've volunteered, but time will be used to advantage in subgroup level

Garth: hopefully initial draft edit language to get spun into final specifications, also that there'll be plenty of opportunities for reviews & editing on final specs

Garth: pleased we've allocated a few dollars, Bill is working at reasonable rates (above and beyond volunteer time as Secty as group), hopefully raises the odds of getting us to goal on target specification

George: Bill is following our directions and orders, at our beck & call, not innovating himself

BillM: definitely not!

Markus: we mean by editor not how W3C WG defines it, but simply a person who puts in specification prose decisions of WG, drafting group consensus

Markus: we have had Word-based specs so far which presents problems for collaborative editing & good output

Markus: we will use the Google Code SVN repository for specs & schemas, we will start w/ representing spec using DocBook5

Markus: docs are in need of cleanup & straightening out and DocBook is a good thign for that and will allow producing nice XHTML & EPUB

Markus: alternative is popular in W3C, respec, it may be a future option for us, we're starting w/ DocBook

[keith\_fahlgren](keith_fahlgren.md) respec

Markus: respec.js (JS based)

[keith\_fahlgren](keith_fahlgren.md) http://dev.w3.org/2009/dap/ReSpec.js/documentation.html

Markus: we'll be committing to repository later this week

## fwd/backwards compatibility guidelines ##

Markus: link to new version, only presentation has changed not logic or nature, is in agenda

Markus: need to discuss addition of enumerating a process for testing fwds compatibility, that includes us building a list of Reading Systems that we find significant enough in terms of deployment to include

Markus: impossible to test all RS on the market so we need a limited list

Markus: proposed lists is 10 RS

George: could a company test on their own?

WillM: if we say X readers meet the bill, it is arbitrary, we need hard criteria

Markus: we're saying we don't test ourselves but let anyone w/ a RS test

Keith: the reason why that might not be ideal is that the reason this testing list is being enumerated is to try to be able to test compatibility conformance and reallity of our definition of acceptable compatibllity

Keith: e.g. are text & images preserved in existing RS if we do this crazy innovation, but so much of real world implementation details will be critical

Keith: we can say all we want but if Nook or Happy Reader doesn't do X we need to know it definitively, we may choose to ignore but...

Garth: in theory this form of testing (design principles 1.3), it's in the cases where EPUB3 is modifying/removing existing 2.0 features

Brady: it feels it might make sense to put this in the hands of developers because it's difficult for us to say what fail means

Brady: "acceptable" can mean different things to different people

Brady: if we make it up to Adobe to tell us, then they can tell us if it's unacceptable

Peter: don't make any list, if you are RS developer and care about the issue, it's your responsibilty to figure out what's going to work

Peter: if something's breaking compatibility it's your responsibility to bring it to WG

Garth: the one that's not the case is Amazon, they aren't in the WG, maybe someone in WG can pick it up

Peter: you don't need to be developer to raise concerns

Brady: impt to highlight areas that might break forwards compatibility

Markus: producing a test specimen is optimal but...?

Brady: we need to make it clear what needs to be tested, not doing testing

Markus: we can't publish a test and wait 6 weeks....

Peter: I'd proposed as we define spec, features get fleshed out, we make best judgment not to break something, someone can create a test to check and demonstrate to WG

BillM: proposer should test if they are proposing something that is going to create breakage

[keith\_fahlgren](keith_fahlgren.md) Yeah, Peter makes me realize that easily-updated systems like Bookworm and Ibis Reader are not really a concern for this topic

Peter: if I propose a new feature I can propose a crafty test that things pass, so without someone who knows RS tests would be not good

Peter: tests would be different for different RS

Peter: how do people know what will break

JOINED: [jstallent](jstallent.md) [2010/09/15 14:32:25]

Brady: I put out volunteers for solutions and only got 2 volunteers, if I add on test requirements my 2 volunteers may get angrier

JamesP: how many of 10 systems have reps on WG

Garth: 9

JamesP: proposer preparing a sample doc is closer to actual use case

JamesP: happy doc provider makes test, happy user goes to nook and it breaks - that's what we want to avoid

JamesP: that's not a model for RS vendor to provide the content (test)

Peter: suppose proposer provided hidden text with two modes of presentation, suppose RS developer says this isn't going to work right because of how I process HTML

Peter: then developer can check it and elevate it as a potentially unacceptable breakage, someone else migth not realize what should be brosken and thus might not make a test that showcases the breaage

Peter: corner case needs knowledge of RS

Peter: I have no idea about how mobigen works, w/out familiarity it's impossible to say

George: we need a little bit of both

WillM: Bill u used "unacceptable"

WillM: supposed I put in new part, some may barf, some may ignore, not sure how we can define in a clean way

[James\_Pritchett](James_Pritchett.md) That was me (JamesP), not George

Garth: Will yr example is particularly relevant, if you throw something new in iBooks will probably barf, but they are involved and by the time we ship hopefully they will rev

Will: your definnition of acceptable is a new version of reader can handle it?

Garth: in environment like iBooks where apps are updated all the time, different question if there's a SadReader that you couldn't update the F/W then you may get to a different answer

Brady: this might be up to developers, since they control update cycles

Peter: ADE is one thing, devices are far more remote, hard to update some of them, very different use cases

Dave: on call, Garth you are correct, if there were features added that we felt were important to support we'd probably come out wth a new version that it didn't break

Dave: we are erring on the side of caution with ingestion systems to ensure highest standards, truth is much wouldn't actually break reader we're just trying to keep things adherent to the spec

[keith\_fahlgren](keith_fahlgren.md) Yeah, extra files don't break iBooks IMHO

Dave: then we can predict results of changes

jamesP: I don't understand the definition of fwd compatibility, if we have a new reader it's not an issue

Markus: really only a problem w/out an easy update facility

Keith: right

Keith: 3 classes: readers that are somewhere on spectrum of fairly easy to update - from trivial, although if developers are on the WG and feel a change proposal will fundamentally break their SW they can raise the issues, for most part we don't expect to be worried about that class

Keith: 2nd class is physical devices where update mechanism is difficult or impossible, that's things like older Sony Reader

[keith\_fahlgren](keith_fahlgren.md) I don't think we realized that yet

Will: people are' still running Win95

Will: ebook store needs to query and serve up different files

Bill: no, that will delay EPUB3 adoption by 2 years

WillM: then testing is one of the most important things we need to do

Dan Hughes: we need to do compatibility testing on our own to ascertain what's happening with the spec, this is different than conformance testing

Keith: 3rd class is services that ingest EPUB that we feel are important from a market, rather than technical, perspective

Garth: I feel it's OK to remove the list, I feel it's dependent on whether the RS is actively moving forward, this list may not be helpful towards our goal

Markus: what is the concrete directive?

Garth: we're in agreement on design principles, that's where we go, 1.3, between RS developers and solution proposers, that group needs to worry about fwd compatibility

Markus: that ties back to what Peter is saying, we can do watchdog stuff collegially in the WG, it's only if we are in doubt that we need to produce test files

Peter: I will produce some test files for our system and they should be encouraged to share

Peter: we can say propose your soluiton, no strings attached, but if someone feels that solution will break, they may ask you to produce test file

BillM: solution proposers should be prepared to produce a test file if asked

Markus: edit in place! ;-)

Garth: OK

WillM: move from EPUB2 to EPUB3 we should be making platitudes even though we can't achieve it completely

WillM: we should have schema evolution going forwards from EPUB3 to EPUB4, statements about namespaces, parts of containers, etc.

WillM: unless we start laying that groundwork we'll

WillM: we'll find ourselves in the same space we are now (lip service)

BillM: schemas in source code control is a step in the right direction

WillM: XML evolution requires strong namespace support so you can handle new tags with new namespaces

Markus: strong statements about RS behavior in encountering unknown elements, etc.

[keith\_fahlgren](keith_fahlgren.md) The OPF Package Schema in 2.0 is not a standalone file. It's embedded in the specification. That's why a different working system matters ("Why Words matters")

Garth: note has been added to 1.3 of Design Principles

BillM: Keith & Will, also "the specification" is not something that's under version control!

ACTION: set up tables on each subgroup page and populate them (wrt expectations on other subgroups)

Markus: links to other requirements in other subgroups that have expectations on them

## subgroup status reports ##

## annotations ##

Will: solicited volunteers, Daniel will add something tomorrow

## EGLS ##

Brady: IRC-run conference directed at looking at specific impls of systems doing vertical writing or other extended language support

Brady: a bit shaky on IRC but should get better, Taipei meeitng in a few weeks

Markus: a number of EGLS participants will come to SF as well

## metadata ##

Dan: metadata group moving towards expanding existing structure, wondering about outright embedding as preferred vocabulary, or something like RDF/A... will be ongoing

Markus: perfect illustration about designing grammars so they can evolve, Dublin Core elements we have now the opposite of that

## navigation ##

George: time tomorrow to work on navigation

Diane: our group is spending time on "hot spots" ... mags on iPad, I just created an analysis, and some vendors discussed the idea that our content is instead of flat, N-dimensional layers, really challenging

Diane: is navigation group here simply looking at TOC or is there cponsideration of "hot spot" navigation?

Diane: I developed analysis presented to group, please send PDF of slides

## text content ##

Markus: next dict-centric call tomorrow, standard time, hope to settle it within a couple of weeks, to have a draft grammar for dicts

Markus: draft solution proposal for representing inline metadata, RDF/A1.1 (attribute collection) injecting to OPS

## styling & layout ##

Brady: 2 volunteers, 3 solution pages up, please check out the pages and please volunteer for other solution proposals

## rich media, interactivity, & ads ##

Peter: hoping to get time to discuss process for solutions given so many reqs, but we are out of time

## new action items ##

  * set up tables on each subgroup page and populate them (wrt expectations on other subgroups)