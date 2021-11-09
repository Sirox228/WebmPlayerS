# WebmPlayerS
my webm player that i created, idk why i do this, but ok

# Integration to source code
just make all like usual but install my edited extension-webm
haxelib remove extension-webm
haxelib git extension-webm https://github.com/Sirox228/extension-webm
and put player file into the source code

# example of usage
var video = new WebmPlayerS("assets/videos/vid.webm", true, true, -1, null, null, null, null);
video.startcallback = () -> {
ForExampleThisIsFunction(ok, scam, idk, 19383, 29920w);
}
video.endcallback = () -> {
remove(video);
}
video.updateHitbox();
add(video);
video.play();

P.S. for know what new WebmPlayerS parametrs are doing, check parameters name in player file
