---
layout: post
title: "Skrzynka z narzędziami"
crawlertitle: "Skrzynka z narzędziami"
summary: "Wachlarz umiejętności"
date: 2018-08-06
categories: wpisy
tags: ['gamedev']
author: "Bartłomiej T. Listwon"
---
Nauka może być najnudniejszą, bądź najbardziej epicką czynnością. Perspektywa długiej drogi do osiągnięcia celu może być odstraszająca, bądź ekscytująca. Wszystko zaczyna się w głowie.
<!--more-->

## Budowę domu zaczyna się od kawy

Marzenie, pomysł, plan to też część procesu twórczego. Znajomość wielu narzędzi nie tylko pozwala dobierać optymalne rozwiązania, ale też w razie ich braku tworzyć zupełnie nowe.

Dużo czasu poświęcam na eksperymentowanie. Poznaję nowe języki, wzorce projektowe, poszukuję aplikacji, które lepiej sprawdzają się w mojej pracy. Niedawno zacząłem zapoznawać się z [Haskellem](https://www.haskell.org/) i zauważyłem elementy, na których wzorowany był język [Rust](https://www.rust-lang.org/pl-PL/) (jak choćby pattern matching, który występuje również w [GDScripcie](http://docs.godotengine.org/en/3.0/getting_started/scripting/gdscript/gdscript_basics.html#match)).

Zainteresowany tematem proceduralnego generowania bezszwowych tekstur przeglądałem różne implementacje algorytmów do tworzenia powtarzalnych wzorów. Dla treningu przepisałem [generator szumu](https://github.com/Listwon/noise_gen) z języka [Python](https://www.python.org/) na Rust. Liznąłem też [Lua](https://www.lua.org/) analizując węzły z programu [Tilemancer](https://led.itch.io/tilemancer). Przy okazji zabaw z obrazami poznałem bardzo prostą w implementacji rodzinę formatów [PNM](https://en.wikipedia.org/wiki/Netpbm_format) pozwalającą na zapis w czytelnej formie tekstowej. Zacząłem pisać własny generator tekstur w oparciu o silnik [Godot](https://godotengine.org/).

W ostatnim czasie przetwarzam dużo plików w formatach JSON i XML, i w zależności od docelowego wykorzystania przeważnie wygodniej pracuje mi się z JSONem w [Node.js](https://nodejs.org/en/), zaś z XMLem w [C#](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/).

Poznając wzorzec [ECS](https://en.wikipedia.org/wiki/Entity%E2%80%93component%E2%80%93system) zainteresowałem się frameworkiem [Entitas](https://github.com/sschmid/Entitas-CSharp), który integruje się z silnikiem [Unity](https://unity3d.com/). Wtedy też po raz pierwszy dowiedziałem się o narzędziu [Roslyn](https://github.com/dotnet/roslyn), które obecnie coraz intensywniej wykorzystuję do generowania kodu C# na podstawie kodu w innym języku.

Podstawowe narzędzia, z których korzystam na co dzień to [Sublime Text 3](https://www.sublimetext.com/), [Cmder](http://cmder.net/) i [Git](https://git-scm.com/). Przez pewien czas byłem zachwycony graficznym interfejsem Gita dostarczanym przez [GitKraken](https://www.gitkraken.com/), ale im dłużej z niego korzystam, tym bardziej mnie frustrują długie czasy ładowania i zwiechy przy bardzo dużych projektach. Do łask powrócił Git w wierszu poleceń. Obiecująco zapowiada się projekt [lazygit](https://github.com/jesseduffield/lazygit), jako pewien kompromis między graficznym interfejsem a konsolą. Wczoraj, po wielu miesiącach pracy z ustawionym w moich narzędziach fontem [Hack](https://sourcefoundry.org/hack/), przesiadłem się na jeszcze przyjemniejszy [Iosevka](https://be5invis.github.io/Iosevka/), który m.in. zawiera ligatury dla symboli używanych w językach programowania i lepiej radzi sobie z renderowaniem [box-drawing characters](https://en.wikipedia.org/wiki/Box-drawing_character) używanych w wielu konsolowych aplikacjach.

Postawiłem na własnym VPSie serwis [Gitea](https://gitea.io/en-us/) do obsługi prywatnych repozytoriów GITa i korzystając z [Termuxa](https://termux.com/) na smartfonie, zapisywałem w podróży notatki i wysyłałem do repozytorium.

Wróciłem do nauki rysowania i zaczęła mi doskwierać nierozwiązana już przez ponad rok sprawa utlenionej gumowej warstwy na piórku od tabletu, która stała się kleista i zbierała brud. Oklejone taśmą piórko wyglądało ohydnie. Wczoraj wpadłem na pomysł, żeby usunąć taśmę, zdrapać brud i wciąż lepką, ale czystą gumę utrwalić bezbarwnym lakierem. Zadziałało, piórko jest gładkie, nie klei się do palców i nie zbiera brudu.
