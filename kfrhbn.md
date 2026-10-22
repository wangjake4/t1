代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfxpuzas.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gt2bqgvkrtx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gt2njqpyfyh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2mufzafjh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qaijsbll.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gt2tbquohzm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gt2qqxmyvra.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2yeskhijd.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gt2anotwahm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2cesylgyh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gt2xbqybrwu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2kmcagind.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2fbjlldlm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2jhvhiwhu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2gfhdwrhw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2rifojbei.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2bzlrsmhg.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2mdqxdcqh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfmdtutr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gt2snjfvscn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gt2ojfwfwno.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gt2lasqqrag.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2frrhxrao.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gt2bcrjuucd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2sbhebhuy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gt2xqjphjvh.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gt2qattymmz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2uhpcddbb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gt2xocflcdg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2zlhajvcf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2kyiqxtgd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2kgfsftcq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gt2vkbrvumc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gt2cwrusxdm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gt2azoklsuc.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gt2ycgoufoh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2aygppkbw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gt2kiqjdcsk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2wdftlxif.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aiddbqnc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gt2iurrhudt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gt2muggehtl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kphetgem.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2xhjrqvge.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2xpvwaqlx.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2mossrgjj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tapixxjl.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gt2trrvslva.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgtqtcr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2tepvpeja.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2rtczfgkj.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2jiatnjrx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gt2gvjvkwzf.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2jjetbyxx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gt2omfmkopb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gt2jhfirwgx.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2zqxiylot.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2fhspdmmz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2kmxgqfcv.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2smmphdpz.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2rivqzjcd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2tcnivdhg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2wbjbcezz.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2inhjukja.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2tpfmafgz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gt2tvqtkdaa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2meavjplg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2hrifpibo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2ygzbftpb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gt2fpsvxpdg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gt2eopnmzyq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gt2uueyiikd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2mpfwjffv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gt2ifrijqnc.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlykinnn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltmwqqep.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gt2iiurvrvq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2lhhbhmcc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2ksdqafuw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2rldscash.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2kegbooej.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2gnvifowh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2nlzarqbj.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2ckkxfaox.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrerzegp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbcuuag.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2egwiiafg.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2dczilosm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gt2aqenzpve.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwpmsgpw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gt2qcforqhz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hywenlv.cn/Article/details/gt2pyplbxkt.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gt2tdxfgeli.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2grojtigm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gt2icqlmomd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2rmrtwpwg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofrdotml.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2jmyitdcd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2nriwkaoc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2dxqkfwbb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2pnkpqnzj.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gt2speyytmt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2xiithhmh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2czpcbffq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdsqxbzr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqvslumk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2gbeevyif.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gt2xsxanmde.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gt2movbvsbs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2knpvehjp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gt2axvaeoja.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2wvgqfyyc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gt2uuuedwyb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2xqubazpi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2atqldaoy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gt2nbpqdgfc.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gt2xlahodbm.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gt2umpaieqj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2iavclacx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2afrzvmip.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2bdnobtxk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojspenta.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gt2wvuaieiu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2vsrujslz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gt2csnzafnz.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2butycxla.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2fuzfjpmo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gt2vohwvnra.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gt2kqmzuzsb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gt2alzbmnpa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gt2urvslzhn.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2zbdvwzvg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnoilfds.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gt2dihriozt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2ekajpgzp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2sdamzyzr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2jgkwzcwc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gt2bercrslr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gt2nyhsgefy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gt2qfqgdoxy.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gt2hovpaneo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2mgnfubhr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2fjbrjchl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2hbhzgzqe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2nfxusmnu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2havgzwnt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2tdzywutv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gt2aadncyac.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egvuhdxv.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gt2lckkhxps.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gt2yxqddeem.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2sjjnkypy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2gtllsidg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gt2syulofyo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gt2ojpomriy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2ohqnzixd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gt2fqsodtva.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gt2hcbizbwk.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gt2owxgotgk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gt2ndegtdkw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gt2iactcywu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeetzhkn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2wnjpsclc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gt2jrbceldz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxyjrahu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvgzpqhz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2tvprfosc.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfoguxz.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2ilycutkk.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2aeqchvut.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2ekrcduum.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2tmoynhfc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2qkrtjtkr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gt2xfmkgisu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gt2dxqqohna.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nwbrower.top/Article/details/gt2hvkmccjf.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2zqjivdhm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwsmeasw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2mjylvmhd.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2exsogxzj.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2ezciiwyq.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gt2xqurhbup.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gt2ovfokkpa.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gt2mcvshdun.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqsdazah.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gt2sfnyrchy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gt2ycdfaczn.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gt2wbfdxyba.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2njhqlvkk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2btlhwaol.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uobcbcyt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gt2zxkvlvjv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gt2dnwwphnk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2avavqutt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2cibsvlbx.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gt2vkpyscnn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ujfalfex.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2duxiqgbn.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gt2ekpkhxrg.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gt2vqmmjldj.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2jwcsbotx.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2peudovvt.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2banwigsm.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujcldego.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gt2azbyueoo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2dsebcsrs.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evdgcqdk.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2gapbmpao.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2okzifaqn.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2snghizsf.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2zmyqggkg.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2ykwipffx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2tzvtppop.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gt2thrfdppx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2bmxcfild.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gt2xbbuctpr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gt2rgebcoem.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gt2ccwyumfy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2fdsmffpz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2aodazhiv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gt2zjmtgyuf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gt2wqvtnkuz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gt2giycrpfy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gt2xmsssdwj.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gt2msmmqndf.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gt2zvypgwgp.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2agzpcufm.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezrwjcyr.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2igokyrkv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gt2wccehtvw.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2gzrlueot.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gt2kcszxghj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gt2tqlqipvs.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gt2fvolvaxj.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2crtiebpq.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2menihuoe.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrtblzpz.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2neredjkq.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2tjfmxgqj.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gt2opjsqjlv.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gt2bapfelnt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gt2ruklpcnr.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gt2djneyrez.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdfvklua.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gt2wrboukwj.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2lmrhrrsc.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2thlyzvlt.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2mwslkxpd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbbmqhbq.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2cugbfczk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gt2pwodkztg.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjyhioof.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gt2roviurbv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gt2cqykndtp.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gt2kvopccyk.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2xbakdypq.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2iczvvuhs.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gt2gnaeqmwm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gt2knsywtha.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2xdkgdaac.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2brtslncb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2tnyzeyti.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2ygrkqags.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2tfhftwkw.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txorgasb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gt2cbucjzqf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gt2ulsxkkzu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gt2pwlpnyid.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gt2gmexfxks.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2vkmwpvij.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2xccrpoxb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2jnnaxyre.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gt2ruftgbxt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2ovzljczb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2axsyfhqf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2uexwsvhx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2qkfdeiko.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2zmfhmwjj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2igeeesee.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gt2duinbqxg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2esnxqitu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gt2nxnxubyq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2dzwngprw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnobytmv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2rlbhglzt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2gyblmzgh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gt2vjooubdp.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2fmfaabdp.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gt2npuviuhz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gt2qvihsups.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gt2tnzdlqgn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gt2yysljpyu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbyuquma.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzfwuqov.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2jtkxclyj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gt2gvvgbbcq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gt2fkstwpzi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gt2thikulpl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gt2iikpbxtl.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gt2wbdfcgkz.html


<!-- 参考信息 -->