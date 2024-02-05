..
        SPDX-License-Identifier: CC-BY-SA-4.0 or-later
        SPDX-FileCopyrightText: 2024 grommunio GmbH

Sent Folder
===========

As per `MSDN docs
<https://learn.microsoft.com/en-us/office/client-developer/outlook/mapi/processing-a-sent-message>`_,
mail clients can set the MAPI property ``PR_SENTMAIL_ENTRYID`` and
point to a folder where a message should be moved once it has been
sent. Note that this is mutually exclusive with
``PR_DELETE_AFTER_SUBMIT`` (only one action can be performed).
