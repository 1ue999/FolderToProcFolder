# FolderToProcFolder
Converts a folder of pictures of a video into another folder, which contains a few .txt things

To get a video ready for processing:

1st:
  Get "release.zip" from the newest release and unpack it.

2nd:
  put your video into the "data" folder

3rd: 
  Run these commands (ffmpeg is reqired, but i am too lazy to get a install guide)
  ```ffmpeg -i <insertVideoname.mp4> -vf "scale=128:72,format=gray,fps=30" output_%06d.png```
