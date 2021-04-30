FROM therecipe/qt:windows_64_static
MAINTAINER Dale Farnsworth

RUN apt-get update \
    && apt-get -y install libusb-1.0 wget

RUN cd /usr/lib/mxe/usr/x86_64-w64-mingw32.static/lib && \
	wget https://www.farnsworth.org/dale/libusb-1.0.a
