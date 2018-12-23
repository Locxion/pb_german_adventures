[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

[![GitHub license](https://img.shields.io/github/license/vesturo/PhantomBotDE.svg?style=for-the-badge)](https://github.com/vesturo/PhantomBotDE/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/vesturo/PhantomBotDE.svg?style=for-the-badge)](https://github.com/vesturo/PhantomBotDE/issues)

![GitHub release](https://img.shields.io/github/release/vesturo/PhantomBotDE.svg?style=for-the-badge)

# Phantombot German Adventures
German Adventures for the Phantombot
Deutsche Abenteuer/Geschichten für den Phantombot


Ich möchte hier eine kleine Sammlung für Deutsche Abenteuer für den Phantombot zusammen tragen.
Jeder kann gerne einen Pull Request mit neuen Abenteuern beisteuern. Bitte beachtet die Reihenfolge der Stories und der Chapter.


Anleitung:

 * - Die Geschichten werden automatisch aus der games-adventureSystem.js mit den Sequenz Nummern geladen. (adventuresystem.stories.[Nummer])
 * - Bitte behaltet UNBEDINGT das unten stehende Format bei!
 * - Du kannst so viele Geschichten haben wie du möchtest, wenn die Sequenznummern sich nicht wiederholen und in der richtigen Reihenfolge sind!
 * - Jede Geschichte MUSS einen Titel haben!
 * - Jede Geschichte kann eine unbegrenzte Anzahl an Kapiteln haben, wenn die Sequenznummern sich nicht wiederholen und in der richtigen Reihenfolge sind!
 * - Die Geschichten werden Zufällig beim aktivieren des Abenteuers ausgewählt.

* ------------------------------------------------------------------------------------------------

 * - Es ist auch möglich, ein Abenteuer für ein Spezielles Spiel fest zu legen, solang man mindestens eine Geschichte ohne festes Spiel angelegt hat!
 * -Bitte geht sicher das die Nummer der Geschichten fortlaufend sind!
 * - $.lang.register('adventuresystem.stories.NUMMER.game', 'SPIEL NAME IN KLEINEN BUCHSTABEN');.

 * Beispiel >
 * $.lang.register('adventuresystem.stories.5.game', 'programming');
 * $.lang.register('adventuresystem.stories.5.title', 'Talk Shows');
 * $.lang.register('adventuresystem.stories.5.chapter.1', 'Zufällige Geschichte ...');
 *
 * Die Variable (caught) beschreibt Spieler die während der Geschichte geschnappt werden.
 * Die Variable (survivors) beschreibt die Spieler die die Geschichte überleben.
 * Ein Stück weiter unten findet ihr ein Template das ihr für neue Geschichten benutzen könnt. Einfach die // davor entfernen!

//$.lang.register('adventuresystem.stories.NUMMER.title', '');
//$.lang.register('adventuresystem.stories.NUMMER.chapter.1', '');
//$.lang.register('adventuresystem.stories.NUMMER.chapter.2', '');
//$.lang.register('adventuresystem.stories.NUMMER.chapter.3', '');
