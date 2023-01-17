## Array

- static
- have to declare num of variables

```
type var_name[num_of_elements];
type var_name[] = {element_1, element_2, ...};

var_name[index]

sizeof(var_name)/sizeof(var_name[0])

for(type i: var_name)
{
  cout << i;
}
```

## Vector

- dynamic

```

vector<type> var_name(num_of_elements);
vector<type> var_name() = {element_1, element_2, ...};

var_name(index).at
var_name[index]

var_name.push_back()
var_name.pop_back()

var_name.insert(var_name.being()+index_number, value)
var_name.erase(var_name.being()+index_number)
```


## 2D array

```
type var_name[rows][cols];
int mat[2][4];


type var_name[][] = { 
                      {element_1, element_2},
                      {element_3, element_4} 
                    }

rows = sizeof(mat)/sizeof(mat[0])
cols = sizeof(mat[0])/sizeof(int)

```





















