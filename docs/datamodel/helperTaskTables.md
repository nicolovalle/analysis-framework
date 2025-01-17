---
sort: 2
title: Helper task tables
---

<a name=helper_tasks></a>
# List of tables created with helper tasks

The AO2D data files contain the basic set of data which is available for data analysis and from which other quantities are deduced (see [AO2D tables](ao2dTables.md)). There are however quantities like PID information, V0 characteristics, etc. which are commonly used in analysis. In order to prevent that tasks to compute such quantities are repeatingly developed, a set of helper tasks is provided by the O2 framework. These tasks are listed below together with the tables they provide.

Click on the labels to display the table content. Click buttons to
<button class="openTables">show</button> / <button class="closeTables">close</button> all tables.

<!-- Block with helper tasks -->

####  o2-analysis-centrality-table
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer//centralityTable.cxx" target="_blank">centralityTable.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::CentV0Ms</button>
  <div class="panel">
    <div>
       V0M estimated centrality table
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/Centrality.h" target="_blank">Common/DataModel/Centrality.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::CentV0M = o2::aod::CentV0Ms::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::cent::CentEstV0M</td>
        <td></td>
        <td>centV0M</td>
        <td>float</td>
        <td>Centrality percentile estimated from V0C+V0A multiplicities</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::CentRun2SPDTrks</button>
  <div class="panel">
    <div>
       Run2 SPD tracklets estimated centrality table
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/Centrality.h" target="_blank">Common/DataModel/Centrality.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::CentRun2SPDTrk = o2::aod::CentRun2SPDTrks::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::cent::CentEstRun2SPDTracklets</td>
        <td></td>
        <td>centRun2SPDTracklets</td>
        <td>float</td>
        <td>Run2 centrality percentile estimated from SPD tracklets multiplicity</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::CentRun2SPDClss</button>
  <div class="panel">
    <div>
       Run2 SPD clusters estimated centrality table
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/Centrality.h" target="_blank">Common/DataModel/Centrality.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::CentRun2SPDCls = o2::aod::CentRun2SPDClss::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::cent::CentEstRun2SPDClusters</td>
        <td></td>
        <td>centRun2SPDClusters</td>
        <td>float</td>
        <td>Run2 centrality percentile estimated from SPD clusters multiplicity</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::CentRun2CL0s</button>
  <div class="panel">
    <div>
       Run2 CL0 estimated centrality table
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/Centrality.h" target="_blank">Common/DataModel/Centrality.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::CentRun2CL0 = o2::aod::CentRun2CL0s::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::cent::CentEstRun2CL0</td>
        <td></td>
        <td>centRun2CL0</td>
        <td>float</td>
        <td>Run2 centrality percentile estimated from CL0 multiplicity</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::CentRun2CL1s</button>
  <div class="panel">
    <div>
       Run2 CL1 estimated centrality table
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/Centrality.h" target="_blank">Common/DataModel/Centrality.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::CentRun2CL1 = o2::aod::CentRun2CL1s::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::cent::CentEstRun2CL1</td>
        <td></td>
        <td>centRun2CL1</td>
        <td>float</td>
        <td>Run2 centrality percentile estimated from CL1 multiplicity</td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-event-selection
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer//eventSelection.cxx" target="_blank">eventSelection.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::EvSels</button>
  <div class="panel">
    <div>

    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/EventSelection.h" target="_blank">Common/DataModel/EventSelection.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::EvSel = o2::aod::EvSels::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::evsel::Alias</td>
        <td></td>
        <td>alias</td>
        <td>int32_t[kNaliases]</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::evsel::Selection</td>
        <td></td>
        <td>selection</td>
        <td>int32_t[kNsel]</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BBV0A</td>
        <td></td>
        <td>bbV0A</td>
        <td>bool</td>
        <td>Beam-beam time in V0A</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BBV0C</td>
        <td></td>
        <td>bbV0C</td>
        <td>bool</td>
        <td>Beam-beam time in V0C</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BGV0A</td>
        <td></td>
        <td>bgV0A</td>
        <td>bool</td>
        <td>Beam-gas time in V0A</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BGV0C</td>
        <td></td>
        <td>bgV0C</td>
        <td>bool</td>
        <td>Beam-gas time in V0C</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BBFDA</td>
        <td></td>
        <td>bbFDA</td>
        <td>bool</td>
        <td>Beam-beam time in FDA</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BBFDC</td>
        <td></td>
        <td>bbFDC</td>
        <td>bool</td>
        <td>Beam-beam time in FDC</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BGFDA</td>
        <td></td>
        <td>bgFDA</td>
        <td>bool</td>
        <td>Beam-gas time in FDA</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BGFDC</td>
        <td></td>
        <td>bgFDC</td>
        <td>bool</td>
        <td>Beam-gas time in FDC</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::MultRingV0A</td>
        <td></td>
        <td>multRingV0A</td>
        <td>float[5]</td>
        <td>V0A multiplicity per ring (4 rings in run2, 5 rings in run3)</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::MultRingV0C</td>
        <td></td>
        <td>multRingV0C</td>
        <td>float[4]</td>
        <td>V0C multiplicity per ring (4 rings in run2)</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::SpdClusters</td>
        <td></td>
        <td>spdClusters</td>
        <td>uint32_t</td>
        <td>Number of SPD clusters in two layers</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::NTracklets</td>
        <td></td>
        <td>nTracklets</td>
        <td>int</td>
        <td>Tracklet multiplicity</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::Sel7</td>
        <td></td>
        <td>sel7</td>
        <td>bool</td>
        <td>Event selection decision based on V0A & V0C</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::Sel8</td>
        <td></td>
        <td>sel8</td>
        <td>bool</td>
        <td>Event selection decision based on TVX</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::FoundBCId</td>
        <td>I</td>
        <td>foundBCId</td>
        <td>int</td>
        <td>BC entry index in BCs table (-1 if doesn't exist)</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::FoundFT0Id</td>
        <td>I</td>
        <td>foundFT0Id</td>
        <td>int</td>
        <td>FT0 entry index in FT0s table (-1 if doesn't exist)</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::FoundFV0Id</td>
        <td>I</td>
        <td>foundFV0Id</td>
        <td>int</td>
        <td>FV0 entry index in FV0As table (-1 if doesn't exist)</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::BcSels</button>
  <div class="panel">
    <div>

    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/EventSelection.h" target="_blank">Common/DataModel/EventSelection.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BcSel = o2::aod::BcSels::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::evsel::Alias</td>
        <td></td>
        <td>alias</td>
        <td>int32_t[kNaliases]</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::evsel::Selection</td>
        <td></td>
        <td>selection</td>
        <td>int32_t[kNsel]</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BBV0A</td>
        <td></td>
        <td>bbV0A</td>
        <td>bool</td>
        <td>Beam-beam time in V0A</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BBV0C</td>
        <td></td>
        <td>bbV0C</td>
        <td>bool</td>
        <td>Beam-beam time in V0C</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BGV0A</td>
        <td></td>
        <td>bgV0A</td>
        <td>bool</td>
        <td>Beam-gas time in V0A</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BGV0C</td>
        <td></td>
        <td>bgV0C</td>
        <td>bool</td>
        <td>Beam-gas time in V0C</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BBFDA</td>
        <td></td>
        <td>bbFDA</td>
        <td>bool</td>
        <td>Beam-beam time in FDA</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BBFDC</td>
        <td></td>
        <td>bbFDC</td>
        <td>bool</td>
        <td>Beam-beam time in FDC</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BGFDA</td>
        <td></td>
        <td>bgFDA</td>
        <td>bool</td>
        <td>Beam-gas time in FDA</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::BGFDC</td>
        <td></td>
        <td>bgFDC</td>
        <td>bool</td>
        <td>Beam-gas time in FDC</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::MultRingV0A</td>
        <td></td>
        <td>multRingV0A</td>
        <td>float[5]</td>
        <td>V0A multiplicity per ring (4 rings in run2, 5 rings in run3)</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::MultRingV0C</td>
        <td></td>
        <td>multRingV0C</td>
        <td>float[4]</td>
        <td>V0C multiplicity per ring (4 rings in run2)</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::SpdClusters</td>
        <td></td>
        <td>spdClusters</td>
        <td>uint32_t</td>
        <td>Number of SPD clusters in two layers</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::FoundFT0Id</td>
        <td>I</td>
        <td>foundFT0Id</td>
        <td>int</td>
        <td>FT0 entry index in FT0s table (-1 if doesn't exist)</td>
      </tr>
      <tr>
        <td>o2::aod::evsel::FoundFV0Id</td>
        <td>I</td>
        <td>foundFV0Id</td>
        <td>int</td>
        <td>FV0 entry index in FV0As table (-1 if doesn't exist)</td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-ft0-corrected-table
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer//ft0CorrectedTable.cxx" target="_blank">ft0CorrectedTable.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::FT0sCorrected</button>
  <div class="panel">
    <div>
       Table with corrected FT0 values
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/FT0Corrected.h" target="_blank">Common/DataModel/FT0Corrected.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::FT0Corrected = o2::aod::FT0sCorrected::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::ft0::T0ACorrected</td>
        <td></td>
        <td>t0ACorrected</td>
        <td>float</td>
        <td>Collision time A-side, corrected with primary vertex</td>
      </tr>
      <tr>
        <td>o2::aod::ft0::T0CCorrected</td>
        <td></td>
        <td>t0CCorrected</td>
        <td>float</td>
        <td>Collision time C-side, corrected with primary vertex</td>
      </tr>
      <tr>
        <td>o2::aod::ft0::T0AC</td>
        <td>D</td>
        <td>t0AC</td>
        <td>float</td>
        <td>Collision time (A+C)/2</td>
      </tr>
      <tr>
        <td>o2::aod::ft0::T0ACorrectedValid</td>
        <td>D</td>
        <td>t0ACorrectedValid</td>
        <td>bool</td>
        <td>Was T0ACorrected computable?</td>
      </tr>
      <tr>
        <td>o2::aod::ft0::T0CCorrectedValid</td>
        <td>D</td>
        <td>t0CCorrectedValid</td>
        <td>bool</td>
        <td>Was T0CCorrected computable?</td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-multiplicity-table
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer//multiplicityTable.cxx" target="_blank">multiplicityTable.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::Mults</button>
  <div class="panel">
    <div>

    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/Multiplicity.h" target="_blank">Common/DataModel/Multiplicity.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::Mult = o2::aod::Mults::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::mult::MultV0A</td>
        <td></td>
        <td>multV0A</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::mult::MultV0C</td>
        <td></td>
        <td>multV0C</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::mult::MultT0A</td>
        <td></td>
        <td>multT0A</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::mult::MultT0C</td>
        <td></td>
        <td>multT0C</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::mult::MultZNA</td>
        <td></td>
        <td>multZNA</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::mult::MultZNC</td>
        <td></td>
        <td>multZNC</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::mult::MultV0M</td>
        <td>D</td>
        <td>multV0M</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::mult::MultT0M</td>
        <td>D</td>
        <td>multT0M</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::mult::MultTracklets</td>
        <td></td>
        <td>multTracklets</td>
        <td>int</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::mult::MultTPC</td>
        <td></td>
        <td>multTPC</td>
        <td>int</td>
        <td></td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-timestamp
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer//timestamp.cxx" target="_blank">timestamp.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::Timestamps</button>
  <div class="panel">
    <div>
       Table which holds the timestamp of a BC
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/" target="_blank"></a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BCsWithTimestamps = soa::Join<o2::aod::BCs, o2::aod::Timestamps></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::timestamp::Timestamp</td>
        <td></td>
        <td>timestamp</td>
        <td>uint64_t</td>
        <td>Timestamp of a BC in ms (epoch style)</td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-track-propagation
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer//trackPropagation.cxx" target="_blank">trackPropagation.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::TracksPropagated</button>
  <div class="panel">
    <div>
       commonly used track parameters, propagated to the primary vertex
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/TrackPropagation.h" target="_blank">Common/DataModel/TrackPropagation.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::TrackPropagated = o2::aod::TracksPropagated::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::soa::Index</td>
        <td>GI</td>
        <td>globalIndex</td>
        <td>int64_t</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::CollisionId</td>
        <td>I</td>
        <td>collisionId</td>
        <td>int32</td>
        <td>Collision to which this track belongs</td>
      </tr>
      <tr>
        <td>o2::aod::track::TrackType</td>
        <td></td>
        <td>trackType</td>
        <td>uint8_t</td>
        <td>Type of track. See enum TrackTypeEnum</td>
      </tr>
      <tr>
        <td>o2::aod::trackpropagated::Sign</td>
        <td></td>
        <td>sign</td>
        <td>int8_t</td>
        <td>sign of the track's charge</td>
      </tr>
      <tr>
        <td>o2::aod::trackpropagated::Pt</td>
        <td></td>
        <td>pt</td>
        <td>float</td>
        <td>track transverse momentum GeV/c</td>
      </tr>
      <tr>
        <td>o2::aod::trackpropagated::Phi</td>
        <td></td>
        <td>phi</td>
        <td>float</td>
        <td>track phi</td>
      </tr>
      <tr>
        <td>o2::aod::trackpropagated::Eta</td>
        <td></td>
        <td>eta</td>
        <td>float</td>
        <td>track eta</td>
      </tr>
      <tr>
        <td>o2::aod::trackpropagated::Px</td>
        <td>D</td>
        <td>px</td>
        <td>float</td>
        <td>x-component of the track momentum GeV/c</td>
      </tr>
      <tr>
        <td>o2::aod::trackpropagated::Py</td>
        <td>D</td>
        <td>py</td>
        <td>float</td>
        <td>y-component of the track momentum GeV/c</td>
      </tr>
      <tr>
        <td>o2::aod::trackpropagated::Pz</td>
        <td>D</td>
        <td>pz</td>
        <td>float</td>
        <td>z-component of the track momentum GeV/c</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::TracksParPropagated</button>
  <div class="panel">
    <div>
       additional track parameters, propagated to the primary vertex
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/TrackPropagation.h" target="_blank">Common/DataModel/TrackPropagation.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::TrackParPropagated = o2::aod::TracksParPropagated::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::track::X</td>
        <td></td>
        <td>x</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::Alpha</td>
        <td></td>
        <td>alpha</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::Y</td>
        <td></td>
        <td>y</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::Z</td>
        <td></td>
        <td>z</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::Snp</td>
        <td></td>
        <td>snp</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::Tgl</td>
        <td></td>
        <td>tgl</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::Signed1Pt</td>
        <td></td>
        <td>signed1Pt</td>
        <td>float</td>
        <td>(sign of charge)/Pt in c/GeV. Use pt() and sign() instead</td>
      </tr>
      <tr>
        <td>o2::aod::track::Px</td>
        <td>D</td>
        <td>px</td>
        <td>float</td>
        <td>Momentum in x-direction in GeV/c</td>
      </tr>
      <tr>
        <td>o2::aod::track::Py</td>
        <td>D</td>
        <td>py</td>
        <td>float</td>
        <td>Momentum in y-direction in GeV/c</td>
      </tr>
      <tr>
        <td>o2::aod::track::Pz</td>
        <td>D</td>
        <td>pz</td>
        <td>float</td>
        <td>Momentum in z-direction in GeV/c</td>
      </tr>
      <tr>
        <td>o2::aod::track::Sign</td>
        <td>D</td>
        <td>sign</td>
        <td>short</td>
        <td>Charge: positive: 1, negative: -1</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::TracksExtended</button>
  <div class="panel">
    <div>

    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/TrackSelectionTables.h" target="_blank">Common/DataModel/TrackSelectionTables.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksExtended = soa::Join<o2::aod::BigTracks, o2::aod::TracksExtended></li>
        <li>o2::aod::BigTracksPIDExtended = soa::Join<o2::aod::BigTracksPID, o2::aod::TracksExtended></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::track::DcaXY</td>
        <td></td>
        <td>dcaXY</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::DcaZ</td>
        <td></td>
        <td>dcaZ</td>
        <td>float</td>
        <td></td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-trackextension
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer//trackextension.cxx" target="_blank">trackextension.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::TracksExtended</button>
  <div class="panel">
    <div>

    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/TrackSelectionTables.h" target="_blank">Common/DataModel/TrackSelectionTables.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksExtended = soa::Join<o2::aod::BigTracks, o2::aod::TracksExtended></li>
        <li>o2::aod::BigTracksPIDExtended = soa::Join<o2::aod::BigTracksPID, o2::aod::TracksExtended></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::track::DcaXY</td>
        <td></td>
        <td>dcaXY</td>
        <td>float</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::DcaZ</td>
        <td></td>
        <td>dcaZ</td>
        <td>float</td>
        <td></td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-trackselection
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer//trackselection.cxx" target="_blank">trackselection.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::TrackSelection</button>
  <div class="panel">
    <div>

    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/DataModel/TrackSelectionTables.h" target="_blank">Common/DataModel/TrackSelectionTables.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::track::IsGlobalTrack</td>
        <td></td>
        <td>isGlobalTrack</td>
        <td>uint8_t</td>
        <td></td>
      </tr>
      <tr>
        <td>o2::aod::track::IsGlobalTrackSDD</td>
        <td></td>
        <td>isGlobalTrackSDD</td>
        <td>uint8_t</td>
        <td></td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-weak-decay-indices
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer//weakDecayIndices.cxx" target="_blank">weakDecayIndices.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::TransientV0s</button>
  <div class="panel">
    <div>
       In-memory V0 table
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/" target="_blank"></a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::V0s = soa::Join<o2::aod::TransientV0s, o2::aod::StoredV0s></li>
        <li>o2::aod::V0 = soa::Join<o2::aod::TransientV0s, o2::aod::StoredV0s>::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::v0::CollisionId</td>
        <td>I</td>
        <td>collisionId</td>
        <td>int32</td>
        <td>Collision index</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::TransientCascades</button>
  <div class="panel">
    <div>
       In-memory cascade table
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/" target="_blank"></a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::Cascades = soa::Join<o2::aod::TransientCascades, o2::aod::StoredCascades></li>
        <li>o2::aod::Cascade = soa::Join<o2::aod::TransientCascades, o2::aod::StoredCascades>::iterator</li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::cascade::CollisionId</td>
        <td>I</td>
        <td>collisionId</td>
        <td>int32</td>
        <td>Collision index</td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-pid-bayes
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer/PID//pidBayes.cxx" target="_blank">pidBayes.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayesEl</button>
  <div class="panel">
    <div>
       Binned (in percentage) Bayesian probability of having a Electron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesEl</td>
        <td></td>
        <td>bayesEl</td>
        <td>int8_t</td>
        <td>Bayesian probability for electron expressed in %</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayesMu</button>
  <div class="panel">
    <div>
       Binned (in percentage) Bayesian probability of having a Muon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesMu</td>
        <td></td>
        <td>bayesMu</td>
        <td>int8_t</td>
        <td>Bayesian probability for muon expressed in %</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayesPi</button>
  <div class="panel">
    <div>
       Binned (in percentage) Bayesian probability of having a Pion
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesPi</td>
        <td></td>
        <td>bayesPi</td>
        <td>int8_t</td>
        <td>Bayesian probability for pion expressed in %</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayesKa</button>
  <div class="panel">
    <div>
       Binned (in percentage) Bayesian probability of having a Kaon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesKa</td>
        <td></td>
        <td>bayesKa</td>
        <td>int8_t</td>
        <td>Bayesian probability for kaon expressed in %</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayesPr</button>
  <div class="panel">
    <div>
       Binned (in percentage) Bayesian probability of having a Proton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesPr</td>
        <td></td>
        <td>bayesPr</td>
        <td>int8_t</td>
        <td>Bayesian probability for proton expressed in %</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayesDe</button>
  <div class="panel">
    <div>
       Binned (in percentage) Bayesian probability of having a Deuteron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesDe</td>
        <td></td>
        <td>bayesDe</td>
        <td>int8_t</td>
        <td>Bayesian probability for deuteron expressed in %</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayesTr</button>
  <div class="panel">
    <div>
       Binned (in percentage) Bayesian probability of having a Triton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesTr</td>
        <td></td>
        <td>bayesTr</td>
        <td>int8_t</td>
        <td>Bayesian probability for triton expressed in %</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayesHe</button>
  <div class="panel">
    <div>
       Binned (in percentage) Bayesian probability of having a Helium3
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesHe</td>
        <td></td>
        <td>bayesHe</td>
        <td>int8_t</td>
        <td>Bayesian probability for helium3 expressed in %</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayesAl</button>
  <div class="panel">
    <div>
       Binned (in percentage) Bayesian probability of having a Alpha
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesAl</td>
        <td></td>
        <td>bayesAl</td>
        <td>int8_t</td>
        <td>Bayesian probability for alpha expressed in %</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidBayes</button>
  <div class="panel">
    <div>
       Index of the most probable ID and its bayesian probability
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesProb</td>
        <td></td>
        <td>bayesProb</td>
        <td>int8_t</td>
        <td>Bayesian probability of the most probable ID</td>
      </tr>
      <tr>
        <td>o2::aod::pidbayes::BayesID</td>
        <td></td>
        <td>bayesID</td>
        <td>o2::track::pid_constants::ID</td>
        <td>Most probable ID</td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-pid-tof
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer/PID//pidTOF.cxx" target="_blank">pidTOF.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFEl</button>
  <div class="panel">
    <div>
       Table of the TOF response with binned Nsigma for electron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaStoreEl</td>
        <td></td>
        <td>tofNSigmaStoreEl</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TOF detector for electron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaEl</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFMu</button>
  <div class="panel">
    <div>
       Table of the TOF response with binned Nsigma for muon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaStoreMu</td>
        <td></td>
        <td>tofNSigmaStoreMu</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TOF detector for muon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaMu</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFPi</button>
  <div class="panel">
    <div>
       Table of the TOF response with binned Nsigma for pion
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaStorePi</td>
        <td></td>
        <td>tofNSigmaStorePi</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TOF detector for pion</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaPi</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFKa</button>
  <div class="panel">
    <div>
       Table of the TOF response with binned Nsigma for kaon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaStoreKa</td>
        <td></td>
        <td>tofNSigmaStoreKa</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TOF detector for kaon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaKa</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFPr</button>
  <div class="panel">
    <div>
       Table of the TOF response with binned Nsigma for proton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaStorePr</td>
        <td></td>
        <td>tofNSigmaStorePr</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TOF detector for proton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaPr</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFDe</button>
  <div class="panel">
    <div>
       Table of the TOF response with binned Nsigma for deuteron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaStoreDe</td>
        <td></td>
        <td>tofNSigmaStoreDe</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TOF detector for deuteron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaDe</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFTr</button>
  <div class="panel">
    <div>
       Table of the TOF response with binned Nsigma for triton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaStoreTr</td>
        <td></td>
        <td>tofNSigmaStoreTr</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TOF detector for triton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaTr</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFHe</button>
  <div class="panel">
    <div>
       Table of the TOF response with binned Nsigma for helium3
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaStoreHe</td>
        <td></td>
        <td>tofNSigmaStoreHe</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TOF detector for helium3</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaHe</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFAl</button>
  <div class="panel">
    <div>
       Table of the TOF response with binned Nsigma for alpha
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaStoreAl</td>
        <td></td>
        <td>tofNSigmaStoreAl</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TOF detector for alpha</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof_tiny::TOFNSigmaAl</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-pid-tof-full
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer/PID//pidTOFFull.cxx" target="_blank">pidTOFFull.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFFullEl</button>
  <div class="panel">
    <div>
       Table of the TOF (full) response with expected signal, expected resolution and Nsigma for electron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDiffEl</td>
        <td>D</td>
        <td>tofExpSignalDiffEl</td>
        <td>float</td>
        <td>Difference between signal and expected for electron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalEl</td>
        <td>D</td>
        <td>tofExpSignalEl</td>
        <td>float</td>
        <td>Expected time for electron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSigmaEl</td>
        <td></td>
        <td>tofExpSigmaEl</td>
        <td>float</td>
        <td>Expected resolution with the TOF detector for electron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFNSigmaEl</td>
        <td></td>
        <td>tofNSigmaEl</td>
        <td>float</td>
        <td>Nsigma separation with the TOF detector for electron</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFFullMu</button>
  <div class="panel">
    <div>
       Table of the TOF (full) response with expected signal, expected resolution and Nsigma for muon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDiffMu</td>
        <td>D</td>
        <td>tofExpSignalDiffMu</td>
        <td>float</td>
        <td>Difference between signal and expected for muon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalMu</td>
        <td>D</td>
        <td>tofExpSignalMu</td>
        <td>float</td>
        <td>Expected time for muon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSigmaMu</td>
        <td></td>
        <td>tofExpSigmaMu</td>
        <td>float</td>
        <td>Expected resolution with the TOF detector for muon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFNSigmaMu</td>
        <td></td>
        <td>tofNSigmaMu</td>
        <td>float</td>
        <td>Nsigma separation with the TOF detector for muon</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFFullPi</button>
  <div class="panel">
    <div>
       Table of the TOF (full) response with expected signal, expected resolution and Nsigma for pion
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDiffPi</td>
        <td>D</td>
        <td>tofExpSignalDiffPi</td>
        <td>float</td>
        <td>Difference between signal and expected for pion</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalPi</td>
        <td>D</td>
        <td>tofExpSignalPi</td>
        <td>float</td>
        <td>Expected time for pion</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSigmaPi</td>
        <td></td>
        <td>tofExpSigmaPi</td>
        <td>float</td>
        <td>Expected resolution with the TOF detector for pion</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFNSigmaPi</td>
        <td></td>
        <td>tofNSigmaPi</td>
        <td>float</td>
        <td>Nsigma separation with the TOF detector for pion</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFFullKa</button>
  <div class="panel">
    <div>
       Table of the TOF (full) response with expected signal, expected resolution and Nsigma for kaon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDiffKa</td>
        <td>D</td>
        <td>tofExpSignalDiffKa</td>
        <td>float</td>
        <td>Difference between signal and expected for kaon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalKa</td>
        <td>D</td>
        <td>tofExpSignalKa</td>
        <td>float</td>
        <td>Expected time for kaon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSigmaKa</td>
        <td></td>
        <td>tofExpSigmaKa</td>
        <td>float</td>
        <td>Expected resolution with the TOF detector for kaon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFNSigmaKa</td>
        <td></td>
        <td>tofNSigmaKa</td>
        <td>float</td>
        <td>Nsigma separation with the TOF detector for kaon</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFFullPr</button>
  <div class="panel">
    <div>
       Table of the TOF (full) response with expected signal, expected resolution and Nsigma for proton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDiffPr</td>
        <td>D</td>
        <td>tofExpSignalDiffPr</td>
        <td>float</td>
        <td>Difference between signal and expected for proton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalPr</td>
        <td>D</td>
        <td>tofExpSignalPr</td>
        <td>float</td>
        <td>Expected time for proton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSigmaPr</td>
        <td></td>
        <td>tofExpSigmaPr</td>
        <td>float</td>
        <td>Expected resolution with the TOF detector for proton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFNSigmaPr</td>
        <td></td>
        <td>tofNSigmaPr</td>
        <td>float</td>
        <td>Nsigma separation with the TOF detector for proton</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFFullDe</button>
  <div class="panel">
    <div>
       Table of the TOF (full) response with expected signal, expected resolution and Nsigma for deuteron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDiffDe</td>
        <td>D</td>
        <td>tofExpSignalDiffDe</td>
        <td>float</td>
        <td>Difference between signal and expected for deuteron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDe</td>
        <td>D</td>
        <td>tofExpSignalDe</td>
        <td>float</td>
        <td>Expected time for deuteron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSigmaDe</td>
        <td></td>
        <td>tofExpSigmaDe</td>
        <td>float</td>
        <td>Expected resolution with the TOF detector for deuteron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFNSigmaDe</td>
        <td></td>
        <td>tofNSigmaDe</td>
        <td>float</td>
        <td>Nsigma separation with the TOF detector for deuteron</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFFullTr</button>
  <div class="panel">
    <div>
       Table of the TOF (full) response with expected signal, expected resolution and Nsigma for triton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDiffTr</td>
        <td>D</td>
        <td>tofExpSignalDiffTr</td>
        <td>float</td>
        <td>Difference between signal and expected for triton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalTr</td>
        <td>D</td>
        <td>tofExpSignalTr</td>
        <td>float</td>
        <td>Expected time for triton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSigmaTr</td>
        <td></td>
        <td>tofExpSigmaTr</td>
        <td>float</td>
        <td>Expected resolution with the TOF detector for triton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFNSigmaTr</td>
        <td></td>
        <td>tofNSigmaTr</td>
        <td>float</td>
        <td>Nsigma separation with the TOF detector for triton</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFFullHe</button>
  <div class="panel">
    <div>
       Table of the TOF (full) response with expected signal, expected resolution and Nsigma for helium3
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDiffHe</td>
        <td>D</td>
        <td>tofExpSignalDiffHe</td>
        <td>float</td>
        <td>Difference between signal and expected for helium3</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalHe</td>
        <td>D</td>
        <td>tofExpSignalHe</td>
        <td>float</td>
        <td>Expected time for helium3</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSigmaHe</td>
        <td></td>
        <td>tofExpSigmaHe</td>
        <td>float</td>
        <td>Expected resolution with the TOF detector for helium3</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFNSigmaHe</td>
        <td></td>
        <td>tofNSigmaHe</td>
        <td>float</td>
        <td>Nsigma separation with the TOF detector for helium3</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFFullAl</button>
  <div class="panel">
    <div>
       Table of the TOF (full) response with expected signal, expected resolution and Nsigma for alpha
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalDiffAl</td>
        <td>D</td>
        <td>tofExpSignalDiffAl</td>
        <td>float</td>
        <td>Difference between signal and expected for alpha</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSignalAl</td>
        <td>D</td>
        <td>tofExpSignalAl</td>
        <td>float</td>
        <td>Expected time for alpha</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFExpSigmaAl</td>
        <td></td>
        <td>tofExpSigmaAl</td>
        <td>float</td>
        <td>Expected resolution with the TOF detector for alpha</td>
      </tr>
      <tr>
        <td>o2::aod::pidtof::TOFNSigmaAl</td>
        <td></td>
        <td>tofNSigmaAl</td>
        <td>float</td>
        <td>Nsigma separation with the TOF detector for alpha</td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-pid-tof-beta
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer/PID//pidTOFbeta.cxx" target="_blank">pidTOFbeta.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTOFbeta</button>
  <div class="panel">
    <div>
       Table of the TOF beta
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtofbeta::Beta</td>
        <td></td>
        <td>beta</td>
        <td>float</td>
        <td>TOF beta</td>
      </tr>
      <tr>
        <td>o2::aod::pidtofbeta::BetaError</td>
        <td></td>
        <td>betaerror</td>
        <td>float</td>
        <td>Uncertainty on the TOF beta</td>
      </tr>
      <tr>
        <td>o2::aod::pidtofbeta::ExpBetaEl</td>
        <td></td>
        <td>expbetael</td>
        <td>float</td>
        <td>Expected beta of electron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtofbeta::ExpBetaElError</td>
        <td></td>
        <td>expbetaelerror</td>
        <td>float</td>
        <td>Expected uncertainty on the beta of electron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtofbeta::SeparationBetaEl</td>
        <td></td>
        <td>separationbetael</td>
        <td>float</td>
        <td>Separation computed with the expected beta for electrons</td>
      </tr>
      <tr>
        <td>o2::aod::pidtofbeta::DiffBetaEl</td>
        <td>D</td>
        <td>diffbetael</td>
        <td>float</td>
        <td>Difference between the measured and the expected beta for electrons</td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-pid-tpc
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer/PID//pidTPC.cxx" target="_blank">pidTPC.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCEl</button>
  <div class="panel">
    <div>
       Table of the TPC response with binned Nsigma for electron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaStoreEl</td>
        <td></td>
        <td>tpcNSigmaStoreEl</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TPC detector for electron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaEl</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCMu</button>
  <div class="panel">
    <div>
       Table of the TPC response with binned Nsigma for muon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaStoreMu</td>
        <td></td>
        <td>tpcNSigmaStoreMu</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TPC detector for muon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaMu</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCPi</button>
  <div class="panel">
    <div>
       Table of the TPC response with binned Nsigma for pion
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaStorePi</td>
        <td></td>
        <td>tpcNSigmaStorePi</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TPC detector for pion</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaPi</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCKa</button>
  <div class="panel">
    <div>
       Table of the TPC response with binned Nsigma for kaon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaStoreKa</td>
        <td></td>
        <td>tpcNSigmaStoreKa</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TPC detector for kaon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaKa</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCPr</button>
  <div class="panel">
    <div>
       Table of the TPC response with binned Nsigma for proton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaStorePr</td>
        <td></td>
        <td>tpcNSigmaStorePr</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TPC detector for proton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaPr</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCDe</button>
  <div class="panel">
    <div>
       Table of the TPC response with binned Nsigma for deuteron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaStoreDe</td>
        <td></td>
        <td>tpcNSigmaStoreDe</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TPC detector for deuteron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaDe</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCTr</button>
  <div class="panel">
    <div>
       Table of the TPC response with binned Nsigma for triton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaStoreTr</td>
        <td></td>
        <td>tpcNSigmaStoreTr</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TPC detector for triton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaTr</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCHe</button>
  <div class="panel">
    <div>
       Table of the TPC response with binned Nsigma for helium3
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaStoreHe</td>
        <td></td>
        <td>tpcNSigmaStoreHe</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TPC detector for helium3</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaHe</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCAl</button>
  <div class="panel">
    <div>
       Table of the TPC response with binned Nsigma for alpha
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaStoreAl</td>
        <td></td>
        <td>tpcNSigmaStoreAl</td>
        <td>int8_t</td>
        <td>Stored binned nsigma with the TPC detector for alpha</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc_tiny::TPCNSigmaAl</td>
        <td>GI</td>
        <td></td>
        <td>?</td>
        <td></td>
      </tr>
    </table>
  </div>

</div>

####  o2-analysis-pid-tpc-full
Code file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master//Common/TableProducer/PID//pidTPCFull.cxx" target="_blank">pidTPCFull.cxx</a>
<div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCFullEl</button>
  <div class="panel">
    <div>
       Table of the TPC (full) response with expected signal, expected resolution and Nsigma for electron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSignalDiffEl</td>
        <td>D</td>
        <td>tpcExpSignalDiffEl</td>
        <td>float</td>
        <td>Difference between signal and expected for electron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSigmaEl</td>
        <td></td>
        <td>tpcExpSigmaEl</td>
        <td>float</td>
        <td>Expected resolution with the TPC detector for electron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCNSigmaEl</td>
        <td></td>
        <td>tpcNSigmaEl</td>
        <td>float</td>
        <td>Nsigma separation with the TPC detector for electron</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCFullMu</button>
  <div class="panel">
    <div>
       Table of the TPC (full) response with expected signal, expected resolution and Nsigma for muon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSignalDiffMu</td>
        <td>D</td>
        <td>tpcExpSignalDiffMu</td>
        <td>float</td>
        <td>Difference between signal and expected for muon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSigmaMu</td>
        <td></td>
        <td>tpcExpSigmaMu</td>
        <td>float</td>
        <td>Expected resolution with the TPC detector for muon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCNSigmaMu</td>
        <td></td>
        <td>tpcNSigmaMu</td>
        <td>float</td>
        <td>Nsigma separation with the TPC detector for muon</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCFullPi</button>
  <div class="panel">
    <div>
       Table of the TPC (full) response with expected signal, expected resolution and Nsigma for pion
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSignalDiffPi</td>
        <td>D</td>
        <td>tpcExpSignalDiffPi</td>
        <td>float</td>
        <td>Difference between signal and expected for pion</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSigmaPi</td>
        <td></td>
        <td>tpcExpSigmaPi</td>
        <td>float</td>
        <td>Expected resolution with the TPC detector for pion</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCNSigmaPi</td>
        <td></td>
        <td>tpcNSigmaPi</td>
        <td>float</td>
        <td>Nsigma separation with the TPC detector for pion</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCFullKa</button>
  <div class="panel">
    <div>
       Table of the TPC (full) response with expected signal, expected resolution and Nsigma for kaon
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSignalDiffKa</td>
        <td>D</td>
        <td>tpcExpSignalDiffKa</td>
        <td>float</td>
        <td>Difference between signal and expected for kaon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSigmaKa</td>
        <td></td>
        <td>tpcExpSigmaKa</td>
        <td>float</td>
        <td>Expected resolution with the TPC detector for kaon</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCNSigmaKa</td>
        <td></td>
        <td>tpcNSigmaKa</td>
        <td>float</td>
        <td>Nsigma separation with the TPC detector for kaon</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCFullPr</button>
  <div class="panel">
    <div>
       Table of the TPC (full) response with expected signal, expected resolution and Nsigma for proton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <div>Is used in:
      <ul>
        <li>o2::aod::BigTracksPID = soa::Join<o2::aod::BigTracks, o2::aod::pidTPCFullEl, o2::aod::pidTPCFullMu, o2::aod::pidTPCFullPi, o2::aod::pidTPCFullKa, o2::aod::pidTPCFullPr, o2::aod::pidTOFFullEl, o2::aod::pidTOFFullMu, o2::aod::pidTOFFullPi, o2::aod::pidTOFFullKa, o2::aod::pidTOFFullPr></li>
      </ul>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSignalDiffPr</td>
        <td>D</td>
        <td>tpcExpSignalDiffPr</td>
        <td>float</td>
        <td>Difference between signal and expected for proton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSigmaPr</td>
        <td></td>
        <td>tpcExpSigmaPr</td>
        <td>float</td>
        <td>Expected resolution with the TPC detector for proton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCNSigmaPr</td>
        <td></td>
        <td>tpcNSigmaPr</td>
        <td>float</td>
        <td>Nsigma separation with the TPC detector for proton</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCFullDe</button>
  <div class="panel">
    <div>
       Table of the TPC (full) response with expected signal, expected resolution and Nsigma for deuteron
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSignalDiffDe</td>
        <td>D</td>
        <td>tpcExpSignalDiffDe</td>
        <td>float</td>
        <td>Difference between signal and expected for deuteron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSigmaDe</td>
        <td></td>
        <td>tpcExpSigmaDe</td>
        <td>float</td>
        <td>Expected resolution with the TPC detector for deuteron</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCNSigmaDe</td>
        <td></td>
        <td>tpcNSigmaDe</td>
        <td>float</td>
        <td>Nsigma separation with the TPC detector for deuteron</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCFullTr</button>
  <div class="panel">
    <div>
       Table of the TPC (full) response with expected signal, expected resolution and Nsigma for triton
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSignalDiffTr</td>
        <td>D</td>
        <td>tpcExpSignalDiffTr</td>
        <td>float</td>
        <td>Difference between signal and expected for triton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSigmaTr</td>
        <td></td>
        <td>tpcExpSigmaTr</td>
        <td>float</td>
        <td>Expected resolution with the TPC detector for triton</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCNSigmaTr</td>
        <td></td>
        <td>tpcNSigmaTr</td>
        <td>float</td>
        <td>Nsigma separation with the TPC detector for triton</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCFullHe</button>
  <div class="panel">
    <div>
       Table of the TPC (full) response with expected signal, expected resolution and Nsigma for helium3
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSignalDiffHe</td>
        <td>D</td>
        <td>tpcExpSignalDiffHe</td>
        <td>float</td>
        <td>Difference between signal and expected for helium3</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSigmaHe</td>
        <td></td>
        <td>tpcExpSigmaHe</td>
        <td>float</td>
        <td>Expected resolution with the TPC detector for helium3</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCNSigmaHe</td>
        <td></td>
        <td>tpcNSigmaHe</td>
        <td>float</td>
        <td>Nsigma separation with the TPC detector for helium3</td>
      </tr>
    </table>
  </div>

  <button class="myaccordion"><i class="fa fa-table"></i> o2::aod::pidTPCFullAl</button>
  <div class="panel">
    <div>
       Table of the TPC (full) response with expected signal, expected resolution and Nsigma for alpha
    </div>
    <div>
      Header file: <a href="https://github.com/AliceO2Group/O2Physics/tree/master/Common/Core/PID/PIDResponse.h" target="_blank">Common/Core/PID/PIDResponse.h</a>
    </div>
    <table class=DataModel>
      <tr>
        <th>Name</th>
        <th></th>
        <th>Getter</th>
        <th>Type</th>
        <th>Comment</th>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSignalDiffAl</td>
        <td>D</td>
        <td>tpcExpSignalDiffAl</td>
        <td>float</td>
        <td>Difference between signal and expected for alpha</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCExpSigmaAl</td>
        <td></td>
        <td>tpcExpSigmaAl</td>
        <td>float</td>
        <td>Expected resolution with the TPC detector for alpha</td>
      </tr>
      <tr>
        <td>o2::aod::pidtpc::TPCNSigmaAl</td>
        <td></td>
        <td>tpcNSigmaAl</td>
        <td>float</td>
        <td>Nsigma separation with the TPC detector for alpha</td>
      </tr>
    </table>
  </div>

</div>
<!-- Block with helper tasks -->
