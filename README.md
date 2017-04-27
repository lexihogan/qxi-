# qxi-using UnityEngine;
using System.Collections;

public class ExampleClass : MonoBehaviour {
    void Example() {
        if (Application.platform == RuntimePlatform.OSXEditor)
            Debug.Log("Do something special here!");
        
    }
}
mport javax.script.*;

public class EvalScript {
    public static void main(String[] args) throws Exception {
        ScriptEngineManager manager = new ScriptEngineManager();
        ScriptEngine engine = manager.getEngineByName("nashorn");

        // evaluate JavaScript code
        engine.eval("print('Hello, World')");
    }
}
Example 2 - Evaluating a Script Fil// create File object
        File f = new File("test.txt");

        // expose File object as a global variable to the engine
        engine.put("file", f);

        // evaluate JavaScript code and access the variable
        engine.eval("print(file.getAbsolutePath())");
    }
}
// create File object
        File f = new File("test.txt");

        // expose File object as a global variable to the engine
        engine.put("file", f);

        // evaluate JavaScript code and access the variable
        engine.eval("print(file.getAbsolutePath())");
    }
}
