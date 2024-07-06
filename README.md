# Random Quote Generator

This project is a simple web application that fetches and displays random quotes using the Quotable API. It allows users to generate new quotes and share them on Twitter.

## Features

- Display a random quote and its author on the webpage.
- Ability to fetch a new random quote with the click of a button.
- Option to tweet the displayed quote and author.

## Technologies Used

- HTML
- CSS
- JavaScript
- [Quotable API](https://api.quotable.io/)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/CodeWithMariam/random-quote-generator.git
    ```
2. Open `index.html` in your web browser.

## Usage

1. Click the "New Quote" button to generate and display a new random quote.
2. Click the "Tweet" button to share the displayed quote on Twitter.

## Code Explanation

- The application uses the `fetch()` function in JavaScript to asynchronously request data from the Quotable API (`https://api.quotable.io/random`).
- Upon successful retrieval of data, the quote and author are displayed on the webpage.
- Error handling is implemented to manage cases where fetching the quote fails or encounters network issues.

## Future Improvements

- Implement caching or local storage to save and display previously fetched quotes.
- Allow users to customize and style the quote display.
- Enhance accessibility and responsiveness of the user interface.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Related Links

- [Quotable API Documentation](https://api.quotable.io/)
- [How to Fetch Data in JavaScript](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- [Tweeting with Twitter Intent](https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/overview)
