# homework
Променя се сървърът, като вместо да се създаде една нишка, се създава thread pool с 10 нишки. Това позволява създаването и работенето на 10 нишки, но ако се създаде още една, тя ще се блокира, докато някоя от предните не приключи.
За да работи, трябва първо да се пусне сървърът, после 10 клиента. За да се провери дали работи, може да се пусне още един клиент, който няма да респондва, докато не спрем някой от другите клиенти.
