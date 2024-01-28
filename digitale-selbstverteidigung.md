---
tags: Materialliste, digitale Selbstverteidigung, Linkliste
---
Materialien zur digitalen Selbstverteidigung
===
* Webseite der Cryptoparty Köln-Bonn https://crypto.koeln
* Mailkontakt: kontakt@crypto.koeln ([PGP](https://pgp.mit.edu/pks/lookup?op=get&search=0xE51CD26133E2CC11) Fingerprint 8CB5 66A7 C55D 3D25 037A  533D E51C D261 33E2 CC11)
* Fediverse: @cryptoparty@bonn.social
## Browser-Plugins
* uBlock Origin
  * [Available Filter Templates](https://letsblock.it/filters) einige hilfreiche Filter
  * [The Ultimate Superuser’s Guide to uBlock Origin](https://www.maketecheasier.com/ultimate-ublock-origin-superusers-guide/)
* [Privacy Badger](https://privacybadger.org/)
* Disconnect
* [Noscript](https://noscript.net/)
* Clear URLs [Firefox](https://addons.mozilla.org/en-US/firefox/addon/clearurls/) [Chrome](https://addons.mozilla.org/en-US/firefox/addon/clearurls/) Entfernt Tracking-Felder aus URLs. Beispiele: 
    * Die Adresse <code>https://www.heise.de/news/Digitalstrategie-Oeffentliche-Hand-will-mit-Open-Source-digital-souveraen-werden-7164622.html?wt_mc=sm.red.ho.botti.messenger.link.link</code> mit dem Parameter <code>?wt_mc=sm.red.ho.botti.messenger.link.link</code> enthält den Hinweis, dass dieser Link aus dem Telegram-Channel des Heise-Verlags heraus aufgerufen wurde. Der Parameter ist für den Aufruf des Artikels nicht nötig und dient nur der Analyse, woher ein Seitenzugriff stammt.
    * Die Adresse <code>https://www.google.com/search?q=datenschutz&rlz=1C1GCEA_enCH977CH977&oq=da&aqs=chrome.0.69i59j69i57j69i59l2j35i39j0i67j0i512l4.661j0j15&sourceid=chrome&ie=UTF-8</code> gibt mit <code>&rlz=1C1GCEA_enCH977CH977&oq=da&aqs=chrome.0.69i59j69i57j69i59l2j35i39j0i67j0i512l4.661j0j15&sourceid=chrome&ie=UTF-8</code> Hinweise auf den Browser (Chrome), die verwendete Sprache (Englisch), ob die Nutzerin den Browser selbst installiert hat und vor der Installation schon ein Google-Konto besaß. Eine genaue Aufschlüsselung liefert [unfurl](https://dfir.blog/unfurl/?url=https://www.google.com/search?q=dfir.blog&rlz=1C1CHBF_en-GBGB901GB901).
    * Die Methode wird bald nicht mehr funktionieren. Facebook hat bereits [Gegenmaßnahmen](https://www.ghacks.net/2022/07/17/facebook-has-started-to-encrypt-links-to-counter-privacy-improving-url-stripping/) ergriffen.
* [Decentraleyes](https://addons.mozilla.org/de/firefox/addon/decentraleyes/) Schützt vor Tracking durch "gratis", zentralisiertes Abliefern von Content. Es sorgt dafür, dass Anfragen Netzwerke wie "Google Hosted Libraries" nicht erreichen, aber imitiert sie, sodass die Seiten intakt bleiben. Ergänzt reguläre Contentsperren.
    * [LocalCDN](https://addons.mozilla.org/de/firefox/addon/localcdn-fork-of-decentraleyes/) Emuliert externe Frameworks (z.B. jQuery, Bootstrap, AngularJS) und stellt sie als lokale Ressource bereit. Verhindert unnötige Anfragen von Drittanbietern an Google, StackPath, MaxCDN und mehr. Vorbereitete Regeln für uBlock Origin/uMatrix.
* [JShelter](https://jshelter.org/) An anti-malware Web browser extension to mitigate potential threats from JavaScript, including fingerprinting, tracking, and data collection!
* [HowTo: Beliebige Add-Ons in Fennec auf Android installieren](https://www.kuketz-blog.de/howto-beliebige-add-ons-in-fennec-auf-android-installieren/)
* [Consent-O-Matic](https://github.com/cavi-au/Consent-O-Matic) ([Projektseite](https://consentomatic.au.dk/))
> Consent-O-Matic is a browser extension (available for Chrome, Firefox, Edge and Safari on iOS/MacOS) that recognizes a great deal of those CMP (Consent Management Provider) pop-ups that we've all grown to both love and hate. But since you've told it your preference in cookies upon installation, it will autofill those forms for you when it encounters them. And let you know that it did so, with a satisfying little checkmark next to its icon. Nice.

&nbsp;&nbsp;&nbsp;&nbsp;Wir haben das Plugin unter Firefox und Chrome getestet und konnten auf spiegel.de, heise.de, sueddeutsche.de, faz.de sowie zeit.de keine Wirkung feststellen. Falls Sie erfolgreich testen konnten und Hinweise haben, wo unser Fehler liegt, melden Sie sich gern.

* Das Add-on "[I don't care about cookies](https://www.i-dont-care-about-cookies.eu/)" sollte man nicht oder zumindest nicht ohne zusätzliche Blocker (wie uBlock Origin) nutzen, denn es versucht zwar, die datenschutzfreundlichsten Einstellungen zu klicken, arbeitet dabei aber nicht zuverlässig. *Update 16.9.2022:* Das Plugin wurde von Avast [übernommen](https://www.i-dont-care-about-cookies.eu/whats-new/acquisition/). Avast steht in der Kritik, seit Google die Erweiterung im Jahr 2019 aus dem Chrome Web Store [entfernt](https://9to5google.com/2019/12/17/chrome-avast-extensions-removed/) hat, weil es Nutzungsdaten an den Hersteller sendete. Als Antwort auf die Übernahme bildete sich bereits ein [Fork](https://github.com/OhMyGuus/I-Dont-Care-About-Cookies).
* Mitaka - a browser extension makes your OSINT search & scan easily
    * [github](https://github.com/ninoseki/mitaka)
    * [Artikel in der c't](https://www.heise.de/tests/Browser-Erweiterung-Mitaka-fuer-Security-Recherchen-7137996.html)
    * [Download für Chrome](https://chrome.google.com/webstore/detail/mitaka/bfjbejmeoibbdpfdbmbacmefcbannnbghttps://chrome.google.com/webstore/detail/mitaka/bfjbejmeoibbdpfdbmbacmefcbannnbg)
    * [Download für Firefox](https://addons.mozilla.org/de/firefox/addon/mitaka/)
* Firefox Relay ermöglicht das Erstellen von Wegwerf-Mailadressen.
* [Certificate Patrol](http://patrol.psyced.org/) CertPatrol implements ''pinning'' for Firefox/Mozilla/SeaMonkey roughly as now recommended in the User Interface Guidelines of the World Wide Web Consortium (W3C). Certificate pinning may be considered annoying, but actually it is frequently reminding you that you should be more careful and paranoid.
    * für [Firefox](https://addons.thunderbird.net/en-us/firefox/addon/certificate-patrol/)
* [Ad nauseam - clicking ads so you don't have to](https://adnauseam.io/) As online advertising becomes ever more ubiquitous and unsanctioned, AdNauseam works to complete the cycle by automating ad clicks universally and blindly on behalf of its users
* [Bypass Paywalls Clean combines all soft paywall hacks into one neat package](https://linuximpact.com/bypass-paywalls-clean-combines-all-soft-paywall-hacks-into-one-neat-package/) We've all been there. You've clicked on a fascinating link, and been sucked into the witty intro. A few seconds later, usually just as you've almost made it to the end of the first sentence of the second paragraph, the text blurs, and a pop-up appears in the centre of your vision. Yes, you've hit the soft paywall, and now your day is ruined. You'll have to stop randomly cruising from article to article or exploring a website's deep archives, and do some actual work instead. Fortunately, there's an easy way to quickly bypass most soft paywalls.
    
## Alternative Browser
* [Contra Chrome](https://contrachrome.com/comic/page01/) erläutert in Comicform die Datenschutzprobleme in Googles Browser
* [Chromium stable downloads](https://www.chromium.org/getting-involved/download-chromium)
* [Browser-Nutzung unter Android – Digitaler Schutzschild Teil1](https://www.kuketz-blog.de/browser-nutzung-unter-android-digitaler-schutzschild-teil1/)
* [Browser-Nutzung am Desktop – Digitaler Schutzschild Teil2](https://www.kuketz-blog.de/browser-nutzung-am-desktop-digitaler-schutzschild-teil2/)
* [Browser privacy settings you need to change right away: Chrome, Firefox and more](https://www.cnet.com/how-to/browser-privacy-settings-you-need-to-change-right-away-chrome-firefox-and-more/)
* [Browser-Tests bei Mike Kuketz](https://www.kuketz-blog.de/?s=browser)
* Fennec
* Bromite
* [Librewolf](https://librewolf.net/)

## Browser absichern
[Mehr Sicherheit und Anonymität in Firefox über »about:config« erreichen](https://gnulinux.ch/mehr-sicherheit-und-anonymitaet-in-firefox-%C3%BCber-about-config-erreichen)

## Mailverschlüsselung
* [Thunderbird](https://www.thunderbird.net/)
* [GPG for Windows](https://gpg4win.de/)
* [Einfach, sicher, kostenlos: DGNcert für sichere Mail-Kommunikation ](https://www.dgn.de/dgncert/so_funktionierts.html) Offene Punkte: Wo wird das Zertifikat erzeugt? Erzeugt DGN nicht nur die Signaturkette sondern gleich das ganze Zertifikat bei sich selbt, könnte es kompromitiert sein. Weiterhin ist die DGN-CA nicht in allen Mailclients im Lieferzustand enthalten, was zu einer Fehlermeldung führt, wenn jemand eine mit einem DGN-Zertifikat signierte Mail erhält, die aber mangels CA nicht überprüft werden kann.
* Kagel Blog: [PGP Schlüssel generieren wie ein Experte](https://www.kagel.ch/artikel/pgp-schluessel-generieren-wie-ein-experte/) Normalerweise, wenn Sie einen Schlüssel generieren, erhalten Sie standardmässig einen RSA Schlüsselpaar (meistens mit einer Länge von 2048 oder 4096 Bits), wobei der Hauptschlüssel zertifizieren und signieren kann, und ein separater Unterschlüssel für die Verschlüsselung generiert wird. Standardmässig laufen keine der Schlüssel ab. Wir können das jedoch optimieren!

## Vertrauenswürdige Mailanbieter
* [Posteo](https://posteo.de)
* [Mailbox.org](https://mailbox.org)

## Wegwerf-Mailadressen
* [anonbox](https://anonbox.net/index.de.html) (CCC)
* [Spamgourmet](https://www.spamgourmet.com/index.pl) (Spende wird erbeten)
* [Trashmail](https://trashmail.com/)
* Aus dem [Privacy-Handbuch](https://almnet.de/privacy-handbuch/privacy-handbuch-html/handbuch_31g.htm)
    * [spambog.com](http://www.spambog.com/) (weitere E-Mail Domains auf der Webseite, Account kann mit Passwort gesichert werden, Löschen der Mails ist möglich, Session-Cookies erforderlich)
    * [OneWayMail.com](http://onewaymail.com/) (weitere E-Mail Domains auf der Webseite, keine Cookies oder Javascript nötig, E-Mails können gelöscht werden, 5 weitere Domains)
    * [trash-mail.com](http://www.trash-mail.com/) (keine Cookies oder Javascript nötig, E-Mails können gelöscht werden)
    * [mailcatch.com](http://www.mailcatch.com/) (keine Cookies oder Javascript nötig, E-Mails können gelöscht werden)
    * [mailinator.com](http://www.mailinator.com/) (bietet 5 weitere Domains, keine Cookies oder Javascript nötig, E-Mails können gelöscht werden, POP3-Abruf möglich)
    * [weg-werf-email.de](http://www.weg-werf-email.de/) (Session-Cookies erforderlich, Passwortschutz möglich)
    * [GuerrillaMail](https://www.guerrillamail.com/) (HTTPS, Session-Cookies erforderlich, E-Mails können gelöscht werden)
* Yahoo bietet das Einrichten von Wegwerfadressen nach dem Format ```<freiWaehlbareZeichenkette>-<variablerZusatz>@yahoo.com``` an.
* Gmail bietet die Möglichkeit, die vorhandene Adresse um einen mit einem Pluszeichen abgetrennten Zusatz zu erweitern, zum Beispiel ```<meinName>+<variablerZusatz>@gmail.com```. Das Pluszeichen wird allerdings von einigen Webformularen nicht anerkannt. Darüber hinaus ist der Trick natürlich bekannt, so dass sich leicht von einer dergestalt aufgebauten Mailadresse auf die eigentliche Hauptadresse schließen lässt.

## Datenträgerverschlüsselung
* [Veracrypt](https://veracrypt.fr/) verschlüsselt wahlweise ganze Datenträger oder erstellt verschlüsselte virtuelle Laufwerke in frei wählbarer Größe.
* [Cryptomator](https://cryptomator.org/) With Cryptomator, the key to your data is in your hands. Cryptomator encrypts your data quickly and easily. Afterwards you upload them protected to your favorite cloud service.
* [Boxcryptor](https://www.boxcryptor.com/en/) (kommerzielles Produkt)
* [EncFS](https://vgough.github.io/encfs/)
* [ecryptfs](http://ecryptfs.org/)
* [CryFS](https://www.cryfs.org/) kommandozeilenbasiert, verschlüsselt Daten in Cloudspeichern
* [Shufflecake: plausible deniability for multiple hidden filesystems on Linux](https://shufflecake.net/) Shufflecake is a tool for Linux that allows to create multiple hidden volumes on a storage device in such a way that it is very difficult, even under forensic inspection, to prove the existence of such volumes. This is useful for people whose freedom of expression is threatened by repressive authorities or dangerous criminal organizations, in particular: whistleblowers, investigative journalists, and activists for human rights in oppressive regimes. You can consider Shufflecake a "spiritual successor" of tools such as Truecrypt and Veracrypt, but vastly improved: it works natively on Linux, it supports any filesystem of choice, and can manage multiple nested volumes per device, so to make deniability of the existence of these partitions really plausible.
* [rclone](https://rclone.org/) Rclone is a command-line program to manage files on cloud storage. It is a feature-rich alternative to cloud vendors' web storage interfaces. Over 70 cloud storage products support rclone including S3 object stores, business & consumer file storage services, as well as standard transfer protocols.
  * [Cloudspeicher mit rclone verschlüsseln](https://gnulinux.ch/cloudspeicher-mit-rclone-verschluesseln) Das FLOSS Tool rclone eignet sich hervorragend zur Dateisynchronisierung zwischen unseren Rechnern und den Cloudanbietern unserer Wahl. Als Dreingabe ermöglicht rclone eine Ende-zu-Ende Verschlüsselung. Lesezeit: 30 Minuten

## Dateiverschlüsselung
* [7-Zip](https://7-zip.org/)
    
## Dateien sicher löschen
Die hier beschriebenen Werkzeuge arbeiten vor allem auf mechanischen Festplatten zuverlässig. Für USB-Sticks oder SSD-Platten reichen sie wahrscheinlich nicht aus.
* ```dd if=/dev/zero of=/dev/sda bs=4M status=progress``` (```/dev/sda``` hier durch den zu löschenden Datenträger ersetzen). Hinweise wie "Platte siebenmal mit Zufallswerten überschreiben" stammen aus dem letzten Jahrhundert, werden seitdem brav nachgeplappert, stimmen aber schon lange nicht mehr. Wer es schafft, eine mit ```dd``` gelöschte mechanische Festplatte auch nur teilweise wieder auszulesen, möge uns gern eine Mail schreiben.
* ```shred``` (Unix-Kommando)
* [File Shredder](http://www.fileshredder.org/)
* [DBAN](https://www.heise.de/download/product/dariks-boot-and-nuke-dban-54943)
* [CCleaner](https://www.ccleaner.com/ccleaner)
* [Parted Magic](https://partedmagic.com/)
* Hammer, Bohrer oder was die rohe Physik zu bieten hat
    
## Dateien vielleicht wieder herstellen
* [Recuva](https://www.ccleaner.com/recuva)
* [Testdisk](https://www.cgsecurity.org/wiki/TestDisk_DE)
* [Photorec](https://www.heise.de/download/product/photorec-45742)
* [NTFS undelete](https://www.heise.de/download/product/ntfs-undelete-57833)
* [Sys Rescue CD](http://www.system-rescue-cd.org/Changes-x86/)
* [Ultimate Boot CD](http://www.ultimatebootcd.com/)
* Kommerzielle Tools
    * [Undelete Plus](https://www.undeleteplus.com/)
    * [EaseUS Data Recovery Wizard](https://www.easeus-software.com/de/datenrettung-software/datenrettung-assistent.html) Bei [heise.de](https://www.heise.de/download/specials/Software-zur-Datenrettung-6008456) gibt es einen Gutscheincode
    * [Disk Drill](https://www.cleverfiles.com/de/data-recovery-software.html)
    * [R-Studio](https://www.heise.de/download/product/r-studio-16902)
    
## Passwortverwaltung
* [Keepass](https://keepass.info/)
    * [Keepass-Diff](https://github.com/Narigo/keepass-diff) A CLI-tool to diff Keepass (.kdbx) files. Useful, if syncing with Dropbox or NextCloud and getting multiple files due to conflicts. 
    * [KeepassXC](https://keepassxc.org/) ist eine optisch etwas modernere Version
      * Falls bei der Installation die Meldung “MSVCP140.dll fehlt” oder “VCRUNTIME140.dll fehlt” auftaucht:
        [Lösung: MSVCP140.dll oder VCRUNTIME140.dll fehlt](https://www.giga.de/downloads/windows-10/tipps/msvcp140.dll-fehlt-so-behebt-ihr-den-fehler-auch-vcruntime140.dll/) aufrufen und https://aka.ms/vs/16/release/vc_redist.x64.exe (für 64-Bit-Windows) wählen
      * Unter Ubuntu tauchten Fehler bei Autotype auf. Auf einem Testsystem half die Installation von ```ydotool``` mittels ```sudo apt install ydotool```.
    * [Passwörter systemübergreifend verwalten und synchronisieren mit Keepass](https://www.heise.de/ratgeber/Passwoerter-systemuebergreifend-verwalten-und-synchronisieren-mit-Keepass-5064157.html)
    * [Passwortverwaltung mit KeePass(XC|DX) – Digitaler Schutzschild Teil3](https://www.kuketz-blog.de/passwortverwaltung-mit-keepassxcdx-digitaler-schutzschild-teil3/)
    * [KeePassXC: Auto-Type und Browser-Add-on im Alltag nutzen – Passwörter Teil1](https://www.kuketz-blog.de/keepassxc-auto-type-und-browser-add-on-im-alltag-nutzen-passwoerter-teil1/)
    * [KeePassDX: Magikeyboard und AutoFill im Android-Alltag nutzen – Passwörter Teil2](https://www.kuketz-blog.de/keepassdx-magikeyboard-und-autofill-im-android-alltag-nutzen-passwoerter-teil2/)
    * [Syncthing: KeePass-Datenbank zwischen PC und Android synchronisieren – Passwörter Teil3](https://www.kuketz-blog.de/syncthing-keepass-datenbank-zwischen-pc-und-android-synchronisieren-passwoerter-teil3/)
    * [Bitwarden](https://bitwarden.com/) verwaltet Passwörter zentral auf einem Server und gleicht die lokalen Kopien damit ab. Bei Bedarf kann auch ein eigener Server zum Speichern der Passwortdatenbank genommen werden. Bitwarden beherrscht inzwischen auch Passkeys.
        * Unter Ubuntu ließ sich das Appimage nicht starten und stürzte mit einem Coredump ab. Abhilfe schaffte die Installation zweier Pakete mittels ```sudo apt install qt6-wayland``` sowie ```sudo apt install xcb```.
    * [Passwortmanager-Apps im Privacy-Check](https://www.heise.de/ratgeber/Passwortmanager-Apps-im-Privacy-Check-5050304.html)
* Bin ich von einem Datenleck betroffen?
    * [Have I been pwned?](https://haveibeenpwned.com/)
      * [See your identity pieced together from stolen data](https://www.abc.net.au/news/2023-05-18/data-breaches-your-identity-interactive/102175688)
    * [HPI Identity Leak Checker](https://sec.hpi.de/ilc/)
* Zwei-Faktor-Authentifizierung
    * tOTP
        * [AndOTP](https://github.com/andOTP/andOTP) (im [Playstore](https://play.google.com/store/apps/details?id=org.shadowice.flocke.andotp&hl=en&gl=US))
        * [FreeOTP](https://freeotp.github.io/) (im [Playstore](https://play.google.com/store/apps/details?id=org.fedorahosted.freeotp&hl=en&gl=US))
        * [Python tOTP Demo](https://python-totp.herokuapp.com/)
    * FIDO2
        * [Solokeys](https://solokeys.com/)
        * [Yubikey](https://www.yubico.com/)
    * [2FA QR code generator](https://stefansundin.github.io/2fa-qr/) Secret zum Testen: JBSWY3DPEHPK3PXP
    * [TOTP Token Generator](https://totp.danhersam.com/)
* [List of the most common passwords](https://en.wikipedia.org/wiki/List_of_the_most_common_passwords)
* [The to 500 worst passwords of all time](http://www.whatsmypass.com/the-top-500-worst-passwords-of-all-time)
* [Real-World Passwords](https://www.schneier.com/blog/archives/2006/12/realworld_passw.html)
* [123456 – Deutschlands häufigste Passwörter im Jahr 2021](https://www.heise.de/news/123456-Deutschlands-haeufigste-Passwoerter-im-Jahr-2021-6297181.html)
* t3n: [Das sind die beliebtesten unsicheren Passwörter 2023: Platz 1 werdet ihr leicht erraten](https://t3n.de/news/unsicherse-passwoerter-2023-1597613/) Herrlich einfach machen es sich immer noch viele Nutzerinnen und Nutzer bei der Wahl ihrer Passwörter – und müssen im Nachhinein feststellen: Das war wahnsinnig leichtsinnig.
* [Cracking passwords, or why use password_hash()](https://www.michalspacek.com/talks/cracking-passwords-or-why-use-password_hash-phpce)
* [1password alternatives](https://www.teampassword.com/blog/1password-alternatives)
* [Passwortlisten](https://wiki.skullsecurity.org/index.php/Passwords)
* [ danielmiessler / SecLists / Passwords ](https://github.com/danielmiessler/SecLists/tree/master/Passwords)
* [Liste von Passwort-Cracking-Tools](https://www.heise.de/ct/13/03/links/084.shtml)
    * [Hashcat](https://hashcat.net/hashcat/)
    * [John the Ripper](https://www.openwall.com/john/)
        * [Anleitung](https://blog.varonis.de/john-the-ripper/)
    * [Brutedum](https://github.com/GitHackTools/BruteDum)
        * [Anleitung](https://null-byte.wonderhowto.com/how-to/brute-force-ssh-ftp-vnc-more-with-brutedum-0197449/)
* [Choosing a secure password](https://boingboing.net/2014/02/25/choosing-a-secure-password.html)
* Bruce Schneier: [Why I hate password rules](https://www.schneier.com/blog/archives/2021/11/why-i-hate-password-rules.html)
* [Unmasked: What 10 million passwords reveal about the people who choose them](https://wpengine.com/resources/passwords-unmasked-infographic/)
* [Passwörter: 64 Prozent der User verwenden Kennwörter mehrmals](https://www.heise.de/news/Passwoerter-64-Prozent-verwenden-Kennwoerter-mehrmals-7328871.html)
* [AI password cracking](https://www.homesecurityheroes.com/ai-password-cracking/)
* LfDI Berlin: [Anforderungen an ein sicheres Passwort](https://www.datenschutz-berlin.de/buergerinnen-und-buerger/selbstdatenschutz/it-sicherheit/passwortsicherheit/)
  * Ratgeber [Umgang mit Passwörtern](https://www.datenschutz-berlin.de/fileadmin/user_upload/pdf/broschueren/2020-BlnBDI-Ratgeber_Passwoerter.pdf) (PDF)
 
## Alternative Messenger
* [Signal](https://signal.org/)
    * [veröffentlichter Server-Quellcode](https://github.com/signalapp/Signal-Server)
    * [Signal-cli](https://github.com/AsamK/signal-cli/releases/tag/v0.8.4.1) Signal auf Kommandozeile
    * [Signal FOSS](https://www.twinhelix.com/apps/signal-foss/) Signal ohne Google-Bibliotheken
    * Spektrum.de [Mythos Signal: Licht und Schatten beim nicht kommerziellen Messenger](https://www.spektrum.de/news/mythos-signal-licht-und-schatten-beim-nicht-kommerziellen-messenger/2190072) Lange galt Signal als Wunderwaffe gegen Überwachung. Teile der Tech-Community und der digitalen Zivilgesellschaft kritisieren die App jedoch wegen überraschender Datenflüsse, organisatorischer Intransparenz und undemokratischer Machtverhältnisse.
    * [Why not Signal](https://dessalines.github.io/essays/why_not_signal.html) Während dieser Text sehr ausführlich die Nachteile Signals beschreibt, geht er leider händewedelnd über die Nachteile der aufgeführten Alternativen hinweg, beispielsweise den Umstand, dass die bei Matrix anfallenden Metadaten nicht gelöscht werden können oder dass Briar nicht nur kräftig die Akkulaufzeit verringert, sondern auch ständig online sein muss, um eventuell eintreffende Nachrichten zu empfangen, die anderfalls stillschweigend verloren gehen. Die lobenswerte Sorgfalt, die bei der Aufzählung der Signal-Mängel angewandt wurde, hätte der Analyse der Alternativen gut getan.
    * [Signal: Unsere Push-Benachrichtigungen zeigen Spionen nichts](https://www.heise.de/news/Signal-Unsere-Push-Benachrichtigungen-sind-sicher-vor-Spionage-9573116.html) Geheimdienste sammeln Daten aus Push-Benachrichtigungen von Android und iPhone. Beim Signal-Messenger ist da wenig zu holen, sagt die Stiftung.​
* [Threema](https://threema.ch/)
* [Wire](https://wire.com/)
* [Element](https://element.io/) ([Matrix](https://matrix.org/docs/projects/client/element))
    * [Fluffy](https://fluffychat.im/) [Google Playstore](https://play.google.com/store/apps/details?id=chat.fluffy.fluffychat)
    * [Ein Fehler in der Matrix](https://www.cr-online.de/blog/2022/06/02/ein-fehler-in-der-matrix/) 
Mit Matrix gibt es ein Open-Source-Projekt, das es gestattet, einen Ende-zu-Ende-verschlüsselten Messengerdienst mit dem üblichen Funktionsumfang auf eigenem Metall zu betreiben. Unter Kontrollgesichtspunkten ist das erstmal super. Die öffentliche Verwaltung in Frankreich setzt deshalb künftig komplett auf dieses Konzept.1 Alles gut? Leider nicht ganz.
* OMEMO (XMPP)
    * [Dino](https://dino.im/)
    * [Gajim](https://gajim.org)
    * [Conversations](https://conversations.im/)
* [Briar](https://briarproject.org/) versendet Nachrichten über das Tor-Netz und kann im Extremfall komplett ohne Internet Daten via Bluetooth übertragen
* [Delta Chat](https://delta.chat/) (SMTP)
* Messenger-Vergleiche
    * [Freie Messenger](https://www.freie-messenger.de/)
    * [Messenger-Matrix von Mike Kuketz](https://www.messenger-matrix.de)
    * [Vergleichstabelle 1](https://www.picflash.org/viewer.php?img=p9NCOGXNV05TY.png)
    * [Vergleichstabelle 2](https://www.cryptoparty.in/cryptopartykbn/messenger)
    * [Vergleichstabelle 3](https://docs.google.com/spreadsheets/d/1-UlA4-tslROBDS9IqHalWVztqZo7uxlCeKPQ-8uoFOU/htmlview) als Google-Doc
    * [Secure messaging apps in comparison](https://www.securemessagingapps.com/)
    * [Whatsapp-Alternativen - Messenger im Überblick](https://www.verbraucherzentrale.de/wissen/digitale-welt/datenschutz/whatsappalternativen-messenger-im-ueberblick-13055)
    * [Neue WhatsApp-Datenschutzrichtlinie: Messengerdienste im Vergleich](https://netzpolitik.org/2021/neue-whatsapp-datenschutzrichtlinie-messengerdienste-im-vergleich/#)
* c't-Artikel zu Whatsapp-Alternativen
    * [Immer wieder WhatsApp? Eine Übersicht über Messenger-Dienste](https://www.heise.de/ct/artikel/Immer-wieder-WhatsApp-Eine-Uebersicht-ueber-Messenger-Dienste-4416561.html)
    * [Sieben Messenger gegen WhatsApp](https://www.heise.de/select/ct/2019/11/1558438610171788)
    * [Grundlagen sicherer privater Kommunikation](https://www.heise.de/select/ct/2019/11/1558438564072031)
* [Datenschutzfreundliche und sichere WhatsApp-Alternativen](https://www.kuketz-blog.de/datenschutzfreundliche-und-sichere-whatsapp-alternativen/)
* [Messenger-Apps auf dem Smartphone – Digitaler Schutzschild Teil6](https://www.kuketz-blog.de/messenger-apps-auf-dem-smartphone-digitaler-schutzschild-teil6/)
* [Internes Dokument verrät, welche Daten das FBI von welchem Messenger erhält](https://www.derstandard.at/story/2000131585109/internes-dokument-verraet-welche-daten-das-fbi-von-welchem-messenger)
* [FBI über Messenger: An welche Daten von WhatsApp & Co. US-Strafverfolger kommen ](https://www.heise.de/news/FBI-ueber-Messenger-An-welche-Daten-von-WhatsApp-Co-US-Strafverfolger-kommen-6282456.html)
* [Goldbug](http://goldbug.sourceforge.net/)
* heise+: [Messenger-IDs: Warum Messenger nach Ihrer Telefonnummer fragen](https://www.heise.de/hintergrund/Messenger-IDs-Warum-Messenger-nach-Ihrer-Telefonnummer-fragen-5066901.html?seite=all)
* [SimpleX Chat](https://github.com/simplex-chat) Der Messenger wirbt mit Dezentralität sowie Vermeidung von Metadaten. Allerdings befindet sich das Projekt noch in einem sehr frühen Entwicklungsstadium und eignet sich nur für Technikaffine. Wer uns testweise kontaktieren möchte, kann dies unter [dieser Adresse:](https://simplex.chat/contact/#/?v=1&smp=smp%3A%2F%2F6iIcWT_dF2zN_w5xzZEY7HI2Prbh3ldP07YTyDexPjE%3D%40smp10.simplex.im%2Fif9WJLaxuFXDC61EK6jzdw2vS8ufy_VK%23MCowBQYDK2VuAyEAGPjf6hkFpUronsxUOAlkJ-qjUy3muP58CmhjGwqhT1o%3D))
* [Link Previews: How a Simple Feature Can Have Privacy and Security Risks](https://www.mysk.blog/2020/10/25/link-previews/)

* [Berty](https://berty.tech/) kommuniziert über ein P2P-Netz. Leider gelingt es nicht zuverlässig, sich miteinander zu verknüpfen. Das gegenseitige Scannen von QR-Codes scheint noch halbwegs zu funktionieren, aber der Einladungslink führt zu einer Fehlermeldung. Auch der Nachrichtenaustausch schlägt häufig fehl. In unseren Tests gingen drei Viertel der Testnachrichten verloren.
* [Zulip](https://zulip.com/)
* [Messenger- und Video-Dienste: Bundeskartellamt zu Datenschutz, Transparenz und Interoperabilität](https://www.bundeskartellamt.de/SharedDocs/Meldung/DE/Pressemitteilungen/2023/17_05_2023_SU_MD.html) [PDF](https://www.bundeskartellamt.de/SharedDocs/Publikation/DE/Sektoruntersuchungen/Sektoruntersuchung_MessengerVideoDienste.pdf?__blob=publicationFile&v=4)
  * heise: [Bundeskartellamt: Messenger-Dienste verletzen Verbraucherrechte ](https://www.heise.de/news/Bundeskartellamt-Messenger-Dienste-verletzen-Verbraucherrechte-9058967.html) Die deutschen Kartellwächter haben eine umfangreiche Untersuchung zu Video- und Messengerdiensten vorgelegt. Fazit: Datenschutz ist vielen zu unwichtig. "Ebenfalls verbraucherrechtlich heikel sei, dass Dienste beim Synchronisieren von Kontakten auch jene Personen erfassen, die bisher nicht bei dem jeweiligen Dienst registriert sind. Das könnten Verstöße gegen die DSGVO sein, wenn die Daten dauerhaft gespeichert würden. Dies gelte auch dann, wenn die Telefonnummern verschlüsselt dargestellt werden. Einige Dienste könnten die Verbraucher besser darüber informieren, wie die Sicherheit der Kommunikation gewährleistet wird, zum Beispiel mit Ende-zu-Ende-Verschlüsselung, meint das Bundeskartellamt."

## Alternative Suchmaschinen
* [YaCy](https://yacy.net/) - eine verteilte Suchmaschine
* [Duck Duck Go](https://duckduckgo.com/)
* [Startpage](https://www.startpage.com/) - greift anonymisiert auf den Google-Index zu
* [Metager](https://metager.de/) - Metasuchmaschine
* [Searx](https://searx.space/) - Suchmaschine mit der Möglichkeit zum Einrichten eigener Instanzen
* [Qwant](https://www.qwant.com/)
* [Neeva](https://neeva.com/) - kostenpflichtig, verlangt Anmeldung über Mailadresse
* [Yandex](https://yandex.com/) - Bildersuchmaschine
* [etools](https://www.etools.ch/) - Metasuchmaschine
* [Ecosia](https://www.ecosia.org/)
* Einschätzungen von [digitalcourage](https://digitalcourage.de/digitale-selbstverteidigung/es-geht-auch-ohne-google-alternative-suchmaschinen)

## Videokonferenzsysteme
* Jitsi ([Liste](https://pads.ccc.de/ep/pad/view/jitsiliste/latest))
    * [BSI: Sicherer Einsatz von Jitsi Meet](https://www.allianz-fuer-cybersicherheit.de/SharedDocs/Downloads/Webs/ACS/DE/BSI-CS/BSI-CS_143.html) ([PDF](https://www.allianz-fuer-cybersicherheit.de/SharedDocs/Downloads/Webs/ACS/DE/BSI-CS/BSI-CS_143.pdf;jsessionid=DCE35917E34B411EF9D2AA345D26C2DA.internet472?__blob=publicationFile&v=4))
* Big Blue Button ([Liste](https://pads.ccc.de/ep/pad/view/ro.e01-$L2cd/latest))
    * [Senfcall](https://www.senfcall.de/) (kommerzieller Anbieter)
    * [BigBlueButton Installationsanleitung (Version 2.5)](https://www.c-rieger.de/bigbluebutton-v-2-5-inkl-greenlight/)
* [Alfaview](https://alfaview.com) (kommerzieller Anbieter)
* [Mailbox.org](https://mailbox.org) (setzt auf Jitsi auf und kostet 3 € pro Monat)
* [Sichere Videokonferenz](https://sichere-videokonferenz.de/) wirbt mit DSGVO-Konformität und Hosting in Deutschland

## Anonymes Surfen
### Tor
* [Tor Project](https://torproject.org)
* [OnionShare](https://onionshare.org/)
* für iOS [Onionbrowser](https://onionbrowser.com/) (gratis mit Spendenmöglichkeit)
* [Set TOR Exit Node – TOR Browser, Country Code, Specific Node](https://www.optimizationcore.com/security/set-tor-exit-node-tor-browser-country-code-specific-node/)
* [Anonsurf](https://linuxhint.com/anonsurf/) Send all your (Kali) Linux data trough Tor.
* [How to circumvent the Great Firewall and connect to Tor from China?](https://support.torproject.org/censorship/connecting-from-china/)
* [What is Snowflake?](https://support.torproject.org/censorship/what-is-snowflake/)
* [Dark Web Map](https://www.hyperiongray.com/dark-web-map/)
* [Tor Statistics](https://metrics.torproject.org/) The Tor network is one of the largest deployed anonymity networks, consisting of thousands of volunteer-run relays and millions of users. Users, advocates, relay operators, and journalists can better understand the Tor network through data and analysis made available by Tor Metrics. Analyzing a live anonymity system must be performed with great care so that the users' privacy is not put at risk. Any metrics collected must not undermine the anonymity or security properties of the Tor network.
* [Missing Link: Wie sicher ist der Anonymisierungsdienst Tor?](https://www.heise.de/hintergrund/Missing-Link-Wie-sicher-ist-der-Anonymisierungsdienst-Tor-6272025.html)
* [How to find the administrator of an onion site?](https://medium.com/@moon_osint/how-to-find-the-administrator-of-an-onion-site-89d176b0061a)
  * [TOR Node List](https://www.dan.me.uk/tornodes) — This page contains a full TOR nodelist
  * [ExoneraTor](https://metrics.torproject.org/exonerator.html) —Check IP if it is used as a TOR node
  * [Onionite](https://github.com/lukechilds/onionite) — Node info, top nodes by consensus weight with search function
  * [Collector Tor](https://collector.torproject.org/archive/relay-descriptors/microdescs/) — Archive of nodes IPs and ports
* [Dark Web Map](https://www.hyperiongray.com/dark-web-map/)
* [Darknetlive](https://darknetlive.com/)
  * [Darkweb Forums](https://darknetlive.com/forums/)
* [Anleitung](https://wiki.ubuntuusers.de/Tor/Programme_zur_Nutzung_von_Tor_konfigurieren/), um Thunderbird über Tor und Privoxy laufen zu lassen
  * Englischsprachige [Anleitung](https://linuxconfig.org/install-tor-proxy-on-ubuntu-20-04-linux) zur Installation von Tor unter Ubuntu und der Möglichkeit, unter anderem die Shell über Tor kommunizieren zu lassen.
  * [Warum das Darknet nicht nur für Kriminelle ist ](https://www.heise.de/news/Warum-das-Darknet-nicht-nur-fuer-Kriminelle-ist-7237406.html) Das Darknet hat einen miserablen Ruf, zu Unrecht. Schließlich kann man im Darknet auch viele sinnvolle Dinge anstellen. c't 3003 gibt Tipps.
        1. Install-Datei überprüfen
        1. Vorsicht mit eigenen Daten
        1. Vertraue niemandem
        1. Sicherheitsstufe einstellen
        1. Tails benutzen
* Simplified Privacy: [How you can be deanonymized through Tor](https://simplifiedprivacy.com/how-you-can-be-deanonymized-through-tor/) Tor is an excellent tool for privacy, and we do not recommend you avoid it.  However, there are many limitations to be aware of and ways of using it that can compromise your anonymity on Tor.  This article will discuss just a few of the ways, but there may be others that the public is unaware of.  For example in 2017, the FBI dropped a case against a school worker accused of downloading child pornography because the FBI would have rather let him go than reveal the source code for how they deanonymitized him through Tor.  [1] If you really want to get your privacy game to the next level, consider subscribing for free to our new content by email, by Session messenger, RSS feed, or Nostr.
   1. JavaScript based attacks
   1. Cookies
   1. Compromised Exit Nodes
   1. Compromised Middle Relays
   1. Compromised Entrance Guards
   1. Opening Files Outside Tor
   1. Ultrasonic Sounds
 * [Operation Liberty Lane (LE Running Gaurd and middle nodes to deanonymize HS users) ](https://www.reddit.com/r/TOR/comments/19benkx/operation_liberty_lane_le_running_gaurd_and/) Operation Liberty Lane (FBI/DHS joint operation) is a multi-national law enforcement operation that involves the United States, Brazil, Germany, and the United Kingdom, and targets users of illegal hidden services. It appears this once theoretical attack has been operationalized and has unmasked thousands of users. The NCA and FBI have jointly developed a software program called "Good Listener" that involves LE spinning up as many guard and middle nodes as possible, and then using a timing attack to correlate the IP at the malicious gaurd to the timing at the illegal HS. It appears that this is only possible once the HS has been identified and the traffic to it can be interecepted and fed into the program.There was a few posts previously about cases where users using TAILS and WHONIX were caught so a NIT was ruled out, we now have our answer. This next part is only a guess, but it's likely KAX17 was run by the German government in support of this operation. 
 
### Andere Netze
* [ZeroNet](https://zeronet.io) ein zensurresistentes P2P-Netz, das erst durch Tor anonym wird
* Wie gut ist mein Browser wiedererkennbar?
    * [Cover your Tracks](https://coveryourtracks.eff.org/) (früher Panopticlick)
    * [Am I unique?](https://amiunique.org/)
    * [Whoer](https://whoer.net/)
    * [Browser-Fingerprint-Studie der Friedrich-Alexander-Universität](https://browser-fingerprint.cs.fau.de/)
    * [Browserleaks](https://browserleaks.com/) 
    * [Schemeflood](https://schemeflood.com/) erkennt einen Computer browserübergreifend anhand der installierten Programme
    * [FPmon](https://github.com/fpmon/fingerprinting-monitor) für Chrome zeigt an, ob und wenn ja welche Fingerprinting-Techniken eine Webseite nutzt
    * [fingerprint.com](https://fingerprint.com/) Powered by the most accurate device fingerprinting technology, Fingerprint enables engineers to prevent fraud, improve user experiences, and better understand their traffic.
* [Tribler](https://www.tribler.org/)
* [I2P](https://geti2p.net/de/)
* [Freenet](https://freenetproject.org/)
* [gnu:net](https://gnunet.org/de/index.html)
* [JonDo](https://www.anonym-surfen.de/)
    * [JonDoFox](https://www.anonym-surfen.de/jondofox.html)
* [Retroshare](https://retroshare.cc/) Chat, Instant Messenger, E-Mail, Newsgroups, Anonymes/-Filesharing, Darknet, Voice over IP, Videokonferenz, Soziales Netzwerk, Internet Relay Chat
* [Entwurf eines Gesetzes zur Änderung des Strafgesetzbuches - Strafbarkeit des Betreibens krimineller  Handelsplattformen im Internet und des Bereitstellens entsprechender Server-Infrastrukturen](https://www.bundesrat.de/SharedDocs/drucksachen/2021/0101-0200/147-1-21.pdf?__blob=publicationFile&v=1)
* [HowTo: Internet-Zensur umgehen und anonym bleiben](https://www.kuketz-blog.de/howto-internet-zensur-umgehen-und-anonym-bleiben/)

## VPN
* [Schnelles und einfaches VPN mit Wireguard](https://www.golem.de/news/open-source-schnelles-und-einfaches-vpn-mit-wireguard-2106-156912.html)
  * [Rosenpass](https://rosenpass.eu/#start) Build post-quantum-secure VPNs with WireGuard
* [Israeli firm Kape Technologies buys ExpressVPN raising privacy concerns](https://www.hackread.com/israeli-firm-kape-technologies-expressvpn-privacy/)
* [Kape Technologies buys ExpressVPN for $936 mln](https://www.reuters.com/technology/kape-technologies-buys-expressvpn-936-mln-2021-09-13/)
* [Sicheres Surfen: Britisch-israelische Firma Kape kauft ExpressVPN](https://www.heise.de/news/Sicheres-Surfen-Britisch-israelische-Firma-Kape-kauft-ExpressVPN-6192012.html)
* [Report: No-Log VPNs Reveal Users' Personal Data and Logs](https://www.vpnmentor.com/blog/report-free-vpns-leak/)
* [Mullvad VPN](https://mullvad.net/en/)
    * [Mullvad, DNS over HTTPS and DNS over TLS](https://mullvad.net/de/help/dns-over-https-and-dns-over-tls/)
* [Mozilla VPN](https://www.mozilla.org/de/products/vpn/)
* [NordVPN](https://nordvpn.com/de/download/): Android, iOS, Linux, macOS, Windows sowie Chrome, Edge, Firefox, Android TV
    * [NordVPN Has Completed an Application Security Audit (2019)](https://nordvpn.com/wp-content/uploads/2020/01/6-11-2019_NordVPN-Has-Completed-an-Application-Security-Audit.pdf)
* [ProtonVPN](https://protonvpn.com/), Android, iOS, Linux, macOS, Windows
    * [All Proton VPN apps are now open source and audited (2020)](https://protonvpn.com/blog/open-source/)
    * [Proton VPN’s no-logs policy confirmed by an external audit (April 2022)](https://protonvpn.com/blog/no-logs-audit/)

## Alternative Betriebssysteme für Android-Telefone
* [Lineage](https://lineageos.org/)
* [Resurrection Remix](https://resurrectionremix.com/)
* [e](https://e.foundation/)
* [Graphene](https://grapheneos.org/)
* [Calyx](https://calyxos.org/)

## Tails
* [Tails](https://tails.boum.org)
    * [Warnings: Tails is safe but not magic!](https://tails.boum.org/doc/about/warnings/)
* [Anleitungsheft bei Capulcu](https://capulcu.blackblogs.org/neue-texte/bandi/)
* heise+: [Hochsicherheits-Linux auf USB-Stick: Geschützt surfen und arbeiten mit Tails](https://www.heise.de/ratgeber/Security-Mit-Tails-sicher-im-Internet-unterwegs-6289028.html?seite=all)

## Whonix
* [Whonix](https://www.whonix.org/)

## Qubes
* [Qubes](https://www.qubes-os.org/)

## Backups
* [Duplicati](https://www.duplicati.com/) (Artikel in der [c't](https://www.heise.de/select/ct/2019/24/1573928793884407))
* [restic](https://restic.net/)
* [Bacula](https://www.bacula.org/)
* [bareos](https://www.bareos.com/)
 
## Kollaboratives Arbeiten
* [Cryptpad](https://cryptpad.fr/)
* [HackMD](https://hackmd.io/) 
* [Obsidian](https://obsidian.md/)
* [Taskcards](https://www.taskcards.de/) (Padlet-Alternative)
* [Gobby](https://gobby.github.io/)
* [Etherpad](https://etherpad.org/)
* [Kolab](https://kolab.org/) Kolab Groupware is a Free Software groupware solution for Email communications, Events & Appointments, Contacts and more. It supports mixed client environments because of an open storage format, and the use of well-established, standard protocols such as IMAP and SMTP.
* [OnlyOffice](https://www.onlyoffice.com/)

## Apps
* [Datenkrake Google: Android saugt rund 20x mehr Daten ab als iOS](https://www.maclife.de/news/datenkrake-google-android-rund-20x-mehr-daten-ios.html)
* [Mobile Handset Privacy: Measuring The Data iOS and Android Send to Apple And Google](https://www.scss.tcd.ie/doug.leith/apple_google.pdf)

### Android
* Alternativer Appstore [F-Droid](https://www.f-droid.org/)
    * [Aurora Store](https://f-droid.org/en/packages/com.aurora.store/) ermöglicht anonymes Installieren von Apps aus dem Google-Playstore und gibt genauere Auskunft über möglicherweise unerwünschte Eigenschaften.
* [Blokada](https://blokada.org/)
* [NetGuard Firewall – Android unter Kontrolle Teil 4](https://www.kuketz-blog.de/netguard-firewall-android-unter-kontrolle-teil4/)
### iOS
* [Netguard](https://apps.apple.com/de/app/netguard/id446320156)
* [Newpipe](https://newpipe.net/) ist ein alternativer Youtube-Client mit einigen Erweiterungsmöglichkeiten wie Werbeblockern

## Schadsoftareabwehr
* [desinfec't](https://www.heise.de/download/product/desinfect-71642)
* [virustotal](https://www.virustotal.com/gui/home/upload)
* [ClamAV](https://www.clamav.net/) Open Source, im Vergleich zu kommerziellen Produkten langsame Versorgung mit Signaturenupdates und schlechte Erkennungsraten. Wird häufig auf Fileservern eingesetzt, um dort abgelege Windows-Programme auf Schadcode zu untersuchen
    * [ClamTK](https://github.com/dave-theunsub/clamtk/)
    * [Clamwin](https://clamwin.com/)
    * [Moon Secure](https://sourceforge.net/projects/moonav/)
* [Bitdefender](https://github.com/bitdefender) auf Github
* [Avira](https://github.com/Avira) auf Github
* [Armadito](https://github.com/armadito/armadito-av) auf Github
* [Open Antivirus](http://www.openantivirus.org/index.php)
* [Virenschutz unter Linux](https://www.heise.de/tipps-tricks/Virenschutz-unter-Linux-3885535.html)
* [Neue Malware-Familie für Linux entdeckt](https://www.heise.de/news/Neue-Malware-Familie-fuer-Linux-entdeckt-6211764.html)
* [Ist Kaspersky wirklich ein Problem?](https://www.spektrum.de/news/it-sicherheit-ist-kaspersky-wirklich-ein-problem/2000236) Das Bundesamt für Sicherheit in der Informationstechnik (BSI) warnt vor dem russischen Unternehmen. Doch wie berechtigt es ist, Kaspersky als unsicher zu bezeichnen, bleibt unklar.

## Identitätsdiebstahl
* Heise: [Identitätsdiebstahl: Erste Hilfe bei Onlinebetrug unter Ihrem Namen](https://www.heise.de/ratgeber/Identitaetsdiebstahl-Erste-Hilfe-bei-Onlinebetrug-unter-ihren-Namen-7452745.html) Kriminelle kaufen mit illegal erworbenen Login-Daten auf Ihre Rechnung ein oder posten Beschimpfungen in Ihrem Namen? Das sollten Sie jetzt tun.
* Erstmaßnahmen
  * Ein vertrauenswürdiges System verwenden.
  * Passwörter ändern
    * des gekaperten Accounts
    * aller angeschlossenen Konten  
  * Konto im Auge behalten. Rechnungen überprüfen
  * Kreditkarten sperren lassen (116116)
  * Eventuell Anzeige erstatten
* Weitere Maßnahmen
  * Mailkonto auf unbekannte Weiterleitungen prüfen.
  * Ordner für gesendete Nachrichten überprüfen.
  * Alle Mails nach sensiblen Informationen durchsehen (Namen, Anschriften, Telefonnummern, Geburtsdaten, Kontoinformationen). 
  * System auf Schadsoftware scannen (beispielsweise mit [desinfec't](https://www.heise.de/download/product/desinfect-71642). Im Positivfall eventuell forensisch sichern lassen und neu aufsetzen
* LfDI Berlin: [Hilfe, mein Kundenkonto wurde gehackt! Was tun gegen Identitätsdiebstahl und Accountübernahme?](https://www.datenschutz-berlin.de/jahresbericht-2022#_idTextAnchor056) Identitätsmissbrauch im Onlinehandel ist ein großes Ärgernis für die betroffenen Personen. Auch in diesem Jahr haben wir wieder einige Beschwerden zu diesem Thema erhalten. Die gute Nachricht ist, dass betroffene Personen selbst etwas tun können, um sich vor Identitätsmissbrauch zu schützen. Aber auch die Unternehmen sind in der Pflicht, Maßnahmen zum Schutz ihrer Kund:innen zu ergreifen.


## Links
* Linkliste der c't zum [Privatsphärenschutz](https://www.heise.de/select/ct/2022/16/softlinks/y46t)
* [Datenschutzrechtliche Selbstauskunft](https://ct.de/ycyu)
* [Ungewöhnliche IT-Sicherheits- und Datenschutztipps Teil 1](https://www.kuketz-blog.de/ungewoehnliche-it-sicherheits-und-datenschutztipps-teil1/)
* [Ungewöhnliche IT-Sicherheits- und Datenschutztipps Teil 2](https://www.kuketz-blog.de/ungewoehnliche-it-sicherheits-und-datenschutztipps-teil2/)
* [Werkzeuge zur digitalen Selbstverteidigung](https://flaschenpost.piratenpartei.de/2021/03/05/werkzeuge-zur-digitalen-selbstverteidigung/)
* [Datenschutzfreundliche Web-Frontends für YouTube, Twitter, Instagram, Reddit und Co.](https://www.kuketz-blog.de/datenschutzfreundliche-web-frontends-fuer-youtube-twitter-instagram-reddit-und-co/)
* De-Mail
    * [Bullshit made in Germany: So hosten Sie Ihre De-Mail, E-Mail und Cloud direkt beim BND!](https://media.ccc.de/v/30C3_-_5210_-_de_-_saal_g_-_201312282030_-_bullshit_made_in_germany_-_linus_neumann)
    * [Digitale Behördenbriefe Telekom-Chef erklärt De-Mail zum »toten Gaul«](https://www.spiegel.de/netzwelt/web/timotheus-hoettges-telekom-chef-erklaert-de-mail-zum-toten-gaul-a-3a60e22c-9769-4e7a-a39d-1567a91fb857)
* [Google’s FLoC Is a Terrible Idea](https://www.eff.org/deeplinks/2021/03/googles-floc-terrible-idea)
* [Beschlagnahme von E-Mails in aller Heimlichkeit](https://netzpolitik.org/2021/beschlagnahme-von-e-mails-in-aller-heimlichkeit/)
* [Task-Force will Nutzung von US-Clouddienstleistern prüfen](https://www.golem.de/news/datenschutz-task-force-will-nutzung-von-us-clouddiensten-pruefen-2102-154206.html)
* [Deine Daten, Deine Rechte](https://deinedatendeinerechte.de/)
* [Cookie Consent Speed.Run](https://cookieconsentspeed.run/)
* [Terms and Conditions Apply](https://termsandconditions.game/) versuche, alle AGB abzulehnen.
* [Over the wire wargames](https://overthewire.org/wargames/)
* [Bildungswesen: Entlarvung der häufigsten Microsoft-Mythen](https://www.kuketz-blog.de/bildungswesen-entlarvung-der-haeufigsten-microsoft-mythen/)
* [Ein halbes Jahr im Leben von Malte Spitz](https://www.zeit.de/datenschutz/malte-spitz-vorratsdaten) anhand von mit öffentlich einsehbaren Informationen verknüpften Vorratsdaten
* [E-Mail-Konto gehackt - Was Sie jetzt tun müssen](https://www.heise.de/hintergrund/E-Mail-Konto-gehackt-Was-Sie-jetzt-tun-muessen-6207187.html)
* [Alexa, Siri, Google: Bericht listet von Sprachassistenten gesammelte Daten auf ](https://www.golem.de/news/alexa-siri-google-bericht-listet-von-sprachassistenten-gesammelte-daten-auf-2110-160543.html)
* [Für Anfänger/Bequeme: Werbung und Tracker unter iOS/Android systemweit verbannen](https://www.kuketz-blog.de/fuer-anfaenger-bequeme-werbung-und-tracker-unter-ios-android-systemweit-verbannen/)
* [Appcheck Mobilsicher](https://appcheck.mobilsicher.de/)
* [Checkliste: Neues Smartphone sicher einrichten (Android)](https://mobilsicher.de/checkliste/neues-smartphone-bekommen-so-richten-sie-es-ein-android)
* Metadaten aus Dateien löschen
    * [Exiftool](https://exiftool.org/)
    * [Metadata Anonymization Toolkit](https://exiftool.org/)
    * [MAT2](https://0xacab.org/jvoisin/mat2)
* Pentesting Cheat Sheet [1337_file.txt](https://raw.githubusercontent.com/Leetcore/1337-observer/main/1337_file.txt)
* [You probably don’t need to worry about public WiFi anymore](https://www.washingtonpost.com/technology/2022/09/26/public-wifi-privacy/)
* [Datenanfragen](https://www.datenanfragen.de/) Unternehmen müssen Dir Auskunft über Deine Daten geben und sie wenn nötig berichtigen oder sogar löschen. Als gemeinnütziger Verein helfen wir Dir, diese Rechte zu nutzen – natürlich kostenlos und ohne Registrierung.
* Heise: [FAQ: Grundlagenwissen zu Cyberangriffen und wie sich Risiken verringern lassen](https://www.heise.de/ratgeber/Cyberangriffe-Welche-es-gibt-und-wie-sich-Risiken-verringern-lassen-7523370.html) Cyberangriffe können jeden betreffen, doch mit ein paar einfachen Maßnahmen können Sie Ihr persönliches Risiko zumindest minimieren
* Verbraucherzentrale Niedersachsen: [Fakeshop-Finder: Prüfen Sie, ob ein Online-Shop seriös ist](https://www.verbraucherzentrale-niedersachsen.de/fakeshop-finder) Mit dem Fakeshop-Finder können Sie einen kostenlosen URL-Check durchführen, um vor der Bestellung zu erfahren, ob ein unbekannter Online-Shop vielleicht ein Fakeshop sein könnte. Außerdem können Sie herausfinden, wie der Shop von anderen Verbraucherinnen und Verbrauchern bewertet wird.
    
## Schnitzeljagd
Unter https://cloud.datenburg.org/s/csXbXDseep7Qo6N findest Du die Keepass-Datenbank Netzwaerts.kdbx. Um sie öffnen zu können, brauchst Du ein Passwort. Suche hierzu im Netz nach einem Zitat von Alan Moore, das mit “People shouldn't be afraid of their government." beginnt. Der _zweite_ Satz (mit Groß- und Kleinschreibung, Freizeichen und Punkt, aber ohne Anführungsstriche) ist das Passwort, mit dem Du die Keepass-Datei geöffnet bekommst. Du findest dort einen einzigen Eintrag. Dieser Eintrag hat ein Kommentarfeld mit weiteren Anweisungen. Viel Erfolg!)


## Cloudanbieter
* [Systemli](https://www.systemli.org/) hat offenbar als Zielgruppe linksgerichtete Aktivistinnen
* [Verschiedene Cloudspeicher](https://www.heise.de/select/ct/2020/9/softlinks/ytqf?wt_mc=pred.red.ct.ct092020.022.softlink.softlink) Achtung, nicht alle Anbieter befinden sich im Wirkbereich der DSGVO
    * [Telekom Magenta Cloud](https://cloud.telekom-dienste.de/)
    * [Strato Hi-Drive Cloud](https://www.strato.de/cloud-speicher/)
    * [Tresorit](https://www.tresorit.com/) Proprietär, Firmenstandort Schweiz, Kosten für Privatpersonen ab 10 € pro Monat.
    * [Securesafe](https://www.securesafe.com) Proprietär, Firmenstandort Schweiz. Filesharing kostet extra, was erst nach der Registrierung klar wird. Für zwei Zugriffsberechtigte kostet ein Jahr 86 €. Bei Tests gelang es nicht, den beworbenen Businessaccount für 3 € zu erhalten.
* Clouds zum Selberhosten oder Mieten: Sowohl Nextcloud als auch Seafile bieten die Möglichkeit, einen eigenen Server zu betreiben oder sich komplett administrierten Cloudspeicher zu mieten.
    * [Seafile](https://www.seafile.com/en/home/) stellt einen Client zur Verfügung, der das Cloudlaufwerk transparent auf dem eigenen Desktop darstellt.
    * [Nextcloud](https://nextcloud.com/) eine klassische Weboberfläche mit vielen Erweiterungsmöglichkeiten, beispielsweise ein kollaboratives Office
* [Hetzner](https://www.hetzner.com/de/storage/storage-share) Nextlcoud-Hosting in Deutschland, ADV
* [Mailbox.org](https://mailbox.org/de/produkte#cloudspeicher) Mindestkosten 1 € pro Monat. wIm Standardaccount Cloud-Speicher für 3 € pro Monat. Andere Zugriffsberechtigte müssen ebenfalls ein Mailbox-Konto haben. Firmenstandort Deutschland, ADV wird angeboten.

## Soziale Medien
### Fediverse
* Eine [Übersicht](https://fediverse.party/en/miscellaneous/)
* [Mastodon](https://joinmastodon.org)
    * [chaos.social](https://chaos.social)
    * [bonn.social](https://bonn.social)
    * Clients:
      * [Sengi](https://nicolasconstant.github.io/sengi/)
      * [Tusky](https://tusky.app/)
      * [Andstatus](http://andstatus.org/)
* [Pleroma](https://pleroma.social/)
* [Misskey](https://join.misskey.page/en-US/)
* [Peertube](https://joinpeertube.org/)
* [Pixelfed](https://pixelfed.org/)
* [Diaspora](https://diasporafoundation.org/)

## Konten löschen
* [Facebook komplett löschen - so geht's](https://www.heise.de/tipps-tricks/Facebook-komplett-loeschen-so-geht-s-4061586.html])
* [Wie Sie vergessene Accounts finden und löschen](https://www.t-online.de/digital/internet/id_86098254/wie-sie-vergessene-accounts-finden-und-loeschen.html)
* [Just delete me](https://backgroundchecks.org/justdeleteme/)
* [PrivacyBot](https://privacybot.io/) - A free and open source way to delete your data from an exhaustive list of data brokers and people search services.

## Werkzeuge
* [Test Adblock](https://d3ward.github.io/toolz/adblock.html) prüft, ob die wichtigsten Werbetreibenden und Tracker browserseitig blockiert werden.
* Exodus Privacy: [Welche App enthält wie viele Tracker?](https://reports.exodus-privacy.eu.org/en/reports/)
* [Burp suite](http://portswigger.net/burp/proxy.html) Auftrennen von SSL-Verbindungen, um den Datenverkehr von Apps zu untersuchen
* [Kali Linux](https://www.kali.org/) is an open-source, Debian-based Linux distribution geared towards various information security tasks, such as Penetration Testing, Security Research, Computer Forensics and Reverse Engineering.
    * [Learn About the Best Features of Kali Linux](https://www.debugpoint.com/kali-linux-features/) Learn what the key best features and tools about Kali Linux and why it is so popular in the information security industry.
    * heise+: [Hacking-Tools: Hacking-Stick mit Kali Linux einrichten](https://www.heise.de/ratgeber/Hacking-Tools-Hacking-Stick-mit-Kali-Linux-einrichten-6223844.html)
    * [Kali Linux Penetration Testing Tutorial: Step-By-Step Process](https://www.esecurityplanet.com/networks/kali-linux-tutorial/)
* [IT-Sicherheit: Reverse Engineering von Android-Apps](https://www.heise.de/ratgeber/IT-Sicherheit-Reverse-Engineering-von-Android-Apps-4994208.html)
* [Reverse Engineering von Android-Apps](https://www.heise.de/select/ct/2021/1/2031818243766930133)
* [Android-Traffic unter der Lupe](https://www.heise.de/select/ct/2017/13/1497715250712891)
* [Raspberry Pi als Hacking-Werkzeug für SSL- und Man-in-the-Middle-Angriffe](https://www.heise.de/select/ct/2016/10/1463049049556018)
* [mitmproxy](https://mitmproxy.org/)
* [OWASP ZAP](https://www.zaproxy.org/)
* [Cookie Consent Speed Run](https://cookieconsentspeed.run/) Wer schafft es am schnellsten, ein Cookie-Banner so zu beantworten, dass keine Cookies gespeichert werden? Das Spiel wäre lustiger, wenn es nicht aus lauter Tricksereien bestünde, die von realen Webseiten praktiziert werden.
* [clickclickclick](https://clickclickclick.click/)
* [VirusTotal- Analyze suspicious files and URLs to detect types of malware, automatically share them with the security community](https://www.virustotal.com/gui/home/upload)
* [Verschlüsselter Dateiversand mit ablaufenden Links](https://send.vis.ee/)
* [Temporäre Telefonnummer für Verifikations-SMS-Empfang](https://sms24.me/)
* [Tracktor.it](https://www.tracktor.it/) Hilfe beim Erstellen von Beschwerden gegen unzulässiges Tracking
* Zusamenstellungen alternativer Dienste und Programme
    * [Prism Break](https://prism-break.org/en/) 
    * [Privacytools](https://www.privacytools.io)
* Videostreams in der Konsole und ohne Werbung ansehen
    * [Mein YouTube Terminal Workflow](https://paper.wf/kubikpixel/mein-youtube-terminal-workflow)
    * [Mediatheken & TV im Terminal](https://paper.wf/kubikpixel/mediatheken-und-tv-im-terminal)
* [Welche meiner Aktivitäten hat Google von mir gespeichert?](https://myactivity.google.com/myactivity)
* [Sherloq](https://github.com/GuidoBartoli/sherloq) Forensische Bildanalyse, unter anderem zum Erkennen von Manipulationen
* Geografischen Ort zu einer IP-Adresse bestimmen
    * [IPLocation](https://www.iplocation.net/)
    * [KeyCDN](https://tools.keycdn.com/geo)
* [Empfehlungsecke: OSINT-Tools](https://www.kuketz-blog.de/empfehlungsecke-osint-tools/)
* [BleachBit](https://www.bleachbit.org/) When your computer is getting full, BleachBit quickly frees disk space. When your information is only your business, BleachBit guards your privacy. With BleachBit you can free cache, delete cookies, clear Internet history, shred temporary files, delete logs, and discard junk you didn't know was there. Designed for Linux and Windows systems, it wipes clean thousands of applications including Firefox, Adobe Flash, Google Chrome, Opera, and more. Beyond simply deleting files, BleachBit includes advanced features such as shredding files to prevent recovery, wiping free disk space to hide traces of files deleted by other applications, and vacuuming Firefox to make it faster. Better than free, BleachBit is open source.
* [Shennina - Automating Host Exploitation with AI](https://github.com/mazen160/shennina) Shennina is an automated host exploitation framework. The mission of the project is to fully automate the scanning, vulnerability scanning/analysis, and exploitation using Artificial Intelligence. Shennina is integrated with Metasploit and Nmap for performing the attacks, as well as being integrated with an in-house Command-and-Control Server for exfiltrating data from compromised machines automatically.
* [Portmaster](https://safing.io/) is a free and open-source application firewall that does the heavy lifting for you. Restore privacy and take back control over all your computer's network activity.
* [Awesome OSINT](https://github.com/jivoi/awesome-osint?tab=readme-ov-file) A curated list of amazingly awesome open source intelligence tools and resources. Open-source intelligence (OSINT) is intelligence collected from publicly available sources. In the intelligence community (IC), the term "open" refers to overt, publicly available sources (as opposed to covert or clandestine sources)

## Allgemeine Tips
* System und Apps aktuell halten
* Backups anlegen
* Abhängigkeiten vermeiden,nicht alles auf ein Pferd setzen
* Passwörter
    * Lange Passwörter wählen. Je länger das Passwort, desto weniger komplex muss es sein, desto leichter lässt es sich merken.
    * Für jedes Konto ein eigenes Passwort wählen (kein Credential Stuffing). 
    * Wiederherstellungs-Mailadressen besonders gut schützen.
    * Passwörter nicht ohne sehr guten Grund mit anderen teilen 
    * Antworten auf Wiederherstellungfragen so wählen, dass sie nicht durch einfaches Nachlesen im Facebook-Profil herausgefunden werden können.
    * SSO über Facebook- oder Google-Konto vermeiden. Erstens fallen bei diesen Diensten unnötige Nutzungsdaten an, zweitens auf diese Weise ein zentraler Angriffspunkt ([SPOF](https://de.wikipedia.org/wiki/Single_Point_of_Failure)), an dem die Sicherheit mehrerer Konten hängt.
    * Regelmäßig nachsehen, ob es Datenlecks gegeben hat ([Havebeenpwned](https://haveibeenpwned.com/), [HPI Identity Leak Checker](https://sec.hpi.de/)).
    * Regelmäßig zwangsweise geänderte Passwörter sind tendenziell schwach, weil sie häufig nach einem Muster (z.B. Passwort+Monat+Jahr) gebildet werden.
    * Passwörter aufzuschreiben kann unter Umständen vertretbar sein. Bei den meisten Menschen sind Taschendiebe, welche im Gedränge das Portemonnaie mit dem Passwortzettel stehlen, nicht an diesem Zettel, sondern an Bargeld und Kreditkarten interessiert).
    * Gedicht- oder Liedanfänge sind als Erzeugungshilfe von Passwörtern nicht mehr geeignet, weil die Passwortcracker-Tools inzwischen entsprechende Datenbanken haben. Gleiches gilt für Ersetzungsregeln ("O" zu "0", "I" zu "1", "B" zu "8", "E" zu "3").
    * Muster auf der Tastatur ("qwerasdf" oder "qaywsx") als Passwort vermeiden.
    * Zwei-Faktor-Authentifizierung (2FA) wählen
* Mails misstrauen. 
    * Links auf Plausibilität testen. Insbesondere Paketdienstleister verlinken bei ihren Sendungsverfolgungen nicht auf Shortlinks, sondern auf irgendwas mit ihrem Namen und Länderkennung ".de", beispielsweise [https://www.dhl.de/de/privatkunden/dhl-sendungsverfolgung.html](https://www.dhl.de/de/privatkunden/dhl-sendungsverfolgung.html). Im Zweifelsfall nach "Sendungsverfolgung $NameDesPaketdiensts" suchen und das gelieferte Ergebnis anklicken. Die Seite [Check short URL](http://checkshorturl.com/expand.php) ermöglicht es, online nachzusehen, was sich hinter einem Shortlink verbirgt.
    * Anhänge nicht blind ausführen. [Virustotal](https://virustotal.com) bietet die Möglichkeit, Dateien online auf Schadcode zu scannen. Achtung, nur Dateien hochladen, deren Inhalt Außenstehende sehen dürfen.
    * Notfalls bei der Absenderin nachfragen, ob sie wirklich etwas geschickt hat.
    * Macros in Office-Dateien im Zweifelsfall nicht aktivieren. Im täglichen Gebrauch kommen Macros nur sehr selten vor. In Bewerbungen oder Rechnungen tauchen sie praktisch nie auf.
    * Swisscybersecrity.net veröffentlichte eine gute [Checkliste zum Erkennen von Phishing](https://www.swisscybersecurity.net/cybersecurity/2022-03-30/wie-sie-phishing-erkennen/0lt0)
        - [ ] Fehlt in der Mailadresse eine persönliche Anrede?
        - [ ] Erhalte ich diese Mail unerwartet?
        - [ ] Versucht der Absender, Druck aufzubauen?
        - [ ] Ist der Text voller Tipfehler?
        - [ ] Verwendet ein angeblich Schweizer Absender "ß" statt "ss"?
        - [ ] Führt der Link zu einer seltsamen URL?
        - [ ] Ist der Firmenname in der URL falsch geschrieben? Die falschen Schreibweisen können sich bisweilen gut verstecken, beispielsweise "arnazon.com_" (mit "rn" statt "m") statt "amazon.com" oder "googIe.com_" (mit großem "I" statt kleinem "l") statt "google.com"
        - [ ] Ist der Firmenname in der URL eine Unterseite einer fremden Website (d.h. der Name steht nicht vor .com oder .sh usw?)
    * Nicht jedes Indiz ist für sich genommen ein eindeutiger Hinweis, aber je mehr davon zutreffen, umso verdächtiger. Ein paar Ergänzungen:
        - [ ] Ist im Adressfeld wirklich Ihre Mailadresse angegeben, oder wendet sich die Mail an jemand Anderen oder "undisclosed recipients"? Das kann bei Newslettern in Ordnung sein, aber wenn sich jemand namentlich an Sie wendet, kommt das selten vor.
    * Google bietet ein (leider etwas pfuschig gebautes) [Quiz](https://phishingquiz.withgoogle.com/) zum Erkennen von Phishing
* Ein gut gepflegtes System und offene Augen sind der beste Virenschutz. Wenn es unbedingt ein Virenscanner sein muss: Der bei Windows mitgelieferte Defender reicht völlig aus. Um ein System offline nach Schadcode zu durchsuchen, eignet sich die beim Heise-Verlag erhältliche [desinfec't](https://www.heise.de/news/Jetzt-herunterladen-Trojaner-mit-Desinfec-t-2020-21-plattmachen-4922300.html)
* Nur selber hosten, wenn Fachwissen und Zeit vorhanden sind
* Sich regelmäßig informieren. Sicherheitslücken weisen nicht von selbst auf sich hin.
    * [heise security](https://www.heise.de/security/news/7_tage_news/)
    * [Golem Security](https://www.golem.de/specials/security/)
    * [CERT Bund](https://www.cert-bund.de/overview)
    * [Firefox Monitor](https://monitor.firefox.com/breaches) Alle von Firefox Monitor erkannten Datenlecks
* [Attending a protest](https://ssd.eff.org/en/module/attending-protest)
* [Kuketz IT-Blog](https://www.kuketz-blog.de/)
    [HowTo: Internet-Zensur umgehen und anonym bleiben](https://www.kuketz-blog.de/howto-internet-zensur-umgehen-und-anonym-bleiben/)
* [Linkliste zur DSGVO](https://blog.forum-politische-bildung.de/sel-igbce-18/2018/05/28/linkliste-zur-dsgvo/)
* [Podcast des LfDI B-W](https://www.baden-wuerttemberg.datenschutz.de/datenfreiheit/)
* [The Joy of Cryptography is a free undergraduate textbook that introduces students to the fundamentals of provable security.](https://joyofcryptography.com/)
* [Heise-Security-Checklisten 2021](https://ftp.heise.de/ct/listings/2021/20/ct_security_checkliste_2022.pdf)
* [Die c’t-Security-Checklisten 2022](https://www.heise.de/ratgeber/Die-c-t-Security-Checklisten-2022-6183129.html)
* [Don't fall for tricky URLs](https://datadetoxkit.org/en/security/trickyURLs/)
* [unredacter](https://github.com/BishopFox/unredacter) liest verpixelten Text
* LfDI Berlin: [Wie sicher ist dein Smartphone? (PDF)](https://www.datenschutz-berlin.de/fileadmin/user_upload/pdf/publikationen/informationsmaterialien/2020-BlnBDI-Ratgeber_Smartphone.pdf)

## Organisationen
* [Chaos Computer Club](https://ccc.de)
    * [CCC Köln](https://koeln.ccc.de)
* [Cryptoparty International](https://cryptoparty.in)
    * [Cryptoparty Köln-Bonn](https://crypto.koeln) ([alternativer Link](https://cryptoparty.in/cryptopartykbn)) Mail: kontakt@crypto.koeln
* [Digitalcourage](https://digitalcourage.de)
* [Epicenter.Works](https://epicenter.works/)
* [Electronic Frontier Foundation](https://www.eff.org/)
* [Frag den Staat](https://fragdenstaat.de/)
* [My Privacy is None of Your Business](https://noyb.eu/en)
* [Uncensored Library](https://www.uncensoredlibrary.com/de)

## Fallbeispiele
### Staatstrojaner
* [Entwurf eines Gesetzes zur Anpassung des Verfassungsschutzrechts](https://dserver.bundestag.de/btd/19/247/1924785.pdf)
* [(Verfassungsblog) Staatstrojaner für Nachrichtendienste: Zur Einführung der Quellen-Telekommunikationsüberwachung im Artikel 10-Gesetz](https://verfassungsblog.de/staatstrojaner-nachrichtendienste/)
* [Verfassungsklage gegen neue Abhörmöglichkeiten der Geheimdienste durch Quellen-TKÜ](https://www.haufe.de/compliance/recht-politik/verfassungsklage-gegen-online-durchsuchung-mit-staatstrojaner_230132_463812.html?ecmId=32727&ecmUid=3358950&chorid=123456789&newsletter=news%2FPortal-Newsletter%2FCompliance%2F403%2F123456789%2F2021-07-09%2FTop-News-Verfassungsklage-gegen-neue-Abhoermoeglichkeiten-der-Geheimdienste-durch-Quellen-TKUe)
* 2017 [Vault 7 (Wikipedia)](https://en.wikipedia.org/wiki/Vault_7)
    * 2017 [WannaCry](https://en.wikipedia.org/wiki/WannaCry_ransomware_attack) 
    * 2017 [Petya](https://en.wikipedia.org/wiki/Petya_(malware)) 
* [Experten sehen "zunehmende Bedrohungslage" durch Cyberangriffe](https://www.heise.de/news/Experten-sehen-zunehmende-Bedrohungslage-durch-Cyberangriffe-6141310.html)
* Pegasus
    * [Wikipedia-Artikel](https://de.wikipedia.org/wiki/Pegasus_(Spyware))
    * [Pegasus internals: Technical Teardown of the Pegasus malware and Trident exploit chain](https://media.ccc.de/v/33c3-7901-pegasus_internals)

### Whatsapp
* [Whatsapp-Sicherheitslücken führen zu enormer Zunahme von E-Mail-Angriffen](https://www.vadesecure.com/de/blog/whatsapp-sicherheitslucken)
* [9 things you need to know about the WhatsApp zero-click spyware attack](https://www.fastcompany.com/90349568/9-things-you-need-to-know-about-the-whatsapp-spyware-attack)
    * [Wie "Pegasus" aufs Handy kommt](https://www.tagesschau.de/investigativ/ndr-wdr/spaeh-software-pegasus-smartphone-101.html)
    * [Spyware Pegasus: Wie die NSO Group für mehr Transparenz sorgen wollte](https://www.heise.de/hintergrund/Pegasus-Wie-die-NSO-Group-fuer-mehr-Transparenz-sorgen-wollte-6141498.html?seite=2)
    * [NSO-Spionagesoftware Pegasus: Null Klicks bis zum totalen Kontrollverlust](https://www.spiegel.de/netzwelt/apps/nso-spionagesoftware-pegasus-null-klicks-bis-zum-totalen-kontrollverlust-a-171b6f46-848f-4674-8dbb-ac906e6594c8)
    * [Snowden fordert Malware wie Atomwaffen zu behandeln](https://www.golem.de/news/pegasus-snowden-fordert-malware-wie-atomwaffen-zu-behandeln-2107-158275.html) Ein Handel mit Atomwaffen ist nicht erlaubt, warum sollte er mit Malware erlaubt sein, fragt Snowden. Amnesty veröffentlicht ein NSO-Erkennungstool.
        * [Mobile Verification Toolkit](https://github.com/mvt-project/mvt)
    * [Der Staatstrojaner-Skandal im Überblick](https://netzpolitik.org/2021/pegasus-der-staatstrojaner-skandal-im-ueberblick/)

## Bücher
* Stefan Mey: [Darknet](https://www.chbeck.de/mey-darknet/product/32823389)
* Cory Doctorov: [Little Brother](https://craphound.com/littlebrother/download/)
* Christian Linke: [Scriptkid - erpresst im Darknet](https://www.dtv.de/buch/scriptkid-erpresst-im-darknet-71810)
* Katharina Nocun: [Daten, die ich rief](https://www.luebbe.de/bastei-luebbe/buecher/politik-und-gesellschaft/die-daten-die-ich-rief/id_6549526)
* Malte Spitz: [Was macht ihr mit meinen Daten?](https://netzpolitik.org/2014/was-macht-ihr-mit-meinen-daten-malte-spitz-erneut-visualisiert-in-buch-und-infografik/)

## Spiele
* Beholder
* Through the darkest of times (Schwerpunkt Widerstand gegen den Nationalsozialismus)
* Ministry of broadcast

## Oft gestellte Fragen - FAQ
### Mein Rechner wurde gehackt und ich beim Betrachten zweifelhafter Seiten gefilmt
Kurze Antwort: mit an Sicherheit grenzender Wahrscheinlichkeit nein
Lange Antwort: Sehen wir uns den Header einer an den Kölner CCC verschickten Mail an:

```
Return-Path: <SRS0=/g3y=3U=tiestudio.co.uk=tie78vrkf14@koeln.ccc.de>
X-Original-To: mail@koeln.ccc.de
Delivered-To: otrs@mail.koeln.ccc.de
Received: from mail.thetiestudio.com (mail.thetiestudio.com [5.77.50.113])
 (using TLSv1.2 with cipher ECDHE-ECDSA-AES256-GCM-SHA384 (256/256 bits))
 (No client certificate requested)
 by w12t.koeln.ccc.de (Postfix) with ESMTPS id B2F7420456
 for <mail@koeln.ccc.de>; Sun, 20 Nov 2022 22:13:12 +0100 (CET)
Received: by mail.thetiestudio.com (Postfix, from userid 10002)
 id F132E51246; Sun, 20 Nov 2022 21:13:11 +0000 (GMT)
To: mail@koeln.ccc.de
Subject: =?UTF-8?B??=
X-PHP-Originating-Script: 10002:mails.php
From: =?UTF-8?B??= <mail@koeln.ccc.de>
MIME-Version: 1.0;
Content-type: multipart/mixed; boundary="--R6TljqRagn"
X-PPP-Message-ID: <20221120211311.64172.19759@mail.thetiestudio.com>
X-PPP-Vhost: tiestudio.co.uk
Message-Id: <20221120211311.F132E51246@mail.thetiestudio.com>
Date: Sun, 20 Nov 2022 21:13:11 +0000 (GMT)
```

Die Zeile ```From: =?UTF-8?B??= <mail@koeln.ccc.de>``` sorgt dafür, dass die Mailadresse des Kölner CCC als Absender erscheint. Diesen Eintrag kann allerdings jede erzeugen. Sie könnte ```olaf.scholz@bundeskanzleramt.de``` dort hinschreiben. So lange ihr Mailserver diese Angabe nicht prüft, geht die Mail in dieser Form erst einmal raus. Erst der empfangende Mailserver könnte prüfen, ob der sendende überhaupt befugt ist, unter dieser Adresse Nachrichten zu verschicken. Vergleichen Sie es, wenn als Absender eines Briefs der Präsident der USA auf dem Umschlag steht, die Briefmarke aber eine der Deutschen Post ist und der Brief laut Stempel in Hamburg eingeworfen wurde. Bei dieser Mail weisen die Zeilen ```Received: by mail.thetiestudio.com (Postfix, from userid 10002)``` sowie ```Message-Id: <20221120211311.F132E51246@mail.thetiestudio.com>``` darauf hin, dass die Mail nicht wie beim oberflächlichen Betrachten behauptet vom CCC Köln, sondern von ```thetiestudio.com``` stammt, auf dessen Seiten es wahrscheinlich eine Sicherheitslücke gibt, die es erlaubt, mit Hilfe eines PHP-Skripts (```X-PHP-Originating-Script: 10002:mails.php```) unter beliebigen Absendenamen Mails zu verschicken.

### Belauscht mich mein Smartphone heimlich?
TL,DR: höchstwahrscheinlich nicht
* Gizmodo [These Academics Spent the Last Year Testing Whether Your Phone Is Secretly Listening to You](https://gizmodo.com/these-academics-spent-the-last-year-testing-whether-you-1826961188)
* EFF [Facebook Doesn't Need To Listen Through Your Microphone To Serve You Creepy Ads](https://www.eff.org/de/deeplinks/2018/04/facebook-doesnt-need-listen-through-your-microphone-serve-you-creepy-ads)
* USA Today [No, Facebook doesn't secretly listen via your microphone to target ads at you](https://eu.usatoday.com/story/tech/2018/04/10/no-facebook-doesnt-secretly-listen-via-your-microphone-target-ads-you/505257002/)
* New Statesman [Testing the long-held belief that Facebook listens to your conversations to advertise stuff](https://www.newstatesman.com/science-tech/social-media/2018/03/testing-facebook-listens-your-conversations-adverts)
* Wired [Facebook's Not Listening Through Your Phone. It Doesn't Have To](https://www.wired.com/story/facebooks-listening-smartphone-microphone/)
* Independent [Is Facebook listening to me through my phone? Mark Zuckerberg finally responds to ‘conspiracy theory’](https://www.independent.co.uk/life-style/gadgets-and-tech/news/facebook-listening-listen-does-is-microphone-app-phone-mark-zuckerberg-a8299281.html)
* Quora [Is Facebook listening to me through my phone's microphone?](https://www.quora.com/Is-Facebook-listening-to-me-through-my-phones-microphone)
* Mashable [People think Facebook is listening to them. Here's how they're fighting back.](https://mashable.com/2017/11/01/facebook-microphone-spying-ads-preventing)
* Phys [No, Facebook doesn't secretly listen via your microphone to target ads at you](https://m.phys.org/news/2018-04-facebook-doesnt-secretly-microphone-ads.html)
* Vox [The perennial debate about whether your phone is secretly listening to you, explained](https://www.vox.com/the-goods/2018/12/28/18158968/facebook-microphone-tapping-recording-instagram-ads)
* Inc [Here's the Real Reason You Think Facebook Is Listening to Your ConversationsNo microphones, no recording. But we know a lot more about how Facebook monitors searches from your contacts, and how you may be seeing ads that match up with shared interests.](https://www.inc.com/john-brandon/heres-real-reason-you-think-facebook-is-listening-to-your-conversations.html)
* Chip [Das Gespenst in der Maschine: Wie Facebook unsere Gespräche heimlich belauscht](https://www.chip.de/news/Wie-Facebook-unsere-Gespraeche-heimlich-belauscht_131223311.html)
* Stern [Hört die Facebook-App wirklich Ihre Privatgespräche mit?](https://www.stern.de/digital/smartphones/facebook--lauscht-die-smartphone-app-wirklich-bei-gespraechen-mit--7488112.html)
* Zeit [Werden wir übers Smartphone abgehört?](https://www.zeit.de/digital/2019-08/facebook-smartphone-apps-illegales-abhoeren-mikrofon-werbung/komplettansicht)
* Mimikama [Ob und wie genau Facebook heimlich mitlauscht, wollten Mitarbeiter des NDR herausfinden.](https://www.mimikama.at/facebook-auf-dem-pruefstand-lauscht-das-unternehmen-mit/)
* NDR [Smartphone-App: Hört Facebook Gespräche mit?](https://www.ndr.de/ratgeber/verbraucher/Smartphone-App-Hoert-Facebook-Gespraeche-mit,facebook2806.html)
* [Schauen Notebooks und Smartphones heimlich zu?](https://medium.com/br-next/schauen-notebooks-und-smartphones-heimlich-zu-ff1e516579a) Seit Beginn der Corona-Pandemie verbringen viele Menschen mehr Zeit in Online-Konferenzen. Wir haben mit technischen Mitteln getestet, ob uns Apps dabei heimlich filmen oder über die Schulter schauen können.
    * br Puls [Können iPhone und Android Handys heimlich mithören? Wir programmieren Apps, um das zu beweisen!](https://www.youtube.com/watch?v=rX2tK-qSVpk) Der im Video durchgeführte Test, bei dem zwei Leute ein paar Minuten über ein Thema reden und nachsehen, was direkt danach passiert, hat weder zur Bestätigung, noch zur Falsifizierung der These irgendeine verallgemeinerbare Aussagekraft. Die Tatsache, dass es technisch möglich ist, eine App zu programmieren, die das Mikrofon anschaltet, ist nicht überraschend. Eine App auf bestimmte Stichworte zu programmieren und damit das Mitlauschen effizienter zu gestalten, ist zwar möglich, konterkatiert aber die These, Apps lauschten heimlich mit, um beliebige Gesprächsinhalte zu Werbezwecken zu analysieren.
    * br Puls [So können Handy und Laptop heimlich zuschauen: Unsere App zeigt wie es geht.](https://www.youtube.com/watch?v=YGKY_F50I_8) Auch diese Reportage bietet keine Überraschungen. Apps können Kameras und Mikrofone anschalten - natürlich, genau dafür sind sie da.
* Kaspersky [Lauschangriff durch Smartphones – Fakt oder Fiktion?](https://www.kaspersky.de/blog/smartphones-eavesdropping/19862/)
* Quarks: [Passgenaue Werbung – Belauschen uns unsere Smartphones? ](https://www.quarks.de/podcast/quarks-daily-spezial-folge-66-passgenaue-werbung-belauschen-uns-unsere-smartphones/)
* La-Liga-App
    * Zeit [Offizielle Liga-App aktiviert Handy-Mikrofone](https://www.zeit.de/digital/datenschutz/2018-06/la-liga-app-spanien-fussball-dsgvo-pay-tv-lizenz-betrug)
    * Deutschlandfunk [Lauschangriff auf spanische Fußball-Fans](https://www.deutschlandfunk.de/liga-app-lauschangriff-auf-spanische-fussball-fans-100.html)

## Schlussbemerkung
Alle hier vorgestellten Maßnahmen sind notwendigerweise unvollständig. Perfekte Sicherheit kann es prinzipbedingt nicht geben. Der Aufwand, sie zu erreichen, steigt exponentiell. Wir können allenfalls die Schwelle für einen Angriff so hoch legen, dass er sich nicht mehr lohnt. Am Ende ist es ein reines Kräftemessen.

Letztlich versuchen wir hier, ein gesellschaftliches Problem mit technischen Mitteln zu bekämpfen. Das ist bestenfalls eine Notlösung. Spätestens seit den Anschlägen auf das World Trade Center beknien wir den Staat, uns möglichst viele Rechte zu nehmen, um uns vor dem Terrorismus zu bewahren. Das mit dem Verlust der Grundrechte klappt auch großartig, der Schutz vor dem Terrorismus hingegen ist größtenteils Sicherheitstheater. An der Flughafenkontrolle werden wir bis auf die Unterwäsche abgetastet und durchleuchtet, Flüssigkeiten ab 100 ml und Nagelscheren gelten als terrorverdächtig und werden konfisziert. Etwa 50 Meter hinter der Kontrolle hingegen bekommen wir im Duty-Free-Shop alles, was wir für eine Flugzeugentführung brauchen. Für einen simplen Personalausweis müssen wir uns einer erkennungsdienstlichen Behandlung unterziehen, die vor wenigen Jahren nur Straftätern vorbehalten war. Polizeistreifen tragen Waffenarsenale mit sich herum, als befänden sie sich im Kriegseinsatz und nicht der Fußgängerzone von Gelsenkirchen. Öffentliche Plätze und U-Bahnen sind mit Kameras vollgehängt, die framegenau festhalten, wann mir das Smartphone aus der Tasche geklaut und wann in der Schlägerei die Rippen gebrochen wurden. Verhindert haben sie nichts, aber seht her, wie kristallklar die Verbrechen dokumentiert sind!

Das Sicherheitstheater findet auch im Internet statt. Begeistert plappern wir nach, das Netz dürfe kein rechtsfreier Raum sein. Stimmt, ist es auch nicht, denn schon seit Jahrzehnten kassieren wir vierstellige Abmahnforderungen, wenn wir irgendwo ein Bild posten, an dem irgendwer die Rechte hat. Ein unvollständiges Impressum kann ebenso teuer werden. Das Recht im Netz wird mit großer Härte durchgesetzt. Das hindert uns nicht daran, nach einem Ministerium für Wahrheit zu rufen, das uns vor Fake News bewahrt und nach einer Klarnamenspflicht, damit wir die Hater, die sich schon seit Jahren nicht mehr hinter Pseudonymen verbergen, endlich erwischen zu können. Überwachung und Zensur finden wir großartig, so lange davon unsere Feindbilder betroffen sind. Dass ein Filter kein Gut und Böse, kein rechts oder links kennt, sondern unterschiedslos auf alles losgeht, was ihm als verfolgungswürdig eingespeist wird, ignorieren wir - bis es zu spät ist.

Natürlich können wir uns irgendwelche Plugins installieren, Nachrichten verschlüsseln und mit Tor unsere Spuren verwischen, aber wenn gleichzeitig Gesetze beschlossen werden, die den Einbruch in unsere Smartphones und Computer legalisieren, Verschlüsselung verbieten und die Totalüberwachung unserer Kommunikation ermöglichen, ist es nur eine Frage der Zeit, bis kein Browserplugin, kein GnuPG und kein Anonymisierungnetz dieser Welt uns noch Schutz bieten können, weil sie entweder verboten oder ausgehebelt sind. Überwachungsphantasien ziehen sich quer durchs politische Spektrum. Alle Bundesregierungen der letzten Jahrzehnte, egal ob Schwarz-Gelb, Rot-Grün oder Schwarz-Rot, haben den Abbau von Grundrechten und den Aufbau eines Polizeistaats vorangetrieben, und nur das Bundesverfassungsgericht hat die schlimmsten Auswüchse verhindern können. Es gibt keinen Anlass, anzunehmen, das werde sich mit der nächsten Regierung ändern. Es werden sich allenfalls die Ausreden ändern, mit denen dies stattfindet - wenn wir nichts dagegen unternehmen.

Das geht aber nur politisch. Wir müssen in die Parteien und Verbände. Wer im Parlament dem Überwachungsstaat das Wort redet und schwadroniert, notleidende Kleinstbetriebe wie Facebook, Amazon und Google bräuchten Datenreichtums-Almosen, um nicht zu verhungern, muss Gegenwind bekommen. Dazu aber reicht es nicht, bequem vor der Tastatur sitzend zu erwarten, die nützlichen Idioten der [GFF](https://freiheitsrechte.org/en/), dem [CCC](https://www.ccc.de) oder [Digitalcourage](https://digitalcourage.de) bekämen das schon wieder geregelt. Diese Organisationen brauchen Eure Hilfe - finanziell und personell. So lange wir Leute in der Parlamente wählen, die handwerklich stümperhafte und verfassungswidrige Gesetze verabschieden, sich von Lobbyisten ihre Meinung in die Feder diktieren lassen und Netzpolitik für eine Nebenschiene des Fischereirechts halten, werden wir den Kampf um die Macht im Netz verlieren.

Bewegt Euch.
