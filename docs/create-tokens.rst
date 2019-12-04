.. comment include:: utils.rst

Create tokens
=============

|
.. image:: images/BottomBar-Tokens.png
   :scale: 80%
   :align: center
|

The ability for anyone to create new tokens on the FIN4Xplorer plattform is at the heart of its concept. Once a token is created, it can be claimed by anyone. A successful claim results in having a balance on the respective token. Since we base our token contracts on the `ERC-20 standard <https://en.wikipedia.org/wiki/Ethereum#Development_governance_and_EIP>`_ this balance will show up on any Ethereum digital wallet app that supports the ERC-20 standard. Note that also in such apps you have to switch to the Rinkeby testnet.

Token creation wizard
^^^^^^^^^^^^^^^^^^^^^

.. image:: images/CreateANewToken.png
   :scale: 35%
   :align: right

The effort put into creating a token can range from a quick 1-min-clicktrough to a lengthy eloborate planning in a multi-disciplinary team. The possible entry points for the token creation process are:

- Creating a new token from scratch
- Uploading a token draft in JSON format
- Copying an existing token design as template

The last two will import a token creation draft showing up at the bottom of the box. The first option will take you directly into the token creation wizard. It consists of 5 steps: *Identity*, *Design*, *Actions*, *Minting* and *Proving*. In each step, an info box can be opened that provides explanations.

.. image:: images/WizardSteps.png
   :scale: 37%
   :align: center

Note that at any point you can leave the wizard and your progess will be stored as draft. Drafts can be used to resume the process later on or to download, share and import them.

Once the 5 steps are completed, the token can be created on the blockchain. One ore more transactions have to be confirmed for that. One for the token-creation itself and one for each proof that has parameters. Until all proof-parameterization transactions are confirmed, the token will remain in a disabled state.
