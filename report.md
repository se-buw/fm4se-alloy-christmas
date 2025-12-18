## WishList
### :x: Failed: Here is a solution allowed by your predicate, but incorrect:
```
this/Puppy={}
this/Doll={Doll$0}
this/PS5={}
this/Xbox={}
this/DogBasket={}
this/Ball={}
this/Dresses={}
this/BarbieGame={}
this/DogGame={}
this/DollHouse={}

```

## SecretSanta
### :x: Failed: Here is a solution allowed by your predicate, but incorrect:
```
this/Intern={Intern$0, Intern$1}
this/Intern<:supervisor={Intern$0->Intern$0, Intern$1->Employee$0}
this/Employee={Employee$0, Intern$0, Intern$1}
this/Employee<:officePartners={Employee$0->Employee$0, Employee$0->Intern$0, Employee$0->Intern$1}
this/Employee<:isSecretSantaFor={Employee$0->Intern$1, Intern$0->Intern$0, Intern$1->Employee$0}

```

## ChristmasTree
### :x: Failed: Here is a solution allowed by your predicate, but incorrect:
```
this/Tree={Tree$0, Tree$1, Tree$2, Tree$3, Tree$4, Tree$5, Tree$6, Tree$7}
this/Tree<:x={Tree$0->6, Tree$1->6, Tree$2->6, Tree$3->6, Tree$4->6, Tree$5->6, Tree$6->6, Tree$7->5}
this/Tree<:y={Tree$0->0, Tree$1->6, Tree$2->6, Tree$3->6, Tree$4->6, Tree$5->2, Tree$6->7, Tree$7->6}

```

