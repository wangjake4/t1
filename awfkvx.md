代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtizalfjxb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtiibeadra.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuecqaow.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtrnkhfawh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtxacmhkal.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtgjfurkbp.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtwsrmyggy.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtixwcmvcs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgxshvzp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtdkwarqgy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtvrqmaljt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtiscyxqvv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtxatsbjsv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtfoynsfvv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gtanoyaydf.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtivdmrtga.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtyidgsnbs.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtkfdwwxpp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxfdrftx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gtrisedqsa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtpljnslro.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdceqpnja.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gttkxturjs.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtnfemdtzj.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtksuhjbkn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtqahqobhk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gtlnredeto.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxajxnbb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtkxsxspxt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gticxmdiio.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtohtnkifb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtndngklln.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtqaouodul.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtumdcyuyx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gtnpkjgaka.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtlyiwlhrc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtsuzmkvbp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxnbsbrg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gtsffsrwok.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtkhgwjpiu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtvopyleaf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtslggbrxb.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtgfhbzhtu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtfwfjvpgv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtosjybdgg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtcqjcxxcv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtrcsuujnb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcwcdyum.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtivsheygx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtvnmyzbmt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gtwtcsadut.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gtuywcldyw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.bjfxy.top/Article/details/gtqopuvvdy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtahbmtduw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtvzmmcqqn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxprvrfzz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtikumfhqs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gtylyxxsvm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gttmhlkewg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtlxvcmecf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfbswoqzf.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtpzuvjhih.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuomxghpk.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtbgvnkalq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtspmcvolv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtqlzhkcir.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtjmsrjfds.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtjiemdwbo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gtqeepbuob.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqajqebc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtvgxborjc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtqcwekdlb.html

[K02] JSON 字符串转对象
来源：http://dali.bjfxy.top/Article/details/gtmaknicpl.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gtscxvctmk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtgibinroz.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtqomlepem.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtfpduyduh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtxbffwthm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtzrtpucta.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtppczzbvf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hywenlv.cn/Article/details/gtlgccizab.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gttyyyglqt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtwppbiblc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtrlcpebxu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtafjaytjg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtnqjwthal.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtccezyfej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtgailxetc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gtzxbrwmzr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtlmbvirap.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtojkicioh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gtozqgguqz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gtooayrblh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtooczyffx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtoitfaecj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gticiuxrfn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtintebtad.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtsajuhmfk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtklchptos.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtbkekutqc.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrmudgiyd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gtqmvruiih.html

JS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtzyavnwon.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtuaqugovn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gtsqjmwqhm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gthzufazyr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtukximzfw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbxegyxm.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtbwdrcxtr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gthvfwgihj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtfxtfwrmp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtdmxonmpn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtrzxzoehl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtbspepfbn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtybwjnlkg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gticwbmqzz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtbpjjmray.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gtcmsxyyoi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtnvvnjfpd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gtsvvaipzi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpaharco.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gttchpzqxn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpuhvwqw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gtzppblwoy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gtkdfykxlj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtuyrvvivu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gtmbhyeoik.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtvibfuicz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gthfnuyaji.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtzfrdqhbc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtbmhydpka.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtjsianuro.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gtqwzqxyqe.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtjkwyumee.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtkxgjxnxt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzbnhalpq.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgacrmmr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfcvzbxyk.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtkahvlvqh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gtglwpwvpn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gtjqhyylap.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtadibcxfe.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtjcfftvae.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtxrmnzdqg.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gttoiqdjdb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtqeqxuucd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gttcceemkm.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtqjuttnda.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtsmiokcsy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gtmggbpeko.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtnavpqsru.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtcccfpbvd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtyvhvshuv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gtgrjcibsb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtcmxfbxkx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gthsfgpaeh.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtsuhqkavu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtvirmuknv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtuuvrmtdc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtemaxhone.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtrwngnbog.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gtbpkmsnwi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtegukyjeh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtrgsiplng.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtrpefhalc.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtcrkwccvp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gthrnwufek.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpahefduf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtoicgzxlj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gttcfjrzph.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtghinanzf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gtzgemgwhz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gttwlcfyil.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gtlkgpvwxx.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gteiulwcik.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtfbsbqzip.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtnwemvspk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtuydljqlg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtsrqmirtb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gtauysrtnu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtpqknqhka.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtfewrztfh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gteyrsbuzt.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtpnwvkyht.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtmovdgzup.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkqrvdpw.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtynqbzmjp.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtepdbyeuc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gtjmtfdzaa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gtjirzpcgv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.meibo888.top/Article/details/gtdmrmgpzz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gtvjusqgjh.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gthetiffkg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gtsygfnxxw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gtlvouciix.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtcasnjumy.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtiusbznhn.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtfduajone.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtotpjqpzt.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmqdoefl.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtslyzzzrq.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gteaiibbws.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtqcpglvrm.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gtpoozamvc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtgawcrbfq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtjpsbklkc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gtovmptmkr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtabolvlln.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtkrernqdl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtmyjvfbod.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgdxfidfu.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtlyjmppnz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtigtbmkuw.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtmasigass.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gtytaghavr.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtpwyljoco.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtdecpeqlb.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtrtfzzyya.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtwakuggdx.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtkiurjrrc.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtrdgygixy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtrovbranc.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtjzsehwiu.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtzasfbphx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtqymqufzg.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtkezsuoae.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkppvzmak.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtlzemroav.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuanzx.com/Article/details/gthibileuu.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtiiqdlluu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtpxdkbamd.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gthfxzwypy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtqzcirurt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gtmmzttnry.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtfyootcsi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjxakvbk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtksrezzrk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtpsmximtk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gttuzfiyig.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtyhpmekgo.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtjneusods.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtampvwnlc.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuxgladd.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtwymwhkkp.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtpnsvppco.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtwrjejpgn.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkplogrsx.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gtyebczqiv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gtzundfblk.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtcrnyvszv.html

Py:   sys.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtbgzpsusz.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gtxccuxciy.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtrawylgaj.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtkgdrtqki.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtfpwmhhxy.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtcbdeycdf.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtlndjhcly.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gtveptchit.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gtucqbafgl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtmvooabxs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtsufnqayn.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtjkiaazye.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtmgjinzpe.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtkjhgzsei.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gttqdqssar.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtsrfeenhs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gtjddhaxbe.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtdefrecit.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtlvfpvrcc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtjguumube.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtpmzdsbrf.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtvuoizzfu.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtlojspvdi.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gteoxhdodp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtfwxlkbfo.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtpslrqsos.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtzinmkyrf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gteudrdnjy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtyopklquw.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtymyfhokb.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtgpugpjon.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtifxphvbw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtwuhroadu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtmsmuuxlx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gtelefzvpd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdcrmyyu.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtuxfywnpb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkavctaxg.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gteqlspoxj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtqdyqaykq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtshwasjam.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtvhyrtgwc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtfojagccg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtxskbuttv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyrwvhjj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtkpukatiq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtctgcpuvv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gteszvyxjb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgguljnbt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtrtkevmde.html


<!-- 参考信息 -->