# Video Milestone Reached

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "video_progress",
  "detailed_event": "Video Milestone Reached",
    "event_data": {
        "identifier": "<identifier>",
        "type": "<type>",
        "video_milestones_reached": <video_milestones_reached>,
        "video_percent": "<video_percent>",
        "video_title": "<video_title>",
        "video_topic": "<video_topic>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.identifier|string|Captures the ID of video content viewed by visitor.|YT456789, BC4567890, 876546789|||||||
|event_data.type|string|Captures the type of video viewed.||||||||
|event_data.video_milestones_reached|integer|Count of video milestones reached \(25%, 50%, 75%\).||||||||
|event_data.video_percent|string|Captures the milestone \(25%, 50%, 75%\) reached when viewing a video.|25, 50, 77, 99|||||||
|event_data.video_title|string|Captures the Name of video content viewed by visitor.|Twitch\_FPS, Age of Empires, Halo|||||||
|event_data.video_topic|string|The topic of the video.||||||||




