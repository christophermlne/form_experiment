form_experiment
===============

learning to code a drupal module

Note: Currently, the table described below needs to exist or the module will crash

CREATE TABLE `formtestsave` (
  `id` int(11) unsigned NOT NULL AUTO_INCREMENT,
  `first_name` text,
  `last_name` text,
  `middle_inital` tinytext,
  `year_of_birth` int(4) DEFAULT NULL,
  `computer` text,
  `comment` longtext,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=23 DEFAULT CHARSET=latin1;
