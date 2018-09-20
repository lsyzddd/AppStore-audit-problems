ios的一些权限提示必须添加，否则ios官方审核不能通过
```
"plistcmds": [
  "Set :NSContactsUsageDescription 允许后，将导入通讯录中的联系人，可查看谁在使用嘿猪App",
  "Set :NSMicrophoneUsageDescription 允许后，将使用您的麦克风",
  "Set :NSPhotoLibraryUsageDescription 允许后，可以直接从相册中选取图片",
  "Set :NSCameraUsageDescription 允许后，可以使用拍照功能",
  "Set :NSPhotoLibraryAddUsageDescription 允许后，拍摄的照片可以保存到相册，方便下次直接从相册选取",
  "Set :NSLocationAlwaysUsageDescription 允许后，将获取您当前的位置，在频道中展示",
  "Set :NSLocationWhenInUseUsageDescription 允许后，将获取您当前的位置，在频道中展示",
  "Set :NSLocationAlwaysAndWhenInUseUsageDescription 允许后，将获取您当前的位置，在频道中展示"
]
