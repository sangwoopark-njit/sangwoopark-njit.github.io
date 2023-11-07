---
layout: page
title: News
description: SangWoo Park's news
---

<style>
  .figure-container {
    position: relative;
    overflow: hidden;
    width: 100%; /* Set the desired width for your figure */
    height: 400px; /* Set the desired height for your figure */
	margin-bottom: 20px; /* Add margin to create vertical space */
  }

  .figure img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Crop the image to fit the fixed dimensions */
  }

  .buttons {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
	color: white;
  }

  .button {
    background: none;
    border: none;
    font-size: 24px;
	color: white;
  }
</style>

<div class="figure-container">
  <div class="figure">
    <img src="publpics/njit_campus_01.jpg" alt="njit_campus_01">
  </div>
  <div class="buttons">
    <button class="button prev-button" onclick="changeFigure(-1)">&lt;</button>
    <button class="button next-button" onclick="changeFigure(1)">&gt;</button>
  </div>
</div>


<script>
  let currentFigureIndex = 0; // Initialize the current figure index
  const figures = [
    'njit_campus_01.jpg',
    'njit_campus_02.jpg',
    'njit_campus_03.jpg',
    'njit_campus_04.jpg',
    'njit_campus_05.jpg',
  ]; // Provide the image file names for all your figures

  function changeFigure(step) {
    // Update the current figure index based on the step (1 for next, -1 for previous)
    currentFigureIndex += step;

    // Wrap around if exceeding the figure count
    if (currentFigureIndex < 0) {
      currentFigureIndex = figures.length - 1;
    } else if (currentFigureIndex >= figures.length) {
      currentFigureIndex = 0;
    }

    // Change the displayed figure source
    const figure = document.querySelector('.figure img');
    figure.src = `publpics/${figures[currentFigureIndex]}`;
  }
</script>
* November 2023: Congratulations to Kushagra Verma for receiving the 2023 Fall [URI Seed Grant](https://centers.njit.edu/uri/programs/index.php) (phase 2: $3000) on the topic of "Bioenergy Optimization: Enhancing Anaerobic Digestion for Maximum Biogas Output."

* November 2023: Congratulations to Irma Melo for receiving the 2023 Fall URI Seed Grant (phase 1: $500) on the topic of "Optimizing the Operations of UPS Parcel Sorting System."

* April 2023: Our lab has received the RETDIC Faculty Seed Grant Award from NJIT.

* August 2022: I have joined the [New Jersey Institute of Technology](https://www.njit.edu/) as an Assistant Professor.

* April 2022: I have successfully defended my dissertation and received my Ph.D. from UC Berkeley IEOR.

* July 2020: Our paper [“Homotopy Method for Finding the Global Solution of Post-contingency Optimal Power Flow”](https://ieeexplore.ieee.org/document/9147711)
has won the Best Student Paper Award of 2020 American Control Conference (ACC).

* April 2019: I received the [Marshall Oliver-Rosenberger Fellowship](https://ieor.berkeley.edu/announcing-the-fall-2019-grassi-mor-fellows/) from the Department of IEOR, UC Berkeley.

* March 2019: I was nominated by the Department of IEOR, UC Berkeley to receive the 2018-2019 Outstanding Graduate Student Instructor Award.

* September 2018: I successfully passed the Doctoral Qualifying Examination and advanced to candidacy.

* November 2016: I joined Professor [Javad Lavaei’s group](https://lavaei.ieor.berkeley.edu/Group.html) at [UC Berkeley IEOR](https://ieor.berkeley.edu/) as a PhD student.

* May 2016: I graduated from [Johns Hopkins University](https://www.jhu.edu/) with a B.S. in Environmental Engineering.