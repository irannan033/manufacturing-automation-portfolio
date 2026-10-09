# Video-Based Worker Capacity Analytics

**Focus:** Computer vision · Manufacturing analytics  
**Tools:** Python, OpenCV, Ultralytics YOLO

## Objective
Explore video-based measurement of work activity in a production process, including counting inspected panels and identifying idle periods or periods when the worker is outside the camera view.

## Current development direction
- Read video and extract frames for inspection and labeling.
- Prepare a dataset focused on the panel objects needed for counting.
- Experiment with object detection and frame-by-frame tracking/counting.
- Plan a dashboard that can present real-time indicators and historical trends.

## Metrics to explore
- Panels processed within a time window.
- Count consistency and missed/duplicate detections.
- Idle intervals and out-of-view intervals, with careful interpretation.
- Comparison between automated counts and a manually verified sample.

## Important limitation
Video-based counts are estimates and require validation under real camera angles, occlusion, lighting, and process variation. The system should not be treated as a definitive worker-performance measure without transparent rules and appropriate human review.
