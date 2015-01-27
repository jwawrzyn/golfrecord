var golfTrackApp = angular.module('golfTrackApp')

golfTrackApp.controller('CourseListCtrl', function($scope) {
	var currentCourse = 'All';
	var currentDetailRecord = '';

	$scope.courses = [
		{ 'name' : 'All'},
		{ 'name' : 'Foxboro' },
		{ 'name' : 'University Ridge' }
	];

	$scope.rounds = [
		{ 'date' : '05/30/2014',
			'course' : 'Foxboro',
			'player' : 'Jenny',
			'score' : '95',
			'detailId' : '2014_5_30' },
		{ 'date' : '06/28/2014',
			'course' : 'Foxboro',
			'player' : 'Jenny', 
			'score' : '92',
			'detailId' : '2014_6_28'},
		{ 'date' : '07/15/2014',
			'course' : 'University Ridge',
			'player' : 'Jenny',
			'score' : '55',
			'detailId' : '2014_7_15'}
	];

	$scope.details = [
		{ 'detailId' : '2014_5_30',
			'hole' : '1',
			'score' : '5',
		},
		{ 'detailId' : '2014_5_30',
			'hole' : '2',
			'score' : '5',
		},
		{ 'detailId' : '2014_5_30',
			'hole' : '3',
			'score' : '5',
		},
		{ 'detailId' : '2014_5_30',
			'hole' : '4',
			'score' : '5',
		},
		{ 'detailId' : '2014_5_30',
			'hole' : '5',
			'score' : '5',
		},
		{ 'detailId' : '2014_5_30',
			'hole' : '6',
			'score' : '5',
		},
		{ 'detailId' : '2014_5_30',
			'hole' : '7',
			'score' : '5',
		},
		{ 'detailId' : '2014_5_30',
			'hole' : '8',
			'score' : '5',
		},
		{ 'detailId' : '2014_5_30',
			'hole' : '9',
			'score' : '5',
		},
	];

	$scope.selectCourse = function (courseSelected) {
            currentCourse = courseSelected;
     }

	$scope.courseIsSelected = function (roundInQuestion) {
            return currentCourse == 'All' || roundInQuestion.course == currentCourse;
        }

	$scope.selectDetail = function(detailSelected) {
		currentDetailRecord = detailSelected;
	}

	$scope.detailIsSelected = function (detailInQuestion) {
		return currentDetailRecord == detailInQuestion.detailId;
	}
});
