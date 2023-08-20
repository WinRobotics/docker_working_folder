FROM osrf/ros:noetic-desktop-full-focal

RUN apt-get install
RUN apt-get update
RUN apt-get install -y git && apt-get install -y python3-pip
RUN echo "Git and Python 3 installed"
WORKDIR /rtabmap/build
RUN cmake ..
RUN make && sudo make install

