# Minecraft

--minutes command block--

/execute @a[scores={sec=60..}] ~ ~ ~ scoreboard players add @a min 1

/execute @a[scores={sec=60..}] ~ ~ ~ scoreboard players remove @a sec 60

--hours command block--

/execute @a[scores={min=60..}] ~ ~ ~ scoreboard players add @a hour 1

/execute @a[scores={min=60..}] ~ ~ ~ scoreboard players remove @a min 60

--day command block--

/execute @a[scores={hour=24..}] ~ ~ ~ scoreboard players add @a day 1

/execute @a[scores={hour=24..}] ~ ~ ~ scoreboard players remove @a hour 24

--week command block--

/execute @a[scores={day=7..}] ~ ~ ~ scoreboard players add @a week 1

/execute @a[scores={day=7..}] ~ ~ ~ scoreboard players remove @a day 7

--month command block--

/execute @a[scores={week=30..}] ~ ~ ~ scoreboard players add @a month 1

/execute @a[scores={week=30..}] ~ ~ ~ scoreboard players remove @a week 30
