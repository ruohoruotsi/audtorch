Changelog
=========

All notable changes to this project will be documented in this file.

The format is based on `Keep a Changelog`_,
and this project adheres to `Semantic Versioning`_.

Unreleased
----------

* Added: `RandomConvolutionalMix` transform

Version 0.4.2 (2019-11-04)
--------------------------

* Fixed: critical bug of missing files in wheel package (#60)


Version 0.4.1 (2019-10-25)
--------------------------

* Fixed: default axis values for Masking transforms (#59)


Version 0.4.0 (2019-10-21)
--------------------------

* Added: masking transforms in time and frequency domain


Version 0.3.2 (2019-10-04)
--------------------------

* Fixed: long description in ``setup.cfg``


Version 0.3.1 (2019-10-04)
--------------------------

* Changed: define package in ``setup.cfg``


Version 0.3.0 (2019-09-13)
--------------------------

* Added: ``datasets.SpeechCommands`` (#49)
* Removed: ``LogSpectrogram`` (#52)


Version 0.2.1 (2019-08-01)
--------------------------

* Changed: Remove os.system call for moving files (#43)
* Fixed: Remove broken logos from issue templates (#31)
* Fixed: Wrong ``Spectrogram`` output shape in documentation (#40)
* Fixed: Broken data set loading for relative paths (#33)


Version 0.2.0 (2019-06-28)
--------------------------

* Added: ``Standardize``, ``Log`` (#29)
* Changed: Switch to `Keep a Changelog`_ format (#34)
* Deprecated: ``LogSpectrogram`` (#29)
* Fixed: ``normalize`` axis (#28)


Version 0.1.1 (2019-05-23)
--------------------------

* Fixed: Broken API documentation on RTD_


Version 0.1.0 (2019-05-22)
--------------------------

* Added: Public release


.. _Keep a Changelog: https://keepachangelog.com/en/1.0.0/
.. _Semantic Versioning: https://semver.org/spec/v2.0.0.html
.. _RTD: https://audtorch.readthedocs.io/
