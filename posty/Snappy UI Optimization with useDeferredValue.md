https://www.joshwcomeau.com/react/use-deferred-value

## UseDeferredValue

hook jest często nie doceniony 

ma potencjał wpłynąć pozytywnie na UX

## Problem 

czeste odświeżanie kosztownego UI w tym przypadku snipettu który posada kolorowanie a to jest sporo makrupu

możemy tutaj szukać rozwiązań opóźniających odświeżania np tylko raz na 200ms ale to powoduje że lepsze urządzenia też tracą a chociaż mozga odświeżać szybciej 

zwykle można zauważyć które elementy UI mają większy/mniejszy priorytet 

![img](https://www.joshwcomeau.com/images/use-deferred-value/high-vs-low-priority.png)

## Rozwiązanie 

