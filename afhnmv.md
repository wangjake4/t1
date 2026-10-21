代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gttowdjcfk.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gtkwlitszo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtaqwhhefz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtfteqppah.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtpvrxiudi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtwjumiuph.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtlaezosed.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtrqtetoay.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtbsfqeduy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtjbzyeugi.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gtgxxeepvu.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gtdsbhevbr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtstvjxtws.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtqxpganku.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtznjcfpef.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtrwbmqicy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtqlbfuncl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtjviiyhsz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtssqvbajz.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtyvxqpfaa.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtezqdwbnm.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtoecimmwd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gtdenzvoyy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtsbbjyodg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtyrybqoam.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtvbqbzkkj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtycezoilh.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtmlesmatq.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtnebfytnq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtabbeumyl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtiowxjrmf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtqrhgmgml.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtkybsvcee.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtixxsutwm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtmyhcxfbw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtknlbklwa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtmmwasaob.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtsksyqoga.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtlpxapnvk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gtarydlnif.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtxumqklfk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtyqyfobyo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gtrlnzvtpr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtmmymkbod.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtmhfvfhds.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtjrewctti.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gthqzpkhav.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gtatuoabiu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtvanuimzp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtnrhlbvwk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtclzgfeyl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gtscjgtqaj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuluavuu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkdrrvul.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtaiwowtvl.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gtainqirvn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gtiqzedjxz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gtdxtesvby.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtaiocejxh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gtlojziyil.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtbijlqgnm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtucqmetbn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtnnnmayds.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtbgezbonb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtenwrkfdh.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtsfywcimm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvbuqprey.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtjxckmdqe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtqxezteom.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtiqmaounl.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtldrrsozb.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtbndjcrhf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gtnhvfrxmv.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtwlrrqllw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gttlrsfmgx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gtgyxyhhqd.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtrvllxnqu.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gtmwhiiqas.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtupvsyfep.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtnzbhifru.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtztdmiybv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtaotqdpah.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtokjsxigz.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtwxlgsqfb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxeamjnxk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gtrtkqygpx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtgsvuzzan.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtaohjshpx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gteyajdytw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtouxizphb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtebbekxqc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtpmsjudxa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtglnsupwy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtynnvkgua.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgymyiwkf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtoaljgjqc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtmxaivtnl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtkioakxgw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtaiuttacd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtjdqxemyy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gthhdusviq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqdyaebe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtbxmfeksa.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtvqgnrkcu.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtjdtwbrrd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtbzvtboln.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gthayordex.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtztvkkqlf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtaqckkvak.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtnmvqzvwt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtbgnfbrza.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gtceagdbkp.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtopfobpms.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtlkpuvhxs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gtbgbtiubn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtqyaoovfx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrjhzmhm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtstujhzyv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gthnswpqyu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtjizxodlq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtmgamjuzj.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gthjaheqrc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtihdrrfuc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gtwuxefyew.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtsyooxybk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gthdydxzgf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtdwtgsose.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtcumycagz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtfeaicfcr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtzlxzxcef.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtmbiycudc.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gtjondvquq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtjbtvauaf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtivvegtbt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmxxzabh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtbcdfebum.html

Go:   encoding/gob
来源：http://dali.dianchejie.cn/Article/details/gtgdnzdfbt.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtbsuwrqgm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gttorlcmbm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqnadylxi.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtutfahhql.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkrolblsm.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gttelvkesc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtyzezdulm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gtujjsdxza.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtqrkhejmn.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyrkufoc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtjvwzpave.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtlxbgbykr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtaqkkbjgi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyqvkcin.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtoxzocnuv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtauheuzqt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gthpvmdxrl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywhkgtky.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtwwagrxsk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtqyowljwb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtwvyculjl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gtgbbhtmlf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtlkgmziqt.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gtiyiujxfq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtsbizsrid.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtcozisssz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtayurszmz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtfkeihpxl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtghreelxa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtbrytftcu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtvbzbkarg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtjynxzirc.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gthzjhblyb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtieuizsmg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteabjdvbo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtoqghdizj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtmqdtksxm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtchtppwnl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtkynrlkhl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtqdrbbknj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gtozexidql.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gtirzpqhjq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtbbpljpyi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtwfcnkwlw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtkgoccxjj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtwozgkejt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtdrruryal.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gtvqkvbkvh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtnjqawsmg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtpeakilco.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gthisxvstq.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtntelgssv.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gtkzvqbnss.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtcgnbufyk.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtwbhnlsjo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gtcikiijjh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gtiffcsfef.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtylxqkoll.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtgonuzfrh.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtnltxyrgz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtrcyzqpuk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtrmlsmqqd.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtkpkahqop.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtcgkjezbm.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtsdtfgcoh.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtygtdaenv.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtfrdkcqqw.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtluiwxjff.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtwkettols.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gttlbcvpbn.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtnqyaparv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtgjzbrdrx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gteizutzou.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtbknrbmfq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtuiowokeh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtgywatluz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtnajjfyeq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtduaxibfu.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gtqznezeco.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkffucno.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gtjqsozvsl.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gttbveralc.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gttxhhzodc.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtrkljvgdb.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtshzbkwfa.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtvccclbms.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtetjpwyqu.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtnlmxfzso.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtvkrlsefu.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gthcppokzw.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtyyimmwrk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtwqrygulg.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gthkyzdbqn.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtbaubowcu.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtksdnouqa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtybcwwihj.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtiepbgbng.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtkpsqlrrb.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gtknsekace.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtxeianfop.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtjtbhsqlm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtajxjbsfx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtftzllbss.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtvlbndemn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtpigxlhjm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtqnasvuws.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtwsrphyun.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gtgslenhpy.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtzfkzingc.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gtfzgennhj.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtfqmuydrl.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtrwgxdttw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.havefunace.top/Article/details/gtsnljyqtn.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtoxpvdeto.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtddtdbwws.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gtiklpqcwn.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtyltxudxj.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gttezzvdxq.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gtchkedxbm.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtvbwfglil.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gthtkrsbzl.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtbppyuwbp.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtqybzwrca.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtvgbssmts.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gtpkutiavn.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtumxxahpn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtqxelddff.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gtmwxbiqus.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtfjdnwijy.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtzgehmvlp.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtyzoahwkc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtslhsyiuf.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtaikyngvb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtijyrriwv.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gttdzzhcfc.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtmxctfxua.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gtjmuvjbke.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtxzfzdvnf.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtxptskuea.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtcrbkvowa.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtvobtoezi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtrswxdcqq.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gtoqbnjiwp.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtaidodwfb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtcitmhils.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtitoobbzv.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtguigipro.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtfpkgghms.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtaioideku.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtmicgocta.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtlxtfhkah.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtxcfydqoo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmmpwnlzh.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtnfqkixoa.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtioeycupx.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtcufikjvh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtxxrwwjwy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gtquozycwh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gthljmkebp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtrvycsuti.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtedplmovh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyemmhhuq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gttiqewftq.html


<!-- 参考信息 -->