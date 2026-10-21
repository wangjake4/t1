代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtqqxnumxg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtaqmcukpn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gtbazfcfxb.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gthtnglklq.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtfkjcnhhk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtmbfwwijg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtlqwagyrv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtdijrrnnl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtpilhfxih.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtjfbnaokj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtfijrcloy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtkcrxcebi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtynxmpgob.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gttvdxiwst.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtihmoixut.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtxqxobvmc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gtwhvshplb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtfwqdjpzt.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtnpybxohn.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gtfxgznrzw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gthuqljqcq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtihtpwola.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtgfmdofok.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtclkxdulc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtdmrzqapk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtfcbihfam.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gtmiijzyom.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtudqkhwbm.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtoaotxyof.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtprysrtuy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtdeueypru.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gtzrzugoku.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gtptdjmlyw.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgddlkryl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gtvvwshggi.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtiuhthzco.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtzpsdsomt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtsxmvwpsj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gttrelzavq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtwznaefbc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtxbrnddya.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gtjeqnqmbp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtwjiuvowp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gthbijuiya.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtgvcsfhhg.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtaiiypldw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtibtywpte.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtzsthlsis.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtyubpjvuz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gthajpvvym.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtobvncvwj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtbyyvqdnk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtagtxjcwp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtyyqdtzvk.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtxxilirsj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtbibzehid.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtvoibmwpw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtlqycruys.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmhiztip.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtwlwtxnqc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtydmqadjm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtczleakuv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gtwmhgnqdv.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtfutpfyjs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtavezdypq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtrltiewgd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtuhjdtdvx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtvfeketov.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gtousdkxvm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gtyfrclosw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtntpjtlrn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtqhowggci.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttfxfbxha.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtehxaxhas.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtoyoddhcu.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gtsfheeziu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojwyloeo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtdsfiznat.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtprdykezf.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtseisfeme.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtisxfgtah.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtbtqmufee.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtytfkbkds.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtpjhlvdbq.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gttxzucgcw.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtrldfureh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtzrtvvayp.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtqockzbzu.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtwwswnowy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtiobncwpq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtbnapojah.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtzdvnya.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxkkmqfat.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtrybpbtzr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtvbiwjndt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtfofuudsi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtxneiitsl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtdnuetcdh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkrkizot.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gtnpdomxsn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtuwvwezss.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtxunvcnlt.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtvtozuump.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtiwjjqjbk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtyvnkgild.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtqnmkwhdw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gttrddhmbd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtaztoaffd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtclboovxq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtnmxuewnq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtjiktbffv.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gtyuxuqttq.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtmabogffr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtrdjqwrwa.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtxbnyfcut.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtmbzwnwfi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbhxmamu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtuqfwfnnw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtgtgguwzx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtyrujkkde.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtnalaliet.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtwrlcboos.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gtscvuapby.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtpuakamxj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtbhhnyacu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gtwyelduga.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtbjguxhbc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtghrohplm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtfsvqolgo.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtdpsrutoz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtklnzaatj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtaliqzzvt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtfrullcch.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtangqciii.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtjbzamvgg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gtpugyrxiz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtuefxxgyy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gtozeiapey.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gttzisgiem.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtzeyhztrv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtrboidkfe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtjwqlhhit.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtrzhofeii.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtatckarjw.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtqramhamt.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtxzdbfalp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtsbtwfwmq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtatxdneqy.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtnlarljpk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtagqzgmts.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gtbmceamsm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gthvvpcweb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gtaeqpomwp.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtesagkkxs.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtdyebchbt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gtqwccixta.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gtpbdbymbc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtkezogpae.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gtejddslvg.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtjghioocm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtnxtqstkb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtonrnfztr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtkzgapsvy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtztimoujv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gtkncspagp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsijholnq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtbpeekrau.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteshystn.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gturududkx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gtgzhajupl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtsnfazmsy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gteranvcob.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtuzyfdbtn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtpyffflue.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtasczrvzk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtebzmeuxv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtwithvjcf.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtkfugzsla.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtwcwlsdll.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtgvjmio.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtjxlnzdfn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtredjxabz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtjfpocfpu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtxzfadlkw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtbqgmythe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtmlwqnvjs.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtpaeqxnel.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtinncbffl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gtnfiowsjl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtekhboqjw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtrerxulil.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtldiqkebm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbsdqyua.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtcbfdknob.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtlziqbdwz.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtpwsluekp.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtzfrqnpzd.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtfqnwiosg.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gteldinoxq.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gttcmuwikb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtgbpgjvup.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtcbcuyohw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtnxnvakoh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtbedijgca.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gthkfmoiay.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gthijqofyy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtrkktrfbf.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtzhsvtssz.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtprlowqwz.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtirvnwgqi.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtrbqdamox.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gthembtldm.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtkczsvakf.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtywtszgsb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtvtbwykmp.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtkzaktuom.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtxsscenfw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtikaoifsu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtbhtecwyo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtfuezpqtj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtuaucquzu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gtcvcstded.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtebnzzhpx.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtugbenkzs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcqaklonc.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtldwhgsfg.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtmfkcvvbr.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwtcbsuh.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjtqavcq.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtfwlousgs.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtutpemtph.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gttszbmhlx.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtxnkhisyi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gteszpeloi.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtvyvollgg.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtzdsvztfx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtzecaerfk.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtuiijnmgg.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtjrqgjzzg.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtlfzgxvro.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtsavamjnd.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtpgmbeuoh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtesugvhzb.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtfsmpqsal.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtaigfehfv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtshtxikkc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqchmroa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtnvyfftjw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtgbgvwyve.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtdmhlykel.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtjqqjjgsp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtndoourit.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtfvfqvcmt.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtksjqnerp.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtebyonyzj.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtaoxqxkps.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtzwebyusk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtmpkwwhoa.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gtszhaeuww.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtazqxlxfw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtprvuzcdk.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtnpxqezmu.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtrpwajyvh.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gtyuaubjod.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtbymyifeq.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtinolpxqw.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtagvhqxdg.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtexvogamy.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrqlzhqd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gtbdbxropi.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gtlqwhhyrq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtknbhlyvh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gtlncegyxf.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtumlhqdfg.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtymmrimts.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtachrghwv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtxeusygjr.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtgajmqnya.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtfoqkvcaw.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtlffdwnqc.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtgatgvggx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gtgksyurvc.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtwmhxmlug.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtcuwkqocn.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtkwdssjuk.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtoprtracu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gtcdijjwck.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjwqwmoj.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtpnnfmaom.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtnaximvca.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gtqwhyntla.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gthdcyntqr.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtkjycssrf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtuctxyyty.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtztbkfdva.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtuujnhjnp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtpkriragj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzzyfkjfo.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtwmdrmwnx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsjntshhh.html


<!-- 参考信息 -->