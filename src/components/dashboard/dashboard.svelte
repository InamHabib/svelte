<script>
    import { Tile } from "carbon-components-svelte";
    import { Notification } from "carbon-icons-svelte/lib";
    import "@carbon/styles/css/styles.css";
    import "@carbon/charts/styles.css";
    import { StackedAreaChart, BarChartSimple } from "@carbon/charts-svelte";
</script>

<div class="internal-container">
    <div class="left-section">
        <div class="chart-header">
            <h2>Annual Views</h2>
        </div>
        <div class="chart-body"> 
            <StackedAreaChart
            theme="g100"
            defaultFillColor="#9fd3f6"
            data={[
                {
                    group: "Views",
                    date: "2018-12-31T18:30:00.000Z",
                    value: 0,
                },
                {
                    group: "Views",
                    date: "2019-01-05T18:30:00.000Z",
                    value: 37312,
                },
                {
                    group: "Views",
                    date: "2019-01-07T18:30:00.000Z",
                    value: 22392,
                },
                {
                    group: "Views",
                    date: "2019-01-14T18:30:00.000Z",
                    value: 52576,
                },
                {
                    group: "Views",
                    date: "2019-01-18T18:30:00.000Z",
                    value: 20135,
                },
            ]}
            options={{
                title: "Average views",

                axes: {
                    bottom: {
                        title: "2022 Annual views graph",
                        mapsTo: "date",
                        scaleType: "time",
                    },
                    left: {
                        mapsTo: "value",
                        scaleType: "linear",
                    },
                },
                curve: "curveNatural",
                height: "400px",
                color: {
                    scale: { Views: "#2ba1c7" },
                },
            }}
        />

        </div>

        <div class="chart-footer">
            <div class="bar-chart">
                <BarChartSimple
                    theme="g100"
                    data={[
                        {
                            group: "data",
                            date: "2019-02-01T04:40:00.000Z",
                            value: 10000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:42:04.000Z",
                            value: 20001,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:44:08.000Z",
                            value: 10002,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:45:08.000Z",
                            value: 10062,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:47:12.000Z",
                            value: 30003,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:48:16.000Z",
                            value: 20004,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:49:20.000Z",
                            value: 10005,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:52:24.000Z",
                            value: 50006,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:54:24.000Z",
                            value: 20006,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:56:28.000Z",
                            value: 40007,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:57:32.000Z",
                            value: 30008,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:00:36.000Z",
                            value: 10000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:02:36.000Z",
                            value: 10000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:05:40.000Z",
                            value: 20000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:06:44.000Z",
                            value: 10000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:07:48.000Z",
                            value: 30000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:10:52.000Z",
                            value: 10000,
                        },
                    ]}
                    options={{
                        title: "Vertical simple bar (time series - dense data)",
                        axes: {
                            left: {
                                mapsTo: "value",
                            },
                            bottom: {
                                mapsTo: "date",
                                scaleType: "time",
                            },
                        },
                        timeScale: {
                            localeObject: {
                                code: "tr",
                                formatLong: {},
                                localize: {},
                                match: {},
                                options: {
                                    weekStartsOn: 1,
                                    firstWeekContainsDate: 1,
                                },
                            },
                        },
                        bars: {
                            maxWidth: 200,
                        },
                        height: "400px",
                    }}
                />
            </div>
            <div class="bar-chart">
                <BarChartSimple
                    theme="g100"
                    data={[
                        {
                            group: "data",
                            date: "2019-02-01T04:40:00.000Z",
                            value: 10000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:42:04.000Z",
                            value: 20001,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:44:08.000Z",
                            value: 10002,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:45:08.000Z",
                            value: 10062,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:47:12.000Z",
                            value: 30003,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:48:16.000Z",
                            value: 20004,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:49:20.000Z",
                            value: 10005,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:52:24.000Z",
                            value: 50006,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:54:24.000Z",
                            value: 20006,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:56:28.000Z",
                            value: 40007,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T04:57:32.000Z",
                            value: 30008,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:00:36.000Z",
                            value: 10000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:02:36.000Z",
                            value: 10000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:05:40.000Z",
                            value: 20000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:06:44.000Z",
                            value: 10000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:07:48.000Z",
                            value: 30000,
                        },
                        {
                            group: "data",
                            date: "2019-02-01T05:10:52.000Z",
                            value: 10000,
                        },
                    ]}
                    options={{
                        title: "Vertical simple bar (time series - dense data)",
                        axes: {
                            left: {
                                mapsTo: "value",
                            },
                            bottom: {
                                mapsTo: "date",
                                scaleType: "time",
                            },
                        },
                        timeScale: {
                            localeObject: {
                                code: "tr",
                                formatLong: {},
                                localize: {},
                                match: {},
                                options: {
                                    weekStartsOn: 1,
                                    firstWeekContainsDate: 1,
                                },
                            },
                        },
                        bars: {
                            maxWidth: 200,
                        },
                        height: "400px",
                    }}
                />
            </div>
        </div>
    </div>
    <div class="right-section">
        <Tile class="tile-container"
            ><div class="tile-content">
                <span><Notification size={24} /></span><span class="text"
                    >Notifications</span
                ><span>1000</span>
            </div></Tile
        >
        <Tile class="tile-container"
            ><div class="tile-content">
                <span><Notification size={24} /></span><span class="text"
                    >Views</span
                ><span>1000</span>
            </div></Tile
        >
        <Tile class="tile-container"
            ><div class="tile-content">
                <span><Notification size={24} /></span><span class="text"
                    >Alters</span
                ><span>1000</span>
            </div></Tile
        >
        <Tile class="tile-container">
            <div class="tile-content">
                <span><Notification size={24} /></span><span class="text"
                    >Messages</span
                ><span>1000</span>
            </div></Tile
        >
    </div>
</div>
