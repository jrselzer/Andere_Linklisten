---
tags: Materialliste, digitale Selbstverteidigung, Linkliste
---
Materialien zur digitalen Selbstverteidigung
===
* Webseite der Cryptoparty Köln-Bonn https://crypto.koeln
* Mailkontakt: kontakt@crypto.koeln ([PGP](https://pgp.mit.edu/pks/lookup?op=get&search=0xE51CD26133E2CC11) Fingerprint 8CB5 66A7 C55D 3D25 037A  533D E51C D261 33E2 CC11)
* Fediverse: @cryptoparty@bonn.social
## Browser-Plugins
* Adblocker
  * [Werbeblocker im Vergleich: Zwölf Tools gegen störende Banner ](https://www.heise.de/ratgeber/Werbeblocker-im-Vergleich-Zwoelf-Tools-gegen-stoerende-Banner-9626680.html?seite=all) Im Kampf gegen aufdringliche Onlinewerbung haben die Browserhersteller aufgerüstet. Wir zeigen, wie gut Vivaldi, Brave & Co. ihre Nutzer vor Werbemüll schützen. 
  * uBlock Origin
    * [Available Filter Templates](https://letsblock.it/filters) einige hilfreiche Filter
    * [The Ultimate Superuser’s Guide to uBlock Origin](https://www.maketecheasier.com/ultimate-ublock-origin-superusers-guide/)
  * **uBlock Origin lite** wird mit dem Umstieg auf Manifest V3 ab Juni 2024 technisch bedingt die Nachfolge von uBlock Origin antreten
    * [für Chrome](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh?pli=1)
    * [für Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin-lite/)
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
* dnip.ch: [Tracking, nein danke!](https://dnip.ch/2023/12/20/tracking-nein-danke/) Die vergangene Woche war Tracking durch Webseiten ein Dauerthema. Niemand scheint unseren Willen nach Privatsphäre respektieren zu wollen. Da muss doch irgendwie Abhilfe möglich sein? Wir zeigen, wie.
    
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
* [Mullvad](https://mullvad.net/en/browser)

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
* Firefox-Relay bietet die Möglichkeit der Einrichtung von Wegwerf-Mailadressen
* [anonbox](https://unbox.at/) Mit der kostenlosen Open Source Lösung unbox.at schützt du deinen Posteingang mit E-Mail-Aliasnamen. Antworte anonym auf weitergeleitete E-Mails. Der Absender erhält die E-Mail so, als käme sie von deinem Alias. Oder starte eine Konversation direkt von deinem Alias aus.

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

## Datenschutzeinstellungen verbessern
* [Datenschutz: utiq-Tracking in drei Schritten deaktivieren/verhindern](https://www.kuketz-blog.de/datenschutz-utiq-tracking-in-drei-schritten-deaktivieren-verhindern/) Das neue Tracking-Verfahren nutzt das Wissen der Telekommunikationskonzerne darüber, wem welcher Internetanschluss gehört, um Websites und Online-Werbung zu personalisieren. Die Methode wird von den Machern bewusst als europäische und datenschutzfreundliche Alternative in der AdTech-Branche positioniert. „Utiq ist der authentische Einwilligungs-Service, der verantwortungsvolles digitales Marketing ermöglicht.“
* Mike Kuketz [Für Anfänger/Bequeme: Werbung und Tracker unter iOS/Android systemweit verbannen](https://www.kuketz-blog.de/fuer-anfaenger-bequeme-werbung-und-tracker-unter-ios-android-systemweit-verbannen/) Die meisten Apps aus den Stores von Google und Apple beinhalten Software-Bausteine von Drittanbietern, die dem Nutzer Werbung einblenden oder seine Aktivität auf Schritt und Tritt verfolgen. Als Nutzer hat man allerdings keinen Einblick in die App bzw. sieht ihr von »außen« nicht an, wie sehr die Werbe- und Trackingbausteine die Sicherheit und den Datenschutz gefährden. Nachfolgend möchte ich eine einfache Lösung für Android- und iOS-Nutzer vorstellen, um sich vor dieser (größtenteils rechtswidrigen) Datensammlung zu schützen. Zunächst wird kurz erläutert, wie der Schutz vor Werbung und Trackern technisch funktioniert. Anschließend wird für beide Plattformen eine bebilderte Anleitung bereitgestellt, um die Schutzmaßnahme umzusetzen. Nach erfolgter Umsetzung werden Werbung, Tracker und Co. sowohl beim Surfen im Internet (via Browser) als auch in allen Apps gefiltert/blockiert.
* [Smartphone, don't spy!](https://smartphone-dont-spy.de/en) This checklist is designed to help you check your smartphone security in a fun way with specific tips. Points and levels in different categories should encourage you to tick off as many things as possible.

### Windows
Es gibt mehrere Gratis-Programme, die versprechen, in Windows datenschutzrelevante Einstellungen zu verbessern. Die Erwartungen an die Leistungsfähigkeit dieser Programme sollten nicht zu hoch angesetzt werden, meint ein [Test in der c't](https://www.heise.de/select/ct/2017/1/1483282098626844) hinter einer Bezahlschranke. Getestet wurde
* [O & O Shutup](https://www.oo-software.com/de/shutup10)
* [Donotspy](https://pxc-coding.com/donotspy11/)
* [W10privacy](https://www.w10privacy.de/)
* [Windows 10 Privaxy.exe](https://wiki.piratenpartei.de/WIN)
 
 ### Android
 
 ### iOS

## Passwortverwaltung
* [Keepass](https://keepass.info/)
    * [Keepass-Diff](https://github.com/Narigo/keepass-diff) A CLI-tool to diff Keepass (.kdbx) files. Useful, if syncing with Dropbox or NextCloud and getting multiple files due to conflicts. 
    * [KeepassXC](https://keepassxc.org/) ist eine optisch etwas modernere Version, das auch über Browserplugins eingebunden werden kann
      * Falls bei der Installation die Meldung “MSVCP140.dll fehlt” oder “VCRUNTIME140.dll fehlt” auftaucht:
        [Lösung: MSVCP140.dll oder VCRUNTIME140.dll fehlt](https://www.giga.de/downloads/windows-10/tipps/msvcp140.dll-fehlt-so-behebt-ihr-den-fehler-auch-vcruntime140.dll/) aufrufen und https://aka.ms/vs/16/release/vc_redist.x64.exe (für 64-Bit-Windows) wählen
      * Unter Ubuntu tauchten Fehler bei Autotype auf. Auf einem Testsystem half die Installation von ```ydotool``` mittels ```sudo apt install ydotool```.
    * [Passwörter systemübergreifend verwalten und synchronisieren mit Keepass](https://www.heise.de/ratgeber/Passwoerter-systemuebergreifend-verwalten-und-synchronisieren-mit-Keepass-5064157.html)
    * [Passwortverwaltung mit KeePass(XC|DX) – Digitaler Schutzschild Teil3](https://www.kuketz-blog.de/passwortverwaltung-mit-keepassxcdx-digitaler-schutzschild-teil3/)
    * [KeePassXC: Auto-Type und Browser-Add-on im Alltag nutzen – Passwörter Teil1](https://www.kuketz-blog.de/keepassxc-auto-type-und-browser-add-on-im-alltag-nutzen-passwoerter-teil1/)
    * [KeePassDX: Magikeyboard und AutoFill im Android-Alltag nutzen – Passwörter Teil2](https://www.kuketz-blog.de/keepassdx-magikeyboard-und-autofill-im-android-alltag-nutzen-passwoerter-teil2/)
    * [Syncthing: KeePass-Datenbank zwischen PC und Android synchronisieren – Passwörter Teil3](https://www.kuketz-blog.de/syncthing-keepass-datenbank-zwischen-pc-und-android-synchronisieren-passwoerter-teil3/)
    * [Bitwarden](https://bitwarden.com/) verwaltet Passwörter zentral auf einem Server und gleicht die lokalen Kopien damit ab. Bei Bedarf kann auch ein eigener Server zum Speichern der Passwortdatenbank genommen werden. Zur bequemen Anbindung gibt es eine ganze Reihe Browser-Plugins. Bitwarden beherrscht inzwischen auch Passkeys.
        * Unter Ubuntu ließ sich das Appimage nicht starten und stürzte mit einem Coredump ab. Abhilfe schaffte die Installation zweier Pakete mittels ```sudo apt install qt6-wayland``` sowie ```sudo apt install xcb```.
    * [Passwortmanager-Apps im Privacy-Check](https://www.heise.de/ratgeber/Passwortmanager-Apps-im-Privacy-Check-5050304.html)
    * t3n: [Sicher im Netz: Diese 7 Passwortmanager musst du kennen ](https://t3n.de/news/passwortmanager-sicherheit-1634480/) Eine alte Information-Security-Weisheit lautet: Ein Passwortmanager ist besser als kein Passwortmanager. Wir stellen sieben beliebte Optionen vor. 
* Passkeys
  * [Passkeys: Wie ein Account ohne Passwort funktioniert](https://www.heise.de/hintergrund/Bestandsaufnahme-Passwort-Nachfolger-Passkeys-9048722.html) Passwörter adieu! Mit dem Nachfolger Passkeys können Sie sich passwortlos aber dennoch sicher und komfortabel einloggen – seit Kurzem auch bei Google-Diensten.
  * [Funktionsweise von Passkeys im Detail erklärt](https://www.heise.de/ratgeber/Funktionsweise-von-Passkeys-im-Detail-erklaert-9659204.html?seite=all) Passkeys sind in allen Belangen sicherer als Passwörter. Warum das so ist, schlüsseln wir in diesem Deep Dive in die Funktionsweise von Passkeys auf.
  * [Passkeys: Die passende Schlüsselverwaltung auswählen](https://www.heise.de/ratgeber/Passkeys-Die-passende-Schluesselverwaltung-auswaehlen-9660336.html?seite=all) Wer seine Internetkonten per Passkey absichern möchte, muss eine Variante der Schlüsselverwaltung bemühen. Wir zeigen, welche für Sie die richtige ist.
  * [FAQ: Fragen und Antworten zu Passkeys](https://www.heise.de/ratgeber/FAQ-Fragen-und-Antworten-zu-Passkeys-9756135.html) Der Passwort-Nachfolger Passkeys soll das Einloggen im Netz so einfach machen, wie nie – wir beantworten die häufigsten Leserfragen zum Thema.
  * [Passkey Revolution: Google Syncs Passkeys to Apple & Windows Devices](https://www.corbado.com/blog/google-passkeys-sync-windows-macos) Google Password Manager now syncs passkeys across Chrome on Windows, macOS and Android, which is ground-breaking as Google solves cross-platform passkey issues.
*  Bin ich von einem Datenleck betroffen?
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
* [Das Authentifzierungsspiel](https://auth-game.fly.dev/) In diesem Spiel wollen wir euch zeigen, wie einfach es ist, einen Passwortmanager zu benutzen und auch, vor welchen Bedrohungen euch dieser schützen kann. Hierfür benötigt ihr am besten ein fertig eingerichteten Passwortmanager oder ein Notizbuch. Beides kann genutzt werden, um eure Passwörter an einem wiederfindbaren Ort zu sammeln.
* [Studie: So viel Zeit ist 2025 zum Knacken eines Passworts nötig](https://www.heise.de/news/Studie-So-viel-Zeit-ist-2025-zum-Knacken-eines-Passworts-noetig-10373334.html) Neue Analysen legen nahe, dass aufgrund des KI-Booms leistungsfähigere Hardware verfügbar ist, die auch das Knacken von Passwörtern deutlich beschleunigt.
* [Are Your Passwords in the Green?](https://www.hivesystems.com/blog/are-your-passwords-in-the-green?utm_source=tabletext) Since 2020, we’ve been on a mission to crack the code - literally - on passwords. Our Hive Systems Password Table shows just how fast a hacker can brute-force your password… but what you see in the table is just the tip of the iceberg. Curious how we actually build it? You’re in the right place. It’s way more than just pretty colors (although yes, there’s a version that’s completely purple - and yes, it’s glorious). Let’s dive into the data, the assumptions, and all the behind-the-scenes work that makes this table more than meets the eye (cue Transformers theme song).
 
## Alternative Messenger
* [On the privacy of push notifications](https://blog.phnx.im/privacy-of-push-notifications/) In December 2023, Reuters, TechCrunch, 404 Media, and others reported on the surveillance of Apple and Google users through push notifications. We were involved in the original investigation by netzpolitik.org. These findings have been confused in various places with an older privacy issue. In this blog post, we want to examine the problem and address potential misconceptions.
* [The Medium is the Message: How Secure Mesaging Apps Leak Sensitive Data to Push Notification Services](https://petsymposium.org/popets/2024/popets-2024-0151.pdf) Like most modern software, secure messaging apps rely on thirdparty components to implement important app functionality. Although this practice reduces engineering costs, it also introduces the risk of inadvertent privacy breaches due to misconfiguration errors or incomplete documentation. Our research investigated secure messaging apps’ usage of Google’s Firebase Cloud Messaging (FCM) service to send push notifications to Android devices. We analyzed 21 popular secure messaging apps from the Google Play Store to determine what personal information these apps leak in the payload of push notifications sent via FCM. Of these apps, 11 leaked metadata, including user identifiers (10 apps), sender or recipient names (7 apps), and phone numbers (2 apps), while 4 apps leaked the actual message content. Furthermore, none of the data we observed being leaked to FCM was specifically disclosed in those apps’ privacy disclosures. We also found several apps employing strategies to mitigate this privacy leakage to FCM, with varying levels of success. Of the strategies we identified, none appeared to
be common, shared, or well-supported. We argue that this is fundamentally an economics problem: incentives need to be correctly aligned to motivate platforms and SDK providers to make their systems secure and private by default.
* Netzpolitik.org: [Push-Dienste: Behörden fragen Apple und Google nach Nutzern von Messenger-Apps](https://netzpolitik.org/2023/push-dienste-behoerden-fragen-apple-und-google-nach-nutzern-von-messenger-apps/) Smartphone-Apps verschicken Benachrichtigungen über Apple und Google, auch vermeintlich sichere Messenger. Damit können Behörden Nutzer-Daten bei Smartphone-Firmen abfragen. Bis jetzt verweigern alle Beteiligten Auskunft darüber. Nach unserer Initiative fordert jetzt ein US-Abgeordneter Transparenz.
* [iPhone und Android: Push-Nachrichten als Datenschatz für staatliche Überwachung](https://www.heise.de/news/iPhone-und-Android-Push-Nachrichten-als-Datenschatz-fuer-staatliche-Ueberwachung-9566588.html) Push-Nachrichten für iPhones und Android-Geräte laufen über Apples und Googles Server. An diesem Datenschatz sind auch staatliche Akteure interessiert.
* Mike Kuketz: [Android: Abhilfe gegen staatliche Überwachung durch Push-Nachrichten](https://www.kuketz-blog.de/android-abhilfe-gegen-staatliche-ueberwachung-durch-push-nachrichten/) Gestern kam eine brisante Enthüllung ans Licht, die die US-Regierung lieber geheim gehalten hätte. Was bekannt wurde, ist weder überraschend noch unerwartet. Die Frage ist nun, wie man sich davor schützen kann.
* Reuters: [Governments spying on Apple, Google users through push notifications - US senator](https://www.reuters.com/technology/cybersecurity/governments-spying-apple-google-users-through-push-notifications-us-senator-2023-12-06/) WASHINGTON, Dec 6 (Reuters) - Unidentified governments are surveilling smartphone users via their apps' push notifications, a U.S. senator warned on Wednesday. In a letter to the Department of Justice, opens new tab, Senator Ron Wyden said foreign officials were demanding the data from Alphabet's (GOOGL.O), opens new tab Google and Apple (AAPL.O), opens new tab. Although details were sparse, the letter lays out yet another path by which governments can track smartphones.
### Signal
* [Signal](https://signal.org/)
* [veröffentlichter Server-Quellcode](https://github.com/signalapp/Signal-Server)
* [Signal-cli](https://github.com/AsamK/signal-cli/releases/tag/v0.8.4.1) Signal auf Kommandozeile
* [Signal FOSS](https://www.twinhelix.com/apps/signal-foss/) Signal ohne Google-Bibliotheken
* Spektrum.de [Mythos Signal: Licht und Schatten beim nicht kommerziellen Messenger](https://www.spektrum.de/news/mythos-signal-licht-und-schatten-beim-nicht-kommerziellen-messenger/2190072) Lange galt Signal als Wunderwaffe gegen Überwachung. Teile der Tech-Community und der digitalen Zivilgesellschaft kritisieren die App jedoch wegen überraschender Datenflüsse, organisatorischer Intransparenz und undemokratischer Machtverhältnisse.
* [Why not Signal](https://dessalines.github.io/essays/why_not_signal.html) Während dieser Text sehr ausführlich die Nachteile Signals beschreibt, geht er leider händewedelnd über die Nachteile der aufgeführten Alternativen hinweg, beispielsweise den Umstand, dass die bei Matrix anfallenden Metadaten nicht gelöscht werden können oder dass Briar nicht nur kräftig die Akkulaufzeit verringert, sondern auch ständig online sein muss, um eventuell eintreffende Nachrichten zu empfangen, die anderfalls stillschweigend verloren gehen. Die lobenswerte Sorgfalt, die bei der Aufzählung der Signal-Mängel angewandt wurde, hätte der Analyse der Alternativen gut getan.
* [Signal: Unsere Push-Benachrichtigungen zeigen Spionen nichts](https://www.heise.de/news/Signal-Unsere-Push-Benachrichtigungen-sind-sicher-vor-Spionage-9573116.html) Geheimdienste sammeln Daten aus Push-Benachrichtigungen von Android und iPhone. Beim Signal-Messenger ist da wenig zu holen, sagt die Stiftung.​
* [mollyim-android-unifiedpush](https://github.com/mollyim/mollyim-android-unifiedpush) Molly is a hardened version of Signal for Android, the fast simple yet secure messaging app by Signal Foundation. Back in 2018, Signal allowed the user to set a passphrase to secure the local message database. But this option was removed with the introduction of file-based encryption on Android. Molly brings it back again with additional security features. Molly connects to the Signal server, so you can chat with your Signal contacts seamlessly. Please remember to review the Signal Terms & Privacy Policy before signing up. We update Molly every two weeks to include the latest features and bug fixes from Signal. The exceptions are security issues, which are patched as soon as fixes become available.
* [How to: Use Signal](https://ssd.eff.org/module/how-to-use-signal) Signal is a free and open-source application for Android, iOS, and desktop that employs end-to-end encryption  to keep communications safe. Signal has certified to courts that it only maintains two types of user data  available to law enforcement: timestamps of when each account was created and the date that each account last connected to the Signal service.

### Threema
* [Threema](https://threema.ch/)

### Wire
* [Wire](https://wire.com/)

### Element
* [Element](https://element.io/) ([Matrix](https://matrix.org/docs/projects/client/element))
    * [Fluffy](https://fluffychat.im/) [Google Playstore](https://play.google.com/store/apps/details?id=chat.fluffy.fluffychat)
    * [Ein Fehler in der Matrix](https://www.cr-online.de/blog/2022/06/02/ein-fehler-in-der-matrix/) 
Mit Matrix gibt es ein Open-Source-Projekt, das es gestattet, einen Ende-zu-Ende-verschlüsselten Messengerdienst mit dem üblichen Funktionsumfang auf eigenem Metall zu betreiben. Unter Kontrollgesichtspunkten ist das erstmal super. Die öffentliche Verwaltung in Frankreich setzt deshalb künftig komplett auf dieses Konzept.1 Alles gut? Leider nicht ganz.
### Omemo
* OMEMO (XMPP)
    * [Dino](https://dino.im/)
    * [Gajim](https://gajim.org)
    * [Conversations](https://conversations.im/)
### Briar
* [Briar](https://briarproject.org/) versendet Nachrichten über das Tor-Netz und kann im Extremfall komplett ohne Internet Daten via Bluetooth übertragen
### Delta Chat
* [Delta Chat](https://delta.chat/) (SMTP)
### Ricochet
* [Ricochet Refresh](https://www.ricochetrefresh.net/) Ricochet Refresh is a peer-to-peer messenger app that uses Tor to connect clients. When you start Ricochet Refresh it creates a Tor hidden service on your computer. The address of this hidden service is your anonymous identity on the Tor network and how others will be able to communicate with you. Ricochet Refresh uses the original Ricochet open-source software but has improved on it substantially, such as upgrading its security and making it compatible with Tor Onion Services v3 instead of the older v2.
### Messenger-Vergleiche
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
    * [Sechs sichere Messenger im Vergleich](https://www.heise.de/ratgeber/Sechs-sichere-Messenger-im-Vergleich-10297137.html) Schlicht oder verspielt, aber jedenfalls sicher? Wir vergleichen sechs Ende-zu-Ende-verschlüsselte Messenger mit unterschiedlichen Prioritäten und Konzepten. 
* [Datenschutzfreundliche und sichere WhatsApp-Alternativen](https://www.kuketz-blog.de/datenschutzfreundliche-und-sichere-whatsapp-alternativen/)
* [Messenger-Apps auf dem Smartphone – Digitaler Schutzschild Teil6](https://www.kuketz-blog.de/messenger-apps-auf-dem-smartphone-digitaler-schutzschild-teil6/)
* [Internes Dokument verrät, welche Daten das FBI von welchem Messenger erhält](https://www.derstandard.at/story/2000131585109/internes-dokument-verraet-welche-daten-das-fbi-von-welchem-messenger)
* [FBI über Messenger: An welche Daten von WhatsApp & Co. US-Strafverfolger kommen ](https://www.heise.de/news/FBI-ueber-Messenger-An-welche-Daten-von-WhatsApp-Co-US-Strafverfolger-kommen-6282456.html)
* [Goldbug](http://goldbug.sourceforge.net/)
* heise+: [Messenger-IDs: Warum Messenger nach Ihrer Telefonnummer fragen](https://www.heise.de/hintergrund/Messenger-IDs-Warum-Messenger-nach-Ihrer-Telefonnummer-fragen-5066901.html?seite=all)
  
### SimpleX
* [SimpleX Chat](https://github.com/simplex-chat) Der Messenger wirbt mit Dezentralität sowie Vermeidung von Metadaten. Allerdings befindet sich das Projekt noch in einem sehr frühen Entwicklungsstadium und eignet sich nur für Technikaffine. Wer uns testweise kontaktieren möchte, kann dies unter [dieser Adresse:](https://simplex.chat/contact/#/?v=1&smp=smp%3A%2F%2F6iIcWT_dF2zN_w5xzZEY7HI2Prbh3ldP07YTyDexPjE%3D%40smp10.simplex.im%2Fif9WJLaxuFXDC61EK6jzdw2vS8ufy_VK%23MCowBQYDK2VuAyEAGPjf6hkFpUronsxUOAlkJ-qjUy3muP58CmhjGwqhT1o%3D))
* [Link Previews: How a Simple Feature Can Have Privacy and Security Risks](https://www.mysk.blog/2020/10/25/link-previews/)
### Session
* [Don't use Session (Signal fork)](https://soatok.blog/2025/01/14/dont-use-session-signal-fork/) The main reason I said to avoid [Session](https://getsession.org/), all those months ago, was simply due to their [decision to remove forward secrecy](https://web.archive.org/web/20241225131654/https://getsession.org/session-protocol-explained) (which is an important security property of cryptographic protocols they inherited for free when they forked libsignal). Lack of forward secrecy puts you in the scope of [Key Compromise Impersonation (KCI) attacks](https://www.cryptologie.net/article/372/key-compromise-impersonation-attacks-kci/), which serious end-to-end encryption apps should prevent if they want to sit at the adults table. This is why I [don’t recommend Tox](https://github.com/TokTok/c-toxcore/issues/426).
### Tox
* [Tox Handshake Vulnerable to KCI](https://github.com/TokTok/c-toxcore/issues/426) [(Link to Tox messsenger)](https://tox.chat/)I found this source code confusingly written (and downright scary at times) and the specification woefully underspecified and inexplicit, so it's entirely possible my understanding of the handshake is inaccurate. But on the off-chance that 5 minutes of source code review at 4am yielded something accurate, here is my understanding of the handshake.
### Berty
* [Berty](https://berty.tech/) kommuniziert über ein P2P-Netz. Leider gelingt es nicht zuverlässig, sich miteinander zu verknüpfen. Das gegenseitige Scannen von QR-Codes scheint noch halbwegs zu funktionieren, aber der Einladungslink führt zu einer Fehlermeldung. Auch der Nachrichtenaustausch schlägt häufig fehl. In unseren Tests gingen drei Viertel der Testnachrichten verloren.
### Zulip
* [Zulip](https://zulip.com/) Organized chat for distributed teams
### Telegram
* heise: [Faktencheck: Telegram ist weniger privat als andere Messenger](https://www.heise.de/hintergrund/Faktencheck-Telegram-ist-weniger-privat-als-andere-Messenger-9860521.html) Die Annahme, Telegram sei besonders sicher, scheint sich hartnäckig zu halten. Fakt ist: In puncto Verschlüsselung ist Telegram der Konkurrenz unterlegen.​
### Volla
* [Messenger-Alternative: Volla Messages mit großen Versprechungen ](https://www.heise.de/news/Messenger-Alternative-Volla-Messages-mit-grossen-Versprechungen-10352561.html) Die angebliche "WhatsApp- und Telegram-Alternative" Volla Messages wird mit Lob überhäuft, kann aber noch(?) kaum echte Vorteile ins Feld führen.
  
### Allgemein
* [Messenger- und Video-Dienste: Bundeskartellamt zu Datenschutz, Transparenz und Interoperabilität](https://www.bundeskartellamt.de/SharedDocs/Meldung/DE/Pressemitteilungen/2023/17_05_2023_SU_MD.html) [PDF](https://www.bundeskartellamt.de/SharedDocs/Publikation/DE/Sektoruntersuchungen/Sektoruntersuchung_MessengerVideoDienste.pdf?__blob=publicationFile&v=4)
  * heise: [Bundeskartellamt: Messenger-Dienste verletzen Verbraucherrechte ](https://www.heise.de/news/Bundeskartellamt-Messenger-Dienste-verletzen-Verbraucherrechte-9058967.html) Die deutschen Kartellwächter haben eine umfangreiche Untersuchung zu Video- und Messengerdiensten vorgelegt. Fazit: Datenschutz ist vielen zu unwichtig. "Ebenfalls verbraucherrechtlich heikel sei, dass Dienste beim Synchronisieren von Kontakten auch jene Personen erfassen, die bisher nicht bei dem jeweiligen Dienst registriert sind. Das könnten Verstöße gegen die DSGVO sein, wenn die Daten dauerhaft gespeichert würden. Dies gelte auch dann, wenn die Telefonnummern verschlüsselt dargestellt werden. Einige Dienste könnten die Verbraucher besser darüber informieren, wie die Sicherheit der Kommunikation gewährleistet wird, zum Beispiel mit Ende-zu-Ende-Verschlüsselung, meint das Bundeskartellamt."
* Der Hamburgische Beauftragte für Datenschutz und Informationsfreiheit [Messenger-Dienste in der Kinder- und Jugendarbeit](https://datenschutz-hamburg.de/fileadmin/user_upload/HmbBfDI/Datenschutz/Informationen/240724_HmbBfDI_Messenger_Dienste_Kinder_und_Jugendlicharbeit.pdf) Messenger-Dienste können eine Chance sein, in der Kinder-, Jugend- und Familienhilfe die jeweiligen Zielgruppen zu erreichen und jungen Menschen die Teilhabe zu vielfältigen, kostenlosen und nichtkommerziellen Kinder- und Jugendangeboten zu ermöglichen. Der Auftrag, sowohl zur Teilhabe zu befähigen als auch vor Risiken zu schützen, leitet sich aus der UN-Kinderrechtskonvention und aus dem Sozialgesetzbuch VIII ab.

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
* [Pimeyes](https://pimeyes.com/) - Face Search Engine Reverse Image Search. Ob diese Suchmaschine datenschutzfreundlicher als die Konkurrenz sind, wird an dieser Stelle nicht bewertet. Es geht hier nur um die Möglichkeit der Rückwärtssuche nach Gesichtern.
* Einschätzungen von [digitalcourage](https://digitalcourage.de/digitale-selbstverteidigung/es-geht-auch-ohne-google-alternative-suchmaschinen)
* [A look at search engines with their own indexes](https://seirdy.one/posts/2021/03/10/search-engines-with-own-indexes/)

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
  * heise [Warum das Darknet nicht nur für Kriminelle ist ](https://www.heise.de/news/Warum-das-Darknet-nicht-nur-fuer-Kriminelle-ist-7237406.html) Das Darknet hat einen miserablen Ruf, zu Unrecht. Schließlich kann man im Darknet auch viele sinnvolle Dinge anstellen. c't 3003 gibt Tipps.
        1. Install-Datei überprüfen
        1. Vorsicht mit eigenen Daten
        1. Vertraue niemandem
        1. Sicherheitsstufe einstellen
        1. Tails benutzen
* [Is Tor Trustworthy and Safe?](https://cyberinsider.com/tor/) There is a lot of misinformation being promoted in various privacy circles about Tor. This article will examine some facts about Tor and assess whether it is the infallible privacy tool it’s made out to be by some.
* [VPN + Tor: Not Necessarily a Net Gain](https://archive.fo/IzoMI) So many people share the advice to use a VPN in conjunction with Tor, usually by way of placing the VPN between the user and her guard node (connecting to Tor through a VPN). More rarely, the advice is given to place the VPN between her exit and her destination (connecting to a VPN through Tor). On the surface, these ideas sound good, or at least not bad. The first one especially sounds like it must help. More encryption is always better, right? This post will discuss my reasoning for why using a VPN with Tor is not the obvious security gain that people make it out to be. Users may not lose any safety by adding a VPN, but they probably aren't gaining any. [original source](https://matt.traudt.xyz/p/mRikAa4h.html)
#### Entanonymisierung im Tor-Netz
* Simplified Privacy: [How you can be deanonymized through Tor](https://simplifiedprivacy.com/how-you-can-be-deanonymized-through-tor/) Tor is an excellent tool for privacy, and we do not recommend you avoid it.  However, there are many limitations to be aware of and ways of using it that can compromise your anonymity on Tor.  This article will discuss just a few of the ways, but there may be others that the public is unaware of.  For example in 2017, the FBI dropped a case against a school worker accused of downloading child pornography because the FBI would have rather let him go than reveal the source code for how they deanonymitized him through Tor.  [1] If you really want to get your privacy game to the next level, consider subscribing for free to our new content by email, by Session messenger, RSS feed, or Nostr.
   1. JavaScript based attacks
   1. Cookies
   1. Compromised Exit Nodes
   1. Compromised Middle Relays
   1. Compromised Entrance Guards
   1. Opening Files Outside Tor
   1. Ultrasonic Sounds
 * [Operation Liberty Lane (LE Running Gaurd and middle nodes to deanonymize HS users) ](https://www.reddit.com/r/TOR/comments/19benkx/operation_liberty_lane_le_running_gaurd_and/) Operation Liberty Lane (FBI/DHS joint operation) is a multi-national law enforcement operation that involves the United States, Brazil, Germany, and the United Kingdom, and targets users of illegal hidden services. It appears this once theoretical attack has been operationalized and has unmasked thousands of users. The NCA and FBI have jointly developed a software program called "Good Listener" that involves LE spinning up as many guard and middle nodes as possible, and then using a timing attack to correlate the IP at the malicious gaurd to the timing at the illegal HS. It appears that this is only possible once the HS has been identified and the traffic to it can be interecepted and fed into the program.There was a few posts previously about cases where users using TAILS and WHONIX were caught so a NIT was ruled out, we now have our answer. This next part is only a guess, but it's likely KAX17 was run by the German government in support of this operation.
 * heise: [Boystown-Ermittlungen: Mit der Stoppuhr auf Täterfang im Darknet](https://www.heise.de/news/Boystown-Ermittlungen-Mit-der-Stoppuhr-auf-Taeterfang-im-Darknet-9885038.html) Die Ermittlungsakte zum Boystown-Prozess enthält Hinweise auf eine Timing-Analyse, mit der Tor-Nutzer deanonymisiert werden können. Abhilfe ist nicht in Sicht.
 * DLF Kultur: [Tor-Netzwerk- Auch das Darknet kann überwacht werden](https://www.deutschlandfunkkultur.de/tor-netzwerk-auch-das-darknet-kann-ueberwacht-werden-dlf-kultur-231662a1-100.html) 
 * Lage der Nation: [Folge 398](https://lagedernation.org/podcast/ldn398-grenzkontrollen-in-frankfurt-oder-merz-wird-cdu-kanzlerkandidat-explodierende-pager-und-funkgeraete-im-libanon-darknet-geknackt-kollaps-der-carolabruecke-ampel-plant-riester-reform-feedba/) ab Minute 43:11
 * c't: [Das Darknet gestoppt](https://www.heise.de/select/ct/2024/22/2426321434318736715) Deanonymisierung von Tor-Nutzern mittels Timing-Analyse. Das Tor-Netz bietet seinen Nutzern Anonymität, die Journalisten und Dissidenten vor Repressalien schützt, aber auch Kriminelle vor der Polizei. Der Prozess um die Pädo-Plattform „Boystown“ offenbarte Hinweise, wie der Betreiber per Timing-Analyse trotzdem identifiziert wurde.
 * c't: [Unhidden Services - Deanonymisierung von Tor Hidden Services verhindern](https://www.heise.de/select/ct/2017/22/1508778711558534) Das Tor-Netz verspricht Nutzern und Hidden-Service-Anbietern ein hohes Maß an Anonymisierung: Indem Daten mehrfach verschlüsselt werden und Umwege über mindestens drei Tor-Knoten nehmen, soll niemand die Quelle identifizieren können. Ohne besondere Vorsichtsmaßnahmen riskieren Hidden-Service-Betreiber jedoch, trotzdem enttarnt zu werden.
 * [The Vanguards Onion Service Addon](https://github.com/mikeperry-tor/vanguards) Even after deployment of the new v3 onion service protocol, the attacks facing onion services are wide-ranging, and still require more extensive modifications to fix in Tor-core itself. Because of this, we have decided to rapid-prototype these defenses in a controller addon in order to make them available ahead of their official Tor-core release, for onion services that require high security as soon as possible.
 * NDR: [Investigations in the so-called darknet: Law enforcement agencies undermine Tor anonymisation](https://www.ndr.de/fernsehen/sendungen/panorama/aktuell/Investigations-in-the-so-called-darknet-Law-enforcement-agencies-undermine-Tor-anonymisation,toreng100.html) The Tor network is considered the most important tool for surfing the internet anonymously. Law enforcement agencies have apparently begun to infiltrate it in order to expose criminals. They have been successful in at least one case.
 * NDR: [Anonymisierungsdienst Tor angreifbar: Snowden-Effekt verpufft](https://www.ndr.de/fernsehen/sendungen/panorama/aktuell/Anonymisierungsdienst-Tor-angreifbar-Snowden-Effekt-verpufft,tor192.html) Durch die Snowden-Enthüllungen 2013 wurde der Tor-Browser weltweit populär. Panorama hat recherchiert, dass das dahinterliegende Anonymisierungsnetzwerk in den vergangenen Jahren von Ermittlungsbehörden unterwandert wurde. Wie haben sie das geschafft?
 * ARD [Strafverfolger hebeln Tor-Anonymisierung aus](https://www.tagesschau.de/investigativ/panorama/tor-netzwerk-100.html) Das Tor-Netzwerk gilt als wichtigstes Werkzeug, um sich anonym im Internet zu bewegen. Behörden haben begonnen, es zu unterwandern, um Kriminelle zu enttarnen. In mindestens einem Verfahren waren sie erfolgreich.
 * DW [Q&A: Ist das Tor-Netzwerk noch sicher?](https://www.dw.com/de/qa-ist-das-tor-netzwerk-noch-sicher/a-70320968) Zwei Millionen Menschen weltweit nutzen das Tor-Netzwerk, um anonym zu surfen oder Zensur zu umgehen. Jetzt gibt es Berichte, das System sei geknackt worden. Was ist dran? Die DW liefert Antworten.
 * heise ["Passwort" Folge 18: Löcher in der Zwiebel? Ein Blick auf das Tor-Netzwerk](https://www.heise.de/news/Passwort-Folge-18-Loecher-in-der-Zwiebel-Ein-Blick-auf-das-Tor-Netzwerk-10001997.html) Der Podcast von heise security nutzt sein Erwachsenwerden, um sich ins Darknet zu begeben. Konkret sehen sich die Hosts in dieser Episode das Tor-Netzwerk an. Ein Overlay-Netz, das die anonyme Nutzung von Internetdiensten ermöglicht und damit ein wichtiges Werkzeug für Dissidenten oder Journalisten darstellt – aber auch für Kriminelle aller Couleur und viele andere Betätigungsfelder.
 * [Das Tor-Netzwerk ist jetzt also überwacht?](https://www.youtube.com/watch?v=YOJabNSX4V4)
 *  [Secretary Johnson announces results of operation that dismantled underground child exploitation enterprise on Tor network](https://www.ice.gov/news/releases/secretary-johnson-announces-results-operation-dismantled-underground-child) **Washington** — Department of Homeland Security (DHS) Secretary Jeh Johnson, with U.S. Immigration and Customs Enforcement (ICE), U.S. Postal Inspection Service (USPIS) and the U.S. Attorney for the Eastern District of Louisiana today announced the complete results of one of the largest online child exploitation investigations in the history of ICE, involving victims in 39 states and five countries.
 *  Torproject [Is Tor still safe to use?](https://blog.torproject.org/tor-is-still-safe/) In response to the claims made in Deutsche Welle's (DW) reporting, which suggests that v3 Onion Services were impacted by this attack, we cannot confirm whether the affected service had Vanguard protections enabled. Given the time frame of the attack, it is likely the affected service lacked Vanguard protections, which made Onion Services more vulnerable to relatively easy guard discovery attacks although the exact method remains unclear. We are continuing to investigate this issue and will provide updates as more information becomes available.
   
##### Warum Technik nicht alles ist und die Ermittlungsbehörden nicht untätig sind.
* https://www.rundschau-online.de/region/rhein-berg/burscheid/burscheid-angeklagter-verteilt-bilder-von-gewalt-an-kindern-im-internet-701640
* https://www.rundschau-online.de/region/rhein-berg/burscheid/kinderporno-prozess-geld-verdient-hat-der-burscheider-damit-wohl-nicht-714746
* https://www.ksta.de/region/leverkusen/burscheid/kinderporno-prozess-geld-verdient-hat-der-burscheider-damit-wohl-nicht-714746
* https://www.ksta.de/region/leverkusen/burscheid/burscheid-kinderporno-bilderspeicher-waren-unter-den-top-five-im-internet-705324
* https://www.ksta.de/region/leverkusen/burscheid/prozess-so-sorgfaeltig-soll-der-burscheider-sein-kinderporno-netz-aufgezogen-haben-704567
* https://www.ksta.de/region/leverkusen/stadt-leverkusen/kinderpornografie-landgericht-koeln-verurteilt-burscheider-zu-acht-jahren-haft-729358
 
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
* c't 3003: [Tails: Dieses sichere Betriebssystem solltet ihr kennen](https://www.youtube.com/watch?v=GCqB2YntLwU) Wir zeigen euch, wie ihr in 5 Minuten Tails OS auf einem USB-Stick installiert und dann super anonym unterwegs seid. 

## Whonix
* [Whonix](https://www.whonix.org/)

## Qubes
* [Qubes](https://www.qubes-os.org/)

## Backups
* [Duplicati](https://www.duplicati.com/) (Artikel in der [c't](https://www.heise.de/select/ct/2019/24/1573928793884407))
* [restic](https://restic.net/) kommandozeilenbasiert, erfordert Einarbeitung
* [Bacula](https://www.bacula.org/)
* [bareos](https://www.bareos.com/)
* [Syncthing](https://syncthing.net/) Synchronisiert mehrere Rechner untereinander im Peer-to-Peer-Verfahren ohne zentralen Server. Braucht einen gewissen Einarbeitungsaufwand
 
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
* Alternative Bildschirmtastaturen
  * [FUTO Keyboard](https://gitlab.futo.org/alex/keyboard-wiki/-/wikis/FUTO-Keyboard) FUTO Keyboard is a keyboard being developed, forked from the AOSP keyboard. The goal is to create a good, customizable keyboard that doesn't sacrifice on privacy or freedoms.
  * [HeliBoard](https://f-droid.org/packages/helium314.keyboard/) HeliBoard ist eine datenschutzbewusste quelloffene Tastatur, die auf AOSP / OpenBoard basiert. Verwendet keine Internetberechtigung und ist daher zu 100 % offline.

### iOS
* [Netguard](https://apps.apple.com/de/app/netguard/id446320156)
* [Newpipe](https://newpipe.net/) ist ein alternativer Youtube-Client mit einigen Erweiterungsmöglichkeiten wie Werbeblockern

## Dateiversand
* [Wormhole](https://wormhole.app) Ende-zu-Ende-verschlüsselter Dateiversand
* [Magic-Wormhole](https://magic-wormhole.readthedocs.io/en/latest/welcome.html#) Kommandozeilenbasiertes Werkzeug zur Dateiübertragung. Schnell, verschlüsselt, einfach in der Handhabung und sehr effektiv, was das Umgehen von netzseitigen Beschränkungen angeht.

## Steganografie
* [Stegosuite](https://codeberg.org/tob/stegosuite) Stegosuite is a free steganography tool written in Java. With Stegosuite you can hide information in image files.
  
## Schadsoftwareabwehr
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
* Windows Defender
    * [DefenderUI](https://www.defenderui.com/) Oberfläche zum Einstellen des Windows-Defenders
    * [Reicht der Windows-Defender als Virenschutz?](https://www.heise.de/tipps-tricks/Reicht-der-Windows-Defender-als-Virenschutz-5050100.html)

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
* t3n: [Was tun, wenn’s brennt? So bekommst du dein gehacktes web.de- oder GMX-Konto zurück](https://t3n.de/news/gmx-web-de-sicherheit-gehackt-1610315/) Besitzer:innen von web.de- und GMX-Mail-Konten sehen häufig beim Einloggen Hinweise auf fehlgeschlagene Login-Versuche. Was dahintersteckt und wie man sich davor schützt – und was man nach einer tatsächlichen feindlichen Übernahme des Kontos tun kann.
* [Maltego](https://www.maltego.com/) Werkzeug zur Informationssammlung über eine Person. Ausgehend von bekannten Daten wie beispielsweise dem Namen, der Mailadresse oder Postanschrift sucht das Programm im Netz allgemein und sozialen Netzen im Besonderen nach weiteren Informationen und hilft dabei, sie übersichtich darzustellen.

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
* [All your computers are beschlagnahmt](https://archive.org/details/de_beschlagnahmt-1.1.0/mode/2up) gibt nicht nur für den Fall einer Haudurchsuchung mit Hardwarebeschlagnahme einige Tipps zum Absichern der eigenen Systeme. Der Text ist nicht ganz aktuell und sollte daher nur als Ausgangspunkt weiterer Recherchen dienen.
* [Opsec 101](https://opsec101.org/) In this guide we'll cover the basics of Opsec in a way that most anyone should be able to understand. This guide is split up into topics designed to be linked to directly for the purpose of convenient educational discussion. As this is intended for all audiences, it will be rich in easily destroyable strawmen examples that do not necessarily reflect complex realistic threats and risks. If you do not like the included examples, feel free to contribute your own via pull-request. Note: This guide is not a "how to be anonymous on the internet", "how to protect yourself online", or "best practices" guide. Those are all countermeasure-first approaches that assume a threat model that applies to you (when it often doesn't). Instead, this guide teaches you how to understand that for yourself through the opsec process. While many guides can be useful to learn about potential threats and countermeasures, the countermeasure-first approach of the "best practices" fallacy has no place in opsec and ultimately leads to baseless paranoia.
* SRF: [Cookie-Banner - So teilen die grössten Schweizer Webseiten Ihre heiklen Daten](https://www.srf.ch/news/schweiz/cookie-banner-so-teilen-die-groessten-schweizer-webseiten-ihre-heiklen-daten) Alter, Standort, Vorlieben – wer Online liest wird mitgelesen. SRF zeigt, wie gross das Geschäft mit den Daten ist und welche Webseiten besonders heikle Daten teilen.
* envanto tuts+ [How to Self-Host Google Fonts on Your Own Server](https://webdesign.tutsplus.com/how-to-self-host-google-fonts--cms-34775t) Hosting Google Fonts locally on your own server has many advantages, such as better privacy and security, offline availability, and improved performance. In this tutorial, we show you how to self-host Google Fonts instead of pulling them from Google’s CDN.
* [Security Education Companion](https://www.securityeducationcompanion.org/) SEC is a resource for people teaching digital security to their friends and neighbors. If you’d like to help your community learn about digital security but aren’t sure where to start, these articles, lesson plans, and teaching materials are for you!
* Surveillance Self-Defense (EFF)
  * [Attending a Protest](https://ssd.eff.org/module/attending-protest) Protecting your electronic devices and digital assets  before, during, and after a protest is vital to keeping yourself and your information safe, as well as getting your message out. Theft, damage, confiscation, or forced deletion of media can disrupt your ability to publish your experiences. At the same time, those engaging in protest may be subject to search or arrest, or have their movements and associations surveilled.
  * [How to: Use Signal](https://ssd.eff.org/module/how-to-use-signal) Signal is a free and open-source application for Android, iOS, and desktop that employs end-to-end encryption  to keep communications safe. Signal has certified to courts that it only maintains two types of user data  available to law enforcement: timestamps of when each account was created and the date that each account last connected to the Signal service.
  * [Want a security starter pack?](https://ssd.eff.org/playlist/want-security-starter-pack) Surveillance impacts all of us, no matter where we live or what we do. While some of us might be directly affected, others may simply want to know what measures they can take to protect their communications and data  from spying. This introductory playlist will help you discover how to assess your personal risk , protect your most cherished communications and information, and start thinking about incorporating privacy-enhancing tools into your daily routine.
  * [Databroker Files: Sieben Wege, um deinen Standort vor Databrokern zu schützen](https://netzpolitik.org/2025/databroker-files-sieben-wege-um-deinen-standort-vor-databrokern-zu-schuetzen/) Databroker verkaufen die Handy-Standortdaten von Millionen Menschen weltweit. Zehntausende App sind betroffen, wie Veröffentlichungen von netzpolitik.org und Recherche-Partnern aus sechs Ländern zeigen. Das kannst du tun, um dich zu schützen.
    * Mobile Advertising ID abschalten
    * Apps den Standort-Zugriff entziehen
    * Ortungs-Technologien abschalten
    * Ortung via IP-Adresse eindämmen
    * Tracking ablehnen, wo es nur geht
    * Umsatteln auf Tracking-freie Alternativen
    * Sich für politische Lösungen starkmachen
    
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
Allgemein werden Dienste, welche die automatische Löschung der eigenen Daten bei einer ganzen Reihe von Unternehmen anbieten, kritisch gesehen. Erstens verlangen diese Angebote ihrerseits personenbezogene Daten, was kritisch wird, wenn diese Anbieter die Seiten wechseln, zweitens orientieren sie sich häufig am US-Datenschutzrecht und nicht an der DSGVO, drittens verfahren sie grobschlächtig, indem sie auch Dienste ansprechen, bei denen gar keine Daten gespeichert sind und viertens sind ihre Erfolgsquoten mäßig. Nach derzeitigem Kenntnisstand ist es besser, sich direkt mit den datensammelnden Unternehmen in Verbindung zu setzen, als eine Vermittlungsinstanz dazwischenzuschalten.
* [Facebook komplett löschen - so geht's](https://www.heise.de/tipps-tricks/Facebook-komplett-loeschen-so-geht-s-4061586.html])
* [Wie Sie vergessene Accounts finden und löschen](https://www.t-online.de/digital/internet/id_86098254/wie-sie-vergessene-accounts-finden-und-loeschen.html)
* [Just delete me](https://backgroundchecks.org/justdeleteme/) liefert Kontaktadressen und Anleitungen, wie beim Löschen zu verfahren ist
* [PrivacyBot](https://privacybot.io/) - A free and open source way to delete your data from an exhaustive list of data brokers and people search services.
* [Aboalarm](aboalarm.de)
* [Accountkiller}(https://www.accountkiller.com/de/home-de) bietet Anleitungen zum Kontolöschen

## Werkzeuge
* [Datensparsames Android mit der Android Debug Bridge](https://gnulinux.ch/datensparsames-android-mit-der-android-debug-bridge-teil1-samsung-phablet) Der Artikel beschreibt den Versuch, unter Android durch Umbau mittels der Android Debug Bridge (ADB), ohne Root soweit wie möglich an das Datenschutzniveau besserer Android Custom ROMs heranzukommen. Es ist der erste Teil einer voraussichtlich dreiteiligen Serie. Im ersten Teil wird der Ansatz für ein aktuelles Samsung Android (Stock-ROM) mit Android 14 demonstriert.
* [Test Adblock](https://d3ward.github.io/toolz/adblock.html) prüft, ob die wichtigsten Werbetreibenden und Tracker browserseitig blockiert werden.
* Exodus Privacy: [Welche App enthält wie viele Tracker?](https://reports.exodus-privacy.eu.org/en/reports/)
* [Burp suite](http://portswigger.net/burp/proxy.html) Auftrennen von SSL-Verbindungen, um den Datenverkehr von Apps zu untersuchen
* [mitmproxy](https://mitmproxy.org/)
* [OWASP ZAP](https://www.zaproxy.org/)
* [Cookie Consent Speed Run](https://cookieconsentspeed.run/) Wer schafft es am schnellsten, ein Cookie-Banner so zu beantworten, dass keine Cookies gespeichert werden? Das Spiel wäre lustiger, wenn es nicht aus lauter Tricksereien bestünde, die von realen Webseiten praktiziert werden.
* [clickclickclick](https://clickclickclick.click/)
* [VirusTotal- Analyze suspicious files and URLs to detect types of malware, automatically share them with the security community](https://www.virustotal.com/gui/home/upload)
* [Verschlüsselter Dateiversand mit ablaufenden Links](https://send.vis.ee/)
* [Temporäre Telefonnummer für Verifikations-SMS-Empfang](https://sms24.me/)
* [Tracktor.it](https://www.tracktor.it/) Hilfe beim Erstellen von Beschwerden gegen unzulässiges Tracking
* [Welche meiner Aktivitäten hat Google von mir gespeichert?](https://myactivity.google.com/myactivity)
* [Sherloq](https://github.com/GuidoBartoli/sherloq) Forensische Bildanalyse, unter anderem zum Erkennen von Manipulationen
* [BleachBit](https://www.bleachbit.org/) When your computer is getting full, BleachBit quickly frees disk space. When your information is only your business, BleachBit guards your privacy. With BleachBit you can free cache, delete cookies, clear Internet history, shred temporary files, delete logs, and discard junk you didn't know was there. Designed for Linux and Windows systems, it wipes clean thousands of applications including Firefox, Adobe Flash, Google Chrome, Opera, and more. Beyond simply deleting files, BleachBit includes advanced features such as shredding files to prevent recovery, wiping free disk space to hide traces of files deleted by other applications, and vacuuming Firefox to make it faster. Better than free, BleachBit is open source.
* [Shennina - Automating Host Exploitation with AI](https://github.com/mazen160/shennina) Shennina is an automated host exploitation framework. The mission of the project is to fully automate the scanning, vulnerability scanning/analysis, and exploitation using Artificial Intelligence. Shennina is integrated with Metasploit and Nmap for performing the attacks, as well as being integrated with an in-house Command-and-Control Server for exfiltrating data from compromised machines automatically.
* [Portmaster](https://safing.io/) is a free and open-source application firewall that does the heavy lifting for you. Restore privacy and take back control over all your computer's network activity.
* Netzpolitik.org: [Jetzt testen: Wurde mein Handy-Standort verkauft?](https://netzpolitik.org/2024/databroker-files-jetzt-testen-wurde-mein-handy-standort-verkauft/) Unsere Recherche mit dem BR zeigt: Datenhändler verkaufen die Standortdaten von Millionen Menschen in Deutschland. Uns liegt ein Datensatz mit Kennungen von bis zu 11 Millionen Geräten vor. Mit diesem Databroker-Checker kannst du jetzt testen, ob auch dein Gerät getrackt wurde.
* [Ausweiskopie - My identity card copy](https://github.com/Varbin/ausweiskopie) Easily watermark and hide information in copies of your (german) identity card! Ausweiskopien schwärzen und einfach kenntlich machen.

### Internetzensur
* [OONI Probe](https://ooni.org/install/)
  * [OONI Measurement Aggregation Toolkit (MAT)](https://explorer.ooni.org/chart/mat) Create charts based on aggregate views of real-time OONI data from around the world

### OSINT
* [Empfehlungsecke: OSINT-Tools](https://www.kuketz-blog.de/empfehlungsecke-osint-tools/)
* [Awesome OSINT](https://github.com/jivoi/awesome-osint?tab=readme-ov-file) A curated list of amazingly awesome open source intelligence tools and resources. Open-source intelligence (OSINT) is intelligence collected from publicly available sources. In the intelligence community (IC), the term "open" refers to overt, publicly available sources (as opposed to covert or clandestine sources)
### Videostreams in der Konsole und ohne Werbung ansehen
* [Mein YouTube Terminal Workflow](https://paper.wf/kubikpixel/mein-youtube-terminal-workflow)
* [Mediatheken & TV im Terminal](https://paper.wf/kubikpixel/mediatheken-und-tv-im-terminal)
### Geografischen Ort zu einer IP-Adresse bestimmen
* [IPLocation](https://www.iplocation.net/)
* [KeyCDN](https://tools.keycdn.com/geo)
### Alternative Dienste und Programme
* [Prism Break](https://prism-break.org/en/) 
* [Privacytools](https://www.privacytools.io)
### Raspberry Pi
* [Raspberry Pi als Hacking-Werkzeug für SSL- und Man-in-the-Middle-Angriffe](https://www.heise.de/select/ct/2016/10/1463049049556018)
* [Eblocker](https://eblocker.org/) Die weltweit erste Plug & Play-Lösung für werbefreies, anonymes Surfen und Jugendschutz auf allen Geräten.
* [Pi-hole](https://pi-hole.net/) The Pi-hole® is a DNS sinkhole that protects your devices from unwanted content, without installing any client-side software.
* [Adguard Home](https://adguard.com/en/adguard-home/overview.html) AdGuard Home is a network-wide software for blocking ads & tracking. After you set it up, it’ll cover ALL your home devices, and you don’t need any client-side software for that. With the rise of Internet-Of-Things and connected devices, it becomes more and more important to be able to control your whole network. [How to set up](https://github.com/AdguardTeam/AdGuardHome#getting-started)
### Kali Linux
* [Kali Linux](https://www.kali.org/) is an open-source, Debian-based Linux distribution geared towards various information security tasks, such as Penetration Testing, Security Research, Computer Forensics and Reverse Engineering.
    * [Learn About the Best Features of Kali Linux](https://www.debugpoint.com/kali-linux-features/) Learn what the key best features and tools about Kali Linux and why it is so popular in the information security industry.
    * heise+: [Hacking-Tools: Hacking-Stick mit Kali Linux einrichten](https://www.heise.de/ratgeber/Hacking-Tools-Hacking-Stick-mit-Kali-Linux-einrichten-6223844.html)
    * [Kali Linux Penetration Testing Tutorial: Step-By-Step Process](https://www.esecurityplanet.com/networks/kali-linux-tutorial/)
### Android
* [Reverse Engineering von Android-Apps](https://www.heise.de/select/ct/2021/1/2031818243766930133)
* [Android-Traffic unter der Lupe](https://www.heise.de/select/ct/2017/13/1497715250712891)
* [IT-Sicherheit: Reverse Engineering von Android-Apps](https://www.heise.de/ratgeber/IT-Sicherheit-Reverse-Engineering-von-Android-Apps-4994208.html)
  
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
* Netzpolitik.org: [So geht sichere Kommunikation](https://netzpolitik.org/2024/digitale-selbstverteidigung-so-geht-sichere-kommunikation/) Wie man Informationen so übers Internet weitergibt, dass nur die Zielpersonen sie erfahren. Und wie man sein Telefon gegen Staatstrojanerangriffe abhärten kann.
  * Apple.com: [About Lockdown Mode](https://support.apple.com/en-us/105120) Lockdown Mode helps protect devices against extremely rare and highly sophisticated cyber attacks.

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
* Netzpolitik.org: [Die große Datenhändler-Recherche im Überblick](https://netzpolitik.org/2024/databroker-files-die-grosse-datenhaendler-recherche-im-ueberblick/) Der unkontrollierte Datenhandel der Online-Werbeindustrie ist eine Gefahr für den Datenschutz von Abermillionen Menschen und für die nationale Sicherheit Deutschlands. Das zeigen Recherchen von netzpolitik.org und dem Bayerischen Rundfunk. Die Databroker Files im Überblick.
* Netzpolitik.org: [Firma verschleudert 3,6 Milliarden Standorte von Menschen in Deutschland](https://netzpolitik.org/2024/databroker-files-firma-verschleudert-36-milliarden-standorte-von-menschen-in-deutschland/) Datenhändler verbreiten die Standorte von Menschen in Deutschland – teils sogar kostenlos, wie Recherchen von netzpolitik.org und BR zeigen. Ein Datensatz mit 3,6 Milliarden Einträgen offenbart genaue Bewegungsprofile und eine neue Dimension der Massenüberwachung.
* [ransomware.live](https://www.ransomware.live/) This page lists the latest 100 ransom claims detected by Ransomware.live. We continously scrape ransomware group sites to detect new victims.
Ransomware.live has been tracking ransomware's victims since April 2022.

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
Symptome:
* Auf den ersten Blick habe ich mir die Mail selbst geschickt-
* Es ist immer die gleiche Drohung: Sie haben angeblich Schmuddelseiten oder sogar Seiten pädokriminellen Inhalts besucht. Das Erste ist unangenehm, das Zweite nach [§ 184b StGB](https://www.gesetze-im-internet.de/stgb/__184b.html) sogar haftbewehrt.
* Um die Drohkulisse zu verstärken, wird gern der Name "Pegasus" fallengelassen, ein in der Tat mächtiges Angriffswerkzeug, das aus Presseberichten bekannt ist, aber vor allem von Regierungen und Ermittlungsbehörden eingesetzt wird. Die Spionagesoftware kann geradezu magische Dinge und hat angeblich Ihre komplette Infrastruktur übernommen.
* In fortgeschrittenen Versionen kennt die Angreiferin Ihr Passwort.
* Die Betrügerin baut zeitlichen Druck auf und droht mit der Veröffentlichung des Ihnen unangenehmen Wissens. Die Fristen sind meistens sehr kurz gesetzt und beginnen mit dem Öffnen der Mail, das angeblich registriert wird.
* Gelegentlich ist die Drohbotschaft als Bild oder PDF angehängt, um Spamfilter zu umgehen.
  
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

#### Woher kennt die Betrügerin Ihr Passwort?
Wahrscheinlich wurde eines Ihrer Onlinekonten tatsächlich geknackt und Ihr Passwort so das vieler anderer listenweise auf dem Schwarzmarkt angeboten. Das sollten Sie ernst nehmen und Ihr Passwort ändern. Sehen Sie auf [Have I been pwned](https://haveibeenpwned.com) oder dem [HPI Identity Leak Checker](https://sec.hpi.de/ilc/search?lang=de) nach. Sie sollten dort Treffer haben. Ändern Sie deswegen (falls nicht schon geschehen) die Passworte Ihrer betroffenen Onlinezugänge sowie die der damit verbundenen Konten (beispielsweise, wenn Sie Ihr Mailkonto als Wiederherstellungsadresse für Ihren Social-Media-Zugang hinterlegt haben). Wählen Sie ein gutes Passwort, im Zweifelsfall also keins, das Sie sich selbst ausdenken, sondern sich durch einen Zufallsgenerator erzeugen lassen. Wenn Sie sich das Passwort nicht merken können, erwägen Sie die Benutzung eines Passwortmanagers.

Lassen Sie sich nicht unter Zeitdruck setzen. Die Drohung ist nur in sehr seltenen Fällen wahr. Fragen Sie um Rat, gern auch [uns](mailto:kontakt@crypto.koeln).

Weitere Hinweise gibt es unter [“Hello pervert” sextortion scam includes new threat of Pegasus—and a picture of your home](https://www.malwarebytes.com/blog/news/2024/09/hello-pervert-sextortion-scam-includes-new-threat-of-pegasus-and-a-picture-of-your-home) von Malwarebytes sowie [New Email Scam Includes Pictures of Your House. Don’t Fall For It.](https://www.eff.org/deeplinks/2024/09/new-email-scam-includes-pictures-your-house-dont-fall-it) der EFF.

### Meine Bank hat mir geschrieben, mit meinem Konto sei etwas nicht in Ordnung
Sehen wir uns auch diese Mail genauer an:

```
Content-Transfer-Encoding: quoted-printable
content-type: text/html; charset="utf-8"
X-RT-Original-Encoding: ascii
Content-Length: 3933

<!doctype html>
<html>
<head>
	<title></title>
</head>
<body>
<p><img alt="" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMgAAACJCAMAAABegodlAAAAwFBMVEUKQ4r////gXwwEQYnV2uUAN4X5+vx0ha8AO4bx8/cAI31meKfK0d/gXQD54tneVADibTL00MLyw7I3W5fhZib32cz99fLniWfdSgAAMIIAM4MAKH9WcaMALYHp7PIAF3re4+xMa58AHnymr8m+xthXap+ZqcX77ejcQQAbSo4kUJEkQoouSo2HmLuqts21vNEAAHSXn74ADXhNX5lDY5s+U5J6j7XokHHusZrso4Plf1rxu6Xib0DpmX3lfU/spY30WC5cAAAGcUlEQVR4nO2cfVfaShDGEzYblrdSRFCCIKCivItVe6/tbb//t7qEKCDJZGdkEldOnn96TqGb/SWZnWdml1r2kcj67Alw6ahA3J7zlVXYgBRK0vqyEsXyDogSX1eDdyCffV8PUDEDMUwZiGnKQExTBmKaMhDTlIGYpgzENGUgpikDMU0ZiGnKQExTBmKaKCC0RqQSH5hO8C8jL6SZHAFE1Gka4advCeW1i4NB0VPWaDweR44Xf2MIIMWeWyDIHeLeVKGkmkwvZvOy040bzol/xASQ9sImyZkgMFSnnh+WC4jh5vF7BQQQmaeBuBNtlIj2eNFzccPN2EDEiAZiP+reLTldICkQLz4BRPZoIMNWPIdX6uIH6/EFu6WIQVIexHPk0Y/DH8yLnxwJ5JkGUmjF3USvRBpM93hJICXM6rKV248ZUD2RBnN1k6OAiDoxSGbwXRSS9p66QrMEkryWd00DuYbfa0Vcy3uXmrmRQFpD2tWdEXgbvTJtqHmHE0ReUNYZ2+7eQCOqOo3DvtDNjWbjO7Rot/PQiEXiA3GnOpdAAxk4tOtDvlFYxDui9200EHKQAP7Im9HGsefaqdFA1CNxAtHWWyji8qdzjGQQMaVFO+AbyQkJMTUiyIQYpNHGQtHcSew6/jEQS1GDJNI3esRR7Ou2dmZEEEn0jd3IJ9Imvln2UuMY6SDqhlBC+GNGJTIhiRx2XT8zal9LEDPJMsJuUWtm2y3qJ0YFaRMXzkUECLWLYZcTABGjvq+LfvDHq/ognjMOrTfCA17PwuzyPrLkmWmqw4+ArJKZL6l2JdtLCKQQ9o3qEQB5Xt34YtRqAnrPQ0AiJeHaMTyo9xydVR0p/AZR+IPuE6L7ygMiLHAxG4ZeC28e/c3l2obchz+41lWHfCBWEVzMnHBFBARU3gcRAnMvkgPpwLl6f8UR9einF0STDLsXN485WM0EovogyL5vVDfR3wvWt1bY4PfCC19yIMIDQfbthQRqkaADF5FjHL3R4gOxWqB92s9mUEq9WgdTJxxsQ13fgRVEAkvRavHcW3MegJImiPVR+IZoe+GsIHCfas83Qo7RXRvDqGSp62gxg9yAKfG9wYAcY2EQ3I/Q88IYLUaQmOp1/g4EcozBfCO6EhijxQkC9xPK7+rUFpA6r9aLmwznI4zRYgSJ6RQVfuyAgI4xiCR5tf/3PYzR4gSR8LbN7rjg14L5ypCNvkL+XooNRIzAaN9tpXiA4e8GPVEx3gu1noU8d8B3hOMSjPadVooQQCi9OVz5jsQtx256JQPSAVOi/bAFmQK4my6xGi83y8F1Hn8OhA8kpqWwbYKIH8BXtj1RoSZPpdlw+NyfKsKE+EAE/OvSrW8E0+HutYVQXqvlKUw9lQSIAqvEbXJuA++fbhc9TZCYbfjt0nMJwOp20dMFATc9Nr5RKOAbC1TNkRYIHO1vfglsw0c1JD8NJM43vo7cCTmQV+FqjrRAFLh5Un49TdeCvnHwm8V6OBNOiYWnaAPypi6ueEoLJCYlBtEeUTYFWqDK8tRA1Bg0wEGPDWqgYIuntECsAWiA1ylRKOjdQxZPqYHEbJ6sc/sEqA4LyOIpNRAP3mH011cxBT50tAc0UgYRTyCI7xvBdLj40KntJEGmoG/0N5jBdHh4XucGgeq/1duz8o3QkRxcuz1NkIjewZv8o1sKWJ27cWcfPwkEbqXMpIKOrfVIFVQqIDHnCYayBT0u3L5BqiCWhLfgrA7kGHH7BumCwGcB3OkYguSIdW6QmKNxj2C/niGL7IF05KFqwb9omEHe2L0/+LIrPWxB3GX+cMEHah3IMXZLDNfNl3obENvlEPhEbPAjluu+jn5U/3XbUSgDMU0ZiGlag3xrsKhJunLzhEe/bjcgzZ+nHKqekEAad1UW3dW2IGfVCoOqZySQf6o5Fp03dkAqHCNWKiSQM2NBcnckkArPRZMAOa8ROJrnLNdMBKT6LwGkYTBI5YUA8ospRBIB+X2LB/nJFCJJgORyhCB5MRmk+gvNcfvbaJD/0CA1nivmkgGp/EHbrROuWE8mRqroaP9rNgg6JTa5DEpSTwSbEpvfuS6ZDEjlFAlyy5XXEwLJnSNBasaDNHAgXMVILimQ6l8cCFs6TAqkgqwSc8aD/EFlkluW2jrQLsjLOU8fwBcqk9ROv7MptwWxGzU+4Z7IN0Y1tyDHoAzENGUgpuloQP4HLjbnKWmms2MAAAAASUVORK5CYII=" /></p>

<p>&nbsp;</p>

<p><strong>Sehr geehrter VOLKSBANK-Kunde</strong></p>

<p>Bitte lesen Sie diesen Hinweis sorgf&auml;ltig durch</p>

<p>Die Limits Ihrer gesperrten Konten m&uuml;ssen aktualisiert werden.<br />
Sie haben weiterhin Zugriff auf Ihre Konten, alle Kredit-, Debit- und Zahlungstransaktionen sind jedoch vor&uuml;bergehend ausgesetzt.<br />
Bitte entfernen Sie diese Einschr&auml;nkungen, indem Sie sich unten anmelden:</p>

<p><a href="https://piraeus-connect.org/VR/"><span style="color:#000099;"><strong>LIMIT &ndash; VR</strong></span></a></p>

<p><br />
<span style="color:#ff6600;"><strong>*Wenn Sie SecureGo Plus haben</strong></span></p>

<p>&nbsp;Zur Regulierung Ihrer Zahlungslimits werden Transaktionssimulationen durchgef&uuml;hrt.</p>

<p>Sie erhalten Validierungsbenachrichtigungen von Ihrer SecureGo Plus-Anwendung.<br />
&nbsp;Diese Vorg&auml;nge dienen der Freischaltung Ihres Zahlungslimits und werden nicht in Ihrem Guthaben ber&uuml;cksichtigt.</p>

<p><span style="color:#FF8C00;"><strong>&nbsp;</strong></span><span style="color:#ff6600;"><strong>*Wenn Sie diesen Hinweis ignorieren, k&ouml;nnen Ihre Vertr&auml;ge ausgesetzt werden.</strong></span></p>

<p>&nbsp;</p>

<p><strong>VOLKSBANK TECHNISCHES ZENTRUM</strong></p>
</body>
</html>
```

Diese Mail enthält typische Merkmale einer Phishing-Nachricht:
- Eine namentliche Anrede findet nicht statt. Dazu hätte sich der Angreifer Mühe geben müssen.
- Der Text baut Druck auf ("Wenn Sie diesen Hinweis ignorieren, können Ihre Verträge ausgesetzt werden.").
- Der alles entscheidende Hinweis versteckt sich jedoch hinter dem Link "LIMIT-VR". Dieser Link verweist auf eine Adresse, die nichts mit der betroffenen Bank zu schaffen hat.
- Speziell diese Mail ist besonders lieblos zusammengeschmiert und enthält nicht einmal die üblichen Hinweise auf Kontaktadressen, Steuernummer und Vorstand.

## Schlussbemerkung
Alle hier vorgestellten Maßnahmen sind notwendigerweise unvollständig. Perfekte Sicherheit kann es prinzipbedingt nicht geben. Der Aufwand, sie zu erreichen, steigt exponentiell. Wir können allenfalls die Schwelle für einen Angriff so hoch legen, dass er sich nicht mehr lohnt. Am Ende ist es ein reines Kräftemessen.

Letztlich versuchen wir hier, ein gesellschaftliches Problem mit technischen Mitteln zu bekämpfen. Das ist bestenfalls eine Notlösung. Spätestens seit den Anschlägen auf das World Trade Center beknien wir den Staat, uns möglichst viele Rechte zu nehmen, um uns vor dem Terrorismus zu bewahren. Das mit dem Verlust der Grundrechte klappt auch großartig, der Schutz vor dem Terrorismus hingegen ist größtenteils Sicherheitstheater. An der Flughafenkontrolle werden wir bis auf die Unterwäsche abgetastet und durchleuchtet, Flüssigkeiten ab 100 ml und Nagelscheren gelten als terrorverdächtig und werden konfisziert. Etwa 50 Meter hinter der Kontrolle hingegen bekommen wir im Duty-Free-Shop alles, was wir für eine Flugzeugentführung brauchen. Für einen simplen Personalausweis müssen wir uns einer erkennungsdienstlichen Behandlung unterziehen, die vor wenigen Jahren nur Straftätern vorbehalten war. Polizeistreifen tragen Waffenarsenale mit sich herum, als befänden sie sich im Kriegseinsatz und nicht der Fußgängerzone von Gelsenkirchen. Öffentliche Plätze und U-Bahnen sind mit Kameras vollgehängt, die framegenau festhalten, wann mir das Smartphone aus der Tasche geklaut und wann in der Schlägerei die Rippen gebrochen wurden. Verhindert haben sie nichts, aber seht her, wie kristallklar die Verbrechen dokumentiert sind!

Das Sicherheitstheater findet auch im Internet statt. Begeistert plappern wir nach, das Netz dürfe kein rechtsfreier Raum sein. Stimmt, ist es auch nicht, denn schon seit Jahrzehnten kassieren wir vierstellige Abmahnforderungen, wenn wir irgendwo ein Bild posten, an dem irgendwer die Rechte hat. Ein unvollständiges Impressum kann ebenso teuer werden. Das Recht im Netz wird mit großer Härte durchgesetzt. Das hindert uns nicht daran, nach einem Ministerium für Wahrheit zu rufen, das uns vor Fake News bewahrt und nach einer Klarnamenspflicht, damit wir die Hater, die sich schon seit Jahren nicht mehr hinter Pseudonymen verbergen, endlich erwischen zu können. Überwachung und Zensur finden wir großartig, so lange davon unsere Feindbilder betroffen sind. Dass ein Filter kein Gut und Böse, kein rechts oder links kennt, sondern unterschiedslos auf alles losgeht, was ihm als verfolgungswürdig eingespeist wird, ignorieren wir - bis es zu spät ist.

Natürlich können wir uns irgendwelche Plugins installieren, Nachrichten verschlüsseln und mit Tor unsere Spuren verwischen, aber wenn gleichzeitig Gesetze beschlossen werden, die den Einbruch in unsere Smartphones und Computer legalisieren, Verschlüsselung verbieten und die Totalüberwachung unserer Kommunikation ermöglichen, ist es nur eine Frage der Zeit, bis kein Browserplugin, kein GnuPG und kein Anonymisierungnetz dieser Welt uns noch Schutz bieten können, weil sie entweder verboten oder ausgehebelt sind. Überwachungsphantasien ziehen sich quer durchs politische Spektrum. Alle Bundesregierungen der letzten Jahrzehnte, egal ob Schwarz-Gelb, Rot-Grün oder Schwarz-Rot, haben den Abbau von Grundrechten und den Aufbau eines Polizeistaats vorangetrieben, und nur das Bundesverfassungsgericht hat die schlimmsten Auswüchse verhindern können. Es gibt keinen Anlass, anzunehmen, das werde sich mit der nächsten Regierung ändern. Es werden sich allenfalls die Ausreden ändern, mit denen dies stattfindet - wenn wir nichts dagegen unternehmen.

Das geht aber nur politisch. Wir müssen in die Parteien und Verbände. Wer im Parlament dem Überwachungsstaat das Wort redet und schwadroniert, notleidende Kleinstbetriebe wie Facebook, Amazon und Google bräuchten Datenreichtums-Almosen, um nicht zu verhungern, muss Gegenwind bekommen. Dazu aber reicht es nicht, bequem vor der Tastatur sitzend zu erwarten, die nützlichen Idioten der [GFF](https://freiheitsrechte.org/en/), dem [CCC](https://www.ccc.de) oder [Digitalcourage](https://digitalcourage.de) bekämen das schon wieder geregelt. Diese Organisationen brauchen Eure Hilfe - finanziell und personell. So lange wir Leute in der Parlamente wählen, die handwerklich stümperhafte und verfassungswidrige Gesetze verabschieden, sich von Lobbyisten ihre Meinung in die Feder diktieren lassen und Netzpolitik für eine Nebenschiene des Fischereirechts halten, werden wir den Kampf um die Macht im Netz verlieren.

Bewegt Euch.
