# Telephone System

This project simulates a telephone system using Java classes for a desk phone and a mobile phone, along with an interface for telephone functionality.

## Project Structure

- **Main.java:** Contains the main method to demonstrate the functionality of the telephone system.
- **MobilePhone.java:** Implements the `ITelephone` interface for a mobile phone.
- **DeskPhone.java:** Implements the `ITelephone` interface for a desk phone.
- **ITelephone.java:** Defines the interface for telephone functionality.

## Usage

The `Main` class demonstrates how to use the telephone system by creating instances of mobile and desk phones, powering them on, making calls, and answering calls.

## Classes

### MobilePhone

- **Fields:**
    - `myNumber`: The phone number of the mobile phone.
    - `isRinging`: Indicates if the phone is currently ringing.
    - `isOn`: Indicates if the phone is powered on.

- **Methods:**
    - `powerOn()`: Powers on the mobile phone.
    - `dial(int phoneNumber)`: Dials a phone number.
    - `answer()`: Answers an incoming call.
    - `callPhone(int phoneNumber)`: Initiates a call to a phone number.
    - `isRinging()`: Checks if the phone is currently ringing.

### DeskPhone

- **Fields:**
    - `myNumber`: The phone number of the desk phone.
    - `isRinging`: Indicates if the phone is currently ringing.

- **Methods:**
    - `powerOn()`: Does not apply as desk phones do not have a power button.
    - `dial(int phoneNumber)`: Dials a phone number.
    - `answer()`: Answers an incoming call.
    - `callPhone(int phoneNumber)`: Initiates a call to a phone number.
    - `isRinging()`: Checks if the phone is currently ringing.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
