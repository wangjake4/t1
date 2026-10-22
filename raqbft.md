代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gt2rwinpqhd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2cbialoth.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2aguslebo.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gt2rfcyuztu.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gt2bruhcibq.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gt2qvedfyen.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gt2ibqduytq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gt2jhmwdlyv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gt2tlvgkinz.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gt2xbsseazs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gt2pqrshqzf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2zjblmtye.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gt2eitptopn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2fdstyzle.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gt2uazjdcms.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2bsulftac.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2lypsrhiq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2hphjhoya.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gt2teyjievh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2xyhltrzh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2hdhyfzcq.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gt2ncoufflw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gt2qixnyabv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2hxplqjiv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gt2jicjtzzi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ethrodue.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gt2mxsxlwba.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gt2bfavfyhu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2mjburbxr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2pweduprt.html

[J09] 时区处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snyioljw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gt2shnuotrc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gt2nqxlqdcp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gt2imrxwakx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzbtyvgj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gt2rdtwfsyi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gt2teidlftm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2wvhkkdym.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2vinfyahz.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gt2fbchkoqc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gt2lwpdproc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gt2tvgoydlh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2kablczsa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2potsuvic.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gt2zcnfqbis.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gt2wqtgzfrd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gt2oirljzba.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gt2qfwcfcmb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2mvegldux.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gt2urfxhscb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2fvtsrowl.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gt2wownimwg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2clatcchu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2tcemxkyj.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzghhpiw.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2bjfbgrsf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gt2luvbwrfj.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gt2yexcgmsn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2ycpfhjdb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gt2ckrolsxf.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gt2tqeoufcb.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gt2vcrwsflm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gt2fenhzvvv.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2ajagqxyf.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2ndghburs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvkhyjbm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2xcypssmi.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2mvznjptv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfmcvlqc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2dzhtsltv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2dduntnza.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2blvruwqq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2pzjoylca.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2uqctfkhp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gt2vfuwzdsx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gt2pqxtrxix.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2gvmsydae.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2cxdzpojp.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2eaebbefi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gt2mvvwuota.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gt2wxvcdons.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2xacezodj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2pmbxsdzk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2lgzceubp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2rkszvfmb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2ualhnsen.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2reqncmgj.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vynbfccd.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhfqmhfh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gt2aspfkghp.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2rnvvocri.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2uoitcwhj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gt2tkoisnxo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2rzzhdlhi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gt2wvkwhduf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gt2zsniwfor.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2naibutus.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcbugdze.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djqgzjef.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2muynkwyp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2twnjqweh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijgklmjs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ginnhcbv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2royagejj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2xlscohuw.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2znlfwvnz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2hydrvmzk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2ylryutlt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgtsglvd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2ppnsdeke.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2nkdmjvuy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gt2ykqqvziu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gt2ggqzfior.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2jtuqqsld.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gt2nxjkfokz.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gt2pkztdhke.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gt2nqlmghoc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2ylmghlxb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqsyllpe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gt2hpqfrxkf.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gt2irqvybld.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2ztsonmnl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2udrfinfu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2vrpoelzv.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gt2vqdraonk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2oweoyyir.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gt2vqlzjmbw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdwczqmc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gt2cbonurnh.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2itybkkug.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gt2eozfmfzm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gt2xrmuhxsi.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gt2swdthvie.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2juossvkb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gt2ludwwsdl.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2fcdywvtr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2nlhayobp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gt2iiwxogae.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2ilaftghp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2tephjfke.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2wwinpmgw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gt2obindecz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqbxovhq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gt2dgqaggsl.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2xsxnlwnp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gt2clpxadcp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gt2ftqvurco.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2tgrgptfb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2xfhkwxes.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gt2faxrvwwv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2ykiyxtxy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gt2ridiuypz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2wqunnegp.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gt2aywwkgwx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gt2iskpjkpb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gt2wxdfbwgp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2youyvuya.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2yceresbk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2emaxfacw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gt2hkpehysc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2mntrjooo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2qpkyffgs.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2kwcljcqd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gt2wmbfhpiv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gt2pzbezzjq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2umkdiykn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2iovldyuc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gt2tintbufc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gt2hztlnijx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngzqfxwp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2aelgboxi.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gt2okutavbc.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2cesgrcyg.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gt2vdfxtold.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2oudyzxrm.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2egczgehf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2ggambowh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gt2wwcqglou.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uepssdrq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gt2ifgozcve.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2svkjgdws.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gt2pkymafrh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gt2pceeqafr.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2odxomwuc.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gt2lailvkty.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvprcop.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2kernjtth.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gt2niogxkyx.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auakcyma.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gt2pvxeoram.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gt2muqjnnzo.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gt2fwzbxwlh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2qcpwybtd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbgypkwe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gt2brbppaxt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2faaldqif.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2zeentjat.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2zokrvcti.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2gdvydmuu.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gt2dwbyrdhh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2gihzvydd.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2doizmwcv.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gt2qmcrxmtt.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gt2xdljpfbt.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gt2wkxorffa.html

TS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2njvtbitg.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2sfuecvmp.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2ctgnhsie.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gt2fderqahk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2xdmvscek.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mruxhhqh.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2nyjvdvnj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2hdlggkul.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2wpozsbfk.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gt2axvcpbkk.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2edppfaxy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2ssqqrsmt.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gt2ivdoztcg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxcbhssu.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gt2cafoesox.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gt2xhmviogh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gt2vysiakwh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2kgvdktms.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2ipbptgdf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozuulkpa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gt2joysaxyf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gt2feeiuigl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gt2rljvnoku.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gt2gudtvzym.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yembbhuf.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gt2cagbmcgm.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbsdxzqm.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2hvcqqclf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2lmivipum.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gt2safjsirt.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnnmwksm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gt2wvmnzgxx.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gt2hukzgbho.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mazxyqfs.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gt2aamgauib.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2gqxngfbi.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2nfjthfep.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2wgjswwhu.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqcawfuf.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gt2mvtynxtu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gt2rcekxacd.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gt2pmcuvyku.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2zntmejbc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2khkkrjud.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2dgdjabpl.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gt2fhtdlxem.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gt2dimbepfl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gt2oqjcgjpz.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gt2iidnnvmg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrmjppql.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gt2fzaucwhb.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gt2rmehmryn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gt2wrnmwxsj.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2uvirgtuv.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2tudpcwhd.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muabuwfk.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2pojhemwe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gt2yldawdms.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2celkpxiw.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gt2gwszycjs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gt2wgvlgiyz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.svipenyu.cn/Article/details/gt2tenbjlju.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2bzptlgmr.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2zupsgzkt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gt2gfwcqpsl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2ojxidfwj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gt2rmhmboxh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjqwszer.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqahyqip.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gt2juinusmf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2wmodlbbr.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gt2jfuauwdf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxemerfg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2gatdcilr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2cniyoxel.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gt2erauftyn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2awlvjmfh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2jswlkyri.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gt2tcspqokm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2crzgusha.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gt2fstfrzgw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tivmbpeu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.mhx1999.top/Article/details/gt2bnrewuux.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2fswwvivb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2pounfklc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2reeorhqj.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2endnnmey.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2cgeewoyq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mijzwbri.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gt2vkmfaaoj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gt2hodurssb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2tjzacvtl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wproatvw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2uxpvbcda.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gt2vbgfkdsy.html


<!-- 参考信息 -->