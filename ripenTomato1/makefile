takedata : takephoto
	while true; do takephoto; sleep 1;done 

takephoto : currentTime
	raspistill -o $(time).jpg

currentTime : 
	export time="$(date +"%F_%T")"
