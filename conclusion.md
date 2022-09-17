{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "87cb2093-00ab-4f67-b688-b137488de945",
   "metadata": {},
   "source": [
    "# CONCLUSION"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7727051d-2670-4825-ac0e-d4f5cfda8020",
   "metadata": {},
   "source": [
    "FIFA22 is a football simulation video game developed by EA Vancouver as part of Electronic Arts' FIFA series. FIFA22 contains a rich dataset with plenty of attributes covering all aspects of a real-life footballer in an attempt to immitate him as much as possible in the virtual world. This rich dataset provides a huge oppurtunity for us, data scientists or data analysts to analyze and come up with visualizations and patterns. I will try to cover the following:\n",
    "\n",
    "The dataset distribution based on player nationality, player overall rating, age vs overall rating, player valuation and so on. The patterns in the dataset Top football playing Countries, Top Clubs, Top players and so on."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "05d530b6-7288-4c6d-8d94-780548465adf",
   "metadata": {},
   "source": [
    ">  14616 of the players are Right footed while Left footed players are 4549"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "12f260c8-d0cc-44ee-a74b-8e2318a83530",
   "metadata": {},
   "source": [
    ">most position played is Central midfield with 4191 and centre forward the least postion with players with 451 players"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8d9c43bd-b795-4e27-8a79-b3ff5ec43d2f",
   "metadata": {},
   "source": [
    ">England, Germany and Spain are the top 3 Country with the most players with 1717, 1214 and  1085 players respectively"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "e5a7d27b-9d90-4f14-ac76-b419b5bcc10c",
   "metadata": {},
   "source": [
    ">for the top 50 country with the most players, it can be seen that Bosnia has the oldest team, followed by china and Korea Republic and Paraguay while Netherland has the yougest team\n",
    "\n",
    ">for counties with at least 50 players, Indian players has least potential on average with 60, followed by China with 62 and Saudi Arabia with 65, republic of Ireland and Korea Republic with 67, and sweden, Japan, Bolivia and Northern Ireland with 68, and Austria with 69 making the country with the least potential on average while Portugese Players has the Highest Potential followed by Spanish and Italian players\n",
    "\n",
    ">In terms of total player value of TOP CLUBS, Machester city has the Most expensive squad, followed by PSG, while Arsenal has the least expensive squad followed by AC milan\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "701c0442-aef9-47e5-b959-7e506d2bba68",
   "metadata": {},
   "source": [
    ">out of the Top clubs, Real Mdrid has the highest wage bill with over 4M euros weekly followed by Mancity with 3.6M and ManUnited with 3.4 Euros, while AC milan has the least wage bill 986K\n",
    "weekly wage bill, followed by Dortmund with 1.3M\n",
    "\n",
    "> it shows left footed players has higher potential/overall, passing and dribbling thAN RIGHT FOOTED PLAYERS, but right footed Players has more shooting power\n",
    "\n",
    ">The Italian Seria A turns out to be the league with the oldest player on average(😀as we are all expecting), while the french Ligue has the youngest players on average\n",
    "\n",
    ">EPL turns to pay players more than the other major leagues, while French Ligue 1 pays the least\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "a9134508-4442-40b7-abcc-4ef5a543bd46",
   "metadata": {},
   "source": [
    ">EPL is the league with the highest total value of players, it also tops as the league with the average value with player of 14M euros on average\n",
    "\n",
    ">players playing in spanish league tends to have highest overall than other major league\n",
    "\n",
    ">players playing in EPL has the highest Potential on average while players in the french Ligue 1 has the least avreage potential of the 5 major league\n",
    "\n",
    ">Lionel Messi is the best Player with 93overall followed by lewandoski with 92 and C. Ronaldo with 91\n",
    "\n",
    ">K. Mbappe is the player with the highest potential of 95 followed by Messi, Donaruma, Halland who has 93\n",
    "\n",
    ">The top 3 best Goal keeper are 1. Oblak, 2. Ter stegen 3. Manuel Neuer\n",
    "\n",
    "> the the most expensive Goal keepers are Donaruma, oblak and ter Stegen\n",
    "\n",
    "> the Goal keepers with the highest wages are Ter Stegen, T. courtouis and Ederson\n",
    "\n",
    ">the # most expensive Players are K. Mbappe, E. halland and Harry Kane\n",
    "\n",
    "> The 3 oldest Players are C. Lucchett 43yrs old, Da Vaca 43yrs old, and G. Buffon(GK) 42yrs old\n",
    "\n",
    "> The Players with the Highest dribbling skill is Messi, followed by Neymar and Mbappe\n",
    "\n",
    "> PSG players has the best dribbling skills on average, followed by Juventus and Real Madrid\n",
    "\n",
    ">Porgueese, Brazilian and Argentinian players are the nationals the best dribbling skills on average\n",
    "\n",
    "> The 3 fastest players are Mbappe, Adama Traore and A. Davies\n",
    "\n",
    "> the players with the best finishing Ability is messi, Lewandoski and C. Ronaldo\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6602626b-5550-49fc-b4b8-b2e2ae23c526",
   "metadata": {},
   "source": [
    "## EPL"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8297a3e5-f2e1-407c-b496-04fccf5e454c",
   "metadata": {},
   "source": [
    ">there are 652 players playing in EPl \n",
    "\n",
    ">Norwich has the least weekly wage bill with 649K followed by Brentford with 704k, While Manchester City has the highest with 3.61M weeekly wage bill\n",
    "\n",
    ">K. De Bruyne 350K, R. Sterling 290K, and Critiano Ronaldo 270K Receive the highest wages in EPL\n",
    "\n",
    ">Burnley has the oldest squad in Epl while leeds has the youngest squad\n",
    "\n",
    ">H. Kane, K. De Bruyne and J sancho are the most valuable EPL players\n",
    "\n",
    "> Man city(3.61M) has the highest weekly  wage bill in EPL followed by Manchester United and Liverpoll while Brentford(704K) has the least"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d78e9bbd-c1a3-4f8e-8e54-7d6e3c034e16",
   "metadata": {},
   "source": [
    "## Nigerian Players"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7b66e52f-3698-4e8e-9f9c-e7ed75b68b22",
   "metadata": {},
   "source": [
    "> there are 125 Nigerian players in the DS\n",
    "\n",
    ">The league with most Nigerian players is Turkish Super Lig with 14 Nigerian players which accounts to 11.2% of the total Nigerian players in the dataset, followed by Norwegian eliteserien and Italian Serie A with 8 Nigerian Players each and the famous EPL, Danish superliga, belgian Jupiler Pro league and German 1. Bundesliga with 7 players each\n",
    "\n",
    ">Most nigerians players plays as a stricker 32%(40 players) of total players\n",
    "\n",
    "> Wilfried Ndidi is the highjest Nigerian footballer earner folowed by Kelechi Iheanacho and Iwobi earning 120K, 83K and 68K respectively\n",
    "\n",
    "> Wilfriend Ndidi is the Nigerian player with the highest potential with 88 followed by V. Osimen with 87 and Chukwueze 85\n",
    "\n",
    "> W. Ndidi is the most valuable Nigerian Player valued at 66.5M\n",
    "\n",
    "> C. Ejuke is the fastest Nigerian player with pace of 94\n",
    "\n",
    "> S. kalu is the Best Nigerian freekick taker\n",
    "\n",
    "> Nigerias best finisher is Osihmen\n",
    "\n",
    "> the player with the highest shot power is Nwakaeme\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6482484b-aa95-4611-ba0b-9d323fe407f6",
   "metadata": {},
   "source": [
    "## Predicted 2023 overall for some players\n",
    ">L. Messi\t91\n",
    "\n",
    ">R. Lewandowski \t90\n",
    "\n",
    ">Cristiano Ronaldo\t89\n",
    "\n",
    ">Neymar Jr\t90\n",
    "\n",
    ">K. De Bruyne\t89\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "8948f4ad-377f-4ab5-b261-9729b85e497c",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "",
   "name": ""
  },
  "language_info": {
   "name": ""
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
