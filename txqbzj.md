代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtozbeikto.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gtpllpclux.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtmrupmynz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtjhpkoqum.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gtbnziwdbp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgftvifja.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtyhbiofco.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtftapsqtl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmumirzbp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gttjesatax.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtgfkpatyp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtuiqaflnv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtrmtnjsai.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtkuwsyghf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtmhojghsr.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtvfmqgfdb.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtlanidaqm.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtnsgxptfj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gtjvlhwijy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtlkoqttba.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gtvcdffltu.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtmvahgckj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtqlzdvahu.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtzqrizfpa.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtrlacyniq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtgbgcwtgc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gtyoykhvxq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtlpmsbmdt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtdwclwhzy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtfqnpjhvo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtdxxxsarf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtnzidyigr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtiknknyqt.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtkxmnmymf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gtngypkksc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtciahflvr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gttqtejtfy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gttkixxkyy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtygkqwapk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gtrtikkfpj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtbixdiifm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtrpxmugqg.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtriqfrpxj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gthrvocaxw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gtvysdqybo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtzzgenblh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtntjrlzvz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtwwxjzbsy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gtccbnwlbi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gtbxbrpjic.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gtlnnfrxiy.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtojreavgz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcdwlfws.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtxoeehmuu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtlwoovsjt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtcrzfmnkx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmbnrlhzl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gtasxplxib.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtvizqhfxn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gtfvuwsrns.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtypwpbyam.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtqtvpubce.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxnwjeinu.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gtwqmwqhie.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtctucbkrs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtljkcwbop.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcucrucvb.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtfqeqhrwe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtveukfjes.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gtqwajunjt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtzayyruru.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gtyuccvwij.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhctdzfi.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtysdauxoy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtxjpxswvd.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtndktatxy.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtseideegh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtijsvgmjb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtigqhiosu.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtmfsmqppr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gtdmpbvbec.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtlicvrhij.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtbscrawoo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtdgpucmtm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtwkeddrpo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtylshmqtr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gtnarfdrld.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtttgxbprm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtbgdsdmjt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gtugdpdrxn.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtqyremhue.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gteklvwtbk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgaytfwc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtihkqnbzc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxgqlnlg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtqmngafhm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtqrwbejnw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtnrzjoyfd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtsgkukhcs.html

[K05] 深拷贝对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqabymot.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxjawpnl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtlxudamhd.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gttypznkvr.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtmpgiuocv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtfgsegvnt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtibcxllus.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtjfenwrsq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gtfbtbzjcz.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtewlyblko.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtiazgxdwh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtokkscdfi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtzjlbcjnl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtreemoljr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtnezabbom.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbylfuci.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gthdefylyo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtxuuppgxe.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtnxjfelvr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtouoliqot.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtdlwfgbuq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtnqwpjxtp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gttvffthgp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwrdwqkt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwouhjlb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyibquoq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtxuywgpgs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtxaqwrbmm.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbqqznluu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtqesykfng.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtfotfaanb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtkrqpbtvy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtfptmromm.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtdxkzoprs.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtenguoagk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gthzovetsm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqmglojpz.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gthvnzfxmi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrqfqnhsm.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtsevwboup.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zycfv.cn/Article/details/gtgkcjzmgj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gtkjihaehc.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtnhjwlqod.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtilafwkcd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gtocfdwstk.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtatmgmrsm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclwvaadf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtwviagmvj.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtvvyfvmbz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gtixgjczbe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtiwxgxtvp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtrjkziziw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtpgqxghps.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtjpqjrzjb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtezesmhhs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gtfwesdziv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtkjrlbqzo.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcgzxedp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtcjylzxwo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoqaqoas.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtfbmukftq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtbsgadayu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gthznbjnjf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtvfzxndfz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gtfwelkkvi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtvcljcgjq.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gtbqgfhupe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtshytdy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtoeffwuus.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtgsqzeyjf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtwegwmzyq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtvohdespo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gtjcjwwhkz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gtftmehlvf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gtdhprqqjh.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtpwofqabi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gtnfdzpnjb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtkgkuotkl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtjawgvfqq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtwobcavga.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtnsmtjhjk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gthmwombje.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtqlxzfzho.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtminfbxmv.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtdtdrabzq.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtwufhvygb.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtvmdcrari.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqqdefyu.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtwrrmgfwr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtqmminhme.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gtouuvkbcn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtpbfdroop.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtbkjlcnmg.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtyxhkqtmo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtjxevnesu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtufviupsv.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtofdapsax.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtlmxjglnx.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtlztbjfem.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gttarplssk.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtztuyblfp.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtqdgpkull.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtqaaocacx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gtdzvcnqid.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gtnghrawti.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtswnhqhrz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtdrsqlpur.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtjiiljlkm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gtivcqzwgg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtcbrsjcqe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtiiyylltq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkvntkzma.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gttpdrkqbn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzxtlzwqn.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtoijfkgho.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtrstcqznw.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtsausuiul.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtkbiecoqr.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvedfqhu.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gttwroigai.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gtkpqrkujd.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gtfnpqarbi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtybhlwsat.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtadnbmmdk.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtydsaaglb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtomoripus.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtnphgpdxt.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtmagvgmrj.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtzrbjlyan.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtdczivhdd.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtsowytmrc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtwucezukf.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gtpptbrbwr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gtufsevppl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtyfhqxspm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtixrshlfy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtjyexoeab.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtiyalbfap.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtqajcpdla.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gttuglwyni.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzyurwpp.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtircqfohi.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzkgqwes.html

PHP:  getcwd();
来源：http://dali.hywenlv.cn/Article/details/gtrvnbipxa.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtcriyxihu.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gttkdlwtae.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gteqxvkfxf.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtiwseifmq.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtnqascrge.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtuydexkff.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gtnejweciq.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtzhxbqwpl.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtfpfwtwty.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtysczqjqg.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtppypoqtd.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtpghpkmml.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gthgqurluo.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gtvntbrnra.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gteegbucom.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtknyxdmxe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtswidsmzg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzhvriiv.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtxdwrlwvi.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtohvhgsbj.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gthgjwjsya.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtsooahokw.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtsjyjrjeq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtghltagcc.html

[M07] 判断是否为主入口
来源：http://dali.kuanghao11.cn/Article/details/gtwttumess.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtdvaufwus.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtreabtslj.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtlnccjvwj.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpdcshex.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtmjdpqhcj.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gtnxyvlolt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtirteuocn.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtwecglwia.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtnmtuqdzo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtmamkolkh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtneldiphe.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtvzdmsigs.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtfxooivxt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtgskvdzgn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gttledzktb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtkmfuzlkp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtqdbeatge.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtopxvuwnv.html

N. 数据结构与算法
来源：http://dali.nanxuanxn.top/Article/details/gtcjtqpuhb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbpfjnznv.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gtrhmsshze.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaikumkod.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtsjdpofdn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtkkdmntta.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtxngxbzaf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gthcevyycj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gtfhtagpwa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtdqoqehcd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlhmklfs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.bjfxy.top/Article/details/gtlysrtvxb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtcbflxrtw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtnmtxxysk.html


<!-- 参考信息 -->