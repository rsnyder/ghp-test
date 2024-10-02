[![](https://v3.juncture-digital.org/images/wb.svg)](https://v3.juncture-digital.org/wb)

# GHP Test

## Level 2 heading

Lorem ipsum odor amet, consectetuer adipiscing elit. Primis ipsum bibendum eu tellus litora nullam fermentum eleifend morbi. Aliquet maximus risus praesent mus convallis risus dignissim nisl. Congue dis congue sodales mus blandit enim dui vitae. Urna consequat dictumst tincidunt sollicitudin semper tempus vestibulum. Facilisi nec consequat platea dui cubilia montes eleifend ridiculus massa. Ut condimentum a laoreet suspendisse; diam semper penatibus. Praesent ipsum dis parturient auctor cras venenatis per. Penatibus fringilla libero finibus class conubia.

## Level 3 heading

Viverra placerat finibus nunc; id eleifend tempus ridiculus montes. Fusce cubilia ligula nullam; cras ligula justo duis cursus? Inceptos ligula arcu egestas vivamus faucibus. Taciti ante augue urna phasellus; ultricies consequat ac risus. Erat habitant nisi suscipit ut massa pharetra ligula. Urna fusce dignissim semper orci luctus semper consectetur habitasse! Eget parturient magnis nisl malesuada potenti euismod venenatis.

Tellus nullam lobortis aliquam gravida facilisi cras. Ex vulputate vulputate semper sociosqu lectus. Ac consequat interdum ac lobortis laoreet ut aenean. Congue erat habitant ante nascetur nostra senectus. Laoreet sem luctus, in nec hendrerit per dapibus curae. Tincidunt aliquam ex primis nullam potenti convallis. Primis nostra lectus efficitur curae; platea nec purus.

## Level 3 heading

Neque convallis tempor suscipit arcu parturient facilisis gravida eros. Sodales consectetur lorem consequat velit primis mus fringilla. Nec sem tellus consectetur vestibulum augue ad curabitur. Lacinia porta primis tincidunt habitasse netus. Nostra sed nisi tellus dictumst proin turpis enim. Mi montes montes velit sapien lacus ornare penatibus faucibus. Orci nostra blandit ipsum iaculis consectetur sem platea pellentesque.

Maximus habitant dis, integer semper vivamus platea. Auctor curabitur tortor est integer magnis ultricies suscipit libero. Bibendum lectus facilisi, fusce lobortis scelerisque porta eget. Condimentum bibendum cubilia leo fames natoque lobortis volutpat fermentum. Purus duis platea morbi blandit netus ullamcorper semper sem. Ligula enim lectus felis proin lectus vulputate gravida dui.

## Table

| Value | Description |
| -------- | ---------------------------------------- |
| *contain*  (_default_)  | The image keeps its aspect ratio, but is resized to fit within the available space |
| *cover*  | The image keeps its aspect ratio and fills the the available space. The image will be clipped to fit  |

## Table in list

- **caption** (_string_) :  A caption for the carousel viewer.  Image-specific captions are set in the image list.
- **aspect-ratio**: (_string_) :  Use the `aspect-ratio` attribute to customize the size of the carousel’s viewport from the default value of **16/9**.  Other values include **3/2** and **1/1**.
- **autoplay** (_boolean_) :  The carousel will automatically advance when the `autoplay` attribute is used. To change how long a slide is shown before advancing, set autoplay-interval to the desired number of milliseconds. For best results, use the loop attribute when autoplay is enabled. Note that autoplay will pause while the user interacts with the carousel.
- **fit** (_string_) :  The `fit` attribute is used to define how an image should be resized to fit its container.
| Value | Description |
| -------- | ---------------------------------------- |
| *contain*  (_default_)  | The image keeps its aspect ratio, but is resized to fit within the available space |
| *cover*  | The image keeps its aspect ratio and fills the the available space. The image will be clipped to fit  |
- **gallery** (_boolean_) :  The `gallery` attribute syncs the active slide with a set of thumbnails, creating a gallery-style carousel.
- **loop** (_boolean_) :  By default, the carousel will not advanced beyond the first and last slides. You can change this behavior and force the carousel to "wrap" with the `loop` attribute.
- **navigation** (_boolean_) :  Use the `navigation` attribute to show previous and next buttons.
- **orientation** (_string_) :  Setting the `orientation` attribute to **vertical** will render the carousel in a vertical layout. If the content of your slides vary in height, you will need to set amn explicit height or max-height on the carousel using CSS.
- **pagination** (_boolean_) :  Use the `pagination` attribute to show the total number of slides and the current slide as a set of interactive dots.
- **scroll-hint** (_boolean_) :  Use the `scroll-hint` attribute to add inline padding in horizontal carousels and block padding in vertical carousels. This will make the closest slides slightly visible, hinting that there are more items in the carousel.
- **slides-per-page** (_number_) :  The `slides-per-page` attribute makes it possible to display multiple slides at a time. You can also use the `slides-per-move` attribute to advance more than once slide at a time, if desired.
- **slides-per-move** (_number_) :  Generally used in conjunction with the `slides-per-page` attribute to advance more than one slide at a time.
