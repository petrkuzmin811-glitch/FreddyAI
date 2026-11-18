# Third-party components

- Vosk Android 0.3.75, https://github.com/alphacep/vosk-api — Apache License 2.0.
- vosk-model-small-ru-0.22, https://alphacephei.com/vosk/models — Apache License 2.0. The license copy is included beside the model in StreamingAssets.
- JNA 5.18.1, https://github.com/java-native-access/jna — dual licensed LGPL 2.1 or Apache License 2.0; this distribution selects Apache 2.0.
- Newtonsoft.Json, https://github.com/JamesNK/Newtonsoft.Json — MIT; Unity resolves the package and its license.
- Unity Editor/player and uGUI use Unity's applicable terms/package licenses.
- UVCAndroid 1.0.13, https://github.com/shiyinghan/UVCAndroid/tree/1.0.13 — Apache License 2.0. This app redistributes the unmodified reachable USB/UVC Java classes and ARM64 shared libraries from the Maven Central AAR. The reproducible extraction script is in BuildTools/prepare_uvc.py. Full upstream source and license files are in ThirdParty. No UVC native code has been modified.
- Native UVC dependencies: libusb 1.0 (LGPL 2.1 or later), libuvc (BSD), libjpeg-turbo (IJG/BSD/zlib as documented upstream), libyuv (BSD). Corresponding source is included in ThirdParty/UVCAndroid-1.0.13-source.zip; license copies are in ThirdParty/Licenses and the upstream source. Shared libraries can be replaced/relinked in the supplied Unity project/AAR. The application license does not impose restrictions on modifications or reverse engineering necessary to debug changes to LGPL components.
- The user supplied Freddy sprites, sound recordings, music, and original ESP firmware. They remain subject to their respective rights. The application's MIT license does not cover them or the character.
- Groq, OpenRouter, Fish Audio and Open-Meteo are external services and retain their respective terms. No service keys are included.

The standalone Python dependencies are listed in Python/requirements.txt and are not redistributed as installed Python packages in this archive.

- TensorFlow Lite SSD MobileNet COCO model: official TensorFlow distribution, https://storage.googleapis.com/download.tensorflow.org/models/tflite/coco_ssd_mobilenet_v1_1.0_quant_2018_06_29.zip. Model SHA256 e4b118e5e4531945de2e659742c7c590f7536f8d0ed26d135abcfe83b4779d13. TensorFlow/LiteRT: Apache 2.0; license in ThirdParty/Licenses/TensorFlow-Lite.txt. LiteRT Android 1.4.2 and bundled ML Kit face detection 16.1.7 resolve through Gradle. ML Kit is subject to Google's applicable SDK terms; frames are processed on-device.
