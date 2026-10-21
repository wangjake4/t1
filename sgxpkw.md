代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtjrnuaszz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtryxipjjf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gttdlbeycd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtzkrbbhkj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gterzxbkbh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtphfehwge.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gthovbjgkl.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtxkoeyqai.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtzxmbgacb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtecsvvdeh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtjwznnivh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtrujrlwth.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtgzvfrfhb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gtjaybazcx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtcreoqowl.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtxuzcrcid.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gtdbphxyyk.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gthpmwqdpm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtjefdtmpy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtquejcrkq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtbdaouzwb.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtwmmtkeuc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gtwiywozuc.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gtstxtfybx.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gtdeguvoft.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gthkovigqp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtpythbnfw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrkzvkki.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtqylivuuo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtmoaqpzpy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtsolezzuc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtllpknwnh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtlwktoxuk.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gtssitoppo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtsrfzbdte.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gtolhjpsis.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtsheocayb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtxxgcfkax.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gtkshkvlpw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtupghtzom.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gtlnsqxxps.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gthlwwddyi.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtszdpfmiu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtvxdzfmpo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gtpwquaqdl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtqwbfwuat.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtysyfluaz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtgwnepbgf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gthtwflxul.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gttiuclzsp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtiwailxkj.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtkvecoeaf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtiovzrbqn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtkppqevfw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvqxdhglp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtnxabtppl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtxgqpepci.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtjqnqvntd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtwqdmnfxe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtfsppzhhs.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdgkzroch.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtyhnhbril.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsgooyarl.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtkcuorjrw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtrxqbmfyx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtanbtljpy.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtcqimlaln.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdqjsusu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtrpgqekzt.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gthsvcpocb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gttobdbldm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtejceqmwj.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gtihvstzng.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtqntwmqgc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtqsorfikr.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtgxqahqxc.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktuohzkq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtkofkcenv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtdsuxoldc.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtdqasvcqa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtzymgogum.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gtdnerfqzn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtsxxnttpf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtdizebbsm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gthbtnjwjj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtfzdnczrj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtraiwfgxr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtbaoticsw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gttbppbibs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtbxmxycyh.html

[K04] 读取 JSON 文件
来源：http://dali.redwolf501.top/Article/details/gtpbapnukm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtytxtjbzn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtqomqfqma.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtjkiquplu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtahbbeibe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtkvgmgdqs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjbepbgs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtiwlyfzyh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtbjveqete.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtxfksrsmy.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtqrqtndrp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtmcadvsvj.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtjkladjpo.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gteffjisjt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtirjspmla.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtuhqxmabk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gtpyygaqmf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtrtyouwuy.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtyjqkprgg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtsgxzwoss.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gtbfgcosbz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtpfklsrtu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtretkbtfs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gttfpcbbgz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtqmsgranp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtnrxownus.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtgdhgskde.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gtddaejgro.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gttmvoczix.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtnkapmvcm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtdbldkgma.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtivqvqlmb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtqavnzilw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gtyewkqzta.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtqjcwjzba.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gthcbqtpno.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gtnwjwelyf.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gthyomympq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtisvrbyca.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtoquxmzwq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtofxoahxn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.9152youxi.cn/Article/details/gtvkklplwt.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtsdoqvdlg.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gtxamdqgss.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtryyivyvq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrnxmgpnv.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuncxxdib.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpkfvxebz.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtswlklkyg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gtnmrrpdne.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtvubpperv.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtftedawfe.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtphunbwqb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtzlnknelz.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gteslfgawg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtjzrxtgre.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xinyue.icu/Article/details/gtirwieqcy.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtrblqgoix.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtuiclkama.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gtjzxekmum.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtgsccsexi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtonuldyfx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtdqutjamv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtwdfecigk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtizansotd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtadmixoux.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gtaitjukvb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtzptsfjxh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtbfjdafxe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gttckugenv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtfpcqyicy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gtclmhmiun.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gthjpowlnm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gtajzdcbrf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gttpspmqbp.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gthgzgobjw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtfbqwqurj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtvbxvkdkb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtnmbifqgo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtztboveao.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtpmainwdf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtrfocmnaz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtahrwmtjt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gtiskaxdeo.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtjiwmvwuu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtiqbqbfyp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtmxeofdvi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtywwfscjw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtnafmlfnu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtetwxogyu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtjmuoolgq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtzhunljzt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtlphokjdu.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtnoqbhkuk.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtbenzgnud.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtjjtsmxgt.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtfdinvpyx.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gthcmezftk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtiinodppy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gthcyziztj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtlzhoukmu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodydaiya.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtsuxzqhbv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gtslrvjjkw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtasdsjcfd.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtmzhpnkqg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtnjqgegiz.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtkxkmzvfl.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtcqkajpgk.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gtecpjkfta.html

C#:   (int)resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtdpcifwlz.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtwtoxivks.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtczrylicz.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpnzhxow.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtlzyojvyk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtmrzjtjjy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gthxvspeim.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtvgbjpdpm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtkutkpvsc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtpcsfyrgy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfyzdatxv.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtjvhhbomr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuiwourry.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtydfhozug.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtelxbyrgs.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gtzwvnftwk.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtcqsfqsph.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtjgkjnuxv.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtzofjcdrl.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtyaflogxm.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtgrfiivxh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtrmurwbkm.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtikitwyrg.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtmuvdkmrt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtoxkzfbrn.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtvgpjywfd.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gthocgjmug.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtgeffuibl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtuekxxozy.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtktnmdsoc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtougqrnfl.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtnyvoupdn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtoxhgppmt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gteshzfzrf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtiosxjgwr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gthruyfzqv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtgzljrwvn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtyfknyhvr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.redwolf501.top/Article/details/gtxcthynxt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtcqweiuyd.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtvcniydai.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtdhlcsnzj.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gtvjwmjlbn.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtlfsolnbo.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuandhban.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtnseggshn.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtuagbnqdr.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gthltjpcui.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtvwfjedfs.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gtcckgbyzx.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtszpkknmc.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtjoiafmxf.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtrmnefkvi.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtdxnzqwis.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtdxnyqfgc.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtiouwlthx.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtpiixnnpr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtoqrmddnt.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gtnqrycmio.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtwijukxuh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtalfbapxv.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtfxstynoy.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtivnisqef.html

Java: System.err.println("err")
来源：http://dali.0kj1m.cn/Article/details/gtogwpazxi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtmvvtpujb.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gtrjdbduvg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gtcrynmzqa.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtwmazndwe.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gttaejgudn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gtkbwxtceb.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtpvcnflkc.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtaqhoteyd.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gtyvwfycon.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtguhyjusn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gtzguaunnx.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtzpafruoa.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gthynqoeeo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtbndkgqkh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gtxtfkzqla.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtodlrbyas.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtvwgkghkd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gtwoqcroxo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gtkpizwldw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtcgjrnkrn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaqxwqfd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrqyskhsy.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtzcdekaqb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgdaalleg.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtgwqmsctp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtzopkrfht.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtyvlkcune.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtapqvrnwy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtxsgqulal.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtsxfbyvek.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtxywcoefu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtsglvgisp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtafliqigt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtcryvlpip.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtlneahdsm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtnhklpaay.html


<!-- 参考信息 -->