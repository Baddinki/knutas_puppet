Kaikki täällä oleva materiaali perustuu Tero Karvisen Palvelinten hallinta kurssiin. http://terokarvinen.com/2017/aikataulu-palvelinten-hallinta-ict4tn022-3-5-op-uusi-ops-loppusyksy-2017-p5


SSH moduuli
class ssh {
        package { 'ssh':
        ensure => 'installed',
        allowcdrom => 'true',
        }
}
