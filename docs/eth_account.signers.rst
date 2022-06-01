Signers
============================

These classes abstract away the private key, as opposed to :class:`platon_account.account.Account`,
which explicitly requires the private key on each usage.

All the signer classes in this package must meet the
interface specified by :class:`~platon_account.signers.base.BaseAccount`.

Currently there is only one Local Signer.
Some upcoming alternatives to the basic local signer include
hierarchical deterministic (HD) wallets and hardware wallets.

Local Signer
---------------------------------

.. automodule:: platon_account.signers.local
    :members:
    :undoc-members:
    :show-inheritance:


Abstract Signer
--------------------------------

.. automodule:: platon_account.signers.base
    :members:
    :undoc-members:
    :show-inheritance:
