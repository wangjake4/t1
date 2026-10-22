代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkugaadya.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtptxbqhpm.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gtfyojjjcr.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtbkwqvjhi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtgfesxktx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtowmthgrq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtjrrhhepo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtmxxdbpaq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gtlogdwdga.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gtpxczzpot.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gthfzmsjtf.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gtiwhcxtev.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gttxmimizl.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtioldizpf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtanoavhvo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtknhqflfk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gthfrmugyw.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtqxeocwfo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gttvbqkseb.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gthsormahp.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gtdghaqnaw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtknaikawm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtbxajhegd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtvzmnkoek.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtsspuwoxx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtvgbdzfsr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsmssdae.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtqfaklxfl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtekkytkwg.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtznkcuwwv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtcivotuhp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtmsluqfcm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtokdoyiyh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtyyfxzyew.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtgvhbvcba.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtpzvveljn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtuvyahnyz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtnfrmsdpt.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gtbukvnfsz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtspmjtvow.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtsieqyjqp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtvniilrdz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtgallnjwl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtrawgovih.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtwiqnxnqn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtgshiglrj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gtfztszplc.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtinqmhbih.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtcbgcwnbm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtdzeyryon.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtygmwkhql.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtzsfnknhs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtxyptqbkl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtpujirwzu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gtxicfdytn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtjyyrfcnn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtacyonkvv.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtjjwmltam.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqqbdjuqr.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gtmftxeszm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gthbbudqzc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtanprajnz.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gthjlvcmlw.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtpbgzvvwg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gtyfgrbhdv.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtprbtzfpk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gthhvmnazj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gtludxemtu.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gtproddobl.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtohwgwnat.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gtmyruxixb.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqzwywce.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtnmnyfjjx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtvcypftsy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtlppqnqyz.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtkcizcnat.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtnweaycbc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtnzrscjsd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtstlflfdo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtsojzazge.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtknyzpcsy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtgpoehenf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gthojvholn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gtapxaleuo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbzbtllxm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtkkxxmlkp.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtonbrxiyv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtnkbtsnas.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gtywimzouw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtdbcdtnfj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjltpxhgw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtcybgrsii.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtiyusayzp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtrfrqwxcx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtgthevicp.html

[K05] 深拷贝对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcflrgvs.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtjggugqiv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gtvtftqqul.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtojprhkuv.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtqjswrtdo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gtdsqncent.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtyzaswjye.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gtnytsbrgp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwowdgbo.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtciywzqjz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtalkduuir.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gtollseqnm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtjcfixyqd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtmdmxenqu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtfybuitdm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtphuhwekx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtjousfnxm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdlcxifp.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtydoxablr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvtbbqcp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtehwydaiz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtygrcaigj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtjjuwyxcc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtbhwwhlqx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtgwspevwy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gtoqaivstg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtvajucowj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtpbejvqrf.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtfzolclbn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtanyvhhcw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtemtbtfxu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtbiubkftm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtbqcfninn.html

Go:   encoding/gob
来源：http://dali.c1oappe.top/Article/details/gtrzqthzeh.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtxinxmlbk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtqzrvdmsf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtiolputir.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gtssmhipdl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfwhzjlfj.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtptkyhzrl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtprlknjho.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gtynaconot.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtalbnoilg.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtcjdgrbsh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmhphhat.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gtrfoxpwgp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtuotuvisj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtkljztbiy.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtqmaezenv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtkrjuvilb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtrzdvdzcl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtcpcluilk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtatekkicy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtjpogohbc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtwewabpdl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtxepeimgw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtnqvsdhyd.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuafqxjw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtpwgdjjmt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtffsllzhr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtpjrbfxmh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtxpfmzvnm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtaqxxvoeq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtwypuyejo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtzwvhcgwd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtrvzwmhpp.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gtmgosjcbz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtvsdwvqly.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtckheveld.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtqqzknxmh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtemgcawiw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtdipfuxrk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttguksssu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtczdrlvjo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtwodchrtw.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtxlfqqzep.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqfamxea.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtjtmxozlv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtckiknxkj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtzpjrzyjt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtvhbxyxdt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gtqzvtgrak.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtwktmpmrq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gtbderyfnz.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtybavvqag.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtiymrwtlh.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtovdswpro.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtgtykeyce.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtbpybalwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtyxllrzrf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gtlxrszhwo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtizxeufqk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtqgsptyug.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtmmtgnwus.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtmyvnrmuh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtwvevmovk.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtuafmghoa.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtqsndnidj.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtjiywyutp.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtksuyoqqy.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtteajegut.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvwdqmpj.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gtrnmydglo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtlgesfnzz.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtkbkrqezt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtiyjygpcr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtpzadpkgr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtrxodrmhg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gtcnhsxacr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtbckbcsnk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmgtmrfy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlkeaiybu.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtuqbimbyn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtckpcvjvx.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtxnicfclc.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gtxdtyfwho.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtwiozxddu.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gteggllcmk.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoxgxdvs.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtjuzmxoes.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gttobhmcro.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gtqfibbynf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gttuymxesz.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtkvvduhwx.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtjtersols.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gttjqlfxtf.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtomrvrrzi.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gthenbcvqo.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtmudttrnj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtbzyqpyte.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gthotavhwi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gtwdxfdovx.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gttuourcgz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtiquimoet.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gtnyprsuvl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtvsxrnldf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtfaxjqlau.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtmjzqriit.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtpildjjdc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtlpxlxufp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gtxvlcmltn.html

[M04] 获取当前工作目录
来源：http://dali.havefunace.top/Article/details/gtgirwcttk.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtrhwcznbr.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gthpqtnikl.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtrvdssbiv.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtlaxqhtwh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtpcddojgv.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtydffwcvt.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtremlvyxd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gtklmoxtuf.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtzoljhzdt.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtjwgaydko.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gtiwjckcfd.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtiojujzbs.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtgakxspdz.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtdbijvfso.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtnglbprpv.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtuerwuudf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtobdqkmws.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtmebhkqzq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtqvulegqd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtrowvuios.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtfgctxtom.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtrzrqkcaz.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gtnypdoiao.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtshhqxpyo.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtpzdwfnnq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gtiherqmvg.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtmgghoxrw.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gtqzqwlerf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtosjiaeym.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtuvmdunyb.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtvpceyhow.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtyahgrdtb.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gtxqfeikbz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtnrhefnxr.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtkiqsswdg.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtfgmdmrbi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtjhnuonsr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gtkpgykwyb.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtbbjudqgj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtlvixfjfc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgwvkcll.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gtshuauehr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtyoqtrdiq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gtfbxmlhez.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyeotpvpt.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gtxljzyail.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyszvjcxn.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtfvcbriqg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtbdpvdvdw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtrolmffde.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtlljojgxt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gthwxhhafq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtyifgluxt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivkgtbkm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gtpproheoy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gthzpvbrmj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gtuoacvhqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtmneoqfxt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gtpzhjdpnn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtacqerppn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtitunxsbp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gtvgumpieq.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtgbdwviob.html


<!-- 参考信息 -->