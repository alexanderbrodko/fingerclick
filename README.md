https://alexanderbrodko.github.io/fingerclick/

AI sound recognition training tool in browser. Click "Start" and approve using microphone, then you can see a sound spectrum. You can mark a spectrogram column as a positive or negative trainging sample. Or use a checkbox to automatically mark all new samples as negative.

You can also load a neural network which detects finger snaps. You can train it more for a personal purposes.

![image](https://github.com/alexanderbrodko/fingerclick.js/assets/57812581/1b0491d7-190c-485a-a2e3-11de705cde8c)

Once you trained it, press "Copy to clipboard" and then use the JSON with https://github.com/cazala/synaptic

```let myNetwork = synaptic.Network.fromJSON(networkJSON);```
