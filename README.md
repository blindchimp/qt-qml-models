Qt QML Models
=============

Additional data models aimed to bring more power to QML applications by using useful C++ models in back-end.

* `QQmlObjectListModel` : a much nicer way to expose C++ list to QML than the quick & dirty `QList<QObject*>` property . Supports all the strong model features of `QAbstractListModel` while showing the simple and well know API of QList.

* `QQmlVariantListModel` : a dead-simple way to create a dynamic C++ list of any type and expose it to QML, way better than using a `QVariantList` property.
