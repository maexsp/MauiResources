# MauiResources
Demo to show an issue with Maui Path loading issue (big path images result in very slow app startup time)

- Android: 30 images will not load on Android emulator (GC free endless-loop) and also on Android Samsung Galaxy S22 not loading at all
           20 images will load but needs about 15 sec on the emulator

- WinUI: Needs about 40 sec for 30 big path images

- iOS: Not tested yet

![grafik](https://user-images.githubusercontent.com/15746917/188088974-241acb8d-4295-4141-9387-9c105f795763.png)

![grafik](https://user-images.githubusercontent.com/15746917/188087725-dba006ef-4d3f-4e41-8100-25fb5b34cbf0.png)
