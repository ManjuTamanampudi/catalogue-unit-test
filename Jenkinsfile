

def configMap= [
    project: "roboshop",
    component: "catalogue"
]
echo " calling piplines in groovy"
if(env.BRANCH_NAME.equalsIgnoreCase('main')){
    echo " cheking later"
}
else{
    nodeJSEKSPipeline(configMap)
}
