<template>
  <div class="hello">
    <ul>
      <li v-for="movie in movies" v-bind:key="movie._id">
        <span class="title">{{movie.title}}</span>
        <span>Rating: {{movie.rating}}/10</span>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Movies",
  data() {
    return {
      movies: [
        {
          _id: "5da6c7f3c277a40fef1e37bb",
          title: "Black and Blue",
          rating: 4.4,
          id: "tt7390646",
          _createdOn: "2019-10-16T07:34:11.083Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b7",
          title: "Escape Plan 2: Hades",
          rating: 4.1,
          id: "tt0926129",
          _createdOn: "2019-09-25T17:40:39.108Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b9",
          title: "Fifty Shades of Grey",
          rating: 4.1,
          _createdOn: "2019-09-25T17:40:39.108Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b8",
          title: "Prom Night",
          rating: 4.1,
          id: "tt2322441",
          _createdOn: "2019-09-25T17:40:39.108Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b2",
          title: "Street Fighter",
          rating: 4,
          id: "tt1014775",
          _createdOn: "2019-09-25T17:40:39.107Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b4",
          title: "Exorcist II: The Heretic",
          rating: 4,
          id: "tt0157262",
          _createdOn: "2019-09-25T17:40:39.107Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b3",
          title: "Beverly Hills Chihuahua",
          rating: 4,
          id: "tt0076009",
          _createdOn: "2019-09-25T17:40:39.107Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b6",
          title: "Holmes & Watson",
          rating: 4,
          id: "tt6513656",
          _createdOn: "2019-09-25T17:40:39.107Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b5",
          title: "2001: A Space Travesty",
          rating: 4,
          id: "tt1255919",
          _createdOn: "2019-09-25T17:40:39.107Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36ad",
          title: "S. Darko",
          rating: 4,
          id: "tt0180052",
          _createdOn: "2019-09-25T17:40:39.106Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36af",
          title: "Swept Away",
          rating: 4,
          id: "tt0308208",
          _createdOn: "2019-09-25T17:40:39.106Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36ae",
          title: "The Adventures of Pluto Nash",
          rating: 4,
          id: "tt0291502",
          _createdOn: "2019-09-25T17:40:39.106Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b1",
          title: "The Cat in the Hat",
          rating: 4,
          id: "tt0111301",
          _createdOn: "2019-09-25T17:40:39.106Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36b0",
          title: "Ballistic: Ecks vs. Sever",
          rating: 4,
          id: "tt0312528",
          _createdOn: "2019-09-25T17:40:39.106Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a8",
          title: "Stan Helsing",
          rating: 3.9,
          id: "tt1530509",
          _createdOn: "2019-09-25T17:40:39.105Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36aa",
          title: "Speed 2: Cruise Control",
          rating: 3.9,
          id: "tt1153706",
          _createdOn: "2019-09-25T17:40:39.105Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a9",
          title: "The Human Centipede II (Full Sequence)",
          rating: 3.9,
          id: "tt0120179",
          _createdOn: "2019-09-25T17:40:39.105Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a7",
          title: "In the Name of the King: A Dungeon Siege Tale",
          rating: 3.9,
          id: "tt1185266",
          _createdOn: "2019-09-25T17:40:39.105Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36ab",
          title: "Dance Flick",
          rating: 3.9,
          id: "tt0118661",
          _createdOn: "2019-09-25T17:40:39.105Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36ac",
          title: "The Avengers",
          rating: 4,
          id: "tt1231277",
          _createdOn: "2019-09-25T17:40:39.105Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a3",
          title: "The Flintstones in Viva Rock Vegas",
          rating: 3.8,
          id: "tt0094118",
          _createdOn: "2019-09-25T17:40:39.104Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a5",
          title: "The Love Guru",
          rating: 3.9,
          id: "tt0891592",
          _createdOn: "2019-09-25T17:40:39.104Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a4",
          title: "Teen Wolf Too",
          rating: 3.9,
          id: "tt0811138",
          _createdOn: "2019-09-25T17:40:39.104Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a1",
          title: "I Know Who Killed Me",
          rating: 3.8,
          id: "tt1714203",
          _createdOn: "2019-09-25T17:40:39.104Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a2",
          title: "Piranha 3DD",
          rating: 3.8,
          id: "tt0158622",
          _createdOn: "2019-09-25T17:40:39.104Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a6",
          title: "Street Fighter: The Legend of Chun-Li",
          rating: 3.9,
          id: "tt0460780",
          _createdOn: "2019-09-25T17:40:39.104Z"
        },
        {
          _id: "5d8ba697c277a40fef1e369e",
          title: "The Fog",
          rating: 3.8,
          id: "tt0119707",
          _createdOn: "2019-09-25T17:40:39.103Z"
        },
        {
          _id: "5d8ba697c277a40fef1e36a0",
          title: "Superman IV: The Quest for Peace",
          rating: 3.8,
          id: "tt0897361",
          _createdOn: "2019-09-25T17:40:39.103Z"
        },
        {
          _id: "5d8ba697c277a40fef1e369f",
          title: "Mortal Kombat: Annihilation",
          rating: 3.8,
          id: "tt0094074",
          _createdOn: "2019-09-25T17:40:39.103Z"
        },
        {
          _id: "5d8ba697c277a40fef1e369c",
          title: "Dungeons & Dragons",
          rating: 3.8,
          id: "tt0095560",
          _createdOn: "2019-09-25T17:40:39.103Z"
        },
        {
          _id: "5d8ba697c277a40fef1e369d",
          title: "Mac and Me",
          rating: 3.8,
          id: "tt0432291",
          _createdOn: "2019-09-25T17:40:39.103Z"
        },
        {
          _id: "5d8ba697c277a40fef1e369b",
          title: "The Wicker Man",
          rating: 3.8,
          id: "tt0190374",
          _createdOn: "2019-09-25T17:40:39.101Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3699",
          title: "Dragon Wars: D-War",
          rating: 3.8,
          id: "tt0085750",
          _createdOn: "2019-09-25T17:40:39.101Z"
        },
        {
          _id: "5d8ba697c277a40fef1e369a",
          title: "Jaws 3-D",
          rating: 3.8,
          id: "tt0450345",
          _createdOn: "2019-09-25T17:40:39.101Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3698",
          title: "Batman & Robin",
          rating: 3.8,
          id: "tt0372873",
          _createdOn: "2019-09-25T17:40:39.101Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3696",
          title: "Fifty Shades of Black",
          rating: 3.8,
          id: "tt0103923",
          _createdOn: "2019-09-25T17:40:39.100Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3694",
          title: "Bucky Larson: Born to Be a Star",
          rating: 3.7,
          id: "tt0110857",
          _createdOn: "2019-09-25T17:40:39.100Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3692",
          title: "Spy Kids 4-tt1517489D: All the Time in the World",
          rating: 3.7,
          id: "tt0295254",
          _createdOn: "2019-09-25T17:40:39.100Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3695",
          title: "Police Academy: Mission to Moscow",
          rating: 3.7,
          id: "tt4667094",
          _createdOn: "2019-09-25T17:40:39.100Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3693",
          title: "Feardotcom",
          rating: 3.7,
          id: "tt1411664",
          _createdOn: "2019-09-25T17:40:39.100Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3697",
          title: "Captain America",
          rating: 3.8,
          id: "tt0118688",
          _createdOn: "2019-09-25T17:40:39.100Z"
        },
        {
          _id: "5d8ba697c277a40fef1e368c",
          title: "Hercules in New York",
          rating: 3.6,
          id: "tt0065832",
          _createdOn: "2019-09-25T17:40:39.099Z"
        },
        {
          _id: "5d8ba697c277a40fef1e368f",
          title: "The Adventures of Sharkboy and Lavagirl 3-D",
          rating: 3.7,
          id: "tt0424774",
          _createdOn: "2019-09-25T17:40:39.099Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3691",
          title: "The Room",
          rating: 3.7,
          id: "tt0368226",
          _createdOn: "2019-09-25T17:40:39.099Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3690",
          title: "The NeverEnding Story III",
          rating: 3.7,
          id: "tt0110647",
          _createdOn: "2019-09-25T17:40:39.099Z"
        },
        {
          _id: "5d8ba697c277a40fef1e368d",
          title: "Spice World",
          rating: 3.7,
          id: "tt0120185",
          _createdOn: "2019-09-25T17:40:39.099Z"
        },
        {
          _id: "5d8ba697c277a40fef1e368e",
          title: "Crossroads",
          rating: 3.7,
          id: "tt0275022",
          _createdOn: "2019-09-25T17:40:39.099Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3687",
          title: "Dumb and Dumberer: When Harry Met Lloyd",
          rating: 3.6,
          id: "tt0329028",
          _createdOn: "2019-09-25T17:40:39.098Z"
        },
        {
          _id: "5d8ba697c277a40fef1e368a",
          title: "The Open House",
          rating: 3.6,
          id: "tt7608028",
          _createdOn: "2019-09-25T17:40:39.098Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3686",
          title: "Far Cry",
          rating: 3.6,
          id: "tt0400426",
          _createdOn: "2019-09-25T17:40:39.098Z"
        },
        {
          _id: "5d8ba697c277a40fef1e368b",
          title: "The Master of Disguise",
          rating: 3.6,
          id: "tt0295427",
          _createdOn: "2019-09-25T17:40:39.098Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3688",
          title: "Texas Chainsaw Massacre: The Next Generation",
          rating: 3.6,
          id: "tt0110978",
          _createdOn: "2019-09-25T17:40:39.098Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3689",
          title: "Scary Movie 5",
          rating: 3.6,
          id: "tt0795461",
          _createdOn: "2019-09-25T17:40:39.098Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3682",
          title: "Slender Man",
          rating: 3.5,
          id: "tt5690360",
          _createdOn: "2019-09-25T17:40:39.097Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3685",
          title: "Barb Wire",
          rating: 3.5,
          id: "tt0115624",
          _createdOn: "2019-09-25T17:40:39.097Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3684",
          title: "Daddy Day Camp",
          rating: 3.5,
          id: "tt0462244",
          _createdOn: "2019-09-25T17:40:39.097Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3683",
          title: "3 Ninjas: High Noon at Mega Mountain",
          rating: 3.5,
          id: "tt0118539",
          _createdOn: "2019-09-25T17:40:39.097Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3680",
          title: "The Starving Games",
          rating: 3.5,
          id: "tt2403029",
          _createdOn: "2019-09-25T17:40:39.096Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3681",
          title: "Vampires Suck",
          rating: 3.5,
          id: "tt1666186",
          _createdOn: "2019-09-25T17:40:39.096Z"
        },
        {
          _id: "5d8ba697c277a40fef1e367f",
          title: "Bratz",
          rating: 3.5,
          id: "tt0804452",
          _createdOn: "2019-09-25T17:40:39.096Z"
        },
        {
          _id: "5d8ba697c277a40fef1e367d",
          title: "Santa Claus Conquers the Martians",
          rating: 3.4,
          id: "tt0058548",
          _createdOn: "2019-09-25T17:40:39.094Z"
        },
        {
          _id: "5d8ba697c277a40fef1e367e",
          title: "The Emoji Movie",
          rating: 3.4,
          id: "tt4877122",
          _createdOn: "2019-09-25T17:40:39.094Z"
        },
        {
          _id: "5d8ba697c277a40fef1e367b",
          title: "Steel",
          rating: 3.4,
          id: "tt0120207",
          _createdOn: "2019-09-25T17:40:39.093Z"
        },
        {
          _id: "5d8ba697c277a40fef1e367c",
          title: "Catwoman",
          rating: 3.4,
          id: "tt0327554",
          _createdOn: "2019-09-25T17:40:39.093Z"
        },
        {
          _id: "5d8ba697c277a40fef1e367a",
          title: "Jack and Jill",
          rating: 3.4,
          id: "tt0810913",
          _createdOn: "2019-09-25T17:40:39.093Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3679",
          title: "Enes Batur",
          rating: 3.4,
          id: "tt7668842",
          _createdOn: "2019-09-25T17:40:39.093Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3676",
          title: "Kazaam",
          rating: 3.3,
          id: "tt0116756",
          _createdOn: "2019-09-25T17:40:39.092Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3678",
          title: "Gunday",
          rating: 3.4,
          id: "tt2574698",
          _createdOn: "2019-09-25T17:40:39.092Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3677",
          title: "Rollerball",
          rating: 3.4,
          id: "tt0246894",
          _createdOn: "2019-09-25T17:40:39.092Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3673",
          title: "The Human Centipede III (Final Sequence)",
          rating: 3.2,
          id: "tt1883367",
          _createdOn: "2019-09-25T17:40:39.091Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3671",
          title: "BloodRayne",
          rating: 3.1,
          id: "tt0383222",
          _createdOn: "2019-09-25T17:40:39.091Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3672",
          title: "Troll 2",
          rating: 3.2,
          id: "tt0105643",
          _createdOn: "2019-09-25T17:40:39.091Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3675",
          title: "Tees Maar Khan",
          rating: 3.3,
          id: "tt1572311",
          _createdOn: "2019-09-25T17:40:39.091Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3674",
          title: "Left Behind",
          rating: 3.3,
          id: "tt2467046",
          _createdOn: "2019-09-25T17:40:39.091Z"
        },
        {
          _id: "5d8ba697c277a40fef1e366e",
          title: "Who's Your Caddy?",
          rating: 3.1,
          id: "tt0785077",
          _createdOn: "2019-09-25T17:40:39.090Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3670",
          title: "Jaws: The Revenge",
          rating: 3.1,
          id: "tt0093300",
          _createdOn: "2019-09-25T17:40:39.090Z"
        },
        {
          _id: "5d8ba697c277a40fef1e366f",
          title: "Hobgoblins",
          rating: 3.1,
          id: "tt0089280",
          _createdOn: "2019-09-25T17:40:39.090Z"
        },
        {
          _id: "5d8ba697c277a40fef1e366d",
          title: "Race 3",
          rating: 3,
          id: "tt7431594",
          _createdOn: "2019-09-25T17:40:39.089Z"
        },
        {
          _id: "5d8ba697c277a40fef1e366c",
          title: "Baby Geniuses",
          rating: 2.9,
          id: "tt0118665",
          _createdOn: "2019-09-25T17:40:39.089Z"
        },
        {
          _id: "5d8ba697c277a40fef1e366b",
          title: "Date Movie",
          rating: 2.9,
          id: "tt0466342",
          _createdOn: "2019-09-25T17:40:39.089Z"
        },
        {
          _id: "5d8ba697c277a40fef1e366a",
          title: "Meet the Spartans",
          rating: 2.8,
          id: "tt1073498",
          _createdOn: "2019-09-25T17:40:39.089Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3667",
          title: "Daniel the Wizard",
          rating: 2.7,
          id: "tt0421051",
          _createdOn: "2019-09-25T17:40:39.088Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3668",
          title: "Gigli",
          rating: 2.7,
          id: "tt0299930",
          _createdOn: "2019-09-25T17:40:39.088Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3669",
          title: "Glitter",
          rating: 2.8,
          id: "tt0118589",
          _createdOn: "2019-09-25T17:40:39.088Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3662",
          title: "Alone in the Dark",
          rating: 2.6,
          id: "tt0369226",
          _createdOn: "2019-09-25T17:40:39.087Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3663",
          title: "From Justin to Kelly",
          rating: 2.6,
          id: "tt0339034",
          _createdOn: "2019-09-25T17:40:39.087Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3664",
          title: "Battlefield Earth",
          rating: 2.6,
          id: "tt0185183",
          _createdOn: "2019-09-25T17:40:39.087Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3665",
          title: "Going Overboard",
          rating: 2.7,
          id: "tt0096870",
          _createdOn: "2019-09-25T17:40:39.087Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3666",
          title: "Dragonball Evolution",
          rating: 2.7,
          id: "tt1098327",
          _createdOn: "2019-09-25T17:40:39.087Z"
        },
        {
          _id: "5d8ba697c277a40fef1e365e",
          title: "Pledge This!",
          rating: 2.4,
          id: "tt0417056",
          _createdOn: "2019-09-25T17:40:39.086Z"
        },
        {
          _id: "5d8ba697c277a40fef1e365f",
          title: "Son of the Mask",
          rating: 2.4,
          id: "tt0362165",
          _createdOn: "2019-09-25T17:40:39.086Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3660",
          title: "Epic Movie",
          rating: 2.5,
          id: "tt0799949",
          _createdOn: "2019-09-25T17:40:39.086Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3661",
          title: "Turks in Space",
          rating: 2.5,
          id: "tt0808240",
          _createdOn: "2019-09-25T17:40:39.086Z"
        },
        {
          _id: "5d8ba697c277a40fef1e365a",
          title: "Birdemic: Shock and Terror",
          rating: 2.2,
          id: "tt1316037",
          _createdOn: "2019-09-25T17:40:39.085Z"
        },
        {
          _id: "5d8ba697c277a40fef1e365b",
          title: "The Hottie & the Nottie",
          rating: 2.3,
          id: "tt0804492",
          _createdOn: "2019-09-25T17:40:39.085Z"
        },
        {
          _id: "5d8ba697c277a40fef1e365c",
          title: "Saving Christmas",
          rating: 2.3,
          id: "tt4009460",
          _createdOn: "2019-09-25T17:40:39.085Z"
        },
        {
          _id: "5d8ba697c277a40fef1e365d",
          title: "House of the Dead",
          rating: 2.3,
          id: "tt0317676",
          _createdOn: "2019-09-25T17:40:39.085Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3658",
          title: "Manos: The Hands of Fate",
          rating: 2.2,
          id: "tt0060666",
          _createdOn: "2019-09-25T17:40:39.084Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3659",
          title: "Code Name: K.O.Z.",
          rating: 2.2,
          id: "tt4458206",
          _createdOn: "2019-09-25T17:40:39.084Z"
        },
        {
          _id: "5d8ba697c277a40fef1e3657",
          title: "Superbabies: Baby Geniuses 2",
          rating: 2.1,
          id: "tt0270846",
          _createdOn: "2019-09-25T17:40:39.083Z"
        }
      ]
    }
  }
}
</script>

<style scoped>
ul {
  list-style: none;
  text-align: left;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 20px;
}

.title {
  max-width: 200px;
  font-weight: bold;
}
li {
  display: flex;
  justify-content: space-between;
}
</style>
