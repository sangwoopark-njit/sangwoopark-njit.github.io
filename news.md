---
layout: page
title: News
description: SangWoo Park's news
---

<div class="figure-pane">
  <div class="figure-container">
    <img class="figure" src="publpics/njit_campus_01.jpg" alt="njit_campus_01">
    <img class="figure" src="publpics/njit_campus_02.jpg" alt="njit_campus_02">
    <img class="figure" src="publpics/njit_campus_03.jpg" alt="njit_campus_03">
	<img class="figure" src="publpics/njit_campus_04.jpg" alt="njit_campus_04">
	<img class="figure" src="publpics/njit_campus_05.jpg" alt="njit_campus_05">
	<img class="figure" src="publpics/njit_campus_06.jpg" alt="njit_campus_06">
    <!-- Add more images as needed -->
  </div>
  <button class="prev-button" onclick="changeFigure(-1)">&lt;</button>
  <button class="next-button" onclick="changeFigure(1)">&gt;</button>
</div>


<style>
  .figure-container {
    display: flex;
    overflow: hidden;
    position: relative;
  }

  .figure {
    flex: 1;
	margin-bottom: 20px; /* Adjust the margin as needed */
    transition: transform 0.3s ease;
  }
</style>


<script>
  let currentFigureIndex = 0; // Initialize the current figure index

  function changeFigure(step) {
    // Update the current figure index based on the step (1 for next, -1 for previous)
    currentFigureIndex += step;

    // Get all figure elements
    const figures = document.querySelectorAll('.figure');

    // Wrap around if exceeding the figure count
    if (currentFigureIndex < 0) {
      currentFigureIndex = figures.length - 1;
    } else if (currentFigureIndex >= figures.length) {
      currentFigureIndex = 0;
    }

    // Calculate the transform value to swipe to the current figure
    const transformValue = `translateX(-${currentFigureIndex * 100}%)`;

    // Apply the transform to the figure container for the swiping effect
    const figureContainer = document.querySelector('.figure-container');
    figureContainer.style.transform = transformValue;
  }

  // Initially, show the first figure
  changeFigure(0);
</script>

* August 2022: I have joined the [New Jersey Institute of Technology](https://www.njit.edu/) as an Assistant Professor.

* April 2022: I have successfully defended my dissertation and received my Ph.D. from UC Berkeley IEOR.

* July 2020: Our paper [“Homotopy Method for Finding the Global Solution of Post-contingency Optimal Power Flow”](https://ieeexplore.ieee.org/document/9147711)
has won the Best Student Paper Award of 2020 American Control Conference (ACC).

* April 2019: I received the [Marshall Oliver-Rosenberger Fellowship](https://ieor.berkeley.edu/announcing-the-fall-2019-grassi-mor-fellows/) from the Department of IEOR, UC Berkeley.

* March 2019: I was nominated by the Department of IEOR, UC Berkeley to receive the 2018-2019 Outstanding Graduate Student Instructor Award.

* September 2018: I successfully passed the Doctoral Qualifying Examination and advanced to candidacy.

* November 2016: I joined Professor [Javad Lavaei’s group](https://lavaei.ieor.berkeley.edu/Group.html) at [UC Berkeley IEOR](https://ieor.berkeley.edu/) as a PhD student.

* May 2016: I graduated from [Johns Hopkins University](https://www.jhu.edu/) with a B.S. in Environmental Engineering.