# Javascript Templating
A fast and efficient technique to render client-side view templates with Javascript by using a JSON data source.
## Mustache
A logic-less template syntax.It is often considered the base for JavaScript templating and It can be used for HTML, config files, source code and anything. It works by expanding tags in a template using values provided in a hash or object. It is called as *logic-less* because there are no if statements, else clauses, or for loops.
## Mustache-Express
If you intend you use mustache with Node and Express, you can use mustache-express. Mustache Express lets you use Mustache and Express together easily.

# Flexbox
**Properties for the Parent (flex container)**
![image!](https://css-tricks.com/wp-content/uploads/2018/10/01-container.svg)
1- *display* property : so when you give it a value flex (display : flex) then you enables a flex content for all the direct children.
2- *flex-direction* property : defining the direction flex items are placed in the flex container and it has many values.
3- *flex-wrap* property : You can change that and allow the items to wrap as needed with this property.
4- *flex-flow* property : This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes. The default value is row nowrap.

**Properties for the Children (flex items)**
![image!](https://css-tricks.com/wp-content/uploads/2018/10/02-items.svg)
1- *order* property : controls the order in which they appear in the flex container.
2- *flex-grow* property : the ability for a flex item to grow if necessary. It accepts a unitless value that serves as a proportion.
3- *flex-shrink* property : the ability for a flex item to shrink if necessary.
4- *flex-basis* property : defines the default size of an element before the remaining space is distributed.


There are a lot of properties related to flex box you can check them [here](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).