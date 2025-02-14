# Queue Simulation with Vue.js

This project demonstrates a **queue simulation** using **Vue.js** to visualize enqueue, dequeue, peek, and other queue operations. The queue items are represented as dice, which are added or removed from the queue. The user can interact with the queue using buttons that perform various operations.

## Features

- **Enqueue Operation**: Add a new item (die) to the queue.
- **Dequeue Operation**: Remove the front item from the queue.
- **Peek Operation**: View the first item in the queue without removing it.
- **Size**: Display the current number of items in the queue.
- **IsEmpty**: Check if the queue is empty.
- **Animations**: Smooth transitions for enqueue and dequeue actions, with visual feedback on each item.

## Technologies Used

- **Vue.js**: A progressive JavaScript framework used to build the interactive UI.
- **HTML/CSS**: To structure and style the page.
- **JavaScript**: For managing the logic behind the queue operations.

## Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AyushSinghRawat-hub/vue-queue-simulation.git
## How to Use

Once the page is loaded in the browser, you will see the following interactive features:

1. **Enqueue**: Click the `enqueue()` button to add a new die to the queue. The die will be added to the right side (end) of the queue.
2. **Dequeue**: Click the `dequeue()` button to remove the die at the front of the queue. The first item in the queue will be removed.
3. **Peek**: Click the `peek()` button to check the first item in the queue without removing it.
4. **Size**: Click the `size()` button to display the current number of items in the queue.
5. **Is Empty**: Click the `isEmpty()` button to check if the queue is empty. It will return `True` if the queue is empty, otherwise `False`.

### Visual Features

- **Dice**: Each item in the queue is represented as a die with a number displayed inside. The color of the die changes based on its value.
- **Hover and Click Effects**: When an item is active (highlighted), it scales up slightly and changes color to give a visual cue to the user.

### Key Concepts

- **Queue**: A queue is a linear data structure that follows the **FIFO** (First In, First Out) principle. Items are added to the rear and removed from the front.
- **Vue.js**: Vue.js is used for creating a reactive user interface where the UI automatically updates when the data changes. Each operation (enqueue, dequeue, etc.) modifies the queue, and Vue.js ensures the UI updates accordingly.

## Contribution

If you'd like to contribute to this project, feel free to fork it, make your changes, and submit a pull request. Contributions are always welcome!

- **Bug Fixes**: If you find a bug, please submit an issue or create a pull request with the fix.
- **Enhancements**: Suggest features or improvements by opening an issue or contributing directly.
