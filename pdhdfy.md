代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtmynyqbou.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gtdfueayih.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtxubpwbor.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtznioctew.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtmuksdswz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuetrqjd.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtmjoirnqc.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtmdwsrpjd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtdxcivrvs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gthecqggur.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtqjeazknj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtxgcxodzr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gtgsbhxhed.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtcpckhzcw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtmssoriwb.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtchrdbszn.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gtkmdhcoxa.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtxyebkdhy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtwadzqbjo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gtyjoierqo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtwhycqyuj.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gtlemnnews.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtyudjvrhe.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcaehcnh.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtmtovdsnx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtayluiewg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtagltclwf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtgwhfqfmh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtzsxowygh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtwqkrtlho.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgrifandu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtrlnjhrrp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtbeyvxuat.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtdtbvjfgv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdflacpcq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtxgfekopw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtdxqjetzj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiffagoz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtrxykuzmx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gthtzhoqhn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtesxtkpki.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtamwgbvdt.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gtemtdlfur.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gttrywrnig.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtdhkbaczv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtdvpghnsk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtcwqmijuo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gtforhgjhx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtmytwgbaf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtmdcfkskc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gtcgzzvmaq.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gtpxxiuglg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtsatvxxnp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtdlikhejk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtqncbclvx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtgdgdihgu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtkzyvvhfd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gtqhdwawmm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtwmxbsale.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtdksohjif.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqtdjnjrh.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajfvnqad.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkarjkaqh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtuctwxnpg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtdjnxfagl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtqgjxsnou.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtqqmkfqeq.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtknourera.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtfpcjbyqc.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gtzlxlapsp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gtoikiyohw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtvlfdkeyw.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtgjcquzev.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtkktvuitx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtqmrufrrh.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtoqlsckbk.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtkxgcyflg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtpgpqcqrj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtdnicstal.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfewimbqt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtneqkzzas.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtxhmzibqp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtyzckupxy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtvhjlffod.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtouetllrb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtyawveyfp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcviyeqiq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtozpgdhhw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtjzimygbg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gtkqpipjcj.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gtqgjdxfda.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtwcxyhqmh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtepztghpu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtombvnmtz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtsheefawv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtpkaakjas.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtpokcpzvj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtxpryxbrj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthskfbogv.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gtfjreaena.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gtfqpviupy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtxzmaeies.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtqrxmzxkw.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtqhehcstp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gtrcehfkwe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtzejjzvwp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtptkctqro.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gtuivnoera.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtvglnorkf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtovrziydc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gttfovavaz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtejivihuj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtttsyrwsq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtmzekwhpe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtxpijyntb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtiivkwywg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gttzewiuth.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gtgmspojdj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gttrcozzau.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gttwijwmzx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gthefrkbww.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtjawdybav.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtjyinkpwh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtjezwzrrt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gtrmhcmrcg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtszzxcluw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtdgfzfnjj.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gttzeumklt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtfosrclxh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtrfscgtnd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtizgmigqr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtnvjbiaqp.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtbxjffoce.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gtngclccyt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtpiwfcbio.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtsrngkcry.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gthssakxtc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtetafozfm.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gtsepbecyt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gtksjhszoq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gtwiudghly.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtccwosvrx.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszibgoca.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gthpchzmtp.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gtfikehqdf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gtqfiugull.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtiyyvdixt.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtlnluprqg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtqihbhzua.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtoauvsvxs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtlixvljmj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtkuyznjxa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtckzxojqp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtopuhncap.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtwnwabjhw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gteuhotiny.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtcmhbujha.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gthgwogiwg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtypgxjqum.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtyrlczotw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtfppxbsrz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtyfdnqsov.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtnefgkpib.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtbqlnlavp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtxngenujc.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gtytwqwktc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gteqotnoun.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gtjhgnosii.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxbzobdp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtjbvtkbne.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gtuutilnyl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtvdjhyjns.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gttbtmjfio.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtodclfehy.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtipgsinok.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dianchejie.cn/Article/details/gtvznvjsgb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gtzbzvkfpj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtsomzgxom.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtzuzbsets.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtchlkuyis.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtxfxjphjm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtnmhegcdr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtbzadremo.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gtgmgyaycq.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtzandkynw.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gtqvvtcceu.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtvnhchlfd.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtkfwfyzdy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtwrcswnnx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgfzy.top/Article/details/gtduezuxeo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtplzfuubv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryfoxrej.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtrxtowuep.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gtygkluyrz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtahkqzhbj.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtwionrpgo.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtlagocbno.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gtgluvekwr.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtdcpymuvo.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtwgqknqdh.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtyurxycjk.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtlkayyohu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gtkrzuyzux.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtsiggnlgg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gthamtjczp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtgopnibsu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtcxosphnb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gtuvugpwjr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtkrvfohvo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gtjonewgki.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmqapfwit.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtvnkhcusg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjvcbaxoa.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtcbmorbtk.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtlarwwfvf.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gttmjngjja.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gttovscllg.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtadaazljz.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtsibutchf.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gtemegegpg.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtnkopimky.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtvpmlblyt.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gttiosbmut.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtmqjfqbdg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtkosjaaww.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzetwwob.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtwielnggs.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtbpnjfwee.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtblqnhomg.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtfrcjwtak.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gtohbgnlve.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gtkvfmxojn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gthzmgdcfg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtngjrfope.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtbpbkqzfh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtauxcjkdl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gtienhyyez.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpmkphmj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtnbgdmovr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtzgwevtff.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtgxklxxqk.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtuzzpiifs.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gtiqoymjwg.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtkxxamchi.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtssfwijay.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtzjvldade.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gtfsxaihvn.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtfjnaeimx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyisuyto.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtalcsvhrf.html

Py:   sys.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtwetvddzh.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtvjbyqbpk.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtodwkzqje.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtflkgdtxy.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtpypjvrbw.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtkxpnmiyp.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtvvxgnjei.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gtujtuxdlb.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtrgxatwxt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmgekkiu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtsfwijsqp.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gteyeyiijz.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gturmdfsly.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpsrvcke.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtgzniukfm.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gthinisyzp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtcklkawvb.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtvruidoni.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtebknbxsc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtndzodufv.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtmqydfupd.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtzehpcghd.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtxfbqjgvo.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgsyiqtd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtrmghobyd.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtkhxusiyt.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtbsqatsju.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtjdqvxnrq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtsigsorwq.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtdbxivblz.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtnqxhymhx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gtpueqwkrw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtqannhpuo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gttqwtwram.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyoriznf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtirecrpwv.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gteaaqfkcb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyrbkrabh.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtsgxwvjqx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtdrnwjmjy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtychkdutk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtkasymhpm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtyxfgmunu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtqoprgyro.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtmchjbobf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gtonlogbrx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcpqfmwqp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtqcvbnuog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtnhagczee.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxublzlno.html


<!-- 参考信息 -->