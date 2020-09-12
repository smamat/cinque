This project was created to demonstrate the use of Redux in React

# Components

The app consists of presentational and container components. The presentational components concern with displaying the data on the page whereas the container components handles the data logic.

## Presentational components

  `┌---- CourseList --------┐`                                                              
  `|                        |`           
  `|  ┌--- DishList ----┐   |`         
  `|  | -bruschetta     |   |`              
  `|  | -insalata       |   |`      
  `|  | -....           |   |`    
  `|  └-----------------┘   |`      
  `|                        |`       
  `|  ┌--- DishList ----┐   |`      
  `|  | -spaghetti      |   |`      
  `|  | -penne          |   |`      
  `|  | -....           |   |`      
  `|  | -....           |   |`      
  `|  └-----------------┘   |`     
  `└------------------------┘`    


### DishList

This component presents a list of dishes

### CourseList

This component displays a list of courses

### ChoiceList

This component provides a list of dishes the user selected from the menu

## Container Components

