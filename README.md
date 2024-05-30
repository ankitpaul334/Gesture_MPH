Media Pipe Holistics - used to analyse the body action, poses, gestures from video streams
pose- detect and track human key points (joints, limbs real time)
hand- track gestures and recognize hand poses
face- detect face features (eyes,nose,mouth) emotion detection

import drawing_utils module from solutions. func help visualize output of media pipe by draw landmarks,connections in image or video frame.
import holistics module from solutions. integrate pose,face,hand trackinginto single model. detect key points on face,hands etc.
creates a drawing_spec object, which tells how to draw certain objects(line,points) on image; representing blue color (0,0,255)-RGB; thickness of line and radius.

call draw_landmarks module from mp_drawing, retrieve documents.
draws landmarks and connections for the face. 

image: The image or frame on which to draw.
results.face_landmarks: Detected face landmarks.
mp_holistic.FACE_CONNECTIONS: Face connections to be drawn between landmarks.
Two DrawingSpec objects specifying how to draw landmarks and connections for the face. 
Landmark - green color (80,110,10), thickness 1, and radius 1
Connections between landmarks - pink color (80,256,121), thickness 1, and radius 1.
