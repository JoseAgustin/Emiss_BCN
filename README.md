# Emiss_BCN
Tijuana-Rosarito-Tecate emissions

## Descripción

Inventario de emisiones para modelación de calidad del aire con **WRF-Chem** para la región de **Baja California Norte** (Tijuana-Rosarito-Tecate).
Incluye emisiones de contaminantes criterio (CO, NOₓ, SO₂, PM₂.₅, PM₁₀, COV) organizadas en sectores: 
fuentes móviles, fuentes de área y fuentes de punto.

## Estructura del repositorio

```
Emiss_BCN/
├── 01_datos/       # Datos de entrada del inventario de emisiones
├── README.md
└── .gitignore
```

## Requisitos

- Fortran 90/95 o superior
- Bibliotecas NetCDF (libnetcdf, libnetcdff)
- WRF-Chem (para usar las emisiones generadas)
- Python 3.x (para scripts de pre/post-procesamiento, opcional)

## Uso

1. Preparar los datos de entrada en `01_datos/`
2. Compilar los programas Fortran
3. Ejecutar los scripts en orden secuencial
4. Las salidas son archivos NetCDF listos para WRF-Chem

## Referencia

Si utiliza este código en su investigación, por favor cite:

> García-Reynoso, J.A. et al. Inventario de Emisiones de **Baja California Norte** (Tijuana-Rosarito-Tecate) para modelación de calidad del aire.
> Centro de Ciencias de la Atmósfera, UNAM. https://github.com/JoseAgustin/Emiss_BCN

## Autor

**José Agustín García Reynoso**  
Centro de Ciencias de la Atmósfera, UNAM  
📧 agustin@atmosfera.unam.mx  
🔗 https://github.com/JoseAgustin

## Licencia

Ver archivo [LICENSE](LICENSE) para detalles.
