2/14/2024

Henlu ông :) vào ngày va lung tung hôm nay, tui tặng ông một chiếc video dài 2 giây :) và được tạo nên bởi miếng code cũng khá khó nhằn nhưng với sự giúp đỡ của Stack Overflow và ChatGPT thì tui cũng đã xong nó. Ông hãy chạy tất cả các code blocks (3 cái, lần lượt) ở trong `main.ipynb` file nhé. Code block cuối sẽ hơi lâu một chút (30-40 phút haha) thì ông cứ bấm đợi nó chạy ra cái thanh progress bar rồi để máy đấy làm cái khác nhá! Nhớ ông

Code info như sau:

- Libraries: Manim for animation, numpy for mathematical operations, math for basic math functions, and tqdm for progress update bars.
- Parameters: random seed, cloud density, color scheme, and coordinate ranges.
- *get_z* function: calculates the vertical position (z-coordinate) of points on the shape given their horizontal coordinates (x and y).
- *get_cloud* function: It generates points within specified horizontal ranges (x and y) and computes their corresponding vertical positions (z) using the *get_z* function. Randomness as noisy dots.
- Heart Class: a Manim scene class, 3d, animation-like. Includes: *construct* method: This method outlines the animation sequence, loops through different parameters to create variations of the shape. For each parameters, generates a cloud ưith the *get_cloud* function. Then creates dots for each point in the cloud, adds them to the scene, waits QUICKLY, and QUICKLY clears the scene for the next iteration.
- Rendering `%%manim -qm` or quick rendering quality.
