# Skewed container react (sc-react)
A react library for creating non-rectangular/slanted container divs.

### Installation
```
npm install --save sc-react
```
or 
```
yarn add sc-react
```

### Adding sc-react
```
import SkewedContainer from 'sc-react';
```
### Example
```
export default class extends React.Component{
    render(){
        return(
            <div>
                <SkewedContainer
                top="left || right"  
                bottom="left || right"
                bgColor="blue"  
                >
                    {/* YOUR CODE HERE */}
                </SkewedContainer>
            </div>
        )
    }
}
```

### Properties
```
SkewedContainer.propTypes = {
    className: PropTypes.string,
    style: PropTypes.object,
    top: PropTypes.string,
    bottom: PropTypes.string,
    noMargin : PropTypes.bool,
    bgColor: PropTypes.string
}
```