WirelessDyno
============

Measuring the force exerted on a physical structure as it moves over a range of motion has many practical applications.  Such a measurement system is generally referred to as a dynamometer.  This project aims to explore a particular kind of dynamometer, where a wireless microcontroller is embedded directly to a strain gauge and combined with an acceloremeter.

One practical application of interest is in ground fluid pumping where we'd like to be able to measure the force/weight exerted on the pumping equipment as it moves through its pumping motion.  Sampled quickly and accurately enough, these measurements can be used to derive a variey of useful information pertaining to the performance of the pumping system and the behavior of a the pump hundreds or even thousands of feet below.

The Strain Gauge
----------------

The strain gauge is an electro-mechanical device employing a wheatstone bridge resistor configuration.  Commercially available load cells are available for a variety of mechanical situations.
It outputs a differential signal that we'll input into a Sigma Delta style ADC.
