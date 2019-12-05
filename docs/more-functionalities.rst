More functionalities
====================

All the functionalities presented below are accessible via the `Home site <dapp-overview.html#home>`_.

Wallet
~~~~~~

The wallet box shows the users balance on all tokens with approved claims. The token name links to its respective detailed site (TODO ref).

.. image:: images/Wallet.png
   :scale: 40%

The transfer icon links to a site allowing the `transfer <#transfer-tokens>`_ of balances on transferable tokens to other users.

Transfer Tokens
^^^^^^^^^^^^^^^
Note that once a transfer has been made, there is no way to undo it from the senders site. Only the recipient could choose to send it back.

.. image:: images/Transfer.png
   :scale: 80%

Settings
~~~~~~~~

*Settings* contains Links to the *About* and *System settings* sites. The latter contains the language preference and a list of relevant smart contract addresses.

.. image:: images/Settings.png
   :scale: 80%

Furthermore, `User groups <#id1>`_ and `Token collections <#id2>`_ can be found there.

User Groups
^^^^^^^^^^^

User groups can be used for two purposes. Firstly to define "administrators" of a `token collection <#id2>`_ who can add or remove tokens from a collection. Secondly, certain proof types can notify members of a user group about a pending approval that one of them should approve or reject.

Under *My groups* users can message the owner (unless they are the owner) and leave groups (also possible for owners). Upon leaving a group, users can choose to notify the group owner about it or not.

.. image:: images/Groups.png
   :scale: 60%

Editing a group as owner comprises the options to add or remove members and to transfer ownership of the group.

.. image:: images/GroupEdit.png
   :scale: 60%

Token collections
^^^^^^^^^^^^^^^^^

Token collections are a way to curate a list of tokens with a much lower effort then the `token curated registry <#token-curation>`_.

.. image:: images/Collections.png
   :scale: 80%

They can be used for organisations to promote their tokens in one place, for individuals to create portfolios or other use cases.

.. image:: images/CollectionDetails.png
   :scale: 80%

The collection creator can add or remove tokens from the collection, appoint an admin group to do the same or transfer ownership of the collection.

.. image:: images/CollectionEdit.png
   :scale: 80%

Inbox
~~~~~

.. image:: images/Inbox.png
   :scale: 80%
   :align: right

*Your messages* shows all messages sent to you. These can be

- Proof contracts notifying you about pending approvals: for you directly or a group you are a member of
- Reasons why a proof you submitted got rejected
- System notifications like a user leaving a group you created
- Messages from other users

If you get a new message while being on the DApp, the notification bell in the top right corner of the site will turn yellow and take you to the messages site upon clicking.

*Message user* takes you to the option to message other users directly. The QR icon can be used to scan the public address of the recipient instead of having to type or paste it in.

.. image:: images/UserMessage.png
   :scale: 70%

Token curation
~~~~~~~~~~~~~~

*Token curation* takes you to the Token Curated Registry (TCR). Here, anyone with enough *Governance Tokens* (GOV) can participate in curating a list of "official positive action tokens" (OPAT). Users can propose tokens to be voted into the listing as well as challenge them once they are in it.

.. image:: images/TokenCuration.png
   :scale: 80%

Listing
^^^^^^^

Listing is the central place of the TCR, here, the curation of OPATs is happening. After applying a token to the listing that is not already on it, a voting period starts where users can vote for taking it in or not. Only in the reveal period where votes can't be changed anymore it will become public what users voted for, not before. Depending on the quorum parameter as can be seen under `Parameters`_ the majority of votes decide what happens. If a token makes it onto the listing, it can be challenged. This triggers another vote/reveal procedure which results in kicking the token off the listing or keeping it. The proposer or challenger has to put GOV on stake and gets rewarded if the vote turns out in their favor or looses GOV if it does not.

To participate in these procedures, a user must have sufficient GOV. This can be claimed under `Management`_ from *Reputation Tokens* (REP) beyond a certain threshold.

.. image:: images/Listing.png
   :scale: 30%

Tokens on the listing will be displayed with a star icon in the list of all `tokens <dapp-overview.html#tokens>`_.

.. image:: images/TokensWithOPAT.png
   :scale: 35%

Management
^^^^^^^^^^

Here, users can claim GOV from REP if they are above a certain threshold. This claiming can be repeated once the user spends GOV and falls below the amount they have as REP.

The other functionality here is to delegate some of your GOV to a user of your choosing and see how much GOV in total was delegated to you, if any. The idea being that an user might trust another user to participate in governance procedures on their behalf because they are for instance more competent in a certain topic. Unlike all other token transfers, this amount can be refunded from the sender. 

.. image:: images/Management.png
   :scale: 30%

Parameters
^^^^^^^^^^

Similar to collectively deciding if a token should be on the listing or not, the parameters of the system as a whole can be changed collectively. The procedure is similar and involves proposing a new value for a parameter, followed by vote and reveal phase after which the new value is accepted or rejected. The GOV required to put on stake for a proposed reparameterization are much higher then those for proposing a token. The idea being that reparameterizations should happen very rarely and only if a proposer is "serious" about it.

.. image:: images/Parameters.png
   :scale: 35%
