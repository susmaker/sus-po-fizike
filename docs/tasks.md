Использованные формулы и константы.
--------------------------------------------------------------------------------

Справа написаны номера задач, в которых используются эти формулы и константы.

!!! tip "Формулы"

    $n_1sin{\alpha} = n_2sin{\beta}$ (2)

    $\frac{1}{F} = \frac{1}{d} + \frac{1}{f}$ (3, 4)

    $F = \frac{1}{D}$ (3)

    $\Gamma = \frac{f}{d} (4)$

    $T = \frac{\lambda}{v_с}$ (5)
    
    $v = \frac{\lambda}{T}$ (6)

    $v = \omega R = \frac{qBR}{m}$ (15)

    $T = \frac{t}{N}$ (6, 7, 8)

    $T = 2\pi\sqrt{\frac{m}{k}}$ (7)

    $T = 2\pi\sqrt{\frac{l}{g}}$ (8)

    $T = \frac{1}{\nu}$ (15)

    $\omega = 2\pi\nu$ (9, 15)

    $\omega = \frac{1}{\sqrt{LC}}$ (9)

    $W = \frac{CU_m^2}{2}$ (5)

    $W_m = \frac{LI_m^2}{2}$ (10)

    $W_м = \frac{Li^2}{2}$ (10, 11)

    $W_m = W_м + W_э$ (10)

    $\xi = Blv\sin{\alpha}$ (12)

    $\xi = \frac{\Delta \phi}{\Delta t}$ (19)

    $\xi _i = - \frac{\Delta \phi}{\Delta t}N$ (13)

    $F = \frac{mv^2}{R} = qvB$ (14)

    $F_А = IBl$ (16, 17)

    $A = F * \Delta x$ (16)

    $F_Т = mg$ (17)

    $\phi = BS$ (18)

    $I = \frac{\xi}{R} = \frac{q}{\Delta t}$ (19)

    $q = \frac{U^2}{r}t$ (20)

    $U = |\frac{\Delta \phi}{\Delta t}| = s|\frac{\Delta B}{\Delta t}|sin{\alpha}$ (20)

    $s = \pi r^2$ (20)

!!! tip "Константы"

    $n_{воздуха} = 1$ (2)

    $n_{воды}$ $= 1.33$ (2)

    $e = 1.6 * 10^{-19}Кл$ (15)

    $m_e = 9.1 * 10^{-31}кг$ (15)

    $p = 1.6 * 10^{-19}Кл$ (14)

    $m_p = 1.67 * 10^{-27}кг$ (14)

    $v_с = 3 * 10^8\frac{м}{с}$ (скорость света) (5)

    $g = 10\frac{м}{с^2}$ (17)

1
--------------------------------------------------------------------------------

Дано:

$h_ф = 4м$

$h_ш = 1м$

$x = 3м$

Найти:

$l$

Решение:

![Рисунок](img/z1.png "Рисунок")

$AB = h_ф$

$A_1B_1 = h_ш$

$BB_1 = x$

$B_1C = l$

$(AB \perp BC) \And (A_1 \perp B_1) \Rightarrow AB \parallel A_1B_1 \Rightarrow (\angle BAC = \angle B_1A_1C) \And (\angle ABC = \angle A_1B_1C)$

$(A_1 \in AC) \And (B_1 \in BC) \Rightarrow \angle ACB = \angle A_1CB_1$

$(\angle BAC = \angle B_1A_1C) \And (\angle ABC = \angle A_1B_1C) \And (\angle ACB = \angle A_1CB_1) \Rightarrow \triangle{ABC} \sim \triangle{A_1B_1C} \Rightarrow \frac{AB}{A_1B_1} = \frac{BC}{B_1C}$

$BC = BB_1 + B_1C$

$\frac{AB}{A_1B_1} = \frac{BB_1 + B_1C}{B_1C}$

$\frac{h_ф}{h_ш} = \frac{x + l}{l}$

$\frac{h_фl}{h_ш} = x + l$

$h_фl = (x + l) * h_ш$

$h_фl = xh_ш + lh_ш$

$l(h_ф - h_ш) = xh_ш$

$l = \frac{xh_ш}{h_ф - h_ш}$

$l = \frac{3м * 1м}{4м - 1м} = 1м$

Ответ: $1м$.

??? note "Другие решения"

    https://fizika.my-dict.ru/q/1026993_otvet-ulicnyj-fonar-visit-na-vysote/

    https://fizika.my-dict.ru/q/3083727_ulicnyj-fonar-visit-na-vysote-4/

2
--------------------------------------------------------------------------------

Дано:

$h = 1.25м$

$\alpha = 45^{\circ}$

Найти:

$x$

Решение:

![Рисунок](img/z2.png "Рисунок")

!!! note ""

    $n_1sin{\alpha} = n_2sin{\beta}$

    $n$ - показатель преломления

    $n_{воздуха} = 1$

    $n_{воды} = 1.33$

$\frac{x}{h} = \tan{\beta}$

$x = \tan{\beta}h$

$\beta = \arcsin{\frac{n_{воздуха}\sin{\alpha}}{n_{воды}}}$

$\beta = \arcsin{\frac{1\sin{45^{\circ}}}{1.33}} = 0.56рад = 32.12^{\circ}$

$x = \tan{32.12^{\circ}} * 1.25м = 0.78м$

Ответ: $0.78м$.

??? note "Другие решения"

    https://5terka.com/node/6151 (для угла в $38^\circ$)

3
--------------------------------------------------------------------------------

Дано:

$D = 5дптр$

$d = 60см = 0.6м$

Найти:

$f$

Решение:

!!! note ""

    $\frac{1}{F} = \frac{1}{d} + \frac{1}{f}$

    $F = \frac{1}{D}$

$F = \frac{1}{5дптр} = 0.2м$

$d$ > $2F \Rightarrow$ изображение будет меньше оригинала.

$D = d^{-1} + \frac{1}{f}$

$\frac{1}{f} = D - d^{-1}$

$f = (D - d^{-1})^{-1}$

$f = (5дптр - 0.6м^{-1})^{-1} = 0.3м$

Ответ: изображение получится на расстоянии $0.3м$ и будет меньше оригинала.

??? note "Другие решения"

    https://otvet.mail.ru/question/74998862

    https://5terka.com/node/6193

4
--------------------------------------------------------------------------------

Дано:

$d = 50см = 0.5м$

$\Gamma = \frac{1}{5}$

Найти:

$F$

Решение:

!!! note ""

    $\frac{1}{F} = \frac{1}{f} - \frac{1}{d}$

    $\Gamma = \frac{f}{d}$

$f = \Gamma d$

$F^{-1} = f^{-1} - d^{-1} = (\Gamma d)^{-1} - d^{-1}$

$F = ((\Gamma d)^{-1} - d^{-1})^{-1}$

$F = ((\frac{1}{5} * 0.5м)^{-1} - (0.5м)^{-1})^{-1} = 0.125м$

Ответ: $0.125м$.

??? note "Другие решения"

    https://easyfizika.ru/zadachi/optika/opredelit-glavnoe-fokusnoe-rasstoyanie-rasseivayuschey-linzy-esli-izvestno-chto/

    https://xn--b1aai8acvc.xn--p1acf/%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B8%D1%82%D0%B5-%D0%B3%D0%BB%D0%B0%D0%B2%D0%BD%D0%BE%D0%B5-%D1%84%D0%BE%D0%BA%D1%83%D1%81%D0%BD%D0%BE%D0%B5-%D1%80%D0%B0%D1%81%D1%81%D1%82%D0%BE%D1%8F/

5
--------------------------------------------------------------------------------

Дано:

$L = 10мкГн = 10^{-5}Гн$

$W_m = 0.004пДж = 4 * 10^{-15}Дж$

$U_m = 50мкВ = 5 * 10^{-5}В$

Найти:

$\lambda$

Решение:

!!! note ""

    $W = \frac{CU_m^2}{2}$

    $T = \frac{\lambda}{v_с}$

    $v_с = 3 * 10^8\frac{м}{с}$ (скорость света)

$W = W_m$

$C = \frac{2W_m}{U_m^2}$

$T = 2\pi\sqrt{LC} = \frac{\lambda}{v_с}$

$\lambda = 2\pi v_с\sqrt{LC} = 2\pi v_с\sqrt{L\frac{2W_m}{U_m^2}} = \frac{2\pi v_с\sqrt{2LW_m}}{U_m}$

$\lambda = \frac{2 * 3.14 * 3 * 10^8\frac{м}{с} * \sqrt{2 * 10^{-5}Гн * 4 * 10^{-15}Дж}}{5 * 10^{-5}В} =$

Ответ: $10657.51м$.

??? note "Другие решения"

    (При $U_m = 5 * 10^{-4}В$)

    https://xn--b1aai8acvc.xn--p1acf/%D0%B2-%D0%BA%D0%B0%D1%82%D1%83%D1%88%D0%BA%D0%B5-%D0%B2%D1%85%D0%BE%D0%B4%D0%BD%D0%BE%D0%B3%D0%BE-%D0%BA%D0%BE%D0%BD%D1%82%D1%83%D1%80%D0%B0-%D0%BF%D1%80%D0%B8%D0%B5%D0%BC%D0%BD%D0%B8%D0%BA%D0%B0/

    https://www.liveexpert.org/topic/view/1824180-v-katushke-vhodnogo-kontura-priemnika-induktivnostyu-10-mkgn-zapasaetsya-pri-prieme-volni-maksimalnaya-energiya-4-10-15-dzh-na-kondensatore

6
--------------------------------------------------------------------------------

Дано:

$t = 10с$

$N = 20$

$\lambda = 1.2м$

Найти:

$v$

Решение:

!!! note ""

    $v = \frac{\lambda}{T}$

    $T = \frac{t}{N}$

$v = \frac{\lambda}{\frac{t}{N}} = \frac{\lambda N}{t}$

$v = \frac{1.2м * 20}{10с} = 2.4\frac{м}{с}$

Ответ: $2.4\frac{м}{с}$.

??? note "Другие решения"

    https://easyfizika.ru/zadachi/kolebaniya-i-volny/rybolov-zametil-chto-za-10-s-poplavok-sovershil-na-volnah-20-kolebanij/

    https://5terka.com/node/3546

7
--------------------------------------------------------------------------------

Дано:

$k = 250\frac{Н}{м}$

$N = 20$

$t = 16с$

Найти:

$m$

Решение:

!!! note ""

    $T = \frac{t}{N} = 2\pi\sqrt{\frac{m}{k}}$

$\frac{t}{N} = 2\pi\sqrt{\frac{m}{k}}$

$\frac{t^2}{N^2} = 4\pi^2\frac{m}{k}$

$m = \frac{t^2k}{4N^2\pi^2}$

$m = \frac{16с^2 * 250\frac{Н}{м}}{20^2 * 4 * 3.14^2} = 4.06кг$

Ответ: $4.06кг$.

??? note "Другие решения"

    https://5terka.com/node/3527

    https://xn--b1aai8acvc.xn--p1acf/%D0%BD%D0%B0%D0%B9%D0%B4%D0%B8%D1%82%D0%B5-%D0%BC%D0%B0%D1%81%D1%81%D1%83-%D0%B3%D1%80%D1%83%D0%B7%D0%B0-%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D0%B9-%D0%BD%D0%B0-%D0%BF%D1%80%D1%83%D0%B6%D0%B8%D0%BD/

    https://otvet.mail.ru/question/68147790

8
--------------------------------------------------------------------------------

Дано:

$l = 80см = 0.8м$

$t = 3мин = 180с$

$N = 100$

Найти:

$g$

Решение:

!!! note ""

    $T = \frac{t}{N} = 2\pi\sqrt{\frac{l}{g}}$

$\frac{t}{N} = 2\pi\sqrt{\frac{l}{g}}$

$\frac{t^2}{N^2} = 4\pi^2\frac{l}{g}$

$\frac{l}{g} = \frac{t^2}{4N^2\pi^2}$

$g = \frac{4lN^2\pi^2}{t^2}$

$g = \frac{0.8см * 100^2 * 4 * 3.14^2}{180с^2} = 9.74\frac{м}{с^2}$

Ответ: $9.74\frac{м}{с^2}$.

??? note "Другие решения"

    https://5terka.com/node/5216

    https://fizika.my-dict.ru/q/1037109_kakoe-znacenie-polucil-dla-uskorenia-svobodnogo/

    https://otvet.mail.ru/question/48469626

9
--------------------------------------------------------------------------------

Дано:

$L = 5.1мкГн = 5.1 * 10^{-6}Гн$

$\nu = 10МГц = 10^7Гц$

Найти:

$C$

Решение:

!!! note ""

    $\omega = 2\pi\nu = \frac{1}{\sqrt{LC}}$

$2\pi\nu = \frac{1}{\sqrt{LC}}$

$\sqrt{LC} = \frac{1}{2\pi\nu}$

$LC = \frac{1}{4\pi^2\nu^2}$

$C = \frac{1}{4\pi^2\nu^2L}$

$C = \frac{1}{4 * 3.14^2 * (10^7Гц)^2 * 5.1 * 10^{-6}Гн} = 4.97 * 10^{-11}Ф$

Ответ: $4.97 * 10^{-11}Ф$.

??? note "Другие решения"

    https://uchi.ru/otvety/questions/kondensator-kakoy-yomkosti-nado-vklyuchit-v-kolebatelniy-kontur-chtobi-pri-induktivnosti

    https://xn--b1aai8acvc.xn--p1acf/%D0%BA%D0%BE%D0%BD%D0%B4%D0%B5%D0%BD%D1%81%D0%B0%D1%82%D0%BE%D1%80-%D0%BA%D0%B0%D0%BA%D0%BE%D0%B9-%D0%B5%D0%BC%D0%BA%D0%BE%D1%81%D1%82%D0%B8-%D0%BD%D0%B0%D0%B4%D0%BE-%D0%B2%D0%BA%D0%BB%D1%8E%D1%87/

10
--------------------------------------------------------------------------------

Дано:

$L = 0.2Гн$

$I_m = 40мА = 4 * 10^{-2}A$

$I_m = 2i$

Найти:

$W_м$

$W_э$

Решение:

!!! note ""

    $W_m = \frac{LI_m^2}{2}$

    $W_м = \frac{Li^2}{2}$

    $W_m = W_м + W_э$

$W_м = \frac{Li^2}{2} = \frac{L(0.5I_m)^2}{2}$

$W_м = \frac{0.2Гн * (0.5 * 4 * 10^{-2}A)^2}{2} = 4 * 10^{-5}Дж$

$W_э = W_m - W_м$

$W_э = \frac{0.2Гн * (4 * 10^{-2}А)^2}{2} - 4 * 10^{-5}Дж = 1.2 * 10^{-4}Дж$

Ответ: $W_м = 4 * 10^{-5}Дж$; $W_э = 1.2 * 10^{-4}Дж$.

??? note "Другие решения"

    https://bambookes.ru/stuff/reshenie_zadach/fizika/v_kolebatelnom_konture_induktivnost_katushki_amplituda_kolebanij_sily_toka/2-1-0-944

    https://fizika.my-dict.ru/q/1398787_v-kolebatelnom-konture-induktivnost-katuski-ravna/

    https://easyfizika.ru/zadachi/kolebaniya-i-volny/v-kolebatelnom-konture-induktivnost-katushki-ravna-0-2-gn-amplituda-sily-toka/

11
--------------------------------------------------------------------------------

Дано:

$i_1 = 12А$

$i_2 = 8А$

$\Delta W_м = -2Дж$

Найти:

$L$

$W_{м1}$

$W_{м2}$

Решение:

!!! note ""

    $W_м = \frac{Li^2}{2}$

$\Delta W_м = W_{м2} - W_{м1} = \frac{Li_2^2}{2} - \frac{Li_1^2}{2} = L(\frac{i_2^2 - i_1^2}{2})$

$L = \frac{2\Delta W_м}{i_2^2 - i_1^2}$

$L = \frac{2 * (-2Дж)}{8^2А - 12^2А} = 0.05Гн$

$W_{м1} = \frac{Li_1^2}{2}$

$W_{м1} = \frac{0.05Гн * 12А^2}{2} = 3.6Дж$

$W_{м2} = W_{м1} + \Delta W_м$

$W_{м2} = 3.6Дж - 2Дж = 1.6Дж$

Ответ: $L = 0.05Гн$; $W_{м1} = 3.6Дж$; $W_{м2} = 1.6Дж$.

??? note "Другие решения"

    https://5terka.com/node/5873 (см. ответ в комментариях ВК)

12
--------------------------------------------------------------------------------

Дано:

$l = 0.25м$

$B = 8мТл = 8 * 10^{-3}$

$v = 5\frac{м}{с}$

$\alpha = 30^\circ$

Найти:

$\xi _i$

Решение:

!!! note ""

    $\xi = Blv\sin{\alpha}$

$\xi _i = 8 * 10^{-3} * 0.25м * 5\frac{м}{с} * \sin{30^\circ} = 5 * 10^{-3}В$

Ответ: $5 * 10^{-3}В$.

??? note "Другие решения"

    https://easyfizika.ru/zadachi/magnitnoe-pole/najti-velichinu-eds-induktsii-v-provodnike-s-dlinoj-aktivnoj-chasti-0-25-m-kotoryj/

    https://bambookes.ru/stuff/reshenie_zadach/fizika/najti_ehds_indukcii_v_provodnike_s_dlinoj_aktivnoj_chasti/2-1-0-928

13
--------------------------------------------------------------------------------

Дано:

$\Delta t = 5мс = 5 * 10^{-3}с$

$N = 500$

$\phi _1 = 7мВб = 7 * 10^{-3}Вб$

$\phi _2 = 3мВб = 3 * 10^{-3}Вб$

Найти:

$\xi _i$

Решение:

!!! note ""

    $\xi _i = - \frac{\Delta \phi}{\Delta t}N$

$\xi _i = - \frac{\phi _2 - \phi _1}{\Delta t}N$

$\xi _i = - \frac{3 * 10^{-3}Вб - 7 * 10^{-3}Вб}{5 * 10^{-3}с} * 500 = 400В$

Ответ: $400В$.

??? note "Другие решения"

    https://easyfizika.ru/zadachi/magnitnoe-pole/za-5-ms-v-solenoide-soderzhashhem-500-vitkov-provoda-magnitnyj-potok-ravnomerno/

    https://5terka.com/node/5834

14
--------------------------------------------------------------------------------

Дано:

$B = 0.01Тл$

$R = 10см = 0.1м$

Найти:

$v$

Решение:

!!! note ""

    $F = \frac{mv^2}{R} = qvB$

    $p = 1.6 * 10^{-19}Кл$

    $m_p = 1.67 * 10^{-27}кг$

$\frac{m_pv^2}{R} = pvB$

$\frac{m_pv}{R} = pB$

$v = \frac{pBR}{m_p}$

$v = \frac{1.6 * 10^{-19}Кл * 0.01Тл * 0.1м}{1.67 * 10^{-27}кг} = 95808.38\frac{м}{с}$

Ответ: $95808.38\frac{м}{с}$.

??? note "Другие решения"

    https://chemzanyatsa.com/proton-v-magnitnom-pole-s-indykciei-0-01-t-opisal-okryjnost-radiysom-10-santimetrov-naiti-skorost-protona.html

    https://abiturient.pro/fizika/754900-proton-v-magnitnom-pole-s-indukciej-001-t-opisal-okruzhnost-radiusom-1.html

15
--------------------------------------------------------------------------------

Дано:

$B = 4мТл = 4 * 10^{-3}Тл$

Найти:

$T$

Решение:

!!! note ""

    $\omega = 2\pi\nu$

    $T = \frac{1}{\nu}$

    $v = \omega R = \frac{qBR}{m}$ (15)

$\omega = \frac{v}{R} = \frac{\frac{qBR}{m}}{R} = \frac{qBR}{mR} = \frac{qB}{m}$

$T = \frac{2\pi}{\omega}$

$T = \frac{2\pi m}{qB} = \frac{2\pi m_e}{eB}$

$T = \frac{2 * 3.14 * 9.1 * 10^{-31}кг}{1.6 * 10^{-19}Кл * 4 * 10^{-3}Тл} = 8.93 * 10^{-9}с$

Ответ: $8.93 * 10^{-9}с$.

??? note "Другие решения"

    https://5terka.com/node/3991

    https://bambookes.ru/stuff/reshenie_zadach/fizika/ehlektron_dvizhetsja_v_odnorodnom_magnitnom_pole_indukciej/2-1-0-852

16
--------------------------------------------------------------------------------

Дано:

$l = 8см = 0.08м$

$I = 50А$

$B = 20мТл = 2 * 10^{-2}Тл$

$\Delta x = 10см = 0.1м$

Найти:

$A$

Решение:

!!! note ""

    $F_А = IBl$

    $A = F * \Delta x$

$A = F_А * \Delta x = IBl * \Delta x$

$A = 50А * 2 * 10^{-2}Тл * 0.08м * 0.1м = 8 * 10^{-3}Дж$

Ответ: $A = 8 * 10^{-3}Дж$.

??? note "Другие решения"

    https://5terka.com/node/3983

    https://bambookes.ru/stuff/reshenie_zadach/fizika/v_provodnike_s_dlinoj_aktivnoj_chasti_8_sm_sila_toka_ravna_50_a_nakhoditsja_v_odnorodnom_magnitnom_pole/2-1-0-844

17
--------------------------------------------------------------------------------

Дано:

$l = 20см = 0.2м$

$m = 4г = 4 * 10^{-3}кг$

$I = 10А$

$F_Т = F_А$

Найти:

$B$ (модуль и направление)

Решение:

!!! note ""

    $F_Т = mg$

    $g = 10\frac{м}{с^2}$

    $F_А = IBl$

$mg = IBl$

$B = \frac{mg}{Il}$

$B = \frac{4 * 10^{-3}кг * 10\frac{м}{с^2}}{10А * 0.2м} = 0.02Тл$

Ответ: $0.02Тл$.

??? note "Другие решения"

    https://uchi.ru/otvety/questions/sila-toka-v-gorizontalno-raspolozhennom-provodnike-dlinoy-20-sm-i-massoy-4-g-ravna-10-amp

    https://5terka.com/node/3981

18
--------------------------------------------------------------------------------

Дано:

$S = 50см^2 = 1см * 50см = 0.01м * 0.5м = 5 * 10^{-3}м^2$

$B_1 = 0.2Тл$

$B_2 = 0.3Тл$

$\Delta t = 4мс = 4 * 10^{-3}с$

$\xi = 10В$

Найти:

$N$

Решение:

!!! note ""

    $\xi _i = |\frac{\Delta \phi}{\Delta t}|N$

    $\phi = BS$

$\Delta \phi = \phi _2 - \phi _1 = B_2S - B_1S = (B_2 - B_1)S$

$\xi _i = |\frac{(B_2 - B_1)S}{\Delta t}|N$

$N = \frac{\xi _i}{|\frac{(B_2 - B_1) * S}{\Delta t}|}$

$N = \frac{10В}{|\frac{(0.3Тл - 0.2Тл) * 5 * 10^{-3}м^2}{4 * 10^{-3}с}|} = 80$

Ответ: $80$.

??? note "Другие решения"

    https://5terka.com/node/4066

    https://bambookes.ru/stuff/reshenie_zadach/fizika/skolko_vitkov_dolzhna_soderzhat_katushka_s_ploshhadju_poperechnogo_sechenija_50_sm2_chtoby_pri_izmeneniimagnitnoj_indukcii/2-1-0-923

19
--------------------------------------------------------------------------------

Дано:

$R = 0.03Ом$

$\Delta \phi = 12мВб = 12 * 10^{-3}Вб$

Найти:

$q$

Решение:

!!! note ""

    $\xi = \frac{\Delta \phi}{\Delta t}$

    $I = \frac{\xi}{R} = \frac{q}{\Delta t}$

$\frac{\frac{\Delta \phi}{\Delta t}}{R} = \frac{q}{\Delta t}$

$\frac{\Delta \phi}{\Delta tR} = \frac{q}{\Delta t}$

$q = \frac{\Delta \phi \Delta t}{\Delta tR} = \frac{\Delta \phi}{R}$

$q = \frac{12 * 10^{-3}Вб}{0.03Ом} = 0.4Кл$

Ответ: $0.4Кл$.

??? note "Другие решения"

    https://5terka.com/node/4068

    https://bambookes.ru/stuff/reshenie_zadach/fizika/kakoj_zarjad_q_projdet_cherez_poperechnoe_sechenie_vitka/2-1-0-925

20
--------------------------------------------------------------------------------

Дано:

$r = 10см = 0.1м$

$R = 0.01Ом$

$\alpha = 60^\circ$

$Q = 555мкДж = 555 * 10^{-6}Дж$

$\frac{\Delta B}{\Delta t} = 0.05\frac{Тл}{с}$

Найти:

$t$

Решение:

!!! note ""

    $q = \frac{U^2}{r}t$

    $U = |\frac{\Delta \phi}{\Delta t}| = s|\frac{\Delta B}{\Delta t}|sin{\alpha}$

    $s = \pi r^2$

$t = \frac{QR}{U^2} = \frac{QR}{(S|\frac{\Delta B}{\Delta t}|(sin{\alpha})^2)} = \frac{QR}{(\pi r^2|\frac{\Delta B}{\Delta t}|sin{\alpha})^2}$

$t = \frac{555 * 10^{-6}Дж * 0.01Ом}{(3.14 * (0.1м)^2| * 0.05\frac{Тл}{с}| * sin{60^\circ})^2} = 3с$

Ответ: $3с$.

??? note "Другие решения"

    https://self-edu.ru/ege2017_phis_30.php?id=19_26