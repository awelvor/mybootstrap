/* wordpress.sql */


select "PAROISSE BONNE NOUVELLE";
select option_value from wphc_options where option_name="blogname";
select now();
select "WP_POSTS";
delete from wphc_posts where post_type="revision";
delete from wphc_posts where post_status="auto-draft";
delete from wphc_posts where post_status="trash";
select "WP_POSTMETA";
delete wphc_postmeta from wphc_postmeta left outer join wphc_posts on wphc_posts.id= wphc_postmeta.post_id where wphc_posts.id is null;
select "WP_OPTIONS";
delete from wphc_options where option_name like '%transient%';
select "WP_TERM_RELATIONSHIPS";
delete wphc_term_relationships from wphc_term_relationships left outer join wphc_posts on wphc_term_relationships.object_id=wphc_posts.id where wphc_posts.id is null;
select "PLUGIN MODERN EVENTS CALENDAR LITE";

delete wphc_mec_dates  from wphc_mec_dates  left outer join wphc_posts on wphc_mec_dates.post_id =wphc_posts.id where wphc_posts.id is null;
delete wphc_mec_events from wphc_mec_events left outer join wphc_posts on wphc_mec_events.post_id=wphc_posts.id where wphc_posts.id is null;
delete wphc_posts from wphc_posts left outer join wphc_mec_dates  on wphc_posts.id=wphc_mec_dates.post_id  where wphc_posts.post_type="mec-events" and wphc_mec_dates.id  is null;
delete wphc_posts from wphc_posts left outer join wphc_mec_events on wphc_posts.id=wphc_mec_events.post_id where wphc_posts.post_type="mec-events" and wphc_mec_events.id is null;

select "BILAN WPHC_POSTS";
select post_type, count(*) from wphc_posts group by post_type;
select now();
select "BYE...";

select id, post_title, guid, post_mime_type from wphc_posts where post_type="attachment"
select post_type, post_mime_type, count(*) from wphc_posts group by post_mime_type;

/* mailpoet */
/* newsletters */
select
wphc_mailpoet_newsletters.id, wphc_mailpoet_newsletters.subject, wphc_mailpoet_newsletters.type,wphc_mailpoet_newsletters.sent_at
from wphc_mailpoet_newsletters

/* newsletters ->templates*/
select
wphc_mailpoet_newsletters.id, wphc_mailpoet_newsletters.subject, wphc_mailpoet_newsletters.type,wphc_mailpoet_newsletters.sent_at,
wphc_mailpoet_newsletter_templates.newsletter_id,wphc_mailpoet_newsletter_templates.name
from wphc_mailpoet_newsletters
left outer join wphc_mailpoet_newsletter_templates on wphc_mailpoet_newsletter_templates.newsletter_id=wphc_mailpoet_newsletters.id
select
wphc_mailpoet_newsletters.id, wphc_mailpoet_newsletters.subject, wphc_mailpoet_newsletters.type,wphc_mailpoet_newsletters.sent_at,
wphc_mailpoet_newsletter_templates.newsletter_id,wphc_mailpoet_newsletter_templates.name
from wphc_mailpoet_newsletters
right outer join wphc_mailpoet_newsletter_templates on wphc_mailpoet_newsletter_templates.newsletter_id=wphc_mailpoet_newsletters.id
where wphc_mailpoet_newsletters.id is null
/* newletters -> posts */
select
wphc_mailpoet_newsletters.id, wphc_mailpoet_newsletters.subject, wphc_mailpoet_newsletters.type,wphc_mailpoet_newsletters.sent_at,
wphc_posts.id, wphc_posts.post_title, wphc_posts.post_type
from wphc_mailpoet_newsletters   
left outer join wphc_mailpoet_newsletter_posts on wphc_mailpoet_newsletters.id = wphc_mailpoet_newsletter_posts.newsletter_id
left outer join wphc_posts on wphc_posts.id = wphc_mailpoet_newsletter_posts.post_id
order by wphc_mailpoet_newsletters.id
/* listes de diffusion (segments)*/
select
wphc_mailpoet_segments.id, wphc_mailpoet_segments.name, wphc_mailpoet_segments.type
from wphc_mailpoet_segments
/* liste d'abonnés */
select
wphc_mailpoet_subscribers.id, wphc_mailpoet_subscribers.email
from wphc_mailpoet_subscribers
select "scheduled tasks";
select status, count(*) from wphc_mailpoet_scheduled_tasks group by status
select * from wphc_mailpoet_scheduled_tasks where status="completed"
delete from wphc_mailpoet_scheduled_tasks where status="completed"

select 
wphc_mailpoet_subscriber_segment.id, wphc_mailpoet_subscriber_segment.subscriber_id, wphc_mailpoet_subscriber_segment.segment_id,
wphc_mailpoet_subscribers.id, wphc_mailpoet_subscribers.email,wphc_mailpoet_subscribers.first_name,wphc_mailpoet_subscribers.last_name,
wphc_mailpoet_segments.id, wphc_mailpoet_segments.name,wphc_mailpoet_segments.type,wphc_mailpoet_segments.description
from wphc_mailpoet_subscriber_segment
left outer join wphc_mailpoet_subscribers on wphc_mailpoet_subscriber_segment.subscriber_id = wphc_mailpoet_subscribers.id
left outer join wphc_mailpoet_segments on wphc_mailpoet_subscriber_segment.segment_id = wphc_mailpoet_segments.id

select
wphc_mailpoet_sending_queues.id,   wphc_mailpoet_sending_queues.task_id,   wphc_mailpoet_sending_queues.newsletter_id,
wphc_mailpoet_newsletters.id, wphc_mailpoet_newsletters.subject,
wphc_mailpoet_scheduled_tasks.id, wphc_mailpoet_scheduled_tasks.type,
wphc_posts.id, wphc_posts.post_title, wphc_posts.post_type
from wphc_mailpoet_sending_queues
inner join wphc_mailpoet_scheduled_tasks on wphc_mailpoet_scheduled_tasks.id=wphc_mailpoet_sending_queues.task_id
inner join wphc_mailpoet_newsletters      on wphc_mailpoet_newsletters.id = wphc_mailpoet_sending_queues.newsletter_id
inner join wphc_mailpoet_newsletter_posts on wphc_mailpoet_newsletters.id = wphc_mailpoet_newsletter_posts.newsletter_id
inner join wphc_posts on wphc_posts.id = wphc_mailpoet_newsletter_posts.post_id

/* end */



select * from wphc_posts where post_date like "2022-10-12%";
select * from wphc_posts where post_modified like "2022-10-13%";

select post_type, count(*) from wphc_posts group by post_type;
select id, post_title, post_type from wphc_posts where post_type="mec_calendars";

select
wphc_posts.id, wphc_posts.post_title,
wphc_postmeta.post_id, wphc_postmeta.meta_key, wphc_postmeta.meta_value
from wphc_posts
inner join wphc_postmeta on wphc_posts.id= wphc_postmeta.post_id;

select
wphc_posts.id, wphc_posts.post_title, wphc_posts.post_type,wphc_posts.guid,
wphc_postmeta.post_id, wphc_postmeta.meta_key, wphc_postmeta.meta_value
from wphc_postmeta
inner join wphc_posts on wphc_posts.id= wphc_postmeta.post_id;

select
wphc_posts.id,  wphc_posts.post_type,wphc_posts.guid
from wphc_postmeta
inner join wphc_posts on wphc_posts.id= wphc_postmeta.post_id;


select
wphc_posts.id, wphc_posts.post_title,
wphc_postmeta.post_id, wphc_postmeta.meta_key, wphc_postmeta.meta_value
from wphc_postmeta
left outer join wphc_posts on wphc_posts.id= wphc_postmeta.post_id
where wphc_posts.id is null;

delete wphc_postmeta
from wphc_postmeta
left outer join wphc_posts on wphc_posts.id= wphc_postmeta.post_id
where wphc_posts.id is null;

/*                terms   */

select
wphc_terms.term_id, wphc_terms.name, wphc_terms.slug,
wphc_term_taxonomy.term_taxonomy_id, wphc_term_taxonomy.term_id, wphc_term_taxonomy.taxonomy, wphc_term_taxonomy.description,
wphc_posts.post_title, wphc_posts.post_type
from wphc_terms
inner join wphc_term_taxonomy on wphc_terms.term_id= wphc_term_taxonomy.term_id
inner join wphc_term_relationships on wphc_term_taxonomy.term_taxonomy_id = wphc_term_relationships.term_taxonomy_id 
left outer join wphc_posts on wphc_term_relationships.object_id = wphc_posts.id

select
wphc_posts.id, wphc_posts.post_title, wphc_posts.post_type,
wphc_users.user_login,
wphc_term_taxonomy.taxonomy, wphc_term_taxonomy.description,
wphc_terms.name, wphc_terms.slug
from wphc_posts
inner join wphc_users              on wphc_users.id                       = wphc_posts.post_author
inner join wphc_term_relationships on wphc_term_relationships.object_id   = wphc_posts.id
inner join wphc_term_taxonomy      on wphc_term_taxonomy.term_taxonomy_id = wphc_term_relationships.term_taxonomy_id 
inner join wphc_terms              on wphc_terms.term_id                  = wphc_term_taxonomy.term_id
where wphc_posts.post_title like "%202%"
order by   wphc_posts.id


select 
wphc_term_relationships.object_id, wphc_term_relationships.term_taxonomy_id,
wphc_posts.id, wphc_posts.post_title, 
wphc_terms.name
from wphc_term_relationships
left outer join wphc_term_taxonomy on wphc_term_taxonomy.term_taxonomy_id= wphc_term_relationships.term_taxonomy_id
left outer join wphc_terms on wphc_term_taxonomy.term_taxonomy_id=wphc_terms.term_id
left outer join wphc_posts on wphc_term_relationships.object_id=wphc_posts.id
where wphc_posts.id is null

select 
wphc_posts.id, wphc_posts.post_title, wphc_term_relationships.object_id
from wphc_term_relationships
left outer join wphc_posts on wphc_term_relationships.object_id=wphc_posts.id
where wphc_posts.id is null
 
delete wphc_term_relationships
from wphc_term_relationships
left outer join wphc_posts on wphc_term_relationships.object_id=wphc_posts.id
where wphc_posts.id is null

select
wphc_mec_events.id, wphc_mec_events.post_id,wphc_mec_events.start, wphc_mec_events.end,
wphc_posts.id, wphc_posts.post_title
from wphc_mec_events
left outer join wphc_posts on wphc_mec_events.post_id=wphc_posts.id
where wphc_mec_events.end <now() - interval 1 day
order by wphc_mec_events.end

select
wphc_mec_dates.id, wphc_mec_dates.post_id,wphc_mec_dates.dstart, wphc_mec_dates.dend,
wphc_posts.id, wphc_posts.post_title,wphc_posts.post_type
from wphc_mec_dates
left outer join wphc_posts on wphc_mec_dates.post_id=wphc_posts.id
where wphc_mec_dates.dend < now()- interval 1 day
order by wphc_mec_dates.dend

select
wphc_mec_dates.id, wphc_mec_dates.post_id,wphc_mec_dates.dstart, wphc_mec_dates.dend
from wphc_mec_dates
where wphc_mec_dates.dend < now()- interval 1 day

delete wphc_mec_dates from wphc_mec_dates where wphc_mec_dates.dend < now()- interval 1 day;
delete wphc_mec_events from wphc_mec_events where wphc_mec_events.end < now()- interval 1 day;




select 
wphc_mailpoet_newsletter_posts.id, wphc_mailpoet_newsletter_posts.newsletter_id, wphc_mailpoet_newsletter_posts.post_id,
wphc_posts.post_title, wphc_posts.post_type,
wphc_mailpoet_newsletters.subject,wphc_mailpoet_newsletters.type
from wphc_mailpoet_newsletter_posts
left outer join wphc_posts on wphc_mailpoet_newsletter_posts.post_id=wphc_posts.id
left outer join wphc_mailpoet_newsletters on wphc_mailpoet_newsletters.id=wphc_mailpoet_newsletter_posts.newsletter_id


truncate wphc_actionscheduler_logs;
select * from wphc_actionscheduler_actions where status='failed';
select * from wphc_actionscheduler_actions where hook like "aioseo%";
select url, created_at from wphc_mailpoet_newsletter_links where url like "https:%"
order by created_at

select post_title , post_status, post_password from wphc_posts where(post_password!='') or (post_status='private');

select * from wphc_posts where post_title like '%accueillir%'

/* elementor */

select wphc_posts.post_title 
from wphc_postmeta where post_id=14994;
select * 

select 
wphc_posts.post_title, wphc_posts.post_author,
wphc_postmeta.post_id, wphc_postmeta.meta_key, wphc_postmeta.meta_value
from wphc_postmeta 
inner join wphc_posts on wphc_posts.id = wphc_postmeta.post_id
where ((wphc_postmeta.meta_key ='_wp_page_template') or  (wphc_postmeta.meta_key ='_elementor_template_type')) and (wphc_postmeta.post_id>15000)
order by wphc_postmeta.post_id;

select wphc_posts.id, wphc_posts.post_title,
meta1.meta_key, meta1.meta_value,
meta2.meta_key, meta2.meta_value
from wphc_posts
inner join wphc_postmeta as meta1 on wphc_posts.id = meta1.post_id
inner join wphc_postmeta as meta2 on wphc_posts.id = meta2.post_id
where (meta1.meta_value = "elementor_header_footer") and (meta2.meta_key="_wp_page_template")







