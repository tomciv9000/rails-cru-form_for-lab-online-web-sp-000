rails g model Arti name:string genre:string bio:text --no-test-framework


rails g resource Artist name:string bio:text  --no-test-framework

rails g resource Genre name:string --no-test-framework

rails g resource Song name:string artist_id:integer genre_id:integer --no-test-framework