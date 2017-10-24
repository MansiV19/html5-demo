# HTML5 - Demo

HTML5 form using bootstrap with validation

- First name & Last name - `required`
- Email address - `type="email", autocomplete="off", required`
- Mobile number - `pattern="^[7|8|9][0-9]{9}$", maxlength="10", onkeypress="return isNumberKey(event)"`
- Address - `required`
- Gender - `radio`
- Date of birth - `type="text", onfocus="(this.type='date')", onblur="if(this.value==''){this.type='text'}", required`
- Select city - `required`
- Select subject - `checkbox`
- Password - `type="password", pattern="^(?=.*\d)(?=.*[a-z])(?=.*[A-Z]).{6,20}$"` ( password must between 6 to 20 characters which contain at least one numeric digit, one uppercase and one lowercase letter )
- Submit button


# New Features!

- Added Editable Caption to image
- Use HTML5 `<figure>` and `<figurecaption>`
