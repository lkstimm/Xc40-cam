# xc40-cam

Phone camera page for the **Hello XC40** Android Automotive app.

Open it by scanning the QR code shown in the car. The page streams JPEG frames from the phone camera, encrypted with AES-GCM (the key travels only inside the QR code's URL fragment, never to a server), over a public MQTT broker to the car, where Depth Anything V2 Small turns them into a live point cloud.
