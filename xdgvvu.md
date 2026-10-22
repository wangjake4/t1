代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtfooeyqai.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtroyuumid.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtipdkldnz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtvnklaien.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gtxnvqliay.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtvmdevosu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtusduiv.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtddeqbwwp.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gthrhunwlo.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtiwqhqogb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtrryrwrji.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtwnsmxdev.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtgotkedfm.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtqsngaoxq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gtcmxepwrv.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gthwtntuvj.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtpdlbpwhp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtebldqzku.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtluvrmkpw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtddknmkre.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpimoezlx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gttlkjrimo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtqzeobvcz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtckopunua.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtqffwraas.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtfradhiwv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtbijsllsi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtbqjgneyz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gtqbxzqdtx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbxpoffp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gttxsthqvf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gtxdmotfgg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtefxnwfwc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtsjikyczg.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gtadapatkl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtcsadhate.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtdtczwgap.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtfpztmogx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygibahdb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtqicztkaw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gtgvwhumhp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtpebwravr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtzqthncyi.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtlghsqtjo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtdpigocsh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtcicgcsrl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtgwpyiegr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtjbmbbffs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gtuhwnrmis.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtfyzakecg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtdmhqmuel.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gtppfmjozi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxyocwqxa.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtfyuxgrtd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgmiloxz.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtmftwymth.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtipageygs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtdjnoizef.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtgrcxefls.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvnymaqtm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtmfoknrum.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtnufjztfp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtppqixjff.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gthvvizynw.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtrwvuqqgw.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gthdhaohse.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtyuemgulz.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtiuligsbt.html

TS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtbbzeisct.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtosejqsbz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtavblpctw.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtalifsbxj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnbtxsel.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gttaktjoqn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtputdtqfz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gthpzknlxg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtsstzwpwo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtmuklukec.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxgkmexha.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtfwadtqxs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtresrsitb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtbpdzjdmj.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtplercpsp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtdntdgxjf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtzwssqgrf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtiyxhgdro.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamxlswpy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtlyhcmowv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtsocnazuz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtohfvdfis.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gtdofjjsnr.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtzdzsfujq.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gteyamunrk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtoagoiruc.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtkgttqfcp.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtsokqtikp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtmyxrooxz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gtoqoekyjl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbdszhwk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtswepvoon.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtvjbalrxu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtizmxitcu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gtbarunlup.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtvlhntrsw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtjghgtcws.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gtoiiabhvp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtvsiajfrs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gttmgwiyxo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtslltjope.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gtfrpybwkv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccmperfy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtntcltsre.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtuqutdmdv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtgbybhcof.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtivthzyci.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gtjrscceho.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtetnzrzmk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtlkxeivgc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gtxbxbvorq.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtfmliqfhv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtcaziuxwd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtfqiexpjr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtmjdxkcyv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gtukcoepdv.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gtqkgzprmk.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gtjviyeszy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtyexsstrs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtinznhpvn.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtfvikmqan.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttbnmnnoa.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtasjfxzyr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gtjjjkgrwy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtpmitvnxj.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtelkioldl.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gteatoqvzb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gtzocrlctn.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gtwiaynedv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtnyidsvzf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtvponsuxy.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtpcouuvdh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtlucggjnw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gtpbyftmyb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtunahwvfp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwttdhyzi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtujyhqqzi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtkovfeutt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtvfgtukzf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gtesoryjdz.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtgyixotzg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtzmdexgcf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtufrvgatm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtfwpbuamq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxqtnzvt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gtxahhwdtc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtsehqjakh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gthifbibdc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtatbanqak.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtfmniuxwa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtprdelnwz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yongpay.top/Article/details/gtgpyuqicg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtunmnyolb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtkqnkiket.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtyaihurbf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtyddjbzhn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtqampglbn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtmsrmcwnn.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gtbrjscsuu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtlmbwodvu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtoxsekkht.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtxdxwnjkj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gttumrrprs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gtfywvkxfb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtbgtmdcvx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtrugaaflt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gtdszqljnt.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gtmdtyevxt.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtawxwqooy.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gtlrxovkwz.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtyrsueqjm.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtdpwovxia.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtyzhjrhsv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtngrrtiaq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmxvgqac.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gtzhsaemlo.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtohjvkhdx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtcyjhsfvz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtnqnzlfsj.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtafhuycgn.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtgortrdjg.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtbqbwanra.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtnfupojwo.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtgqbqveyc.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtzdotfyak.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtehrcqpxh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcygouqay.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtrtsvneva.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtxesusdkk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtejpueqhx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtvstdkypa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gtunwgllrm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtxjigdnss.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gtyqxqnzyo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtagywuclp.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtmaxixclw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlpfdntmo.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtflskmxvk.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtudknfybz.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtvhdyidhu.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtplscrmny.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtozdskxvm.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtqyguvyue.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gtvwlckucj.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtttazdztd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtahzzbotw.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtlcxizmyd.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtkzyacfji.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtcarizfsd.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtxraxtnzi.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtozuuxofm.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtibumqhck.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtlnkhxrkb.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gtvmagwqzm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtfsbaoeex.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtcqwadatl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gtbvxjxhrh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gtzmcnpmio.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtqjpwaomd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtmxihfftp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtocycnlnl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtcgayrgju.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtdupfgkby.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gtsvbrsuoc.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtzyyyqkpq.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gturuihahr.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtvipoosjt.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtnoiwmxbg.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtlogqfgqd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gtnitjjqst.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtahihkdfy.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gthesmnycr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtqxgwmuub.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtttqnluuw.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtkxxjfoms.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlqgztsf.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtenrniloi.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtobvxdsqf.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtybazlvhg.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtaligvyte.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gtnwptokte.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtpptydusr.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtadycflms.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrsicbil.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtbxplekxo.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtnggfotql.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gthrnzjucj.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtxrcgxwbi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtyfnkhezx.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtenjwfxpp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtiodfwrbg.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtgiuagrtb.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtvnkiiggw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gtgpvgpoxe.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtluzcnymq.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtzcxvcdbk.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtpwqiqugl.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gtzassgzjc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtioqwvhzq.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtzzodszmx.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtuiycvaqn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtwbbxhcmd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gtmvbrfvph.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtjfvjbtlr.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtelqbbuqt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gtfzigotux.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gtaqhjxyke.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gtvzakffbh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmanbmjrr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkqtqcxul.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtwtastlad.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkpquyhad.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtpqxwtgay.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtgeqixdvo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhnwekzi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjtoiwjm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtsqluixhx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtcakqwoeg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtjkryngzs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtcfwvilfa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtejdsvjjo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtvcdfnlqw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gteqqqgutx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gteyimhspx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtojwzjqau.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuzmrcdg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gtqseqzarj.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtxlaavmaa.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtshaovviw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gtzuvcqlru.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gtperssugm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtivewtoto.html


<!-- 参考信息 -->