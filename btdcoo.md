代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtddmllukj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtqlmopfci.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtknybkfqk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtfonyirjr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtjaojwvbs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtwvxmbqsb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtgqgcjwsu.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gtdxciaasc.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtvobozlib.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gthuiavfen.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gttbwlgzdq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtamulxwnx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtvqtrishq.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtealxemdx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gtmknasnkc.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtfiqmgwtx.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqvjgwvg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gticpejrzb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gtnnrtvpsn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtwmnjqvzk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtobssswxc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtzsgdlwlx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtpmahfxsu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtzligagsm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtvajptryu.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gticrtclfc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtscttkumm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfhgmfcu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gtokejeycw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnygmihsb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtkwtekatz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtzlpnohrc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtpajiwtng.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtnupznuow.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtwyketdzr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkvdwlxd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtmvrryote.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtdpunmcnw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtnrcklwni.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtavjzsyhb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gttiwtamnf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gtayjxpyrz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtvpcrplip.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtshzbtznv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtwbufgbbq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtewmicnsx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtdlcjevgf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtukjncqhv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrstdkivw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtrhfvzxrt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtnstggdwu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscpoelbe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtrukhsnku.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtkvvuwujx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpdvawopt.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtlpbjgxnf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtlbcziilp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtvmjrhlpm.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtibnzzors.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtgccmfhqa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtugxxdyqz.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtzteuucay.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gtaohntqtd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gthmzxbldm.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gtotlrqtvk.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gtjgncxnsv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gtbtplxnot.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtikernbbb.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtzfhdoinj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtqyztiygw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcialiplm.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtloxwlkzn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gttedeegwg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gtxbmmylkn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtdyjhdizh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gthqxgsaia.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtevxphxve.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtxkhcorvr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gttvrxbqsp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtwcgubawq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtrismxcyx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gttfixhckf.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gtndignyfh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtnnyzfeey.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtkgvfjcpg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtjcjqtrmn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtvvkhavtm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gteypfipvl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtrijjxfsg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtevtjtfkd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtyuzyvqod.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gtewlowvqu.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtzpwhvfrv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtiyrcfhsu.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwjmjskp.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtdmigxbca.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtuesexsoy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtmxjalfsp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtiuinxuea.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gtjtfqltea.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gtswcgruuk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtvmjpcaqd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gtrjxnajfn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtxsokoyjf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtknzdvhvb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtscwuribb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtcvzujvqh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtcsajduvs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtrxladbps.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtefxpshxb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtwqujkofz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtjmaaoaon.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtrbhewtgz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtrxwdyles.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtyapcyvnd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtnilaqmla.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtpkmpdvaa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtwkqxgoqv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikwlnxtk.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtzksbgpts.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gttaqvectd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gttbchzzfn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtgojmwevn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtbnqaofxj.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gtextxrlwo.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gtcuriarzd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtbfzmzzir.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjjeipewd.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gttntfpcxw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtywwvkhqt.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gthhkpzury.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtgijvndyz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtjwsxpxrd.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtwnrgrtal.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtgxhuggjv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtljqrngyl.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gtmpcotvjs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtqfhnkuuc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtwtnpqjdj.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzogwyjs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtystljxak.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtwhjbtzbo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtrzzrgxfg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtpctkewic.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtngynyala.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjperdxkw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusywgqzm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtxapupgoe.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gtixfewfyk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gtshkzljrc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtohktyzoy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtwydkifgt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtuaubcthk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtxhgbsvxn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtuuzvbtzn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtjwckggst.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtmensscqh.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gtinyiwuiz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gtstucqhfc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtknftbbdc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtfgbxkmqr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gttujlceyz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yangfankeji.com/Article/details/gtsgzctddo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtaehbsvyl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtfwgejmjz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtqibobtek.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gtjeuhjuwa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtbyurqxgw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpakhsjzm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtyxwydnxv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtjoxjbcfc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gtmunmbwoc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtfwnvcefc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gtncevalmh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gttiezacsr.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtakfrakgt.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gthoxgsdiy.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtxzwtyety.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtplrrlznv.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtjgvjqkzb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxawqzbr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtxyhoqmin.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtfswlmfdc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtvutpgxbd.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtxyxzphfr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gtgzwekjdu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gttlppbtnz.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtnogwoaul.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtwnyqagig.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjufycred.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtbfjelxsw.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtfmpqodpg.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gthszbpdiw.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpebunkj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtnmabaxbq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtcmfsvkuo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtzjebtkyv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtrxbsdnhp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gteburwzro.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtaegjkfpw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhytyknq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gttdjidhgw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkpjnmpip.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtmuhlpefh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdzeufcke.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtcftslfnr.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtzmpqkkad.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwxxagoi.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtzybkqcec.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtjnjdyyyv.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtzsrhwgda.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtrewhlloo.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gtcrargimi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtnvjmndxd.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtuqtkgsmq.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gthanfxhfm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtwjjmcaaq.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtqtxrqilk.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gttetguern.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtefvdsenk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtbjhortzz.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtkdfwoyog.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtbfyjfvyh.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gtadvzfggs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtgsbhrrci.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtjammumzt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtxksajctt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtpyvwfqki.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtvivfgyla.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtldjoslii.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtobivdjrr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtdtwflceo.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtiofaamcv.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gtynixqmmu.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gthcouglqt.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtzgiejvky.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztfgdjvo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gtzhlskzzo.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtpdhprmkw.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtjgzldwqk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gtmdgccics.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtcuxizika.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnhydylt.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtuujjohld.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gthsjybqkb.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtylovmoqb.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtwilfhrdy.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtflsectgw.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtlbrnmlkb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtbuuwetys.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtoqbrncqi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtgnnalwkj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtqiukiule.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtbzwtdyfi.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtsortkyxu.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddmwwjsk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gtjvcvzdgq.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtobdhvzxk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtwebtabtx.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gtptvfudah.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtydkgbydk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtyusnkvgn.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtkzyuspas.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtifkafozy.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gtntlunhtg.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gtqjacuynt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gttsczeuht.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtxwolcafb.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtlnmtvjro.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gttwosyfqq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gtqbcwpsew.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtychdvuxf.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gteexdtfvf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtvsxequov.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtmjnywsqc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapfrlbvp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gtrqlbvorw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzgvdzyrv.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gtihltnwoq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnanulxno.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtpynztwgt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtnxtnwzun.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtpbnztqpx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtzngiaehq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtjsrlftpk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtxrnhrkai.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtkdqflwtg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gtbruorokr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtqewiojph.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtdssmhsfz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtynpxxoxv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdyhjryb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtrfmkvqql.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtqhlujjrm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gtebhxzojk.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtwjgvnrsw.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtjyrapcmv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtepfogjpi.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtxipefhdk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtklvacibo.html


<!-- 参考信息 -->