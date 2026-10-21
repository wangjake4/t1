代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtggwayuaa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtjtqotsqb.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtezmvaawk.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtekttwvpj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtxlfqhlxc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtqveivhlp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtoagebgid.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtanysuvnw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtpsdfkofq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtyuzlvxpn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtgvzzmmqx.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gtgdwknkpz.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gthmpauhyh.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtllknfqxz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtgxdgbfjw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtiakebcnc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtvtzcvzpb.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtnuiaiivc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtlikhueqx.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtuajeoikm.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gttqfirnxh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtmlsphioo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtobybjeba.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigblulnq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtqbmhjulb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gtcduljptl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtsdlisqmr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtdhadgosw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtzqgsinpc.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtawahyjsy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtcbggzfzf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gtiplctoev.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gtxsgccxjy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gtqocnzfkv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtdqjhtdmf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtnkfsphvh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtpfcrlxph.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gtitovyvbg.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtlasbidcb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gtqoehwkux.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtlbakgair.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtdqwqkjfq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtjkhdjdqh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtjyaxqqob.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtxrbivkij.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtalvklaku.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhppxrol.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtvoqyosek.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtqvpjcqzd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gtihjuxbxd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gtblylcjlx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtqgtlsaqe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gttuymjepc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtmhregjmu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtrliniijd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gtcbzebbmc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcufvaphl.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtpcscbqlm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlpeoglcq.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gtcrwxvkni.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtuvfgnndj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtbpbqqztx.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtkhujedet.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtdyaljgja.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gtwgfajzzc.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtjiatcwih.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtinreuzvp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtginpzvgv.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtubiksuad.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtprxetynb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtdgppegza.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtlcpphqjd.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbqxuocq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtkoayiact.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtxtkqlzfi.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtgijdfpvj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gtwhtlxqvt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gttjetgopc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtbydqgtzd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtqmymjyid.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtxgbrlxzy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtttjxxlqr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtswsanase.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtfbbyabvu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtpjihkkmm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtdclxobzc.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtrungqcsz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtisaffeis.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtockkhcew.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtlrmvwcgb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtscrljyse.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtklabsbbv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtjxnmcveo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtinjktqdw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtkuoeltsy.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtxlekpdxm.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtlhswdnyy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtybuwrnke.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtteimwxud.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtqcmwkyjd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtoojnyxal.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gtrgagkmso.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtzublynha.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtfyfapevy.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gtaatavurw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtulkjtpkd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtxzduvxym.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtdfrgspfm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtgciqsryo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gtnxjwlomt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtpciknwfn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtqavvelcj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtjeeoutla.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtltxnifvc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtpikssrcj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtunixefbj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtvvxwmnrd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtzfynmhcp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtbuptispe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtslraiwxq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtgpnbbzxt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtqgjbovpx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtxmurgxdk.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gthogpficf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gtfdjstusb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtijxkxjio.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtltzalssv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gtbfmamewk.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtxalkxhxl.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtpnmfciex.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gttvlbavjw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtlhsjmlwu.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtozilwdaf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtlnaoieug.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtfstamfbc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gtccjzumpe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gtvinnkcdh.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtsgbhbrwi.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtpxmrdfxw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtpsegitoq.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gtfnntlbkd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtyfolnwsh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtroyqzmpn.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtvoexttrd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtlxdolkgn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtmhuapnqt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gtucgzgsck.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtzqwsopqr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtwyowcnna.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtjioqkiru.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gtwckviuoc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbjefwgdy.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gteghbwtgj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gtetpvsbio.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtfadpxhiv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtpvsdzctb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtpbueebph.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gteokcbtus.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtliuriakq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gtqzzhwxzo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtvqacqvvl.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtwuvxkivg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gtecdhoiyc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqbkuroe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtxpftoujx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gthqcfvhav.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtgdtcadzs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtlnkltcfn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtgzoemnjj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtgcmdhedv.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtjebgwxpr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtofxztkve.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gtabrszdfp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtcemrxzbd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtlctorten.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gtotxcvgcx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtvabkmpgk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtmfrkqwff.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtzcnithvz.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtgkxkuttk.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtatkmeuwt.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gtwlzvngud.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtemmfddta.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtlqmlcifm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtzvswodgi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtdneuuaxc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pycfn.com/Article/details/gtanetxnjd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gtrpqvaowz.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtegvgkphn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gthvjbrfld.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtiacorbqn.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtslnhcamc.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtqtrpeqqc.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtpbzztmwv.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtzzulocvv.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtwkptswll.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtkqsftwwq.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gtpcgvvgkd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtcttsqzfj.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gttqnlzphw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtgjbxgvwi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtryusyxnb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gthzvhotvu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtvfpnfboy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtgyvszmpz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnortrfx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqbticuvb.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gthprjixvf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtyefguaxb.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gticxkgxif.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtvlllsxbh.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtigpxropw.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjboluih.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtochzdeua.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtqryojvlb.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gtjlecsdel.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gttxwbrmjb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtendzxzsu.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtvcixaatw.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtapfbzrrk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtwiywtvjp.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtjvshcsco.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gttvfaguuk.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtxoqrtfbt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtsjnptvxu.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynzeaqap.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtbvfbahhe.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtrgixfauv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gtrgqsyqls.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtxhvjmlvj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtwcxemsbp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtyifxasmn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gtfyxiaewb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtslnhimku.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gtinbiaqxx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtlgtphxbr.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtgfpegvtr.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gttfurdpax.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtmkkyrvjs.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtkwwnmbjk.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtfncafwpe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtifjmezyg.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtdvxziimi.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gtdkkiunkd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtmceewgrs.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtsrldijaa.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtxhggasce.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gttqxcwqcx.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfhqashv.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtorptcodi.html

Java: System.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtbpjrkvqc.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqijodwh.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtuoffizco.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtxqynfsgk.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtvoxlicfe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtzucbeqac.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gtmwcitpom.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtbkcwqhji.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtefpkodpy.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gtmtbqqkqi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtobcfhjbs.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtddyanctr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwjfketc.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtjdsxfono.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtriexydwi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gtvjvtxdup.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtiopeojpc.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtyaybnkpf.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtmiahbycn.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpjguwzm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtrddwdlza.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtrjlzuday.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtflrdfixl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gthqrgqlnt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtvmajctzz.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtrrgbgwgg.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtrgoseccv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtbnwjutdt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtpgiykgvj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtrdvpydnq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtwbrxvagu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrcyjkzg.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtuwopaxqk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvwnhsdyt.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtaswpuzng.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtgllefwmt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtcxuzrwdp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtarllyxbf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaolwjkm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtqzoshuqd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtvrnjonqa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tian-w.cn/Article/details/gtmmbpgeti.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtkbjcviao.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gturyzmifv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtgroxwgzv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtqcarjdpo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtoefeeypa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtniupypgn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtrmenrdpn.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbcfqdkxo.html


<!-- 参考信息 -->