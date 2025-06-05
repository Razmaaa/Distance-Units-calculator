
const fromUnit = document.getElementById("from_unit")


const toUnit = document.getElementById("to_unit")

const unitLength = document.getElementById("unit_length")

let result

const calculationOutput=document.getElementById("calculation_output")

function convertKmTo(length,unit){
  if(unit==='mi'){
    return length/1.6
  }else if (unit==='m'){
    return length*1000
  }else if (unit==='yd'){
    return length*1093.61
  }else if (unit==='km'){
    return length
  }
}
function convertMiTo(length,unit){
  if(unit==='mi'){
    return length
  }else if (unit==='m'){
    return length*1609.34
  }else if (unit==='yd'){
    return length*1760
  }else if (unit==='km'){
    return length*1.6
  }
}
function convertYdTo(length,unit){
  if(unit==='mi'){
    return length/1760
  }else if (unit==='m'){
    return length/1.094
  }else if (unit==='yd'){
    return length
  }else if (unit==='km'){
    return length/1094
  }
}
function convertMTo(length,unit){
  if(unit==='mi'){
    return length/1609
  }else if (unit==='m'){
    return length
  }else if (unit==='yd'){
    return length*1.094
  }else if (unit==='km'){
    return length/1000
  }
}


function convertDistance(length,from,to){
  if(from!=='km'&&from!=='mi'&&from!=='m'&&from!=='yd'){
      return alert(`Invalid unit: ${from},Please use 'km', 'mi', 'm', or 'yd'.`)
  } 
  if (to!=='km'&&to!=='mi'&&to!=='m'&&to!=='yd'){
      return alert(`Invalid unit: ${to},Please use 'km', 'mi', 'm', or 'yd'.`)
  }
  if (length<=0){ return alert('Distance must be greater than zero!')}

  if(from==='km'){
    return `${convertKmTo(length,to)} ${to}`
  }else if (from==='mi'){
    return `${convertMiTo(length,to)} ${to}`
  }else if (from==='m'){
    return `${convertMTo(length,to)} ${to}`
  }else if (from==='yd'){
    return `${convertYdTo(length,to)} ${to}`
  }
}

// console.log(convertDistance(50,'km','m'))
// console.log(convertDistance(100,'m','m'))
// console.log(convertDistance(60,'mi','m'))
// console.log(convertDistance(100,'m','km'))
// console.log(convertDistance(60,'yd','m'))
// console.log(convertDistance(60,'mi','km'))
// console.log(convertDistance(60,'mi','yd'))

