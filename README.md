![LUKS logo](https://gitlab.com/cryptsetup/cryptsetup/wikis/luks-logo.png)

What the ...?
=============
**Cryptsetup** is utility used to conveniently setup disk encryption based
on [DMCrypt](https://gitlab.com/cryptsetup/cryptsetup/wikis/DMCrypt) kernel module.

These include **plain** **dm-crypt** volumes, **LUKS** volumes, **loop-AES**
and **TrueCrypt** (including **VeraCrypt** extension) format.

Project also includes **veritysetup** utility used to conveniently setup
[DMVerity](https://gitlab.com/cryptsetup/cryptsetup/wikis/DMVerity) block integrity checking kernel module.

LUKS Design
-----------
**LUKS** is the standard for Linux hard disk encryption. By providing a standard on-disk-format, it does not  
only facilitate compatibility among distributions, but also provides secure management of multiple user passwords.  
In contrast to existing solution, LUKS stores all setup necessary setup information in the partition header,  
enabling the user to transport or migrate his data seamlessly.

Why LUKS?
---------
 * compatiblity via standardization,
 * secure against low entropy attacks,
 * support for multiple keys,
 * effective passphrase revocation,
 * free.

[Project home page](https://gitlab.com/cryptsetup/cryptsetup/).
-----------------

[Frequently asked questions (FAQ)](https://gitlab.com/cryptsetup/cryptsetup/wikis/FrequentlyAskedQuestions)
--------------------------------

Download
--------
All release tarballs and release notes are hosted on [kernel.org](https://www.kernel.org/pub/linux/utils/cryptsetup/).

**The latest cryptsetup version is 1.6.6**
  * [cryptsetup-1.6.6.tar.xz](https://www.kernel.org/pub/linux/utils/cryptsetup/v1.6/cryptsetup-1.6.6.tar.xz)
  * Signature [cryptsetup-1.6.6.tar.sign](https://www.kernel.org/pub/linux/utils/cryptsetup/v1.6/cryptsetup-1.6.6.tar.sign)
    _(You need to decompress file first to check signature.)_
  * [Cryptsetup 1.6.6 Release Notes](https://www.kernel.org/pub/linux/utils/cryptsetup/v1.6/v1.6.6-ReleaseNotes).

Previous versions
 * [Version 1.6.5](https://www.kernel.org/pub/linux/utils/cryptsetup/v1.6/cryptsetup-1.6.5.tar.xz) -
   [Signature](https://www.kernel.org/pub/linux/utils/cryptsetup/v1.6/cryptsetup-1.6.5.tar.sign) -
   [Release Notes](https://www.kernel.org/pub/linux/utils/cryptsetup/v1.6/v1.6.5-ReleaseNotes).
 * [Version 1.6.4](https://www.kernel.org/pub/linux/utils/cryptsetup/v1.6/cryptsetup-1.6.4.tar.xz) -
   [Signature](https://www.kernel.org/pub/linux/utils/cryptsetup/v1.6/cryptsetup-1.6.4.tar.sign) -
   [Release Notes](https://www.kernel.org/pub/linux/utils/cryptsetup/v1.6/v1.6.4-ReleaseNotes).

Source and API docs
-------------------
For development version code, please refer to [source](https://gitlab.com/cryptsetup/cryptsetup/tree/master) page,
mirror on [kernel.org](https://git.kernel.org/cgit/utils/cryptsetup/cryptsetup.git/) or [GitHub](https://github.com/mbroz/cryptsetup).

For libcryptsetup documentation see [libcryptsetup API](https://gitlab.com/cryptsetup/cryptsetup/wikis/API/index.html) page.

NLS PO files are maintained by [TranslationProject](http://translationproject.org/domain/cryptsetup.html).

Help!
-----
Please always read [FAQ](https://gitlab.com/cryptsetup/cryptsetup/wikis/FrequentlyAskedQuestions) first.
For cryptsetup and LUKS related questions, please use the dm-crypt mailing list, [dm-crypt@saout.de](mailto:dm-crypt@saout.de).

If you want to subscribe just send an empty mail to [dm-crypt-subscribe@saout.de](mailto:dm-crypt-subscribe@saout.de).

You can also browse [list archive](http://www.saout.de/pipermail/dm-crypt/) or read it through
[web interface](http://news.gmane.org/gmane.linux.kernel.device-mapper.dm-crypt).
