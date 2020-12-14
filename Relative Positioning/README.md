# Relative Positioning with Rendering System

### Reminders

* If relative is applied, the rendering system renders blocks as static then decides the relative position.

* If static blocks and relative blocks are together, relative blocks always over static blocks

* Relative blocks doesn't affect to width or height of parent element because the rendering system renders blocks as static first then decides the relative position.


#### Korean
* relative를 적용하면, Rendering system은 static으로써 먼저 위치를 잡고, static으로써 위치를 잡은 후의 결과에 relative  position을 적용

* static과 relative가 섞여있으면, 무조건 relative가 위로 올라옴

* static으로 그려놓고 relative를 움직였기 때문에, 부모의 element의 width나 height에는 영향을 주지 않는다. 즉, static으로 그렸을 당시의 width와 height를 유지