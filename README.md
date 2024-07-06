'@override
  Widget build(BuildContext context) {  
    return MaterialApp(
      home: Scaffold(
        body: EassyRadio(
                titles: const ['Dli', 'Non Dli'],
                values: const ['dli', 'no dli'],
                getData: (e){
                  // your selected output
                  print(e);
                }
            );,
      ),
    );
  }'
