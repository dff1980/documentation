# Информация о текущих курсах по линейке SUSE Rancher
В настоящий момент существует два варианта прохождения обучения:
* [Платные курсы предоставляемые компанией SUSE](https://www.suse.com/training/course/)
* [Курсы предоставляемые сообществом](https://community.suse.com/all-courses)

Доступные курсы предоставляемые компанией SUSE покрывают все продукты компании (исключения, продукты только что появившиеся в портфолио, для которых доступны только внутренние курсы компании)

Ниже рассмотрим курсы доступные по продукту SUSE Rancher, и возможности по сертификации.

Дорожная карта обучения от компании SUSE по обучению SUSE Rancher:

```mermaid
flowchart TB
style id10 fill:#90EBCD
style id11 fill:#90EBCD
style id1 fill:#30BA78
style id2 fill:#30BA78
style id3 fill:#30BA78
style id4 fill:#30BA78
style id5 fill:#30BA78
style id6 fill:#30BA78
style id7 fill:#30BA78


  id10([Ранее не встречал K8S]) --> id1([KUB201 Kubernetes Administration 2 days])
  id11([знаком с K8S]) --> id20[Направление]
  id1 --> id20
  id20 --> |Администрирование| id2(["RAN201 SUSE Rancher Operations 3 days#starf;"])
  id20 --> |Развертывание| d30
  subgraph d30 ["SUSE Rancher Deployment eLearning Modules#starf;"]
    id3([Deploy RKE])
    id4([Deploy RKE2 and K3s])
    id5([Deploy SUSE Rancher])
    id6([Deploy RKE with SUSE Rancher])
    id7([Backup and Restore RKE and RKE2 Clusters])
  end
id40["#starf; - Доступна сертификация"]
```

Если говорить о сертификации SCA in SUSE Rancher 2.6, то от компании SUSE доступен курс [RAN201 SUSE Rancher Operations](https://www.suse.com/training/course/ran201v2.6) предназначенный для подготовки к этому экзамену, [курс](https://community.suse.com/courses/5804003/content) от сообщества более общий он включает в себя так-же части из курсов по развертыванию RKE, однако в нем пропущены некоторые части, к которым подготовится придется самостоятельно.

Если пользоваться курсами от сообщества, то перед экзаменом, настоятельно рекомендуется просмотреть список тем курса от компании SUSE и подтянуть, те темы, в которых есть пробелы.
