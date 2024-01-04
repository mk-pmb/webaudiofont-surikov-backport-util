
<!--#echo json="package.json" key="name" underline="=" -->
webaudiofont-surikov-midifilejs-backport-util
=============================================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Tools for backporting patches from bundled JS files in `surikov/webaudiofont`.
<!--/#echo -->


Motivation
----------

The git repo [`surikov/webaudiofont`](https://github.com/surikov/webaudiofont)
has some improvements to 3rd-party JS MIDI libraries, including improvements
to `MIDIFile.js` which we
[tried to backport](https://github.com/nfroidure/midifile/issues/34).
Unfortunately, this turned out to be more complicated than expected,
because some of the development there was done inside a bundled file.
This repo here aims to provide tools for un-bundling that bundle,
and for comparing the resulting parts to official versions of the
original files.







&nbsp;


License
-------
<!--#echo json="package.json" key=".license" -->
MIT
<!--/#echo -->
