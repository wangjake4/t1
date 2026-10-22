代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtjebzvhfd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtbrghhwnk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtuorrcywd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gtofjdkvld.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gtodfwdaav.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtjwsnmofb.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gtmfcuhaxu.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gtkqahobtl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gtodbxbekh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtjjnojrlb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtxkodlorn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtluziojdl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtgkaxjhrj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtzeuljjhn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtdkwxpemd.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gtcmjrpmrw.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevemqmfm.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtsjmotfeg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtfhsscllb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gthjabbhue.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtyhenbwce.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtpkriyyvl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtqsxxkpiv.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gtntgeqssl.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtumbxcjaf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtbzedwyuw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtcqdwublq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtsbvglrhn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtjmougfbv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gttimiikff.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtoxogdrhz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtvzyzbeyb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gthizyqpfs.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghaxyfqn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtlrnvxsah.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtaaxuavlx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gttnavjzef.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtxvncgaml.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gtkbwxtoxu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtnurkxpos.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtlwhfcgit.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtbffumcsf.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gtidaacnzu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gtyfqsmptp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtfzgwyuqi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtisgwdlnl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtxnqtsvng.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtcvtqqxfh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtdrblzkut.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtrrkjcrwo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gtgsgcgkji.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtvuupznld.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gteyrhiwjm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgmuuyao.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtodypqbso.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtgvuaqegw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gtydxghlgk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtlolcpqoq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtapgxmamm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtlkihrycj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcwpromiz.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtiwuhtgyh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkekpapcp.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gtfijpofcs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gthsstpcog.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjcpvhhh.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtnmpkbnik.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtnbhsecpw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtkhvbphka.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gtnqlssazt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtzbgatyls.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjptsayo.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtaaooqfbc.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdfxxqmn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtsebnxjsa.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gteagbrgpz.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtnbtnhjuv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtwftvcfyl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtrkaytbta.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtmtwzkknu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtycaiujdb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gtytybalxw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtigiaggxh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtymhaykwq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtprfoeumi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtsoriuhlq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtiiipzvos.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gtppvieagi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtxwhomler.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtasfspcel.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtprumrhdp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgdmbmio.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtokxgnyic.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtyvdhcyvw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtorblouoh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtkiykvttx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtxxxorxwh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqwkuamy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtcmsciubv.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtgsbtujpr.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gthabflhpu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtkldmkpod.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtqgyroldn.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtygjsrmnm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtegqeuwft.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtjiqegwln.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtweaibqnb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gtxqceoaer.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gtutilgzdf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtpztioxct.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtlimgtndf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtkcknrwmo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtjkhqhvqe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gtysdnbvty.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtykerakgs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtzfbfxriw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtmsipbrbx.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtoiacsqcg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeyhgkpo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtabbxzedp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtzlvbeohs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtxbohsioj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gthxwqdioo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtdgvihhtu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtqseqwlof.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtclfwtqcm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtgbknpsrc.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gtoaryzxeo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtsnkpvwqu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtlrpgwwcl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtnuehxadc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtnozxtigr.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtjewqqgbh.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtrpknjimh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtvnwipofw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyhoickuc.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtmwthoeqi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpjhlclxv.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtuasiqefh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gtgpwrtrji.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gtzqvfmwzn.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtockiuere.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gttjgftmme.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gthtmbobji.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gtugssqhkh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmxakxhw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gtsbtkjugr.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtmfubgpxq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtjbbdxmos.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtbwvolgxk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtvnzddzlc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtsrdeslux.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtothyfirg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtpriwecoo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrrvazlp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtzyqzehqi.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gtginugeof.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtuonmiufx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtnugnkhcx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtiwowpfju.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtyiwwmqhv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gtkisbfilw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gttnckefmv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gtnrcxtkda.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gttzwhotvq.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtueoaaytx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtqlcfehvs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtnldkjtut.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtouwfrppo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gtknpieten.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gtnaxgincw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gtjuppxeiv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gtdxrrolmw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtlcqhgnls.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpycfoyq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtdgvmmoti.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtlgztskxs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtahuoyewu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtslltdegp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtdygcbiou.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtctnborjz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtgvqzkpzr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtzgurldim.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gttfieaxpi.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtlufzzfet.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtgpddmdgs.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtgoaephnr.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtnwywbntb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtpkdvvvaw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtvdgeheou.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtrnxbfekr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtqnhedawa.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtxaqdfepx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtpbikmfrh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtfhtypqtp.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtliwjgpcb.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtccuafhaw.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtistpqcjw.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtslrucupe.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtjachogrd.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmwaecxs.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gtybmsjgvt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtnctlgpzh.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtufphoenj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gthbkwmwpw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtkxlfjidk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gtoclgqzsr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtexicmtem.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gtlsehrfcd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gtizmrwizk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrvfkrlcm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtxbfymtgt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkhpnbakv.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gteyxxuwgp.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gthxwqzyfs.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtozdruwos.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtnrqnypzx.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtjkltjbfl.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtfpkaxcsy.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtbsncxtvy.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gtmizkqnhc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gthwgoxygk.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtljbseana.html

Py:   os.environ.get("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtmxykklpg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtrkyedavd.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtvudbagbf.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtvcfkrdpk.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtseeweizq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtcgwiupsj.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtkpdqxikx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtttcjnvrc.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtbrbmuhyb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtsighcwtg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtswjniqwl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtqbtvbbok.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtquoctvav.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtqwiekrpa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfregubyl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjxttwfr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtsqplqwgm.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtyjrsvfxj.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtedzydjnw.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtswplyzsm.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtiyigvvir.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtfpkgxeeq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtzulocwtz.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtxuoaztgx.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtmcyecfyr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtmqphrwpq.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gtuychjkbo.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtxlwizpoo.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztqwgqou.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtyewhhrde.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtcjsyzacn.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvszlanpk.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtuwubvuyi.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtpwhhpugi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtgvpamnkw.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtgnlmdgzn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtvudjxhii.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gtdnwzkakk.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gthjmouuan.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtqclusuum.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gttwtzgwul.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtvvearynl.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gthfpehnle.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnmosnvb.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtkfbtezpm.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtadffhflp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gtcetkjfdq.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtzpwjicaw.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtcicygyba.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtfdlntesl.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtxcuumcql.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtnmnwbjis.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzldgbgbd.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtgyxctjhj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtonawkpxt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gtegcoofae.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtfnqcwucx.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtaomjeqdw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtcqqgbwza.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtrwbjtgkc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtkbjeymio.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gtfdkjadna.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtojzgipba.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtlnrhxulp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxwidgeun.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqdzrufq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtkpdfbous.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtynnnbadb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtowgfdwep.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtwxfexxfp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtkhxikrpn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gttvgyojig.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtmkdxkpqr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtuuunjxwb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtwzahthqu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtrpttbtmv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gthykhwziq.html


<!-- 参考信息 -->