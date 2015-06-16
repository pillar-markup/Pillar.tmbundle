###Textmate Installation:

* Download the `Pillar.tmbundle.zip` from the [latest release](https://github.com/pillar-markup/Pillar.tmbundle/releases/latest).
* Unzip.
* Double click on a bundle file to install it.
* Open TextMate preferences and add these 2 shell variables :
	- PHARO_VM that gives the absolute path to the PharoVM binary (not the .app folder)
		Example: /Applications/Pharo.app/Contents/MacOS/Pharo
	- PILLAR_IMAGE that gives the absolute path to the image to use for processing Pillar files. This image must have Pillar loaded (cf. [Pillar documentation](https://github.com/pillar-markup/pillar-documentation))
		Example: /Users/bob/Repositories/PharoBooks/BookSkeleton.git/Pharo.image
		

###Developer installation 

	cd ~/Library/Application\ Support/Avian/Bundles
	git clone https://github.com/pillar-markup/Pillar.tmbundle 

You can then easily benefit from new updates by doing:
	 
	 cd ~/Library/Application\ Support/Avian/Bundles 
	 git pull
