**Vosk**

```
$ kubectl apply -f vosk.yaml
```

**Test**
You need to install the following dependencies

```
$ pip3 install sounddevice websockets
$ python test_microphone.py -u wss://stt.example.com
```