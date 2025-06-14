GenCheck is a multi-modal content verification platform designed to detect whether a given text, image, or video is AI-generated or human-created. With the rapid rise of generative AI tools like ChatGPT, DALL·E, Midjourney, and deepfake generators, GenCheck aims to bring transparency and trust back to digital content.

The tool targets academic institutions, media companies, hiring platforms, and individual users who need to verify the authenticity of the content they consume or receive.

🎯 Project Goals:
Build a reliable detection system for text, image, and video content using AI/ML-based techniques.

Provide confidence scores and insights into why a piece of content is likely AI-generated.

Support common file types and seamless user experience for uploading, analyzing, and receiving results.

Offer a modular architecture for easy extension (e.g., audio detection, document metadata forensics).

Educate users on content manipulation and generative AI ethics via clear, explainable results.

🧩 Key Functionalities:
🔠 Text Analysis Module:
Detects AI-generated content (e.g., ChatGPT, GPT-3/4)

Outputs confidence score and explains decision (e.g., low burstiness, predictable structure)

Supports plain text, PDFs, and DOCX

🖼️ Image Analysis Module:
Identifies AI-generated images (e.g., DALL·E, Midjourney, Stable Diffusion)

Highlights visual anomalies or forensic artifacts

Parses metadata (EXIF) for tampering or absence of camera signatures

🎞️ Video Analysis Module:
Detects deepfake or AI-manipulated videos

Analyzes face landmarks, blinking frequency, lip-sync accuracy

Frame-by-frame anomaly detection

📊 Report Dashboard:
Unified result view with detection status (Human / AI-generated)

Confidence percentages and indicators

History log for past analyses (per user/session)

🔐 Optional Features:
User authentication (for saved histories)

API access for integration with third-party platforms

Exportable detection reports (PDF format)
