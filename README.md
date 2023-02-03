# African_hack
African haha katone

Пока собирались, Африканцы набили лб плотненько, уже не по 0,5)) тут регаемся https://zindi.africa/competitions/zindi-new-user-engagement-prediction-challenge 

базлайн я закинул 

скиньте еще мне ники, я нас в тиму добавлю работаем короче

О задаче:

Кароч задача бинарной классификации, уйдет ли пользователь через месяц с сайта зинди или нет, по его активности

для ID_users нужны метки классов активности

Метки его активности через в течение месяца, нет никакакой активности 0

На месяцах стоят маски (разобраться равные ли маски в файлах)

Активность - регистрация и вот это:

Лежит в user_activity.Title.unique()

'$identify', 'Signed Up', 'Viewed All Competitions', 'Viewed All Discussions', 'Viewed All Learning Pages', 'Confirmed Email', 'Joined Competition', 'Downloaded Competition Datafile', 'Signed In', 'Updated Discussion', 'Joined Team', 'Created Submission', 'Viewed Discussion', 'Updated Submission', 'Signed Out',

'badge_OCZE', 'Updated Profile', 'Viewed FAQ', 'Viewed All Jobs', 'Created Team', 'Invited Member To Team', 'Updated Team','Updated Comment', 'Updated Discussion Team Participants',

'badge_HYIO', 'badge_MLPD', 'Applied To Job', 'Votes (Up/Down)', 'Transferred Team Leadership', 'badge_PLDS', 'Changed Password', 'Deleted Team', 'Accepted Team Leadership Transfer',

'Revoked Team Leadership Transfer', 'Report Something', 'Kicked Member From Team', 'Left Team', '$create_alias' + uniq blog, job, comp


По поводу сабмитов
там всего 2 колонки
User_ID_Next_month_Activity и Active
Если че чекаем базлайн
