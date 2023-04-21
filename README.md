# MERNSTACKconst greet=(name)=>{
    console.log(`hello,${name}`);
}
greet('bahubali');
greet('kattappa');
global.setTimeout(()=>{
    console.log('in the timeout');
},5000);
const int=setInterval(()=>{
    console.log('in the every interval');
},2000);
