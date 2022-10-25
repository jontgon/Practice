# Practice
1st attempt using github platform
go
<?xml version='1.0' encoding='utf-8' ?>

<!-- build 20204.22.0708.0320                               -->
<workbook original-version='18.1' source-build='2020.4.20 (20204.22.0708.0320)' source-platform='win' version='18.1' xmlns:user='http://www.tableausoftware.com/xml/user'>
  <document-format-change-manifest>
    <_.fcp.MarkAnimation.true...MarkAnimation />
    <_.fcp.ObjectModelEncapsulateLegacy.true...ObjectModelEncapsulateLegacy />
    <_.fcp.ObjectModelTableType.true...ObjectModelTableType />
    <_.fcp.SchemaViewerObjectModel.true...SchemaViewerObjectModel />
    <SheetIdentifierTracking />
    <WindowsPersistSimpleIdentifiers />
  </document-format-change-manifest>
  <preferences>
    <preference name='ui.encoding.shelf.height' value='24' />
    <preference name='ui.shelf.height' value='26' />
  </preferences>
  <datasources>
    <datasource caption='mlbpitching (mlbpitching)' inline='true' name='federated.1xurpiz04swff81768nnh1jlx64g' version='18.1'>
      <connection class='federated'>
        <named-connections>
          <named-connection caption='mlbpitching' name='excel-direct.13ej3ao0f80wnv19h0lk81721wvo'>
            <connection class='excel-direct' cleaning='no' compat='no' dataRefreshTime='' filename='C:/Users/14062/Desktop/class/CSCI_444/datasets/PITCHING_DATA/mlbpitching.xlsx' interpretationMode='0' password='' server='' validate='no' />
          </named-connection>
        </named-connections>
        <_.fcp.ObjectModelEncapsulateLegacy.false...relation connection='excel-direct.13ej3ao0f80wnv19h0lk81721wvo' name='mlbpitching' table='[mlbpitching$]' type='table'>
          <columns gridOrigin='A1:AG152:no:A1:AG152:0' header='yes' outcome='6'>
            <column datatype='integer' name='id' ordinal='0' />
            <column datatype='integer' name='year' ordinal='1' />
            <column datatype='integer' name='teams' ordinal='2' />
            <column datatype='integer' name='total_pitchers' ordinal='3' />
            <column datatype='real' name='average_age' ordinal='4' />
            <column datatype='real' name='runs_per_game' ordinal='5' />
            <column datatype='real' name='ERA' ordinal='6' />
            <column datatype='integer' name='games_played' ordinal='7' />
            <column datatype='integer' name='games_finished' ordinal='8' />
            <column datatype='integer' name='complete_game' ordinal='9' />
            <column datatype='integer' name='shutouts' ordinal='10' />
            <column datatype='integer' name='shutouts_team' ordinal='11' />
            <column datatype='integer' name='saves' ordinal='12' />
            <column datatype='real' name='innings_pitched' ordinal='13' />
            <column datatype='integer' name='hits' ordinal='14' />
            <column datatype='integer' name='runs' ordinal='15' />
            <column datatype='integer' name='earned_runs' ordinal='16' />
            <column datatype='integer' name='home_runs' ordinal='17' />
            <column datatype='integer' name='walks' ordinal='18' />
            <column datatype='integer' name='intentional_walks' ordinal='19' />
            <column datatype='integer' name='strikeouts' ordinal='20' />
            <column datatype='integer' name='hit_batter' ordinal='21' />
            <column datatype='integer' name='balks' ordinal='22' />
            <column datatype='integer' name='wild_pitches' ordinal='23' />
            <column datatype='integer' name='batters_faced' ordinal='24' />
            <column datatype='real' name='WHIP' ordinal='25' />
            <column datatype='real' name='BA_bip' ordinal='26' />
            <column datatype='real' name='hits_9' ordinal='27' />
            <column datatype='real' name='homeruns_9' ordinal='28' />
            <column datatype='real' name='walks_9' ordinal='29' />
            <column datatype='real' name='strikeouts_9' ordinal='30' />
            <column datatype='real' name='strikeout_walk' ordinal='31' />
            <column datatype='integer' name='errors' ordinal='32' />
          </columns>
        </_.fcp.ObjectModelEncapsulateLegacy.false...relation>
        <_.fcp.ObjectModelEncapsulateLegacy.true...relation connection='excel-direct.13ej3ao0f80wnv19h0lk81721wvo' name='mlbpitching' table='[mlbpitching$]' type='table'>
          <columns gridOrigin='A1:AG152:no:A1:AG152:0' header='yes' outcome='6'>
            <column datatype='integer' name='id' ordinal='0' />
            <column datatype='integer' name='year' ordinal='1' />
            <column datatype='integer' name='teams' ordinal='2' />
            <column datatype='integer' name='total_pitchers' ordinal='3' />
            <column datatype='real' name='average_age' ordinal='4' />
            <column datatype='real' name='runs_per_game' ordinal='5' />
            <column datatype='real' name='ERA' ordinal='6' />
            <column datatype='integer' name='games_played' ordinal='7' />
            <column datatype='integer' name='games_finished' ordinal='8' />
            <column datatype='integer' name='complete_game' ordinal='9' />
            <column datatype='integer' name='shutouts' ordinal='10' />
            <column datatype='integer' name='shutouts_team' ordinal='11' />
            <column datatype='integer' name='saves' ordinal='12' />
            <column datatype='real' name='innings_pitched' ordinal='13' />
            <column datatype='integer' name='hits' ordinal='14' />
            <column datatype='integer' name='runs' ordinal='15' />
            <column datatype='integer' name='earned_runs' ordinal='16' />
            <column datatype='integer' name='home_runs' ordinal='17' />
            <column datatype='integer' name='walks' ordinal='18' />
            <column datatype='integer' name='intentional_walks' ordinal='19' />
            <column datatype='integer' name='strikeouts' ordinal='20' />
            <column datatype='integer' name='hit_batter' ordinal='21' />
            <column datatype='integer' name='balks' ordinal='22' />
            <column datatype='integer' name='wild_pitches' ordinal='23' />
            <column datatype='integer' name='batters_faced' ordinal='24' />
            <column datatype='real' name='WHIP' ordinal='25' />
            <column datatype='real' name='BA_bip' ordinal='26' />
            <column datatype='real' name='hits_9' ordinal='27' />
            <column datatype='real' name='homeruns_9' ordinal='28' />
            <column datatype='real' name='walks_9' ordinal='29' />
            <column datatype='real' name='strikeouts_9' ordinal='30' />
            <column datatype='real' name='strikeout_walk' ordinal='31' />
            <column datatype='integer' name='errors' ordinal='32' />
          </columns>
        </_.fcp.ObjectModelEncapsulateLegacy.true...relation>
        <metadata-records>
          <metadata-record class='capability'>
            <remote-name />
            <remote-type>0</remote-type>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias />
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='context'>0</attribute>
              <attribute datatype='string' name='gridOrigin'>&quot;A1:AG152:no:A1:AG152:0&quot;</attribute>
              <attribute datatype='boolean' name='header'>true</attribute>
              <attribute datatype='integer' name='outcome'>6</attribute>
            </attributes>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>id</remote-name>
            <remote-type>20</remote-type>
            <local-name>[id]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>id</remote-alias>
            <ordinal>0</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>year</remote-name>
            <remote-type>20</remote-type>
            <local-name>[year]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>year</remote-alias>
            <ordinal>1</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>teams</remote-name>
            <remote-type>20</remote-type>
            <local-name>[teams]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>teams</remote-alias>
            <ordinal>2</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>total_pitchers</remote-name>
            <remote-type>20</remote-type>
            <local-name>[total_pitchers]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>total_pitchers</remote-alias>
            <ordinal>3</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>average_age</remote-name>
            <remote-type>5</remote-type>
            <local-name>[average_age]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>average_age</remote-alias>
            <ordinal>4</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>runs_per_game</remote-name>
            <remote-type>5</remote-type>
            <local-name>[runs_per_game]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>runs_per_game</remote-alias>
            <ordinal>5</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>ERA</remote-name>
            <remote-type>5</remote-type>
            <local-name>[ERA]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>ERA</remote-alias>
            <ordinal>6</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>games_played</remote-name>
            <remote-type>20</remote-type>
            <local-name>[games_played]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>games_played</remote-alias>
            <ordinal>7</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>games_finished</remote-name>
            <remote-type>20</remote-type>
            <local-name>[games_finished]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>games_finished</remote-alias>
            <ordinal>8</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>complete_game</remote-name>
            <remote-type>20</remote-type>
            <local-name>[complete_game]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>complete_game</remote-alias>
            <ordinal>9</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>shutouts</remote-name>
            <remote-type>20</remote-type>
            <local-name>[shutouts]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>shutouts</remote-alias>
            <ordinal>10</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>shutouts_team</remote-name>
            <remote-type>20</remote-type>
            <local-name>[shutouts_team]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>shutouts_team</remote-alias>
            <ordinal>11</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>saves</remote-name>
            <remote-type>20</remote-type>
            <local-name>[saves]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>saves</remote-alias>
            <ordinal>12</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>innings_pitched</remote-name>
            <remote-type>5</remote-type>
            <local-name>[innings_pitched]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>innings_pitched</remote-alias>
            <ordinal>13</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>hits</remote-name>
            <remote-type>20</remote-type>
            <local-name>[hits]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>hits</remote-alias>
            <ordinal>14</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>runs</remote-name>
            <remote-type>20</remote-type>
            <local-name>[runs]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>runs</remote-alias>
            <ordinal>15</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>earned_runs</remote-name>
            <remote-type>20</remote-type>
            <local-name>[earned_runs]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>earned_runs</remote-alias>
            <ordinal>16</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>home_runs</remote-name>
            <remote-type>20</remote-type>
            <local-name>[home_runs]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>home_runs</remote-alias>
            <ordinal>17</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>walks</remote-name>
            <remote-type>20</remote-type>
            <local-name>[walks]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>walks</remote-alias>
            <ordinal>18</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>intentional_walks</remote-name>
            <remote-type>20</remote-type>
            <local-name>[intentional_walks]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>intentional_walks</remote-alias>
            <ordinal>19</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>strikeouts</remote-name>
            <remote-type>20</remote-type>
            <local-name>[strikeouts]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>strikeouts</remote-alias>
            <ordinal>20</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>hit_batter</remote-name>
            <remote-type>20</remote-type>
            <local-name>[hit_batter]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>hit_batter</remote-alias>
            <ordinal>21</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>balks</remote-name>
            <remote-type>20</remote-type>
            <local-name>[balks]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>balks</remote-alias>
            <ordinal>22</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>wild_pitches</remote-name>
            <remote-type>20</remote-type>
            <local-name>[wild_pitches]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>wild_pitches</remote-alias>
            <ordinal>23</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>batters_faced</remote-name>
            <remote-type>20</remote-type>
            <local-name>[batters_faced]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>batters_faced</remote-alias>
            <ordinal>24</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>WHIP</remote-name>
            <remote-type>5</remote-type>
            <local-name>[WHIP]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>WHIP</remote-alias>
            <ordinal>25</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>BA_bip</remote-name>
            <remote-type>5</remote-type>
            <local-name>[BA_bip]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>BA_bip</remote-alias>
            <ordinal>26</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>hits_9</remote-name>
            <remote-type>5</remote-type>
            <local-name>[hits_9]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>hits_9</remote-alias>
            <ordinal>27</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>homeruns_9</remote-name>
            <remote-type>5</remote-type>
            <local-name>[homeruns_9]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>homeruns_9</remote-alias>
            <ordinal>28</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>walks_9</remote-name>
            <remote-type>5</remote-type>
            <local-name>[walks_9]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>walks_9</remote-alias>
            <ordinal>29</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>strikeouts_9</remote-name>
            <remote-type>5</remote-type>
            <local-name>[strikeouts_9]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>strikeouts_9</remote-alias>
            <ordinal>30</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>strikeout_walk</remote-name>
            <remote-type>5</remote-type>
            <local-name>[strikeout_walk]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>strikeout_walk</remote-alias>
            <ordinal>31</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <precision>15</precision>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;R8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>errors</remote-name>
            <remote-type>20</remote-type>
            <local-name>[errors]</local-name>
            <parent-name>[mlbpitching]</parent-name>
            <remote-alias>errors</remote-alias>
            <ordinal>32</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[mlbpitching_112779023741449183B85B25DF023EC0]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
        </metadata-records>
      </connection>
      <aliases enabled='yes' />
      <column caption='BA bip' datatype='real' name='[BA_bip]' role='measure' type='quantitative' />
      <column caption='Whip' datatype='real' name='[WHIP]' role='measure' type='quantitative' />
      <_.fcp.ObjectModelTableType.true...column caption='mlbpitching' datatype='table' name='[__tableau_internal_object_id__].[mlbpitching_112779023741449183B85B25DF023EC0]' role='measure' type='quantitative' />
      <column caption='Average Age' datatype='real' name='[average_age]' role='measure' type='quantitative' />
      <column caption='Balks' datatype='integer' name='[balks]' role='measure' type='quantitative' />
      <column caption='Batters Faced' datatype='integer' name='[batters_faced]' role='measure' type='quantitative' />
      <column caption='Complete Game' datatype='integer' name='[complete_game]' role='measure' type='quantitative' />
      <column caption='Earned Runs' datatype='integer' name='[earned_runs]' role='measure' type='quantitative' />
      <column caption='Errors' datatype='integer' name='[errors]' role='measure' type='quantitative' />
      <column caption='Games Finished' datatype='integer' name='[games_finished]' role='measure' type='quantitative' />
      <column caption='Games Played' datatype='integer' name='[games_played]' role='measure' type='quantitative' />
      <column caption='Hit Batter' datatype='integer' name='[hit_batter]' role='measure' type='quantitative' />
      <column caption='Hits' datatype='integer' name='[hits]' role='measure' type='quantitative' />
      <column caption='Hits 9' datatype='real' name='[hits_9]' role='measure' type='quantitative' />
      <column caption='Home Runs' datatype='integer' name='[home_runs]' role='measure' type='quantitative' />
      <column caption='Homeruns 9' datatype='real' name='[homeruns_9]' role='measure' type='quantitative' />
      <column caption='Id' datatype='integer' name='[id]' role='dimension' type='ordinal' />
      <column caption='Innings Pitched' datatype='real' name='[innings_pitched]' role='measure' type='quantitative' />
      <column caption='Intentional Walks' datatype='integer' name='[intentional_walks]' role='measure' type='quantitative' />
      <column caption='Runs' datatype='integer' name='[runs]' role='measure' type='quantitative' />
      <column caption='Runs Per Game' datatype='real' name='[runs_per_game]' role='measure' type='quantitative' />
      <column caption='Saves' datatype='integer' name='[saves]' role='measure' type='quantitative' />
      <column caption='Shutouts' datatype='integer' name='[shutouts]' role='measure' type='quantitative' />
      <column caption='Shutouts Team' datatype='integer' name='[shutouts_team]' role='measure' type='quantitative' />
      <column caption='Strikeout Walk' datatype='real' name='[strikeout_walk]' role='measure' type='quantitative' />
      <column caption='Strikeouts' datatype='integer' name='[strikeouts]' role='measure' type='quantitative' />
      <column caption='Strikeouts 9' datatype='real' name='[strikeouts_9]' role='measure' type='quantitative' />
      <column caption='Teams' datatype='integer' name='[teams]' role='measure' type='quantitative' />
      <column caption='Total Pitchers' datatype='integer' name='[total_pitchers]' role='measure' type='quantitative' />
      <column caption='Walks' datatype='integer' name='[walks]' role='measure' type='quantitative' />
      <column caption='Walks 9' datatype='real' name='[walks_9]' role='measure' type='quantitative' />
      <column caption='Wild Pitches' datatype='integer' name='[wild_pitches]' role='measure' type='quantitative' />
      <column caption='Year' datatype='integer' name='[year]' role='dimension' type='quantitative' />
      <layout _.fcp.SchemaViewerObjectModel.false...dim-percentage='0.5' _.fcp.SchemaViewerObjectModel.false...measure-percentage='0.4' dim-ordering='alphabetic' measure-ordering='alphabetic' show-structure='true' />
      <semantic-values>
        <semantic-value key='[Country].[Name]' value='&quot;United States&quot;' />
      </semantic-values>
      <_.fcp.ObjectModelEncapsulateLegacy.true...object-graph>
        <objects>
          <object caption='mlbpitching' id='mlbpitching_112779023741449183B85B25DF023EC0'>
            <properties context=''>
              <relation connection='excel-direct.13ej3ao0f80wnv19h0lk81721wvo' name='mlbpitching' table='[mlbpitching$]' type='table'>
                <columns gridOrigin='A1:AG152:no:A1:AG152:0' header='yes' outcome='6'>
                  <column datatype='integer' name='id' ordinal='0' />
                  <column datatype='integer' name='year' ordinal='1' />
                  <column datatype='integer' name='teams' ordinal='2' />
                  <column datatype='integer' name='total_pitchers' ordinal='3' />
                  <column datatype='real' name='average_age' ordinal='4' />
                  <column datatype='real' name='runs_per_game' ordinal='5' />
                  <column datatype='real' name='ERA' ordinal='6' />
                  <column datatype='integer' name='games_played' ordinal='7' />
                  <column datatype='integer' name='games_finished' ordinal='8' />
                  <column datatype='integer' name='complete_game' ordinal='9' />
                  <column datatype='integer' name='shutouts' ordinal='10' />
                  <column datatype='integer' name='shutouts_team' ordinal='11' />
                  <column datatype='integer' name='saves' ordinal='12' />
                  <column datatype='real' name='innings_pitched' ordinal='13' />
                  <column datatype='integer' name='hits' ordinal='14' />
                  <column datatype='integer' name='runs' ordinal='15' />
                  <column datatype='integer' name='earned_runs' ordinal='16' />
                  <column datatype='integer' name='home_runs' ordinal='17' />
                  <column datatype='integer' name='walks' ordinal='18' />
                  <column datatype='integer' name='intentional_walks' ordinal='19' />
                  <column datatype='integer' name='strikeouts' ordinal='20' />
                  <column datatype='integer' name='hit_batter' ordinal='21' />
                  <column datatype='integer' name='balks' ordinal='22' />
                  <column datatype='integer' name='wild_pitches' ordinal='23' />
                  <column datatype='integer' name='batters_faced' ordinal='24' />
                  <column datatype='real' name='WHIP' ordinal='25' />
                  <column datatype='real' name='BA_bip' ordinal='26' />
                  <column datatype='real' name='hits_9' ordinal='27' />
                  <column datatype='real' name='homeruns_9' ordinal='28' />
                  <column datatype='real' name='walks_9' ordinal='29' />
                  <column datatype='real' name='strikeouts_9' ordinal='30' />
                  <column datatype='real' name='strikeout_walk' ordinal='31' />
                  <column datatype='integer' name='errors' ordinal='32' />
                </columns>
              </relation>
            </properties>
          </object>
        </objects>
      </_.fcp.ObjectModelEncapsulateLegacy.true...object-graph>
    </datasource>
  </datasources>
  <worksheets>
    <worksheet name='Sheet 1'>
      <table>
        <view>
          <datasources>
            <datasource caption='mlbpitching (mlbpitching)' name='federated.1xurpiz04swff81768nnh1jlx64g' />
          </datasources>
          <datasource-dependencies datasource='federated.1xurpiz04swff81768nnh1jlx64g'>
            <column caption='Hits' datatype='integer' name='[hits]' role='measure' type='quantitative' />
            <column-instance column='[year]' derivation='None' name='[none:year:qk]' pivot='key' type='quantitative' />
            <column caption='Runs Per Game' datatype='real' name='[runs_per_game]' role='measure' type='quantitative' />
            <column caption='Strikeouts' datatype='integer' name='[strikeouts]' role='measure' type='quantitative' />
            <column-instance column='[hits]' derivation='Sum' name='[sum:hits:qk]' pivot='key' type='quantitative' />
            <column-instance column='[runs_per_game]' derivation='Sum' name='[sum:runs_per_game:qk]' pivot='key' type='quantitative' />
            <column-instance column='[strikeouts]' derivation='Sum' name='[sum:strikeouts:qk]' pivot='key' type='quantitative' />
            <column-instance column='[total_pitchers]' derivation='Sum' name='[sum:total_pitchers:qk]' pivot='key' type='quantitative' />
            <column-instance column='[wild_pitches]' derivation='Sum' name='[sum:wild_pitches:qk]' pivot='key' type='quantitative' />
            <column caption='Total Pitchers' datatype='integer' name='[total_pitchers]' role='measure' type='quantitative' />
            <column caption='Wild Pitches' datatype='integer' name='[wild_pitches]' role='measure' type='quantitative' />
            <column caption='Year' datatype='integer' name='[year]' role='dimension' type='quantitative' />
          </datasource-dependencies>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
          <pane id='1' selection-relaxation-option='selection-relaxation-allow' y-axis-name='[federated.1xurpiz04swff81768nnh1jlx64g].[sum:strikeouts:qk]'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
          <pane id='3' selection-relaxation-option='selection-relaxation-allow' y-axis-name='[federated.1xurpiz04swff81768nnh1jlx64g].[sum:total_pitchers:qk]'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
          <pane id='4' selection-relaxation-option='selection-relaxation-allow' y-axis-name='[federated.1xurpiz04swff81768nnh1jlx64g].[sum:runs_per_game:qk]'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
          <pane id='5' selection-relaxation-option='selection-relaxation-allow' y-axis-name='[federated.1xurpiz04swff81768nnh1jlx64g].[sum:hits:qk]'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
          <pane id='6' selection-relaxation-option='selection-relaxation-allow' y-axis-name='[federated.1xurpiz04swff81768nnh1jlx64g].[sum:wild_pitches:qk]'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
        </panes>
        <rows>([federated.1xurpiz04swff81768nnh1jlx64g].[sum:total_pitchers:qk] + ([federated.1xurpiz04swff81768nnh1jlx64g].[sum:hits:qk] + ([federated.1xurpiz04swff81768nnh1jlx64g].[sum:strikeouts:qk] + ([federated.1xurpiz04swff81768nnh1jlx64g].[sum:runs_per_game:qk] + [federated.1xurpiz04swff81768nnh1jlx64g].[sum:wild_pitches:qk]))))</rows>
        <cols>[federated.1xurpiz04swff81768nnh1jlx64g].[none:year:qk]</cols>
      </table>
      <simple-id uuid='{A0854498-0FAC-4061-AED8-C60CDA63B65A}' />
    </worksheet>
  </worksheets>
  <windows source-height='30'>
    <window class='worksheet' maximized='true' name='Sheet 1'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[federated.1xurpiz04swff81768nnh1jlx64g].[none:year:qk]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{9AA03EEB-B906-4CE0-9D3F-60AD36A5E2F3}' />
    </window>
  </windows>
  <thumbnails>
    <thumbnail height='192' name='Sheet 1' width='192'>
      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
    </thumbnail>
  </thumbnails>
</workbook>
