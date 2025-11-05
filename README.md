# WebVR Experiments with YouTube

### **Description / Rationale**
This is a project, consisting of several YouTube related experiments. They show the possibilities of web VR in streaming YouTube videos. In particular the following are available:
1. Streaming simple Youtube videos directly into web VR with Invidious API (updated 2025-11-05). See: index.html.
2. Streaming 360 Youtube videos (when compatible) into web VR with the help of Youtube to HTML5 Loader. See: Yotube360video.html.
3. Streaming simple Youtube videos and removing their chroma key backgrounds. See: YoutubeChromaKey.html.
4. Streaming Youtube videos using CSS3D made available through <a href="https://github.com/ryota-mitarai/aframe-websurfaces">AFrame Websurfaces component</a>. Please note that it does not support VR mode. See: YoutubeWebSurfaces.html.

### **Instructions**
To see the project at work just copy the repository to your local server and explore all the functionality. For reference, please see the code or original components/repositories. To open other experiments on Glitch.com, just add html page after the main URL.

### **Tech Stack**
The project is powered by AFrame.

### **Recent Updates (2025-11-05)**
- **Fixed YouTube video loading errors** in index.html
- Replaced broken yt2html5.com API with Invidious (open-source YouTube frontend)
- Implemented multiple fallback Invidious instances for reliability
- Added proper error handling and user feedback
- Fixed null reference errors in video extraction
- Added loading indicator for better UX

### **Known Issues & Limitations**
- Age-restricted videos may not work
- Private or unlisted videos will fail to load
- Some videos may be geo-blocked
- Invidious instances may occasionally be down (automatic fallback handles this)

### **Troubleshooting**
If you see "Failed to load video from all sources":
1. Ensure the video is public and not age-restricted
2. Try a different video
3. Wait a few minutes and retry (Invidious instances may be temporarily busy)

### **Disclaimer**
This project was created to show possibilities of webVR in streaming videos from Youtube and is intended for experimentation purposes only!
