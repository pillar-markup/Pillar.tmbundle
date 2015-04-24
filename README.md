###Textmate Installation:

* Download the `Pillar.tmbundle.zip` from the [latest release](https://github.com/pillar-markup/Pillar.tmbundle/releases/latest).
* Unzip.
* Double click on a bundle file to install it.
* Open TextMate preferences and add these 2 shell variables :
	- PHARO_VM that gives the absolute path to the PharoVM
		Example: /Users/bob/Pharo/VirtualMachines/pharo
	- PILLAR_IMAGE that gives the absolute path to the image to use for processing Pillar files
		Example: /Users/bob/Repositories/PharoBooks/BookSkeleton.git/Pharo.image

###Developer installation 

	cd ~/Library/Application\ Support/Avian/Bundles
	git clone https://github.com/pillar-markup/Pillar.tmbundle 

You can then easily benefit from new updates by doing:
	 
	 cd ~/Library/Application\ Support/Avian/Bundles 
	 git pull
