```javascript
import React, { useState } from 'react';
const Fraser = () => {
  const from = 'Glasgow, Scotland';
  const [lives, setLives] = useState('Tokyo, Japan');
  const [likes, setLikes] = useState(['🧀', '🍻', '🐶', '👨‍💻']);
  return (
    <div>
      <h1>Hello 👋 I'm Fraser from {from} and I currently live in {lives}</h1>
      <ul>
      {likes.map((thing) => <li>thing</li>)}
      </ul>
      <button onClick={() => console.log("Hello!")}>Say Hello</button>
    </div>
  );
}
```

