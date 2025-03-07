torchtext
=========

This library is part of the `PyTorch
<http://pytorch.org/>`_ project. PyTorch is an open source
machine learning framework.

Features described in this documentation are classified by release status:

  *Stable:*  These features will be maintained long-term and there should generally
  be no major performance limitations or gaps in documentation.
  We also expect to maintain backwards compatibility (although
  breaking changes can happen and notice will be given one release ahead
  of time).

  *Beta:*  Features are tagged as Beta because the API may change based on
  user feedback, because the performance needs to improve, or because
  coverage across operators is not yet complete. For Beta features, we are
  committing to seeing the feature through to the Stable classification.
  We are not, however, committing to backwards compatibility.

  *Prototype:*  These features are typically not available as part of
  binary distributions like PyPI or Conda, except sometimes behind run-time
  flags, and are at an early stage for feedback and testing.


The :mod:`torchtext` package consists of data processing utilities and
popular datasets for natural language.

.. toctree::
   :maxdepth: 2
   :caption:  Package Reference

   self
   nn_modules
   data_functional
   data_metrics
   data_utils
   datasets
   torchtext.vocab <vocab>
   torchtext.utils <utils>
   transforms
   functional
   models

Getting Started
---------------

.. toctree::
   :maxdepth: 1
   :caption: Getting Started

   tutorials/sst2_classification_non_distributed
   tutorials/t5_demo


.. automodule:: torchtext
   :members:

.. toctree::
   :maxdepth: 1
   :caption: PyTorch Libraries

   PyTorch <https://pytorch.org/docs>
   torchaudio <https://pytorch.org/audio>
   torchtext <https://pytorch.org/text>
   torchvision <https://pytorch.org/vision>
   TorchElastic <https://pytorch.org/elastic/>
   TorchServe <https://pytorch.org/serve>
   PyTorch on XLA Devices <http://pytorch.org/xla/>
