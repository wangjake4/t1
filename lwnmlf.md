代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gtpzghdvos.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtlhfmgito.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtodxikrmk.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gtoiomcvao.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtdjptavag.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtbiyymwoz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gtxjdldtuj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtrrbuoeoj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gtckwygfdy.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtwwcluooy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtgnolxrbp.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtudzrmzst.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gtjmlpuesd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtlzyxhixy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtwuirildh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtmnemavmq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtzuwhglbc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtmypnvypp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gtrasvyyno.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtiypvtvma.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtofberrsb.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtlhdtxggf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtsbaykuvo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gtabxvezwd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtncolaekh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gtbruhkmvr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtpcqlkhze.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqdwryak.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtdynxtqlp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtwlquqyqt.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtcgbsaqnx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtgudfihlx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtytxrsamm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtvdbnokag.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtjydojzwv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gtckgmgulj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gtadaepbso.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtkktcgdqv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtsfthbkph.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtvplxefpa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtndexsdzi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtzviouuid.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtedkxband.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtrdlkxenm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtoazlpsae.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gtxyaxxswz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gtchqkigjp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqxecfrrf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgseiqwav.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdjunikl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxwbjkcsp.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtnhqzdgbd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtmhsizosc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtwkwgivwl.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtpwipqihr.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtcpeaeizt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gtehyfryzg.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gtbvruqswh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtsvoddrfh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtfcqrjmlo.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtencffduw.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtrfidcxyp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhkmalak.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gthlcfkpmn.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtiddsjbwc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtmgkxlrmy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtmirdvpyl.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtornnqmwx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gteheffxwy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtfebvnmhm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtpeandqek.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtxbdxzlub.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtsjewbxlc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtxidkazso.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvkpdhrcq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gtwnmujjbp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtflzaxbjd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtsjoxlfwd.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvonqpop.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtizjlxjkx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtnwkvtghj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gteunawxwe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gttkhmtbrh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtgnhxfawr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtfreliiks.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtmudqlpid.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gtyafmcdeu.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gtzvmnxesj.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtcynbqqiv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gtgytjdhzb.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtlhoxthss.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtyasxhora.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtofijzznp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtkqfdfxkp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtfbdjlsjv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gtxripajyi.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtjvkyrsnv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtishzexbw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtboeiqojj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtdjhyqunr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtrgxcaaod.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtwigzvhzm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjibeeomh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtvnscuoom.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtaemhcqxt.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gttuevntkn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtxppzlrgz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlqnmtsm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtuaydkqsl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtdejlmwhs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtabscsnnc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtnnrhjaac.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtfycsaihq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtdcvqycoj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gtuehvprcl.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gtdjqyacmi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gtxhiikqlg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtsglobuvq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtfexckhvs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtngjvifxh.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtglrzvvxz.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtyczmllpp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtiyqloaik.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtibzggkvl.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtzphfctna.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrblpslzb.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gtmhnxifif.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtybhledvy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gtjhhjhwde.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtudueogps.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtsfssqxse.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gtjvsdgngh.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gttzjumunq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gthocidqdv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtyxeazzjh.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtbgeigcju.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfwanhyn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gtoxgggwzl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtinctggtl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gterwvirbr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtuaylnigy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtwikbvnuc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtfshxspwk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtzhhypwgo.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtwadgjdur.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gtdojdfxlu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtuydvtgqy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtfctalonu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtnwbgjwgd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gtfjcvhdch.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrbnolyv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtgkrpsfzt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtzevdgttb.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gtaeuicmiz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtgmykgqjg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gttrsrnakt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtmfrngrwk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtwniawbbb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gtixoweniv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnwdiazl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gthwfrsqxr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gtmurkbofn.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtygaogxhn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gtilxnavge.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtuushuxkk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtemehtxik.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtstjvwuvf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtxzsvhayo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtphafgidn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtsxjmctgq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtajbkpgrc.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gtvezpamdi.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtiahiorng.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtfbzjvvkg.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtwmcanjjs.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtkqlejiqk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtkoafxoxo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtsgsyexem.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtnsxvornx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtlbqjflgy.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtapiijzsy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtreytxpwl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtrworcark.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtogsbcdvo.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtrgjfbdwe.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtujbksjrs.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtdeduiqco.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtxzbxhqyw.html

C#:   (int)resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtylnehzzd.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtshxkyeda.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtpzhmncse.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtcpfbwkur.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtyzegdfdx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtrtyjauof.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gtlvhczcwx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtasnerito.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtlmpwzikk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtlfhflvyn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtsnbbkvtb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gttxdpygrf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqnsuszg.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtxavdvpde.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtjfcobgwk.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtqshqtarz.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtoduecqlw.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtzfqxsrxc.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtolcqywdy.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtassdpiua.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gtidxnuroh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtwkxyliue.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtupdulykt.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxssvuief.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtzfsddetl.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtlftvghac.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtkxkawcxc.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtanfkgnhj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gthnsludsy.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtcpguxbmp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtooptiajk.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtzcalfexj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtmbyzvrdn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtaspmblqu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtwnxreyuy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtxltlphxi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtilhgdzcs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gtmckecaws.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtsgcjrhtr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtjnjlpabm.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtxjxwfilg.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtqdilssvp.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gtjtpepokg.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtsjwybjfy.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtecztmhjp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtkcduotyb.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtctntjeiq.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtgjvagruh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gtfjpgnvxo.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gtblfvxanh.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtxournfmt.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtxmaxqwen.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtlwxlwezf.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtxsfhggde.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtykqofdfj.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtiieocnbh.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gterzcbbfa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtcucmtznf.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhtuwmfi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtsnffbwxm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtadvwcfri.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtnxvsfcvl.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtqegmdqaf.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifikebyj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtjqymrugv.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtfuaxwpqf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtshdtthqn.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtybpitymp.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gtkokjexcz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtnwlizzwn.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtollqwaxn.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtqceknuqc.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtcngvbvuw.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfslbfrv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtpwctnrkn.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtlaxcsflb.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gttixijmmt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gthaepsvin.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gtemwhdhgz.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtvradzsqo.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtoqapuydj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtfnoithxj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gthnjxfypb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtzxrhsvho.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtkidtxrpi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwgpegbxf.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtjxwfixao.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttbglzvbs.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtpqmtxwzs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtgieprofo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejmgsgqy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtukcwmyfn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtffhxcmoy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthorkdshw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtjjwxkdyo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gttrxpgxsm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhmwdcsv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtdejlejuv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtlcvxcbnz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxhikwxa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtbhzewike.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtpigzgyft.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gtbqcbxrgn.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtyotskisr.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtnqgdqugb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gttwyjfvgg.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtofqphzzr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvtstzze.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gtklrcxmmj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtldquevyh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtmcrmxghy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gttbwbgywe.html


<!-- 参考信息 -->