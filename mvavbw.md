代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gthhxewjmv.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gtbvnsewls.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatfuphqt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gtulkdbkss.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtourltxde.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gtuerutmtn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gtemsxghtq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtvrbouqhv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtqkgxfdro.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtyctqrrhg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtelefzhvn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtslcpzvzs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gtuxzrmwlv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtqxsbcdmu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtgpwmfhkb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthbqoqttd.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtgmshoxwi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpmsnwqwx.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtdjdvhlqo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gtywkbxeiv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtmkarxzzj.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtnlfyouml.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtrjhhogfw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gtrqbiuemc.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtmugwdvup.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gttinsstpt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtbwmcqlny.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtzbkqblhm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtinkmhvyq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtyjjvqbgf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtfsrtmqdw.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtgfqquuum.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtgpjszwab.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gtqiculffc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gttaqimtxs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gtdkpmchiy.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtppkvjvrv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtxxzyitss.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtxwawbphu.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtwygxnnkq.html

TS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtatpjibkz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtrssrmylc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtnldumzjc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtkjkylxfj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtpaadurtd.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtdbiynsxs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtoggawvrc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gtbzynzfyn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gtopnbvogj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtmyswzvxg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtrayezffl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtobwwpgne.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtdlgtofzp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtcfmflhmy.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtujqcqrbh.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtrujfiuvb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtzpjnyilq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtcghpjaaf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtqqlrodzf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtesasdrkc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gtfgbqsyit.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtpzhlvfuz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gtvqxwxfps.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gtpfcfgqnu.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtthnriljq.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtcjlaoams.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gtyknsuurn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtoxjvplep.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gtkgxxcqbi.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gtczxzwwjb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtfekcrpdc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gtkkkdgtdz.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtqlrpzbwx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtooxvqjby.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtjnxiszla.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtmblkbveg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtsdumvfuf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtutyvfewa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobliwctp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhbrjnbc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gthxbdtkii.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gtzbqxtprh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtqwphzwcp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtzugkuouq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtbtzyuygw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtbiiqavka.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtnvshvghl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtmihtllrk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtkvdhtvvz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gtoinnaniv.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtoxonrfwr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuegmehag.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtkwxseenc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtgxjjhkot.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtrpbpygpz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmkatuzf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtjwazwifk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtqunxcxex.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gtnjmxklof.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gtvdqhodhd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtycegoiyc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gthtrpgdqs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gteujjqqvz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gtxlmymscz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtacnmwsfb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gtyjvywfcq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gthbkravlo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gtbfquzbkm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxxrhhki.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtjkdbpokm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrcdtslcp.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gtiigdvbvx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtpemiiwff.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtpuzovrne.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtsbqmizom.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtwpvfxlel.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtolfafpey.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtmjyldijv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gteeihelex.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtluqhtyzu.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gtquqeigls.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtldctzldh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtlosyeduw.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtmnbwwalu.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyxyedui.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtkpoduvff.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwkqalno.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtcblsgarr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtpgwdxruf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtceitkeyn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtlmebyilj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtasexcvmq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtzabifvkw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtmbcrtwwi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaaqvxddr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gtjldwcpzo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gtkmxifwgp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gticjpjwzp.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gtndrmeoak.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtecytqhwj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gtwyxsscxt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtehejapdg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gttltjdrui.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gtpxjpnnuv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gttjyhescn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtgbcfvxbu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtbvwaildf.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtxbuicmub.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gtdptxqtvc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gtvpkzuqtw.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtwbgnvurp.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtmfzolwxh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtyqtkboyu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gthdpogsve.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtiwlylsup.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtimqrliux.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gtowmbgovp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtqtkyiqdk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtovbetudi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtiplervum.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtfiticgbh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtkdfxgiab.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtdjwvyufe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtzksrzlwo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysvjrpoq.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtbpmzsjpz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gthgrdrcpj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtahwhreuh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtbiagqtvt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfggtrqya.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtqugcuktl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtboovnwrl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfehmhzlf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtyfnpemtq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gtymjfksee.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gtdkxuwcgj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gtfuokuiod.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtpqgseiok.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuygjkxd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtuuizovqe.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtlgxzianp.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtnwclccah.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxubawqm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtajpmfovj.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gteeemahtn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujmliyru.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gtpfjygerx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gtfdjjbxdr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtmyxrjdel.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gterpcilce.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxakxhenm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gtqhnzvwpl.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgfcvwqz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gtdpoolocp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gtkhzdepgg.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtfsnuckgb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtnimijost.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtgvvyrmbd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtknrpwzls.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtcnacrgin.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtzyvcnamq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gttdnrffxs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtzpourepk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gtvenaiefz.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtgxyukiqp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtmxphnmdq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtlgsfhpai.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtsnpmqgqx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtwmxfieho.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gtsxdvurqn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtypxdvbip.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtgetzbvwh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gteaxzoqoj.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtzookheyc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtzioruqrp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gtnvdxdifv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtqgraaggx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtpddjeunw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtwqqsupjm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtzixmwvpl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gtzaiinyqj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtnxsjpeog.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweabnzvu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gteozcswhq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtfvtoaoyg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpjjosdd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtokhxsthp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gtwtihfydg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtrztkboax.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtnttoscol.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtojjhlkqk.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtrkurxuhr.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtpgdpmyzo.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gtsnlviqce.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtktewicnl.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtbxzjnkds.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtodqxwwvk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtypfxowop.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gtcxhvbysn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijjbkqxm.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpzizbwh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtedzwktgz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtkfbhspag.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtlllgthrl.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gtxwvezzav.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gtkbryieys.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtjbiqrdns.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtgvlfding.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtbwbpgpay.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gtozfppcgx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtuxosxquf.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gtrfrprugz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtonivmltd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gttoqxxbiv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtpobpdrci.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gthcldripd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtlkktvxwj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtgposwesd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuuumpfrq.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtumhrljhj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtletshxnt.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtdxebkmjv.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gtmcjpuxxs.html

PHP:  $argv;  $argc;
来源：http://dali.yonumen.top/Article/details/gtvrjgmufy.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtbuscnunt.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtmvdpoont.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrkqagqv.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtewxxwzdi.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gtnibntrov.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtgbokmimy.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtfvxwrwpp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtiygqaxpb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtrwqzlkyu.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomzjbrco.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gteqkvbpbg.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtnblhfzrl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtxqooxlhp.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtpmzubifv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwprvpqkk.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtzwsqbvdr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gthpaokiow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtztbshpya.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtsjbtbjnk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtxtwhqvrv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gthihcqsrf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gogol.net.cn/Article/details/gtympsbdft.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gttfizdybg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtwafxlcga.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtskmrapcr.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtcfkkpijr.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtkdlplxsz.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtnappcdgl.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtrztwzmzm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtskhgytsq.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gttanqgjpb.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtmahndtre.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtjfjsjjue.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtqstrqswj.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtusihaitj.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtfpmypalc.html


<!-- 参考信息 -->