

| Tests   |      location      |  scale |shape |
|:----------:|:-------------|:------|:------|
| test52 |  ~ te(lon, lat,air, k=c(5,5,5,5)) | ~ te(lon, lat,air, k=c(5,5,5,5)) | ~1|
| test53 1|  ~  te(lon, lat,k=c(1,1)) | ~  te(lon, lat,k=c(1,1)) | ~1|
| test53 2|  ~  te(lon, lat,k=c(5,5)) | ~  te(lon, lat,k=c(5,5)) | ~1|
| test54  |  ~  te(lon, lat,k=c(5,5)) | ~  te(lon, lat,k=c(5,5)) | ~1|
|          |  + s(air,bs='cr')        |                          | |
| test55  |  ~  te(lon, lat,k=c(5,5)) | ~  te(lon, lat,k=c(3,3)) | ~te(lon, lat,k=c(3,3))|
|          |  + s(air,bs='cr')        |                          | |
| test56  |  ~  te(lon, lat,k=c(5,5)) | ~  te(lon, lat,k=c(3,3)) | ~1|
|          |  + s(air,bs='cr')        |                          | |
