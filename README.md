# leaflet-tiles
矢量/栅格切片

```
geoserver+leaflet

EPSG:4326   (大地坐标系，单位：度)->WGS84       # EPSG(欧洲石油调查组织),适合GPS卫星定位
EPSG:3857   (投影坐标系，单位：米)->WGS900913   # 伪墨卡托投影,高纬度地区形变的非常严重
EPSG:4527  （投影坐标系，单位：米)->CGCS2000    # 高斯克吕格投影，中国地区偏移较少

矢量切片（渲染模式/切片模式）（wmts或tms）
渲染模式：pdf/geojson
切片模式：png(透明)/jpg        # leaflet默认坐标系EPSG:3857，使用udig编辑相关样式即可

栅格切片：png                  # tms
```
