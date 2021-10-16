# Przenoszenie między przestrzeniami branchy plików śledzony przez git'a 


## Wrzucenie na stos z bierzącego katalogu roboczego
`git stash push`

## Jeśli plik został tylko zmodyfikowany, a chcemy wrzucić na stos to należy dodać falge u
`git stash push -u`

## Pobranie ze stos do katalogu bierzącego 
`git stash pop`

## lub podając nazwę
`git stash pop stash@{1}`

## Przeniesienie danych z jedengo brancha do drugiego tworzonego w locie poprzez stos

`git stash branch1 branch2`

## Wylistowanie stosu
`git stash list`

## Skasowanie pliku ze stosu wg nazwy
`git stash drop stash@{1}`

## Wyczyszczenie całego stosu 
`git stash clear`


