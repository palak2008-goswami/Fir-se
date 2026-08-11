#functional requirements
FR-01: User shall be able to create an account.
FR-02: Industry shall be able to create a scrap listing.
FR-03: User shall be able to upload images of the material.
FR-04: System shall store material information.
FR-05: System shall allow buyers to browse available materials.
FR-06: System shall allow buyers to search and filter listings.
FR-07: System shall provide AI-based material analysis.
FR-08: System shall recommend potential reuse opportunities.
FR-09: System shall match material listings with suitable buyers.
FR-10: Buyer shall be able to express interest in a listing.
FR-11: Seller and buyer shall be able to negotiate/request a transaction.
FR-12: System shall track transaction status.
FR-13: System shall support logistics/pickup workflow.
FR-14: System shall calculate environmental impact metrics.
FR-15: Admin shall be able to manage users and listings.
#non functional requirements 
NFR-01: System should be secure.
NFR-02: System should be scalable.
NFR-03: API responses should have reasonable latency.
NFR-04: User data should be protected.
NFR-05: Uploaded files should be validated.
NFR-06: System should provide appropriate error handling.
NFR-07: AI predictions should provide confidence information where applicable.
# MVP requirements 
-Authentication
-Seller profile
-Buyer profile
-Scrap listing
-Image upload
-Browse/search listings
-Basic matching
-Buyer interest/request
-AI image analysis
-Price estimation
-Logistics
-Impact engine
-Fir Se Scout
#USER'S REQUIREMENTS:-
1) Seller/waste generator 
-Create account
-Create company profile
-Create scrap listing
-Upload material images
-Edit listing
-Delete listing
-View interested buyers
-Accept/reject requests
-Track transactions
-View impact generated
2)buyer user
 - Create account
-Create company profile
-Define material requirements
-Browse listings
-Search/filter
-View material details
-Send interest/request
-Track accepted transactions
3) logistic partner 
-View pickup requests
-Accept delivery jobs
-Update pickup status
-Update delivery status
4)ADMIN
-Manage users
-Verify companies
-Manage listings
-Handle reports
-Monitor transactions
-Manage categories
-View analytics 

ROLE HIERARCHY:


                    FIR SE
                       │
          ┌────────────┼────────────┐
          ↓            ↓            ↓
       Seller        Buyer       Admin
          │
          └──────────────┐
                         ↓
                  Logistics Partner
