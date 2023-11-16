
# Turistas de Sabores 
Trabajo final de Programación front-end en UTN-BA como parte de BA Multiplica 2023. 

El código cuenta con el desarrollo explícito de la presentación de una página de recomendaciones gastronómicas de restaurantes, bares, cafeterías y heladerías de Buenos Aires. El proyecto parte de la idea de generarle una página web a mi usuario de instagram @turistasdesabores destinado a dicho fin. 



## Acceder al repositorio
 https://github.com/AbrilFrega/turistasfinal.github.io 


## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Pink | ![#ff99cc](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAAAXNSR0IArs4c6QAAAhhJREFUOE+llP1Lk1EUxz9zTptYa+Zbms2mFUiEFEVQUVQkQf9g/0K/BoWS0AtB9AIhIphruOUkTa3HrOV0u3F277O7+zzPgvL8sj33nPM9r98TU48WFTdHobuDhnzZgSc52Kvat+C/W6dgrAdiRvGzAi+KxNSDd4rJQbhwHNrbtLamYH4dXq9EAwbt92vwplT30YAid7KQTVuAX3vwvACfPRd06DBORUrB0hY8W67bWcD0IQ2aTlqA1R8w/cmWnojD3SwMH7E2m2V4mgfvdwBQPif64PIwdMS1Q7UGc+vwtqS/RXd+ANpM48r78LIAy98bAWyG/pMM6LQ02zjtVHQ5EuR6BpLt0cGMfxgwZUo/1lR60YNkAvq6bKkr2/B4KTS0MKCYyDpcG4FOk42MzV8P0Xu7MJODb7pvzRINKBZXTsC5ftsv36tS1Suy8DUE5k45qI6aqKzIx029Ti2kdYbiMDUOmZTrWvBgOvcfgBeHYHIA4oY9PoSs0oc1eL/6DyWH2ODvhPk1vA2xyGGKHy+qd6VtrW1miLzN5EMHJNzDS8KGfluqn40A3shAV0KDywGZW9MTbxIXcCTlOh2IelLqvXEY7LbxgmWJzdQYSI99CdxOm+HVkzDRaznc6nyNHnU5Lbu5sAGvivUQGvBsr2ZGp7kyLfrTyCrIot2qPsaLG8TUw3nF7Sz0/OUORrHo/hn3WGyVYTbPHxf6/hZvNkl1AAAAAElFTkSuQmCC) #ff99cc |
| Fucsia | ![#f8f8f8](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAAAXNSR0IArs4c6QAAAdFJREFUOE+l1c2rjVEUBvDfIWIgHwNJmRpcxcTM7BpISSgiA0IyYILyVTJBijvwUQYSRWKARAZi5g9gYMCQDEwoKRGvlrNeZ599ztGNPXr32ms9ez1rr2e9nWa8aVzDIr31HKvxubDVnzewBVPy4B1202k0jcM4jpl5+B0XcGAEYO3/BUdxvgWMuNvYiE6CvMcuPK5Ax+lj9AM3sa3r180w1hjuYEkB8AzrCuqzcBcri4tfYBNe14Cx34PTmJOgXzGBY7k/lWWYnvsPGXOvl0Qvw9Z2HVsxNQ1vsR2zcRnzR1yW5kHAxUl9WXpEQR5hAZYXtidYNfhog4DhsxmXMC8DfmbN2gd7k7V9NVnA8DuHfZhWBX3CkaQ/pKuGZxiOw140WiRqvHNEf/a1zTCfB1hTtEjU8yHW/gvgCRzCjCo4WukM4nzSlGs1xKPEqnQ7oKKhlOvaBc2nCdgqpLVtGBwgg49yEvsLqjlFfkNewcIE/5adEEOhWP2AMbLKoP+SXlCNybKiUENQLWmFz31EjdtVzc5ehhdT6K2GR42v9ZWmozdD43u7N3QBd+As5v69Pn+yqlX0EQdxNQDHmsYtLC1o1HOw7regHj7tsIjzl91fwi8pjKBMyUmChgAAAABJRU5ErkJggg==) #ff00ff|
| White | ![#00b48a](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAAAXNSR0IArs4c6QAAACxJREFUOE9j/P///38GKgLGUQMpDs3RMKQ4CBlGw3A0DMkIgdFkQ0agoWkBAE8+T8Xjo4rXAAAAAElFTkSuQmCC) #ffffff|
| Black | ![#00d1a0](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAAAXNSR0IArs4c6QAAAodJREFUOE+lVb9LanEU/1gkNkjpICK0Oijk4uamQwgRJShFg2IhDrmooBmIS0mQDmnQIKJQSA0lkThEbf0BOjjUWDS4KIggivk438f94r3e9+jxznS/58fnez7ne865CrvdPimVSlhZWYEgr6+vcDqd6PV6XCf9uLq6ws7ODubm5pjp8/MTgUAACgCTeDyOZDKJxcVFZhyNRsjlcohEIrKAUv9+v49EIoHz8/PfgBR1c3MDt9sNhYJUwNfXF/b391Gv10Wgdrsd04zG4zGur6/h9XqZHwc0mUy4vb2F2WzmAC8vL9jc3OTU1Wo17u7u4HA4+MWNRgMejwdvb29iQDoFg0Gk02ksLy8z42AwQDabxdHRETufnJywMiiVSnZut9ss5v7+nifBMxQ05XIZu7u7mJ+fZ6qPjw/4fD4sLS3h8vISOp1O9jIhfgbQaDQy6haLhflMJhPUajXo9XpYrVaue3p6wtra2syjzQCSx/b2Ni4uLqDValnA9/c3q5nwYO/v76y2rVbrZ4DklclkEAqFsLCwIArqdrs4PDxk9OVENkNylHtRahGq8d7eniyYqG3kPB4eHrC+vs6pUj0fHx+xsbHx74CpVAqxWAwqlUoUTK10enoKsv+YsnQa6FFIpHMrnSJZytLaEc3n52cGKEyIoHO5XDMLZOZRjo+PEQ6HOVVhixBgoVCAwWBg4MPhkHUCLYVpEQHSypoO+q/RI6pUE5vNxqeBqE7TIp9qtQqqsSDS3ckzzOfzbNCFGf7T+tra2hLNNPUmNfnBwQG7gwH6/X6cnZ1Bo9H8tT5CVtIp6nQ6iEajKBaLUJhMpkmlUsHq6iqnId2D0n4j6uQjLAuyN5tN9kv4Bd4ZQWkGF2QDAAAAAElFTkSuQmCC) #000000 |

