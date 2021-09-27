Hello
Hello
Hello
Hello
Hello
Hello






//Welcome to my README!
import React, {Component} from "react";

class App extends Component{
    constructor(props){
        super(props);
        
        this.state = {
            name = "Thomas Madden",
            knowsReact : true,
            diligent : true,
            hairColor : "Red",
        }
    }

    render(){
        return(
            <div>
                <p className="intro">
                    Hello! my name is {this.state.name} and I {this.state.knowsReact ? 
                    "am" : "am not"} well-versed in React. 
                </p>
                <p className="intro">
                    I am a {this.state.diligent ? "hard worker " : "lazy oaf "}with {this.state.hairColor} hair.
                </p>    
            </div>
            /*In case you were wondering...this prints out:
                Hello! my name is Thomas Madden and I am well-versed in React.
                I am a hard worker with red hair. 
            */
        )
    }
}