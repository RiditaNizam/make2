public int[] make2(int[] a, int[] b) {
  
  int[] answerArray = new int[2];
  
  if(b.length == 0){
    answerArray[0] = a[0];
    answerArray[1] = a[1];
  }

  else if(b.length >= 1){
    if(a.length == 0){
      answerArray[0] = b[0];
      answerArray[1] = b[1];
    }
  
    else if(a.length == 1){
      answerArray[0] = a[0];
      answerArray[1] = b[0];
    }
  
    else if (a.length >= 2){
      answerArray[0] = a[0];
      answerArray[1] = a[1];
    }
  }
  
  return answerArray;
  
}
