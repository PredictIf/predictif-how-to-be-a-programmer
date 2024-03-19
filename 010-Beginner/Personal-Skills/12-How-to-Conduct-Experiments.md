# How to Conduct Experiments

 *...the harm was done: the topic became known as “computer science” - which, actually, is like referring to surgery as “knife science” - and it was firmly implanted in people's minds that computing science is about machines and their peripheral equipment.*

Programming ought not to be an experimental science, but most working programmers do not have the luxury of engaging in what Dijkstra means by computing science. We must work in the realm of experimentation, just as some, physicists do. The kinds of experiments you will have to perform include:

- Testing systems with small examples to verify that they conform to the documentation or to understand their response when there is no documentation,
- Testing small code changes to see if they actually fix a bug,
- Measuring the performance of a system under two different conditions due to imperfect knowledge of their performance characteristics,
- Checking the integrity of data, and
- Collecting statistics that may hint at the solution to difficult or hard-to-repeat bugs.

I don't think I can explain the design of experiments here; you will have to study and practice. However, I can offer two bits of advice.

First, try to be very clear about your hypothesis, or the assertion that you are trying to test. It also helps to write the hypothesis down, especially if you find yourself confused or are working with others.

You will often find yourself having to design a series of experiments, each of which is based on the knowledge gained from the last experiment. Therefore, you should design your experiments to provide the most information possible. Unfortunately, this is in tension with keeping each experiment simple - you will have to develop this judgement through experience.
