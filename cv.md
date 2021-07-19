# __Kateryna Vinskovska__

### CONTACT INFO
- _Location:_ Kyiv, Ukraine
- _Phone:_ +38 (093)-285 - 19 -48
- _E-mail:_ kostiukkaterina@gmail.com

---

### WORK EXPERIENCE
##### FEB 2021 - JUNE 2021
_Sales Manager, "ItUa", Kyiv_
- Search of clients, processing of incoming applications.
- Management and support of existing clients.
- Consulting clients, presentation and selection of the optimal solution for business.
- Negotiating directly with business owners.
- Execution of contracts and reporting in CRM.

##### JUNE 2017 - SEPT 2020
_Sales Manager, OOO "VP Roganskiy myasokombinat", Kyiv_
- Sale of goods to supermarkets (Auchan, Velyka Kyshenya, Novus)
- Signing agreements with clients
- Control of production of goods in accordance with the requirements of each customer
- Conducting negotiations with the heads of areas
- Maintaining communications with outlets (managers, sellers and end buyers)
- Analysis of sales market;
- Accounting control

---

### EDUCATION
_Kyiv National University of Trade and Economics (Kyiv, 2013 - 2018)_
- Department of Accounting and taxation
- Faculty of Accounting, Auditing and Information Systems
- Master's degree of Accounting and taxation

---

### SKILLS
Microsoft Office, 1C, HTML, CSS ( Sass) , JavaScript, Gulp, Git, Bootstrap, Photoshop, Бітрікс24, AmoCRM.

---

### CODE

```
    // Timer
    const deadline = '2021-07-20';
    function getTimeRemaining(endtime) {
        const t = Date.parse(deadline) - Date.parse(new Date()),
              days = Math.floor(t/ (1000*60*60*24)),
              hours = Math.floor(t / (1000*60*60) % 24),
              minutes = Math.floor(t / (1000*60) % 60),
              seconds = Math.floor(t / 1000 % 60);
        return {
            'total': t,
            'days': days,
            'hours': hours,
            'minutes': minutes,
            'seconds': seconds
        };
    }
    function getZero(num) {
        if (num >=0 && num < 10) {
           return  `0${num}`;
        } else {
            return num;
        }
    }
    function setClock(selector, endtime) {
        const timer = document.querySelector(selector),
              days = document.querySelector('#days'),
              hours = document.querySelector('#hours'),
              minutes = document.querySelector('#minutes'),
              seconds = document.querySelector('#seconds'),
              timeInterval = setInterval(updateClock,1000);
        updateClock();
        function updateClock() {
            const t = getTimeRemaining(endtime);
            days.innerHTML = getZero(t.days);
            hours.innerHTML = getZero(t.hours);
            minutes.innerHTML = getZero(t.minutes);
            seconds.innerHTML = getZero(t.seconds);
            if (t.total <= 0) {
                clearInterval(timeInterval);
            }
        }
    }
    setClock('.timer', deadline);
```

---

### LANGUAGES
- _Ukrainian:_ native language
- _Russian:_ fluent
- _English:_ B1 (certify of Cambridge Assessment English)

---

### SOFT SKILLS
Ambitious, diligent, initiative, punctual, stress-resistant, sociable.
