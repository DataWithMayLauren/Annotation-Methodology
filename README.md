# Annotation & Data Quality Standards

Since most of my professional work is under NDA, this repository outlines my technical approach to ensuring high-quality data for AI models.

### 🌍 Lidar & 3D Cuboids
- **Precision:** I focus on tight-fitting cuboids with zero-margin error on the ground plane.
- **Temporal Consistency:** Ensuring object IDs remain consistent across frames in point cloud sequences.
- **Attributes:** Experienced in tagging occlusion levels and activity states.

### 🖼 2D Semantic Segmentation
- **Pixel-Perfect Borders:** I use high-magnification for polyline placement to ensure no background leakage.
- **Complexity:** Capable of handling dense urban scenes with 50+ overlapping instances.

### 🛠 Tools I'm Familiar With
- **Platforms:** CVAT, Labelbox, Scale AI, LidarLite.
- **Office:** Advanced Excel/Google Sheets for bookkeeping and data tracking.
