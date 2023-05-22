function validateEmail(email) {
  var regex = /^[\\w-\\.]+@([\\w-]+\\.)+[\\w-]{2,4}$/;
  return regex.test(email);
} from verify_email import verify_email
is_valid = verify_email('example@example.com')
var verifalia = require('verifalia');
var client = verifalia.newClient({
  // Your Verifalia credentials
  username: 'YOUR-USERNAME',
  password: 'YOUR-PASSWORD'
});

client.emailValidations.submit([
  'alice@example.com',
  'bob@example.net',
  'carol@example.org'
], function (err, result) {
  // Handle errors (if any)
  if (err) throw err;

  // Display the results
  console.log(result.entries);
});
