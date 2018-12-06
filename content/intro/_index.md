---
title: "Εισαγωγή - Testing"
author: ["IOANNIS ZANNOS"]
lastmod: 2018-12-06T15:58:35+02:00
draft: false
weight: 1
---

## Αντικείμενο {#αντικείμενο}

Εδώ δείχνουμε μια εικόνα που είναι αποθηκευμένη στο standard μέρος.  Αυτό το μέρος είναι εκτός του markdown περιεχομενου, δηλαδή εκτός του `contents`. Αυτό σημαίνει ότι είμαστε ελέυθεροι να σβήνουμε τα περιεχόμενα του `contents` κάθε φορά πριν μετατρέπουμε το παρόν αρχείο σε markdown.

To ζητούμενο path που θα μπεί το αρχείο είναι `<hugo-site-root>/static/images/<filename.png>`.

<a id="orgadb2ec3"></a>

{{< figure src="/images/org-mode-unicorn-logo.png" caption="Figure 1: This is the caption actually and it is: Org Logo" >}}

Αν παραλείψουμε το `/images/` από το path που θα μπεί το αρχείο τότε θα το βρεί το hugo αντίστοιχα στο:  `<hugo-site-root>/static/<filename.png>`. Πχ:

<a id="orgd9f727f"></a>

{{< figure src="/PEARLLITHIC.png" caption="Figure 2: H εικόνα αυτή βρίσκεται κατευθείαν μέσα στον φάκελο `/static/`." >}}

Το path που βάλαμε για την παραπάνω εικόνα ήταν απλά: `/PEARLLITHIC.png`.

Εδώ συνεχίζουμε με το κείμενο.


## Εργαλεία {#εργαλεία}

This is chapter 2!

There should be an image following here:

{{< figure src="/chapter.jpg" >}}
