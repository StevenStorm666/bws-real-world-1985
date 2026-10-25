# Real World 1985 — a Boxing World Simulator database

A world for Boxing World Simulator that starts on 1 January 1985 with real people only: the boxers, champions,
promoters, trainers, gyms and officials of the time, as far as open sources let us find them. Tested with game
version 2.3.0.

## What is in it

- **1,592 pros** from 72 nations as they stood on 1 January 1985: record, age, weight class, nationality, promoter and
  trainer. Larry Holmes, Marvin Hagler, Thomas Hearns, Julio César Chávez, Azumah Nelson, Khaosai Galaxy and the rest.
- **The champions of the day:** the WBC, WBA and IBF title holders of 1 January 1985, plus European (EBU), North American
  (NABF), Oriental and Pacific (OPBF), British and other national champions.
- **1,550 future pros** who turn professional in the year they really did, 1985 to 2017: Mike Tyson in March 1985,
  then Evander Holyfield, Roy Jones Jr., Oscar De La Hoya, Manny Pacquiao, Floyd Mayweather Jr., the Klitschkos, Canelo
  and many more, including 122 women.
- **209 amateurs** of 1985, from the 1984 Olympic teams and the European and world championships, who can turn pro
  during the game.
- **65 promoters** that existed in 1985 (Top Rank, Don King Productions, Main Events, …), **387 trainers** who were
  working then (Eddie Futch, Emanuel Steward, Angelo Dundee, Cus D'Amato, Kevin Rooney, …), **172 gyms**,
  **378 venues**, **107 judges and referees**, and the sanctioning bodies, TV networks and magazines.

From the game's default world:
- **Sponsors and anti-doping agencies:** the game's own 99 sponsors and 5 agencies, unchanged, so some are modern
  (betting sites, streaming, agencies founded after 1985).
- **Sanctioning bodies:** the game's set of 23, with their real names, founding years and 1985 descriptions. Bodies
  founded later, such as the WBO (1988), only appear in the game from their founding year.
- **TV networks and magazines:** real names and histories; their audience and money figures are the game's.
- **Managers:** the database has none; the game creates them.

## Install

1. Close the game.
2. Download `Real_World_1985.bwdb.json` from the [latest release](https://github.com/StevenStorm666/bws-real-world-1985/releases/latest).
3. Put it in the game's database folder, `Documents\Boxing World Simulator\Databases\` (the game creates the folder on
   its first start). If you have an older version of the file, replace it.
4. Start the game, start a new career or Simulation Mode and pick **Real World 1985** under "Choose your world" with start year **1985**.

## Pictures

The database comes without pictures. If you have your own, put them in
`Documents\Boxing World Simulator\Portraits\Real World 1985\` under the file names the database refers to
(for example `Boxers/rw43.png`).

## Versions

Each release is a git tag `db-vN`; `git tag -n1 -l 'db-v*'` lists them with what changed. Release candidates are tagged
`db-vN.rcM`.

## Known gaps

See [TODO.md](TODO.md).

## Licence

The database is licensed under [CC BY 4.0](LICENSE). Boxing World Simulator and the parts of the database that come
from the game itself (sponsor and agency descriptions) belong to the game's developer.
