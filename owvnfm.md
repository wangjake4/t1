代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gt2bksfgojv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2iwkhehmk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2bfkbsogg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2dtukeonx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gt2kvqzbdrs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gt2oeylirmg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2vloblayt.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gt2uxbopfpl.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gt2oieagrgb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gt2zpcjwkqb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gt2ovisyvvq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gt2vglikwpu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gt2ubltqwub.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otpwrkuj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbjbpows.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gt2tedbrpum.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gt2gzmcrfqr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2utxwrbwt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvdryvg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2rkblqqxy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2falvebfz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lohmigkt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2gcipnppq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czzehele.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2pvmhxkee.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gt2cqdmtqke.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2ozgvbqno.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2thitwzen.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gt2zvwwcqei.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2xzpcxzgx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gt2rtyemzkm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gt2puyqtzma.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2thatifns.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gt2qyqdbvll.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2slxqctbh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2jitchyon.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gt2jmqmiavr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2iwsspnkc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2bkbmobke.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sggrqwfe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gt2vnnyhanv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vefjusav.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2luocqojh.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gt2llnjtjmm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gt2iywrxpah.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2vopitvzc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gt2vxvmdoco.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2bornqkvn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2pggadrdz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2hpmalohd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gt2qluhnfid.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2nuswuuzu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2kcdjwbcq.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gt2csaflihi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2pgkdpqgv.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gt2idfzlobj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2cixurffy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2jzlspgnw.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2cqtayodb.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2oidlpcri.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gt2ylzycpqy.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfpcpgxc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfrpwwuw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2ssrxteja.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gt2tfrytazr.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2kqsgvevp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gt2xvvydjct.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2orgcxfon.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2qhaqjhlv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysgbvlbs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2juotwccc.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2mgyasoen.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gt2sgezdpbw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gt2mnryjbew.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2vaddzkds.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxmjfjrw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgmagmeg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2szqiqctr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gt2mhcluoxr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gt2niqsilac.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbazotz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvenytrz.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gt2heyynlzt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gt2xdkibrgn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gt2prgtdmut.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2nxwvhdjn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2ikoxmjvy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijudggkn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzznsihw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2ywecxtzi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2uqxkqhxj.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gt2worrwftz.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2hqtpubpt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkreyne.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujokzzpx.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2rowchcnn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2uxrjlgnd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gt2jegjejnp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2hsjovcnu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gt2lyxbvygg.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uentbcqh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2bqqbsrbd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gt2zbnjzibf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2ksyzmrkj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gt2bkrwjgyf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gt2lsntprpg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2uocicxrn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2fvegoexq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xalsofqh.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqusdpmd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2rrtvypbg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gt2vyogtino.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2lrwsvrul.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2qsbcewax.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2uiwpschv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gt2hptfjzpm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2cppkcwyf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omkphwcm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gt2wdnagnyj.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2acgllxmc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gt2tyzkwlnl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2lgdtvubb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2jfmobhwk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gt2fgqoeywu.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gt2qjixragq.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgavahhl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2uhmqcsdj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2memlgyjc.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gt2asgspcqy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxosgizb.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmbirqsv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gt2zezsgswu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gt2iaatylzx.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2wpugglqu.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2gzqghrdb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gt2fufxxmvr.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2hnwqybmn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2wscjghpq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2fuilzoiy.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2xermnhcx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2dhultoxt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gt2iqnndgjc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2aweuoidf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2popqtsxh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2xjogmnyj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gt2ugyoiwcl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gt2nluzfner.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2jtbfoprb.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gt2bftsezvg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gt2lxamfqyo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gt2jmorfndl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2mpuvgegt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2ozqsgtwp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gt2tsfhlncp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfybjaja.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gt2afrywjcq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2lqnqgqqn.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gt2qfjspttf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gt2kglirrgd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2dqosyupm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2hrqqnpsi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2eswoyknt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jglklpfs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jibqdofg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gt2tcftnezv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gt2jciretfv.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gt2iaxmzlak.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2beayhaao.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymprhltm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2mfdjrkbg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2qohlhlxw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlaaomgl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gt2dpcalego.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gt2kijkuocm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2beeokwwj.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gt2mijaugjr.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2ifjwttdn.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gt2vcedblva.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2nnbfoyld.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdkvjand.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2etibjkyr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gt2byrmtkag.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gt2xzgesvlc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2nolgqfvy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlxxiek.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gt2uymlmlqd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykiyytcs.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2hxialccv.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gt2tdaeqbkh.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqbjdcvh.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gt2amfkvfkn.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gt2pihajyon.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2hebgoqki.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gt2jelysfsn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gt2tflmlmxt.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gt2ixdlowak.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2nhbeclet.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzznsxhe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gt2ydrzcubq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gt2xqpnkwrq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2zkiqpzdl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2vsduebpr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2yvkggkgx.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gt2egyodhyg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2zixgfveh.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2foaaggob.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkmbcisp.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2eiqjmiex.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2egwsdcqh.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2awjgjjfj.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2owfuufho.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amtbdfhl.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avvucsrf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2lkffaimp.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2splicbyo.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2jkbdqyyz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpifbgna.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2eovapnjl.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2uwxvqheq.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nawbcnzv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2dyymvuof.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gt2gcehqmzo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2zivjuyoc.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gt2dxdtqhsy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2qaoljvvs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gt2zcdjghkk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2evehsjli.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2vvwntaur.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gt2tkxspwht.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysfmpccw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gt2nschemcl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gt2jyswhkpn.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gt2trbgzqzd.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gt2pvzwyiac.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gt2nipjclef.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2knqkmzym.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olpgyncy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gt2jitcbjiq.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gt2ykeearpb.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gt2pkdydltt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gt2fnirwlkr.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gt2nlikkhtq.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2qgifyfhp.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lshndvjd.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2yivlnqew.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2smnheatk.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2czntaipy.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2zkydniyq.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gt2pptslsec.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gt2ruwqefkj.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gt2xqxposnv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gt2txgofbid.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2vyvdqppl.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrdwljfb.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2wrciiysl.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gt2tbktyqjc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gt2ceasiecl.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gt2vykbrurq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gt2svyoswzs.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gt2cxjjjqts.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gt2nmdtuyco.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gt2wlbmaogc.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2shorjnsr.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gt2qhyplkyz.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2codfcqgw.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2zunrzssy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gt2najqmlse.html

C#:   static void Main(string[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2ceqvbnxm.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gt2qhgptrnf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gt2blblzfmj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gt2oybapyqu.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iotdfqqf.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gt2mvuxlnmz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gt2qyfdahdh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2jvaghxbv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gt2zpixtnix.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gt2ihnwouug.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2evbrnzfx.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gt2sxzjhfbc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2jykyesbm.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gt2ziycwxza.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2iukuhjmg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrikxmw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2yxshwcyo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2uirahfhw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2ywyghtxf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2ojhyqhcy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gt2pyrfilwg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2didfbthe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gt2phcbwycv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2ngaigpfy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gt2vdvbbwct.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2aebukrji.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iblpccbd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktmzmcix.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2zwpwberh.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gt2ixpviypd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsvblks.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gt2ehejzbpz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gt2zmpcuvtw.html


<!-- 参考信息 -->