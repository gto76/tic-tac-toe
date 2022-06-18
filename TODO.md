

- [x] Add get_label() function that will receive button id and return its label.
- [ ] Prevent button_clicked() function from changing the labels of buttons that already have a piece on them.
- [ ] Add DEBUG variable that can be false or true. If it's false the button_clicked() function should not print the alert message.
- [ ] Add set_label() function that will receive button id and label text and will then update button with it.
- [ ] Add reset() function that will set all labels back to underscore. Code between curly brackets will execute 9 times, each time with id variable having a different value:
	```js
	for (let id of [1, 2, 3, 4, 5, 6, 7, 8, 9]) {
		...
	}
	```
- [ ] Crete is_filled() function that will return true if there are no more free cells and true otherwise.
- [ ] Create get_winner() function that will return 'X', 'O' or none, indicating the winner.