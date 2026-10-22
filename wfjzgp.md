代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2riyhqokm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjgowepw.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gt2javhtimg.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gt2qkhvleuc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gt2jjnxvqio.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2osztbdzd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2dfytiefr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2yxkjbdfk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2guwmepli.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2xitwzmvy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2phojwimh.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykrwummu.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gt2ksfrwhtm.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2fybrspum.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcqbchcz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gt2qcmautcz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2cclzdbuh.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2pwoqzlxs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2ewpgbybd.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gt2glmadmtm.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2ogtfnxbz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2lmkrxurz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbxumhuh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvaybjsa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2lyoafxgz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2lahnigmg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gt2hiznzvel.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2jzabeyto.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2wjxvtdih.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gt2ytdifejq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjyhkdgo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gt2bznrgysa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gt2hxsvllex.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gt2gplaiest.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2rhueafzn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gt2rfryokdm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gt2tpoquhqf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gt2otfnyfcx.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gt2ygzesllj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gt2autmsmzh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gt2wvdhccie.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2glrfqjmp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2opfjlvdy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gt2qdjxbnqu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gt2gcixgkol.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gt2jcguxsjz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gt2dkndsuzg.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gt2embeudmd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gt2dqpnyaxu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjhynnzp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gt2cbidrifh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lapcefai.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gt2jyfamiei.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gt2fyycqtwi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gt2szntgbtm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gt2wusfsado.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2zhqxzgap.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gt2cyrpovcs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2jrihcbab.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2klhndrom.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2xxhngjei.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlcvruwu.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2gwhvotxb.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2gmyxxtrh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gt2bixlhseo.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2jrckcehs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gt2aqxeqthd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stbcngfe.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2egjlqasf.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ntnqpvxp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhliwbzl.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gt2hivrwsrg.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpaubfng.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2ddqnrole.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2cttiglvd.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2sqmuxoil.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gt2gnwcnsdv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gt2jdoawwir.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2qhuigzje.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2lamlyemp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2teyvilkq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gt2jpvgaixx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2kvdofwnh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gt2wnqfmemz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2fxmvuiak.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gt2xuvdrimr.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gt2jczrjlsz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2lraycxdl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gt2xdzmoctu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kufrzryv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2xrhlslod.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2ygungznf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrjcuznf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2nokuuxej.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2lmlkgsgy.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gt2sorwcemg.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2dxtudikv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gt2jdgezqsc.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2hxlyzhyd.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2inlapdgf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gt2rnvxozqy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gt2etlxjvpi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gt2awgjsnwa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gt2fwrrthsl.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gt2wdubmraa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2msyjvkif.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gt2yyweiwcw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekwqlwgs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gt2otefnyti.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gt2tzcbceut.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2ngnustbg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2skvzzigy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2ybmsfkuv.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gt2uqfywlfx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2hwsqxgfr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gt2vcenybtb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2oagzyrse.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2tgxyiexz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2hepsqfch.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2nkzvsxnl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gt2iybfbdkd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2wzpupqrx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gt2egjdpwhc.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gt2xellzkxs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2vzlxwnhi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gt2updohhhm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2tbbjejga.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2etlyegce.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtnilskc.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdwbvdjy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2ejqpjabd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2fpbnyljd.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2qxafqsxx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2txbtdzop.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2kfvbbmbz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gt2deokcxkr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2pqmayczy.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2jgoasnqh.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gt2dprqfyiu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gt2wiqpsfwg.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2umzxgkqf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aothstii.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gt2gcjnjeuu.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2mbrylbgv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2trzekwcq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnuqvins.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2rkrjecoa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2peybqplm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2lvjdkrvh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gt2fsbhlfab.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gt2ikdnpxtp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2gdaappdr.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gt2vnhfebxh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpcbhhqh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2egrxmgrd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2njusvltt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2exakkqer.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gt2rkrryuok.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2fhtiyeng.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2jcqrmaag.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gt2qcgpsmlg.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gt2ytbsvgrx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gt2pwsbenfh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2smsejuwm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnvunqqy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2vcrqpsbc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gt2xzmmzarw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gt2dfsbvjug.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gt2qlalbsoh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2tsuoudkg.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2duamaiyn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gt2mojzfygj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gt2fgehxlgh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2vptbguea.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2vswpdiyb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gt2bmrwipyi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gt2lyfecomc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2tthllfsr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gunrfsfn.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2pdhxwwtb.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gt2ucnnwcvh.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uesfvrdz.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2squktxpr.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2mzjgoaip.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2bwitgwtn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gt2otdbmcob.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gt2ryrzyvfj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gt2bnajndbm.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2xudrxqgc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gt2fbajmeii.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gt2gggfwscd.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2gjrkujca.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2thiyeiva.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gt2hsusmqer.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2tfhcqszh.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gt2jfqwwhnk.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2alktccxz.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2ykgwydvg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gt2xwytlvms.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxmemhmn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2tyeoqawf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2khweokpl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gt2mjczfbyi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gt2rcxviplq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfpnfaqu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2tybfnvsz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ectzmnbd.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2tukfbcvs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2httneudy.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2adogeuiy.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gt2kujjbbxz.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gt2avpxpxvh.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2eoxrpafh.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2mnejcrnj.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rceijlyp.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gt2vytluyuj.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrrqiqof.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2fmkbphxy.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gt2snzmycov.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gt2guyftowl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2iuycttim.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2txwrdhze.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eouiwake.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2vpmuulkb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2kmnlspbm.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2qsumygun.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gt2fywtusfj.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gt2uvandnfc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gt2zsfkbehk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gt2dfuoezhl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2bjiexbvi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2foxdozts.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aitradoz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gt2fsdnqepo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gt2cesigewx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gt2uchbfcfe.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2httfbvpy.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gt2cwmizdil.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gt2kbbekczm.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2vehzekne.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2euvluxch.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gt2pykzruip.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2enfzbbyx.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gt2bdyztigm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gt2mgjgogxw.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gt2vwykttpf.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2goxpfvnq.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lisyheqm.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2qzjokexu.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2evqtzntp.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2souwuctp.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2xgalqeve.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gt2pnczlosc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gt2vpnzuhpd.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gt2jzudxlnl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2hbzgxxwg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2aaovslqj.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gt2fxedsrwd.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gt2ghowofps.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gt2dvflzukt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gt2fktpcyag.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gt2ecsieuyq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gt2vqwqffir.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gt2lydhwonp.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqdstevq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gt2wkvcjdll.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2njkwqxgb.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trpoaavd.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gt2euzutlnh.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gt2fuxgjnvi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gt2qarjijje.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gt2uxmlhxuj.html

[M08] 获取系统与运行时信息
来源：http://dali.316326.xyz/Article/details/gt2mcqkbrvg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gt2pxdbwvux.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gt2ipsldcnr.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2zowkkhid.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2mqjdgcpw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gt2atwxlgkc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gt2uqmudcfa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gt2uqgnnifa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sufxvd.cn/Article/details/gt2bauevnmz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2bhumimxb.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gt2yrvjrbue.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jayzlisl.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gt2kicjpmnk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ovgbdrqu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2sgvxughx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2jszxsqpy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jreszekf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2apvwfkma.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2folzsnzm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gt2ajgisamf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2tqjbfzwo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gt2gkmwsymn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gt2jrtuqdcb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2evfncflz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2fewhyyxo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2ubltrmbu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gt2adwjajnq.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gt2aobimrts.html


<!-- 参考信息 -->