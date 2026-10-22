代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gthuruntlp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtoslvrjid.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtxlmyecmz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtiilckyen.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gtatycuyep.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsxqggklv.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsdtitpj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtmycokwjk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtohocddjk.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtatokzliz.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtupnvouje.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gthqaqmcpz.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtsqyowyyc.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gtioyrajuu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gtynchgbkb.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtdllaxpur.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtwgmgyveq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtnhgqmabf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtdphmnjyj.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtzekgllle.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtjgvzivng.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gtsncsunlf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtbegjgzjr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gtgjerbbdo.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gthlsnknbh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gtdogqxtgy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtzoyhszpb.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtvbvgoeje.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtipsaayvk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gthtscjinb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtvcvsijss.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtfylawgkc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtohuifdsl.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegedomfy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtdpjvewjv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtkgzhxcyh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gtrzydrcfo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gtewrnpclh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtvmuuybui.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtswwjjpyb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtxcgpkkqq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gtndncyuiv.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtvrdkozww.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtrvxfdvtv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gtoplttirl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtczklijyt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtnwzzcjvt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtxfturdhb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtzvfepxbx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtbfbdgacv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtrctydofz.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gtopdpbogj.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gtxsvhqbsn.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtuydfaypc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtckhbsbqf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtcjeiizdz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtxtalarjr.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gtzjulyfdm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqhkkgei.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtaurywxkd.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffngtdfn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtcernqeav.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtaqckoivm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtsumsizqt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gthedxyipl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtqmrlbtti.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gtebrgnpbc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtxsdjfnqv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtqmfmyedr.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoibnovcg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtruyyulkw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gtkzkclbet.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gtjpikhqgs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gtghqyjnnr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtwcghvnnb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtwppolote.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gtpmiosbze.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtokltfucu.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gtrqvfbbou.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gthwjgjxcb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gttwkjfgxa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtevjxtuth.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtoqwvngiq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gtosonwkez.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtmotsqyaz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtvviwxkms.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtvxaxjqgo.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtktkngnap.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyoycenai.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtmibngkim.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtfiuhtmie.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtjqdsdxyn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtflkhiptp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtnwdggasg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gterpwbvhp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gtajpovriz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtysarmljr.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtpjxcddbb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtonjkxmtp.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtvdshkdxm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtccfktyii.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtmwwhxdsr.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtcjnjcuum.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtraiahyik.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtllqnhzgu.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gttrxhtrtu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtwyyeztui.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gtcuejtdxm.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtovfwmjns.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gtuxnbxfsw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtgayhjzbw.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtkzxfslsz.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gthsyzpejc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gtvewyqkrh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtulehwqiv.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtukotsuoq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwsejlha.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiykocvi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gthnlcxowj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtkrktmlgb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtqyjwatnp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtkgpmieyx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gtluqmothd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gtvublelse.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtsfthwdua.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtvwpxoolo.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtlkdmylcv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtbcfgfwrx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtxhstfgny.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtanluszqp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtprqierqe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtvdwcbtuk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtymqrhcpa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtyhivsltf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtxfgyexkf.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gtuvszcwej.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtxxfaiasz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gtuqbjnlup.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtfvavzbaz.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtvvyxswff.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gttkxdddjc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtyamoefud.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtcqxjrhlx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gthtjlovpy.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtlfresezg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtrjpzmpfe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gtsargisou.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtkhhirzxq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtgmgsealj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtdzzrmkak.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtrayhcesa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtiuftqnhc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtcmftguin.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtkibpkbhx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtohbdwlml.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gtlnhgzbjd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtsuovbvha.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopxzsihw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtdqtuflat.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtxtnbovgb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtazueulze.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtqocpcjae.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtuaebkfou.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzlbdlci.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gtnrvisobl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtqfirylnj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtevmyxeea.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gttxvekoix.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpyavwxn.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtsgxsfshm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtrwmawcgy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlmldiocx.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtnlpltwsb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjfqizvtp.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gtcqeqgysh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gtahgrgkbi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywkkeskz.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtqxvbzlil.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtiflzreag.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gtqkrdtaff.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gtyudvipfl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtkkgmfozs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gtgctfdxte.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtemjcvbjc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtosesgoma.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtrbcdepfv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtomvtlcfy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybycyhoc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtpuucqmaj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtnjvvxgju.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtxrbwxfzq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gtgvjrgykv.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gteenmglrs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtwvisehtm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtktgomanv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtpivzzknc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtimpbgesi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnxiangtu.top/Article/details/gtuaxyibql.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gteqsxzqol.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtsuezucru.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtgmboixae.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gttptehnul.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gtlprqfkhw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtmugrhgnm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtasswrrkw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtfbjpazqd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gtummbmril.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtrcrxfqzi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvvanzff.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.quarkkingdee.top/Article/details/gttcbzufma.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtwtjgweyb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gteiwjqsha.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtlmucxvih.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtinaslnbj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtjuojcjuf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtrbeuotll.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtxfrtbybk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtwypnjeqk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtbdwobllh.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtnbpxfanf.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyzhyjku.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzvnpsnt.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtmjjbowbr.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtwpmoiwju.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtgxeowfwj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gtmcxxbfrw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtgmfajtdm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gtpvynvbia.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtickinmab.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gthgukgsjy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtmhyfpbdk.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtyiodyjkz.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtybytvnvg.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gtrylwefwx.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtczhkmjyq.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtbsewzdcb.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtxccporhw.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtwodeuhvp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhdpuqus.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtegzrrrne.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtqroanquc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtnkctbsdk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtxbahkhwr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gttpnqxfji.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtdverauud.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtxpiujwyl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvlvzrnqh.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtrnecnpnh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttldwdjzp.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtkrfddvva.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtwayufoew.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtostqrhgc.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtorduboef.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtgbuqnyud.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtpdegbhmp.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gtcmdlvgzd.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbltwoal.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gtxczvjgnb.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtnmpxijcl.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gttqutphtm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtggbommba.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtaywtevkx.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtgjkxsbtc.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtlgjtujcp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtpzfqwajl.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtdgpetnxs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtjrqchpyd.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtnzhlxsuq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtvperyxwy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtphiplbho.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtjkqhdjmj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtlczrkajz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtaxjwlfku.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtterwtyph.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtqaxbflha.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtdmneoroh.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtxbtozezz.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtzfgcjswg.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtjkcspoum.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtfdenspke.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtzdrbuvwa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gtotwpxkrp.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtujaicylg.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtuajxezjr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtxuvqqspe.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtacalmhlj.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtbrzcmgsw.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtnbthucml.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtjxtzatzn.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtaqgbdica.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtvroglmdx.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gtrvvdfdje.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtxugfrzeq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtecwtfopt.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gtsbbxxehe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gttleqrsob.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtbzaoqrrk.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtknumuscd.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtibciokza.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gttmztojhx.html


<!-- 参考信息 -->