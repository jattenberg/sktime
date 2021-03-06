
.. _forecasting_ref:

sktime.forecasting: Time series forecasting
===========================================

The :mod:`sktime.forecasting` module contains algorithms and composition tools for forecasting.

.. automodule:: sktime.forecasting
    :no-members:
    :no-inherited-members:

Base
----

.. currentmodule:: sktime.forecasting.base

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    ForecastingHorizon

Naive
-----

.. currentmodule:: sktime.forecasting.naive

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    NaiveForecaster

Trend
-----

.. currentmodule:: sktime.forecasting.trend

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    PolynomialTrendForecaster

Exponential Smoothing
---------------------

.. currentmodule:: sktime.forecasting.exp_smoothing

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    ExponentialSmoothing

.. currentmodule:: sktime.forecasting.ets

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    AutoETS

ARIMA
-----

.. currentmodule:: sktime.forecasting.arima

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    AutoARIMA

Theta
-----

.. currentmodule:: sktime.forecasting.theta

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    ThetaForecaster

Composition
-----------

.. currentmodule:: sktime.forecasting.compose

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    EnsembleForecaster
    TransformedTargetForecaster
    DirectRegressionForecaster
    DirectTimeSeriesRegressionForecaster
    RecursiveRegressionForecaster
    RecursiveTimeSeriesRegressionForecaster
    ReducedRegressionForecaster
    ReducedTimeSeriesRegressionForecaster
    StackingForecaster

Online Forecasting
------------------

.. currentmodule:: sktime.forecasting.online_learning

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    OnlineEnsembleForecaster
    NormalHedgeEnsemble
    NNLSEnsemble

Model Selection
---------------

.. currentmodule:: sktime.forecasting.model_selection

.. autosummary::
    :toctree: modules/auto_generated/
    :template: class.rst

    CutoffSplitter
    SingleWindowSplitter
    SlidingWindowSplitter
    ForecastingGridSearchCV

.. autosummary::
    :toctree: modules/auto_generated/
    :template: function.rst

    temporal_train_test_split
