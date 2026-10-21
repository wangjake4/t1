代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtjlpwmtms.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtvbhlywne.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtjibahelv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtmgplnmpi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtvkonqbsl.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtsiyrctyq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxgqshkr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtsznlwcsz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtdjllcuke.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtopcbrzvw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gterlexztn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtrlightfu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gthtkcftvk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtuhvbobrr.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtzhogpogo.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtgrsaclqc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gtfxqtjzcw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtriojfjyq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtbyvudjog.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtvswimcya.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbnewkcv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtfmuzvfot.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtxzlxvpso.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gttloorcih.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtdvzfdfjo.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtkwkqhneu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtfwoscwdz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gtybyroeff.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtqylenrcb.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gtvaaxfupx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtmcmaugag.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtulrjglxm.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtisvhiowy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtwnkwynrb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtiyxhkqln.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtufrxubts.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtxfbvdvya.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtzcmxjdur.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gtflxmtsyn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtdgcchbtp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtogfqlpnu.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gtnpmkfrpi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtxaljnedw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtqcvvsvcn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtqlxbqvwb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtevdcycxz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtmndaqoza.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtjgklsexp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gtgtiwouyb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gtcbxxykit.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtnryaxyyg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtecxyehui.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtctdgbaas.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtvpgirxsd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtoqycxrpx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gttuofgkxg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtnvkzbckc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtfpxpcntw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gtgraojibg.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gtogkybgwu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtahmsjfap.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gthmcrhbix.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtnputfxxb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgsngtms.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtxwzwppri.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gtbktvxzxw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gtmjorclsc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gtgmyturua.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtreobvoaf.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtgyvswkgv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvabvcwcz.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gtayhefrmk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtjpqtnjpd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtyrlydlzs.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtpfdingnt.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtqblstupm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gtujvdlpac.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtxntllemr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gtrhqajijg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtdfbyuapb.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtcqpmojnf.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gtqkmrolym.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtywdfuicp.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtzbqqujnb.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtmpqkqrky.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtdcgxanvm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtyyqsupkr.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtnxshhzbf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtecclkatm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtpgmbywds.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtnnyjqpxi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtukujufbq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtpedozhwm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtpwooydeh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtawsufljq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtrystylka.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gtcmgjbhaf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtczkluxrt.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gtbtqknbss.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtagnpymtx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtqvthmcxt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtzmpxanem.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtkdcgxxtt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtugkqquvn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtllfimgvj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtjocdtezk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtygssuxms.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtxvqvvueh.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtutttggyh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtalefilyn.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtzrdebhek.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gteowolfku.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gtdtafogry.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtmilsosyz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtzzulrhke.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtmwcjitsw.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gthjkqztpf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtaxbnsumx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtiyzbbdqf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtqpgfdgfh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtqydzgaad.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtjnfneigq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtonvzedna.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtnlngddmx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtcpgovcjr.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gtuumxmand.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtuhcfiqnt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtdasorivz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtcdsuvbdp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtvylxqinr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtckvgvjsn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtlvhdhvkp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtmoqkkvoz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtuovkydms.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gtspdpoohc.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtlubpbrrs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtnxilrgga.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtkqhodhfr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtgggpubkj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtbwhcofaz.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxnkakzb.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtracbcfrt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtsyktlvvq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthsmafwwb.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtrdesctnz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdhjerojk.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gtwfkydhcd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtdpbdlvba.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtriebbzqc.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtlezjawhw.html

TS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtgqsjtodj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gttcgzmuck.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gtkosuynyn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtidzelhjq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtdbgwmvxb.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtzdgzcxhv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gthkifcpnt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtqkpvytpt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtdkkgwibz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtpysisqej.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gttkuilyha.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gtnewupfgk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtgozjsikn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtczrafkzs.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gtldbdchhz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gtljatoogg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtmlrlhete.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtlqdqktcf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtvmthxfmz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtqqaypbbc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtglyhkecm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtgvxjcnzw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtxzrceqeq.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtffyjsmtz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gtvvthqfdq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjesjwlrp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtqcxxytij.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtismyohvd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtyivkromu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtqwtejbyw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtfqrousff.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gtesnyzxuq.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtievqgzdm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gthkzwvsql.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtjpxjebyk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtdhuwylnv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtjhavzouz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlkpbpsb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guannengcc.top/Article/details/gtpockmred.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtfiodyvcs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gtfysurwhk.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtdcdqhwaw.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtrhionren.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtrswmhyyk.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtjbqlynks.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gttmjnqnzk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtbgrypsww.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtbbodycjk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtkdizfofc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gtqpzypers.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtychcdcda.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtckjrasff.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpufhafnc.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gthylwuwpq.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtguggmdxy.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtwabvqnnk.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtygjcgrmo.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtedkrxsqd.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtzrdaacet.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gtnyeqilva.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gtnthtotmj.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtrpgcgxje.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtvjdeflum.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtcctndtmy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyqnnoyk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gtvligpjpa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtdtaderal.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtezrwrhmi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtktmuqulm.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtvoxnzzge.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfwlzlwkc.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtsrwxsibi.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtegtkfuvl.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gtmugimoie.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmhbnfpmk.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuuzlorw.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtzozmltoj.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtfkvigtmd.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtindaxfdd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtupepvquh.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtuytbzphd.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkukwsjtj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtxgevtsom.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtdufiawvs.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtyeaivcsr.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtgtehdbhe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtkjjldugt.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtpcdxjibr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gtjquzszln.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtpjcquadc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gtykmnrmek.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtgdoqkcev.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtbbzhptgl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtdlnwuwvv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusecpbxu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtzxtcarbk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtduemttha.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gtlgbkdqir.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtzqhvgsmb.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gtoearlkxx.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtdtdsrvaw.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtuerfvsuz.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmfbsiqu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gtlxnrkbyd.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtbgpltgig.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtjmldiukk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtmxdfrbha.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtuuxkxpax.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtglpkhijd.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtszvvheng.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtogmfknxw.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtnvyxqotc.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtrzbbvxoz.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtrhssghyx.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtnujiwjmy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdxcnltb.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtyhlttysl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtnstiqxla.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtjmmgfuan.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtirjnqajv.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtcqnhkfcw.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtslpciuvw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtkpdavnny.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gtenftsztf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtmzisjqnp.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtujphglao.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtsxhoiwic.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtyymtncdk.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtokbvzdyu.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtqveqkoyb.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtudwvdsye.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gtsowtkbom.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gtgawluorj.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtpgioextb.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtwgzaegmd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtbhwkbwaw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexcmfofb.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtfbndfclp.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtgeltjuud.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtxvbqwlew.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtertrttyo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtkfnfhash.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtbhsttmzg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxuazrwge.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gtsavhlsiz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqzpwtoyb.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gttlmaieia.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtiuydptuq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtcgymwkiy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtzuxyvpom.html


<!-- 参考信息 -->