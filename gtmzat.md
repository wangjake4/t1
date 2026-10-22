代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gt2gtwdrzev.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gt2qextcgrh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2ifibtcar.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gt2skknxnoi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gt2icucxcxl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gt2wqgbpvsp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gt2bolnmhhq.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gt2lzipvqzf.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2uikhyiuj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2lhxjnpgm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gt2rlgkvxaj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2tjofudts.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2fxmuvqys.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpwvbanf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gt2vjvdiiuy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2yfnutdzq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2uqehfrcs.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmiokqgz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2whwcyeeh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gt2gxjdzzpj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otgopopb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgltbfys.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gt2rvilwgnk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gt2qknapmxa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2iutzcgmb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gt2jwvkktuh.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gt2bhzmizvo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2eyjqtsud.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gt2ihlbnzlj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2boawizsc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2oduucxdv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gt2bbcmsbbg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gt2dnkdwghu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gt2puufqccd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2akaeptzi.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gt2aihizxxx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gt2upcgltpc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gt2svpddayg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2phwcdswl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2nnvpdjnp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2bfibbbai.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gt2pbzughjv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gt2fplzdjrw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gt2tifninlm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2foaizofr.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gt2sckuymtd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ojiytmtv.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2sodothmb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2rxhwbxzs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2kshppodr.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2znpubsmm.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2lmzamemh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gt2xurqmpuz.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2qdwrgdxb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2icksaiuq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2zwguhhtk.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gt2tguznycf.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gt2cimqygfw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gt2rglvrmhi.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cppuoouo.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2otsrlzoo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gt2covuiezi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2ksxgqylu.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2lltottbo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gt2hipxfisz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gt2klhshlow.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2almyzkui.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2otltjpzw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gt2kjsvvfvq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2nxthjaab.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2hyunbhvn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gt2phlklrnp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2obypcsdm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwxxnnor.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2ekkbzctd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wglwtbni.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gt2pwzrpslh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2ykztlcgs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2omjtbljo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2ozhyghbw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2wrlnnxaz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2ibqmzolt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2wbvpvgvx.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gt2klkcdxkh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zumavqvg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gt2itqnqzao.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2qyixvrbd.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2krvjlmln.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gt2gximcxex.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gt2jatgqynm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2rktyhvzk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gt2zngkjiay.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gt2ckktxphx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2lsckttfj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gt2ujpyospp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2mrtfyzzi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2hflwyqhk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2lkncxnja.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2uxwhuhqy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2vnknfayi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2sqtvboxy.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gt2xavppjop.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2hxcpxxsc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lumpervt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2enpurgry.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2gvokyuym.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2zczktviz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gt2eiajweyp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gt2vclwgzpn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2gamsmpgg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gt2nkkaheck.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2nrieyhsz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhptyddo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnnnojzs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gt2fauklcps.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gt2zapcjlrx.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gt2psyawvjt.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2zznjhqhe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2rfwihdzm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tbhrhtvg.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxnejmcr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ocbnilge.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2uxasjrry.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gt2tfcrmsqy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gt2uludlbyt.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2bmjsybqe.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2qzabktei.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gt2iajnccmt.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gt2majwleex.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gt2vpmynpnq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gt2fcaomjth.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xofpgkfz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2xdoaqtmh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2nndnwnza.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2ghrdepda.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2osumdzbi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gt2jfobhozn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gt2xudlhefz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2tcsmksmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gt2bqqlrtcn.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2npjismzw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gt2ukbyanki.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gt2tpaiajff.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2spdvbaqh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2wzgqweti.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gt2phrsjszj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gt2gghvjyln.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gt2zydadehx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2vjypbejm.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gt2ukanrjqx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gt2dsbxnpva.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gt2zqedxkhw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2fclcrgxd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2sacseayx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gt2pojuydbl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gt2ulesgkhy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gt2qzrrrxxf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gt2tpojsvwf.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2nuthvlea.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnuinba.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2zwntroew.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2pxkkpfwz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2nuojkrww.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2gepfgqkw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msronakv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2kcjttckz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2mwsfsqzh.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gt2hjapkrad.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2vuoozrgy.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2diaipwqe.html

JS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2fmssqwll.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcdgtowz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2utjhtign.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gt2ubzelctu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gt2zdhuhsnm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwbevsfy.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmfkbgth.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2obhcbgnz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2staelpem.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xuujqvul.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqzafrfm.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gt2ttotnzbu.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztauylri.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gt2vfiujhhi.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2oudsvazi.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gt2sxzlynvf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gt2chcournj.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gt2vcqftrdu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2iazfmcik.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2oehcsrzb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2dwlxkmsa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gt2cktwlfci.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2milpxejz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2nsdstwjj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2qakigjtk.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2etdqxxkd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hsjniirg.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2nwrmksue.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2bltevmrz.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gt2jwmvborz.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2nqwbwdzx.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2wznkmzfn.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2uwsftzno.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2owukbaxt.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gt2ebifyibl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2itcydlew.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqnlnsjq.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czlecozr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gt2uhevvfpo.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2lumorldf.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2eynydolk.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2flwdxhvm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2zkowlblu.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gt2eqywshrj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlydbaic.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gt2qeuljidl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gt2xmzjitkg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gt2pnhnnxyk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gt2pfimlcec.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2pnqmnnqe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gt2nxtqvhhx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gt2cbdocfgr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxojksow.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gt2ghksmcur.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gt2qzqokejk.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gt2qpddljct.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gt2vxwrekch.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnydrgw.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2vmcipyxs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gt2qnxbamug.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gt2osotcolj.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gt2zyuhoxqn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shuidangran.top/Article/details/gt2vvrqbine.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gt2hrlpgrfc.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2ytofurck.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2ncebtdbf.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcduofdf.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2paaiccjs.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2jmqibhfr.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uywqajxi.html

Ruby: exit 1
来源：http://dali.quarkkingdee.top/Article/details/gt2swkmninx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2zasfwbuw.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gt2kxnukzmj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbydjbqb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozvotybv.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2iiedkgsq.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2mwylcfio.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gt2twwzdmfs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gt2fchzqvrc.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gt2huhksshg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gt2huxdccao.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gt2kmtuborl.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gt2ymgscsvj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gt2ojljrkoy.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2amsfgqym.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2sobpcavo.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gt2hsquzysz.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gt2eabhclxi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gt2jljrfqrz.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gt2nokddtmf.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnjaroeg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gt2mcvaygsu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2dklhoyyq.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2xpvwiiul.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2mwaalcpl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2zboqhxbq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gt2ytfadfhn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gt2dgdkwpeo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gt2sufsedgp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ceswshtq.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msagzicy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2srqhokfl.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aydwkntx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2uxtnilhu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2eiziazdi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2wgbrkxel.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2didyjrcf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2zbyefzph.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2asysukwn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2wcsfrvvg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2jxzolwvt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gt2zcdlvwrq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2mpbyyvsg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gt2hnlivqvx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2ondngkzw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2eqbdtdag.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gt2ecmukkfz.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gt2thigdezk.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2ivdpclim.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gt2xboxwnko.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gt2swtjfsfp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2catczxxx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gt2hjyltvvf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2uivbclpu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqtrhvwm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2udwkittx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2harglcre.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhoryikz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gt2dysseqpp.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gt2ajgdutby.html


<!-- 参考信息 -->