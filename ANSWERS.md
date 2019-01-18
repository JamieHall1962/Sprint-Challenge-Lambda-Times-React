What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

Props types are a way of checking what type of data a React component requires in order to render properly. In the compose/debug phase I try to create/update (on paper) a list of what props are being passed down to what components. PropType helps me make sure that I've got it right.




 Describe a life-cycle event in React?

 When a component is used it goes through a cycle similar to Birth (Mounting) Life (Rendering and Updating) and then Death (Unmounting). Each phase comes with its own methods that we can use to control the flow of our application.




 Explain the details of a Higher Order Component?

 Stole these two sentences from two different paragraphs of the React documentation, because I can't think of a better way to say it. Components are the primary unit of code reuse in React. Whereas a component transforms props into UI, a higher-order component transforms a component into another component.




 What are three different ways to style components in React? Explain some of the benefits of each.

 1) Plain old CSS. I would include pre-processors such as LESS or SASS here too. And even inline styling would, I believe, fit in this category. Tedious and painstaking, I see no benefit whatsoever to this other than it is a necessary evil to style an app so it isn't just one big pile of text and images all piled on top of each other and rendered every which way by the particular browser the user is using.

 2) A library such as Reactstrap. I like Reactstrap because it has a lot of the CSS stuff that gets used regularly already built in "under the hood". When I used it for my Instaclone project (before ripping it all back out again on Day 4) I liked how it handled forms and buttons with no effort on my part. Libraries abstract away a lot of the tediousness of CSS. Disadvantages include the limited ability to customize a particular style. If everybody used Reactstrap for example, most web sites would have a very similar look and feel.

 3) Styled Components. Still a lot of CSS here. A lot of the tediousness is still involved. But instead of swapping between files, everything is in one file, so fixing errors is much easier. I also like that I don't have to be too creative when coming up with names. I can use broad terms such as <Container> and <Wrapper> over and over again. At least in my mind, this gives me more consistency and a bit easier way to think of the styling while composing the code. No disadvantages that I can see other than those associated with styling in the first place.