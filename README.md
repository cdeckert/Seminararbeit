[![PDF Status](https://www.sharelatex.com/github/repos/cdeckert/Seminararbeit/builds/latest/badge.svg)](https://www.sharelatex.com/github/repos/cdeckert/Seminararbeit/builds/latest/output.pdf)


## Current Status ##

Notes! Please understand that this isn't the final version. It's just a collection of notes.

Thanks


# Futures, Scheduling, Work Distribution#

1. Agenda
2. Einleitung
	1. Fragestellung
	2. Abgrenzung von anderen Arten der Multiprozessorprgrammierung
	3. Aufteilung in Threads ineffizient
	4. Aufteilung in Tasks / Pools von Threads
3. Analyse von Parallelisierung
4. Herausforderung der Realisierung
5. Arbeitsverteilung
	1. Work Stealing
	2. Yielding and Multiprogramming
6. Konkrete Implementierung: Work-Stealing Dequeues
	1. An Unbounded Work-Stealing DEQueue
	2. Work Balancing