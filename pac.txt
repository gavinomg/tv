[
  {
    "outboundTag": "proxy",
    "domain": [
      "domain:example.com",
      "domain:example2.com"
    ]
  },
  {
    "type": "field",
    "outboundTag": "block",
    "domain": [
      "geosite:category-ads-all"
    ]
  },
  {
    "type": "field",
    "outboundTag": "proxy",
    "domain": [
      "geosite:gfw",
      "geosite:greatfire",
      "geosite:tld-!cn",
      "geosite:geolocation-!cn"
    ]
  },
  {
    "type": "field",
    "port": "0-65535",
    "outboundTag": "direct"
  }
]
