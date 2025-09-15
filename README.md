# FS_RajPrabhe
The Student Commute Optimizer is a full-stack web app that helps students save money and time by carpooling with nearby students.
We built Student Commute Optimizer to solve this:

Students enter their home and college location.

The system finds other students going the same way.

Everyone gets a unique anonymous username — so personal info stays private.

Students can chat directly in the app to plan carpooling.

It shows matches on a map for easy visualization.

How We Thought About It / Process

Idea came from real-life problems: students wasting money and time commuting individually.

Decided what was needed: route matching, anonymous identities, chat system, map interface.

System Design:

Frontend: React + Tailwind + Leaflet for map.

Backend: Node.js + Express for API, Socket.IO for chat.

Database: MongoDB to store users, routes, and chats.
We built Student Commute Optimizer to solve this:

    Students enter their home and college location.

    The system finds other students going the same way.

    Everyone gets a unique anonymous username — so personal info stays private.

    Students can chat directly in the app to plan carpooling.

    It shows matches on a map for easy visualization.

How We Thought About It / Process

    Idea came from real-life problems: students wasting money and time commuting individually.

    Decided what was needed: route matching, anonymous identities, chat system, map interface.

    System Design:

        Frontend: React + Tailwind + Leaflet for map.

        Backend: Node.js + Express for API, Socket.IO for chat.

        Database: MongoDB to store users, routes, and chats.

    Implementation:

        APIs for registration, profile update, and fetching matches.

        Chat system works in real-time.

        Haversine formula calculates distance between student routes.

    Testing:

        Multiple users in different browsers → check matches and chat.

        Ensure usernames are unique and anonymous.

    Result:

        Students can find travel partners quickly, coordinate via chat, and save money, time, and fuel.

Implementation:

APIs for registration, profile update, and fetching matches.

Chat system works in real-time.

Haversine formula calculates distance between student routes.

Testing:

Multiple users in different browsers → check matches and chat.

Ensure usernames are unique and anonymous.

Result:

Students can find travel partners quickly, coordinate via chat, and save money, time, and fuel.
