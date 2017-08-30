# KAudioRecorder
İOS Audio Record &amp; Play Helper Class 🔊

#### Use

```Swift
      var recorder = KAudioRecorder.shared
      recorder.recordName = "music"
```

###### Record & Stop & Control

```Swift
      recorder.record()
```
```Swift
      recorder.stop()
```
```Swift
      recorder.isRecording // True | False 
```

###### Play & Stop & Control

```Swift
      recorder.play()
      recorder.play(name:"music") // Recorded name
```
```Swift
      recorder.stop()
```
```Swift
      recorder.isPlaying // True | False 
```

###### Delete

```Swift
      recorder.delete(name: "music") // Recorded name
```

###### Other

```Swift
     recorder.isAuth() // True | False
```
```Swift
     recorder.time // Decimal
     recorder.getTime() // String format
```




