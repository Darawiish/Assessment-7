// 1) Sum Zero


function addToZero(array){
    const output = [];
    for(let i = 0; i < array.length; i++){
        for(let j = 0; j < array.length; j++){
            if(array[i] + array[j] === 0){
                output.push(output)
            }
            else if(answer.length ==! 0){
                return false
            }
        }
    return true
    }
}


runtime = 0(1). 






// 2) Unique Characters



function hasUniqueChars(str){
    let uniqueChars = new Set([]);
    for (let i =0; i < str.length; i++){
        uniqueChars.add(str[i]);
    }
    return uniqueChars.size === str.length;
}


runtime = 0(N)





// 3) Pangram Sentence


function PangramSentence(str) {
    let alphabet = [a-zA-Z]
for(alphabet) {
    if(!str.includes(alphabet[letter])){
        return false
        }
    } return true 
}     



runtime = 0(N^2)





// 4) Longest Word


function longestWord(arr){
   let longestWord = []
    for(word in arr){
        if(arr[word].length >= word.length){
        longestWord = arr[word]
        }
    }
    return longestWord.length 
}



runtime = 0(N).
