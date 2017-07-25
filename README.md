# custom-jabber-emoticons

Installation
------------

Custom emoticons for the team. To install these, go to `C:\Program Files (x86)\Cisco Systems\Cisco Jabber` , 
backup the Emoticons directory and then delete it.

Then run `cd "C:\Program Files (x86)\Cisco Systems\Cisco Jabber" ;git clone https://github.com/tcfbank/custom-jabber-emoticons.git Emoticons` in powershell.

Then restart Jabber

Adding an emoticon
------------------
Add the new emoticon , which can be a png or even an animated gif , to the repo.For this example, let the name be `imagename.gif`. The ideal dimensions are 17x17 pixels

Edit the `emoticonDefs.xml` file and add the below block between the `<emoticons> </emoticons>` tag
```
<emoticon defaultKey="(iconName)" image="imagename.gif" text="icon name" order="33">
	 <alt>(IconName)</alt>
  </emoticon>
```

Restart Jabber and confirm that it works. Commit and push your changes to this repo.

Preview
-------

- all the things: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/allthethings.png)
- Android: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/android.png)
- are you kidding me: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/areyoukiddingme.png)
- aw thanks: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/awthanks.png)
- aw yea: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/awyea.png)
- bad ass: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/badass.png)
- bad poker face: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/badpokerface.png)
- basket: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/basket.png)
- Bluetooth: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/bluetooth.png)
- boom: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/boom.gif) GIF
- bug: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/bug.gif) GIF
- bumble: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/bumble.png)
- bunny: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/bunny.png)
- Cadbury: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/cadbury.png)
- candy corn: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/candycorn.png)
- Caruso: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/caruso.png)
- ceiling cat: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/ceilingcat.png)
- cereal guy: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/cerealguy.png)
- challenge accepted: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/challengeaccepted.png)
- chewy: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/chewy.png)
- choco bunny: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/chocobunny.png)
- cholo: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/cholo.gif) GIF
- chompy: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/chompy.gif) GIF
- content: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/content.png)
- Cornelius: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/cornelius.png)
- dance: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/dance.gif) GIF
- deal with it: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/dealwithit.gif) GIF
- derp: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/derp.png)
- disapproval: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/disapproval.png)
- dosequis: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/dosequis.png)
- Dr. Evil: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/drevil.png)
- Ducreux: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/ducreux.png)
- dumb bitch: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/dumbbitch.png)
- dunno: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/dunno.gif) GIF
- face punch: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/face-punch.gif) GIF
- face palm: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/facepalm.png)
- fap: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/fap.png)
- Farnsworth: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/farnsworth.png)
- forever alone: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/foreveralone.png)
- freddie: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/freddie.png)
- fry: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/fry.png)
- fuck yeah: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/fuckyeah.png)
- gates: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/gates.png)
- green beer: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/greenbeer.png)
- GTFO: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/gtfo.png)
- happy hour: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/happyhour.gif) GIF
- have a seat: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/haveaseat.png)
- I lied: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/ilied.png)
- indeed: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/indeed.png)
- it's a trap: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/itsatrap.png)
- Jackie: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/jackie.png)
- Jobs: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/jobs.png)
- Kenny Powers: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/kennypowers.png)
- knock: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/knock.gif) GIF
- Krang: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/krang.gif) GIF
- Kwanzaa: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/kwanzaa.png)
- Lincoln: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/lincoln.png)
- LOL: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/LOL.png)
- lol old: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/lolold.png)
- lol wut: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/lolwut.png)
- me gusta: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/megusta.png)
- menorah: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/menorah.png)
- mind blown: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/mindblown.gif) GIF
- not bad: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/notbad.png)
- nothing to do here: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/nothingtodohere.png)
- oh god why: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/ohgodwhy.jpeg) JPEG
- oh crap: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/ohcrap.png)
- okay: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/okay.png)
- OMG: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/omg.png)
- PBR: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/pbr.png)
- philosoraptor: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/philosoraptor.png)
- ping-pong: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/pingpong.png)
- poker face: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/pokerface.png)
- present new: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/presentnew.png)
- pumpkin: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/pumpkin.png)
- rage guy: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/rageguy.png)
- Rebecca black: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/rebeccablack.png)
- Reddit: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/reddit.png)
- Rudolph: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/rudolph.png)
- sad panda: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/sadpanda.png)
- sad troll: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/sadtroll.png)
- Samuel: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/samuel.png)
- Santa: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/santa.png)
- scumbag: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/scumbag.png)
- Skyrim: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/skyrim.png)
- SOS: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/sos.gif) GIF
- stare: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/stare.png)
- sticking out tongue: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/sticking_out_tongue.png)
- sweet Jesus: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/sweetjesus.png)
- taft: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/taft.png)
- troll: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/troll.png)
- truestory: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/truestory.png)
- Washington: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/washington.png)
- wat: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/wat.png)
- WTF: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/wtf.png)
- yey: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/yey.png)
- yo dawg: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/yodawg.png)
- Y U no: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/yuno.png)
- Zoidberg: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/zoidberg.png)

Default
-------

- angel: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/angel.png)
- angry: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/angry.png)
- beer: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/beer.png)
- big surprise: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/bigsurprise.png)
- blank: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/blank.png)
- blush: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/blush.png)
- broken heart: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/brokenheart.png)
- cake: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/cake.png)
- call me: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/callme.png)
- closed to the world: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/closed_to_the_world.png)
- coffee: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/coffee.png)
- cool: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/cool.png)
- crazy: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/crazy.png)
- crying laugh: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/crying-laugh.png)
- crying: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/crying.png)
- dazed: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/dazed.png)
- dead: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/dead.png)
- disaproval: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/disaproval.png)
- egg: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/egg.png)
- drink: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/drink.png)
- duck: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/duck.png)
- fist: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/fist.png)
- ghost: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/ghost.png)
- grin: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/grin.png)
- heart: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/heart.png)
- hover: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/hoverBk.gif) GIF
- Kevin: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/kevin.png)
- kiss: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/kiss.png)
- love at first sight: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/love-at-first-sight.png)
- money mouth: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/moneymouth.png)
- nerd: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/nerd.png)
- ninja: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/ninja.png)
- OK: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/OK.png)
- oops: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/oops.png)
- parcel: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/Parcel.png)
- peace: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/peace.png)
- point-down: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/Point-down.png)
- point-left: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/Point-left.png)
- point-right: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/Point-right.png)
- point-up: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/Point-up.png)
- poo: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/poo.png)
- present: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/present.png)
- rock on: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/rock-on.png)
- sad: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/sad.png)
- secret: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/secret.png)
- shamrock: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/shamrock.png)
- sick: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/sick.png)
- sleep: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/sleep.png)
- sleepy: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/sleepy.png)
- smile: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/smile.png)
- spechless: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/spechless.png)
- Spock-on: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/spockon.png)
- star: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/star.png)
- surprised: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/surprised.png)
- tea: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/tea.png)
- thumbs-down: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/thumbs-down.png)
- thumbs-up: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/thumbs-up.png)
- tongue: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/tongue.png)
- tree: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/tree.png)
- turkey: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/turkey.png)
- undecided: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/undecided.png)
- unemotional: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/unemotional.png)
- unimpressed: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/unimpressed.png)
- upset: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/upset.png)
- wink: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/wink.png)
- worried: ![](https://rawgit.com/amithKrishnan/custom-jabber-emoticons/master/worried.png)
