<h1 align="center">
<img src="images/logo_vector.svg" width=300px href="https://makeml.app?from=github_potato_weigher" alt="Object Detection and Segmentation MakeML">
</h1>

[MakeML](https://makeml.app?from=github_live_capture_object_detection) is a Developer Tool for Creating Object Detection and Segmentation Neural Networks without a Line of Code. It's built to make the training process easy to setup. It is designed to handle data sets, training configurations, markup and training processes — all in one place.

## Live Object Recognition Example with CoreML
Is an iOS template project example that can be used to run your own CoreML Object Detection Model.

## Train Custom Object Detection CoreML model
[![MakeML object detection and segmentation ML models](https://img.shields.io/static/v1?label=platform&message=macOS&color=blue)](https://makeml.app)

With MakeML you can prepare dataset and train CoreML model with Tensorflow or Turi Create frameworks in one application.

See the [Tutorial](https://makeml.app/docs/doc1?from=github_live_capture_object_detection) for the training object detection model without a line of code with macOS desktop application.

<div align="center">
<img src="images/dog_detector_markup.gif">
</div>

<div align="center">
<img src="images/doc_detector_result.gif">
</div>

## Using another .mlmodel in iOS application
[![MakeML object detection and segmentation ML models](https://img.shields.io/static/v1?label=platform&message=iOS&color=blue)](https://makeml.app)    [![MakeML object detection and segmentation ML models](https://img.shields.io/static/v1?label=language&message=swift&color=green)](https://makeml.app)

For using this project with another .mlmodel file, add it to the project and change this line with your name of the model.
```
guard let modelURL = Bundle.main.url(forResource: "Model", withExtension: "mlmodelc") else {
    return NSError(domain: "VisionObjectRecognitionViewController", code: -1, userInfo: [NSLocalizedDescriptionKey: "Model file is missing"])
}
```

## Links

[More Tutorials](https://makeml.app/tutorials?from=github_live_capture_object_detection) | [MakeML in App Store](https://apps.apple.com/us/app/makeml/id1469520792?mt=12) | [Full Documentation](https://makeml.app/docs/doc1?from=github_live_capture_object_detection) | [MakeML Chat](https://discordapp.com/invite/vgcG3Su) | [Support page](https://makeml.app/support?from=github_live_capture_object_detection)

