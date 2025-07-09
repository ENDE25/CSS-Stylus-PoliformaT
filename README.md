# Poliformat Dark Theme - UPV  

Un tema oscuro personalizado para Poliformat (Sakai), la plataforma educativa de la **Universitat Politècnica de València (UPV)**.  

## Características principales  
- Modo oscuro con tonos rojos/negros institucionales  
- Optimización de espacio (elimina elementos innecesarios)  
- Calendario más legible con eventos resaltados  
- Prefijos identificativos para asignaturas  
- Mejor organización visual de widgets  

## Instalación con Stylus  

1. Instala la extensión [Stylus](https://github.com/openstyles/stylus) para [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) o [Firefox](https://addons.mozilla.org/es/firefox/addon/stylus/)  
2. Haz clic en el icono de Stylus > "Gestionar estilos"  
3. Crea un nuevo estilo y pega el código CSS  
4. Configura para aplicar a: ``poliformat.upv.es``  

## Personalización  

Para cambiar prefijos de asignaturas:  
```css
#site-list-pinned-item-CODIGO_ASIGNATURA > div > div > a::before {
  content: "SIGLAS: ";
  color: #d31d12;
}
``` 

Para ajustar alturas:  
```css
.Mrphs-toolBody--sakai-synoptic-announcement {
  max-height: 330px;
}
``` 

## Notas importantes  
- Puede dejar de funcionar si Poliformat actualiza su estructura. Última actualización: `10 de julio de 2025`

## Capturas de Pantalla
**Antes:** ![image](https://github.com/user-attachments/assets/74823af2-40fd-4c54-bbf9-0ad3ea9b6f57)
**Después:** ![image](https://github.com/user-attachments/assets/ecc7168e-66e3-458c-9ab1-35bd28f416e7)

**Antes:** ![image](https://github.com/user-attachments/assets/07cf8a54-e88c-44b4-a21e-e334e41bf71e)
**Después:** ![image](https://github.com/user-attachments/assets/12773c48-dd57-4088-8e5f-08bef05bf8ec)




  
```
