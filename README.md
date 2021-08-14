1. BIND
const output1=function(lang1,lang2)
{
    console.log('My name is '+this.name+' and i know '+lang1+' and '+lang2)
}
 const myname1={
    name:'nandha kumar'
}
 const languages1=['javascript','python']
 bindfun=output1.bind(myname1,languages1[0],languages1[1]);
bindfun()

2.CALL
const output2=function(lang1,lang2,lang3){
    console.log('My name is '+this.name+' and i know '+lang1+','+lang2+','+lang3)
}
const myname2={
    name:'nandha kumar'
}
const languages2=['javascript','python','c++']
output2.call(myname2,languages2[0],languages2[1],languages2[2]);

3.APPLY
const output3=function(lang1,lang2,lang3){
    console.log('My name is '+this.name+' and i know '+lang1+','+lang2+','+lang3)
}
const myname3={
    name:'nandha kumar'
}
const languages3=['javascript','python','c++']
output3.apply(myname3,languages3);
