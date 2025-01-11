# Intermittent Blank Screen with FlatList in React Native

This repository demonstrates a bug where a FlatList in React Native intermittently renders a blank screen even after successfully fetching and processing data. The issue is not consistent and appears randomly. 

## Bug Description
A component fetches movie data from a JSON endpoint. The data is successfully fetched and logged to the console. However, the FlatList component sometimes fails to render the data, displaying a blank screen instead.

## How to Reproduce
1. Clone the repository.
2. Run the app on a simulator or physical device.
3. Observe that the FlatList will sometimes show the movie data, and other times it will render a blank screen.

## Solution
The solution involves using the `getItemLayout` prop in the FlatList component for improved performance, handling asynchronous operations and potential data inconsistencies.

## Technologies Used
* React Native
* JavaScript