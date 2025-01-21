# titulo h1
##  titulo h2
### titulo h3
#### titulo h4

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

  ```
  
    public static function rellenarPresentaciones($id_sucursal)
    {
        $presentaciones = Presentacion::where('id_sucursal', $id_sucursal)
            ->orderBy('nombre', 'ASC')
            ->get();

        return response()->json($presentaciones);
    }
  ```

- [x] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
