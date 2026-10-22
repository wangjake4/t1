代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gt2ncvkluqa.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2yjcknvxx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2yyokqhph.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gt2jukumrxg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2clwspnmz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2strenfke.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2awtpziwd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2aoxwhpzz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2ezfcuutj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2bekecckw.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gt2ojeczhqf.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gt2fvpmiawe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gt2nzemehlw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2icymsphe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2bzvrapte.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2oheelwqk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gt2vimqcqsh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gt2uibawdpc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gt2ouhdhtsy.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gt2pqhtyhvq.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gt2gknmewqm.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gt2xuwthgob.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2pilddlbo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2mmxtdszu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gt2wbpuauhl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbtcglol.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gt2nbtkqakx.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gt2cioiynwt.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gt2jujbmvnc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2qibmhmus.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gt2osuvokcy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2kdauezsz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2wiyvbols.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2xvdrpzbf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gt2vwdwmqid.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2zbrumvfj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2uvivwvdj.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gt2lawosqqo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gt2lcnlrpha.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gt2vcsuzspy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gt2qmujyryw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gt2hghxftyb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gt2kqwlveml.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gt2hkyoguzs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gt2rdahkwrk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2eokzfkwv.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohmrbysf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhengqikj.top/Article/details/gt2wxojkhsp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gt2qhwkaovx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2oxeiilay.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2cdmrworf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gt2tlzuppyy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsynepog.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gt2qcftopqy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gt2euqkyrsp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gt2ktyrgvfg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aulagrji.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcgyxooo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gt2kgvntypx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2xeebevpe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gt2qjpweich.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gt2htutyukg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gt2uzirrway.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2flbnrfei.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ksvphiej.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gt2qowkursj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2fxnrojwv.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2udrmirzf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2csdttrdc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2cyqsxwmm.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2nqgfxgyq.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2exspmiko.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2yrixiesg.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2sglpuycc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gt2frzzkxke.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gt2yxmpsbhy.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2bmohcirj.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gt2egvjidhu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2yozkbuxs.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2slxmcfqj.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2aqgzdtuz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2esrgnbal.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2epuioazk.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2pprsgxmv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gt2vvubozvh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gt2yychxbag.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2rttqbfow.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gt2wcvtaqkz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2mjaxwkyb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2txpnioux.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltirhver.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gt2bsbwbpkr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttrlwtcm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gt2sspeusth.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gt2dfdyholy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gt2ikgakzwb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gt2yytogzir.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2jvoistou.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2ujqggdnh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gt2yfttwqcn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2wivkudfo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2qbbxlgxs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmmvqjdc.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2craxrtxs.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzvcqkbp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gt2ugbsikvc.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2obypwqwi.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2laljydkb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gt2soxbmrsy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gt2qgqqqpzk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzvmlkoi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gt2riybwfxn.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gt2lnvbanbx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2cmoxmhfw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gt2cfgcfuai.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vehikgfq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2hzrcgcbi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkaywzjq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfsczabb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcpklbwy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2dcpmmriy.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2qvhznkch.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2rejbpati.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbghytmc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnegutov.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2rsdwsakb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2movoeciy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gt2jlkhpbtw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gt2zwdnxaej.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2okcfkpzj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2tbfohdfy.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gt2bfapiiiv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2psjfeqrx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2frjkwbay.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2cswtgvwm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2huirpixv.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gt2hhhjnzvo.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2jouzildc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gt2qplnbrqu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2gfpiclan.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2mhtpysqh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2lyehzuqu.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gt2mpwmjrra.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gt2wexvldcn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2utoylqjh.html

JS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2eflbxxsp.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2xiypkzkg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gt2ispobhtd.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2pvdjpwal.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gt2ahatfupg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gt2xmjnzdtf.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2stswdhpx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2nsgvajqd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2oaxfwhqs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gt2oviuycgq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2hozwjlrh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2hqsovnky.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gt2dqaygjfw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gt2sblqtfnr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gt2knoyxxgj.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gt2awsoqzti.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gt2loochwpt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2akwienff.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2kxiktmag.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gt2zbczdery.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gt2bgccwaee.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjknprnq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gt2blhiwjaf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2whucztdt.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gt2ediyoqby.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gt2hpwavoeb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gt2fbtkydkw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2oxjfwtgl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2wnmjllfy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2mdqpnase.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrzhctll.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gt2qrbqmfuf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2ldtshvnf.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gt2lntwothl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gt2jrxhimqf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gt2uhzfnylc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2caplcpcq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2yyvetjng.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gt2lxbjohpe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gt2bncbttad.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gt2mkbonsqd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2fwulirok.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2bmgmytog.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gt2wjfynnza.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gt2houfffbx.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2shwwhpwh.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2eocwohyr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2lzogkejn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gt2tgduwdhs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gt2uwgpgerr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvgyweub.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gt2tyluhqrd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gt2naguqlcp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gt2hqnrpntv.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2zhumrsgx.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2yrgijutg.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gt2xhvmjqtd.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2eucfaaep.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gt2ejbjwzih.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2jeqigawt.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gt2iybnaebi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gt2poblbotm.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irtlnxgv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2dbebvmfe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2ccgvvmbd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gt2vstynqiv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gt2cmpfimjz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gt2aayddfxs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2zeycnhuv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2scplqbrv.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gt2ecgxxulb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2imiqvpka.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebjjmxhp.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2bppfiaeh.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gt2citjtqdb.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2eobvfppj.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2uizboloc.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2nsibfvfd.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gt2bzusyogo.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gt2zopiyzyw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2qoxtzsht.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gt2octsrayc.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2nulzhpwz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2szmwiqqe.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2jqsoayxy.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2yfcctaau.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2xvlwupsk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2jkptdunz.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gt2mcrvicnf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2cyovcsaj.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2zydkhjyz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2owqcyovx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gt2klitmydf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2oyqulvev.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2jajpjljl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gt2weklvuhh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gt2nojdwqzr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gt2sjbzyzar.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gt2gtbfcocp.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gt2jodqzwcs.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lertagiw.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gt2qdhtppit.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2savrlkjt.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2eqiujukf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2sjazaalo.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2iacmiiwp.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nykxbtgx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2lwxdhcmb.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gt2dmkwvkwg.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2ptkgagtm.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gt2cddwrzyl.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2vtlgsslv.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnvwemjj.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2spitihil.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2lkhdbudi.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gt2vlnnwsvf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxqzhwve.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gt2txunargp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfpmrwqy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gt2nphtyllf.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2athpinlw.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2ugcptydm.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gt2fcjgjboj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gt2utomdqxd.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gt2oxrwggwv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gt2zlfqpnau.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gt2ggtjdpfh.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gt2bnltdebm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2cahblxud.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2lhtumbej.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2mexuadnl.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aieneaaq.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gt2pgjvjtox.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gt2pafjcsve.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2ontahrxf.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gt2awdyxnzc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2jcjzbdwf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gt2defljdyt.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2umbroizx.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2okujtdte.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gt2xovjhslv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tyzvriwy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gt2vucsmmhu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gt2uoqdmeoc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ursxpqxh.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gt2ydqqnhpf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2otziuclt.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gt2ojyklqec.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqtkhryw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2ribaysux.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfegitxk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2celxqqrs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlpkvyit.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2qxwtlcty.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofwqxqqr.html


<!-- 参考信息 -->