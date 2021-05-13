input: 
<div role="main" class="col-md-12"><div><home ng-version="7.2.9">
    <div class="dashboard learner-dashboard" id="main">
      <div class="row">
        <div class="col-md-12">
          <div class="page-header">
            <h1>My courses</h1>
            <offline-notice>
  <!---->
  </offline-notice>
          </div>
        </div>
      </div>
      <!---->
      <!----><home-nav _nghost-c0="">
    <pl-pills _ngcontent-c0="">
    <div class="default custom-tabs-holder">
      <button aria-haspopup="true" class="mobile-menu-selected-tab" data-toggle="dropdown" aria-expanded="false">
        <span id="selected-tab-text">Current courses</span>
      </button>
      <ul class="nav nav-tabs" role="tablist">
        
      <!----><li _ngcontent-c0="" pl-pills-item="" role="presentation" class="active custom-pills-item">
    <button data-toggle="tab" role="tab" aria-selected="true" data-label="Current courses" tabindex="false">
      Current courses
      
    </button>
  </li><li _ngcontent-c0="" pl-pills-item="" role="presentation" class="custom-pills-item">
    <button data-toggle="tab" role="tab" aria-selected="false" data-label="Upcoming courses" tabindex="-1">
      Upcoming courses
      
    </button>
  </li><li _ngcontent-c0="" pl-pills-item="" role="presentation" class="custom-pills-item">
    <button data-toggle="tab" role="tab" aria-selected="false" data-label="Past courses" tabindex="-1">
      Past courses
      
    </button>
  </li>
    
      </ul>
    </div>
  </pl-pills>

    <div _ngcontent-c0="" class="row">
      <div _ngcontent-c0="" class="col-xs-12 col-sm-12 col-md-4 col-md-offset-4 home-search">
        <pl-search _ngcontent-c0="">
    <div class="row">
      <div class="col-xs-9 col-sm-6 col-md-10 col-lg-10 col-sm-offset-3 col-md-offset-0">
        <div class="row search-field">
          <div class="col-xs-10 no-padding">
            <input class="form-control ng-untouched ng-pristine ng-valid" name="search" type="text" aria-label="Search" placeholder="Search for a course…">
          </div>
          <div class="col-xs-2 no-padding">
            <pl-button class="pull-right reset-button hide">
    <!---->
      <button class="pl-button standard nude size-unset" type="button" aria-disabled="false">
        <!---->
      <span class="loader"></span>
      
              <i class="icon reset-icon"></i>
              <span class="sr-only">Reset</span>
            
    
      </button>
    

    <!---->

    <!---->

    <!---->
  </pl-button>
          </div>
        </div>
      </div>
      <div class="col-xs-3 col-sm-2 col-md-2 col-lg-2">
        <pl-button class="pull-left search-button">
    <!---->
      <button class="pl-button standard disabled nude size-unset" type="button" aria-disabled="true">
        <!---->
      <span class="loader"></span>
      
          <i class="icon search-icon"></i>
          <span class="sr-only">Submit</span>
        
    
      </button>
    

    <!---->

    <!---->

    <!---->
  </pl-button>
      </div>
    </div>
  </pl-search>
      </div>
    </div>

    <div _ngcontent-c0="" class="row options-toggle visible-xs-block">
      <div _ngcontent-c0="" class="col-xs-12">
        <pl-button _ngcontent-c0="" aria-label="Hide Options">
    <!---->
      <button class="pl-button standard nude large" type="button" aria-disabled="false">
        <!---->
      <span class="loader"></span>
      
          <span _ngcontent-c0="" aria-hidden="true">Options</span>
          <i _ngcontent-c0="" class="icon collapse"></i>
        
    
      </button>
    

    <!---->

    <!---->

    <!---->
  </pl-button>
      </div>
    </div>

    <div _ngcontent-c0="" class="row home-filters">
      <div _ngcontent-c0="" class="col-xs-12 col-sm-4 home-sort-by">
        <home-sort-by _ngcontent-c0="" _nghost-c1="">
    <fieldset _ngcontent-c1="" class="form-inline">
      <legend _ngcontent-c1="">Sort by:</legend>
      <div _ngcontent-c1="" class="form-group">
        <input _ngcontent-c1="" id="sortByName" name="sortBy" type="radio" value="name">
        <label _ngcontent-c1="" for="sortByName">Name</label>
      </div>
      <div _ngcontent-c1="" class="form-group">
        <input _ngcontent-c1="" id="sortByProgress" name="sortBy" type="radio" value="progress">
        <label _ngcontent-c1="" for="sortByProgress">Progress</label>
      </div>
    </fieldset>
  </home-sort-by>
      </div>
      <div _ngcontent-c0="" class="col-xs-12 col-sm-4 home-display-options">
        <home-display-options _ngcontent-c0="" _nghost-c2="">
    <fieldset _ngcontent-c2="" class="form-inline">
      <legend _ngcontent-c2="">Display:</legend>
      <div _ngcontent-c2="" class="form-group">
        <input _ngcontent-c2="" id="displayCourseSets" type="checkbox">
        <label _ngcontent-c2="" for="displayCourseSets">Course sets</label>
      </div>
      <div _ngcontent-c2="" class="form-group">
        <input _ngcontent-c2="" id="displayCompletedCourses" type="checkbox">
        <label _ngcontent-c2="" for="displayCompletedCourses">Completed courses</label>
      </div>
    </fieldset>
  </home-display-options>
      </div>
      <div _ngcontent-c0="" class="col-xs-12 col-sm-4 pagination-container">
        <div _ngcontent-c0="" class="col-xs-12 home-per-page">
          <home-per-page _ngcontent-c0="" class="dropup" _nghost-c3="">
    <label _ngcontent-c3="" class="label" role="label" id="homeDashboardPerPageDropdownTop" for="homeDashboardPerPageDropdownTopbutton">Items per page:</label>
    <pl-dropdown _ngcontent-c3="" aria-labelledby="homeDashboardPerPageDropdownTop">
    <div class="pl-dropdown-holder">
      <div class="pl-dropdown">
        <button aria-haspopup="true" class="btn btn-block white-btn dropdown-toggle pl-dropdown-button" data-toggle="dropdown" type="button" aria-expanded="false" id="homeDashboardPerPageDropdownTopbutton">
          <i class="fa fa-sort"></i>
          <!---->
          <span>
            <span>12</span>
          </span>
        </button>
        <ul class="dropdown-menu dropdown-menu-right pl-dropdown-menu">
          
      <!----><li _ngcontent-c3="" pl-dropdown-item="">
    <a aria-selected="false" class="pl-dropdown-item-link" role="option" tabindex="0" data-label="12">
      <!---->
      <span>
        <span>12</span>
      </span>
    </a>
  </li><li _ngcontent-c3="" pl-dropdown-item="">
    <a aria-selected="false" class="pl-dropdown-item-link" role="option" tabindex="0" data-label="24">
      <!---->
      <span>
        <span>24</span>
      </span>
    </a>
  </li><li _ngcontent-c3="" pl-dropdown-item="">
    <a aria-selected="false" class="pl-dropdown-item-link" role="option" tabindex="0" data-label="48">
      <!---->
      <span>
        <span>48</span>
      </span>
    </a>
  </li>
    
        </ul>
      </div>
    </div>
  </pl-dropdown>
  </home-per-page>
        </div>
        <div _ngcontent-c0="" class="col-xs-12 home-pagination">
          <pl-pager _ngcontent-c0="" _nghost-c4="">
    <div _ngcontent-c4="" class="status"><strong>Showing 1 to 3</strong> of 3 </div>
    <div _ngcontent-c4="" class="pager-arrow-set">
      <button _ngcontent-c4="" class="icon previous fa fa-chevron-left" title="Previous page" disabled="" aria-label="Previous page">
      </button>
      <button _ngcontent-c4="" class="icon next fa fa-chevron-right" title="Next page" disabled="" aria-label="Next page">
      </button>
    </div>
  </pl-pager>
        </div>
      </div>
    </div>

    <div _ngcontent-c0="" class="tab-content">
      <!----><div _ngcontent-c0="" class="tab-pane active">
        <!---->
        <div _ngcontent-c0="" class="row">
          <!----><home-card-panel _ngcontent-c0="" _nghost-c6="">
    <!---->

    <!---->

    <!----><!---->
      <!----><div _ngcontent-c6="" class="col-md-3 col-sm-4 course-card-holder">
        <!---->
      <div _ngcontent-c6="" class="panel panel-default panel-course course-card" id="panelOffering-MYbZ-xi6oQpg7a4T0-7">
        <!----><span _ngcontent-c6="" class="badge pull-right">
          <small _ngcontent-c6="">May 2021 Intake</small>
        </span>
        <home-course-title _ngcontent-c6="">
    <div class="panel-heading course-card-header">
      <div class="panel-title course-title-truncate course-card-header-title" title="IT0001: Welcome to Whitecliffe">
        <div class="truncated-content-holder">
          IT0001: Welcome to Whitecliffe
        </div>
      </div>
    </div>
  </home-course-title>
        <div _ngcontent-c6="" class="panel-body course-card-body">
          <home-course-progress _ngcontent-c6="" _nghost-c7="">
    <div _ngcontent-c7="" class="progress-container text-center">
      <div _ngcontent-c7="" class="graph">
        <div _ngcontent-c7="">
          <div _ngcontent-c7="">
            <!---->
            <p _ngcontent-c7="" class="hide">Complete</p>
            <!----><img _ngcontent-c7="" class="img-circle" src="/assets/storage-images/EPzlBJkGSsSRgpSHgMNR_BannerWithoutLogoIT0001v1.jpg?w=146&amp;h=146&amp;fit=crop" alt="Course cover image">
            <!---->
          </div>
          <!---->
        </div>
      </div>
    </div>
  </home-course-progress>
          <home-course-links _ngcontent-c6="">
    <div class="learner-dashboard-course-links">
      <a class="btn btn-default" href="/course/-MYbZ-xi6oQpg7a4T0-7/">
        <i class="icon-iqfy-24 overview"></i>
        <span>Overview</span>
      </a>
      <!---->
      <a class="btn btn-default" href="/course/-MYbZ-xi6oQpg7a4T0-7/#/studynotes">
        <i class="icon-iqfy-24 notes"></i>
        <span>Notes</span>
      </a>
    </div>
  </home-course-links>
        </div>
        <div _ngcontent-c6="" class="panel-footer course-card-footer">
          <pl-button _ngcontent-c6="">
    <!---->
      <a class="pl-button medium rect wide" href="/course/-MYbZ-xi6oQpg7a4T0-7#/overview">
        <!---->
      <span class="loader"></span>
      
            Go to course home
          
    
      </a>
    

    <!---->

    <!---->

    <!---->
  </pl-button>
        </div>
      </div>
    
      </div><div _ngcontent-c6="" class="col-md-3 col-sm-4 course-card-holder">
        <!---->
      <div _ngcontent-c6="" class="panel panel-default panel-course course-card" id="panelOffering-MYbaONQmgtbUBCzHYHM">
        <!----><span _ngcontent-c6="" class="badge pull-right">
          <small _ngcontent-c6="">May Intake 2021</small>
        </span>
        <home-course-title _ngcontent-c6="">
    <div class="panel-heading course-card-header">
      <div class="panel-title course-title-truncate course-card-header-title" title="IT5011: IT Systems">
        <div class="truncated-content-holder">
          IT5011: IT Systems
        </div>
      </div>
    </div>
  </home-course-title>
        <div _ngcontent-c6="" class="panel-body course-card-body">
          <home-course-progress _ngcontent-c6="" _nghost-c7="">
    <div _ngcontent-c7="" class="progress-container text-center">
      <div _ngcontent-c7="" class="graph">
        <div _ngcontent-c7="">
          <div _ngcontent-c7="">
            <!----><p _ngcontent-c7="" class="hide">0%</p>
            <p _ngcontent-c7="" class="hide">Complete</p>
            <!----><img _ngcontent-c7="" class="img-circle" src="/assets/storage-images/SCynHasBRoarTSdIMtKW_ITS.jpg?w=146&amp;h=146&amp;fit=crop" alt="Course cover image">
            <!---->
          </div>
          <!----><circle-progress _ngcontent-c7="">
        <!----><svg preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 190 190" height="190" width="190" class="">
            <defs>
                <!---->
                <!---->
            </defs>
            <!----><!---->
                <!----><circle cx="95" cy="95" r="89" fill="transparent" fill-opacity="1" stroke="transparent" stroke-width="0"></circle>
                <!---->
                        
            <!----><circle cx="95" cy="95" r="78" fill="none" stroke="#4a4a55" stroke-width="12"></circle>
            <!----><!---->
                <!----><path d="M 95 17
        A 78 78 0 0 1 95 17" stroke="#00CCB0" stroke-width="12" stroke-linecap="butt" fill="none"></path>
                <!---->
            
            <!----><text alignment-baseline="baseline" x="95" y="95" text-anchor="middle">
                <!---->
                <!---->
                <!----><!---->
                    <!----><tspan x="95" y="95" dy="0.32em" font-size="40" font-weight="700" fill="#00000000">0%
                    </tspan>
                
            </text>
            <!---->
        </svg>
    </circle-progress>
        </div>
      </div>
    </div>
  </home-course-progress>
          <home-course-links _ngcontent-c6="">
    <div class="learner-dashboard-course-links">
      <a class="btn btn-default" href="/course/-MYbaONQmgtbUBCzHYHM/">
        <i class="icon-iqfy-24 overview"></i>
        <span>Overview</span>
      </a>
      <!---->
      <a class="btn btn-default" href="/course/-MYbaONQmgtbUBCzHYHM/#/studynotes">
        <i class="icon-iqfy-24 notes"></i>
        <span>Notes</span>
      </a>
    </div>
  </home-course-links>
        </div>
        <div _ngcontent-c6="" class="panel-footer course-card-footer">
          <pl-button _ngcontent-c6="">
    <!---->
      <a class="pl-button medium rect wide" href="/course/-MYbaONQmgtbUBCzHYHM#/overview">
        <!---->
      <span class="loader"></span>
      
            Go to course home
          
    
      </a>
    

    <!---->

    <!---->

    <!---->
  </pl-button>
        </div>
      </div>
    
      </div><div _ngcontent-c6="" class="col-md-3 col-sm-4 course-card-holder">
        <!---->
      <div _ngcontent-c6="" class="panel panel-default panel-course course-card" id="panelOffering-MYvj1gyZzBtEWXHWtv5">
        <!----><span _ngcontent-c6="" class="badge pull-right">
          <small _ngcontent-c6="">May Intake 2021</small>
        </span>
        <home-course-title _ngcontent-c6="">
    <div class="panel-heading course-card-header">
      <div class="panel-title course-title-truncate course-card-header-title" title="IT5013: Professional Practice">
        <div class="truncated-content-holder">
          IT5013: Professional Practice
        </div>
      </div>
    </div>
  </home-course-title>
        <div _ngcontent-c6="" class="panel-body course-card-body">
          <home-course-progress _ngcontent-c6="" _nghost-c7="">
    <div _ngcontent-c7="" class="progress-container text-center">
      <div _ngcontent-c7="" class="graph">
        <div _ngcontent-c7="">
          <div _ngcontent-c7="">
            <!----><p _ngcontent-c7="" class="hide">0%</p>
            <p _ngcontent-c7="" class="hide">Complete</p>
            <!----><img _ngcontent-c7="" class="img-circle" src="https://iqfy-storage.imgix.net/DblI50I1QPa1XE0diWW6_P_Practice_Banner.jpg?w=146&amp;h=146&amp;fit=crop" alt="Course cover image">
            <!---->
          </div>
          <!----><circle-progress _ngcontent-c7="">
        <!----><svg preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 190 190" height="190" width="190" class="">
            <defs>
                <!---->
                <!---->
            </defs>
            <!----><!---->
                <!----><circle cx="95" cy="95" r="89" fill="transparent" fill-opacity="1" stroke="transparent" stroke-width="0"></circle>
                <!---->
                        
            <!----><circle cx="95" cy="95" r="78" fill="none" stroke="#4a4a55" stroke-width="12"></circle>
            <!----><!---->
                <!----><path d="M 95 17
        A 78 78 0 0 1 95 17" stroke="#00CCB0" stroke-width="12" stroke-linecap="butt" fill="none"></path>
                <!---->
            
            <!----><text alignment-baseline="baseline" x="95" y="95" text-anchor="middle">
                <!---->
                <!---->
                <!----><!---->
                    <!----><tspan x="95" y="95" dy="0.32em" font-size="40" font-weight="700" fill="#00000000">0%
                    </tspan>
                
            </text>
            <!---->
        </svg>
    </circle-progress>
        </div>
      </div>
    </div>
  </home-course-progress>
          <home-course-links _ngcontent-c6="">
    <div class="learner-dashboard-course-links">
      <a class="btn btn-default" href="/course/-MYvj1gyZzBtEWXHWtv5/">
        <i class="icon-iqfy-24 overview"></i>
        <span>Overview</span>
      </a>
      <!---->
      <a class="btn btn-default" href="/course/-MYvj1gyZzBtEWXHWtv5/#/studynotes">
        <i class="icon-iqfy-24 notes"></i>
        <span>Notes</span>
      </a>
    </div>
  </home-course-links>
        </div>
        <div _ngcontent-c6="" class="panel-footer course-card-footer">
          <pl-button _ngcontent-c6="">
    <!---->
      <a class="pl-button medium rect wide" href="/course/-MYvj1gyZzBtEWXHWtv5#/overview">
        <!---->
      <span class="loader"></span>
      
            Go to course home
          
    
      </a>
    

    <!---->

    <!---->

    <!---->
  </pl-button>
        </div>
      </div>
    
      </div>
    

    <!---->
  </home-card-panel>
        </div>
      </div><div _ngcontent-c0="" class="tab-pane">
        <!---->
        <div _ngcontent-c0="" class="row">
          <!----><home-card-panel _ngcontent-c0="" _nghost-c6="">
    <!---->

    <!----><div _ngcontent-c6="" class="col-xs-12 dashboard-no-courses">
      <img _ngcontent-c6="" class="no-cards-placeholder" src="https://cdn.iqualify.com/0-0-22404-bb1f152d/images/gui/placeholder_search.svg" alt="No courses here">
      <p _ngcontent-c6="">No courses here</p>
    </div>

    <!----><!---->
      <!---->
    

    <!---->
  </home-card-panel>
        </div>
      </div><div _ngcontent-c0="" class="tab-pane">
        <!---->
        <div _ngcontent-c0="" class="row">
          <!----><home-card-panel _ngcontent-c0="" _nghost-c6="">
    <!---->

    <!----><div _ngcontent-c6="" class="col-xs-12 dashboard-no-courses">
      <img _ngcontent-c6="" class="no-cards-placeholder" src="https://cdn.iqualify.com/0-0-22404-bb1f152d/images/gui/placeholder_search.svg" alt="No courses here">
      <p _ngcontent-c6="">No courses here</p>
    </div>

    <!----><!---->
      <!---->
    

    <!---->
  </home-card-panel>
        </div>
      </div>
    </div>

    <div _ngcontent-c0="" class="row home-filters lower-pagination-container">
      <div _ngcontent-c0="" class="col-xs-12 col-sm-6 home-per-page">
        <home-per-page _ngcontent-c0="" class="dropup home-per-page" _nghost-c3="">
    <label _ngcontent-c3="" class="label" role="label" id="homeDashboardPerPageDropdownBottom" for="homeDashboardPerPageDropdownBottombutton">Items per page:</label>
    <pl-dropdown _ngcontent-c3="" aria-labelledby="homeDashboardPerPageDropdownBottom">
    <div class="pl-dropdown-holder">
      <div class="pl-dropdown">
        <button aria-haspopup="true" class="btn btn-block white-btn dropdown-toggle pl-dropdown-button" data-toggle="dropdown" type="button" aria-expanded="false" id="homeDashboardPerPageDropdownBottombutton">
          <i class="fa fa-sort"></i>
          <!---->
          <span>
            <span>12</span>
          </span>
        </button>
        <ul class="dropdown-menu dropdown-menu-right pl-dropdown-menu">
          
      <!----><li _ngcontent-c3="" pl-dropdown-item="">
    <a aria-selected="false" class="pl-dropdown-item-link" role="option" tabindex="0" data-label="12">
      <!---->
      <span>
        <span>12</span>
      </span>
    </a>
  </li><li _ngcontent-c3="" pl-dropdown-item="">
    <a aria-selected="false" class="pl-dropdown-item-link" role="option" tabindex="0" data-label="24">
      <!---->
      <span>
        <span>24</span>
      </span>
    </a>
  </li><li _ngcontent-c3="" pl-dropdown-item="">
    <a aria-selected="false" class="pl-dropdown-item-link" role="option" tabindex="0" data-label="48">
      <!---->
      <span>
        <span>48</span>
      </span>
    </a>
  </li>
    
        </ul>
      </div>
    </div>
  </pl-dropdown>
  </home-per-page>
      </div>
      <div _ngcontent-c0="" class="col-xs-12 col-sm-6 home-pagination">
        <pl-pager _ngcontent-c0="" _nghost-c4="">
    <div _ngcontent-c4="" class="status"><strong>Showing 1 to 3</strong> of 3 </div>
    <div _ngcontent-c4="" class="pager-arrow-set">
      <button _ngcontent-c4="" class="icon previous fa fa-chevron-left" title="Previous page" disabled="" aria-label="Previous page">
      </button>
      <button _ngcontent-c4="" class="icon next fa fa-chevron-right" title="Next page" disabled="" aria-label="Next page">
      </button>
    </div>
  </pl-pager>
      </div>
    </div>
  </home-nav>
    </div>
  </home></div></div>
