```javascript
{
  personal: {
    firstName: "Berk Ege",
    lastName: undefined,
    gender: EGender.MALE,
    birthPlace: "Turkey",
    age: 24
  },
  interests: {
    book: [
      Book.tag.fantasy,
      Book.tag.supernatural,
      Book.type.manga,
      Book.type.novel
    ],
    movie: [
      Movie.serie.get("Harry Potter"),
      Movie.serie.get("Pirates of Caribbean")
    ],
    computer: [
      Computer.activity.game,
      Computer.activity.code
  },
  job: {
    status: EJobStatus.why_not,
    price: unknown,
    details: "I wanna learn something?!"
  }
}
```
