# Poliformat Dark Theme - UPV  

Un tema oscuro personalizado para Poliformat (Sakai), la plataforma educativa de la **Universitat Politècnica de València (UPV)**.  

## Capturas de Pantalla

| Antes | Después |
|-------|---------|
| ![Antes](https://github.com/user-attachments/assets/74823af2-40fd-4c54-bbf9-0ad3ea9b6f57) | ![Después](https://github.com/user-attachments/assets/ecc7168e-66e3-458c-9ab1-35bd28f416e7) |
| ![Antes](https://github.com/user-attachments/assets/07cf8a54-e88c-44b4-a21e-e334e41bf71e) | ![Después](https://github.com/user-attachments/assets/12773c48-dd57-4088-8e5f-08bef05bf8ec) |

## Características principales  
- Modo oscuro con tonos rojos/negros institucionales  
- Optimización de espacio (elimina elementos innecesarios)  
- Calendario más legible con eventos resaltados  
- Prefijos identificativos para asignaturas  
- Mejor organización visual de widgets

_También se puede instalar desde el [sitio web del estilo](https://userstyles.world/style/23410/dark-modern-poliformat)_

## Cómo Instalarlo  

1. Instala la extensión [Stylus](https://github.com/openstyles/stylus) para [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) o [Firefox](https://addons.mozilla.org/es/firefox/addon/stylus/)  
2. Con la página de PoliformaT abierta haz clic en el icono de Stylus > "Buscar"  
3. Aparecerá el estilo "Dark Modern PoliformaT". Al hacer "click" se instalará automáticamente

## Personalización  
Para cambiar prefijos de asignaturas:  
```css
#site-list-pinned-item-CODIGO_ASIGNATURA > div > div > a::before {
  content: "SIGLAS: ";
  color: #d31d12;
}
``` 
>[!WARNING]
Puede dejar de funcionar si Poliformat actualiza su estructura. Última actualización: `10 de julio de 2025`


