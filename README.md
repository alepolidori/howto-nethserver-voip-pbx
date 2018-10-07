# NethServer VoIP PBX

NethServer VoIP PBX is a complete phone switchboard system based on [Asterisk](https://www.asterisk.org/), [FreePBX](https://www.freepbx.org/) and [NethServer](https://www.nethserver.org/) linux distribution.

You can easily install one of your own simply running:

```console
$ git clone https://github.com/alepolidori/vagrant-files.git
$ cd vagrant-files/nethserver-freepbx-14.0.3.6
$ vagrant up
```

to have a VirtualBox machine installed with [Vagrant.](https://www.vagrantup.com/)
Once the machine is running you have 6 PJSIP extensions already configured and ready to use:

- 200
- 201
- 202
- 203
- 204
- 205

All the extensions have the same default secret: `Nethesis,1234.`

The IP address of the virtual machine is `192.168.11.22.`

If you want to install [NethServer VoIP PBX](http://docs.nethserver.org/en/v7/freepbx.html) yourself, you can also follow this 6-steps [guide](https://github.com/alepolidori/nethserver-voip-pbx-guide/).

## Client demo: HTML5 SIP Phone WebRTC

You can experiment the server PBX features with a client demo containing an [HTML5 SIP Phone WebRTC](https://github.com/alepolidori/janus-webrtc-phone) to make audio/video calls.
