# mpv-ytdl-preload
## Mpv script to preload your stream playlist by downloading it as a temp file (support onedrive-index)  
Work for onedrive-index, you can just drag and drop the direct link to mpv and it will preload it as a queue as much as you want  

Edit the script to ur liking,  

**trusted_domains** for onedrive-index domain because onedrive file always end as .aspx extension  

**preload_limit** is how many files you want to preload, it will automatically delete the previous temp if u exceed the limit (only if u already watched it from the playlist queue) and will keep on preloading until your playlist end  

**cache_path & temp** "D:\\MPV Player\\Temp" replace this dir to your own directory, make sure it's exist
