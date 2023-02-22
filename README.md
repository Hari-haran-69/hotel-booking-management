# hotel-booking-management
<!DOCTYPE html>
<html>
  <head>
    <title>Hotel Management System</title>
  </head>
  <body>
    <h1>Welcome to our Hotel</h1>
    
    <h2>Book a Room</h2>
    <form action="/book-room" method="POST">
      <label for="check-in-date">Check-in date:</label>
      <input type="date" id="check-in-date" name="check-in-date">
      <br>
      <label for="check-out-date">Check-out date:</label>
      <input type="date" id="check-out-date" name="check-out-date">
      <br>
      <label for="room-type">Room type:</label>
      <select id="room-type" name="room-type">
        <option value="single">Single Room</option>
        <option value="double">Double Room</option>
        <option value="suite">Suite</option>
      </select>
      <br>
      <button type="submit">Book now</button>
    </form>

    <h2>Available Rooms</h2>
    <table>
      <thead>
        <tr>
          <th>Room Number</th>
          <th>Type</th>
          <th>Price per Night</th>
          <th>Book Now</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>101</td>
          <td>Single Room</td>
          <td>1500</td>
          <td><button type="button">Book</button></td>
        </tr>
        <tr>
          <td>102</td>
          <td>Double Room</td>
          <td>3000</td>
          <td><button type="button">Book</button></td>
        </tr>
        <tr>
          <td>103</td>
          <td>Suite</td>
          <td>4500</td>
          <td><button type="button">Book</button></td>
        </tr>
      </tbody>
    </table>

    <h2>Customer Information</h2>
    <form action="/customer-info" method="POST">
      <label for="first-name">First Name:</label>
      <input type="text" id="first-name" name="first-name">
      <br>
      <label for="last-name">Last Name:</label>
      <input type="text" id="last-name" name="last-name">
      <br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email">
      <br>
      <button type="submit">Submit</button>
    </form>
  </body>
</html>
