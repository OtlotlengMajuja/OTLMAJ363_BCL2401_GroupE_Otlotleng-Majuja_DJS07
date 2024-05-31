# DJS07 Project: Build a Meme Generator

## Introduction

To complete this project, I followed a Scrimba lesson to build a React application that functions as a meme generator.

## Project Overview

The meme generator I developed was required to generate a new meme image when the button was clicked, and allow the user to input text that would appear on the image.

## Elements Included

**Event handling**, using `handleChange` to update the top and bottom text based on user input.
**API fetching**, having `useEffect` fetch the meme data from its API.
**State management**, using the `allMemes` array to store the memes data fetched from the API.

## Reflections

### Areas of Mastery

**React Hooks:** using the `useState` for state management, and `useEffect` for the side effects helped provide insight on what their purpose is and how I could use them in future projects.
**API Integration:** reintroducing the asyncronous fetching and handling of data from an external API in this project, strengthened my practical understanding of API integration.
**Conditional Rendering:** updating the displayed meme image dynamically and text based on the state.

### Challenges Faced

Some of the challenges I faced doing this project were correctly implementing the random image selector to ensure that a new image is displayed each time, as well as properly updating the user inputs. I inserted labels assuming that because it made the application more accessible it would'nt affect the functionality but it did and I attempted to work around it but ultimately removed it so that the application could work as required.

### Overall Learning Experience

With state management particularly I found it a little dense but the further along I went with the lessons and practice videos, the less murky the concept became. Overall even though I might need more practice, the project enhanced my skills in building responsive and data-driven web applivcations using React
