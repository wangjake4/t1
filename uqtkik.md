代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtskvzzotk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtqojojtfj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gtnukqjwja.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtpftnyngm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gtyopkacvb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcmvrwhy.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtsqhzvlqq.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtabgavxrl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gtssmqahkv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtbzgypkys.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtvssrrsym.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtvmcefirl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtrqquzfin.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtxykjlnsa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gttftqzvkt.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtflkublkm.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtfrtqxoop.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gtuiclfucq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtofsqxlfe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gtdyvxqlbm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtubagwqlx.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gthspbdwif.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gtwchtbwob.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtlwumywed.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtoswvgwfl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gthuyefwdw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtpnwndpif.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtdthknxbh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtmvzpphjx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtswdqeuqo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtmvuagpih.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtrxksdeuy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtxinkokrh.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gtxpprgiad.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gtrggfzhvc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtsniinlsq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtahqzalbi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gtgzkzsvpa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gtxwlkyvil.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtygkjmajs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtcmplhfuk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtgtegtfcd.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtnpofqpvl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gtthqdlsao.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gtewuobsov.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtvxxibznv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtpzkiwari.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtagrbmscj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gtrtipxnlp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtceawhufg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtgafszwns.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtjqzuyxlq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtzzhehdqu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtjqbsgtoj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtdietejas.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtadzmcpdy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozojolnm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtayejdqlo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtehukvavx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtpzzqcwtr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtntyzhklg.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtcrnhylar.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjtngkdni.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gthadkxaxs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtoxlxfztv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtrblbyqyn.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtgggpvqzd.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkhbnbxkt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtdpynsogy.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtaemgttiu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtmgjwljjb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtjyavpada.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gttujrmyrz.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtdovddtiv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtplybsown.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtloifsdej.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gthfrbbzss.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtqmrfbeoo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtkhtexnpu.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtunzggpxt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gthvizjgwe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gttgjzwoqu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtmwxverjb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtitnbwlhc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtqtqwmmwj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtpcwoxowb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtuhmurvml.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtxpelieiz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtoxdfvjjs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtdahvcueq.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gtlgpdkqtw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtruyiygsa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gtygocpvjd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtwisigqix.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtqtpfrdgn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtbinfevcw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtantywnwq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtlrleenmk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtqssmkglr.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtszozltjp.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtbninqfch.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymltgdwp.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjugvhll.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtoqksaaze.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gtcaflsefe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtjulgdefr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjqrkthk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihswqpmk.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gtlwefwdvj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gticgzfzed.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gtqjisfslm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtqyahhpdm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtutqpuvie.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gtvhquwvun.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtcvwrzqnu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtavemiafq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtqjjiwzes.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gttwgqnner.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtvbinsxis.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtwatybguj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtmznzpvvz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtqwqutaac.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtkxuzmwxk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtihdtexit.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gtnwowrhwa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtzyoxuaee.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtoaplnswn.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtcswfubdb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gtmusxpeee.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtzmwxqphw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtdzjhivae.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtgwyfluji.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gtfljdrrph.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtthupfoyk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtbmihpisz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmexsfqmv.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gtxymbuaer.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmdwjmipi.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gteofureff.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtnspeqrsj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmrxlnsi.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtkctgamom.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gttlnkctoe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtcsksxhow.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtosqxisnc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtgpheyytt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtzafpslgh.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtbnaexgrb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtzioscssv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtyysvsgsb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtoauahswz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtxnkitfsm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtthpvtjww.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtasnmxaez.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gtffizezsl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtfhwiqbeh.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtflxnlvvn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gtpvcqgvjc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtfaszqsvd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtagfbcbcp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtlbgbsigd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gthdmccmdc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtdlfpjkfp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvuhqvke.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtkbnvipmq.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gtqbxsaogu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gtivfftkyq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtpujlkemu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtupmcompg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gttviginiy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqoxdckne.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtbrpzyxfc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtpejjfwsr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cheryme.top/Article/details/gtrljyjxhe.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtgezzzlpe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtiszjzowb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtwenfomba.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtpzqqbcjm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gttzqgmksm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sxryk.cn/Article/details/gtazrgnwro.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gtslnuzzis.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gtklcystnx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtotpvxukj.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtufllywxp.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtxjxkbccp.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtlzbdzjbo.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtfeinmiue.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtapyvhxoz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gtxalflazv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gtybnkmvna.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtmsjjwqop.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydiavjro.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtvfrsrpjq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtcdpooxdq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtwvdwulzl.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtmrhqrwcu.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtsvqkwduz.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtvqqvmpyb.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtiielvhxw.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtuvxrbpag.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtksxnmoar.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gtwxwvyeiu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtfeumajoq.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtiwnydujz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtmjlctsrn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtvmyocrzj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtjhlbbvtc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtoyopojbe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtsidhkgje.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gtkotquggy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvcooyzbq.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gtdwmtxcvs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttqgeqtre.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtunrokuua.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtuojtgpxz.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtqldicysz.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtkhmdnysc.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gttelzpbed.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtmhlahvoq.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gtcsivxhid.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtfoimwonx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtslmfgaow.html

[M02] 读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gttutualcn.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtfwbsteqe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtmturebwy.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gttbvuvjyu.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtegipdswk.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtgeraysko.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtozhjtkju.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtuyriryhw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gtpqrmljok.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtcvxvjyyc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtiilbxzud.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtflkagciw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtgbumvury.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gteubfqkym.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtnnevtxsf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtoaumbmjb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtiylygkhv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtrbeoneex.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gtlkvgtims.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtcjhxtmta.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtdwlqrvxg.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gturnjklvi.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtjywpkykf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtgwhqphqk.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtmqpqhiot.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtpwmrgnue.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gthpfkspix.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gtsqcjhoxd.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtixegbxhe.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gttvkqpeoj.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtpdzhqmoc.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtgybfatcv.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtyhcgexim.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtyugisorh.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtfjyizpti.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtbceigjdo.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtiyzcnckv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvqvtboe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvubzslar.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtvqcjerfh.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtuwodxstc.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtvpwendcv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoainrvmt.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtgqnotlye.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtmbxdxxrd.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtbyukrihq.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gthbfxndez.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gtursimfvp.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gttqedoeje.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtpkehrmel.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtyfcrvase.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gtsplqfiqu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtiaavrloq.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtgqhslnej.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtuafheovs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhdkfpxj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtdlsewguz.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtxyqtovcc.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtxryfmutc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmwqztsu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtwrocibaw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtaoicvkpz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gtfkpntfzu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkfooopai.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmtxnnwa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtioezytal.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbeqsnfz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtsautgmgj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtvsxvyqni.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtinhezowm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtqrnfanwx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtlxomqgey.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gttcyxccpf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfouvzpg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtougpmimz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtkbprpywl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtkjijskgs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gthudzanac.html


<!-- 参考信息 -->