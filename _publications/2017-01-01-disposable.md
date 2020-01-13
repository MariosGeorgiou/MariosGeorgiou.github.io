---
title: "Cryptography with Disposable Backdoors"
collection: publications
permalink: /publication/2017-01-01-disposable
excerpt: 'Construction of one-time memories relative to a classical oracle.'
date: 2019-01-01
venue: 'MDPI'
paperurl: 'http://uoigroeG.github.io/files/cryptography_with.pdf'
---
Backdooring cryptographic algorithms is an indisputable taboo in the cryptographic literature for a
good reason: however noble the intentions, backdoors might fall in the wrong hands, in which case security
is completely compromised. Nonetheless, more and more legislative pressure is being produced to enforce
the use of such backdoors.
In this work we introduce the concept of disposable cryptographic backdoors which can be used only
once and become useless after that. These exotic primitives are impossible in the classical digital world
without stateful and secure trusted hardware support, but, as we show, are feasible assuming quantum
computation and access to classical stateless hardware tokens.
Concretely, we construct a disposable (single-use) version of message authentication codes, and use
them to derive a black-box construction of stateful hardware tokens in the above setting with quantum
computation and classical stateless hardware tokens. This can be viewed as a generic transformation from
stateful to stateless tokens and enables, among other things, one-time programs and memories. This is
to our knowledge the first provably secure construction of such primitives from stateless tokens.
As an application of disposable cryptographic backdoors we use our constructed primitive above to
propose a middle-ground solution to the recent legislative push to backdoor cryptography: the conflict
between Apple and FBI.We show that it is possible for Apple to create a one-time backdoor which unlocks
any single device, and not even Apple can use it to unlock more than one, i.e., the backdoor becomes
useless after it is used. We further describe how to use our ideas to derive a version of CCA-secure
public key encryption, which is accompanied with a disposable (i.e, single-use, as in the above scenario)
backdoor.
