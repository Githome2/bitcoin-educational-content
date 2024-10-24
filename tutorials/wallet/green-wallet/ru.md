---
name: Green Wallet

description: Руководство по настройке и использованию (CC Bistack)
---

![cover](assets/cover.webp)

Мобильный кошелек для новичков - Бесплатно - Для защиты от 0 до 1,000 €

Для защиты сумм до 1,000€ идеально подходит бесплатный горячий кошелек (подключенный к интернету), который идеален для новичков. Его настройка проста, а интерфейс разработан для начинающих.

Если вы хотите посетить их веб-сайт, кликните здесь (https://blockstream.com/green/)!

## Видеоурок

![green wallet tutorial video](https://www.youtube.com/watch?v=lONbCS31am4)

## Письменное руководство

> Это руководство было создано и принадлежит Bitstack. Bitstack - это биткойн-необанк, базирующийся в Париже, который позволяет осуществлять DCA на биткойн. Руководство написано Лоиком Морелем 15/02/2023. Оно принадлежит им. https://www.bitstack-app.com/blog/installer-portefeuille-bitcoin-green-wallet

![image](assets/0.webp)

Как установить ваш первый биткойн-кошелек? Руководство по Green Wallet

Если вы хотите воспользоваться многими преимуществами системы Bitcoin, включая нецензурируемость и неприкосновенность ваших средств, вы должны лично хранить ключи, дающие доступ к вашим биткойнам.

В этом руководстве я объясню, как настроить ваш первый кошелек с помощью Green Wallet. Это программное обеспечение особенно подходит для начинающих пользователей. Оно очень просто в использовании, даже если у вас нет продвинутых знаний о Bitcoin.

Green Wallet доступен на всех типах устройств. В этом руководстве мы рассмотрим, как использовать его на мобильном устройстве, но вы также можете скачать его на компьютер.

Первый шаг, очевидно, заключается в загрузке программного обеспечения или приложения Green Wallet. Если вы используете мобильное устройство, вы можете просто скачать его из вашего магазина. Убедитесь, что вы находитесь на официальной странице загрузки приложения. Вот страницы в зависимости от вашей системы:

> - Google Play Store
>
> - Apple App Store

Если вы загружаете программное обеспечение на компьютер, я настоятельно советую вам проверить подлинность и целостность двоичного файла перед его установкой на вашу машину. Я объясню, как выполнить эту операцию в будущем руководстве.

## Выбор настроек приложения

При запуске приложения вы попадете на домашний экран. В данный момент у вас нет ни одного кошелька. Позже, если вы создадите несколько кошельков, вы сможете найти их здесь.

Первое действие, которое необходимо предпринять перед созданием вашего кошелька, - это открыть настройки приложения, чтобы выбрать те, которые вам больше всего подходят.

![image](assets/1.webp)

- "Улучшенная конфиденциальность" позволяет отключить возможность делать скриншоты в приложении. Этот параметр также скрывает предварительные просмотры и автоматически блокирует приложение, когда вы блокируете ваш телефон. Он доступен только на Android;
- Затем вы можете выбрать маршрутизацию вашего трафика через Tor, чтобы все ваши соединения были зашифрованы. Это немного замедляет работу вашего приложения, но я рекомендую активировать его для сохранения вашей конфиденциальности;

- Опция "Testnet" позволяет создавать кошельки в Testnet. Это сеть, которая действует точно так же, как система Bitcoin, за исключением того, что биткойны, обмениваемые в ней, абсолютно не имеют ценности. Эта отдельная сеть Testnet предпочтительна для пользователей или разработчиков, которые хотят тестировать приложения без финансовых рисков. Если вы хотите использовать Green Wallet в реальной системе Bitcoin, вы можете оставить эту опцию неотмеченной;

- Опция "Помочь Green" позволяет передавать конфиденциальную информацию в Blockstream, чтобы они могли улучшить свое приложение;

- Опция "Личный сервер Electrum" позволяет подключить ваш собственный удаленный узел Bitcoin для доступа к информации сети и трансляции ваших транзакций;
- Опция "Проверка SPV" позволяет вам самостоятельно загружать и проверять определенную информацию из блокчейна. Это уменьшает необходимость доверять узлу Blockstream. Обратите внимание, что эта опция не предоставляет всех гарантий настоящего узла Bitcoin, но если у вас его нет, это может быть хорошим вариантом для активации.
После выбора настроек вы можете нажать на кнопку "Сохранить" и затем перезапустить ваше приложение.

## Создание биткойн-кошелька

Следующий шаг - создание вашего биткойн-кошелька. Для этого нажмите на:

> - Добавить кошелек;
> - Новый кошелек;
> - Bitcoin.

![изображение](assets/3.webp)

Опция "Восстановить кошелек" позволяет вам восстановить доступ к существующему кошельку, используя его мнемоническую фразу. Опция "Кошелек только для просмотра" позволяет вам импортировать расширенный публичный ключ (xpub) для просмотра движений по кошельку без возможности тратить его средства.

> "Кошелек только для просмотра особенно полезен, если у вас есть аппаратный кошелек. Вы можете импортировать xpub на ваш телефон для создания адресов для получения и отслеживания баланса кошелька, размещенного на аппаратном кошельке."
> Сетевые опции позволяют вам подключить ваш кошелек к различным системам. Сеть "Liquid" - это боковая цепь Bitcoin. Сеть "Testnet" - это копия сети Bitcoin, но с биткойнами, не имеющими ценности. Наконец, сеть "Testnet Liquid" является эквивалентом Testnet для боковой цепи Liquid. В этом руководстве мы просто хотим создать биткойн-кошелек, поэтому выбираем сеть "Bitcoin".

Далее вас спросят, какой тип кошелька вы хотите создать. Простейший вариант - создать кошелек "Single Sig". В этом случае каждый UTXO (часть биткойна), принадлежащий нам, будет заблокирован только одной парой ключей.

Выберите "Одиночная подпись".

Затем вы можете выбрать мнемоническую фразу из 12 слов или из 24 слов. Эта фраза позволит вам восстановить доступ к вашему кошельку с любым совместимым программным обеспечением в случае потери, кражи или повреждения вашего телефона.

Фраза из 24 слов более защищена от атак перебором, чем фраза из 12 слов. Однако на данный момент фраза из 12 слов все еще достаточно безопасна. На практике, если вы выберете фразу из 12 слов, вы будете чуть выше минимального рекомендуемого предела NIST. Это означает, что ваша фраза безопасна сегодня, но может быть не таковой в будущем из-за прогресса в вычислительной технике (если только вы также не используете парольную фразу BIP39). По умолчанию я рекомендую выбирать фразу из 24 слов, но выбор за вами.

![изображение](assets/6.webp)

Затем программное обеспечение предоставит вам вашу фразу для восстановления. Вы должны сохранить ее должным образом, записав на подходящем физическом носителе. Настоятельно рекомендуется не хранить эту фразу на любом цифровом носителе, даже если она зашифрована. Ее следует записать на бумаге или металле в зависимости от хранимой ценности.

Эта фраза имеет первостепенное значение, так как она позволяет получить доступ к ключам вашего кошелька без каких-либо ограничений. Если вы ее потеряете, вы больше не сможете получить доступ к вашим биткойнам, если ваш телефон перестанет работать. Если эта мнемоническая фраза будет украдена, злоумышленник сможет безвозвратно украсть все ваши средства.

Слова в этой фразе должны быть записаны вместе. Не разделяйте вашу фразу! Кроме того, также важно записать каждое слово в определенном порядке вместе с его номером. Перепутанная фраза бесполезна.

Чтобы узнать больше о защите фразы для восстановления, я настоятельно рекомендую прочитать мою специализированную статью на эту тему.

![изображение](assets/7.webp)
Green Wallet затем просит вас подтвердить некоторые слова из вашей фразы, чтобы убедиться, что вы правильно их записали.
![image](assets/10.webp)

Затем вы можете выбрать имя для вашего кошелька, чтобы отличать его от других, если позже вы создадите несколько кошельков. На этом этапе имя не важно, поскольку мы удалим этот кошелек, чтобы проверить валидность мнемонической фразы на следующем шаге.

Вам также будет предложено установить PIN-код. Он используется для блокировки доступа к вашему кошельку. Рекомендуется установить сложный и случайный пароль, особенно для защиты вашего кошелька в случае кражи телефона.

Этот PIN-код никак не связан с самим Bitcoin кошельком. Фактически, только с помощью восстановительной фразы вы сможете восстановить доступ ко всем вашим биткоинам. PIN-код лишь блокирует доступ к вашему кошельку на телефоне. Поэтому, резервное копирование фразы намного важнее, чем резервное копирование этого PIN-кода.

Позже вы можете добавить опцию биометрической блокировки, чтобы избежать ввода PIN-кода каждый раз при использовании. В целом, биометрия намного менее безопасна, чем сам PIN-код. Таким образом, по умолчанию я советую не использовать эту опцию разблокировки.

Вы должны ввести выбранный PIN-код второй раз в приложении Green для его подтверждения.

![image](assets/12.webp)

Поздравляем! Вы завершили создание вашего Bitcoin кошелька.

![image](assets/14.webp)

Если вы хотите добавить к этому Bitcoin кошельку фразу-пароль BIP39, вы должны нажать на три точки в верхнем правом углу экрана при вводе вашего PIN-кода для разблокировки кошелька. Будьте осторожны, я настоятельно советую не использовать фразу-пароль, если вы не понимаете механизмы производных, которые при этом играют. Вы можете потерять доступ к вашим биткоинам.

## Симуляция восстановления вашего Bitcoin кошелька

Прежде чем отправлять биткоины на ваш новый кошелек, крайне важно провести тест восстановления, чтобы убедиться, что ваша резервная копия мнемонической фразы работает. На практике мы удалим кошелек, пока он еще пуст, и попробуем восстановить его, используя только восстановительную фразу, как если бы мы потеряли доступ к нашему телефону.

Помимо проверки валидности фразы, эта практика также позволяет вам попрактиковаться в восстановлении Bitcoin кошелька. Таким образом, если вы когда-либо окажетесь в чрезвычайной ситуации, вы будете точно знать, какие шаги предпринять, чтобы восстановить доступ к вашим средствам.

Для этого, перед удалением вашего кошелька, вам нужно получить справочную информацию, которая позволит вам узнать его позже. Поэтому вы должны скопировать последние 8 символов первого адреса, который вам предложат.
Чтобы получить доступ к этой информации, нажмите на кнопку "Получить". Кошелек отобразит адрес. Запишите последние 8 символов адреса на отдельном листе бумаги. Это соответствует контрольной сумме адреса.

Например, в моем кошельке 8 символов для записи были бы: JTbP4482.

![image](assets/16.webp)

После того как вы записали эту информацию, вы можете удалить ваш кошелек. С главного экрана кошелька нажмите на иконку настроек, затем нажмите на "Отключить".

> "Я хочу еще раз подчеркнуть, что эту операцию нужно выполнять с пустым кошельком, до отправки на него каких-либо биткоинов. В противном случае вы рискуете их потерять."

![image](assets/19.webp)

Затем вы будете перенаправлены на экран разблокировки кошелька. Нажмите на три точки в верхнем правом углу экрана, затем нажмите на "Удалить кошелек" и подтвердите.

![image](assets/21.webp)
Вы сейчас находитесь на главном экране приложения Green Wallet, и доступных кошельков нет. Ваша ситуация аналогична той, как если бы вы потеряли или сломали свой телефон и пытались восстановить свой кошелек только с помощью мнемонической фразы.
Теперь нажмите на "Добавить кошелек", затем "Восстановить кошелек", и, наконец, выберите "Bitcoin".

![изображение](assets/23.webp)

Затем программа спрашивает нас, хотим ли мы восстановить кошелек с помощью QR-кода или мнемонической фразы. В нашем случае это фраза.

Далее нас просят ввести восстановительную фразу. Это та фраза, которую мы записали при создании кошелька. Если вы используете фразу из 24 слов, не забудьте нажать на маленькую кнопку "24".

После ввода всех слов, если программа сообщает вам об ошибке, это означает, что контрольная сумма вашей фразы неверна. В этом случае это означает, что бумажный бэкап вашей мнемонической фразы недействителен. Вам нужно начать этот урок сначала и убедиться, что вы правильно записали фразу, когда она была вам предоставлена.

В противном случае вы можете нажать на "Продолжить".

![изображение](assets/26.webp)

Программа укажет "Кошелек не найден". Это совершенно нормально, поскольку на данный момент мы еще не отправили на него никаких биткойнов. Следовательно, она не может обнаружить никаких транзакций в блокчейне, связанных с этим кошельком.

Нажмите на "Восстановление вручную" внизу экрана, затем нажмите на "Одиночная подпись".

![изображение](assets/28.webp)

Наконец, вам будет предложено дать имя этому кошельку и назначить ему PIN-код. Вы можете дать ему то же имя и PIN-код, что и изначальному кошельку.
Для напоминания, этот PIN-код служит только для разблокировки кошелька в этом приложении и на этом конкретном телефоне. В отличие от восстановительной фразы, он не позволяет воссоздать ваш кошелек в другом программном или аппаратном обеспечении.
![изображение](assets/30.webp)

После проверки PIN-кода вы вернетесь на главную страницу вашего кошелька. Пришло время проверить, работоспособна ли ваша восстановительная фраза, наблюдая за первым производным адресом. Для этого снова нажмите на "Получить", чтобы получить доступ к первому адресу.

Если последние 8 символов точно такие же, как те, которые вы записали в качестве свидетелей на вашей бумаге перед удалением кошелька, то ваша фраза действительна. В моем случае мы видим, что контрольная сумма моего первого адреса действительно равна ранее записанному значению: JTbP4482.

![изображение](assets/32.webp)

Я знаю, что эта практика проверки утомительна, но она абсолютно необходима для обеспечения надлежащей безопасности вашего биткойн-кошелька. Я настоятельно советую вам развивать эту привычку при создании кошелька, будь то на программном или аппаратном обеспечении.

С Green Wallet я использовал первый адрес для выполнения этого процесса. Однако вы также можете взять расширенный публичный ключ (xpub/zpub) или мастер-отпечаток приватного ключа в качестве информации для свидетельства.

## Использование биткойн-кошелька Green Wallet

После настройки и проверки вашего кошелька вы можете начать его использовать.

Для начала я рекомендую настроить параметры вашего кошелька. Для этого нажмите на значок настроек в правом верхнем углу экрана.

- Опция "Отображаемая единица" позволяет вам настроить единицу измерения, используемую в вашем кошельке. Если у вас небольшое количество средств, может быть актуально отображать ваш кошелек в сатах, а не в биткойнах. Сатоши (sat) соответствует одной стомиллионной биткойна: 1 BTC = 100 000 000 сат.
- Опция "Default Fee Amount" позволяет вам настроить размер комиссии, по умолчанию выделенной для ваших транзакций. Чем выше комиссия за виртуальный байт (vbyte), тем быстрее будут подтверждаться ваши транзакции. Позже вы можете изменить этот размер комиссии для каждой транзакции в зависимости от загруженности сети Bitcoin.
- Опция "Biometric Connection" позволяет разблокировать ваш кошелек с помощью отпечатка пальца вместо PIN-кода. В целом, я советую не активировать эту опцию. Биометрические данные намного менее безопасны, чем PIN-код.

![image](assets/34.webp)
По умолчанию Green Wallet присваивает вам аккаунт BIP49 "Nested SegWit" с адресами P2SH (Pay to Script Hash). Несколько лет назад использование этого типа аккаунта было актуально, поскольку не все еще поддерживали нативные адреса SegWit. Сегодня подавляющее большинство сервисов, связанных с Bitcoin, поддерживают SegWit, поэтому использовать аккаунт "Nested SegWit" больше нет необходимости.

Теперь мы создадим новый аккаунт BIP84 "Native SegWit", чтобы воспользоваться всеми его преимуществами, а также иметь адреса P2WPKH (Pay to Witness Public Key Hash). Для этого нажмите на ваш "Legacy SegWit Account", затем на "Add a new account", и наконец на "SegWit Account". После этого вы можете дать название этому аккаунту, если хотите.

![image](assets/36.webp)

В будущем, если вам потребуется создать новые аккаунты в этом кошельке, я рекомендую по умолчанию выбирать аккаунты SegWit V0 BIP84 или SegWit V1 BIP86 (когда они станут доступны).

На главной странице вашего кошелька вы можете видеть ваши различные аккаунты, включая ваш новый аккаунт SegWit.

Далее, работа с приложением Green Wallet очень проста. Чтобы получить биткоины в ваш кошелек, нажмите на кнопку "Receive". Кошелек отобразит адрес для получения. Адрес позволяет получать биткоины в ваш кошелек. Вы можете скопировать его в текстовом формате, чтобы отправить плательщику, или отсканировать QR-код другим Bitcoin кошельком для оплаты на адрес.

![image](assets/38.webp)

Этот тип адреса не указывает плательщику, какую сумму следует отправить вам. Вы также можете создать адрес, который автоматически запросит у плательщика выбранную сумму. Для этого нажмите на "More options" и введите желаемую сумму.

Поскольку вы используете аккаунт SegWit V0 BIP84, ваш адрес должен начинаться с префикса "bc1q". В моем примере я использую кошелек Testnet, поэтому префикс немного отличается от вашего.

Адрес для получения не следует использовать несколько раз. Это плохая практика, которая создает риски для вашей конфиденциальности. По умолчанию Green wallet будет генерировать для вас новый адрес при каждом нажатии на "Receive", если предыдущий уже был использован. Вы также можете нажать на иконку с вращающейся стрелкой, чтобы запросить новый пустой адрес, связанный с вашим кошельком.

> "Совет: Когда вы копируете и вставляете адрес для получения, вам не нужно проверять, что каждый символ адреса верен. На самом деле, адреса включают контрольную сумму для обнаружения маленькой ошибки при вводе. Достаточно проверить первый и последний символы адреса, чтобы убедиться в его действительности."
> На скриншотах ниже вы можете видеть, что я отправил 0.02 btc на мой адрес. Транзакция отображается в Green, сначала как "неподтвержденная", в ожидании включения в блокчейн майнером. Как только транзакция получит несколько подтверждений, вы успешно получите ваши биткоины в свой кошелек.

![image](assets/40.webp)
Если вы хотите отправить биткойны, вам нужно получить адрес получателя, на который вы хотите отправить средства, и нажать на кнопку "Отправить". На следующей странице вам нужно ввести адрес назначения. Вы можете ввести его вручную или отсканировать QR-код, нажав на соответствующий значок. Затем выберите сумму транзакции. Вы можете ввести сумму в биткойнах или сумму в долларах США, нажав на белую двойную стрелку.
![изображение](assets/43.webp)

В центре экрана вы можете выбрать размер комиссии, выделенной для этой транзакции. Вы можете следовать рекомендациям приложения или настроить размер комиссии самостоятельно. Чем выше вы установите комиссию по сравнению с другими транзакциями, ожидающими подтверждения, тем быстрее ваша транзакция будет включена в блокчейн, и наоборот.

Нажмите "Далее". Затем вы попадете на экран с деталями вашей транзакции. Вы можете проверить, что введенный адрес верен, что сумма соответствует тому, что вы хотите отправить, и что размер комиссии корректен.

Чтобы подписать транзакцию и транслировать ее в сеть Bitcoin, переместите зеленую кнопку внизу экрана вправо.

![изображение](assets/46.webp)

Теперь ваша транзакция отображается на панели управления вашего биткойн-кошелька.

## Заключение

Поздравляем! Теперь у вас есть собственный кошелек Bitcoin с самохранением. Ваши биткойны действительно принадлежат вам.

Этот Green Wallet от Blockstream является отличным решением для начинающих с небольшим количеством биткойнов. Как вы видели, им очень легко пользоваться. Однако это все еще горячий кошелек. Если у вас значительное количество биткойнов, я рекомендую использовать аппаратный кошелек.

После того как вы научитесь управлять Green Wallet и поймете, как это работает, вы можете изучить более комплексные решения, такие как Samourai Wallet или Sparrow Wallet.
В заключение, напоминаю вам еще раз, что вы должны абсолютно позаботиться о резервном копировании вашей фразы восстановления. Она предоставляет прямой и неограниченный доступ к вашим биткойнам. Если вы ее потеряете, вы больше не сможете восстановить свои биткойны, если ваш телефон будет потерян, сломан или украден. Любой, у кого есть доступ к этой фразе, может украсть ваши биткойны, и восстановить их будет невозможно.

> Это руководство было создано и принадлежит Bitstack. Bitstack - это биткойн-необанк, базирующийся в Париже, который позволяет осуществлять DCA (постепенное вложение) в биткойны. Руководство написано Лоиком Морелем 15.02.2023. Оно принадлежит им. [Ссылка на оригинальную статью](https://www.bitstack-app.com/blog/installer-portefeuille-bitcoin-green-wallet)