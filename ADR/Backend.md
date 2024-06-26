# Subject: Backend language
Status: Proposed
Context:
The app requires integration with various payment gateways to facilitate secure and seamless transactions. The app should integrate with the restaurants' inventory management systems.
Decision:
We propose to use Node.js as our backend language. Node.js is a popular open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside a web browser. It is well-suited for building scalable network applications and can handle many simultaneous connections with high throughput, which equates to high scalability.
Consequences:
By choosing Node.js, we can use a single language across the application, which can improve efficiency and speed up development. However, Node.js might not be the best choice for CPU-intensive tasks.
