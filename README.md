# pipeline-log-files-generate
this repository contains all the logs generation info

Gstreamer framework is used to develop media elements and audio elements to perform media operations. This code is developed to generate the required debug logs and graphical representation of dot file in current working directory. By using this information we can able to analyse the pipeline. In this code the predefined macros i.e., debug and graphviz are generated by using gstreamer framework.

$GST_DEBUG=*:6 gst-launch-1.0 videotestsrc ! videoconvert ! autovideosink
