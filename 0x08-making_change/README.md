0x08. Making Change


Algorithm
Python

Given a pile of coins of different values, determine the fewest number of coins needed to meet a given amount total.

1. Prototype: def makeChange(coins, total)
2. Return: fewest number of coins needed to meet total
	1. If total is 0 or less, return 0
	2. If total cannot be met by any number of coins you have, return -1
3. coins is a list of the values of the coins in your possession
4. The value of a coin will always be an integer greater than 0
5. You can assume you have an infinite number of each denomination of coin in the list
6. Your solution’s runtime will be evaluated in this task
