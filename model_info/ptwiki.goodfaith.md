Model Information:
	 - type: GradientBoosting
	 - version: 0.5.0
	 - params: {'labels': [True, False], 'subsample': 1.0, 'n_iter_no_change': None, 'max_leaf_nodes': None, 'loss': 'deviance', 'learning_rate': 0.01, 'n_estimators': 700, 'center': True, 'presort': 'auto', 'min_weight_fraction_leaf': 0.0, 'tol': 0.0001, 'population_rates': None, 'init': None, 'min_impurity_decrease': 0.0, 'criterion': 'friedman_mse', 'max_features': 'log2', 'random_state': None, 'max_depth': 7, 'label_weights': OrderedDict([(False, 10)]), 'min_samples_leaf': 1, 'multilabel': False, 'warm_start': False, 'min_impurity_split': None, 'scale': True, 'verbose': 0, 'min_samples_split': 2, 'validation_fraction': 0.1}
	Environment:
	 - revscoring_version: '2.5.1'
	 - platform: 'Linux-4.9.0-9-amd64-x86_64-with-debian-9.9'
	 - machine: 'x86_64'
	 - version: '#1 SMP Debian 4.9.168-1+deb9u2 (2019-05-13)'
	 - system: 'Linux'
	 - processor: ''
	 - python_build: ('default', 'Sep 27 2018 17:25:39')
	 - python_compiler: 'GCC 6.3.0 20170516'
	 - python_branch: ''
	 - python_implementation: 'CPython'
	 - python_revision: ''
	 - python_version: '3.5.3'
	 - release: '4.9.0-9-amd64'
	
	Statistics:
	counts (n=19541):
		label        n         ~True    ~False
		-------  -----  ---  -------  --------
		True     18383  -->    16904      1479
		False     1158  -->      332       826
	rates:
		              True    False
		----------  ------  -------
		sample       0.941    0.059
		population   0.94     0.06
	match_rate (micro=0.835, macro=0.5):
		  False    True
		-------  ------
		  0.119   0.881
	filter_rate (micro=0.165, macro=0.5):
		  False    True
		-------  ------
		  0.881   0.119
	recall (micro=0.907, macro=0.816):
		  False    True
		-------  ------
		  0.713    0.92
	!recall (micro=0.726, macro=0.816):
		  False    True
		-------  ------
		   0.92   0.713
	precision (micro=0.943, macro=0.671):
		  False    True
		-------  ------
		  0.362    0.98
	!precision (micro=0.4, macro=0.671):
		  False    True
		-------  ------
		   0.98   0.362
	f1 (micro=0.921, macro=0.715):
		  False    True
		-------  ------
		  0.481   0.949
	!f1 (micro=0.509, macro=0.715):
		  False    True
		-------  ------
		  0.949   0.481
	accuracy (micro=0.907, macro=0.907):
		  False    True
		-------  ------
		  0.907   0.907
	fpr (micro=0.274, macro=0.184):
		  False    True
		-------  ------
		   0.08   0.287
	roc_auc (micro=0.931, macro=0.932):
		  False    True
		-------  ------
		  0.932   0.931
	pr_auc (micro=0.968, macro=0.768):
		  False    True
		-------  ------
		  0.541   0.995
	
	 - score_schema: {'properties': {'probability': {'properties': {'true': {'type': 'number'}, 'false': {'type': 'number'}}, 'type': 'object', 'description': 'A mapping of probabilities onto each of the potential output labels'}, 'prediction': {'type': 'boolean', 'description': 'The most likely label predicted by the estimator'}}, 'type': 'object', 'title': 'Scikit learn-based classifier score with probability'}

