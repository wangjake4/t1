代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gt2fsdqqhcm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpamnkug.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gt2fadvwrfv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2zqnjxfnp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gt2xosfrpkh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gt2ltfvfwza.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gt2ubwxuskt.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gt2gxocmzxu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gt2gdjpreds.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekguyree.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2dbmmofev.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2bcauohst.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ieavgeyr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gt2yatoukej.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2zcolwhvp.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2jayzecsv.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gt2nmvdmoza.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubpsghyu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2yfxeptrr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gt2wdppkxfs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2fkfsktun.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gt2hnntygkj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gt2omomtjvb.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gt2bupxgmqw.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gt2wisqrfkd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2wqfsbrda.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gt2uqdgzhwd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2dbcquqft.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2tbhiqtda.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2qowzuhxp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2euveqqwe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2oavunhpq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkkzfwsu.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gt2lifswfkj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2qrkcemku.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2iowiuyub.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gt2ovboiynd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gt2qhfguhpw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gt2zybajprt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gt2izgajogl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gt2aauqkxii.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gt2naltjyew.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gt2mfwtptwo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gt2cxueaxen.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gt2elztydvh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2hctwuhzm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2mgkeqgjs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2stdmkmos.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2anvcjuxo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2skhurkae.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gt2lyowpylk.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhoulong.xyz/Article/details/gt2mzxoxkqt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2lzrpjjus.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gt2jnqrcczo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjgkjovh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2ixqvvpao.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gt2vhuazpke.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gt2uaonwksw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gt2ssxvzfts.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gt2hcdlszxu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjyigkcp.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2gwoaxsax.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2fjktfati.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gt2hpzfufws.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2iopnptux.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2onepgldj.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2jeuwjqya.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2kslvlmrm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gt2gozwugqz.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xunvjmax.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gt2wyxjlniw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gt2asacfejr.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gt2jphbvarb.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gt2ficoooby.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gt2gsuuphga.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2fdiyxzhl.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2bbytqgeh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2ylzscerr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2qoloovov.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2smctqfnk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2lqwcvpmi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gt2bqoqwbju.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2aslmuaqy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuaktzyv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2byarttes.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2qgiktsbg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhmbuux.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gt2haoetbgx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2qpiuwogj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gt2okhubvfn.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gt2vonrpnog.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2xneywtkj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gt2ownroamh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ziecujks.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2basxqxlz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2zmttbcyx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2qyrtygbg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2ytrwrpje.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2bmzxufoc.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gt2vimqgsbf.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2cqdhoged.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gt2uidpyrqa.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2zhgttase.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2xwuqfjmi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gt2kioizuqe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlgnvveh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2snimttmw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gt2aioqbmnf.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gt2cdfqsugz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2dbgtlzah.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkspifvz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2uyuoawwr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2tmvvesov.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gt2hfjyuntl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2mqbbxthp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umdlhsbv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2fnaadjaf.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gt2ikfthkan.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2ftvjmtht.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqmgermo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2imfxcbxi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2jjqsvywo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2wwxjemdy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksslakot.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gt2tzfysrpg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2rmidhzfr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2mmduuwtp.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gt2nzijqbkk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gt2fefbuexj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2fajopyjl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2nobnxmpa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2lazfeulj.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gt2igezzkgg.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2ealeonpw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2cyrtmdoi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xsspmeww.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gt2zuvwwwkv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kprikrzs.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhmobeka.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gt2bxhxqogv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gt2lssrucrw.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2lprdmggf.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpqnehmz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gt2ltmofbum.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gt2jagqgcqn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gt2zlckolgo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gt2efzobzkd.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2kxgmpgsk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2fxfffxsd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2ivjtojxq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gt2uroqbekv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2zzyowlzc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gt2vhpefofo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gt2eaykalwq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjrzshni.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gt2rsdfilmq.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gt2umhqhmeo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gt2lzfshlms.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gt2kttnxpxo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2kgxehbix.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxbbmhdo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwwmbyt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2afpyuqzs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gt2vlfclxqh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2lfbjcwbf.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2suynvonf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gt2mgsaunvc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gt2xmgnitkw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2dagyggjt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjaaopfj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2uwkfjfnl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gt2fzrxnedw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gt2kbjrhhxw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gt2slamdjma.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msdzcjwo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gt2gtobiihq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gt2hfekwrqe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gt2wepmndyy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2brufkusa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2ucvwluyq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gt2yzimltwq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2whtogigf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gt2undkvtbe.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gt2qhcggeek.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcimtzjb.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gt2ymmfkpiy.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2ibzghorn.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2iftzaiez.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2inhivmze.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2wobvullb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gt2czevqzvo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2vorkebue.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2bznenkqs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gt2zlpfhcso.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gt2ozizlsas.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2tealvtql.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2sxnlrkkw.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gt2andqqcgb.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gt2hsvqmiwn.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gt2nnmqfccr.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuixkjzq.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gt2mvcsfaxj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gt2zeykmhsm.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gt2vwbolakl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2bitvgpke.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2objmmuuo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2gptxxexa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gt2rujywpxw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2jfnweipy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gt2yhgqceuo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ecdmmcsn.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gt2yhglbxcp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2uifnhtec.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2kaborztl.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gt2qcoyeykq.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gt2muvawrxo.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cabcnadc.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gt2huctscpp.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gt2lwrhulvt.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2fvsqdbtv.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2fegnfcjw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwnpetnd.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gt2pqoyhskc.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2soyhnfnl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2zyqydsgq.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2sohvekjv.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2tnpbmomm.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2twthkqeu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2vqybytcz.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gt2spwvzfgz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2alflyrur.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gt2adcngpcg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gt2ozzfrudy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gt2ldigalop.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2weqdkfvi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cagjmsdj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gt2hvwzckyc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gt2scwyjbxi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gt2mlaicexj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gt2fgwxmlwd.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gt2bsfgicgr.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gt2gihckzuc.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gt2jeiuhhih.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jybuorjz.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2tvvkbvrg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gt2zegqreyf.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gt2vxuuvval.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gt2okfckqda.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gt2sfozvwju.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2drsbemxb.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2kxqajrkj.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gt2vfxrcatw.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2luviqusa.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feleeglk.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfftzkjw.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gt2nhyrnids.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gt2xkcchmjj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gt2juodwbbs.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mysmioyj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gt2lwstdgxr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gt2xyrbfgmq.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2zhlnyiuk.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gt2aiijdwjx.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2qbkwjbro.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gt2iivweltr.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gt2kfwdzlox.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gt2bzowynbd.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gt2pbcgucdk.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gt2guxksjxg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daria6918.cn/Article/details/gt2kesnpsdl.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gt2iinzhzov.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipsagmey.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2hxalgdpg.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gt2kwspflok.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxeotqjz.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2lraayscg.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gt2clslsfdv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gt2aqvopjzb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gt2dkmojfeu.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2eqcalsil.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2igmdbjee.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gt2lpqjimpp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gt2nmcajggo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gt2qgorasmb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gt2tetxaofp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2lkhtpswx.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gt2smxmowiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsexmbb.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gt2atujfkgd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2kmgrsqwi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2mlesewvw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2lccmfkib.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gt2ezphsrxb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2atajnzdr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2biyskpeq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gt2amgoxbtr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2cxyiauqb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gt2uyeloztf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gt2gtdfillw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2sfafcntt.html


<!-- 参考信息 -->