.. _data:

==================================
Ray Data: Scalable Datasets for ML
==================================

.. toctree::
    :hidden:

    Overview <overview>
    quickstart
    key-concepts
    user-guide
    examples
    api/api
    data-internals

Ray Data is a scalable data processing library for ML workloads. It provides flexible and performant APIs for scaling :ref:`Offline batch inference <batch_inference_overview>` and :ref:`Data preprocessing and ingest for ML training <ml_ingest_overview>`. Ray Data uses `streaming execution <https://www.anyscale.com/blog/streaming-distributed-execution-across-cpus-and-gpus>`__ to efficiently process large datasets.

..
  https://docs.google.com/drawings/d/16AwJeBNR46_TsrkOmMbGaBK7u-OPsf_V8fHjU-d2PPQ/edit

Install Ray Data
----------------

To install Ray Data, run:

.. code-block:: console

    $ pip install -U 'ray[data]'

To learn more about installing Ray and its libraries, see
:ref:`Installing Ray <installation>`.

Learn more
----------

.. grid:: 1 2 2 2
    :gutter: 1
    :class-container: container pb-6

    .. grid-item-card::

        **Ray Data Overview**
        ^^^

        Get an overview of Ray Data, the workloads that it supports, and how it compares to alternatives.

        +++
        .. button-ref:: data_overview
            :color: primary
            :outline:
            :expand:

            Ray Data Overview

    .. grid-item-card::

        **Quickstart**
        ^^^

        Get started with Ray Data with a simple example.

        +++
        .. button-ref:: data_quickstart
            :color: primary
            :outline:
            :expand:

            Quickstart

    .. grid-item-card::

        **Key Concepts**
        ^^^

        Learn the key concepts behind Ray Data. Learn what
        Datasets are and how they're used.

        +++
        .. button-ref:: data_key_concepts
            :color: primary
            :outline:
            :expand:

            Key Concepts

    .. grid-item-card::

        **User Guides**
        ^^^

        Learn how to use Ray Data, from basic usage to end-to-end guides.

        +++
        .. button-ref:: data_user_guide
            :color: primary
            :outline:
            :expand:

            Learn how to use Ray Data

    .. grid-item-card::

        **Examples**
        ^^^

        Find both simple and scaling-out examples of using Ray Data.

        +++
        .. button-ref:: examples
            :color: primary
            :outline:
            :expand:

            Ray Data Examples

    .. grid-item-card::

        **API**
        ^^^

        Get more in-depth information about the Ray Data API.

        +++
        .. button-ref:: data-api
            :color: primary
            :outline:
            :expand:

            Read the API Reference
