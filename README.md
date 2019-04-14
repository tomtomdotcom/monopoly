# __How To Win at Monopoly Mathematically.__
## __About Me__

<img src="https://scontent-lhr3-1.xx.fbcdn.net/v/t1.0-9/44792270_10160905537130099_1105985144218451968_n.jpg?_nc_cat=100&_nc_ht=scontent-lhr3-1.xx&oh=4d3b5f25e396efaff8a395deab0db10f&oe=5D776302" width="400">

I am a Software Engineer with experience in scalable cloud based processing of real-time data using AWS solutions in Javascript/Typescript & Java. Currently working as a Software Engineer for a Gambling startup in London.

The purpose of this project is to gain some exposure into writing a thesis, dabble in some python and a bit of probability on the side.

## __Purpose?__

The aim of this _project_ is to determine if there is any specific way a player should play monopoly in order to consistently perform above and beyond the standard player.
* What squares should you purchase?
    * What squares are landed on the most?
    * What squares have the highest returns?
* When should you invest in hotels vs houses?
* How much of your capital should be invested?
* Is it beneficial to go first?

TBC..

## __The Basics of Monopoly__

__Monopoly__ is a board game published by Hasbro. Players roll two-six sided dice to move around the board whilst buying, trading, and developing properties with houses and hotels.

The aim of the game is to drive all the other players into bankruptcy, thus creating a _monopoly_. This is done by collecting rent from their opponents should they land on the players properties or from losing money through Chance or Community Chest cards.

## __What's in the box?__

All property deeds, houses, and hotels are held by the bank until bought by the players.

Traditionally this incorporates;

### __Cards__
A deck of thirty two Chance and Community cards (sixteen a piece) which a player draws when landing on the corresponding squares.

#### __Chance__
 
 * Advance to "Go"
 * Go to jail. Move directly to jail. Do not pass "Go". Do not collect £200
 * Advance to Pall Mall. If you pass "Go" collection £200
 * Take a trip to Marylebone Station and if you pass "Go" collect £200
 * Advance to Trafalgar Square. If you pass "Go" collect £200
 * Advance to Mayfair
 * Go back three spaces
 * Make general repairs on all of your houses. For each house pay £25. For each hotel pay £100
 * You are assessed for street repairs: £40 per house, £115 per hotel
 * Pay school fees of £150
 * "Drunk in charge" fine £20
 * Speeding fine £15
 * Your building loan matures. Receive £150
 * You have won a crossword competition. Collect £100
 * Bank pays you dividend of £50
 * Get out of jail free. This card may be kept until needed or sold

  Of the sixteen chance cards, five of them effect you negatively financially, three of them effect you positively financially, 3 of them have the possibility of collecting "Passing Go Money" dependant on your current board position.

 The "Get out of jail free" card can be sold to other players so is perhaps the most valuable.

#### __Community__

* Advance to "Go"
* Go back to Old Kent Road
* Go to jail. Move directly to jail. Do not pass "Go". Do not collect £200
* Pay hospital £100
* Doctor's fee. Pay £50
* Pay your insurance premium £50
* Bank error in your favour. Collect £200
* Annuity matures. Collect £100
* You inherit £100
* From sale of stock you get £50
* Receive interest on 7% preference shares: £25
* Income tax refund. Collect £20
* You have won second prize in a beauty contest. Collect £10
* It is your birthday. Collect £10 from each player
* Get out of jail free. This card may be kept until needed or sold
* Pay a £10 fine or take a "Chance"

Of the sixteen community chest cards, three of them effect you negatively financially, eight of them effect you positively financially, the remaining only effect your board position.

Again, the "Get out of jail free" card can be sold to other players so is perhaps the most valuable.

* __Deeds__

| Colour        | Name           | Price | House Price |
| ------------- |-------------| -----:| ---:|
| Brown      | Old Kent Road | £60 |£30|
| Brown      | Whitechapel Road      |   £60 |£30 |
| Light Blue | The Angel, Islington      |    £100 |£50|
|-|-|-|-|
| Light Blue | Euston Road      |    £100 |£50|
| Light Blue | Pentonville Road      |    £120 |£60|
|-|-|-|-|
| Pink | Pall Mall      |    £140 |£70|
| Pink | Whitehall      |    £140 |£70|
| Pink | Northumberland Avenue      |    £160 |£80|
|-|-|-|-|
| Orange | Bow Street      |    £180 |£90|
| Orange | Marlborough Street      |    £180 |£90|
| Orange | Vine Street      |    £200 |£100|
|-|-|-|-|
| Red | Strand     |    £220 |£110|
| Red | Fleet Street      |    £220 |£110|
| Red | Trafalgar Square      |    £240 |£120|
|-|-|-|-|
| Yellow | Leicester Square     |    £260 |£130|
| Yellow |Coventry Street      |    £260 |£130|
| Yellow | Piccadilly     |    £280 |£140|
|-|-|-|-|
| Green | Regent Street     |    £300 |£150|
| Green | Oxford Street      |    £300 |£150|
| Green | Bond Street     |    £320 |£160|
|-|-|-|-|
| Dark Blue | Park Lane      |    £350 |£175|
| Dark Blue | Mayfair     |    £400 |£200|