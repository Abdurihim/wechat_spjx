# 微信视频解析接口

**提交方式：GET**

<u>演示</u>

```url
?url=微信视频地址
```

<u>响应</u>

```json
// 20200504002110
// http://api.haobaobattery.cn/mp4.php?url=https://mp.weixin.qq.com/s/N8JAVaY8XUI8O-XsHfBh1A

{
  "base_resp": {
    "ret": 0
  },
  "url_info": [
    {
      "url": "http://mpvideo.qpic.cn/0b78viaaaaaa4qah3ivb2zpfbkwdacvaaaaa.f10002.mp4?dis_k=9a3017f959d9eb9fd98d4787d8303759&dis_t=1588522869",
      "format_id": 10002,
      "duration_ms": 4055413,
      "filesize": 424560974,
      "width": 1702,
      "height": 720
    },
    {
      "url": "http://mpvideo.qpic.cn/0b78viaaaaaa4qah3ivb2zpfbkwdacvaaaaa.f10003.mp4?dis_k=3fa4c9a285205501b23ab848c93d686e&dis_t=1588522869",
      "format_id": 10003,
      "duration_ms": 4055413,
      "filesize": 274510394,
      "width": 1702,
      "height": 720
    },
    {
      "url": "http://mpvideo.qpic.cn/0b78viaaaaaa4qah3ivb2zpfbkwdacvaaaaa.f10004.mp4?dis_k=27f2b5100eed89545d644704ac9d5982&dis_t=1588522869",
      "format_id": 10004,
      "duration_ms": 4055413,
      "filesize": 173184185,
      "width": 1134,
      "height": 480
    }
  ],
  "is_mp_video_delete": 0,
  "is_mp_video_forbid": 0,
  "is_mp_video_urgent_state": 0,
  "title": "كەنتاۋىر",
  "is_mp_video_checking": 0,
  "is_mp_video_check_fail": 0,
  "is_appmsg_unauthorized": 0,
  "is_mp_video_transing": 0
}
```

