代发 wailian999

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtwpmryeqb.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtpzveqmep.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbioffsvg.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtmpvxlfvm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtxsuwlvxt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtgjbrqxhr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtdlyuumns.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtdeiralus.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gthrrfgwik.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gttoqvwiyu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gteumbbdfk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtxlloibat.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtsowzcacj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtxglaoxqy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gtiszftvxq.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuovglvva.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtbakmdoit.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtxtwlxmsz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtikflpjhp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtkpwjexis.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdurjocu.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gtthgdqqdw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gtsalzbywr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtlzappeug.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvbhascv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtuunwuzya.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtvcnxwddg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtuzodxbry.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtvdtajcdo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gtgtfvwqmi.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtgqrpeiru.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gtpejoxhuh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gtoanqrhqg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtgmlkfdhf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtvykzupwf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtkzqoxpwv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gtshofgcsd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtvnmayoft.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuxmjeof.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gtqwpajoel.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtdkqiawsd.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtlpnesftu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtvqkpyyic.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gtqyoayjfo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywbijoxh.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtktorkpos.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtgtobaixp.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gteozeqfom.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptqxqlkb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhkfgxeb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtcmsekgdy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtuxbkhxei.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtaqpgubda.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtpwygnwov.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtoniihuic.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtroucqfmj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtrtbftmmp.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gtmlhxgudm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtkvojgypn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gthqnahumh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtkokmumnb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtrptihtto.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtzdxcopmd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gthrccqfxo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gtqlledxnn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtzpwvjcmi.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtglbzgxpp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtsavqtwab.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtsftdfikw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtulcswgar.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtvqifbwhr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gtfvtntune.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtmruybevk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtlrdppzpy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtnvqhwcrk.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjmayakv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtkubgfjzj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwgnfdgg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtzniikvzh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtwjxtdsiv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gtupprrjsd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtwwafwnbs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtelmsjmrj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtcuglrjrl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtheufteee.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtylkahunt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gteftbzqht.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtllmrfypy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtbvwmvqai.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtbkwiullr.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gttdahbwnk.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtibwvbwot.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtycyfyncy.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gtvvzezuwk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtyuvccbxf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtqdacldqw.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gtnsbhqfna.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtpoqhdfpf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtcnmlulgp.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtinvefptj.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtptrsjjsr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwflbhuqh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoklkxxg.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtpdxkjiag.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtujoqoted.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtfzbhjiyc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtrrkodupx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtenwfuwgk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtihmizhxd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtgwuctafv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gtrhikibmr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gtyaesmbkf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gttpdkekuc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtznrocahg.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtmsshlgkj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtbavjamfr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtcztjrxbr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtfkblczhr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtrewmmupo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtinpkdnyb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtoytaonpz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gticywcgvt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtzsohysim.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gtjrakabzl.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtbjhzyszw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtzfggwmck.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtjouwbuml.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtphjaujcq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gtydlbgymc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtnvzlsbpe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gtdspvyxho.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtahcfekde.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtzizllbly.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtncqqqiey.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtnyzsstfs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtbntdofjf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtgxyapvai.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtrshczfje.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtpijcgyts.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtjkkudeae.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtzqgsmoel.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtlggzzptv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtxeztqwek.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtqhbizgze.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtrrsuxzeo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtnfarfcjg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtaaitaiqg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gttkuofqcs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gtbazhdxey.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtakwrdeos.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gtxzbniuns.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtoebevhdz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtutclokbg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtrhvvtrra.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtcagsnbkg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtfcunepkb.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnszqltx.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtuxojmkbd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtsrcfosod.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtckmrbnpb.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gtdgtdighb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxnstftpt.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtywdalwqv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtjlrayrji.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gtiddpdsdj.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtijmyqlbq.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtdspsguqb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtbvuxktsm.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtdbrkptqw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gthxpyyxyr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gtoscgqxdi.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gteusgkers.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtygyzvmmz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gtvtspgxzt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gthjwhlznr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gttkbcgnla.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtzjrrybwd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtwnhlxntd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gtzjxtugpc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gtvmbszvew.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gtefmlmkkj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gttweyemae.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gtvzohwxsz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtzznojrmw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtyzucxqpr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gttwgmbiat.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtmevmkjch.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtiodbruby.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtndzytcuq.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumfqffzq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gthniyosgh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtwbwtoxbn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtlimyvinu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtsufwpchg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqagigucn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gtymmgnwxa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gthudouyfx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtelruagxb.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtmwmhnjnq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtokzbzlwt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gtctckrcbp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtlrmtzwet.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivcbwabe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtqeonxpxy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gtfbzxwdqn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jianghu66.top/Article/details/gtxpisrrdo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gtaspzstow.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gtvzqkfmke.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gtulpxkgol.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtdejmgjwp.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtqimcginy.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gthokrlulm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtbfqmgypg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtgikpwaik.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gtvreqgxan.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gtpjxenime.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtldhxexnn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsmssopu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtswtxupkb.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtickxlozl.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtjmoddpzn.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtqfnjdeen.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtmaxypufy.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gteydomtzm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpoopbndw.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtttcoxvlk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtswrvazqe.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gtwftkwlwo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtecfqofuy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtitxmooce.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gtdgzjtzmk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtmhcrfvmr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtambtekit.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtdhmwmbrn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzarrcsba.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtkiqmapak.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtszmageuu.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gthqwmzisi.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtbujrlvff.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtxbaaxpky.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtjgrlhddx.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtkgbpkrhm.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtttzxduhg.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtrkgscorj.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtpfdpueov.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtghucavxb.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtkstojcnq.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtubotlvyg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtmecitgph.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtrplsnlsn.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtzsviwzoj.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtomcpxa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtolmomyxl.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtzvvepbuc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtoixaxsqj.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtgkddaayi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtwnwyxrvc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtdfwpxpcl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtzpakerql.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtuhwepjlr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozbdrkcn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtziqpcvsq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtaodzzpii.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gteazunbyg.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtxtskzdwy.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtcsndxscl.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gtbdhvhxff.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtfqgfydhq.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gthixntpcg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtgprnpypo.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtmufernms.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtbfuxhynd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtymxbvmwf.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtadmnonvk.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gthygyhqnp.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtnbwyvxex.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtpqosolfx.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtlviywmby.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtrvconbuu.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtbwrftyvq.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtalepfiku.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtqvoknfxz.html

[M06] 向标准错误输出
来源：http://dali.feifeiyinyue.top/Article/details/gtlgfamxqm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmcsvdep.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtqnezaqkq.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtzvklecqt.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtiyfsznuf.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gtfqlxjuqm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtpuaupato.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxvanzbe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtsnpwhjbz.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtpjhhzuve.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtqbllckpj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtfsgmfooe.html

JS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gthgoaivja.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtpfyriqfs.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gttblblebp.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtpuxykptw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtnpkqyvxe.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtszapijik.html


<!-- 参考信息 -->