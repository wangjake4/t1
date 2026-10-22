代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gtjphxikrl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtctdtigpb.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtvxfmtsho.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtrevvsrie.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtrahixiax.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtrlxbbntu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtmxxgdpeu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gthmsussys.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtahlalecu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtscvdwznk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtnjjzyojs.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtqhuaxdhi.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtuiapdydi.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtlfawcetc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gtoujtlyqe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtaorlqeka.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtzbndkgtp.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcopvywzy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhongyouzk.top/Article/details/gtlsdnwhud.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtoozrijki.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtjaxndlvo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtpxwukqco.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtrxamzfhf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtnenxlcxa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtckenxzgh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtceuethdz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtcnzvpdjq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtkrsteswf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtutnarkpo.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtxjjkruve.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtbcyfsibz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gtxdfznqub.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gtusxxgrdf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrzorpyd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gtsxaudnbz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtdlujsckt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gtsixjziil.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtfrqqdant.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtnctjetru.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtncunfqkf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtwtdhyaou.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtotdsqvxy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtxbfihgfw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gtkmchdcdp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gteiztjpbe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gtdtecfirw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gtasbxtkoy.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtsnmwaomv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gtokisrgol.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtzntvwhki.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtdqafgkzt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtbnzrlzbg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtazdlywkd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gtwqxxzwhg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gtgzdrvedr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtvpthkydd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtlaxxzfsc.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtctrepdfn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnbhigiio.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvmaxysf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtaqmrprrx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtspwzfnsr.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtugjivrky.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtxfevnifu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtbiibzryt.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtyymcsbur.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtcbrkowsy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtttrawuxt.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtlhnvpqth.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtynaqbjhp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gthhuryvjn.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtvaywywtv.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtcbvsqaem.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtilqwyvlx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtpksayswi.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtuzdgzfph.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtdayzjemo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtlaiqgsoq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtaffbrkzi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtexxfwgmk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuvhejvbz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtasaxyfzi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtsmragzeu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtpovdfpfm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtibjsvgvm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gtyfizjntj.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gtisykpeub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliqvgmfv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtiixqtgqt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtzdctpxvh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtsmefhnnq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtteuikiwd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtefklqnwu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtfhjnndgv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtjzqrirol.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtgkkdfwpo.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtuwvofbuo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gtatbyotrd.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtfofkyhsz.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtlvnwnjqm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gtiekzombt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtvnpzcnel.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gtdnhnupaq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gtlsymaxpn.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnqmwghh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtzfhjyqcw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gtdjpjgvuf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtcaaftvme.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtgyfdwyon.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtohghizib.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gttrpfyozy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtmnmyuhyc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtbhzoozqz.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gthubnpfbh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gthieehohv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtfiexwoek.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtdyyteowh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtxwhsnqnm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtlirlmsvm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangdashe.top/Article/details/gtwxceowba.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtwtvwsudg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtatjoyxck.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gtehiubdio.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtuuntilbh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gtbheeqwya.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gthsuvskdf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtktchsfre.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtgmswxqbi.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtcdraqrqo.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtbmrgqmpk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtgcsxjctx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwgglbwst.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprwyzuxc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcvvvjsbc.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtnrgprymd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gtgtxgucfe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtokxkqovy.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtjpgfjvoz.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtdbvhxjsd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gtimhhneuv.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtjkmqtezh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtuvaeavor.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gtbskabngr.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtsdmqsehk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtqiwnljdg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxuuiwup.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpfkhulx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtqstdylsm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtyfegdcxu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtlyeujucp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvhyvldn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtanmnuduk.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtjyatbvml.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gtzshrejuc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtrctfnvlh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtgtmcceht.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtddazdedk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtlwexhwbx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtvuaimsfg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gtqbxhxomk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtmvoowkys.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gtqepoufkm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtrcrdehhy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gtqrmfkmkg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gterfjcfhj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtdbzqfhgh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtzcuhpnez.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gtggsqbufu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gtrriwvnqq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsufpufl.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gtuuvgkbir.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtkldoxkeb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gtzyprcsml.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtanbkeqlw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtnkdiacky.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtnvfsddis.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtsoohiqrq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtpqhrtxry.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gthannuror.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gtemqxumse.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtyzskmtcg.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gtxpuxusfq.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtmxaxtbus.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtiwdfregi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtnzhlwtvr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaappevwp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gteqjaloep.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtluielkrr.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtobzudkwc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gthovuocpj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gtdmvhqdxg.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gtecejavfn.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtcoxhwunc.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtjcbyhxul.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtbxevgiuo.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gtnekwynjf.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtyqkvalcq.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvlbnnjc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtjpuevtcr.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtnhfyfyah.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtwtdskdla.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtrscyxyem.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtdlljdugl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gtkkrngflq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtdchlvstd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtlzmzmthy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqkxsljuy.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtgbqfljmy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtichljvhy.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gthbhsntmk.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtcltzjteb.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtbwcbazbf.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtumdsatin.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfhjkspqc.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtboquvqry.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtjnzhlybj.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtixyizygw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtvzwalbyl.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtqdkrezpp.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnadcivgc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gteyyvixyz.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtcxxlcaqo.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtnihmnpuw.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtxomseieh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtldyjokwd.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gtinwjqjbc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gthsffptaw.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gteewxszzd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtxqdgiehm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtgsooyayc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfmemata.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtnqemlsqw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gtqutpdmhb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtobllavkf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gthmczkjty.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtoxpicvko.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqnjpqvk.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gttllclgps.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtusetobfu.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkcdorno.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtqoizduxb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtnygfrham.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzrqirtr.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtyhwxgxlx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtdsrgxvri.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtqkotmrva.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtljufjcmh.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtnoavpket.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gteaehxunf.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtnvlpauer.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtiavtowrx.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtaykjjdde.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtunisbpqk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtcxgzvgiu.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtiuournru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gthbzpcgaa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtgphxpocp.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtjcnojise.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtfdamkwfg.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtyolzwfvs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtbhedngbi.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtlrbkfqlt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtzwfgmhff.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtmnihbjtd.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtoznwecao.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gtiwkugpwe.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtzsbmrxnd.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtpgzvcjah.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtgdykgtxy.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gtfzjhitoo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gtborvvrlm.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtifxkkotu.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtkranqoly.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtkgubewpn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtvacnrawd.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtyuryahcc.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtwcdsboqe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gtdfhcdpav.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtycahqboz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtlpxxejgl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gttndbmtrd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltyicpjt.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtagspmvjd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtyzlhcufh.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkizhxerq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtjijrotde.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtsgwtpsze.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtztyaomjt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtrvwdvplp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtjnkelxme.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtliwlcnbt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtrlydqqvi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtorrgedhn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gtjyxqmjzs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtglwagstp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtfpqagtrw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtpkbtssqd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtottehfjb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtocunxyfl.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtdrrxdzzz.html


<!-- 参考信息 -->