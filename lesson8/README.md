Lesson8:
--------
We learned how to create our custom drag and drop functionality and how to
code some sort of inertia so it is possible not only to pick up an item but also
to throw it with a simple gesture.
We've also covered some techniques and features that were used for final app presented in lesson7.

Topics covered:
- how to use combination of mouseup, mousedown and mousemove events to create drag and drop
- what is requestAnimationFrame and how to create inertia like behavior with it
- custom CSS animations using `@keyframes`
- how to create CSS loader with spinning animation
- what are `preventDefault()` and `stopPropagation()` event's methods
- how event bubbling works
- what is `getBoundingClientRect()`
- how to create custom listeners
- how to create custom logging function based on `console.log()`

Homework:
---------
For our drag and drop example create some sort of container element which
can recognize that the box was placed inside of it. After you've done with
that try to create an alignment system so when you put the box inside the container
it takes a certain place in it. Finally, make container to attract elements nearby
so when you throw a box in, container would drag the box inside by itself.
