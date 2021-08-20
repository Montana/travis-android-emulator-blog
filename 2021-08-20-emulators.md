---
title: "Using Android Emulators on Travis"
created_at: Fri Aug 20 2021 15:00:00 EDT
author: Montana Mendy
layout: post
permalink: 2021-08-20-emulators
category: news
excerpt_separator: <!-- more --> 
tags:
  - news
  - feature
  - infrastructure
  - community
---
![11](https://user-images.githubusercontent.com/20936398/130273787-9d9ede5d-1ced-49db-a9d9-311960402bc1.png)

In 2021, if an Android or Java developer wants to run an emulator, specifically an Android one in the cloud the developer may find it extremely hard, or may think it's impossible, but the good news is if the App in question does not require features in newer emulators, for example anything post `android-25`, then it is possible to spin up one of the Arm based emulators in the cloud, below I'll list your options.

<!-- more --> 

```markdown
addon-google_apis-google-10
addon-google_apis-google-11
addon-google_apis-google-12
addon-google_apis-google-13
addon-google_apis-google-14
addon-google_apis-google-15
addon-google_apis-google-16
addon-google_apis-google-17
addon-google_apis-google-18
addon-google_apis-google-19
addon-google_apis-google-21
addon-google_apis-google-22
addon-google_apis-google-23
addon-google_apis-google-24
addon-google_apis-google-3
addon-google_apis-google-4
addon-google_apis-google-5
addon-google_apis-google-6
addon-google_apis-google-7
addon-google_apis-google-8
addon-google_apis-google-9
addon-google_gdk-google-19
addon-google_tv_addon-google-12
addon-google_tv_addon-google-13
android-10
android-11
android-12
android-13
android-14
android-15
android-16
android-17
android-18
android-19
android-2
android-20
android-21
android-22
android-23
android-24
android-25
android-26
android-3
android-4
android-5
android-6
android-7
android-8
android-9
build-tools-17.0.0
build-tools-18.0.1
build-tools-18.1.0
build-tools-18.1.1
build-tools-19.0.0
build-tools-19.0.1
build-tools-19.0.2
build-tools-19.0.3
build-tools-19.1.0
build-tools-20.0.0
build-tools-21.0.0
build-tools-21.0.1
build-tools-21.0.2
build-tools-21.1.0
build-tools-21.1.1
build-tools-21.1.2
build-tools-22.0.0
build-tools-22.0.1
build-tools-23.0.0
build-tools-23.0.1
build-tools-23.0.2
build-tools-23.0.3
build-tools-24.0.0
build-tools-24.0.1
build-tools-24.0.2
build-tools-24.0.3
build-tools-25.0.0
build-tools-25.0.1
build-tools-25.0.2
build-tools-25.0.3
build-tools-26.0.0
build-tools-26.0.1
doc-24
extra-android-m2repository
extra-google-admob_ads_sdk
extra-google-analytics_sdk_v2
extra-google-auto
extra-google-gcm
extra-google-google_play_services
extra-google-google_play_services_froyo
extra-google-instantapps
extra-google-m2repository
extra-google-market_apk_expansion
extra-google-market_licensing
extra-google-play_billing
extra-google-simulators
extra-google-webdriver
platform-tools
source-14
source-15
source-16
source-17
source-18
source-19
source-20
source-21
source-22
source-23
source-24
source-25
sys-img-arm64-v8a-android-24
sys-img-arm64-v8a-google_apis-24
sys-img-arm64-v8a-google_apis-25
sys-img-armeabi-v7a-android-10
sys-img-armeabi-v7a-android-14
sys-img-armeabi-v7a-android-15
sys-img-armeabi-v7a-android-16
sys-img-armeabi-v7a-android-17
sys-img-armeabi-v7a-android-18
sys-img-armeabi-v7a-android-19
sys-img-armeabi-v7a-android-21
sys-img-armeabi-v7a-android-22
sys-img-armeabi-v7a-android-24
sys-img-armeabi-v7a-android-tv-21
sys-img-armeabi-v7a-android-tv-22
sys-img-armeabi-v7a-android-tv-23
sys-img-armeabi-v7a-android-wear-23
sys-img-armeabi-v7a-android-wear-25
sys-img-armeabi-v7a-google_apis-10
sys-img-armeabi-v7a-google_apis-15
sys-img-armeabi-v7a-google_apis-16
sys-img-armeabi-v7a-google_apis-17
sys-img-armeabi-v7a-google_apis-18
sys-img-armeabi-v7a-google_apis-19
sys-img-armeabi-v7a-google_apis-21
sys-img-armeabi-v7a-google_apis-22
sys-img-armeabi-v7a-google_apis-23
sys-img-armeabi-v7a-google_apis-24
sys-img-armeabi-v7a-google_apis-25
sys-img-mips-android-15
sys-img-mips-android-16
sys-img-mips-android-17
sys-img-x86_64-android-21
sys-img-x86_64-android-22
sys-img-x86_64-android-23
sys-img-x86_64-android-24
sys-img-x86_64-google_apis-21
sys-img-x86_64-google_apis-22
sys-img-x86_64-google_apis-23
sys-img-x86_64-google_apis-24
sys-img-x86_64-google_apis-25
sys-img-x86-android-10
sys-img-x86-android-15
sys-img-x86-android-16
sys-img-x86-android-17
sys-img-x86-android-18
sys-img-x86-android-19
sys-img-x86-android-21
sys-img-x86-android-22
sys-img-x86-android-23
sys-img-x86-android-24
sys-img-x86-android-tv-21
sys-img-x86-android-tv-22
sys-img-x86-android-tv-23
sys-img-x86-android-tv-24
sys-img-x86-android-tv-25
sys-img-x86-android-tv-26
sys-img-x86-android-wear-23
sys-img-x86-android-wear-25
sys-img-x86-android-wear-26
sys-img-x86-google_apis-10
sys-img-x86-google_apis-15
sys-img-x86-google_apis-16
sys-img-x86-google_apis-17
sys-img-x86-google_apis-18
sys-img-x86-google_apis-19
sys-img-x86-google_apis-21
sys-img-x86-google_apis-22
sys-img-x86-google_apis-23
sys-img-x86-google_apis-24
sys-img-x86-google_apis-25
sys-img-x86-google_apis-26
sys-img-x86-google_apis_playstore-24
sys-img-x86-google_apis_playstore-26
tools
```

Any one of these will work on Travis. What I ended up doing is booting into my Gentoo VM, and created a test bench on Travis, that attempts to start a cluster of Arm based emulators and I was able to get almost if not everything running with android-28 tools, below I'm going to share the project with you, my `.travis.yml` file so you too can learn how to use emulation in Travis. 

So below, I'm going to attach my `.travis.yml` file I created for my project: 

```yaml
---
language: android
jdk: oraclejdk8

android:
  licenses:
    - 'android-sdk-preview-license-.+'
    - 'android-sdk-license-.+'
    - 'google-gdk-license-.+'
 
  components:
    - tools
    - build-tools-30.0.2
    - tools
    - android-30
    - android-22
    - extra-google-google_play_services
    - extra-google-m2repository
    - extra-android-m2repository
    - sys-img-armeabi-v7a-android-22
 
before_install:
  - chmod +x gradlew
  - yes | sdkmanager "platforms;android-30"

before_script:
  - echo no | android create avd --force -n test -t android-22 --abi armeabi-v7a
  - emulator -avd test -no-audio -no-window &
  - bash android-wait-for-emulator
  - adb shell input keyevent 82 &
  
script:
  - ./gradlew clean build
  - ./gradlew test
  - ./gradlew build check

before_cache:
  - rm -f  $HOME/.gradle/caches/modules-2/modules-2.lock
  - rm -fr $HOME/.gradle/caches/*/plugin-resolution/

cache:
  directories:
  - $HOME/.gradle/caches/
  - $HOME/.gradle/wrapper/
  - $HOME/.android/build-cache
```

The app in question is just a simple login page application. You can visit the source code here on my [GitHub](https://github.com/Montana/travis-droidcon2021-talk).

Once you start building, you'll see within 2-3 minutes of the build, this:

<img width="323" alt="Screen Shot 2021-08-20 at 11 00 53 AM" src="https://user-images.githubusercontent.com/20936398/130274985-3a5d9fb7-546f-4061-8936-7bad3cae634a.png">

This is perfectly normal, in fact there's something you can use called `android-wait-for-emulator.sh`, which I recommend just adding to the root of your project, it's a bash script, and reads: 

```bash

 #!/bin/bash
 
set +e

bootanim=""
failcounter=0
timeout_in_sec=360

until [[ "$bootanim" =~ "stopped" ]]; do
  bootanim=`adb -e shell getprop init.svc.bootanim 2>&1 &`
  if [[ "$bootanim" =~ "device not found" || "$bootanim" =~ "device offline"
    || "$bootanim" =~ "running" ]]; then
    let "failcounter += 1"
    echo "Waiting for emulator to start"
    if [[ $failcounter -gt timeout_in_sec ]]; then
      echo "Timeout ($timeout_in_sec seconds) reached; failed to start emulator"
      exit 1
    fi
  fi
  sleep 1
done

echo "Emulator is ready"
```

This saves a little time on booting the emulator. Don't forget, these tests can be performed on the following `os:`, 

```yaml
linux
macOS
```

With the list I provided of emulators that work on Travis, some source code you can mess around with - go ahead have some fun, see what Travis is capable of, and as always if you have any questions please email me at [montana@travis-ci.org](mailto:montana@travis-ci.org). 

Happy building!
