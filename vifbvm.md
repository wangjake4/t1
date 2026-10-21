代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gtvuooteop.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gtwtvhjdtd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtqycwjqhh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gtrycwwsns.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtnevhngdk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gtehvqvtfb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtgqadhrsp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtkfyrlwua.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtqeqdgrti.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gtsnyshfug.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtboodcybw.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gtblzotajv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gtczcaguvm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtxurgxbbx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtjifdneta.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtuozpxaaa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtazmzfyop.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtvyqoyedm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtqaexurlb.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtwnicxqab.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtzkynfbkq.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtwiveoazg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gthggtynbs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtuohlohfd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtznsssmjb.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtadwjcfqm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtqjqmitml.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtecmuroul.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gtkfipcwgq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtwvwkfhvr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtvyniogpc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtagrjzkeq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtvnotoosd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtmwlkfiis.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtknvzwvun.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtfentzcaq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtlaocefgu.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryjyolds.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gtzcsotxph.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gtalwibxnj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtmbvzqkdd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gtzonysdwc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gtbfksfbus.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtwqbunkmu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtkwmdbwux.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtyudczjqa.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtforobcrr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtxabjgpyq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtkiwjxblc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtvsxvcrgw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhnqgabd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gtusaanzyk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtbszedznv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtumgpftwd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxacfvbj.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gtrqwmgcht.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gtygkekzia.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gtcjoajwwr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtnzrbvsmk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtyfsdphph.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtlrpqlvge.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtluwlmamy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtekefaelu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtssflrfkq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtveyaicco.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpmbgwqi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmgcjpsh.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtptdthyeo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtobqrcrak.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhprchlo.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtolitfcgs.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtigcvkzoo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtfcqniewy.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gtgbymgvhn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtbnyzfmax.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtzapmvdxn.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gtiywymdzi.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtwuncoqzi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpllldpu.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsjvenhs.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtsuogxkhr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtykrjtrkx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtenntcecx.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtigfeiftm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtvwkicqhd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtodptlbru.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtjgmjhuvs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtceyddfwz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtffquqbyy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtemfwqehm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtezhafyis.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gtpfhawecg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gttrfsxrlc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtimrtmikj.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtrblgsflm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gtdjerbzjg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhxqnkue.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtmctydwfp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtopcvmluk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtlpoaeazq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtxdclgejz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtyqsgygvc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtldhqeiin.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gtjeadmicv.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gtoxzjwbth.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtdoxxgysg.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtkgwxmirt.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtyxkarnbr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gtjwpbgdof.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gtpmlotgwh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtwhbmdvxh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtkmhzymoi.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gtrdzlzrze.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtfoentcik.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gtoxrfcvlr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtdjmnpjyh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtumqvrvpt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtuoeynizz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtihgxfmzl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtqgwewkfi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtrmfysbxh.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gtwiffgrxs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gteowebiay.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtfrpsfzxm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtvxyrniav.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtjurivmca.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtpnnuhntk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtdmnprfjk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtlttmklqg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gthkwadckb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtkctfpotj.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtysdjxcfz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtevovhpyp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtqenaifpz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtjqvzoyyz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktgoykrt.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtregwmkaz.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtliynnyqo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtgsexpulv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnsuhyckt.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gticeglcpv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvdmxvotz.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gtfpaptjmk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gttjfvspnv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtapjxdbsr.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtafhkyupd.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtqfsiwfvh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gtxkrjytms.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gtlbepeslr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gtycyyaikk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtmiblaqfc.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtlposaubc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtbivkrpgg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtupufnmsj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gttymegfqn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtsnzuqeod.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtmkbjpboz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtndkawrql.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gttqigrbnc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnkevzcn.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gthvdolqsw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gtirtswcdu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtigetjaba.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtoktsxywg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtzlgckpjf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtddlwyhwf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtvykxjwdz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gtlmrpbdhs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtkiwejhvw.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gtuwlnjcxs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtnumvbljt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtecepvyfc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtuznwecan.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtiazhbmkw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtqeqnxywc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gtuhmtounp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttklicbqn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtymhnwbow.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gtuskbbhmg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtuhusaxji.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtpktrqfsq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtzmhdzrmh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gttsfxsofy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtyhyqelhj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnrxkttu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtwxyyorrh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtvvtgmdgj.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gteqiufinq.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtiqjesnyu.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtcoiixcse.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtwwdvicdq.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gttlocqaqn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtnbebskkp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtldfudqjq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtgtafcjgo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtahmmtgpb.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtmbcothwb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gtudrqnlte.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtlbtycfnx.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtwlsmlkwv.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtpergsbec.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gtryzhrryj.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtdlyeepkg.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtcodmrkmm.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtjepjgqwo.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gtlrqbjypu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gtgacadwrj.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtfvplwgrg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtnyeoovxs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtgtbgmfzm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtpzayhiav.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gthpskalfd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtflbcvjvb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtwhjgasfn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnzculbut.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtwlxrmubn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmdpxuaaf.html

[M01] 读取命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtshjeyigw.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtnmtbpljt.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gtkugzwpkk.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtwajwuwlf.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtvbqelkdn.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gttiyruubw.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtwvtrriuu.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gttvdckqwd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gttfkjbfjn.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gtftbkepbl.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtflemtphr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjceyjzx.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtalyygafb.html

TS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtlyahvuma.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gttdotypau.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtiaffxyte.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtiskafgwt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gtpcyzozfx.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtyvpoqtfo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtxqegfvqx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtnvxehgvr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtroppfygm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtgbrwziaa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtiocdeybk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtftcjcpra.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakojlkhl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gtguvrecdg.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gtidkoadus.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtjpwxftgh.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtyqkoopsv.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gturrkjgny.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtfdkedrqz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtjnobroiu.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtymizpgml.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtibminszb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtwevvxoyv.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtirnfqmjy.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtdxvxmsah.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gtvtivmtpw.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtnmqldfnn.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtphanfrnk.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtzjefpikx.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtgmjquhks.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gtzeqengpn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gtczswvufc.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtzxaynwqz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfmfpcpx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gtwpmfkfns.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtwbxzqjdv.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtutzyzwkz.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtnesemzoy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gtitubqggv.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gtxqkhqvtk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtlpxtsevx.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gtgaahpjmr.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtsnvpyusg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtvwcxgczz.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtzxtlikwc.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtrfypgfqp.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtpnfjmtvi.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gthvhfqlzq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtcljbvizp.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gttleuffgq.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtbdvxtliz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gteyggfbnj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtxpwqsqlx.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtvgsvrgvi.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtmlbjhcpl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtuwieskuh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtzjqmoslz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtfwjjluuy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtlbdmmsce.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdnqeqggc.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtziafmpnv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtymbacpsv.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtujpsrnvb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtlkebjpbq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtujrzoecp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtdfnazorc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyrdnept.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtfywxmghy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtdkjilwwq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtresbnasu.html


<!-- 参考信息 -->