Claim tokens
=============

|
.. image:: images/BottomBar-Claims.png
   :scale: 80%
   :align: center
|

Tokens that have been created as outlined in `Create tokens <create-tokens.html>`_, can be claimed.

.. image:: images/ClaimTokens.png
   :scale: 35%

Submitting a claim is the first step to obtaining a balance on the token in question. Once made, it shows up under *My previous claims*. Claims there can be in one of three stages:

- In red with a prompt to *Submit proof*, this is the default after submitting a new claim
- In green, the approved state, which also means that a balance has to be minted to the claimer
- In gray, the rejected state, if one or more of the proofs got manually or automatically rejected

.. image:: images/MyPreviousClaims.png
   :scale: 35%

Proving
^^^^^^^

For a claim to be successful, all the proofs specified by the token creator have to be provided and get approved - automatically or by the chosen person, group or sensor. A proof submission site might look like this.

.. image:: images/ProofSubmission.png
   :scale: 35%

Here, a proof is shown (*ClaimableOnlyNTimes*) that didn't have to be initated manually. It belongs to the category of proofs that automatically give their approval or rejection once a claim is made.

Once all proofs are provided and approved, the claim appears as green and the claimer gets a balance on this token.

.. image:: images/MyPreviousClaims_approved.png
   :scale: 35%

.. image:: images/Wallet.png
   :scale: 35%

Once any proof of a claim is rejected, the entire claim gets rejected. It is not possible to recover this claim by resubmitting proofs - a new claim has to be made if the user wants to try again.
