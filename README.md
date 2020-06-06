[![Build status](https://travis-ci.org/mpromonet/v4l2onvif.png)](https://travis-ci.org/mpromonet/v4l2onvif)
[![CirusCI](https://api.cirrus-ci.com/github/mpromonet/v4l2onvif.svg)](https://cirrus-ci.com/github/mpromonet/v4l2onvif)
[![Snap Status](https://build.snapcraft.io/badge/mpromonet/v4l2onvif.svg)](https://build.snapcraft.io/user/mpromonet/v4l2onvif)
[![C/C++ CI](https://github.com/mpromonet/v4l2onvif/workflows/C/C++%20CI/badge.svg)](https://github.com/mpromonet/v4l2onvif/actions)

[![Docker Pulls](https://img.shields.io/docker/pulls/mpromonet/v4l2onvif.svg)](https://hub.docker.com/r/mpromonet/v4l2onvif/)

# v4l2-onvif

   It is a try to implements an ONVIF server :
   
   * for V4L2 capture devices (NVT/NVS),
   * for V4L2 output devices (NVD).
   
   The web services data binding is generated using [gSOAP](http://www.genivia.com/).

## Build

    make 

## Usage

    onvif-server.exe [-u username] [-p password] [-i v4l2 input device] [-o v4l2 output device]
