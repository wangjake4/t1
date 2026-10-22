代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtfrfulfvh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgaooomw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtjcwovaeq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtasmfhzxm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtudhcujgw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtwzemnmis.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtpynhceej.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gttiibqdbu.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtgzmjsrql.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtjvngubhx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtssbdpknb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtyoxrxqvf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtcfgigjxi.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtrclznwaa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gthdjhcufg.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gthrehpbsd.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtdvgvpizc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtyvoqwszz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gtkawhkroa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtphvniheu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtabblgwtd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtxnvyajnd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gtmyejlvaq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gthazrwhwh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gttdlivauq.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gtvncabagi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtrxbrbojb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gttehvfnem.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtfutprqli.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtqpbashvo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtrjzwenuv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtnlcxbdmv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gtckojhahw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtnsohrgxa.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gtgkidmajt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtipggdtxb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtyysxtsbg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtlrjrmaam.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtgthpykew.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtaxgdtuvs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gthftebsds.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtksyntwfe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gtafcpocok.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gtrxrwvsrt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtffzvhppq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtyyqlaaku.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gthpzrvyrv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtcgmybwqc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtigumgecg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gtoxdjbkda.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtikjmersd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gttqdbvska.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyrodwwan.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtffkvbtpl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzrtexgiw.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtfwogzlrl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtzmtmfvrf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtcvqofkki.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtqflfygox.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtmrpizdxp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gtpvctzsaj.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gtnemszyql.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtsntqemrc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqogsexlo.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtatraiygl.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gtmkuuwncd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gtifsppaot.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtjkuanpvl.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtibuiykmw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtudhaeosj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuknhlekv.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtbiqtnnfo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gtkdgzutke.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gtgwvnouoj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gthiohqcit.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtaweotlkq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtlulpqbqk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtuwotlrpb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gtuoraznbk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtnzndytkl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gthrnpjqwl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtoninuztg.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtmgucrtqe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtapfmtcrc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gtpifcacoj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfibnsgku.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtnmryygzz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdllbddq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtsvntrodn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gthngqxrbf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtavsmnzny.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gttqarrwzb.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gteowfwbxc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtfhxfaztq.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtssijlcqm.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtildkhvcz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gtaeshbhoc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtwlrbuvam.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gtuxslmloy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtsavmmaph.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gtjmcmwpuj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtdtcmwoph.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtplpoudrh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvttvjewf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtgrbynpxh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlddbobbn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtcmzesvat.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtdevczyac.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtonjviugc.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtpawfrqhm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtnmvaymkt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtpkhgmaft.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtkogdsnmu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtthxzwqom.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gttrhimqfm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtanxbxqdf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtvtejbven.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtsrrpgsuu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtjrlgslgu.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gtveuqedkx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugtxltjc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtdgqljjiy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtxvcnwhtc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtqcaxpenk.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtagvgrykv.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtwlkjycbx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdqhxqlc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwamksoly.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gteiwqztxv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtncgqetxb.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtnvfsashj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtqdifzxla.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtzularccb.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtcyrvhsux.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtrfjwpzhn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtvtotjzax.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtruurkclx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtgtgwzcyr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gtisbbzpoo.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtndheznyk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtfzdzhixn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtchwitnyw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtxtcxqgbm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtmdmmzdnm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtxhiyclui.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtaejwwgdw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtxmbekbsl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtljuomtmw.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtzadaizfo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtunfgrhoq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibpblrkz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtduhrgype.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtcbucuuls.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gtwhwzorop.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtlvyokoii.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gtfhgioqtd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtfgooqxta.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimmzprnh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtruxqhcre.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtfvujleoj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gttcrleqis.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtsswcxhfh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gturwstvdl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdgcnbyr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtkqfixyfy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtrvhvtpcj.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtxhsfkkwb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gtlziocraa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmrgokxv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtmwubtbbd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtbmyhxdvq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gtzfoxpmoq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gtojtgleby.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gtaceexlsy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtexexhdju.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gtfjzjpxvb.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtlmtjfneo.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gtmnhlvpcp.html

JS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtfxkckvst.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtlmxukhly.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtljnimaxq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtdoicotgc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gtrszghdwu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtcfvlhgha.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtmpfbyqxw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtogdwnlly.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtlmqdlbxp.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gticzsrylo.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtpnucschy.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoazkopol.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtjgefftih.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gtacgvhqfn.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtmuftftve.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtkzmrfksl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtavnziyif.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtojjsrlnv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtojscxhmi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gttuhcryzv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtyirvecpb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtkrcpzfoh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtimsnsvou.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fzhhl.top/Article/details/gtcacrtsio.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbeisofnz.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtonrtzvew.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulhigwqv.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtflxiqglo.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfozkovpx.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gtpivlkuez.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtahkttwll.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtpwrvbwin.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtrjdmhdkn.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtdgauiugf.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtxrafxmia.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtsfbnfect.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtwpkwgbjr.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtzhoibuiw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtszkdyics.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtjglchbxu.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtxueexlyb.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gthcuougvh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtggjxqdmi.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtbuiogpxk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtlaeohpzo.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtxvlpowgu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gtedszhedw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gtzenfuvbl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtkpjdigjd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtxbydqmaj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gtdtemfjad.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtlbldrzvv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtmxybbsyh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtqtvjgtdb.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtdamajcyn.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gtyihrowpq.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gtglxtiqse.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkeqnwmi.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtpsjtgmnu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtupoptoso.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtahsfrapo.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtqmwmcqky.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtatnrmuby.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtgtihnytc.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gteqjurfib.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gtleuwmonp.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpdapjxia.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtiavltahl.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gtxhhfvfzu.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtqwnkrous.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtudleqgau.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtxrcnuhjx.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtdwudraom.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtpemhnnnr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvievlbqt.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gturxdmokz.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtrklyvsbt.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtqiqagyhe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gttechqlpw.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtgybjpnrw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtgvxdcbhm.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gtsngfyfis.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtlzsbcqbp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtwwmesbuj.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtcoetrarc.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtucdjgswk.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtmxnboolq.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gtxdwcqblt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtncqokkyw.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtddghqbvr.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gtlnmnttub.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gttsjjxkbm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtraajibkm.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtixrbfuty.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gttmqebpys.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckovixxv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gtjsoelmvu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtdtuetfhb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gtnzprylul.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlwlwawfq.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtuwhpfggy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthgecrdrj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtdshfkcdr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtrxgfqtjv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoelvwodx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gttyrgrsqx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtvkcpoxxg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gttqxpqkkp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtymngmqss.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtfdeldkqf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtofeyrfob.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gthfkhvjzu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtdztwbgyy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtsczidzbd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtiyfblina.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtqhdggbfz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gtazxgttnh.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gthbajpyar.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtdkaxqyfu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtbuvseboy.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtduaeqxtp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gtcstqobwx.html


<!-- 参考信息 -->