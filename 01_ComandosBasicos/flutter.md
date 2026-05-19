# 馃惁 Flutter Cheat Sheet

## 馃摝 Widgets de Posicionamiento y Agrupaci贸n

- **Center**: Centra su hijo en relaci贸n al widget padre.
- **Align**: Alinea su hijo dentro de s铆 mismo.
- **ConstrainedBox**: Impone reglas adicionales de tama帽o.
- **Container**: Widget com煤n para pintado, padding y tama帽o.
- **Padding**: A帽ade espacio interno.
- **Transform**: Aplica transformaciones visuales.
- **SizedBox**: Caja de tama帽o fijo.

## 馃П Widgets con M煤ltiples Hijos

- **Column**: Orden vertical de hijos.
- **Row**: Orden horizontal de hijos.
- **Stack**: Superposici贸n de widgets.
- **GridView**: Cuadr铆cula de widgets.
- **ListView**: Lista con scroll vertical.
- **Wrap**: Similar a Row/Column pero con envolvimiento.
- **Table**: Disposici贸n en filas y columnas.
- **SingleChildScrollView**: Scroll para un solo hijo.
- **CustomScrollView**: Scroll avanzado con Slivers.

## 馃洜 Widgets Comunes

- **AppBar**: Barra superior de herramientas.
- **Buttons**: `ElevatedButton`, `FilledButton`, `OutlinedButton`, `TextButton`.
- **Icon**: Muestra un 铆cono.
- **Image**: Muestra im谩genes desde URL o assets.
- **Scaffold**: Estructura base de pantalla.
- **Text**: Muestra texto.
- **Form / FormField**: Formularios y validaciones.
- **Theme**: Aplicaci贸n de temas.

## 馃搷 Navegaci贸n

```dart
Navigator.push(
  context,
  MaterialPageRoute(builder: (context) => SecondRoute()),
);
```

## 馃帥 Gestores de Estado

- **Provider** (recomendado para empezar)
- **Riverpod**
- **InheritedWidget / InheritedModel**
- **BLoC / Cubit**
- **GetX** (muy popular, no recomendado para principiantes)
- **MobX**, **Get_it**

## 馃枼锔?Comandos CLI 煤tiles

```bash
flutter create .
flutter run
flutter build apk
flutter doctor
flutter clean
```

## 馃 Conceptos Clave

- `Widget`, `BuildContext`, `StatefulWidget`, `StatelessWidget`
- `HotReload` vs `HotRestart`
- Todo inicia en `main()`
