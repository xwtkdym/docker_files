FROM ubuntu:18.04
ENV PATH="/opt/depot_tools:$PATH"
RUN apt-get -y update && \
	apt-get -y install git wget curl && \
	git clone https://chromium.googlesource.com/chromium/tools/depot_tools.git /opt/depot_tools && \
	rm -rf /var/lib/{apt,dpkg,cache,log}/
