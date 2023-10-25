# GSTInvoice


 <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">
 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

*********************----HTML CODE -----********************************

<div class="card text-center" >
                <!-- style="background-color: lightskyblue;" -->
                <div class="card-header " >
                    Tax Invoice 
                    </div>
                    <div class="card-body">
    
                        <form id="myForm">
                               <div class="row">
                                   <div class="col-0">
                                       <div class="input-group mb-0">
                                           <span class="input-group-text">Invoce No</span>
                                           <input type="text" id="invno" class="form-control" placeholder="Invoice No." style="max-width: 200px;" >
                                           <span class="input-group-text">Invoce Date</span>
                                           <input type="date" id="invdt" class="form-control" placeholder="Invoice Date" style="max-width: 200px;" >
                                           <span class="input-group-text">Ref No</span>
                                           <input type="text" id="refno" class="form-control" placeholder="Ref No." style="max-width: 200px;" >
                                           <span class="input-group-text">Ref Date</span>
                                           <input type="date" id="refdt" class="form-control" placeholder="Ref Date" style="max-width: 200px;" >
                                       </div>
                                   
                                   </div>
                               </div>
       
                               <div class="row">
                                   <div class="col-0">
                                       <div class="input-group mb-0">
                                           <span class="input-group-text">Party Name</span>
                                           <input type="text" id="partyname" class="form-control" placeholder="Party name" style="max-width: 880px;" >
                                       </div>
                                   </div>
       
                               </div>
                               <div class="row">
                                   <div class="col-0">
                                       <div class="input-group mb-0">
       
                                           <span class="input-group-text" >Address</span>
                                           <input type="text" id="Address" class="form-control" style="max-width: 300px;" placeholder="Address" >
                                           <input type="text" id="Address2" class="form-control" style="max-width: 300px;" placeholder="Area" >
                                           <input type="text" id="Address3" class="form-control" style="max-width: 300px;" placeholder="city" >
       
                                       </div>
                                   </div>
       
                               </div>
                             
       
                               <div class="row">
                                   <div class="col-0">
                                       <div class="input-group mb-0">
                                           
                                               <span class="input-group-text" >GSTNO</span>
                                               <INPut class="form-control" id="gstno" placeholder="GSTNO" style="max-width: 310px;"></INPut>
                                               <span class="input-group-text" >State</span>
                                               <select name="states" id="states"  >
                                               <option value="TS">Telangana</option>
                                               <option value="saab">Andhara pradesh</option>
                                               </select>
                                       </div>
                                   </div>
       
                               </div>
                               <div class="row">
                                   <div class="col-0">
                                       <div class="input-group mb-0">
                                           
                                       </div>
                                   </div>
       
                               </div>
                               <div class="row">
                                   <div class="col-0">
                                       <div class="input-group mb-0">
                                       </div>
                                   </div>
       
                               </div>
                               <div class="row">
                                   <div class="col-0">
                                       <div class="input-group mb-0">
                                       </div>
                                   </div>
       
                               </div>
       
       
                      
                           </form>
                       
                           
                       </div>
                       <hr>
                       


                       <div class="card-body1">

                        <table class="table table-bordered">
                            <thead class="table-dark ">
                              <tr>
                                <th scope="col">No</th>
                                <th scope="col" class="text-center">Items</th>
                                <th scope="col" class="text-center">HSNCODE</th>
                                <th scope="col" class="text-center">Qty</th>
                                <th scope="col" class="text-center">Rate</th>
                                <th scope="col" class="text-center">Amount</th>
                                
                              </tr>
                            </thead>
                            <tbody>
                              <tr>
                                <th scope="row">1</th>
                                <td><input type="text" class="form-control "></td>
                                <td><input type="text" class="form-control "></td>
                                <td><input type="text" class="form-control "></td>
                                <td><input type="text" class="form-control "></td>
                                <td><input type="text" class="form-control "></td>
                                
                            </tr>
                       
                           
            
                            </tbody>
                        </table>


                       </div>



                       <div class="Addtion">
                        <div class="row">
                            <div class="col-0">
                                <div class="input-group mb-0">
                                    <span class="input-group-text" style="width: 150px;">Taxable Value</span>
                                    <input type="text" id="invno" class="form-control text-end" placeholder="TaxableValue" style="max-width: 600px;" >
                                </div>
                            </div>

                        </div>

                        <div class="row">
                            <div class="col-0">
                                <div class="input-group mb-0">
                                    <span class="input-group-text" style="width: 150px;">IGST</span>
                                    <input type="text" id="IGST" class="form-control text-end" placeholder="IGST" style="max-width: 600px;" >
                                </div>
                            </div>

                        </div>
                        <div class="row">
                            <div class="col-0">
                                <div class="input-group mb-0">
                                    <span class="input-group-text" style="width: 150px;">CGST</span>
                                    <input type="text" id="CGST" class="form-control text-end" placeholder="CGST" style="max-width: 600px;" >
                                </div>
                            </div>

                        </div>
                        <div class="row">
                            <div class="col-0">
                                <div class="input-group mb-0">
                                    <span class="input-group-text" style="width: 150px;">SGST</span>
                                    <input type="text" id="SGST" class="form-control text-end" placeholder="SGST" style="max-width: 600px;" >
                                </div>
                            </div>

                        </div>
                        <div class="row">
                            <div class="col-0">
                                <div class="input-group mb-0">
                                    <span class="input-group-text" style="width: 150px;">Round off (+/-)</span>
                                    <input type="text" id="rnd" class="form-control text-end" placeholder="Round off" style="max-width: 600px;" >
                                </div>
                            </div>

                        </div>
                        <div class="row">
                            <div class="col-0">
                                <div class="input-group mb-0">
                                    <span class="input-group-text" style="width: 150px;">Invoice Amount</span>
                                    <input type="text" id="INVAMT" class="form-control text-end" placeholder="Invoice Amount" style="max-width: 600px;" >
                                </div>
                            </div>

                        </div>
                       </div>


                       <div class="card-footer">
                       <Label>Statu......</Label>
                       </div>
            </div>


*****************************  CSS CODE *****************************************************
*{

    padding: 0;
    margin: 0;
    font-family: Verdana, sans-serif;
    /* font-weight: bold; */
    
    
}
 

.maindiv{

    width: 80%;;
    margin: auto;
    height: 100vh;
   
 
}

.maindiv .card {

    width: auto;
    height: 100vh;
    /*background-color:#b0b0e8; background-color: rgb(186, 220, 216); */

   
}

.card-footer{


    text-align: left;
}
.form-control{

    
    margin-right: 5px;
        
    
}
.row{

    margin-top: 5px;
}

.Addtion{

    margin-left: 70%;
    
    
}
.card-body1{

    margin-top: 5px;
}

.hr{

    margin-top: 0px;
}


            

 
