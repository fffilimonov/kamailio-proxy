# kamailio-proxy
simple sip-proxy

All local parameters at kamailio-local.cfg.
Online changing local.uablock = "sipcli|scanner|VaxSIPUserAgent"

kamcmd cfg.set_now_string local uablock "sipcli|scanner|VaxSIPUserAgent|SIPp"
kamcmd cfg.get local uablock
