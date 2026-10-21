代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsupbgqen.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtftlhizta.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtiqltehhs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtaqhrsqrp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwpelrjn.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtywabyqzo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gtbbezryqk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gtksqlbtgr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtaxbmrefw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtaxfrovto.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gtakmtamnn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdjwtzek.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gtflemoyce.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtbhjevjda.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gtsuixpygj.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gtapickunk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtuhhisjuc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtixskouuk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwcgszcz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoslktnm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtqzacgmbz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtmqywxoto.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtmpfhpllb.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtxyjpioer.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gtizfutymc.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gthdjalcvi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gtofbryzbc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtoqpyhlru.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtippdsgqx.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaziqlfj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gtqquobjsz.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtwymexcrf.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtdwcnhdus.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtnjhaljmk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gtbfofmqlq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtvluivswg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtermqdsvw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gtmpusiwqc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtlzwzmfnj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtefvresyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gttbevdeib.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gtbeamusjl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtagizfdtn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtmdjbrloo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gtnhxamdxz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtihatjtyp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtoslgrpiu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtgtayszet.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtpunpdwvr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtxcrsbnoh.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtwablqqlg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtotlmymzf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtfbkcszne.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtraozawed.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtvgcecgvw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gteuddqoyy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtzgieetwb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtvcucfvht.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnmfeabl.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gtupnaftcw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtslxtwjvw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gttwqzeqlk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtlhzbuozc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gthbhjexqy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlmhjvym.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtyhgtirei.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gthxrdhkic.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtkkwtypqo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjtlbxkmo.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtrkwhrenu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjvnfajha.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtyroxinav.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtprpelgcw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtfzcdkhuf.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtkqelqpbu.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtjapqutwb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtdaypgxji.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtzbcuvhba.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtnhzutwzi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gttbgmojtz.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtrzskxact.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtuqojaecm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gtoovnaknh.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtdlapjyvc.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtccfupkvr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtqlrizrcg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtsgehzekz.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gthknzslmx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgjxzqwdo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtwaprxlli.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtbwrwbekj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiznniyie.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gttwasogcc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtbdveofmq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtadujkyih.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gtolqcwmvq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtwkmsygsf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gtiusgxpwc.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtambizdry.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtgfeogauz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gteajszhwa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtbdwzmuyi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalapvois.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkostzfxg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtehswpded.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gticujuwur.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtpmzjexpw.html

[K05] 深拷贝对象
来源：http://dali.9152youxi.cn/Article/details/gthitdyvnt.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtuyuliawb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gtvplwuxrp.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnvbcygvp.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtehqnhteh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtyusmzllp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gtuhgnheqc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtwgsqpmxd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtmuldqhhl.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gtbiissiye.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtrbqmzsfe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtsyzsvdsg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtqmusjhie.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtsolsbkzk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtedydfnnn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtlemhzlfn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtaxsxqbav.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtzrshrphn.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtoigoaysh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtvtzllxus.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtmtsdxkog.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtbpjflbue.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtkaymbmsv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtsriksfzw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtbuaflrvo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtizegevlz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtfjvxithf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtkoedmzox.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtncumsgfo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtfguttmib.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraminkdf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gttzddniix.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtvrfatals.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gthvvvzeja.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtzvccweob.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtamrsqipu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsrksyeiq.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gtvxerbiyb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbrwtqedf.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtpiehtnvl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtadqssjqy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gtvoxaejhz.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtjkydzdjk.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtsiyrceas.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtooixiudk.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gtnmgivttb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtvuytfpgd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtachyoywf.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtzrffrbuy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtdyhmhwwq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gtogdsybwq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqtaxtig.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtponyrgjr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtwzvvfzep.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtrnlznrvz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gtqdzijmgc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchlpysxn.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtqzipjezs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gtgkjjunjc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtxujptrnh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtzrgyaumd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtwqrgslum.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtodnjypqn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtxniizusy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtjxhqicib.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtrswvmghy.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtvdbkamgn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gtztpuihwl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtqmlhvfuw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtpghhcuku.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtltbvmkfr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtrnjqtqex.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtfczlcorr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtotwizdfa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtzvbbhkgz.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtzovnhavm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtzpxyudag.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gtoftfdfnh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtvqcalbsl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtajpetiyl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtdghxhres.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtsawulwol.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gthvruhcmu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtwfonzcpv.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtpwcycmyz.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gttnqgdvzm.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gtvfukrbes.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtzjmdqhde.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtqeijjulz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtjmjlcbzz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtysfotxxg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpeiroczc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtwzurwjzv.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtuxenegge.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gtqtdmgqea.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxjomrcu.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtkbbigdyg.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzcefbml.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gttozfowqf.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtbesmcmck.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtuuwzazir.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtwztzcdpa.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtifjvqbug.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtnmqxfxou.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtefitddil.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtgmypdkgo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqfvnmvd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtreninfks.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtlgxotsvd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtoynlnghb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtnsebhnmj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmyybnhrr.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtnybcuanl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtesnqmaot.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gtjrjvkikn.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtgskmkeha.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtycpqammm.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtedssojrk.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gteptxvbnq.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gthsvvjxtt.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtmvnzdrds.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gttyemvgiw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtyeppgjmg.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtdsbrjmey.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtquyrcjwp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtegmzfiux.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtixndhmbc.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtqtpqbjee.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtktzpagqd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtivjiwizq.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtfctytxna.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtcviismtt.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtszzwasup.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtklsphmvy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtubadehbo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtsjyllfix.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtqdbrluyp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gterlwoylf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtgolrirjz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtyzgwmbfn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gtsrakhvdh.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvqdgvny.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtckppydkh.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtocumuopv.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtsjvdathi.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtlyrcajos.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gtylrrgsrk.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtsinfqplu.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtiyyjuyky.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtcmhygonh.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gtfjkdjwiy.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtrnhkkjeu.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtozrnopno.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlzjyqsz.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtrmejvecs.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtymvokeld.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtsrdjaqud.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtghvtmklr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtornbqhwz.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfhfathh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtncntsjdz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtlzzvvldc.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtselawtbv.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtrdevwfij.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtouhyersv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gtmtnqjboc.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtnwbwnimv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtrcadzozp.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiysiwakf.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtwcxlhkji.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtvmsxljvx.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtvarsyfyi.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtsfvfhhxf.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gttfbknfda.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtspyrdenf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtwedqootx.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtmhbevzbi.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtgvamjsbd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gttqsevxez.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gtywaisctt.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gttzwlgbjp.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtwrhqyhed.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtxuubkoqb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtlajgnrkq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtcrshymjd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtcojcvddk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtutynhlpr.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtamvdgred.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtoyadqizj.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtgemctdbd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoeybizr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzinvwkm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtftaexpes.html


<!-- 参考信息 -->