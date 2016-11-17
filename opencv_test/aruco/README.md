ArUco Marker Detection
======================
In the sample folder which contains .cpp files: g++ -o test detect_markers.cpp `pkg-config opencv --cflags --libs`

Command line parser: ./test -d=16 -l=0.21 -c=./out_camera_data.xml