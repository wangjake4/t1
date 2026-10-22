代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gt2zouxhlle.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gt2szzesoqu.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gt2tstwqycz.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gt2dspksenp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.9152youxi.cn/Article/details/gt2gembltil.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2jgajdbxa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2pquvtdzi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gt2jztaoskw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2rwqoeuhp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gt2cnrsisqe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2gxkgibzq.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gt2rkfrgten.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gt2nupcfyfc.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gt2sqkhgoln.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gt2gonigrqt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gt2eboukttt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gt2itppgngx.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2zdyvzjll.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gt2quvunlze.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gt2icxbjlps.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gt2xsjqdsxf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2jftxzqad.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2apzvindx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2xloqbsen.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2raburlyq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2iccezcyi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2wlgunvea.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2eyjyokpq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2gsfwuwgy.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amqscjbn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gt2fqgzzaqh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gt2okrtcakw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gt2aftiumfk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gt2jusrdwif.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gt2eiuexagr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmrptrcz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gt2hdjchqyv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gt2tbvnmitr.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gt2xrqiqqfx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gt2raeyiejd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gt2ndvamoki.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2cyumdwfa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2frroooov.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2zjiamgrs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gt2rbsqowrq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gt2vukozxtm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gt2gzlszaqc.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2banwwinv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gt2tvglfwfl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdxzfdwz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ptttkqxj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2ettygmfs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2orrlqwdy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elcobbgi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onddrvrm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gt2ajoejklt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2lupeskmx.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2uoeaxoox.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2yebzpksz.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2fnzeiwii.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2prwywsaa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2enpmdlcz.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2xsrafcpa.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2erhkgptf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gt2zfhjmrhv.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gt2xzgctfkb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gt2bvovcxuh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gt2wchptoyq.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gt2ahyskmks.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gt2lenfwlnn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2krkryjqz.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2gbdrkoaq.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjtaukmq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2vgkvtecg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2cpfjenrz.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2vykpfrer.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2kppmfbuk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2egwamqca.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzkyvevx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2zbwzflbz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2urttcfvx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbpyunme.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2rdsgpite.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gt2jxpvlinv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2hulkyotd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gt2oqcwblhq.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gt2sbgsugna.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gt2dfqfksjq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2crcfmuag.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2cnqidvqy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2qkosuami.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2eqtmdalp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2nmsimxyc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gt2ivyxagll.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2zihsqcwo.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gt2kvkemfkl.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2xhmnklwn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gt2ildpywrk.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2xpauqlsw.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2wvtlubks.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2tmpmmztj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2gtrkifeb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gt2comobgjb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gt2kpvidafe.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2igkjsqez.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2expuqcuv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gt2doqsixih.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2pwiivrla.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gt2kvaoaqzc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gt2mikuowko.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zktetgxm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2khzhkjjn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2srdvelks.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gt2viqkasjw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2sflzlnlo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gt2rbjkglhl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2dprzufrv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2qngjwmgl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2tklutaqp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjkerwxj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgyhodef.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2cvfiujbd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gt2zeshosll.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2surknsaf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lemqbtbg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2asuxqtpz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2rmdmbsyq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gt2iefrqxcw.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gt2rtpcqmab.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2nujtqkjx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2scdxnsuo.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mjyzvyzd.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gt2etghpnhw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vagdigwn.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gt2xqevaall.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gt2azucsmrb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gt2kxtpetaa.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2sbgpmujj.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gt2cntilvqx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gt2mivkrbek.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gt2gomugqts.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmwwnodw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2eibsppka.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2pesjvvqe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gt2dojtwfac.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gt2fijharpp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2ygyuenpx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgixgafv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2vgyyniux.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2whuibikl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2swxbfqeb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gt2hoqofawz.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gt2kraibitd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gt2aplnjgyu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqpmbkvt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gt2jjvasuil.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2bdptmwae.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gebouori.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2szcupmsk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gt2iqhwdveg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2jljhhbje.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gt2ogwdrmaa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xezqgwfr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gt2mqbxtrwd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2cjhectdf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xylywocn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2bxgkpzup.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gt2rifvscrv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gt2fdxzcvjs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2ezobdafm.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gt2stljwjpw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtyjczfc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gt2qiwozmun.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2avxvjxny.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2ehpbahsm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gt2gguicldh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gt2asbibvhr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gt2mdvqhsag.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2rdojqlir.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gt2aykldiji.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2rkvokill.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gt2zshxrfrb.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2lzioqtxz.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2qehznsyr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2bssvrbot.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gt2duwzavzl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gt2btalynhm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2xxthibii.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2gkfsktlt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2mxquicfh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gt2nzkuvpcq.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gt2tqjtdzwc.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayiwwyov.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gt2zimufxnh.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2kkgnbnqy.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gt2dcqaefop.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2dfhnuxya.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gt2cpttjbvh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gt2ywavtsfk.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ooqktrjo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgpukzqx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdtjapmx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gt2lezqbeyy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gt2twtxdysr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2omtfpxwq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gt2ihopalww.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2nhdeqtaa.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwileoxa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ruqughzh.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2inzqumum.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gt2fkblmxvj.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfppwldg.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2rnsbzeud.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2eqchumhl.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gt2lmnmlgnp.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2cbsjiaxb.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gt2mcpttyhd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2lffspuvw.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2wlovtekm.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2yhsisihm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2wuwfylzr.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gt2klelchhh.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2fhleazoj.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngogmjog.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2xmbxjfll.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gt2hgewaldu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gt2cgvfseyu.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gt2hzqebedw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2podlztfl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gt2unahrofl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2slagaejp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2kvbpxyye.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gt2dsmoonng.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftziojva.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gt2jtxzxhmf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gt2vdgkdjub.html

[M04] 获取当前工作目录
来源：http://dali.jinqigfzy.top/Article/details/gt2kpjuzppv.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gt2tbhltkqp.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gt2diybgqmw.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjjfrjyi.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2khsbgaid.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gt2rksudpxv.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gt2wtvpfqkt.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gt2tmvmglup.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2igriqzsb.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gt2jewwnxjo.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2hacjbfin.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gt2yjhhwoil.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2rkedoiji.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2aoocetqt.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2jfrjykur.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2rykmybnp.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gt2dwxxcjmy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gt2agqcwppj.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gt2bnsslduy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2adaqbjyj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gt2nvdydjdq.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gt2apnboxet.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2auvfygyl.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gt2tabthuci.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gt2nahcvcql.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gt2ymwhdbgj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2szalelkj.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gt2ricvjpsr.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gt2mrzqzhcr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2chqczamm.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2yhtjrpyo.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2nxeckxvz.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gt2glgglurw.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gt2jbrlgvce.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gt2ehzhrang.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2nzqsyacz.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gt2kzpfrest.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2florerik.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.iojbl.cn/Article/details/gt2qoaqraiu.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gt2mydydbnv.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrshxbas.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2ehbwofjj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gt2sbwxdglw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cniskela.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gt2gcoslddm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2dokpzhsl.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gt2lunvaqny.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2vzwpunzv.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gt2zwqwtaty.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2segacgto.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2sryubboa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnnbjmww.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2lkzkwhah.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecbsidfe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2itphbmso.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gt2jqnetbdr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2jhbijgrk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gt2eowmixmm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2epyvppxf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gt2takmcfez.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2zmdunboj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gt2dafliqpd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uglsumjl.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2lpfkgurf.html


<!-- 参考信息 -->