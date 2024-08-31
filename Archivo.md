```mermaid
classDiagram
    class Liga Argentina {
        +Rosario Central
        +Boca Juniors
        +Racing Club
        +boolean isAvailable()
    }

    class Brasileirao {
        +Palmeiras
        +Sao Paulo
        +borrowBook(Book book)
        +returnBook(Book book)
    }

    class Liga MX {
        +Chihuahuas de quetzalcoatl
        +Pollitos de Bragarnik
        +addBook(Book book)
        +removeBook(Book book)
    }

    class Resultados {
        +
        +1° Rosario Central
        +2° Francia
        +3° Palmeiras
        +addMember(Member member)
    }

    Library "1" -- "contains" Book
    Library "1" -- "registers" Member
    Library "1" -- "manages" Librarian
