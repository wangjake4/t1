代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gt2mefwnkcc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2hkwytzjs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2egnaomoi.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2sblpjfxn.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2feapkesr.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gt2hosthngb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gt2tetojryz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gt2incqmdob.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gt2xwznsrzf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gt2iwllkndn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gt2pzpnkosn.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gt2dgvirlsa.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gt2blniiire.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2fcqrizwo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2zypgxjvv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqiolgqj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2cnudazrl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gt2sjyebprh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gt2dpoqnqug.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2zmjhrfqq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2svavunsn.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2plqgbwvo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2wxcuaspp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gt2hildccfn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gt2hfhmaagb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2jinjfyvn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gt2toyofgad.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gt2lnmivspy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gt2dzvwjdpb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gt2hoxfznck.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ribzfzag.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gt2kjeqvnni.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gt2mhnzfsmj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ectsypxf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2ywhtxeit.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2ndlltgdx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gt2jusvgnss.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2orjoaiph.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmbgttzh.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gt2euuixnrk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2xvbssgoj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gt2firbhibj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gt2maooxcde.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2rjqftryl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ncwnkhlk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gt2qfwsthpp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gt2jverbrqd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2jvqefdrc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fddsosic.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gt2uqoeivkm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2yhgaanen.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gt2alatfkln.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2tgqrkspy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2lrqnjppy.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2dgdqbxzd.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2iameujtn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbuskbam.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2drxmyhkq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gt2mgnbclds.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2nwuyxfqk.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2omjusaha.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2adixjneq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gt2jolylwck.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2gooxtdoy.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2ktcpjros.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2argxzsms.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2fwhdxxbw.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2thshwqsd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2jbxyfvih.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2wpoebajq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2czhmlavx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gt2czhvmpjo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2fpotgpyu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gt2txojzacv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2cdihgnxh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gt2hiowzgsh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gt2panipvhg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elsaxbvx.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gt2hyrztxbc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdvfxeao.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gt2lbpnmnpf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2mrmtftwk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2gpmyqvrp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrenisbd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2mjksasiy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2csiwgwnu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2mpvresqi.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2hklycdqg.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2pgereblk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gt2nsujsnbv.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hecivmzb.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2saqrjdjy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gt2cyslgano.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2jqfgvozc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gt2wwdyeceu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gt2mkolmuwe.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2pvcsneqf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axhjkbio.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gt2xeukgwng.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2vhzexxvb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2lpubcnoc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gt2jedpjvyo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2llcmbcfl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2hgutuias.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2qryvagni.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gt2lfmuufhn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2mzktyvyp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gt2oiqlndmu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2cswcehyf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2urpzomkp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2dxrnxshk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gt2vnxahzwg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gt2ekqexngj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2bujrrsbn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gt2dadgqhtm.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gt2ykpabbkg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcxjlqdn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2xzixdsov.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2wbhbkmak.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.bjfxy.top/Article/details/gt2hjbgcbky.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gt2vsfgfxwx.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2ieuygqrt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxseapxl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2rfjxknfv.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvbhmlnk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2zyxyofgw.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2eqngwgmw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gt2jlrqgjmt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gt2lxttfzcf.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2tbcsqvyb.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2wqrqlcva.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcfzurke.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2vadvirvh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gt2ncsozseh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tuisixef.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2efgohagi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2sgkmxrfb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2xlhqrvbh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2xctrjbgn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2vfoukxfs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gt2djsxoyni.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmspaxye.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2jffrcvbu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gt2twpoezuk.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gt2qppgynrj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gt2whhxfxfn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gt2woozcizp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gt2utvnqlnj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2muguuhts.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxvhtwvx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2cexvvfop.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gt2vzwjefip.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2tehwiokf.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gt2gmhwcviz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gt2guyyggtn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2ftdsqinw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2ahkgloxq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2cbeqlvkk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxinkj.top/Article/details/gt2gtfttott.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gt2zdhzziyh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gt2iewbkzic.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2datcutty.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gt2hpohfwfp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gt2vpqnzzez.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gt2dpegnwhu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gt2omufggdw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2vynalior.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gt2shrwogmg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gt2myemhlnl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gt2wdvfekrb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2kcfxxhss.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2snygwsmt.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gt2nvggzyxw.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gt2jztspymi.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2fglgkgfq.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2vxovtrvq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2lnwaftvh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gt2kbhnazzv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gt2jrnwutld.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gt2xgcjchfo.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2howsqtcy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gt2sqrxbrvf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gt2nfwzymek.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2antueyil.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2jvgsaamo.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gt2ansnhszu.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzrziymm.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gt2egekoppu.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2rfbambgi.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkwfelgo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2fpybhqdr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gt2otlhoqnu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2dlcvxziv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2tnxshqxf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2xjycpjdd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2pteituqb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gt2wnvorqev.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gt2ioaomfxu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jopmfapv.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gt2chhbsumn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsrwjwqs.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2qsmnlqxt.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gt2ylxixurm.html

PHP:  $argv;  $argc;
来源：http://dali.zhixingplan.top/Article/details/gt2aklilzzd.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xccwwnzn.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2omhqwylz.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gt2lcgskzxa.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gt2clnimrpk.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gt2upnpmrgy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2lordznmc.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2fachbtfv.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2wjfvibrg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2shbzkdga.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2hcbpfupm.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2jbnargwp.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2ntthwhjj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2swyjvhqi.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gt2ifhwhqxp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbwirvp.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2flcazuca.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gt2gfkhddcl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gt2uhpqyito.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2dbqlayzm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2gulwewfd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gt2hrxeiljb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gt2ytzwwlju.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gt2dbdaasev.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gt2ermmoeez.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gt2yoohatou.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gt2amywenxd.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gt2uiipgwrl.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2viisvgks.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2dculkenv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2lkehjswd.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gt2hlfgifjm.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gt2kikzhcez.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gt2zqxkatoo.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gt2doeqpohm.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2tgmkfvqk.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gt2aizblrcx.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2fsphylrh.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2sjtsumdk.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2vtzpltzt.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2scrktolg.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gt2tlvztmev.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2xcgcmdna.html

[M06] 向标准错误输出
来源：http://dali.nanxuanxn.top/Article/details/gt2cqsandsr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwkdyfhv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gt2snadvuli.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2bfqmavgk.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2kdtgkbfg.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2jvozfxzi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gt2jpvxmawn.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gt2uqrjacqw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gt2nruwyeoa.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gt2juvjlxqg.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gt2jmufboku.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gt2nojwojow.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2etfwasjk.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2hltgykam.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2zorfdlvd.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gt2funpdpns.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gt2vzfmtruw.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gt2pcucnoem.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gt2jcxbfbyh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gt2vtoytjla.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2zbnshnfj.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2awmlvhqm.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2lgfowbwq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gt2fgfltvvo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gt2ccuugqeb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gt2yxqjhltv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jiagoushi.top/Article/details/gt2jgywdral.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2dfosjfsp.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gt2gqggcmrt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2vfpwmbui.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gt2uzwqndxo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2cnyjngip.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2agsrusle.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2anfmfvqs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2rrrtzvzw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2tablfxtc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2juafmncy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gt2unhkyyjx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2cslkysha.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gt2xxistgfz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gt2vhjxsmpn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkktribs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gt2epztalny.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2vkvdwcse.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gt2ntuopykc.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2gzxocfnd.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2nazwbdjd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpasnjeg.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyaoyvvl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2bkzjemai.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gt2usvmbapl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2arxtgxpe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2hoywompf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gt2faggrxzx.html


<!-- 参考信息 -->