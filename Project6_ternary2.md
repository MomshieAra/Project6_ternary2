# Project6_ternary2

const welcome = user => {
    const name = user && user.name? user.name: " New User" ;
    return 'Welcome, ${name}';
    }

    console.log (welcome({name:'Ara'}));//Welcome,Ara
    console.log(welcome({}));//Welcome, New User
    console.log(welcome());//Welcome, New user
    console.log(welcome(null));//Welcome, New User