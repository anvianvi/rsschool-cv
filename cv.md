# **[rsschool-cv](https://anvianvi.github.io/rsschool-cv/cv)**

# **Pavel Viarbitski**

## **Contacts**

- **Location:** Krakow
- **Phone:** 694668162
- **Email:** verbipo@gmail.com
- **GitHub:** [anvianvi](https://github.com/anvianvi)
- **Telegram** @donajadon

[url](https://www.codewars.com/users/anvianvi/badges/micro?theme=light)

## **About Me**

Hello, my name is Pavel and I am a front-end developer.
I study on my own throughout the year.
I completed several diverse projects in Vanilla JS, a couple of projects with React.
I’m getting to know Angular in more depth.
I'm currently looking for my first job.

## **Skills**

- JavaScript, TypeScript
- Angular, React
- RxJs, NgRX
- Jest
- Graphql
- CSS/SCSS/SASS
- HTML
- GIt, Figma
- Vite, Webpack

## **Code Example**

- **codewadrs** [anvianvi](https://www.codewars.com/users/anvianvi)
- **my portfolio** [anvianvi](https://anvianvi.github.io/portfolio/)

```
enum BorderColors {
  Red = "#EB5757",
  Yellow = "#F2C94C",
  Green = "#27AE60",
  Blue = "#2F80ED",
}

@Directive({
  selector: "[appPublicationDate]",
})
export class PublicationDateDirective {
  @Input() set appPublicationDate(date: string) {
    const currentDate = new Date();
    const publicationDate = new Date(date);
    const differenceInDays = Math.floor(
      (currentDate.getTime() - publicationDate.getTime()) / (1000 * 3600 * 24)
    );

    let borderColor = "";

    if (differenceInDays > 180) {
      borderColor = BorderColors.Red;
    } else if (differenceInDays >= 30 && differenceInDays <= 180) {
      borderColor = BorderColors.Yellow;
    } else if (differenceInDays >= 7 && differenceInDays < 30) {
      borderColor = BorderColors.Green;
    } else {
      borderColor = BorderColors.Blue;
    }

    this.renderer.setStyle(
      this.el.nativeElement,
      "border-bottom",
      `5px solid ${borderColor}`
    );
  }

  constructor(
    private el: ElementRef,
    private renderer: Renderer2
  ) {}
}

```

## **Experience**

#### Front-end Developer

RsSchool Apprenticeship
Mar 2012 – Current

#### Office operation and supply specialist

Wargaming Minsk
Mar 2014 – Mar 2022

## **Education**

- **University:** Institute of Entrepreneurial Activity 2009 – 2013
  Legal support of entrepreneurial activity in small and medium-sized enterprises, manager-economist

- **Courses**
  Over the past year, I have completed a large number of online courses on the following platforms - RsSchool, LinkedIn Learning, EdX, Coursera.

## Languages

English - [B2-C1](https://www.efset.org/cert/XMsGN4)
Polish - A1-A2
Belarusian, Russian - native
