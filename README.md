
# GroupSnap 📷

> **Never miss being in the group photo again**

An innovative Android camera application that seamlessly merges two shots into one perfect group photo. No more asking strangers to take your picture or having someone always behind the camera.

## ✨ Features

- **Dual-Shot Technology**: Take one photo of your group, then add yourself in a second shot
- **Smart Alignment**: Ghost overlay system guides perfect camera positioning
- **No AI Dependencies**: Works on older Android devices (API 21+)
- **Locked Camera Settings**: Consistent exposure, focus, and white balance across both shots
- **Real-time Preview**: See exactly how your final photo will look
- **One-Tap Export**: Instant high-quality merged photo

## 🚀 How It Works

1. **Lock Settings**: App automatically locks camera parameters for consistency
2. **First Shot**: Someone takes a photo of your group (minus photographer)
3. **Position Guide**: Ghost overlay shows exact positioning for second shot
4. **Second Shot**: Photographer joins the scene in an empty area
5. **Magic Merge**: App seamlessly combines both photos into one natural group shot

## 🛠️ Technical Stack

- **Language**: Kotlin
- **Camera**: CameraX API
- **Image Processing**: OpenCV
- **UI Framework**: Android Jetpack Compose
- **Minimum SDK**: Android 5.0 (API 21)
- **Architecture**: MVVM Pattern

## 📱 System Requirements

- Android 5.0+ (API level 21)
- Camera permission
- Storage permission
- Minimum 2GB RAM recommended
- Rear camera with autofocus

## 🏗️ Project Structure

```
GroupSnap/
├── README.md
├── .gitignore
├── LICENSE
├── android-app/
│   └── app/
│       ├── src/main/java/com/yourname/groupsnap/
│       │   ├── MainActivity.kt
│       │   ├── camera/
│       │   │   ├── CameraController.kt
│       │   │   └── CameraViewModel.kt
│       │   ├── processing/
│       │   │   ├── ImageProcessor.kt
│       │   │   └── ImageMerger.kt
│       │   ├── ui/
│       │   │   ├── CameraScreen.kt
│       │   │   └── OverlayManager.kt
│       │   └── utils/
│       │       ├── PermissionHandler.kt
│       │       └── FileManager.kt
│       ├── res/
│       │   ├── layout/
│       │   ├── values/
│       │   └── drawable/
│       └── build.gradle
├── docs/
│   ├── API.md
│   ├── CONTRIBUTING.md
│   └── screenshots/
└── assets/
    ├── app-icon/
    ├── mockups/
    └── demo-videos/
```


## 🎯 Development Roadmap

### Phase 1: Core Foundation ✅
- [x] Project setup and repository initialization
- [ ] Basic camera preview implementation
- [ ] Manual camera controls (exposure, focus lock)
- [ ] Permission handling system

### Phase 2: Dual-Shot System 🔄
- [ ] First photo capture and storage
- [ ] Ghost overlay implementation
- [ ] Camera position guidance
- [ ] Second photo capture with alignment

### Phase 3: Image Processing 📋
- [ ] Basic image merging algorithm
- [ ] Exposure and color matching
- [ ] Edge blending and smoothing
- [ ] Export functionality

### Phase 4: Polish & Optimization 📋
- [ ] UI/UX improvements
- [ ] Performance optimization
- [ ] Error handling
- [ ] Testing and debugging

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](docs/CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- Inspired by Google Pixel's "Add Me" feature
- Built with modern Android development practices
- Thanks to the open-source community for amazing libraries

## 📞 Contact

**Developer**: [Jerin E V]  
**Email**: jevp43@gmail.com  
**GitHub**: [@jer-in](https://github.com/jer-in)

---

⭐ **Star this repo if you find it useful!** ⭐

*Built with ❤️ for photographers who want to be in their own pictures*
