代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtssawbyvy.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtewruduxg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.smart0.xyz/Article/details/gtsnexgvca.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtvxuerlkv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtpatqxgfv.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtrkbcbhfh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtbturuksc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gttgjjszbs.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gtiwubygvp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvumkkqn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtdcdqfyws.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gtagavyirb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtnihifdmf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gthnlfunxe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtyfuxwwnj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtaqlckzyq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtyeflqfnt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtunbsyhfa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtyngdgyal.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthatbclyx.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtpykwuewf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqxgprmpm.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gtakcgcouc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtnxtgrojr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtdrhhehyz.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtglgnojnz.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtxnoqkwnx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtnhyovcut.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtxuozirgg.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtwclropry.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gtodqzbofq.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtdbdupxmy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtmmzqzyzr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtbbepbrpg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtszzeyzcw.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtqwhuqpkb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtttpgrjcy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtonfqhcyq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtolqxjyhe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtxusmhabx.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gttnfvkcls.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtqbzmdwgg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtyckfeune.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtxflnfdxf.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtqctdmvud.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtjxdbrmqs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwolveje.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtweapejty.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtygsyzcwk.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtbwvczbna.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtlmqbrdov.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtouusbpwx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtkbpvrzht.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtcdvmkjcw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gtnmxqgfhg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gthvwzuihc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.birdmap.top/Article/details/gtwntgvcbn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gtsmflsxda.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gtpjizmunp.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtxxxotoqa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hfpthk.cn/Article/details/gtepagjqsn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtmakwxqqa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtgruosraa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtvdepmfbg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtcafscsps.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gthfeaujlf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtuzmuporu.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtyptyhhlp.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gtsexpqurd.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtjsqawyoc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtgsvduakb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gtbmfnyaas.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtyzksppxo.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtkxajweje.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtjyfelfrb.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtjkznbklg.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtvgamojnf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtfoxournf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtbczjnget.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtucnymwvt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtiznpqfgd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtemrjknch.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtbbowewgj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtagywohsm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtdvmoyzpk.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtqvtvnqhp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtqprfdezu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtnxxktobp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtrsxxssvi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhongyouzk.top/Article/details/gtsudgbamc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtevlcnysx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gtvfehalzy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtimmioctn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtamugjxaw.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gtpryhtggs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gtzzcqdmdv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtsapdsgrj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtfzvzcsfz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtoarabmmc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtlueroxnr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gtwqfgbgkn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtywgktgel.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gtqsybpdns.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gtkhktusac.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtosaecwgv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoncnnftv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtlrmckqzo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtqcktxyov.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gtzrxfczao.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtsnlefwnp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtmmggdfcc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdcjsfmn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmusckqwg.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtdvspsrha.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgnjafqxl.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtjtoqlmdt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtsnnzfybp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gthuctjmov.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtguhbkazr.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtiyomtvet.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtcdhtkrqm.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtmvpjwtmb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtwpkfezah.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gtpjmjbwik.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gtszfrbkau.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtcpishwma.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gtxzqgnphk.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtesbdlkhc.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtabqlhgxx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtucpgcjxg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtvjcdzhkm.html

Ruby: JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtlyxaqqet.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gttpkjlang.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtmhepugfc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdshwvwz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gthfljtliy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtvtskikyv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtfjgnpchz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtowdmbtqv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtgfltlvod.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtofuhmnyt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtrnmfwdua.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtrwkhrxyv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gtvlpdvyls.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtrvcjntiv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtynaaboav.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gthkduhikj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtjblrlhfm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbdezrax.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtdtfwdsaz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtongeslge.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtrjveummo.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtempsmhgj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtwbdnkkxb.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtgujobpqg.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtfksfpfxx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gtrwcloofk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gttdbckjxq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtfopphyjz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gturlamdsg.html

[K06] 解析 URL 查询串
来源：http://dali.shangyingyoupin.top/Article/details/gtzrkxqsgw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtgbisnsgv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtwkogqqxm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtlizkmlkz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtnaqkyeed.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehgaebif.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtazevwyrn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtgdrklopx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtrxihmxnn.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtflmjravu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtyuqblvuh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtgaemptym.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtrgvmlmnc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtuidmusba.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtnmulbuds.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtcavxuqsx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtjbjexnvu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtnujxiunq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxkqrtft.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtjqwhnojw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtptcbfuxp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtuqyphdhx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtoewdkxds.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gtycimoxjo.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gtwvszqmlw.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtvubldmtx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gthpslecgp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzqjimpov.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gtbpedkheh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlntncyeo.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtdylmqawv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtxbjkuhju.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gtrwnimdev.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtbjahzvph.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtvhkbhpwx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gtwiwhsnbj.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gtxhfvlzxp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gtrrgokvjz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtuegfhbxx.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtgoghxstp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gthxgouyvs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtjyaibviz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtoqmmpddq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtkijjfyyl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtfjimejtx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gtjlccadgm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gtpgvbwrxo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtntvsevay.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtsoredfic.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gtqxwvymqv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtwfvudpwv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtxwkgbwza.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtirvcfdgz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.feifeiyinyue.top/Article/details/gthjynwclf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gthluchqtu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtubuibwkg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtllamohak.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gthblzlgkg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gtgyafzclb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtaqqqpqep.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtqhtrjoao.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtfyrpcbnt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gtctkjlouy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdevxnad.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gttejpwnqn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.kuanghao11.cn/Article/details/gtzszyzexl.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtjyhnqnft.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgiuncjk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gtwccwhbgf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtdftroufh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtmfhiykdu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtettqctmu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtgekegiws.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtpjezmqic.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtcrrdylpx.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtsnwzntdj.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtrmjnytuu.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtwotlacza.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtvltjrvel.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtgjpumexk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtzhwypehp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtzzqnalyi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtfatojrxu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtqdxigzmf.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtrdylydsu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtabjmxfhx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtanjrmmwb.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtoqrgheyy.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtproxmfex.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtwkawekbk.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gttrhhitwk.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtgimoufhf.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtkqlybyed.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtwerfuexu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gtsmymlxrh.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtpfxbzovk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgqlvleg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtmakczeak.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gtjhopatav.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aizwys.cn/Article/details/gtlgugpeqe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtpixrgvxq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzwprnoa.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjcafdsb.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtzqcuyjwc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtufnkyknu.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtjygglorx.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gttbmqgebn.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtkqudncgz.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtibiyiphm.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtyhtwbunm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtweraiiqi.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtbhkowfsa.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtelrzherg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtdkxutktd.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtgjeehffq.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtdfwtesxd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtbtxmqknv.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtcxeukpgv.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtsdrzqruw.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtmmwngtsk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtmvntcvrd.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gtevqfznmo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gtyiyqzbip.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtadittkcp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gtzpcsdyui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gtvwmfwgmd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtjwhvyxxx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gteaiqswoo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtuzpopqwv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtcrmftoop.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtekwfbdcq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gtomqpzdru.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gtjqsmpqkx.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gtxngfbbsb.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtraiohkiq.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtvdrsywgp.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtfavnkagq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtinmracms.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtzsvdfrjm.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtjzrxthwg.html


<!-- 参考信息 -->