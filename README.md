# Homework for React Native Candidate

Build a car insurance portion of an app. It should consist of a sequence of screens.

## Design

https://www.figma.com/file/tZbqXurwc5iFu5ev3ni38Z/React-Native-homework?node-id=0%3A1

## Requirements

- [ ] Fetch insurance offers by `POST`ing to https://run.mocky.io/v3/8258eada-7c19-41f9-82d6-57a01350073b
    ```js
    // request payload example:
    { 
      regPlate: 'FOO123',
      personalCode: '39001010001',
      startDate: '2022-04-20',
      durationMonths: 6
    }
    ```
- [ ] Implement all provided screens. Just the general behavior is enough, don’t linger over the details
- [ ] Write at least one test
- [ ] Share code as a private repo on GitHub. Add [@Cinamonas](https://github.com/Cinamonas) as a collaborator for review
- [ ] Include instructions on how to test the app in `README`. If TestFlight is used, send invites to _alex at carvertical dot com_ and _artur at carvertical dot com_

## Notes

- You can bootstrap the app however you want
- If you’re unsure on how some interaction should work, just use your best judgement
