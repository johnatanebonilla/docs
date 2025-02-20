---
layout: feature
title: 'Person[erg]'
shortdef: 'person agreement with the ergative argument'
udver: '2'
---

## Person[erg]

Finite verbs in many Indo-European languages agree in [person](u-feat/Person) and number with their subject.

In Basque (a <a href="http://en.wikipedia.org/wiki/Polypersonal_agreement">polypersonal language</a>),
certain verbs overtly mark agreement with up to three arguments:
one in the absolutive [case](u-feat/Case),
one in ergative and
one in dative.
Thus in _dakarkiogu_ “we bring it to him/her”,
_akar_ is the stem (_ekarri_ = “bring”),
_d_ stands for “it” (absolutive argument is the direct object of transitive verbs),
_ki_ stands for the dative case,
_o_ stands for “he” and
_gu_ stands for “we” (ergative argument is the subject of transitive verbs).

* `Person[abs]` is the person of the absolutive argument of the verb. The corresponding feature in Interset 2.041 is called `absperson`.
* `Person[erg]` is the person of the ergative argument of the verb. The corresponding feature in Interset 2.041 is called `ergperson`.
* `Person[dat]` is the person of the dative argument of the verb. The corresponding feature in Interset 2.041 is called `datperson`.

One may want to use just `Person` instead of `Person[abs]`.
However, there are two issues with that (at least in Basque).
First, the absolutive argument is not always the subject. For transitive verbs, it is the object, so the parallelism with nominative-accusative languages would be weak anyway.
Second, we cannot avoid `Number[abs]` (both `Number` and `Number[abs]` can occur at one word)
and thus we keep `Person[abs]` to demonstrate that it is the same layer of agreement for both the features.

### <a name="1">`1`</a>: first person ergative argument

#### Examples

* [eu] _dakarkio<b>gu</b>_ `Person[erg]=1`
* [eu] _<b>dizkizuet</b>_ (lemma _*edun_) `Number[erg]=Sing|Person[erg]=1` `|` `Number[abs]=Plur|Person[abs]=3` `|` `Number[dat]=Plur|Person[dat]=2`
* [eu] _<b>dizkizugu</b>_ (lemma _*edun_) `Number[erg]=Plur|Person[erg]=1` `|` `Number[abs]=Plur|Person[abs]=3` `|` `Number[dat]=Sing|Person[dat]=2`

### <a name="2">`2`</a>: second person ergative argument

#### Examples

* [eu] _dakarkio<b>zu</b>_ `Person[erg]=2`
* [eu] _<b>dizkidazu</b>_ (lemma _*edun_) `Number[erg]=Sing|Person[erg]=2` `|` `Number[abs]=Plur|Person[abs]=3` `|` `Number[dat]=Sing|Person[dat]=1`

### <a name="3">`3`</a>: third person ergative argument

#### Examples

* [eu] _<b>zizkigun, dizkigu</b>_ (lemma _*edun_) `Number[erg]=Sing|Person[erg]=3` `|` `Number[abs]=Plur|Person[abs]=3` `|` `Number[dat]=Plur|Person[dat]=1`
* [eu] _<b>zizkieten, dizkiete</b>_ (lemma _*edun_) `Number[erg]=Plur|Person[erg]=3` `|` `Number[abs]=Plur|Person[abs]=3` `|` `Number[dat]=Plur|Person[dat]=3`

<!-- Interlanguage links updated Út 9. května 2023, 20:03:44 CEST -->
