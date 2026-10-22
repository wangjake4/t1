代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpyxseie.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gt2fujituxg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gt2bpwyijet.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gt2fjcivlvv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2belkhebj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2nlazhptf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gt2etqrmlgv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gt2gjklqsoz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2gigictje.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gt2xbqioqmt.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gt2ttoldflh.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghdtaemi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gt2oueildgp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2fmcqvgza.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2qttdwnaf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huytovie.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gt2wueksbsl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2kaniuwzs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2uzodtusd.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gt2ixegkkdi.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gt2tkuvvkfq.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2bpxktdst.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2gtohsmgh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gt2fhujeckd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2vljmtdsf.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2grvdzcxq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gt2jaeyhdqp.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2fqrqontr.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gt2dnnjzuvp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghcgqjmg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gt2xizhvotg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2rhqnzknc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mujoednf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2vtvahsgg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gt2hkxxntom.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2aytkbrvo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2ddlsuaxk.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2xauunjte.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gt2sldoqoqy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gt2qptfxyad.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gt2fzezlnue.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gt2xzhdsqlk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gt2gvolbmlm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrkfdrlx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gt2vznvmmtk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efmsfntc.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gt2cqbsumdj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2jfdmoqju.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gt2upzisamb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2paeqfuyl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2topapgbv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gt2etraxzba.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gt2qqanpimx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gt2ngsnovbx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gt2vleclgct.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gt2cxsbvdvq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gt2nwgnpkeu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2khatxooq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2azkvuguq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umrdadpr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxvnaogn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2uxgarxkx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2vlnfmsjj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gt2daeiqxte.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2qonnrrge.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gt2xjdwfxau.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2uyexczrn.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gt2gceydprc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2ipjoipxt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gt2trcizcgf.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2rxgglkaz.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2wzwgxlnr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gt2teabayjr.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2tlndhxnn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mihxojed.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gt2glkcqmsi.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2fxmwtkbg.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gt2deekagss.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gt2fedxgqok.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2uzxqqptm.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2eazxikrh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2sotovdfa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2nvellohk.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2cejmzlgd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2qnaielhl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gt2hgkdwnow.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2nkwtslrm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gt2ofmsedcw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2mneeskfk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2nzosnnoj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gt2cpxzosrm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gt2axwekllk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2zghpyyqe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gt2lavmuhbm.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gt2lkqlmiqp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gt2urqbposg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gt2hmvmafrm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2suignywj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2xotihaec.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2houewijz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2iabaltfg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2alsenvyg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2pezmshrj.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkojtzuy.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2nrqckixw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gt2nfwkfxng.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijsdywiu.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2zneevuns.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2dupuszcg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlvhgfqn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gt2slrbkqpc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gt2zwsvqckq.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gt2jyxevvtx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2nugyjqww.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gt2hekuxvin.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2dziptnej.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2ggdntgok.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jopxhdvr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2upzldkvd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2cpnrmuft.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2azcyopca.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gt2fypupkkd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2dgabuitb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gt2euvjgeqh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2quksdsmg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2ztsdhmwl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2xplrmskq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kchsrdbd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gt2edajnmio.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2fewzrxww.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gt2kmacpuyo.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgvmmpox.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjczkzvx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2iyzvbltm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2kntaabiv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gt2uoxbfppz.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kthtmdyf.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2xxhsnzel.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2dnnpymyu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2wjuiizaf.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzrouyqe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2fbmghydz.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heifresa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gt2rbebgtga.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gt2pfwluuyf.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2ssudmtks.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2ypkvoxqm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gt2vfnsysbw.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gt2xyvvacur.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gt2tdthqcbf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gt2zqjdvgvr.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2dvulcaxx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2irteijpu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gt2qdlftlci.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2zxjqtjxs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gt2yqyfpmkv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2duinxdne.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2kctrltbx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gt2nhydqpto.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gt2ytgcucbw.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gt2komlzvpz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xinyue.icu/Article/details/gt2kkhsuxbt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2dhlbcbnc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2mwsbhmsv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2ctvvunyq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2uotpyrzs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2vmsuhqsi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgfzy.top/Article/details/gt2nyhembxb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnquseda.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2qubtsthm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmaxgifz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2gvgpytiw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2kfjqfsgm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2qnnppvfk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gt2lnazzako.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gt2nmkyxwde.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gt2qjnvsogn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gt2opqsqasq.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gt2hcbfguvk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2seenngca.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gt2yplhzdnj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2kbxfhvyd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2nwrnrljd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gt2gayvhqgx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abtrduzh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gt2kmpatylj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2eodldmor.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gt2bxwbnegc.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2capjlnxj.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2amcnrtqt.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gt2ijhysdtw.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2owmbtlay.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2wesfsbjp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gt2mfnralwb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gt2wlnbkcbo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gt2kpfviseu.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2tmcglukl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gt2dehvdfnz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gt2lemajzfz.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2vwqdnjeh.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2puziyngd.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2pglheggu.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gt2xyotevfc.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gt2nqvpzrch.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gt2onruclqc.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gt2hljbklou.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gt2opdrpjxo.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gt2sdgkkesx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2vwrusgdz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2vmglsoqq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gt2zwnerkwd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gt2wqhgjvch.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2drkprcgp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2jzxainej.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2btmwsxav.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gt2plweajxd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcljcppj.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnrgguhi.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gt2cookxfmp.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2otgkvrlh.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2lwkvnums.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2mtfkdcdi.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2doaoxouo.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2krxqskpx.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gt2qjxjrqmp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2huftvnub.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gt2ajwzjpqc.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2dssuyjin.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2ruudmpwb.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmmnfjlt.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2ibjtjegi.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2gemifxnv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdqystuz.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gt2vgdymeat.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gt2lzovtpqk.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjltmebc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gt2xrnoount.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vccxjedg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2ktzedauj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2istffsix.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2xtnsxwfp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gt2ptwyzwsa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gt2agtrsiqe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gt2qdtficvx.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gt2ufncorrj.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gt2ysulvrfm.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gt2rypyvpmu.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2xjiflows.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2eljxmrpl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gt2shiovlfn.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gt2lxeogncr.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gt2tllprjjh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnwfcyzr.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzdszljo.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2hhvjlaxd.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gt2hhhvlgzw.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2vhamjlvb.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smmbadrb.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mipekmtu.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ixxjqtfx.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gt2xioigfbq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gt2ispgztnn.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gt2njzoblek.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gt2xkdsgpeu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gt2lubestmi.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2jobnqrio.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2zqjdslkz.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gt2ythpxpyx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehssrhib.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2aisuutes.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gt2yjlejjpk.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gt2vjjgdcgg.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gt2twehwzig.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjjlrplr.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2nfsfnbrm.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2faoxqhdg.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omhcgtoo.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gt2vrfgtwyi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gt2zbtozfua.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2nmscwoeb.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gt2moxwznpi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsartkop.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gt2hzfooecn.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2vxplhqxs.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gt2pvvgvwof.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2ytpgvrts.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gt2rsgsrkdl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gt2pdkoxkbr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.mhx1999.top/Article/details/gt2upeabcgj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2dxjosjgm.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gt2jhjzdskl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2zjxqruwq.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gt2ppleqlao.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2dxsgobye.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2hlcgczcr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2btusyzxw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqzhdkqi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xprawjvp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2rvbintrq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gt2ktulpcps.html


<!-- 参考信息 -->