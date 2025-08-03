# NeuroVision
NeuroVision is a cutting-edge AI project that aims to generate photorealistic 3D views of scenes or objects using only a single or few 2D images as input. By leveraging Neural Radiance Fields (NeRF) and its real-time optimized variants like Instant-NGP, along with advanced depth estimation (via MiDaS) and camera pose estimation (via COLMAP), the system learns to synthesize new viewpoints of the scene even ones it has never seen before.
The core idea is to reconstruct a 3D scene not through traditional mesh modeling or scanning, but through a learned neural function that maps 3D space and viewing angles to color and density. This allows the system to hallucinate realistic and dynamic perspectives of the input image, producing a seamless 3D experience. An interactive WebGL or Streamlit-based viewer allows users to rotate, zoom, and explore the generated 3D environment in real time.
NeuroVision lies at the intersection of Artificial Intelligence, Computer Vision, and Graphics, and tackles an active research problem with vast real-world applications in:
• Augmented & Virtual Reality (AR/VR)
• Virtual Try-on Systems
• Game Asset Generation
• Digital Product Visualization
• Cnematic Content Creation

This project is designed to push the boundaries of what's possible with limited visual data, opening doors for lightweight 3D content generation without the need for expensive equipment or multi-view camera rigs. It is an in-house applied research project that reflects both academic rigor and industry relevance.
