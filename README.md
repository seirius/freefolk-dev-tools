# freefolk-dev-tools

```
       +------------+ff:download+--------------------->mqtt
       |              +      +  |                       ^
       |              |      |  |                       |
       |              |      |  |                       |
       |              |      |  +-------->ff:converter+-+
       v              |      |                 +
 ff:youtube           |      |                 |
      +               |      v                 |
      |               |     ff:filemanager<----+
      |               |           +
      |               |           |
      v               v           |
api:youtube      ff:queue         |
                     +            v
                     +--------->redis

```