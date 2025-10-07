function filtrovane(arr = [], byType = 'number') {
    console.log(arr)
    const result  = []
    if(!Array.isArray(arr)) {
        return result;
    }


   !!! Дз: Другий параметр byType задає тип по якому фільтрувати.
