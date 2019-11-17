# Docs for Delphi

## FireDac

* Query DB
    ```
    db.DataModule1.FDQuery1.SQL.Clear;
    db.DataModule1.FDQuery1.SQL.Add;
    db.DataModule1.FDQuery1.ParamByName('name').AsString;
    db.DataModule1.FDQuery1.Active;
    db.DataModule1.FDQuery1.Open;
    ```

## ADO

* Query DB
    ```
    ADOQuery1.Close;
    ADOQuery1.SQL.Clear;
    ADOQuery1.SQL.Add
    ADOQuery1.Open;
    ```

## Password Hash

* Uses
    ```
    System.Hash

    THashMD5.GetHashString(password);
    ```
