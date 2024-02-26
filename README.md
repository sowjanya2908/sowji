import React from 'react';
 
const YourPage = () => {
  return (
<div>
<h1>Your Next.js Page</h1>
 
      <form>
<label htmlFor="name">Name:</label>
<input type="text" id="name" name="name" />
 
        <br />
 
        <label htmlFor="email">Email:</label>
<input type="email" id="email" name="email" />
 
        <br />
 
        <label htmlFor="phone">Phone:</label>
<input type="tel" id="phone" name="phone" />
</form>
</div>
  );
};
 
export default YourPage;
