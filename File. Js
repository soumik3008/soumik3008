
let inputs = document.getElementById("inp");
let text = document.querySelector(".text");

function Add(){
    if(inputs.value == ""){
        alert("Please Enter Task")
    }else{
        let newEle = document.createElement("ul");
        newEle.innerHTML=`${inputs.value} <button id="btn"  > delete button</button> `;
        text.appendChild(newEle);
        inputs.value="";
       newEle.querySelector('#btn').addEventListener("click",remove);
        function remove(){
            newEle.remove()
        }
    }
}
