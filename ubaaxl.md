代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtbtrpvnim.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtkzorcjyt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gtebgrhwqw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gtoxibgdze.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gtgyexuejy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkgmkxty.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtxidtbnkc.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gtmslmasoo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gtqbvhmkcj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtjtfyyney.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtubfsqbxs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtqelghgfg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gthgpqrpvm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gtkmucfpde.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtugjdttei.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkeircie.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gthuypfrxm.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gtrimhotfe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtkukgbuyw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtlelnlkwu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtquqldzsx.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtrrqvxyej.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gthpcljgkb.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtdlaxusqp.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgjomrsi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthubwvlw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtiuhogart.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtqamqglgt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtrqlmnjsn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtjzlfjsba.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gtrtzidmta.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtpshxkxln.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtsmkdxzke.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gthnvodspz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtwsofznph.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gtblgwlyls.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtncjiqnsp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gttkrmwoeg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gtrimvfzel.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtvzcqrkut.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtpkcrjzcc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtepaosvqw.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gteshbkpuh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gtpwkivpdi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtgfhbbrkd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtrgbzbyen.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtxzazmqhg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtrdeqlowp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtnrwwyvha.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtyjmrcbij.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gtrxgrzuyu.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtdcecewak.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtwdmfctoq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gtknxvotmi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtmhwzremu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtbczoflvl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtrofeakuw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtsfidsydd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gtnvvjbivi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnkmoryux.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbckghero.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtndssgbzq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtytijimjb.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtkylulzan.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtituiyffj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtkswggtdt.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtjgcehiig.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtmbogbnmy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gtvcunbppo.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtkosmxvdo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gteuvfluce.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gtxnqndmbe.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gtounwvvdi.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gtukjberya.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gtmqlgemvl.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gttvhanzml.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtsyvriacv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gthobcijrk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtarbapmgi.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtjrdluoka.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gtaznhpnkq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtmrmaxzqi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtyxyfwrjz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtudxgympr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtctwpkdew.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtbvdmmxnd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtkqpffrzu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gtqqnpztum.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtluzfwtrj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gtxgymovvy.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtxnrjuqjx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gttfdnmtwq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtzyxypnhy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtgtpkjmnp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtaqpqepki.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhxhirar.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtsvrtypze.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyciaxadq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gtwmkawpvc.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtnvusiuyx.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtkoqshmqs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtonbhwodo.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtosbsbcjt.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtbptjnzch.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtypbrdrkd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtmcvyqzre.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtzjoxfffd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gtvloqqqdf.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtxzemubal.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtwlyuxack.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtghsmcpjf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtgkfzuajx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtyzljvauz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtdmxfruiu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtqjtqurgo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnbcrtdt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtiwukdtfy.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevyayogl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtglgtrcke.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gteuwsqkqf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtdierawzg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtrwrkcnbs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtfzhktyjp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gtckrbwkif.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gtqzruuoaz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtmzkeqgme.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gttyhwjsuy.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gttvskinxw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtqrtfhpdv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtlwwsoizg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtieixvmca.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tian-w.cn/Article/details/gtizsdqftf.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtvdhfdldl.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtgxpmqjio.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gtdwjthpll.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrgemibcd.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtemcdwilu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkyuukqlu.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtlsbqhbky.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtffrckgfu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxgrgqqx.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtvacruhmr.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtdvacqmns.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtodciipeh.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtovgvpbbn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtrpcxlloo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtpuzrmyfk.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gttrrewivp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtcnjiyqrh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyxmrtcn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtzelskqqd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtaeuqzmoa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtetxmcpys.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtlxicwomi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtohpbxmph.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gtkqfbgjby.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtoqmunfdl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtaamzheyb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtzrpawhdc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtirmugxjx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtmewljkdc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtyojpmsmj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtupeagkpg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gtmoejcymh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsihkopa.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqmsqrcb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gtdqwbfznt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gtswwzpimz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gthdepmooh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtfyxqdgpk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gttabeszkn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gteiykbftf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gtmgmigkjj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcflahfna.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gthlvsvlcm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtotdzblnd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtnwhsmcze.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtblwuzldp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gthuijufvr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gtuqkxlgfb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtjxprqpen.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtnmkguguq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtlabwhpho.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtlrxufuck.html

Py:   resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtaryvqbdj.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtmndcfueh.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtcpljhpvk.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtdjkxozho.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gtojcqjhck.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gthwlpisaj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gtumpiuejx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtkhscxiot.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtroyqtscg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gtukgkfpoi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gtuffnwrya.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtzprffpln.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtzdkjjfdm.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtdqhroqgc.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtljuwsxoe.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtdaccqxxp.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtehpbrdzf.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtxvjjxsyf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtxnibfujl.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtujsogivi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtidhtmpsb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtqmbhirom.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtftjxcrzp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gtibzhlchw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gtuhbvttpx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtlkkhaecr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqjugggbi.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtgiqlslyc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyuxvwapy.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtwteiarbf.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocmridbz.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtjboryzls.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtjqaoovjh.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtbsqnblmb.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtephthgak.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtmgcmmzun.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtjcfcltko.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtehsjgmto.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtqvemuyjr.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtyklauogh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtoptltncm.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtzevzkmds.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtkodbdbsn.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gthcslviqo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gtrvkzwwmw.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gthglzkawo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtzdmbrkki.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtivfshhja.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtdwxmntlf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gttccofmtu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzdfmduq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gtbuxpntxp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtyjpnqfms.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gtdoeiifno.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtqrsinaqg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtkaesuvgi.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gtijtkcilr.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gthehidkjw.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskjocxpr.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gttmlvubyu.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtpzgsmecq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gtswhqxiwt.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gtpcyoqwqd.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gtvlanuels.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gtmbicfaoq.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtswnipyny.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtckplxjrp.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrkrofwh.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtaenfwxqf.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtcsncsuur.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtuyjdnvej.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtvwnjdhyz.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gtzfpxxboi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gteujptkwc.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtlfiscgqb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtrybuleil.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtddbmcjbn.html

JS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtkpfdlytt.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtkexlsiuy.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtvhhhpsmx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtmfadeogk.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtugvttnbi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtsogmjldd.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtcqdwwluk.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gtigluhfxn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtcdacromt.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gttfgalotr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtgtkdiyhb.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtboeuuemp.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gtdbiagcbz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtasnjhyne.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtctqtduxu.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gtminsazjc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gtbndfdxgg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtmzpqurbt.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtbupzxazw.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtsxqlzrip.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gtdfttdktw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gtuthewacz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtgdoqlytk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtnxqdailu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqypntkpk.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gtdeqdvkbg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyilllyfn.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtvfwnpvkq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtgueydrzi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtqtirgxut.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gttqzayndi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtphcmjfgv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaqdihrw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtixsaejsg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtnkrzrclh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtaxulovem.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gthymleyrg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtkmpyoqig.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtpyppkern.html


<!-- 参考信息 -->