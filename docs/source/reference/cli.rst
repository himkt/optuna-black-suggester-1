.. module:: optuna.cli

optuna.cli
==========

The :mod:`~optuna.cli` module implements Optuna's command-line functionality using the `cliff framework <https://docs.openstack.org/cliff/latest/index.html>`_.

.. seealso::
    The :ref:`cli` tutorial provides use-cases with examples.

.. autoprogram-cliff:: optuna.cli._OptunaApp
   :application: optuna

.. autoprogram-cliff:: optuna.command
   :application: optuna
