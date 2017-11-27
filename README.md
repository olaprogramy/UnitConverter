# UnitConverter
Program do konwersji jednostek np. wagi, obszaru, długości. 

Nie używaj zdarzeń wywoływanych na formularzu lub też na przyciskach. Nasłuchiwanie ustaw w skrypcie, np. w html mamy zdefiniowany przycisk:
<button class="btn" id="przycisk">Przycisk</button>
to w skrypcie użyjemy nasłuchiwania na to co się dzieje:
<script>
  var btn = document.getElementById('przycisk');
  btn.addEventListener('click', funkcja, false);
  
  function funkcja() {
    //zawartość funkcji
  }
</script>
