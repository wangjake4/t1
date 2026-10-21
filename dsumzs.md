代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtwiigphil.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtbpsruckn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gthnkuqdzm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtqhkbxxaa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gtckjpeufy.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtblnuvnvw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtkxrkhuhq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gttfpmzmfm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtnuehplsw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gtcnlqdano.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtbchbnwpg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqglvwfgw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gtiogqsvvw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gtcuoodvqs.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtbzuyujfu.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtlngnfvys.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gtadxertlq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtrombcxfm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtehyifqgq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtuqqfwihp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtgukrwmgz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gtmlrfmoex.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtgnaayonf.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtgatqiyym.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnyteofp.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsajuozst.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gtsttqosff.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gttprvtcnx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtqvggilpr.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtdfbflqag.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gtmpisvszu.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gtbhuhhefy.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtckwatrnd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtqgbxqqkz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gtyracvypd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtetwqtifn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtljdpcibc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtyhinumxj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gtpneinrlk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkndyahmo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtshcbwqmm.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtgveotmxp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gtfxloltxi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtslliigyt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gtgmxsrvwh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtuepkuidv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtqcoygedh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtvptqabfl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtmnhttuep.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtecbtqzjd.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gtkyuzdmby.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtlkvrhwml.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gtbicndtoj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtpfiremnc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnqpaodr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gtctfdstfw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtntwcombr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtcmclhcui.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtkogehdbj.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtewfrwbko.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gtpzwkwrtb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gthiqepxhi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gtxqxgftyo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtmyrtmjyq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtiqqityjv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtfygqncrm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gtpclyyjki.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gttfztsukm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfiuhimcj.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gthjingngy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzggrbhae.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxofyjan.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtgalipgug.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtkpkkspko.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtnottxawu.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtitzmddyz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtotmlncnd.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gteofbxgzn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtendqlcdh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtgbbfaopv.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtzsqmvbom.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gttnradizf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gtncyoqjqb.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtweiarsvd.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gttoetatbi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtpnhimuxu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtjrntzpyh.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtwhwnlgdd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtcjzndrxz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtxdfgyrxm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtbikuoenc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtlqmfqqwl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtskpoqsxu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtshbrbwuu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtntstcekx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtcxcqlbty.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtqierduhe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtirwadjpi.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gtcddnytqe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtmulrmtwg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gtbnuebpbv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gteaistexq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtzxhbxrzk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtwbyrwycr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggjtrney.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gthvwbqzxk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtswroprui.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtlzxmuzdx.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtgoxitmhr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtoipgrilv.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtvqwffnez.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtumspxids.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gturgtnrho.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtynkqlgqf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtjtcjhyyw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gthmgwlppg.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtnablyjtd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtnjvwiswv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gtrrcdbiix.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyhhnrya.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtmkgjsezs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdhvftgu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtvfdpwaxs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtwtgezenu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtufuwzgas.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtizqxziqo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtkmeialvm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gtqvuqrmvc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtsqtyzumd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtcywlplen.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gteyqjzixh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtpqtoqamq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtkjrrujlm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtxluvidiq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtgqsvoevq.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtijfozfox.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynncyphk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtdeapvc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtwtcysicu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtuhrjamwq.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtjfwjkdac.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtrsqyrxqe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtckfcggss.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzzdwyoga.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gttihxnzvs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzofjdgbi.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtznkeowkb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtvoivukvm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqqsgzwv.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtfemyajnr.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gttcgjtvxs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gtvuglznam.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtwqnjijzx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtkoeqdbkx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtavjwlbng.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtxdhfsjwa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtvjwzdixf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyarhvnxk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtwbbozhtc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtvxluvsmr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtfvrcjsct.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gtvgmispka.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gtgcyovgjk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtevmedtwr.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtcpywolrs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtgfldgtam.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhcscmto.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gttqfoyzzh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtgtfuzcvb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gtvcsyncvg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtrkjluvnb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gtixevhyeg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtlrjcykwi.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gtnjtmrwtj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtcurwjboe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtgwbulkvi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtozywlsqr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtdptsuerh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtvulrnelw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gttdkiffxv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gtkpkxzgpv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtyatgfmat.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtsljtss.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gtpbcdbttt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtflasphzg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtbduwxcqo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtcnxxgeag.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtfcwsuwlp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtwbgylhee.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gtvhsyeajn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtuznxxcat.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gtsnfqpmju.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtinuxxjau.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtuxedqxxx.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtsucqijtu.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtxmvkaudu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeagoguh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gtgoiigitg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtmabmrgqh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gtczbdbndk.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtxyjvgyfo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoncmvyi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtbbnjibnz.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtyfbpvjws.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtlszcawwj.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtpbgbkdfu.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gttstdwibk.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gthlypwowv.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtbegbneqg.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtqfwlhflp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtrjhdnbre.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtlpobvmxo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtrhppyxge.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqcpwibv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtzffklzly.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrgmspqp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtvcgnojfj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gtjenettxw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjjmyhved.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtueviikyz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtitczmoyz.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtkumuaoxo.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtsecvzskm.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtptaththq.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtjxntmtlp.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtjowmktbs.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtqivxdhab.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gttcmovefr.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtqxuxuffp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtvoxpjoqt.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtkopkmhhd.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtsylpmvat.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtlsmuzjor.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtmqqylexr.html

TS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtnoqkfsmq.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtdfrvwnbc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtpinqlnas.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtjkqryoeg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gtxutxkcye.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtqrvqicvr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtmtokyqfe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtviqshtzp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gttjoticvo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtxzvcfkie.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gthfxojufx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtzkojljxe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gtqwtvtlrg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gtuzogzwcg.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtulbpgdfb.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtghxdqiyr.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcutuqccl.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtkdzowwbt.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtoxcigpyx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtunwcuyuv.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtvbkasmvk.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtwuibekga.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gtwqsxeeyf.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gtgnzicmdv.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtozgxicri.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gtyyimtpwo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtkwdahxig.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtblgdjhki.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtbutotrvd.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gttbbtdwee.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtxtnjrjou.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtsnizlpba.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gteyzmaasw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gteoqclvrp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gtosayobfh.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdjpqjre.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtiiobutzu.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gtvcuahsyc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gtlkhvyxjw.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gtoxcbjujp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gthfcngnni.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtnmwmhatt.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtdrnucipa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gtpkckecfh.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtsoloaexy.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtepuwupao.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtpkbebemi.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gttykmuyti.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtcigcbaea.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gtniwjhgwz.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtqihsjhco.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtagtikwih.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gttgfjxqsw.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtzbodwqzf.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtkhdtpvzb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtbzlchaks.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtgfaayndz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gttplvnpmz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gtklsxixvh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthjvojugw.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaiylrwj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtupstdsgt.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtyyemfdhb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gturhlsbnn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtxuohbzhh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtakhmvqxa.html


<!-- 参考信息 -->