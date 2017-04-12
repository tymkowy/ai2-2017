# Aplikacje internetowe II / Python / 2017

## Plik list1.py
```
match_ends
 OK  got: 3 expected: 3
 OK  got: 2 expected: 2
 OK  got: 1 expected: 1
front_x
 OK  got: ['xaa', 'xzz', 'axx', 'bbb', 'ccc'] expected: ['xaa', 'xzz', 'axx', 'bbb', 'ccc']
 OK  got: ['xaa', 'xcc', 'aaa', 'bbb', 'ccc'] expected: ['xaa', 'xcc', 'aaa', 'bbb', 'ccc']
 OK  got: ['xanadu', 'xyz', 'aardvark', 'apple', 'mix'] expected: ['xanadu', 'xyz', 'aardvark', 'apple', 'mix']
sort_last
 OK  got: [(2, 1), (3, 2), (1, 3)] expected: [(2, 1), (3, 2), (1, 3)]
 OK  got: [(3, 1), (1, 2), (2, 3)] expected: [(3, 1), (1, 2), (2, 3)]
 OK  got: [(2, 2), (1, 3), (3, 4, 5), (1, 7)] expected: [(2, 2), (1, 3), (3, 4, 5), (1, 7)]
```
## Plik list2.py
```
remove_adjacent
 OK  got: [1, 2, 3] expected: [1, 2, 3]
 OK  got: [2, 3] expected: [2, 3]
 OK  got: [] expected: []
linear_merge
 OK  got: ['aa', 'bb', 'cc', 'xx', 'zz'] expected: ['aa', 'bb', 'cc', 'xx', 'zz']
 OK  got: ['aa', 'bb', 'cc', 'xx', 'zz'] expected: ['aa', 'bb', 'cc', 'xx', 'zz']
 OK  got: ['aa', 'aa', 'aa', 'bb', 'bb'] expected: ['aa', 'aa', 'aa', 'bb', 'bb']
```
## Plik string1.py
```
donuts
 OK  got: 'Number of donuts: 4' expected: 'Number of donuts: 4'
 OK  got: 'Number of donuts: 9' expected: 'Number of donuts: 9'
 OK  got: 'Number of donuts: many' expected: 'Number of donuts: many'
 OK  got: 'Number of donuts: many' expected: 'Number of donuts: many'
both_ends
 OK  got: 'spng' expected: 'spng'
 OK  got: 'Helo' expected: 'Helo'
 OK  got: '' expected: ''
 OK  got: 'xyyz' expected: 'xyyz'
fix_start
 OK  got: 'ba**le' expected: 'ba**le'
 OK  got: 'a*rdv*rk' expected: 'a*rdv*rk'
 OK  got: 'goo*le' expected: 'goo*le'
 OK  got: 'donut' expected: 'donut'
mix_up
 OK  got: 'pox mid' expected: 'pox mid'
 OK  got: 'dig donner' expected: 'dig donner'
 OK  got: 'spash gnort' expected: 'spash gnort'
 OK  got: 'fizzy perm' expected: 'fizzy perm'
```
## Plik string2.py
```
verbing
 OK  got: 'hailing' expected: 'hailing'
 OK  got: 'swimingly' expected: 'swimingly'
 OK  got: 'do' expected: 'do'
not_bad
 OK  got: 'This movie is good' expected: 'This movie is good'
 OK  got: 'This dinner is good!' expected: 'This dinner is good!'
 OK  got: 'This tea is not hot' expected: 'This tea is not hot'
 OK  got: "It's bad yet not" expected: "It's bad yet not"
```

## Plik lab1-warmup.py
```
helloworld()
    "Hello, world!"

board()
      |  |  
    --------
      |  |  
    --------
      |  |  
    
tictactoe()
    --+--+--H--+--+--H--+--+--
      |  |  H  |  |  H  |  |  
    --+--+--H--+--+--H--+--+--
      |  |  H  |  |  H  |  |  
    --+--+--H--+--+--H--+--+--
    ========+========+========
    --+--+--H--+--+--H--+--+--
      |  |  H  |  |  H  |  |  
    --+--+--H--+--+--H--+--+--
      |  |  H  |  |  H  |  |  
    --+--+--H--+--+--H--+--+--
    ========+========+========
    --+--+--H--+--+--H--+--+--
      |  |  H  |  |  H  |  |  
    --+--+--H--+--+--H--+--+--
      |  |  H  |  |  H  |  |  
    --+--+--H--+--+--H--+--+--    

multiples()
    0 3 5 6 9 10 12 15 18 20 21 24 25 27 30 33 35 36 39 40 42 45 48 50 51 54 55 57 60 63 65 66 69 70 72 75 78 80 81 84 85 87 90 93 95 96 99 100 102 105 108 110 111 114 115 117 120 123 125 126 129 130 132 135 138 140 141 144 145 147 150 153 155 156 159 160 162 165 168 170 171 174 175 177 180 183 185 186 189 190 192 195 198 200 201 204 205 207 210 213 215 216 219 220 222 225 228 230 231 234 235 237 240 243 245 246 249 250 252 255 258 260 261 264 265 267 270 273 275 276 279 280 282 285 288 290 291 294 295 297 300 303 305 306 309 310 312 315 318 320 321 324 325 327 330 333 335 336 339 340 342 345 348 350 351 354 355 357 360 363 365 366 369 370 372 375 378 380 381 384 385 387 390 393 395 396 399 400 402 405 408 410 411 414 415 417 420 423 425 426 429 430 432 435 438 440 441 444 445 447 450 453 455 456 459 460 462 465 468 470 471 474 475 477 480 483 485 486 489 490 492 495 498 500 501 504 505 507 510 513 515 516 519 520 522 525 528 530 531 534 535 537 540 543 545 546 549 550 552 555 558 560 561 564 565 567 570 573 575 576 579 580 582 585 588 590 591 594 595 597 600 603 605 606 609 610 612 615 618 620 621 624 625 627 630 633 635 636 639 640 642 645 648 650 651 654 655 657 660 663 665 666 669 670 672 675 678 680 681 684 685 687 690 693 695 696 699 700 702 705 708 710 711 714 715 717 720 723 725 726 729 730 732 735 738 740 741 744 745 747 750 753 755 756 759 760 762 765 768 770 771 774 775 777 780 783 785 786 789 790 792 795 798 800 801 804 805 807 810 813 815 816 819 820 822 825 828 830 831 834 835 837 840 843 845 846 849 850 852 855 858 860 861 864 865 867 870 873 875 876 879 880 882 885 888 890 891 894 895 897 900 903 905 906 909 910 912 915 918 920 921 924 925 927 930 933 935 936 939 940 942 945 948 950 951 954 955 957 960 963 965 966 969 970 972 975 978 980 981 984 985 987 990 993 995 996 999 1000 

collatz(8)
    8 -> 4.0 -> 2.0 -> 1.0

ftoc(243)
    117.22222222222223
```

## Plik lab2-datastructures.py
```
    s = [0] * 3
    s[0] += 1
    print(s)
      Wynik: [1, 0, 0]

    s = [''] * 3
    s[0] += 'a'
    print(s)
      Wynik: ['a', '', '']

    s = [[]] * 3
    s[0] += [1]
    print(s)
      Wynik: [[1], [1], [1]]


    gcd(a, b):
      while b != 0:
          (a, b) = (b, a % b)
      print(a)
    
        gcd(10, 25) => 5
        gcd(14, 15) => 1
        gcd(3, 9) => 3
        gcd(1, 1) => 1
```
