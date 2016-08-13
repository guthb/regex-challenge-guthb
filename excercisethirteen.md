#Regex

1. `/ Born.*\./`
2. `/Born.*release./`


#Test Strings
`John Winston Ono Lennon, MBE (born John Winston Lennon; 9 October 1940 – 8 December 1980) was an English singer and songwriter who co-founded the Beatles (1960-70), the most commercially successful band in the history of popular music. With fellow member Paul McCartney, he formed a lucrative songwriting partnership.` -- does not pass

`Born and raised in Liverpool, Lennon became involved in the skiffle craze as a teenager; his first band, the Quarrymen, evolved into the Beatles in 1960. When the group disbanded in 1970, Lennon embarked on a solo career that produced the albums John Lennon/Plastic Ono Band and Imagine, and songs such as "Give Peace a Chance", "Working Class Hero", and "Imagine". After his marriage to Yoko Ono in 1969, he changed his name to John Ono Lennon. Lennon disengaged himself from the music business in 1975 to raise his infant son Sean, but re-emerged with Ono in 1980 with the new album Double Fantasy. He was murdered three weeks after its release.` --- pass
`
`Lennon revealed a rebellious nature and acerbic wit in his music, writing, drawings, on film and in interviews. Controversial through his political and peace activism, he moved to Manhattan in 1971, where his criticism of the Vietnam War resulted in a lengthy attempt by Richard Nixon's administration to deport him, while some of his songs were adopted as anthems by the anti-war movement and the larger counterculture.` -- does not pass

`As of 2012, Lennon's solo album sales in the United States exceeded 14 million and, as writer, co-writer, or performer, he is responsible for 25 number-one singles on the US Hot 100 chart. In 2002, a BBC poll on the 100 Greatest Britons voted him eighth and, in 2008, Rolling Stone ranked him the fifth-greatest singer of all time. He was posthumously inducted into the Songwriters Hall of Fame in 1987, and into the Rock and Roll Hall of Fame twice, as a member of the Beatles in 1988 and as a solo artist in 1994.[1]  ....From Wikipedia, the free encyclopedia`  -- does not pass
