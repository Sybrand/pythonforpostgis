# It compiles, but I've not tested it!
#FROM centos/python-36-centos7
FROM python:3.6
USER 0

RUN curl -o gdal-2.4.0.tar.gz http://download.osgeo.org/gdal/2.4.0/gdal-2.4.0.tar.gz

RUN tar xzf gdal-2.4.0.tar.gz && \
    cd gdal-2.4.0 && \
    ./configure && \
    make && \
    make install
