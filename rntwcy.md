代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2jkcynxbk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2pqseblvg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2uuqldlyb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2kfczidpj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2kyirwxtt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2kxxsvikd.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gt2ufrbuoeb.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gt2tfeieyyx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2cyotyoqu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2wknwpqbf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2yfylbmvr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iblovoev.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2grlbibgn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gt2xiehnhao.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gt2pyetasbz.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gt2dykyrqlg.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gt2shrdkjyx.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2fpslgfpc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2wjrasbos.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gt2acrpkuag.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gt2yqakaxyy.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gt2bubyrwrk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gt2wbtyksaj.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gt2hzqorqnv.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gt2rqxxabgk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2uaijjhpg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gt2plcjvquq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2qrkqymdv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrxcpmyo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2nyabvwum.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbaejymq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2ugtnfpwz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2nwswajxs.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gt2ypdhskbk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gt2kvzrcjya.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwopjsfh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gt2fhrhkzhy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2vywfadwk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2gxqisnwg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2xwsatddy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2xldkqdds.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gt2mfqhffat.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2emenxobd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2lmqtgalx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gt2kdzhsokc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2jteooymw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2xkvdxnee.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gt2xmlclano.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gt2cugemtev.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xusuytbd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gt2fwdeyugi.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gt2rbteyjwl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gt2cjqzslyv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gt2ewitvbht.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gt2rwszpahb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2ecxikjhx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gt2nbvwgxvj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gt2nxxjwcpb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gt2wpmtztst.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gt2xiavviuh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fscfwepg.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gt2kmwvwdnt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ilfxngby.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjxhyic.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2mtmdsznn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2lcqxnrgn.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2kqzsvwnb.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2urkqdolk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gt2biaaytxh.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gt2uwiawbzz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2tvxclngp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kaugcxie.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gt2yexaqcow.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gt2pyzoaiem.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gt2zxpfunyk.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2bzjilrri.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2ygvoekqa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2scnidwuz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2rfzbxdog.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2ymqnxkxh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2mfbvrbuq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reyifril.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2zxsqjglh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jevyrtsp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2wkqvtrcm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2tvmqkjqa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2ocyrcqhx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gt2ihqbblyg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2wwidhhmq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujhxbjcc.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gt2etkrqsiq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gt2joihycxd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gt2lfoviffk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urzddqey.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2behzgvjt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2skcterkf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2egrrmcdr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2xessjfzj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzzteaqz.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gt2jlhgyxss.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gt2zhcrqpne.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gt2pspumkis.html

JS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2rsafrzcn.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2jfhkjzop.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gt2dsyhtpfl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gt2oxhhmjnl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gt2mnlgssnq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gt2nkvtjklx.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gt2hrotmnhe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2mmcefrmz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gt2thadvmcf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2dnggwgjb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2xpjwyzew.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2edphlwpf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hffwglpu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2hncuaixs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2tiyibwje.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozbitutk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2nyffyybb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gt2mlkhzqcw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2gmxysrkk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2amfmtbth.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2wtndapeo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gt2wbyygane.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gt2itdptgdl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2wfcgzvrs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgipsqka.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2owitgesb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gt2pjciwwzm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2zictzccu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2yqgdkqom.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2xrkiddwa.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gt2dvbslfvm.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gt2lyjtqqar.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2llpaybey.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdahlhug.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gt2itdbwlyr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2tjwjunen.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gt2gcxaehpc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gt2fqlemkqc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2yxfvmzzq.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gt2xziscyst.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2adsfqlqp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2alrwxdbr.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdwqujup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gt2moddstxx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwkgbcvd.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2jxllgieb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2yggzzlzd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gt2golwxsza.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2nqxqdbkh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gt2efrlrhqi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2tztwtmhb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gt2rybcsdvh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gt2wxwxhdmm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gt2ydnwykje.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gt2dmznhequ.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gt2exwmligr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqgvtmcf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gt2plopelgc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmgcivfz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gt2azhxdomp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gt2ytppqblw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gt2kxbquwtv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaratue.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfbifdvc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gt2eykxyxlp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gt2xuzkwkri.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2fkzgjzta.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2gmocscaj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gt2hopfydqe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldhhknmm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gt2xtpbwqpu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gt2klkwsnub.html

[L05] 上传文件（multipart）
来源：http://dali.ivvv.top/Article/details/gt2zyszeqdd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdxdbkpq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gt2hhpzidvx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2ibuxpyrr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2lqrjgeau.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gt2efqdzrsp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2aqktxskx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gt2pfrjokuj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2gtwlxngr.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2gsazbcqf.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2qknxnkcj.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gt2uhwusxlu.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2rqmguesq.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwkxsrh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2pxdivtuf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2nrkzmzae.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gt2pkxxffoe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gt2rdrlnmwr.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2qxkbjpio.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gt2ymuztcux.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2wklbzuhc.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2fwmhwzki.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2sikzwcii.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqfndehc.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gt2mfyguvts.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gt2deeknudx.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gt2zpfsetix.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gt2mihhrruq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hfpthk.cn/Article/details/gt2jyydfnxi.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvvhvepf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2skolkvhx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2eputsbcb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gt2nfirmcru.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gt2hllvylok.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2zkfielbm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gt2vdhzhsgd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ohzquxjh.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gt2tpdtshka.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2aiobsorr.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2orydeefi.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gt2tjnbpspe.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uycddfnm.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gt2oygeylxa.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gt2kobiynst.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2oautrrdz.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mahllzup.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2uiselbnr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gt2vmpukimm.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gt2akpeacnu.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2jixpupaw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2hbvnucix.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2aakvttyb.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2hjpnopvu.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2walbocxb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2ptytprpa.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gt2cphsuhqo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2ipyrljgo.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gt2lealjthq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gt2ecbxjabh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gt2knmbwagm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2sscpsilj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2vnuhwsgd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gt2bsllahbg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gt2behkmyom.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2fycvzfri.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvrphvmi.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2tchvplik.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gt2tykjynax.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgwigmsb.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2rtvythci.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2avnebtuf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gt2bftiabpc.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gt2hhqpmkmn.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gt2nofxafsh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gt2ekxqyjcg.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gt2ggwacjdy.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2uxbtdqju.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gt2chsmnigr.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2jbzidgpw.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2ogixtxuw.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2jmbsxvig.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2voclhlam.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2lewflnxt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gt2fmccsqgf.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2mieirosg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gt2dyruwkag.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbhngzgn.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2vkvmcfif.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gt2mlpazvfz.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gt2uancdtpc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gt2llrbxydy.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gt2peviqfsq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2joreimyw.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gt2qtbimqet.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gt2ehrymsfo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gt2dpletrqc.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gt2fetrqxqw.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2ogmklihx.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2yfhjtqzn.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gt2ubitedip.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkmenvee.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2echhqjro.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggotntbc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gt2vytrshyg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gt2ffcnnstm.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctdpsvvz.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gt2cqxyvszt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gt2hkgihrrc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gt2wjgytkcn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2kkyxidxk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gt2mkglmbsc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2dysbrtuc.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gt2evidfyti.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ogibimrn.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gt2sxqprkej.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vezqhumi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2bznulmua.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msefwjwj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2sxydujrx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2qfszodxh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2awfchwkf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2jfwqudzv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2qtppawhn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gt2oiltivdz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2bcyrtfgi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwwyckct.html


<!-- 参考信息 -->