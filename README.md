# get-any-name-to-drawer

 key: _scaffoldKey,   //this is key to provied in scaffold 
 leading: InkWell(    // this is given in lable of app bar you can put any were in ontab of any button
              onTap: () {
                _scaffoldKey.currentState!.openDrawer();
              },
