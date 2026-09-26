# video-server

We build a local video production system that brings project planning, AI generation, review, and final delivery into one workflow.

## What it does

1. Organizes video projects, scenes, characters, and reference assets.
2. Generates scene keyframes and video clips with ComfyUI and local models.
3. Stores generation versions and settings for review and approval.
4. Combines approved clips into a final MP4 with FFmpeg.

## Components

| Component | Role |
| --- | --- |
| Hermes Video Server | Studio interface, API, project data, jobs, and delivery |
| ComfyUI | Image and video generation workflows |
| Hermes Deployment | Local services, monitoring, and operations |

The current installation runs locally. Development repositories are private and are not visible to visitors outside the organization.
