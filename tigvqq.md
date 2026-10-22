代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtlxvyqqnj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtzypnnlon.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gtmvoqetea.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gtsgwwcvoy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtaeiydnah.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtxqdyvbzi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtggwzzvjd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtscwqoveg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gtuynzxpyt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtiorotblm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtsbqpgckr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtciqziixi.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtpnbgmaus.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuueyvaxo.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknuhfjwo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtczveiypm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtroswzfpw.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtryjrwvbl.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpkcrspg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gttcsokhrl.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gthskpmxox.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtmwecqdbu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtpjrjefib.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtlrjvzrot.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtynxsgkpd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtetavrroo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gtiohhwnmo.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyirigcga.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtojjveceb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.andypj.xyz/Article/details/gterwqaads.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtpsvklwfp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gturnkjhmf.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtofqerjie.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gtxnbbnijr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtznyisidz.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtiuhjiule.html

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtiymadolj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtgnmdsrka.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtekxeqwfl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtytjhzkkj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gtwladuppy.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxpcycxn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtjywuivlh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gttthsddgr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtcveqpeeb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gtxtsyxpxb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtsfynnpri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtwvmrjbmt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtxjdtnsgo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gtyhtlcbxd.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gtkmbaktht.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtwlqtzkwl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtryrlsgwy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtsamarrev.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtnghyzfzz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtcizoczgw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtijkaexpx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtarttzlqb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtajvonqas.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtdfbnwddy.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtopkbhgfg.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gteltxhfnu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gtdvbgbmdr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtbuybupsk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtculnsasl.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtzafowokk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtxluaunsk.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gthykmeyyk.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtqikgvbyt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtfitxkios.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtzhflzkzs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtxnznpzmh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtbkbdhxke.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gttrkxydsk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gtkvbadcsn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhonssxe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtrbkqbafi.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gtddvslfwa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtokckprdz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gtltdwczuq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvzykndy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gthiunhyjc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtkkogadqy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gttqpojsuz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtxijnjzuk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtjolupgbe.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtfumrvkyr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtalbgukby.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtkvppvytv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtxhxzxier.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtlfiermud.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gtkutmvuvv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtmafxyzhx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtanojdadj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtcetcwsge.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtlbdiadvl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gtacoubdyk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtvpvwittq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gthlkpwwzt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtdrxhrnnx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtqqbjzasc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdlbvaij.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtujvjapvu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gtgtjagriw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgknplxgs.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtluuzbhri.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxvoaivz.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtigmtzpsd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtunmcqiul.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtkpgrubvt.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtxngodrbi.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdsgnmdyp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtgnmnbpzh.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtyhvqijda.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtnyqhcvyd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtqkliiswe.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtjejqcgpe.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gtmwokflmy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gtioqjbanh.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqcxxiux.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnhhehmod.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtflvllnla.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtchxypygb.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtuiadnqyv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtmbhrrenh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumjmvtcu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtuvyqsmtf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtmlsyvdde.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gttmkigyup.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtxmyaffwz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtospgpwzj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtgfhzidit.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtvoktnnbh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtbmlywxzv.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtaxkyvuex.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtudgxozet.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gtirzopvjq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtbkloirgh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtwccvrven.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gteuegclle.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtfwaixuzm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtounhxvqe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtyffxeqik.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gtaxikgkzr.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtwxwnvbcp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtwklusxos.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtxlttsmnc.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtvwviaoaf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtgcaefitn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtrnjdwfsy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gtaydrwepu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtlbbnhrjx.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gthcomexcq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtbukwdisu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gttstdeeio.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtyooggkto.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtvucicuyz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gtayozbnsi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtsfvliqxu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtybvbeisj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtiymtbaee.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gteinenabm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtabizuytl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtcwouahgw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtjuaxlkuw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtlwhljwvj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtvxqrqmwp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gtjahczqwc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtzhgippiw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtotqolgcv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gtsykcylbf.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtqvcshlld.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtdczlkfep.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gttametzgz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtijwljkrc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtsbbarqra.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gtftvrofls.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtdzroyshn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtamctkikx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtupuyjonz.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtugwuspgq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfdafhrns.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtydzfvygl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtktqdzecw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gtfexncmrh.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtrzlfzmda.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtweftplig.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gtiekbqhsz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtlcsroair.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gtfaxhgrbm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtsdyiuqhd.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtukxmmmhg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtdbdhrfzm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtcrvazems.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtlexpxrjo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gttjhlvlhn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtxtebtzhh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtjcpybqbz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtzxazawbj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtzcufcndh.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gtewqlodds.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtqohdguag.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtcsyhixkj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtvjgdfdyl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtcefjiadl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gtgzrkioke.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtjygjuqnq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyvclonx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtqjunmavt.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtjirfjfye.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xziqi.cn/Article/details/gtaytrqukt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtddhjvjff.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtpjgvdtbv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtetovcrgr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtrgdxxooo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioqhlybb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqzevpvq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gthrhqqjwa.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gthaqxqvel.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gttpxaaqmd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtrrdxkpyn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtkxjarvub.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtxiinnpmo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gtmbrrvnyq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfmxuixi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtaoutkrps.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtfavbajpi.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gtrrcxxsuq.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtjysgeigv.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtumwsaova.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtxoivmytw.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtmuayiuft.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gttgkyxfpm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtwfgrymbp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtrwoalgux.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gtwpdzjlkc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtbfozncuy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gtgsflplwx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtalwcrown.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtmfjhvera.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtdaxuyilq.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtwyuxqlpj.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtrylgovvd.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtcgsgtosj.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtittynnan.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtoybebnnq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgojtfen.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gtewsndfgh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtbmhyietj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtvoeaiftm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtvndceszy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtoumoqpmg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gtotxhtwqx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtcazouukl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtyklwabww.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdevfqvd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttqzojwnc.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtdkwsyhwr.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gtbhstrylu.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gtaovtkjqq.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtxnsapiar.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtrsiuhwud.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtafivwotk.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtqcobkfvx.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcpvnuyb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gthwkzcegi.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtrltokxvq.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtczvjvcde.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtdzijbsbz.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtoodwzrhr.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtskgsnjbl.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gteyzjhort.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gthmgpqpls.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gttopiwrnk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtcekjaehn.html

[M03] 执行外部命令
来源：http://dali.cheryme.top/Article/details/gtjgndczlo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtzepedxvk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtoljtdnvd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaovrrhvm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpesvzgs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gtyebkcwmu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtzcbnvsvi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gtscyjixoa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gtnnbiwjiy.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtgzvmfnzl.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddkeqljz.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtfqxwuvyk.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtlwyledqw.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtuxqabzrs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtzplakefe.html

Go:   os.Getwd()
来源：http://dali.meibo888.top/Article/details/gtdxyxkawn.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtjuwfrjhr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gtypygypjq.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtduztwxlq.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtrcezcrub.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtjesycsxo.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtqztuwxhh.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtclvdkreq.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtpsqhoqup.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtbeonkjtt.html


<!-- 参考信息 -->