### HOW TO NOT RUN OUT OF FUEL: Calculating Number of Race Laps Remaining

When participating in races requiring refuelling, you do not want to run out of fuel at any time during the event. Aside from being embarassing, the lack of fuel will result in your car slowing drastically which in turn will result in your competitors gaining rapidly then overtaking you.

Yikes.

To avoid the above, it is important to know the number of laps remaining plus the number of laps of remaining fuel there is sloshing about in your fuel tank. To calculate the _number of race laps remaining_ you will need to know the following:

- Race Distance
- Current lap

To calculate the _Number of Race Laps Remaining_ use the following formula:

Number of race laps - (Current Lap + 1) = Number of Race Laps Remaining

#### Example

- Number of race laps: 13
- Current lap: 7
- 13 - (7 + 1) = 5

Compare the above result, _Number of Race Laps Remaining_, to the number of laps of fuel remaining in your fuel tank to determine whether or not refuelling is necessary.

IF _Number Of Race Laps Remaining_ is **GREATER THAN** Number Of Laps Of Fuel Remaining **THEN** Refuel
IF _Number Of Race Laps Remaining_ is **LESS THAN** _Number of Laps Of Fuel Remaining_ Race on!

```sh
if [ $NumberOfRaceLapsRemaining > $NumberOfLapsOfFuelRemaining ]
then
  Refuel
fi
```

- Number of Race Laps Remaining: 5
- Number of Laps of Fuel Remaining: 3
- 5 > 3 ∴ PIT!

```sh
if [ $NumberOfRaceLapsRemaining < $NumberOfLapsOfFuelRemaining ]
then
  Continue Racing
fi
```

- Number of Race Laps Remaining: 5
- Number of Laps of Fuel Remaining: 6
- 5 > 6 ∴ DO NOT PIT!

#### RESOURCES

- Mathmatics: [Inequality with Greater than and Less than symbols](https://www.smartickmethod.com/blog/math/mathematical-curiosities/math-symbols-greater-than-less-than-equal/)
- Mathmatics: [PEMDAS](https://www.purplemath.com/modules/orderops.htm)
- Bash: [IF-ELSE](https://linuxize.com/post/bash-if-else-statement/)
- Logic/Mathematical Proof: [Therefore/∴](https://en.wikipedia.org/wiki/Therefore_sign)

### LESSON PLAN <--- Don't like that wording Maybe Worksheet?

THIS SPACE LEFT BLANK BECAUSE REASONS
