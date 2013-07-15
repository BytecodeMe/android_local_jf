android_local_jf
================

Local manifest to port CM-10.1 based ROMs to American variants of the SGS4

To initialize your local repository using the Cyanogemod manifest, use commands like these:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-10.1

    curl -L -o .repo/local_manifests/jflte.xml -O -L https://raw.github.com/BytecodeMe/android_local_jf/cm-10.1/android_local_jf.xml
 
    	( or Download: https://github.com/BytecodeMe/android_local_jf/blob/cm-10.1/android_local_jf.xml
		and place it in ~/Android/.repo/local_manifest.xml (or ~/'name you chose'/.repo)

