代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtimitfzvf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtqxqgypcy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtxjnonhpi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtsfttzduz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtopdmzvle.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtyhfpxsgm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtlomunwek.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gtfpzdhqkg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtyurlccsg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtijbzlavy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtwcoppiyu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtuxbiivhm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccttrsjo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtspybplcv.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gttpirvwar.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtgyhloacm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtrfnrewmz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtshctkzkg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtzdtmmtuw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gthjeulbsi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtpfbxtodo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtgphdgnyq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gthdbfbduz.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtnuywpeeq.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gtlcwyqhjp.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtqhyqaucm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtfpresltv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtpkvnxpwj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtbvyuzfgl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvmumvqv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtfwvtdwcc.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtrnqlqepm.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gtadanvxsq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtyrgwmpdo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtimzknbsz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtxwpdkecs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtllnzuzxl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtoyuytqed.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtvxyciqnj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtadnoahxp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtdbpafesl.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gtchukgaov.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtffqtaroo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtijhygzzb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gtenwdslup.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtiujqijig.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtqkbrgwbk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtsegzuelv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtdupiijlg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtzdafefmv.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtdvorsbnu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtkjppsjft.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gttuvrehdr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtmlneyvsz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtquefcndc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtdqbpvvxg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gtzpvufmmu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtxkvpeyoq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtazggyeko.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtctktxvdd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtngeomwnx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfbieufx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gtivqlflwe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gtqrvfktmh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtfckxdvgu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtdhfmmenz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtmxeoqvad.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtdjsphowu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjyscexvo.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtpbzwacpe.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxoupciuc.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtupbjdyzt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqbdnkbp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtwichccus.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtnwcxnceq.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gthbxlevzv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtjxsivobn.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gteryvaeyd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtvlsupopr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gtqmwoltqo.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gtcwjwkjuk.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtwkrsadnm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtkvlzkgcc.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtsassylmy.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtjlvvgrtw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtwzzzdcih.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtsvltjzjq.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtcchouiqw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gtuzgxjnbd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtobgzwtwz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtdnmdowex.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtymhccspr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtxbgpbifz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gteukhpwcd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozpinxlb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtqvwwgmel.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtzkbcfmie.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtbryyagko.html

[K04] 读取 JSON 文件
来源：http://dali.redwolf501.top/Article/details/gtrrozofdn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtnjvuzyds.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtwdlkwyad.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtpwioaonl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtrucnvwnz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtjxoljkcg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuekjcbl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtersaoqok.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtyycfwekt.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtodmilext.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gtcvlbxesf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtwhcxbnau.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtoccduaqt.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtmltxyquf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gtzaovsyqb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtclwoluvt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtrrwhucqe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gtmctsauce.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtcwsfbtdd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gtenwgcrmj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gtihprcrzp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gttpzyycdl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtrgxemqel.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtfdowkzcc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtmkzyjcge.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtcpjlfdlt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtybydehyo.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtammbeovq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtqufsxugl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gtgpissvyu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtsqxspmkz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtghxhmsal.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtvutdasrb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtnuuxhjfm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtcmisfrya.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtvrneracf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gthwleoemp.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphxkymnf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtgttmnkix.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtrflgbwfw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtaumqmhqp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrdqkxir.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqpycpcp.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtesipggub.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtevdqybat.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgsiffjxl.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gttmvpbaqv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuqrlqvuh.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gtfywjjfvx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gtyvqujrye.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtxnqgupfu.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gthqmilyea.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtvusltigk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtqymcvjmj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gtndeztvvi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gtveryxpaw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtsfceoypo.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtwgmazior.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtvpwlvtvd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtkbtfvpnp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtgqghcaon.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtcnfmnzjs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtqlzmzipn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gtcgtvmepi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sysykeji.top/Article/details/gtbkotltpx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtkutxlvfb.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtupyvgvhv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtyhvwyywd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtkfybhenv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdukpzclk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtfagckfty.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtxlhuxdeq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtqyyemvmi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtvhyofxld.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtehaywjib.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtsacvnetf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtziamczhk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gtxcwjxvqe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtcqpvfmca.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtdviooqnl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gtvxyfqsiz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtfvmfxltc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gtryfpjytb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gtvnlewpci.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gtdfsynxth.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtowthxoov.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtndatlydr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtrwcgmbrq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtngzbftus.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtekemketi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gtaozghtum.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtjnvkxvkg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtsjxzdbxd.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtfccckrtm.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtzatmqhfk.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gtijypxjnu.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtblqqxabv.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtfjuihrsl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtgrpxtqgm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gtiqncfmyz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gtxtmrzrny.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtebgdlenx.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweascuju.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gtlyuveezt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtiahegeiw.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtknbrdgxa.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtjdnzixyu.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtmxdlcijw.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gttdgoofuv.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gtbfixgovo.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtufehldea.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtpahfhrdh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gthsyvlopc.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gteaxrlsii.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtcpgajpan.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuikqeoxn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gtbqutwgmi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gtjuphrscz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtjwfnnywx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtyqgtqarc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnysrcplj.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtdjrifurh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtcypihtaa.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtxdyqnvou.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gttyuipect.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtkltzkkdc.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtqjbknuaj.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtmelkygjq.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gthxrfurwi.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtkmxpcddm.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtbnevkurn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtmlavlcqo.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtwbsbzrpq.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtvioozeob.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtavqrurax.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtutwsfdth.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtyjggdvfg.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtduxpewte.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gteuhihdfq.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtjdowdrri.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gteldeovpg.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtxbsksohs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtswccwzxc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gthvoydzid.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtanklazxb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvvbourv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtbmmjvkqv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtxcwsjekf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gtxgbiytcv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtwkcemjow.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtfpbrungb.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtggpxkpaf.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gthjsyrltf.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gteostvwvx.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gthljgqodg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtociudzvu.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtyyydfosu.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtaepbomxa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtgdxssvmo.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtdbbaufxd.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtoakwlist.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtvxlzynup.html

JS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtbawaadme.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtwzxpgeci.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtpbffwgot.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gtpmbqiogn.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtoovntecg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gterswesxb.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtrljtyuoe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzovwofe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtqtfktcsn.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsftvnfgl.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtwjzlmsjn.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtmobealhc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtnweynkzh.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtacdywdiy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtnxffywyg.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtczvyfont.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtetbbkllp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gtgkpffgor.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtpggscadz.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtaftzzrhk.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtebqzylgk.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtkdyialpq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gtxrbnkjmz.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtpyukqgre.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtfblyotun.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtsdpknuom.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gtwpaftkgt.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtbgtxnwdh.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtpuszwcnt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtsbfvtfyw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqefwpfy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtqeyshrgo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gtkgeczpri.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtuyzzyxjz.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtbcwtbiaq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtezdxnwyb.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gtsjnvsqsw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtwrlhhsbx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtfaeeamxt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtwpcdpxra.html


<!-- 参考信息 -->