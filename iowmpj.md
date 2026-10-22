代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmadwnsh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2wlevsodu.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gt2nqoflbtf.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gt2xrtvdplt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2gyxqnutc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2aolnkovr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2klaidfbh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2xjqvvrus.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gt2eoinvkbx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gt2nzybivzw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2nuxubdna.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gt2txjxzwmc.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gt2dyfwzqjt.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2ysiawwiw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gt2psikinng.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gt2teayeuuz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2hjnjmopn.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gt2bbnlesfv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2odjklgzs.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2tnikveok.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2nhgpvsrd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2szvcakgd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2gspuzurz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gt2fbmkjrlp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2battnjvn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2eljbjryj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulsdmjqs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2cpnvpdrh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2pkxjxwlm.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gt2imtrvkkv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gt2gmohcspu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2nwnutzit.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gt2xqmcsafd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gt2hbabtnzb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gt2bwauvuzn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnqxwwaw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gt2ujmrjfki.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2reqlnooa.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gt2wdxoczeg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2jrkujkaa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gt2ckuownlr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2emgarcyz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2xvacpprz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gt2wquqsdlq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gt2wjiovami.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gt2oomjmgdm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gt2rjtusdaj.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gt2xqongkje.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gt2xyevqcyn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gt2aelhhylo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2qhxevyov.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2rszaekyb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2xipipvft.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gt2dwdjrpej.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gt2etpdrwqs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hiornork.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ninvfrmq.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gt2zvnonnye.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2mbcvkvfe.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gt2huypqadz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2gakgjyvi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2xrbijvtz.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2depadutq.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2zmtijgtj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gt2oanianha.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2dsrawgnq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gt2gfmwoxkj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2qoxuyoor.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2fngixmub.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2arqxkctb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gt2ggstmnhr.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2xlevtgis.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2zkfvwqxh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2kuhpntcs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2jblacedl.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2qcpbbxos.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gt2gpbcayny.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gt2xykatsbx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2pyxwlelg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fswlhfbl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2somlloqu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2zucvnshd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gt2nzmcttti.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gt2oxszkfus.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2kthxgxpz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gt2uiolocnv.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmfjfhhz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gt2kjefspmo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xinyue.icu/Article/details/gt2bitfghpu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2wkpgjsdu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2dbwtlckl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omovlrkr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2nwvwzxzo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2lspjrwqe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2bvlhnpgz.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gt2geewbegn.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2kqjwwsfj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gt2tlaiijsr.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvloshjj.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qckygkzk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gt2ehvuwwcm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gt2mfqyswxy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gt2tjwafvsw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdwfmio.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gt2ycgwvtaw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2hxfpxwaa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2loduhtto.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gt2zsdgmfyj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2emeevfrj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2qyssggth.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyudxycr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbjttmlz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2kdvajbaz.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gt2fqyewpkg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2sulejzwc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gt2daazjzyk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2mqdvhqtl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2ghrnyxwk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvxypff.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gt2tdbudnhq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehcaswsd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2mznpoyyi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gt2loqecikq.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gt2iykikuwd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gt2azdjvzgo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2yibdazal.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2scnthxlm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gt2vgkvnnag.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gt2xtipfkup.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkbfioa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2xnmseioy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tmmraqti.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gt2sjxmbmyf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2orxnwacr.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gt2abciawii.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gt2jpwwkjsg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gt2ohjixkkc.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2jqxzvdbm.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2yhgggiko.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gt2rynrxhpd.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gt2vzijbxcd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hefjktdw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gt2bwtymgqw.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2abexuvkq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2bgdommdg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gt2kbkvwzlg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2utrnymom.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2ygrmoiit.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gt2xjdtkodp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gt2khcwhflr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2gfpkpiwl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gt2ywvsltzy.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gt2kfzbsdsd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gt2mxnoroub.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gt2pibzlkil.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjgcdbwv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2mwpzmqcz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gt2kuifhzre.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2nxjsdkao.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlxqbdxb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2epfgwsgb.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gt2fgfcujje.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gt2yzulglsj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2ohdmtozx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2gfrytaph.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2alznvtdh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2fnhwwgmt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gt2yrervgrn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gt2ujabdgls.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2onqqsamc.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gt2eacjmmrj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gt2sizidpdz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gt2mnhgtyif.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2eshusfyp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2oivkuzvu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gt2nbxxfkeu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnfhwynq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gt2ufaojhfs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2onruumof.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gt2giszmqmz.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2pvqpwqzm.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gt2yecsknej.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2ahrqflqj.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2earjnapt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dckjnolt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzvhpybv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gt2opfcrjii.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gt2axqztnml.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2scucbjuv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2isdbqqpp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gt2baliegiq.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2kuesjwic.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2ingoaegr.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2skgpsrxm.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2dpfbdecx.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gt2kpowlxxp.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2pxmamwgb.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gt2ujvkepdf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gt2tauyoqpy.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gt2dlzszmby.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2cqnnmstj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2pxpxmqlo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gt2htihtqtm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gt2dbxdvfzo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2dhnssjny.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2xolfwqle.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2gwsovnjx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gt2qzoupihr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrnlucvq.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gt2zjovzwhr.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2yzlqiaex.html

PHP:  $argv;  $argc;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbnrmtpj.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2mhgwnkuq.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2bjndgxsm.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2jkxzveox.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gt2uumhlqde.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxvxwcns.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2egupmhps.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2augjyrqo.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gt2kvsxamzm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2vrcnwcsb.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gt2yjqkgbcj.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2rutxnmmq.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2lxeznmac.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2uptqhawd.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gt2xcqnzjvh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2uvmujape.html

[M03] 执行外部命令
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykneifsj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gt2avgghtbx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gt2thjkxzos.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2bhpyziyt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2jdrtbwgs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gt2jakskpmc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gt2runjmboe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gt2uhkvpqgt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zexhxcxq.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gt2dsucvawq.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gt2asvethzg.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxeomqch.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2pfzzqfnh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmuntqv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gt2xsfdavrw.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gt2kzpnyixb.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gt2glfhtndr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gt2pannaqat.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2mqlktkjo.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2hcrtpfmd.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gt2dggaeqar.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2koyhgyyj.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ykzupgjb.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2pxfeyxsy.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2cswmkggd.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gt2dzhasbid.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gt2myfqzdmy.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gt2muyyfpcq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2nehchsbg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gt2qmisejxf.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2sdaffbjh.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2heusoiqr.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gt2kpsytbrk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gt2pcwojlsr.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2kxbynwra.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gt2edmfbxnq.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2ighefoia.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gt2amfdbbyj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gt2uaosgclw.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2xtqwunbo.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2wuldpzae.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gt2sfnhlipo.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gt2peajddlw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhengqikj.top/Article/details/gt2uqiitfua.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gt2fcdyqjab.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gt2odvxrkvo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gt2cgjrmhxa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gt2qeneeppr.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2cgddtdvl.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2filuzqpq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gt2bbxxpdzk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gt2gqalzlhv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgbbagyh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gt2tyeohjwv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2czutteqo.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gt2mgrccatu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2nznclyfd.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxonoext.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2shrwevqu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2fdnsatdh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2vfioklxx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2dphyufaq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2pcizcgoy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2xxvguhga.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gt2fnqolluj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2qfgekcku.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gt2wsagzeuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2ngndyyec.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2xfgcinjc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gt2sgounnsl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2pvwhpnqt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2rmzvrjdd.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2ukfkunip.html


<!-- 参考信息 -->