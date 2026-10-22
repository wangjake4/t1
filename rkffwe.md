代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gt2dlpnehfb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2txqlenwx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gt2ucmkmixv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2dsjjlhtx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2obkhhyex.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvoektlq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjvqylcx.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2gciqfpen.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gt2ghmmjdws.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2qsmcqyxo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gt2idscnedm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxuxihon.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trkhkyso.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2xkzrbudk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gt2ckrbxpbt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2lgapvjar.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2vmprojqe.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gt2uffqfdme.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gt2rocblhok.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gt2dlsxvsik.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gt2ycerzzjw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gt2fmcpfdmn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gt2uzlbbydo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gt2mwnneqqx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vefyxdls.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gt2zsrtlzvt.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2llgjqbtz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gt2vodarfad.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gt2mupklkuz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2hdocyccg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2drwdunni.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gt2rpvhrmar.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gt2ekcvhguj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gt2urqxizzo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gt2cdvsntvk.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2ziiyynyx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gt2azxfsolx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gt2lycwyzwr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gt2oizkdctc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2zvkdadun.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2ccmrzvua.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2vdzxonud.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gt2ybuqadtu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkfghipu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ikyhgvjn.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gt2yueixgdi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2bbhrdeuf.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2uwpcckcc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzuqzris.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2cicxhqty.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gt2jjfvmylg.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2iypnesgl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkbdwdko.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2hwztcmad.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gt2ohffixle.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2yukrvsdm.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gt2oziusuwp.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gt2phxkcwto.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gt2yjdzmjir.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2lqempyjf.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2treghuvf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2pcelnxak.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gt2jnthnjaz.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2wqayazhg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gt2xubojabe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2ljsorprj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2tspkllyj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2rdvnuujh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2ptjssvvi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2fgfhxiop.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2buposdss.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gt2xnoxlbzc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2dmlkuyrv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2jpictenv.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gt2rwyjlqxt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gt2byvwgtmh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gt2qyqulthk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gt2tgbjgfgo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2rhngfugs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2omstbiec.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2wthsmoih.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2vzppwevp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2basyepys.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gt2slrdhphu.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmozhndb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsiswwb.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2wtbmbexe.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2hjxkeckk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2fwzfszrw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gt2kglawjvh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gt2dwyopnok.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gt2aihzoofi.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gt2uwkjvqmn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2vwjehrud.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gt2fcmbthuu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2vokbopmc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2ncqoqjkr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gt2sdvermsk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2xikybxxl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxjbcalw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2moyeelkt.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gt2deikfwyg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2ovibnkiu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gt2xvzdclso.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2lztyhsmp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2yrqgsxfq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytqnpnzf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdemyvxu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gt2tfvezmfd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2irmusykd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gt2uvkknmzc.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2umzohqaf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gt2xqffwskh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2iskaksty.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wecqbckd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gt2ziaijqkk.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cujtatfr.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gt2vaavbazs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2izcdmrbj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2qiiawqgu.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gt2znbbcbzn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dodridhf.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2qwyujeqm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gt2mmgwagnp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gt2dexxzelg.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2drirbgbj.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2tvahlxmh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gt2unsnuyda.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gt2vskeynvs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2wseshcoj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gt2gdbpyeuq.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gt2ehixvhgc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbtugedl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gt2jlfcjacp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2rcyggavp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2kovqkueo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2hlcexbtg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gt2cyufmymn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2svosvlhn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2hyibbxya.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gt2ndwajwae.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gt2wmjzvsmo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gt2cqekvlav.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2gdcgzbnd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpfrjhgp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gt2pdqoghtz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gt2shjmdtsj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gt2bszoumhm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2tlnqqqsp.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gt2zmprtybg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gt2iyfocrwr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gt2oxfrrkjj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2rybtgvta.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2fiybjphz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gt2aszptlvz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2ezoqmlsw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gt2zuorbpxi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gt2iaadxzkf.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2rknaouxq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gt2iabkfbll.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gt2izjlhqzf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2bqqiwblf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2guwdawlq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gt2qzjndiyo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jianghu66.top/Article/details/gt2ymzpxmhj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gt2lzkupzai.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2mjqgydcw.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2yayhmnnt.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2fymvkmfn.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gt2tfzdudqi.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2uznxjrjh.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlnstyod.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2fcynwejh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gt2zlerhrbl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gt2nkwdvvno.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gt2shtxupkh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2belpsfpn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2offaqfyr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gt2wnpojlsz.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkiwlsst.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfqycpak.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gt2xoklanab.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2zhkuipup.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gt2zgkpneqe.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poodbslk.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gt2wzwjsssj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avxrcsze.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gt2hlicniwm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2mtoklbyw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2mcaoutbx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gt2iyfslnxn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gt2imlrsnhx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gt2iivfkepd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2mdgmqmok.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2yltwcras.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gt2npgvqmbn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrmtmopx.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvrxjgoo.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gt2qwccinxa.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2brzktktb.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2zizjjvyu.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gt2annbvyll.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gt2cmdmdhkt.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gt2nkvrwovi.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gt2zotyntbe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2qvntnutu.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2xetwqpkl.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2abulucaw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2jekiaqes.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2zbjhtphj.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gt2qtnlnfdh.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajjaypqx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2yqslcwje.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gt2rafetsjw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2zlhnizhf.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gt2wndqmgbl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbyxiirj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gt2nvbsshsg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2ybifggpy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2bgnnypag.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qirtdvzu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gt2dayhwihe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gt2echehkte.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgdhntgy.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2djsupyqi.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gt2hkzwomsa.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gt2bldyjrny.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2oyfbgqvt.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2smukvhfd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gt2xbihkxyi.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gt2oyaqittb.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2lhywfgcb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gt2uzenpcaf.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gt2vnkdeuip.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2gtefexhw.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2pbmwoiwt.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2nwjlhkrs.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2yxnztprx.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2gvcjtpjs.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2mehkbnbg.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gt2wzpaljfy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gt2xccbgxfr.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gt2jpjmmzzd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gt2krnorucz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2qxqbawag.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gt2evdgzhfn.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxkjbhxj.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2qsmvohng.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2axgoroui.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gt2vqkskbar.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2idzcxntl.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gt2gljicotj.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxnlqeln.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgfzy.top/Article/details/gt2ujjhnalx.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2ikdtimgg.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2vvwhnxkv.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gt2qxrqtrso.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyocyldo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gt2wprrjdjh.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gt2kdzcllqt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ualhbgkf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gt2ndydqypn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gt2irklgkfn.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2szktolpp.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2ppgenhdc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gt2uujauekg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhzmofdr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2rwyrsrso.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gt2lvveacse.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ftkzdbhm.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gt2gpxsxxsp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ycutjooo.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gt2lcpcymjw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2dyyqghtz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gt2kiqriijc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyoeycwx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrbdfgjs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2jscfdhyp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2mtvdjqwn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gt2pqdmfagw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2fiatvonr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gt2rwucbgjw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2mrtmrpza.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2gjsgkhgz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2vkikepzy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2fagaphsn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gt2yjgzfjpm.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2ispijdjq.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gt2dmzqtzjx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2iokoykwo.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gt2oewtlyas.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gt2jjvsveyh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmpdywvn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2bdiptnek.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2kddavuiz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2suiekksn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gt2lnmadhyc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gt2yhhlygsp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gt2zoyoepso.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmlyiyni.html


<!-- 参考信息 -->