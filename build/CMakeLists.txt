cmake_minimum_required (VERSION 2.6)

project(GameSpySDK C)
set_property(GLOBAL PROPERTY USE_FOLDERS ON)


ADD_DEFINITIONS(-DGSI_DOMAIN_NAME="openspy.net")
if(UNIX)
    ADD_DEFINITIONS(-D_LINUX)
endif()
ADD_DEFINITIONS(-DGSI_COMMON_DEBUG -D_DEBUG)




include("common.txt")
include("pinger.txt")
include("natneg.txt")
include("qr2.txt")
include("serverbrowsing.txt")
include("chat.txt")
include("Peer.txt")
include("gt2.txt")
include("GP.txt")
include("ghttp.txt")
include("webservices.txt")