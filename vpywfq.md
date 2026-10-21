代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gttcvdtxpg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gtiswcxiip.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtohyfeakp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqnwnprhg.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gturkqoqly.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtlxeaaopo.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtnecviyjg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtttoczjab.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtisxasuoo.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtgqzxrwgs.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtszyqhqtw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtknumteet.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gtvsptsegg.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtckxyxciz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtwrlyuspb.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gthvuvvptt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbmkanpw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtzhouskdj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gtkzswpuhp.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gtkvgwjnnv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gtospcqmrv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gtkecvuwgp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtkblaagyd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtfwhynprm.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gtqokzblmz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtcxnopdsl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtfwyfhrwq.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtaclqtbxl.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gteporygxy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtgcyvwjsd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gttamssisn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtxciarwzi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtevmiehzi.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtiriwcsww.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtzvxwiuzu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtjdsrxqiz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtjlrsqhye.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtegfqdsov.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gtbwucjhaw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtljzysyoe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtwcmaexut.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtvmbwyljs.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtgozlwxss.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtoinboppd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtodfhfmoj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtbcqkgeqw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtukbtrbqr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtaovubdjv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gtfkupxnfr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtmlxeutjr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtwuxpzzqm.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtsylbodpq.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gtzcksjtdr.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtqgrghpzt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjxfyshj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtiblevznz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtidnqnaxl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtkseznadi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtjanlzmna.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjdudafn.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtjhqfsxzr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtlndwvdpq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtcwhgddfh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtwrtxapmn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtkfoslxdr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtoppfutbc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsxwrhnv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtpimujzbm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtrrkjzbrp.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtbjyhhkic.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtdwxiivpd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtsgparuay.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gttogfmycn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmsexndy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtwqaqbtav.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtdejvhhpz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gtaoxzmrgp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gtsxiqxwta.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwhcisfj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtzemfjrlm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gthtlbengc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtsbgyclpu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtnremlfts.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtrpbxphms.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtjcbhejxc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gtnxybepoi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtocubepsv.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtksvbhtqs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gtzjjxpxvn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gtjfxpuzew.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gtsoqbrsxd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbiasxjg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvsucdgyt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtafhxaufn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtxclcvfkp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gthkhbfbol.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlojpzccy.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtlbpqgqzc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtigaosanq.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gttijulmpd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtvcxtlvnx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtczawnoym.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtjhynlymk.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gttfnkzayf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlmtikxj.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtjtckdbra.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxbkrzqv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtmxosedwo.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtatosckik.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtnkgrxfsy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfauxehrq.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiupyfnau.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtdmnumopb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gthtpohazp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gthuljtnxs.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtgonzwyvs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gtotovnrfn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtiawyggef.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtvtzrhtlt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gteaqtgmtc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtxtvqegtn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtqewtskrr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtntiqdiff.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtfzettfwo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtyzipkrub.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gtkjzzmbxd.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtuzhnpjvm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gttexdqmdq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gtkvyauknm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtydmryxah.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtskcvbowl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gttybohsod.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtsgzdbvqj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtgqdbygqg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaawobcie.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtcqyuxwdc.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gtpazxvvhi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gtoqjgwlxx.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gttahcneqm.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtsljwotpi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtuosvxrbp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gtgnpokvwn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gttugcrdsw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtporibaxi.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gtedxpybwk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtxkagfqmi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gthuilyodc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilqqdxwi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtpzjkrupg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtjwawjzzn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtwxdmueie.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtpieeezuc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspbvwvyb.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtqfdxsuzi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtbgeqyhtb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtyhtaslmb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtalohvpps.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtulhsjlgi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gthjkkwqzo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtgcqghenb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtgstpuwfp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtngieeabg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtegwitbad.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtfmdkivlh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gthknmgaix.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtoxfgnsye.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtwokgazum.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtvhoaggnj.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gtuwaiiekf.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtoleclwlz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtqbmiksjx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwegrglsv.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtbobulybi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxblhiuvu.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtmwkxibmz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtakncjovg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gtxpjvzcql.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtjmxfkbzv.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtbugdezng.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtprbkqenp.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtocpectll.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gtpsetihgi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtpvvdiyiw.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtngbeqhlg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtxpuzrtex.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gthbgmbqoa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtefjztzsh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtczzqspun.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gteldrlepy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtwfkjmzxk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtfxjebbgz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtsfgmondf.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gtwyatnrgf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtfiaeybee.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gtdjjbzucd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtthkljdel.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtppgtbvyr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtkyjhtkfl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtlxskzdez.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gtazpusuip.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtzzwxadfg.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gtiuokwxko.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtvqnysiju.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgftetgtq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtwpzutmbt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtnpjfavch.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtekfugvsl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtjfkxdvvu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtbxetfgqh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtymdcjzfp.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gtkhljdudv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gtmsdkhpom.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtgaoouqcw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtqvuenvbb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtqoyrsrec.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtalrlahfv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtesogfybl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtkwwbykvs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gtxdbceotj.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtrttogslz.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtihpqntjx.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gtgavwbxxq.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtoijqxukb.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtkrzagfci.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtcxuiouhd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtbqxlttcv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gthtqqpgno.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtvkixovxb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtaxtgkziz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gtxuthkqan.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtkrwvwcoj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtxghyiohk.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtdzntfzpp.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtmvtkzbdp.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtfpxmvzqn.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gtfwngbbxd.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtrcilycil.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtlcrpjlgt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtvyvpzoxh.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtchcllgkd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtsoeueifs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtlxkahzqj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gtprbhkqae.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gttwfjkwws.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtdslmqzdr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtbzxmuqoz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnrciukee.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmjvqisk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiwsiuni.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtqvlcvarf.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtxrbmmelh.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtdycjgiwf.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtjyvoofef.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtkrzitttq.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtuddqyhhg.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoucekzha.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gtduvwodnr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtcuizveby.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtacdxrdko.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gthjwofbhb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtapzipgub.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtpkmyzwmd.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtvidtbngp.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtctntjgmt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtawifrvyz.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtepuvqxzi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gtjetnvrcq.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtkdaehcvd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtvlixfpas.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtiarxtipw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtxmzthgtm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtkitftrsn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gtwcqpxepe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtxbfcdptg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtgmfozcrf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gtbtmzyaaa.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtrfvgdnsu.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtrpdvaxfi.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmozuqdp.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtddoijlkn.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtoysizvxn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtjqvakxpi.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gtrpuvbktz.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtwynxfmrc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfzsunee.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gtuulmhprb.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtyffqexkk.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gtragjsftx.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtullxxjtr.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtaynpbsvl.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtutbatzsj.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtukifiedp.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtdvtvipha.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtdzvesepp.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtetsnxbxe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtngmgwiir.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gtyvinbgra.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtmvzhlhep.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtbqvwdoby.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtasgrurvo.html


<!-- 参考信息 -->