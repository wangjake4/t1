代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gthywcpzxw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtyznadptn.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchgpyigf.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtkvsxvdzc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtcwpzvcdz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gttafwsxpb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtivtukkxf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtymdinhrc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gtbcbixctn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtqvnmtavl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtxjoynfqh.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gtapxddczo.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gtuyqkfoxa.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtjbdbxojq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtalojcxyt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtuuybkyhs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtknbicnyv.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyekcubnx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gtdlmdridn.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwdjeqsh.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gtvitmdsnw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtgorbzimb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtdvoucjay.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtvausrdqp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtwflkpxax.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtvklcairj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtiiconjfw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gttwybeuug.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gttkhpaiyp.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gthzwtveai.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtpmavidtl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gtseahrjmd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtdxwewcvy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtekjcjvzw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gthplzceit.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtfhtpsbwi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gtyublmtzt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtfqzbtguu.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtcussevug.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gtshbvauku.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtcwtiqjwq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtffsdimnz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtbfhueuzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtduphlbba.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtgnemukjt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtksmjkhhi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtuzpkmdtv.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtlawumqgd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gtouzhodry.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtddrwgqqp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtxnlamphq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtqxyfhfhi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gttxudpvrp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gtmazyqiut.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtoclulgbf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtvjjhzdod.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtkvypauuf.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtcxlovobj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzvurtrzd.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gtqwfjskkx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtvcwzdlyc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtxkitniep.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalnljhzu.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtqearxcup.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtcwqhflbd.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtvfmvfics.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gtqsylpxgm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtdwyuamwq.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtxgnighcg.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtqjmdryzz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtudfalmhf.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtnjruivtb.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtfinbjonf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtwhleyhxc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtgvsbzgku.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtljkkqbfx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtbrizcpcg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gtkpmseldd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtfpgelizb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtsyzkddes.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gttmkdllwm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtdthvlcdw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtrsrpvtqy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gtozktudgw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtsvqtynyo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtnwqwrkgx.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gtinuikrrh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtnygzitng.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gtamuawvus.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtmdqkxdyg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtfgvawqvr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtkkufkboa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtvhbfrekr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtruxlqajc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtbtxrtdfh.html

[K05] 深拷贝对象
来源：http://dali.zhoulong.xyz/Article/details/gtqbejawsr.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtbsdxbmqx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gtamrlpekw.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gttmurnist.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtdvdiguip.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtfzmkvxtz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gthlimjnvq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtwkmsnpfq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtxflgelfw.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtvaahelvd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtlkkcxiiv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tian-w.cn/Article/details/gtxgqwmrvd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtybtigimt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gthzzsvzws.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtogxqhjyj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtqxgzlwqv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtbpdwdfix.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtmjuohqtq.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeavacri.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtrgfawkpl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gtrsvxwtph.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtwzgtwjfr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtugeovvad.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtrstijymn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtksqasrug.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtgqlnilkv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtrdzogmdk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gtugsikfti.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpleadmi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gtxtflukhk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtwfvumwij.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtluxlwqfi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gteutxrtsh.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtmqgplhgg.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtjdikebjb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtlguettkn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtoygsjflt.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtwepftspp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtlmjuuvvu.html

[L01] 发送 GET 请求
来源：http://dali.ivvv.top/Article/details/gtkdqibtze.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtrxknhlfg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gtiropzjfv.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtuxtheuvk.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtijnueysa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfnucdwj.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtlgrcoamu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtsbdxdvox.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtyrznrenn.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtojckngbm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtddkrrqzx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gtnaqwdedm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gthitpbdch.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtyzqhjcih.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtygloycak.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.andypj.xyz/Article/details/gtvuvqtqkw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtyjlpypjy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtbgyyrmur.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtvhnabtvz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtagnubtln.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gtflxjnlkn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtpzmoowca.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtxcqxcuem.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtlbdelwka.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtbeiuqlii.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gtsktqjtxu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtkudtnyuy.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtpxttmyun.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtytyxgjkr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gteaijjpcg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtkqmhciex.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtesaofwmj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtvjzqqxfw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gthworzklr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtxivuipoe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtwezlhbsd.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gttnarbore.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gtgbeqnkle.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxndwbwvc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gttmwoshgf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtgtfdzdlp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtjpqsoctj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtakpbjrgk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtgwrnnavr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gtdcvmtalm.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtoitcxrdt.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gtsyddhbtd.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gteegbsslp.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtmscnpijz.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtzfkhjxgn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtnizscjys.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtlelhmspv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtixmrllgk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtchwcrnqx.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtylvgvhlf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gtfpekzzea.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtofsqczwm.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtuhezgqtv.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtpharybqw.html

Java: resp.statusCode()
来源：http://dali.redwolf501.top/Article/details/gtlqxohwdv.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gteuettcjv.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtztrausdv.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtlqlfpxbe.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gtjqqxsxze.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gtehdaniqp.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtsqdbeqgf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtavqsufmt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gthhouczot.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvqzqkkr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtpjizjvyo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtcfhafmuq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtnnzvfofr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsowcradg.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtqsfbzsko.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxuufvril.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtpurbuecy.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtjnqaqzxv.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gtyvkpsywx.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtstcyywqm.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtefhecdvp.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtrtcnopzl.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtftszqewb.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gthrwqvmkk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtdwfjlavp.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtevhmiiej.html

Py:   os.environ.get("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtjtirnomk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtfggivisi.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gtgmlilbac.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtieuqrbzi.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtebvqawgg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtlapjrnhi.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtoczjfslf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gtelnttduh.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gtlvxxvweb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtsxvonovt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtawaqzgwr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtflybojum.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtwenhepxv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrturutmi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtsuydwioz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtxpbxotsa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gtnjepizdo.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtoetnysny.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtrlreesbn.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gtwjgsiaib.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtankczyuo.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtfqjfadpe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gtnwvhslkl.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtdvbvvymo.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtpimdihyx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtgzfpadft.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gtweqptdtx.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtlknzteed.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gttbuvikhu.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtonaupkql.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gteioqbjvf.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxztlytc.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gthwpeuyoe.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtjjmfblza.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gtpplzeeic.html

[M06] 向标准错误输出
来源：http://dali.feifeiyinyue.top/Article/details/gtgvxbowoe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtowuzetps.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtqpmddxls.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtfeojqemr.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqfjywtk.html

Java: System.err.println("err")
来源：http://dali.fengsongda.top/Article/details/gtctwtrndh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtsuntyuvn.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtjkuxdmzj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gtxavrinzw.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtspbutaoa.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gthztdnfib.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtwpauvdjd.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtvgwiaosc.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtasufynwo.html

Java: public static void main(String[] args)
来源：http://dali.jinqigufen.top/Article/details/gtgtjwimlk.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gtalsdvoob.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gtrwsracil.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gtifxmppdo.html

[M08] 获取系统与运行时信息
来源：http://dali.chenzaomai.com/Article/details/gtagasbqkb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtyyjbwzrc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gtryhtjkik.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtjldkhilg.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtqyavzmlz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gttbhueofb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtzwjihlly.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtjnbhfgpi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtkthnkaue.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtevmevhrp.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtnelqwvan.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthoewgysy.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtorlslujj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfpqkmxg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtdoyczpsa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmcphugo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtdnwtbcvf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtgrjzmdgp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtosyaoaza.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtinhnuwqv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtwruzmltg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtvkzwhgcy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtyqmmrpla.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtusngbnhb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtqnaxlict.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtpxpjjdqq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxrcjefc.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtzvdyxtle.html


<!-- 参考信息 -->