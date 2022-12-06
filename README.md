# Notification Application

## What's inside
* UI/UX Design components from NativeBase
* Redux, Redux Toolkit for state management
* React Navigation for simple navigation also includes custom bottom tab
* Performant, flexible and extensible forms with easy-to-use validation *  using React Hook Form
* Yup to build schema for value parsing and validation
* Includes example screens. On Boarding, Authentication with mobile / otp and a Form screen.
* Includes Vector Icons. Perfect for buttons, logos and nav/tab bars. Easy to extend, style and integrate into your project.

## How to customize theme
* Just navigate to PROJECT-DIRECTORY/src/theme/customeTheme.js and make the desired changes[.example file]()
* You can change colors, fonts, initial color mode(dark/light) etc.
* [see more theme options]()

## How to add fonts
* Download font family from here
* Navigate to PROJECT-DIRECTORY/src/assets/fonts and unzip all fonts here
* Then navigate to PROJECT-DIRECTORY/src/theme/customeTheme.js and add/change fonts and fontConfig.
 fonts: {
    heading: 'Inter',
    body: 'Inter',
    mono: 'Inter',
  },
  fontConfig: {
    Inter: {
      100: {
        normal: 'Inter-Thin',
      },
      200: {
        normal: 'Inter-ExtraLight',
      },
      300: {
        normal: 'Inter-Light',
      },
      400: {
        normal: 'Inter-Regular',
      },
      500: {
        normal: 'Inter-Medium',
      },
      600: {
        normal: 'Inter-SemiBold',
      },
      700: {
        normal: 'Inter-Bold',
      },
      800: {
        normal: 'Inter-ExtraBold',
      },
      900: {
        normal: 'Inter-Black',
      },
    },
 }
Then run npx react-native link or yarn react-native link
Refer here for more