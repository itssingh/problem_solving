## Initialising 2-D vector having n rows and m columns
* vector<vector<int>> arr(n);
    for (int i = 0; i < n; i++) {
        arr[i].resize(m);

        for (int j = 0; j < m; j++) {
            cin >> arr[i][j];
        }

        cin.ignore(numeric_limits<streamsize>::max(), '\n');
    }
 Here **cin.ignore(numeric_limits<streamsize>::max(), '\n')**, ignores the rest of the current line, up to '\n' or EOF - whichever comes first.
 * vector<vector<int>> arr( n , vector<int> (m)); 
    for(int i = 0; i < n; i++){
        for(int j = 0; j < m; j++){
            cin>>arr[i][j];
        }
    }

## Passing vector as reference

