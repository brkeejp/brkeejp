```javascript
{
  personal: {
    firstName: "Berk Ege",
    lastName: undefined,
    gender: Gender.MALE,
    birthPlace: "Turkey",
    age: 24
  },
  interests: {
    book: [
      Book.novel.tag.fantasy,
      Book.novel.tag.supernatural,
      Book.manga
    ],
    movie: [
      Movie.serie.get("Harry Potter"),
      Movie.serie.get("Pirates of Caribbean")
    ],
    computer: [
      Computer.game,
      Computer.game.get("Osu!"),
      //Computer.development.code,
      //Computer.development.game,
      //Computer.development.program,
      // ・・・ ⋋( 'Θ')⋌
      Computer.development
  },
  job: {
    status: "looking",
    price: false,
    details: "I wanna learn something?!"
  }
}
```
