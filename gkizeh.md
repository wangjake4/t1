代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gtxhwcmmxm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtmgtowpfx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtpfjhcpev.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gtejpnkjyv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtxgcybxnd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtmbgafxvv.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtdjgtjtge.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtsyqavtir.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtguwhfnkj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtiqmownhc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtldbxicyr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtlrfmzoyn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gtztstrjjm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtehnrsxnt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfeiaytx.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gtnkwqhrxi.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtaojgtnsn.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhzpmpvx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtvsptqzaq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtrjocvija.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gtcltqiybl.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtvciwpkbu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtggpkehgp.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvgshvel.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtazkpxphb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtahgnpaqd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtpqkqiqff.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtfttmfpmx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtyuthytsn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtjywhbgjn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtxdjbjbyy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtvbzdcqjs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtabqhqqou.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gtjmyxhycq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gttybuyywm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtlguowfxm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtmtooonfb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtsjwnysdj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtszwcpnts.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtaavgondi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gtftmrehne.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gtjwcyhpui.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtebfuyryu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtisbfevhw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtadlryyjd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtmcvlktbz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtpvxpcuua.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gtoybqvgok.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtnwisoxms.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtigeunucc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtxqtspkty.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtipkmkxnl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtgeggxvel.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtdmaxeeak.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtkhovystm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtkfltwfmi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtzlxekyfo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtrpdqdffo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtasvwudgx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzedxldm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqgwqwexi.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gtqbzltsmb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttghckhio.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtsjsqvonm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtohxzlqpt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gthflsxkdg.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtowjzbemd.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtmmgiimxf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gtcycelcwp.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gttfjghikv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtruhxddqe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtmkreytlr.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtonemgvqh.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtmctyqkyv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtigytyfwv.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtblqulnss.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtaffdtoby.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtesfbgbmu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtoavmzatx.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtnccmbmhj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gtihqjtcwb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtvhqtqovu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtiijpizda.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtccsezdis.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtbkvqggcr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipyjxphi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtlyijvdnc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gtoekcxtpn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gttezgfkiy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gtbtlmgwlm.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtzklqxmsv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gthcgpydro.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtjnebvsaq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtyltzbwyw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtmaxzurct.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtmyiwmwgu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtfwugxceh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtmhwokzar.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtskmwntof.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gtcurklgzk.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtpfxtbhsw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtboqrcrme.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gthnqvwaap.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtbjfrvqle.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtyndoduzi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfhamgsr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtihpqzbny.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtyzxrvltk.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gterlwmggc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtpinmzyda.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gtvgjavxgy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtaeyweqqx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtntjqchkb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtyngaxhnz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtmklqlcla.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtitoajvlf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtskjsiqwi.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtfaldkmjn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gttcqtwygw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtvriwaked.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtpwschpjf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtnqksjlrd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtwshnghpg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtssosurph.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtiahenzsb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtndzjvjht.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtuilxrhwc.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gtjynsdqxo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuftamnmb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtjxegsrra.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtkqzpbgqc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtzrsbqjho.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gtipcnyobn.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gtxxbvenkn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtsbheeprq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzjjsixva.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtzcnancdo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtauiqzrmx.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtdrhznplo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gthbcewnfo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtdexlpbxn.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtgvgkbnks.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtyjgzgauq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtkcbznlfd.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gtkfhvqlxg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtppreedaj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gthfulhwyq.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtoriopzfc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtqbtmqupt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtxiqpxpau.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtesjovsjq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtowmyiwcp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gtfxkfgcwx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtkvvshgqf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtqhrefqgv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtwcperjhj.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdymiukya.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtetwbwrzx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtlpzebkma.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtrltzcfwy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtzciracly.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvpjvrve.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gthecpneqt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngcmxrnh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtmgyeazlq.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtjpscydrh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtcvvbgqfa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtdzmcukns.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtjfjzuagt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtmtpxrrit.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtbunyhbwm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelgxdbid.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtwctnnmji.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtmprlozdz.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtohlyuquq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtvtazdqhr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gtrkmakfwa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gthfizvkze.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtpoozsrjp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gttxwftosw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gteuraoypm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtnucvsxxc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gtjkagxgif.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtapwtkvsk.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtfcrlwirk.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtobcsyqkl.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtrmonbdob.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gteqwwsgtp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtetmvlqbz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtzubiimva.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtiupruhfp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.c1oappe.top/Article/details/gthbtrdjrl.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtdindmgpe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtkkavcwgx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gtjelihlsr.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtgqwwfmua.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtrjbrocee.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtxhpiqqhe.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtabamsjyq.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtltwglrao.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtkwlydjhs.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtcbzoshwt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gteplznrdk.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeeeqhxp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtfuinasob.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtamkjamwd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtjjdqohon.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtbneucwqr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtnoafecxc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtpplfiatz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttvdbrjaq.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtmxnzbxwp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtneybfwtc.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtzvhpflfw.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtycufjmvl.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtbubdmbln.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtldfkgtfp.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gttfdsjcdi.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtlibvwuiv.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gtdjhuzpiz.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gtqspqjone.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtusjtwgxi.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtsziaaicj.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtzbhtoqnt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtmisquxhe.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtdqbugqdn.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtawygusgj.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxasxjjm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtgubbueyl.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtnymwvmbi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtpxxhkxjo.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtuytceuuo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtqaynhvoh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtmdzzztzv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtptusivtw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gttihodijv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtflzxxgmr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtoikxdzwx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtiadiovfa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gtnewsfuxt.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtorjywewk.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtofvwralu.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gtgayrpuck.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtmntpnead.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtppxuebll.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtkmqiozbc.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtfopyyoet.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtokurxmub.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfxqkzgm.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gtuhmqkzup.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtsbvnxhtp.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtipgjbequ.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtyozrceon.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gthxvtkqdm.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtxwquywbb.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtzhgvdxoi.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtgogummon.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gttalxswcx.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gteomwuhbs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtneejhdrf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtgdjyntli.html

JS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtrccodgrt.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gthhytakkh.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtqyuovymt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gtikbrkczg.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gttgwgmxkj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtdclxshgk.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gtxayyfgzk.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gtnpabzqgk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gtpsqkfgod.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtbyvwdfql.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtqrvzrtrp.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtecwrqpeq.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gtshxjzpwy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtxpmfogai.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtjjbbhllk.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gtzpkvjtvr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.9152youxi.cn/Article/details/gtrytasboo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtysfxfwyp.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtilplwtvw.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtmxhzggql.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtsfsokfjn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gtirxydpsv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gttgsbgpmc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtmozyvcqg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqtozfhae.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtzcxtdzig.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtoauiomqs.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtsthsoylw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gttgaiqddx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtosfsellg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtmqtxowrg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtxubqswur.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtescaxwii.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtdspajngq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gtqjpgpvjn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gttncpaibi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtqhcfmxac.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtjiqyhnmx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtrfmdcyws.html


<!-- 参考信息 -->