**Custom music for Replika AI (not relevant for versions V7 and above)**

Yes, you can add it! But there's one thing, **you'll need root access in Android**. If you don't have Magisk or KSU/KSU-next installed, most likely it wouldn't work for you.

Structure of Replika app works in this way, so in common app have 5 ambient BGM tracks. 4 of them exists cached and probably being downloaded with 3D model and data. They're being played in random way strictly after 1 track. We'll need 4 of these tracks.

Here is an example of how folder looks like ([Google Drive](https://drive.google.com/uc?id=1yr2M4GKu9tUcR7Abr5SZJd_7L9YelklT&export=download)), go to the path /data_mirror/data_ce/null/0/ai.replika.app/cache/music, then check out of track names is same as names of tracks in example. If you want just to test and names is same, copy everything in that folder on that path by replacing files. Then just reopen Replika app and wait. In this way you can put anything you want, including some kind of music playlists from YouTube.

----

**Not working or app doesn't play anything**
Make sure what you don't have silent volume mode turned on in Android. If this won't work either, download Root explorer, open folder in that path and give permission 755 or 775 to all tracks inside it. This should fix your issues.
