URC Classic Flows - I Need Help!! - 2025/01/24 12:26 GMT+05:30 - Transcript
Attendees
Krithika Rajendran, Krithika Rajendran's Presentation, Prasad Boominathan, Rahul Singh, Rahul Singh's Presentation
Transcript
Krithika Rajendran: So, Wi-Fi access point is basically the Wi-Fi, it's the latest Wi-Fi 7 router that Verizon is now going to start offering with most of their plans. from say now you're going to go on the Verizon site and you're picking some internet plan you would get this Fi 7 router which is called Fi access point okay so the thing about this equipment is that this equipment can function as either a router or an extender okay it's the same thing only it's not like there's a Fi access point that's a router or there's one as an extender basically if you have one at your house that will work as a router now you're getting one more okay it's the exact
Krithika Rajendran: same equipment but that one will act as an extender and you get one more that will also act as an extender. because of some marketing reasons and…
Krithika Rajendran: things like that we don't say Fi access point extender. We just say Fi access point that functions as a router and Fi access point that functions as an extender.
Rahul Singh: See what?
Krithika Rajendran: So this is what Wi-Fi access point is. So in the prospect flow it's pretty sta straightforward because they just need to so how the BPP looks right like be it in prospect or…
Rahul Singh: Yes. Yeah,…
Krithika Rajendran: in URC so we have a section called internet router so in prospect…
Rahul Singh: I do.
Krithika Rajendran: what happens is all these whatever right now is there right rent Verizon router or whole home Wi-Fi plus whole home Wi-Fi all these things will be updated to look like earlier also they would have had the same tiles but the details within the tile would have been different they would have mentioned whatever previous router we were using fires router or…
Rahul Singh: Yeah.
Krithika Rajendran: whatever. So even for whole home Wi-Fi plus it's the same service only basically with what whole home Wi-Fi and whole home Wi-Fi plus are okay so it's the same thing only you'll get the same whatever like one router plus three extenders or one router plus an extender but in this case it's all one equipment so basically this portion within the details will change so for prospect all this is pretty straightforward they just need to replace the info in the tiles but for URC it's little more complex  Right? Because you have taken a plan from Verizon some years ago. And you having some old router. today you come to the URC and you're like okay I want to change my internet speed or something. So when you change your internet speed we will by default make you upgrade to the latest router. so there's this file. Okay. You can go through all of these things over here.
Krithika Rajendran: So this was all done for the regular flow. So now in URC we have two Regular flow means that's the most updated whatever like the plans that people see over here will be all the latest plans. Maybe you're a very recent customer of ours. So you are seeing all that stuff. So we like that we have one more thing called classic plans.  So classic plans are plans that they are in an area where maybe people around you there's very old plans basically which support very less internet speed maybe just up to 100 MBBS or something like that. So there might be certain places in the US where a lot of people you and I live in a neighborhood and in our neighborhood everyone has classic plans. Okay.
Krithika Rajendran: For them so they cannot directly upgrade to the more recent plans…
Rahul Singh: Yeah.  Yeah.
Krithika Rajendran: unless Verizon changes the infrastructure in that whole area. And the reason why Verizon might not be doing that in that whole area is most of these people seem to be content with their plans and it's a big investment for them, so they're like okay fine they are okay with that which is why we still have a prospect flow for classic plans otherwise we would have stopped selling them long time back right so similarly we have a URC for classic plans which looks it's not too different from the regular BPP so…
Krithika Rajendran: if you see the URC classic plans right it's just that the plans that come within this portion will look a bit different.
Rahul Singh: H so deck I have a Jira ticket so I think Yeah,…
Krithika Rajendran: So when they say that for classic flows that we need to incorporate do you have any deck or something like that Monica or someone gave you?  Can you show it to me?
Rahul Singh: I have to share my screen. I think sharing it one minute here. This one is not for the wait. For classic flows, I think she has not shared anything.
00:05:00
Krithika Rajendran: Yeah. s***.
Rahul Singh: Give me one minute, please.
Rahul Singh: So many threads we have right now. I'm losing control of all these. Where could I find it? Monica Rishi. Yeah, this should be the one.
Rahul Singh: Yeah, I think we have a deck. So, I'm sharing it here. Wi-Fi access point. Yeah, this is the one.
Rahul Singh: This also Have the zero ticket. stand.
Krithika Rajendran: So all this is the normal flow only.
Krithika Rajendran: I don't think they have anything specific to classic flows here. So I'll show you what I did for the normal flow and then you see how probably the same similar what do you say scenarios would come up for the classic flows. and then you can see then I would suggest you do one and you show it to Monica. Whenever and then get her feedback on it and then you can work on the rest of the scenarios. So for the normal flow 1 2 3 4 like around five.
Rahul Singh: how many scenarios are there? Three, four or five. Five works. Okay.
Krithika Rajendran: So if you see this right so this is the scenario for this one. So customers currently renting router from us. So this is the default thing usually when you pick a plan a router is included we'll send you router also right and…
Rahul Singh: Yeah. Heat.
Krithika Rajendran: this is like that router basically which also exists as a t within the PPP okay so suppose you picked 500 MBBS plan or something like that okay and then when you come to the route this thing where is in router it will say included And it will be selected by let me explain from this thing. So this is the thing they are on this plan. They don't have any extenders. They see the new Wi-Fi access point in the URC and decide to upgrade their router. This is a very rare case. I don't think many people actually go around looking to upgrade their router or something unless it's very old. But this could be a scenario.
Krithika Rajendran: So in this case I have 500 MBBS is my plan. And then I'm going on to the router section. So I told you when you pick any plan you'll get a So this is already selected rent Verizon router and we're calling it Verizon router. So when you see Verizon router you can think that it is the old So this is the current plan right?  I have a router. This is my current plan. This is how it reflects over here. And over here also you can see the thing. It says rent fires home Wi-Fi router. And now all the other tiles I see so now the whole home Wi-Fi plus I'll see will be the The whole home Wi-Fi one I see will be access points one and we'll have a access point also. You got it?
Krithika Rajendran: So it's like now we are giving them so this is what used to exist right and I already have this okay suppose I didn't have this I wouldn't see this but because I already have it I am seeing it now but we are also showing them this because this is something we have now and if they want to they can opt for this okay okay we'll keep going on and…
Rahul Singh: Okay. Thank you.
Krithika Rajendran: then we'll see whether it's too confusing or what so it is a little confusing  So in internet router no we have around five tiles usually okay plus whole home Fi that rent router what I told you and use your own router if you already have a router you can pick that and you can also buy a router okay so what I'm saying is suppose I'm a prospect right I will only be seeing 1 2 3 4 five five tiles okay all giving me the latest technology but suppose I am a
00:10:00
Krithika Rajendran: existing customer we have to show them what they currently have also right so that's why this additional tile is there which is rent okay so you can think of this Verizon router tile as this is the old router older tile and this is the new one okay…
Rahul Singh: Yeah.
Krithika Rajendran: because this person already has this we are showing this but they can opt for this as well can you see this also says included yeah the other things are all paid services so if they want they can  switch to this basically. So let's say I click on this. So once you click on that then we give them a notification saying that you're upgrading to the latest Wi-Fi access point. So with this Fi access point only those other Fi access points can work as extenders. Okay? You can't use some old extender that you have along with this. So at this point we tell them that you're upgrading to the latest Wi-Fi access point.
Krithika Rajendran: Please return any Verizon router and Verizon Wi-Fi extenders to the nearest eligible Verizon store to avoid fees on unreturned equipment. Okay, let's say in this particular case you're showing the person doesn't have any extenders.
Krithika Rajendran: But suppose I had a router and I have some extenders at this point. So then I get to know that I have to return this also.
Rahul Singh: the previous ones,…
Rahul Singh: right? Yeah.
Krithika Rajendran: Yeah, the previous ones the router plus the extenders I'll have to return because I am upgrading this to this router.
Rahul Singh: The latest one.
Krithika Rajendran: Yeah. And…
Krithika Rajendran: and then in the add Wi-Fi this is the extender section. and in extenders we have two options you can either rent or you can buy. Okay basically this is like suppose I picked whole home Wi-Fi plus here right if I had picked this with this basically that allows me to rent three routers from Verizon. So if I pick this then over here this would have already been selected for me. …
Rahul Singh: H okay.
Krithika Rajendran: because this is basically attached to that one. If you find Yeah.
Rahul Singh: It comes with the plan itself.
Rahul Singh: 
Krithika Rajendran: Suppose I have picked whole home Wi-Fi plus then I will see this rent thing. It'll say included and it might be selected already and then you can pick how many you want. Okay. I'll show you that in the subsequent flows. So in this then we give them another notification saying that Fi access points are only compatible with other Fi access points.  For a Wi-Fi access point to function as an extender, you need to have one functioning as a router. If needed, upgrade the router in your home. So, this is a generic notification because you might not have seen this, What if I okay, I have a old router and now I want to get an extender. So, I'm coming to this extender section, but I don't immediately know right that these new extenders are not compatible with my old routers. So, that's why we give them this info that okay, this functions as an extender.
Krithika Rajendran: And for this you already need to have one functioning as a router. so this is the extender section. And then these are the check out sections. home Wi-Fi router, then rent one Wi-Fi access point so we show all these things in the order summary. So in this one we always show what is removed and what is in added now. So this has been added now. One Wi-Fi access point has been added now.
Rahul Singh: H no no I don't have any doubts on
Krithika Rajendran: And this old one has Rent this thing has been removed. And then similarly on the last page on the confirmation page also it'll be like so the rest of the stuff is like bau wherever this things are there that's where it's changing. So this is the first scenario. Do you have any doubts so far? So now this is the second one.  In this thing, the person has the whole home Wi-Fi plus service. They have already two tend I have two extenders with me and I'm coming to upgrade my internet plan. So, I have this 500 right now. And I'm going to upgrade to 2 gig. So, I'm like okay, I want to change my speed. I'm upgrading to 2 gig.
Krithika Rajendran: So when they select this at this point itself we'll tell them that this 2 gig or whatever gig plans include a new Fi access point please return any Verizon router and Verizon Fi extenders to the nearest store blah blah blah the same stuff same okay so now okay fine I picked that plan now okay and now I'm at the internet router section so you also have to remember that so actually This might not be relevant for you.
Rahul Singh: Okay.
Krithika Rajendran: It's different for classic plans. But for 2 gig and 1 gig, whole home Wi-Fi is included. So whenever you show them selecting 2 gig or 1 gig, whole home Wi-Fi should show as included. But this might not be relevant for you. So don't think about that. I'm just telling you in general. So in this case, I have whole home Wi-Fi plus. I have picked this thing. I know that okay, my router is going to change. so we are showing them the old because I've changed my internet plan. So now we show them. So I told you right the whole home Wi-Fi plus there'll be a tile because they used to have it. they have a tile that shows the old info. It says up to three Verizon Fi extenders and all that. And this is the new so that both the tiles are labeled the same but the info is different. Okay. This says up to four Wi-Fi access points all that stuff.
00:15:00
Krithika Rajendran: So what happens because I've selected 2 gig. So when I open this router section this will be removed okay we have removed this now and this will be selected okay and…
Rahul Singh: H. Okay.
Krithika Rajendran: that we're telling them that this include a new WFi access point which is pre-selected please return any Verizon router so basically whatever service they had right we will select the same service suppose they had whole home Wi-Fi we'll pick whole home Wi-Fi if they had only rent only router we will pick that only Okay,…
Rahul Singh: Out of these three, any may be selected based on what they have selected previously in the internet speed section or based on their previous plan. Okay.
Krithika Rajendran: it's based on the previous plan. Okay, right now I have whole home Wi-Fi plus that means I have a router and I have two three extenders with me. So since you already had that service, we will by default the old whole home Wi-Fi will still show it will say removed.  and then the new whole home Wi-Fi plus will be selected. But if you want to change it you don't want this you can select any of the other ones if you're okay fine maybe I don't need those extenders anymore I can change it to rent Fi access point or I can change it to hold home Wi-Fi or whatever I want. Okay it's just that we are selecting based on the previous selection. so this thing and then we'll go to Fi extender section.
Krithika Rajendran: So in this section again like I said right because I have whole home WFi plus rent Fi access point is already selected for me okay and the previous one okay rent as Fi extender that was included this is removed okay so here we'll tell them that the new Fi access point requires whatever new Wi-Fi access point that function has extenders which you have please return any fires Fi extenders to the nearest available store since So once any of this is selected only then you'll see this subsequent section. Okay, that is how many Wi-Fi access points do you need? So you can pick one or two. So overall they can redeem up to three but at any given point of time they can only redeem two. Okay, so if I need three first I have to get two and then I'll get another one. Then I'll have to come once that gets delivered then I can request for another one.
Krithika Rajendran: So they can select whichever one they want and then again this will show in the thing we're showing whole home Wi-Fi plus.
Krithika Rajendran: So in the order summary we differentiate it like this is whole home Wi-Fi plus removed. This is whole home Wi-Fi plus and in brackets we say Wi-Fi access point and…
Rahul Singh: Yeah, this will also be followed in the classic flaws as well,…
Krithika Rajendran: then this is so These are all in this thing. I'm just showing the different things under each of the checkout sections. Yeah. Yeah.
Rahul Singh: right? the bracket thing the name because the names are same. We are using the Y function.
Krithika Rajendran: Yeah. The language the info on the tiles everything can be the same.
Rahul Singh: Okay.
Krithika Rajendran: And this in check out page and then similarly on confirmation page. So this is the second scenario. So then similarly just this is in this one. This is whole home Wi-Fi plus. so they have two extenders. more than one. Basically, this is when they have whole home Wi-Fi, which basically means they have one extender.
Krithika Rajendran: It's the exact same scenario, except that the number of extenders that this person has is different. And over here, whole home Wi-Fi is removed. We'll show whole home Wi-Fi is selected.
Rahul Singh: I just curious to know is there a chance that the user already had two extenders the other section right…
Rahul Singh: where we say removed right so can you zoom in onto that area maybe it's a dumb question I don't know just asking so has that there can be two tiles with removed.
Krithika Rajendran: Where here?
Rahul Singh: Yeah.
Krithika Rajendran: No. when you select this.
Rahul Singh: No. No. Not with Okay.
Krithika Rajendran: No, actually nothing really happens until you select one of this. So, it's like first you're telling them whether you want to rent a bike. all these things might seem a little weird and unintuitive but it's all things that they've had for a long time.
Krithika Rajendran: So the process to change that they will change it at some point but it's like going to take some more time.
00:20:00
Rahul Singh: Mhm. Yeah.
Krithika Rajendran: So this doesn't do anything. Once you select this you have to pick one one or two. So whether I had two extenders with me or whether I had one extenders with me we just show that this old one is removed and this is selected and now you which we would have selected based on so this person already had one right because they have home Wi-Fi plus whole home Wi-Fi. so we are already selecting one for them.
Krithika Rajendran: So this is selected and…
Rahul Singh: Yes.
Krithika Rajendran: then If you want one more then you you select this. So similarly in the previous one in whole home Wi-Fi plus two was already selected.
Rahul Singh: because that person had two.
Krithika Rajendran: Yeah. Yeah. Yeah. Yeah.
Rahul Singh: Okay.
Rahul Singh: This was the H.
Krithika Rajendran: We will select based on how many they had. And if they want to make any changes then they can. So these two scenarios are fairly similar only the number of extenders changes.  So then there could be a scenario the customer is using their own router. They have zero extenders. They want to update their internet plan. So in this case I have 2 gig no I have 500 Mbps. And then I'm selecting 2 gig. And then now in router section we'll tell them that you need a Fi access point for the internet plan you selected for the 2 gig internet plan. I need a Wi-Fi access point. And then we tell them if you need one you can rent it from us.
Krithika Rajendran: We don't know what router they have. No. So we just say…
Rahul Singh: Yeah. Yes.
Krithika Rajendran: if you need one you can rent it from us. So then the person has to so initially I suggested that we can have something like …
Rahul Singh: Correct.
Krithika Rajendran: because not everyone might know what router they have I might not even know whether I have a Wi-Fi access point or Not everyone is very router literate or whatever.  So I was telling them we can have something like check if my router is compatible or router compatibility or something which Monica liked that idea a lot but I don't think it's something that they can implement right now but maybe she was saying that after it goes live then we can implement it as an enhancement. this is use your own router. So, if they need to rent one from us, they can select a I know that I don't have this, I can choose to rent it from Verizon. in this case, so since the person now has selected this, this gets removed. Whenever you select something that other thing, it will show removed like this.
Krithika Rajendran: And there's no yeah I mean I was thinking have a yeah so in some of the cases in the previous ones and…
Rahul Singh: Yeah.
Krithika Rajendran: all right if suppose they have picked the new plan and then they come to the router section then we take away that CTA okay because they technically shouldn't be able to click it over there if they want then they have to go back and change their plan  That's the basic idea. but I'm thinking maybe for this one maybe we should have had the CTA so basically they have selected their new router and again they'll see this generic notification if they want any extender or something they can go and get that. and similarly in checkout we'll be mentioning those things. Okay.
Krithika Rajendran: So in this case customers using their own router which is a Wi-Fi access point and they want to get extenders. So this is selected they don't need to make any change. I'm like okay fine I already have my Wi-Fi access point so again they see this notification then I can pick rent and then I'll pick how muchever I want whether I want this or one or two or whatever and rest of the thing is the same. So that's all.
Rahul Singh: So much mainly the cases change based on the scenarios the time.
Krithika Rajendran: Yeah. Yeah. Yeah. Home Wi-Fi plus and whole home Wi-Fi are pretty much almost the same thing. Okay. it's just showing that one whatever this thing difference. So for yours also we'll see this classic flow, So in classic flow now the plans under classic flow will be different.  So maybe I'm not very sure because we have put only as a placeholder but I think it starts from 100 and I don't know till what it goes. so in that case maybe in classic I have 100 or something and I'm upgrading to a new higher speed. So I think at that point maybe Verizon will tell me that I need to upgrade my plan.
Krithika Rajendran: So basically your scenarios will probably be the same but I think you should get a little more details from Monica around so for classic plans right I think…
Rahul Singh: Yeah.
Krithika Rajendran: because I don't see it here but certain things you need to confirm with her see in our classic plans whatever we have seen there's no whole home Wi-Fi or no whole home Wi-Fi plus you can see here there are only three things so this is their existing router and this is okay one second fires quantum gateway router.  So classic plans know sometimes there what do you say this thing because there not that many credentials or it's not very clear even if you go to the production and check so whatever we have here might have been based on some screenshot but certain things I'm not sure here it says fires quantum gateway router and then over here maybe this is a better router I don't know and then there is rent only then there's own use your own is same as before and by var router is also
00:25:00
Krithika Rajendran: So this use your own router will stay the same. This buy Verizon router will change to buy Wi-Fi access point and probably you'll have a rent Fi access point. You just need to ask about this. I'm not sure of this things role. Maybe this is a error. Maybe both these are the same only maybe it's basically they mean rent router. So certain things you'll have to check with Monica. And then similarly under this Fi extender section pretty much works the same way.
Rahul Singh: Hurry up.
Krithika Rajendran: It says fires extender by. So you will have to change this to what we have and you add that notification also. And similarly it'll work the same way right when you click on you clicked on this then this thing will come up. So this portion and all will look the same but certain things you just need to check about maybe ask her if you can get a credential or something. so all your things will happen within these two sections. Okay or max maybe the speed section if you have to show them selecting some other plan whole home Wi-Fi but here we've seen whole home Fi some of these things might be so I'll tell you one more thing.
Krithika Rajendran: otherwise you'll get confused in certain places. It might be This is This should say internet router only. So it's always the main thing is on internet router, add Wi-Fi extender. If they don't have anything then Suppose I already have Fi extenders then it will say Fi extenders. It do not say add Wi-Fi extender. Okay. Yeah. Yeah. So, internet speed, internet router. so all these other ones also like this. This is basically so in certain places you might see some error but don't get confused. The correct way is that it should say internet router on okay.
Krithika Rajendran: So I mean always what it is should come on top what it is in the sense is it speed is it plan is it whatever router is it security and…
Rahul Singh: H. Yeah.
Krithika Rajendran: then what they have selected will come underneath okay internet and now this makes sense right internet router this is their router add Wi-Fi extender choose your extender internet speed gigabyte okay so I think two three things you have to clarify with Monica one what are the plans that will come under classic plans what are its speeds okay  And secondly is it like if I make any change to my internet plan basically in all those cases are we giving them Fi access point maybe in some cases maybe I'm having 500 and I'm downgrading to 100 in that case also will we give them Fi access point or how will it be and then what exactly are the things that will come under internet router section I think once you have these things clear right then you can just more or less replicate whatever scenarios
Krithika Rajendran: I had similar things because those same kind of situations only will come up right in fact suppose they don't have whole home Wi-Fi and whole home Wi-Fi plus then you don't even have these two you don't have to think about you have to then more cater using your own router and the other one that is this rent only router you have to just show those scenarios on so it should be fine and in terms of the checkout and things like that
Krithika Rajendran: So yeah so I think in classic flows so they have one more thing that is like an agreement or something but you don't need to show all this okay you can just show what has been changed and then in the checkout page again this is actually even now because I did this a long time ago this is the older checkout thing so for our thing also wait let me tag you in  that. So, we have a new checkout experience. Okay, let me check. Hey
00:30:00
Prasad Boominathan: Another call just got over. So, just joined.
Prasad Boominathan: Yeah. …
Krithika Rajendran: Hey, do you know…
Krithika Rajendran: where I can find the new check out page?
Prasad Boominathan: new check out in the titlement.
Krithika Rajendran: Yeah,…
Prasad Boominathan: Should be so there was a new announcement we created
Krithika Rajendran: tile enhancement I think. Did we do it in a new file? so I took Rahul through what the Wi-Fi access point for the regular flow and then I was just showing him…
Krithika Rajendran: how the classic flow looks and I was just telling him that so I was a few things like I have also forgotten or…
Prasad Boominathan: For classic I think it's 300 100 300 and…
Krithika Rajendran: I don't really remember under classic flow what are the planned speeds They'll have 100,…
Prasad Boominathan: 500. …
Krithika Rajendran: 300, and 500. Yeah.
Prasad Boominathan: but again there are some grandfather plans …
Krithika Rajendran: Yeah. Yeah.
Prasad Boominathan: which was way low so just keep it dynamic there but I won't suggest to have some concrete plans unless we get something from business
Krithika Rajendran: 
Krithika Rajendran: I was telling him to check because I don't think there's nothing specific about classic plans on the Fi access point deck. So I was asking him to check with Monica whether they make any change in their plan
Krithika Rajendran: what if I have 500 and I'm downgrading to 100. So in that case also will we make them change their router to Wi-Fi access point.
Prasad Boominathan: So the routers I think it's going to be a common upgrade for all the plans should be correct.
Krithika Rajendran: Even so whatever I change my plan to I'll be getting a new router basically. and with this one also I was thinking under this we are showing this four things but I'm wondering will this one also be there and this is like some maybe we have Okay.
Prasad Boominathan: So the quantum router is b basically that old router which they had as part of the classic plans.
Prasad Boominathan: So probably with access point I think there will be a new routing router that is going to be updated.
Krithika Rajendran: Okay.
Krithika Rajendran: Yeah. Yeah.
Prasad Boominathan: Yeah. yeah,…
Krithika Rajendran: So, Rahul, you got it now. So, this one is their old router.
Krithika Rajendran: So, this rent only. it will say rent Wi-Fi access point.
Rahul Singh: I change the name as well for this or…
Rahul Singh: will it remain rent Okay.
Krithika Rajendran: No, you can change the name. So, you can have whatever I have over here, even in terms of the info and stuff. So, rent Fi access point functions as a router and all that. And Prasad for this thing, they don't have a whole home Wi-Fi plus, right? Classic plans don't have that.
Prasad Boominathan: that's what I got. but Rahul, you can check with Ain or…
Krithika Rajendran: Yeah. Yeah.
Prasad Boominathan: Monica on just double confirm on this.
Rahul Singh: I'll basically check with her what the contents of internet router so what will be the placement and what is the content there what are the tiles that going Okay.
Prasad Boominathan: So the tile should be like whatever Kika has done so that he can reduce but only thing is the holo Wi-Fi and holo plus
Krithika Rajendran: Yeah. What did Yeah.
Krithika Rajendran: And this also similarly you'll have two tiles that say rent Fi access point by Wi-Fi access point.  And if they already had an extender or something, you'll have to show that and show that as removed. Whenever you get confused, you can just refer to this regular flow or you can ping me.
Rahul Singh: I'll I'll create something that I have understood. I'll share the file with you. and we'll see if it is going in the right direction.
Rahul Singh: Meanwhile, I'll also ping from the tiles.
Krithika Rajendran: Monica. Yeah.
Rahul Singh: Yeah. the tiles and the internet sections just to be sure.
Krithika Rajendran: Yeah. Yeah.
Rahul Singh: Okay. Yeah.
Krithika Rajendran: Just make a list of whatever questions you have so you don't forget. And yeah.
Prasad Boominathan: critica that check out page which you asked so that is a title and all right I think it's on the project midnight file I'll tag you both Rahul and…
Krithika Rajendran: H. Yeah.
Prasad Boominathan: I think with the latest launch the style and…
Krithika Rajendran: So when Rahul is doing these flows for the checkout page, should he use this one the latest one or should he use what was there earlier only the old check out like this only?
00:35:00
Prasad Boominathan: all it got updated so that's what I got from Nandon…
Krithika Rajendran: Okay. Yeah.
Prasad Boominathan: but probably this also you can check with Monica once so whether to update on the latest one or…
Krithika Rajendran: Yeah. Yeah.
Prasad Boominathan: the new type versions …
Rahul Singh: Quite a few questions I will have to write.
Rahul Singh: Okay. Yeah.
Prasad Boominathan: I think we have answers,…
Rahul Singh: Yeah. It makes sense.
Prasad Boominathan: but just to be on a safer side.
Rahul Singh: Otherwise, the effort will be twice if I don't Yeah.
Prasad Boominathan: Yeah. Yeah, that's Rahul,…
Krithika Rajendran: Just clarify those things and then you can start. Yeah, sure.
Rahul Singh: Can you tag me on in these files? Thank you.
Krithika Rajendran: Over here.
Prasad Boominathan: I just pasted a link on the chat. So, this will point you to the classic flow, the latest one. Whatever the tile management which we have done. So can use that.
Prasad Boominathan: 
Rahul Singh: I'll save the link here.
Krithika Rajendran: Okay. You have any other doubt?
Rahul Singh: Thank you.
Prasad Boominathan: 
Prasad Boominathan: Thank you.
Rahul Singh: I have Yes.
Rahul Singh: Thank you everyone. I may have doubts so I may reach out again. So yeah.
Krithika Rajendran: That's fine. Reach out whenever you need help.
Prasad Boominathan: Yeah. Thank you. Bye-bye.
Rahul Singh: Thank you everyone.
Krithika Rajendran: Okay, thanks.
Meeting ended after 00:37:07 👋
This editable transcript was computer generated and might contain errors. People can also change the text after it was created.

