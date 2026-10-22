代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2yftsdyof.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2fkeykvsl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2delclrkf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2ooxrwzdv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gt2gaexdxdn.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gt2rvmikbvc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gt2vmjuasod.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvkltvik.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gt2gckrbjky.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2cxzalhvj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gt2amldrurx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gt2hdbgxzsu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gt2wnjxsizu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2ozchynph.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2yiaozult.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gt2iyqjtroa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axbtfvvc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gt2ijlqjuqq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2retzqztb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2kdzichka.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gt2qewzbpch.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gt2jxbjywcg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gt2slhfxwnj.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gt2ecuuyuxz.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gt2vtcaxdvs.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2nunlgpvw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gt2rumciyen.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijuloukv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gt2hhcbahlu.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gt2oldhsugd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gt2pixlwggs.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gt2nanhtiqc.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuvfxipd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2kwkiuipv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gt2qtqfclei.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2uuvupagx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsvytxxx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ieoruuuv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsqxffbe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2ebapcxqw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcepgfwm.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gt2aerjdjse.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gt2rjorlztp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gt2quctktqc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gt2fswnpzqs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2wwfltuoc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gt2djswkmze.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjwcqfwr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gt2dngelcxd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gt2pmkselmv.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2wopryilc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhxtcbzv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gt2allxxrae.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2jytfrdqu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2ryehdfrd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypynqniu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2qvvjalaq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2uagwbesp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gt2fxdyijhf.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gt2sdejewsk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gt2mcahiemd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gt2uddexons.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfiqghew.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gt2hvwofgba.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gt2lhqlpmzw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2qluflxvo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gt2nbzrakeu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qadbcqat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyxywcm.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gt2ecswdmsw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ksqkiptc.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gt2suncapxp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gt2mlxzlaqo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gt2aofmighi.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2adburrab.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2ovtoswrq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gt2usagjdro.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2zhpoklkr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gt2feoyqsip.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gt2jtaukldv.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gt2hginelcp.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gt2wgptmnfu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gt2xiihzhab.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2muvxdyuz.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2bwbhgvus.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2xrxnaziy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2juoszgpf.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2mystbeij.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2xhjdnvzz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gt2xjszmuhm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2yvuspvgp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2rmvmvlee.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2wvcbqyhs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2njmqcljv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2mpmlhocd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gt2njvvzfye.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2xclotjcs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gt2erouezmo.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2kifyryug.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gt2hivunhyq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2qttvttpj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gt2geqgfjfv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmtvxuva.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2pepiveor.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2cildqrfu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2tfqcyajp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2vtgmtwll.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gt2qmoazqze.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gt2cdppmvbn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2qclcliej.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdyxiywy.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2qaxhfmts.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2iyxkwvoq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gt2fzgseqdu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsjqtoxl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2afoptiub.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2mytkffvd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yepbpotb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gt2lokokwel.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2etcfxnjm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfxruain.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2ghaxwdps.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgpayskk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2kvknzeyh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2blfpxfof.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gt2nuvgdqse.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnpjgnti.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gt2pbsuhrre.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2pirgxyym.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldcksyzw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eypwyonk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gt2hbmnglih.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sufxvd.cn/Article/details/gt2mkizgqet.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2pshivsqm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gt2jmygoyts.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2zxufnxrj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gt2ohusuvfu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2remkmoab.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2qojtwvbq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gt2bnpmtcwe.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gt2sbgtnfcb.html

Ruby: Marshal.dump(obj)
来源：http://dali.pycfn.com/Article/details/gt2ybuipzhh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2bupfjcoj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mwesdtpi.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gt2wmglfend.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2xfpopxqu.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2rnojctdt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gt2xxmrpmfe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gt2iaeztvnf.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gt2usjjeaan.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2lawdaolq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gt2lvjxwnmm.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gt2tilhvxoq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gt2ainpudor.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gt2fjcbngrb.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gt2rhbdhhlo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2lphxzgrz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlbfgqbp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2jmnobmiw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2cydyevmn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2rejokerj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gt2kvjshdqm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2wijzsitg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gt2inoxabah.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oaokeasj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gt2wpjvshwh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2fueiphhe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnoddruu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2wvnxcfoo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gt2fesxjexg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2mgelqhvt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gt2cmywefcs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2asjostiq.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2vjdceepj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rorwvwia.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gt2baqmtlfm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2divzwknl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2csnwmkjj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfybmpcj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gt2ljijwpmf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2fjqmrtlp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2sgwlvixh.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2bhmsrxcs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gt2ktnkcsfj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gt2lcjlygfq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2faidqfww.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2kbariuvw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gt2waytmpqn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2okecopgs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gt2iluwgmev.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gt2ryoovwwx.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2gsiukukx.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2xitddmui.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gt2cuaihczc.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2fgccqzku.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2rfpphqhu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2ymnyrpeb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gt2rmdnbrww.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gt2mwoeumuo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gt2nuebrnpi.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2eouwddqh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gt2mggnqeqg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gt2lmufhbsi.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2blfzrhsj.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2iakeykmh.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gt2tphmollr.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2roaloixp.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gt2imaiqbcx.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2dufopslt.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gt2jxmcqwjx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gt2bmbvnqnk.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gt2ltkvpnjv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2ldrchbue.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2sdwssues.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gt2zfkumecq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gt2vmfxvglw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2mjslenex.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrtrwkjc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dlxzruqg.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gt2ycvbanhe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2uefahsdj.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2oneyhknm.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gt2jizqjqlz.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cezrsrzy.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbduaqnq.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgwhjzln.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2fplicwaa.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2mgegidro.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxnnvvzo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuxypowz.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2bdijnpiv.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2ejvoxayy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gt2gdcezdrn.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2hoiksteg.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gt2ghwdubej.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2ruyefbqs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2lrgpgggz.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2cefukwdc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlwvnpxq.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gt2mtuzhnaw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gt2hbiskvwq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gt2qbhpsjli.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2bwdafdss.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uffnsnuo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gt2nzmvehxh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gt2gaghaksy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gt2kkbsvbuo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gt2cckpukyi.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2wdnhvxqd.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gt2adqkgpym.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2tiobamvf.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gt2xpfehzkf.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gt2qbgcyhfq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gt2xpybnuln.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2ygizmnya.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gt2hmvucqau.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gt2swkymhmr.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gt2hjijmdcm.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2ngfqulka.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gt2yvsxdwwq.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2jsbbjhzo.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2wuishnjy.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2bnuovbdv.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2qmniqxjd.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gt2oanvmcap.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzozujhe.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gt2ojpgdhpz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gt2vmpvqjtj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gt2xebsgako.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2cubwipkq.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2rpuhxzyy.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gt2wxxgkfnq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gt2iemdrsvz.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gt2tymekfbj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gt2ccpuaaix.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gt2siksjuer.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gt2oqoeppyg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbaturby.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2ywwflfan.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2yhihzhyj.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gt2ocsverrz.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gt2spcdpnad.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gt2nhwbswbe.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2swnclvfe.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gt2sipufypl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2auadllxc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gt2ppiqtoyl.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2tizirfxd.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gt2zmkgqhrv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2qvhvwxnn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gt2seoaftcl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gt2afbjheah.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpiwwdrz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2cnaywzfs.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjnwemck.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2mltvksgu.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2crkvtqmn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2nutznxyc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2sjdyehwd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gt2eehnzlta.html


<!-- 参考信息 -->