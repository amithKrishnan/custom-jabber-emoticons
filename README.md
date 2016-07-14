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

