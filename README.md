# graphql-node
graphql with node express

npn install
node server.js
open localhost:4000/graphql
pass this object in query on browser
'query getSingleCourse($courseID: Int!) {
    course(id: $courseID) {
        title
        author
        description
        topic
        url
    }
}'

pass course id in query variable
{
    "courseID":1
}
