# html5-demo

I created a demo form in html with some validations using bootstrap.

Fields in this form are:
1. First name & Last name - First name field is autofocus and both fields are required
2. Email address - type="email", autocomplete="off" and required
3. Mobile number - pattern="^[7|8|9][0-9]{9}$", maxlength="10", onkeypress="return isNumberKey(event)"
4. Address - required
5. Gender - radio button
6. Date of birth - type="text", onfocus="(this.type='date')", onblur="if(this.value==''){this.type='text'}" and required
7. Select city - dropdown and required
8. Select subject - checkbox
9. Password - type="password", pattern="^(?=.*\d)(?=.*[a-z])(?=.*[A-Z]).{6,20}$" (password must between 6 to 20 characters which contain at least one numeric digit, one uppercase and one lowercase letter )
10. Submit button
