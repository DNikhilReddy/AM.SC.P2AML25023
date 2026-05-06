<!Doctype html <h1>AFFORDMED</h1><i class="fa fa-hashtag" aria-hidden="true"></i>
<i class="fa fa-wheelchair" aria-hidden="true">
    <i class="fa fa-remove" aria-hidden="true">
{
    function notify_all(student_ids: array, message: string):
        for student_id in student_ids:
        send_email(student_id, message)
        save_to_db(student_id, message)
        push_to_app(student_id, message)
}   </i>
</i>
<SELECT></SELECT>FROM notifications
WHERE studentID=1042 AND isRead = false
ORDER BY createdAt DESC;
