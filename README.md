# clean_code_javascript_jKEeY
В этом файле я опишу те принципы правильного кода из книги Роберта Мартина "Чистый код"

# Содержательные имена

###  Имена должны передавать намерения программиста

const d; // Прошедшее время - Плохо

function getFlaggedCells(gameBoard) {
    const flaggedCeils = [];
    for (ceil in gameBoard) {
      if (ceild.isFlagged()) flaggedCeils.push(ceil);
    }
    
    return flaggedCeils;
} --- Хорошо


