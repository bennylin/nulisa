Nulisa Aksara Jawa
==================

```
This program is free software: you can redistribute it and/or modify it under the terms of the GNU 
General Public License as published by the Free Software Foundation; either version 3 of the License, 
or (at your option) any later version.

This program comes with ABSOLUTELY NO WARRANTY; see LICENSE file.
```

About
-----
Google Input Tools for Windows is an input method editor which allows users to enter text in any of the supported languages using a Latin (English / QWERTY) keyboard. Users can type a word the way it sounds using Latin characters and Google Input Tools for Windows will convert the word to its native script. Available input tools include transliteration, IME, [user-defined dictionary, user-defined transliteration schemes] and on-screen keyboards.  Features

    Offline Support
    No internet connection is required.

    Word Completions
    Dictionary-based word completions for prefixes.

    Personalized Choices
    Remembers user corrections along with macro and canonical support.

    Easy Keyboard
    Dictionary-enabled keyboard to enter rare and complex words.

    Quick Search
    Single-click web search for highlighted words.

    Cool Customizations
    Customize candidate window size, display fonts and more.

"Nulisa" Aksara Jawa scheme is a transliteration scheme to input Javanese script using a regular QWERTY keyboard, geared toward Latin-alphabet readers and typist, as an alternative of numerous Javanese keyboard layout scheme. This IME scheme  dramatically increases typing speed, and decrease difficulty (barrier entry) for new users by not requiring to memorize almost any special characters (SHIFT, ALT, CTRL, etc.).

Currently Nulisa-v1 hasn't been officially supported by Google, therefore, people who wish to use this transliteration scheme need to download an input method for other language (for example Sanskrit), and then use the Nulisa scheme. Because of that, there's no on-screen keyboard or handwriting recognition yet.

Installation
-------------
1. Install Google IME (Input MEthod) for your chosen language: http://www.google.com/inputtools/windows
2. Download the "Nulisa" Aksara Jawa transliteration schemes [v.1 - Okt 2014] (https://github.com/bennylin/google-ime-scm/tree/master/JV_Nulisa.scm). Check the checkbox before "I agree to the Google Terms of Service and Privacy Policy.", and click "Download" button to download installer. Run the installer after download completed, and follow the instructions on screen. 
3. Copy your chosen scheme file to Google IME Scheme's directory: [Google IME Canonical Scheme] (http://www.google.com/inputtools/windows/canonical.html). The directory mentioned on the previous link is wrong (as of 5/2013). The correct directory for {language} is: ```C:\ProgramData\Google\Google Input Tools\com.google.input_tools.t13n.ime.{language}\schemes\```. ProgramData is usually a hidden directory under C:\\.
4. From Window's language bar select your language, in Google IME select your chosen scheme (Shortcut: Ctrl-M).
5. You can now start typing according to "Nulisa" Aksara Jawa scheme into any Unicode aware application (Open Office, Windows 8.1 programs, etc).

Caveats
-------
* For aksara swara, type the capital letter: "A" for ꦄ "E" for ꦌ"I" for ꦆ , "O" ꦎ , and "U" for ꦈ
* For aksara murda, type the capital letter or the indic transliteration: "Ba" or "bha" for ꦨ
* For aksara rekan, only three are supported in "Nulisa-v1": "f" ꦥ꦳, "v" ꦮ꦳, "z" ꦗ꦳
* When you type a consonant, the corresponding aksara will be accompanied with pangkon: "b" -> "ꦧ꧀"
  only when you type a vocal, the pangkon will be deleted, or replaced by a sandhangan swara: "ba" -> "ꦧ", "be"  -> "ꦧꦺ", etc.
* For ě (pěpět), type "x", lě (nga lělět), type "lx", rx (pa cěrěk), type "rx"
* Lowercase q and uppercase Q is reserved for special characters and quite a few shortcuts.

  q -> pangkon ꧀

  qq -> ꧁

  qqq -> ꧂

  Q -> ꧃

  Qq -> ꧄

  Qqq -> ꧅

  qa -> ꦐ
  qi -> ꦶ
  qu -> ꦸ
  qe -> ꦺ
  qai -> ꦻ
  qx -> ꦼ
  qo -> ꦺꦴ
  qaa -> ꦴ
  qeu -> ꦵ
  qii -> ꦷ
  quu -> ꦹ
  qrx -> ꦽ
  qya -> ꦾ
  qy -> ꦾ
  qra -> ꦿ
  qr -> ꦿ

* Some other special combination:
  jnya -> ꦘ
  rra -> ꦬ
  aum -> ꦎꦀ
  
  leq -> ꦭꦼ

* Punctuations:
  | -> ꧊
  || -> ꧋
  , -> ꧈
  . -> ꧉
  : -> ꧇
  ( -> ꧌
  ) -> ꧍

Test
----

* The following words/phrases have been tested succesfully. (↵ denote "Enter" key)

  "isor brengos nyakil mrongos". type: "isor↵ brengos↵ nyakil↵ mrongos↵"
  "cumplung kecemplung jumbleng". type: "cumplung↵ kxcxmplung↵ jumblxng↵"
  "ngrungkel"
  "nyruput"
  "hyang"
  "nggambleh"
  "nylamur"
  "nyludhag"
  "nylonong"
  "nylêkit"
  "ngrêmbug"
  "nyrêpêg"
  "nangkêpwrêgul"
  "nggrêsula" 
  "nggrêmêt"
  "nggrêgessi"
  "munggwing"
  "anggyat"

  "hambyur" = ꦲ​ꦩ꧀ꦧꦾꦸꦂ
  "ndlajus" = ꦤ꧀ꦢ꧀ꦭ​ꦗꦸꦱ꧀
  "mblujur" = ꦩ꧀ꦧ꧀ꦭꦸꦗꦸꦂ
  "liwat kreteg" = ꦭꦶꦮ​ꦠ꧀ꦏꦽꦠꦼꦒ꧀
  "mangan krupuk" = ꦩꦔ​ꦤ꧀ꦏꦿꦸꦥꦸꦏ꧀
  "krapês-krapês" = ꦏꦿ​ꦥꦼꦱ꧀ꦏꦿ​ꦥꦼꦱ꧀
  "krepyak-krêpyêk" = ꦏꦿꦺꦥꦾ​ꦏ꧀ꦏꦽꦥꦾꦼꦏ꧀
  "krubyuk-krubyuk" = ꦏꦿꦸꦧꦾꦸꦏ꧀ꦏꦿꦸꦧꦾꦸꦏ꧀
  "kyèyèt-kyèyèt" = ꦏꦾꦺꦪꦺꦠ꧀ꦏꦾꦺꦪꦺꦠ꧀
  "gêlêm nurut" = ꦒꦼꦊꦩ꧀ꦤꦸꦫꦸꦠ꧀
  "gêlêm nampa" = ꦒꦼꦊꦩ꧀ꦤ​ꦩ꧀ꦥ​

* Mengapa aksara "dha"-nya aneh? 
  ꦝ yang kontroversial. Konsonan letup retrofleks ḍa (sekarang biasa ditulis "dha") seharusnya pakai ꦝ, bukan ꦣ. ꦣ adalah ꦢ da yang disertai hembusan napas (mahaprana) "dha" dalam Jawa Kuna. Dulu saya juga merasa tidak nyaman dan pernah protes tentang hal ini pada Pak Hadiwaratama, Ketua Tim Registrasi Aksara Jawa ke Unicode. Menurut beliau "padhajayanya (paḍajayanya)" menurut standar Unicode ditulis ꦥꦝꦗꦪꦚ. Sehingga "kodhok (koḍok)" ꦏꦺꦴꦝꦺꦴꦏ꧀, "dhadhu (ḍaḍu)" ꦝꦝꦸ, "dhawul-dhawul (ḍawul-ḍawul)" ꦝꦮꦸꦭ꧀ꦝꦮꦸꦭ꧀, "wedhus (weḍus)" ꦮꦼꦝꦸꦱ꧀, dll. Saya juga bertanya kepada beliau, jika bentuk aksara standarnya ꦝ, apakah tulisan di buku-buku, papan nama, dll. harus ditulis ulang? Apakah guru, murid, & masyarakat harus dibiasakan menggunakan ꦝ? Beliau menjawab biarlah mengalir apa adanya. Jika ingin berkomunikasi langsung dengan Pak Hadiwaratama, kunjungi http://ganeshana.org/. Di situ ada alamat e-mail beliau.
  https://www.facebook.com/groups/aksara.jawa/permalink/447691318648472/
  https://scontent-a-sin.xx.fbcdn.net/hphotos-xap1/v/t1.0-9/282319_453514664731257_1235148416_n.jpg?oh=b4bb892985920a69a90826dfccc0262d&oe=54F6CCDB

Features
--------
 http://www.google.com/inputtools/windows/features.html
 
 Status window

 When Google Input Tools is enabled for an application, it will display a status window on the screen. By default this window will be placed at the bottom-right corner of the desktop, but can be dragged to any other part of the screen as well. The status window contains configuration options for the currently selected input tool. It includes three to five icons (depending on the language and features available), with the application icon at the far left. Next to the application icon, in order, are the Input Tools language indicator, the keyboard button (not present for some languages), the canonical mode button (only present if you have canonical schemes associated with the input tool) and the menu button.

 Edit window (Candidate list)

 When Input Tools is enabled for an application, it displays a window with the typed text and the corresponding word choices in the input language. In the below example, user has typed 'googl' and the input tool has displayed five choices (numbered 1 to 5). This window is sometimes called a 'candidate list'.

 Navigation and selection

 The currently selected (highlighted) candidate in the edit window is the active choice. The active choice can be changed by using the BOTTOM-ARROW or TAB keys to move down the selection, or the UP-ARROW or SHIFT + TAB keys to move up. To select one of the choices for input, use the ENTER key which inserts the active choice at the current cursor position. Using the SPACE key or any other PUNCTUATION CHARACTER also inserts the active choice, along with the typed punctuation character (unless the punctuation character matches one or more candidate suggestions). To insert any candidate, even if not the active choice, type its position number as in: CTRL + [choice_number].

 Word completions

 The choices displayed in edit window will appear in either BLACK or BLUE. Literal matches for what was typed are displayed in BLACK, and will always be grouped in front. If there are better dictionary-based word completions for what was typed, those choices are displayed in BLUE and placed behind.

 Paging

 The input tools only display five choices in the edit window by default (these five choices comprise a page). If there are more candidates, additional choices are displayed on the next page. To page up or down, use the small arrow buttons at the right side of the edit window, or use the Page Up and Page Down keys. Using the arrow or TAB keys to navigate choices will also move to the next or previous page when the active choice is at the start or end of the edit window. You can configure the number of choices displayed per page by clicking the status window's menu button.

 Search

 Clicking on the Google logo in the edit window will search the web for the active/highlighted choice using Google.com. Search can also be triggered for any non-active choice by right-clicking, and then clicking the Search… option.

 User cache

 In some circumstances, the initial active choice is the best option (in the example below, the second choice was the desired option).

To make input easier over time, Google Input Tools remembers previous selections and improves the order of candidates. To share this information across all applications for a user, this personalization is maintained for each user account on the computer. This personalization can be disabled by using the 'Disable User Cache' option, available from the menu button on the status window. Note that caching (personalization) does not apply for word completions shown in BLUE, only for word choices shown in BLACK.

 Switch to English

 The input tools can be switched on or off easily, allowing fast changes between typing in the input tool language and typing in English. To enable or disable the current input tool, click the input tool language button in the status window or use the keyboard shortcuts CTRL + G or F12.

 Keyboard

For some rare or complex words, the input choices given may not include the intended word or phrase. In these situations, the flexible keyboard allows input of any possible word. To open the flexible keyboard, click the keyboard button on status window or by using the keyboard shortcut CTRL + K. To enter characters, you can either type on your physical keyboard or use the mouse to pick on the flexible keyboard. You can hide/show the on-screen keyboard by clicking the up/down arrow on status window. It can be closed by clicking the keyboard button again on status window, or by using the shortcut CTRL + K or ESC.

 Customization

 You can customize many features in the Google Input Tools menu. Options available through the popup menu in the status window are:

    Change or activate one of the available canonical schemes (available only if there is at least one scheme in the Schemes directory).
    Select the font and size to be used to display candidates in the edit window (Suggestion Font).
    Select the font and size to be used to display English/Latin characters inside the edit window.
    Set the page size for the edit window (to restrict the number of choices offered).
    Enable or disable the user cache.
    Add/Edit or Delete macros.
    Information about Google Input Tools, including current version.
    Help documentation, which links to this page.

 Special cases

 There are some special cases in how the input tools behave for some characters in some languages:

    Example in Arabic for the special case of a SPACE, where it is part of the typed word: Space special
    Example in Arabic for the special case of PUNCTUATION, where it is part of the typed word: PUNCTUATION special
    Example in Greek for the special case of CAPITALIZATION, where the first character in uppercase retains its casing: Camelcase special
    Example in Greek for the special case of CAPITALIZATION, where an all uppercase word retains its casing. Camelcase special
    Example in Greek for the special case of DIGITS, where the number is converted digits instead of its whole value: 

Troubleshooting
---------------
* The font didn't come out right
  Please download the font first. Search for "Tuladha Jejeg" on the web. Windows 8.1 already has a font called "Javanese script" (a.k.a. Tuladha Jejeg) installed.

* How do I check if what I'm typing is correct or not?
  Use the Aksara-to-Latin transliterator online tool at http://is.gd/nulisa. You can also download that page for offline use.

* I didn't see the Language Toolbar
  Follow the instruction http://www.google.com/inputtools/windows/configuration.html
  If the 'Language bar' option is not visible in the 'Toolbars' menu, it needs to be enabled through the Control Panel
  (Control Panel → Regional and Language Options → Keyboard and Languages)
  For Windows XP users, see http://www.google.com/inputtools/windows/windowsxp.htmlm
  
* How do I make a personalized dictionary (macro)?
  http://www.google.com/inputtools/windows/macros.html
  Google Input Tools supports adding custom user defined macros. Macros are short character sequences mapped to a word of your choice. When you type a character sequence, if there is a word corresponding to that sequence in the user-defined macros collection it will be shown as the first choice in the edit window. You can manage the macros by choosing the 'Manage Macros…' option from the Input Tools menu. 
  
   When you select this option the 'Manage Macros' dialog opens, allowing you to add, modify and delete the set of macros. 
   
    Click on the 'Add' button. This will add an empty row to the Macros List. You can double-click on the cell (or select it and press F2) to add the new Macro entry.

    Macro Text should consist of only alpha-numeric characters and the length should not exceed 100 characters. Macro Text is case-sensitive.
    Macro Target should not contain any spaces and the length should not exceed 50 characters.

 Once you have the Macros in place you can use them while typing. For example if 'Mon' is mapped to ꦩꦺꦴꦤ꧀ in the Macros, then when you type 'Mon' you will see ꦩꦺꦴꦤ꧀ as the first option. 

* Other questions, see http://www.google.com/inputtools/windows/troubleshooting.html

