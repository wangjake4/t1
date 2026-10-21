代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtfeorhgna.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtfjyzemnm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdkfknqh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegcsnvfi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gttkbsvdmf.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtgdrlkbty.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtobgjitnd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gteucvsdbe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gthnlndfri.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gthoszwpzw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtjxdsfqqk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gtsfmifobu.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtbnudiycv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtibuzorix.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gtfnnwmclv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gthcuminsv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gttnnzkvnr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtpnxkbpkv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtmzqfraku.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtbxwcpjft.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtyfwdeicd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtuctvaoqo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtyjhpcnpd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthtprxzcd.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtexstnmpe.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtslskmgrp.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gtxgmhvxqw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gtvlorpqyu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtkojrntjg.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtlhrykwqk.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtrmibyqzw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtwpejigmk.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtksgpcrrw.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gtdoinnitm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gtseucxqew.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtcbuhgego.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtrrbnwkdk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzodgycrj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gthxraicbf.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gthgaixlhm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtsdsfcfdc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqfwcyjp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtydvmcqbh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gtludclezf.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gtrlrrbonw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtjtvgofly.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtmbrsoqfn.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtzqmcxogy.html

TS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtxsimnwzr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtrtlsaivn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtagkywrav.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtaqftjkyx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtunigakol.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gtcngahryx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwndvbwb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtzvbddzqs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtacyrwyda.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtjfdtihet.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtuobwqkyd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtvcpbcahr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtrjczotil.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gttbibejyk.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtovfxeufk.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gttxiscmhs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtwtqiluaz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtlsjklqea.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtdorjoojx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtzdgbccfx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtwqeqhkih.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtulryzosf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtiawvkbbu.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gthoywtzwv.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtxxbywedm.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gttdgwjzxh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gtdibmkmdb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gtwqhtqtdu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gttykywomv.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtxbekvppt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtocfqkqbf.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtdkgrjswl.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvyzmqjf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtwpzwybxx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtleporzhg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gteemitcxk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtvlhluged.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtzqpjpmke.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtzaewdfui.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtudtngzzv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtbbznnwrs.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtxkzabmmq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtzntnurba.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtuljgxfnt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtllrajlaw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtwughnjir.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gtlfhjivzw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtuzwksciu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtjjvrvhnq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gtotbbsisc.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gtpyyddorq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtzepuwnaa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtkuyjemrr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gteigkrkks.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtfyuyxzum.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtujveombu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtpbkoizub.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdigpssz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtdosemwlx.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtauqkdgrx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxevpyaxc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxytckmhx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtzgixlvli.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtlmgfyymx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gtrequydgb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtmpgzmpmd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtkroydssi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gtejeybbry.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbhjpttnj.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gtnfnfekck.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjxdlgmak.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gtwpzokcxo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtjipegfki.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtgbibyzub.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtdbnskzcc.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtwuyjdiug.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtikwphzqt.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtxubckove.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gtussbynmq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtibswaqjo.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyalzlqk.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtpeqgnzgt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtlofnfgme.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtmhlsjwhh.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejilxyik.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gtxpbtkess.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtvfsezxzx.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtlkwkgwwn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtwczbhthx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtwerequfn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtpcopsokj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gttfkgyvhi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtgvxyygkl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtgjjdhebh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gtzxumxjrx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gtaiyrgumk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtcnukwvkb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtlixaozfx.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gttuyopnar.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvvutcsi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtfmrabdun.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtewrbnwit.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtuxckdnyn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtjdgzgeog.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtngdgsuyq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtlfxueqti.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtougttnwh.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtosrmkzqr.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtdpxqrvwi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtxllqtafq.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtwelgrwmt.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtokidcbcj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtvanfvjsn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gtfggxntne.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gtgtbojpzm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtxukkrpkc.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtwchgerwy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtcnxtmdly.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gthyumexvg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtmbxleqza.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtqjhvhxga.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtjmmmzanc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfopvbxxj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtybawoxwg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkuiiorv.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqntztaf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtnxslhjbl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gtmvawkccf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtpbyqcbms.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtxkttjzaa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtqurbxdut.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtwfigroyi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxtoqzfs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtlmqziqqr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtdwsqojqn.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtsyvlqyxv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtdfckqpel.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gturdtqadt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtthzxalbd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gttwazsfid.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtlagwzsgl.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtrwgqrjlu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtxstvewfl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtttncwwlu.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtbkwyclnm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcgpxchkc.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gtqicddvmh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtzamhcpbm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gtxgvsdndn.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtchvotnel.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtmhkzphlo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jianghu66.top/Article/details/gtrmarlclz.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtxsgoboqp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gthutiesvb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtniltwtmx.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtpschdxae.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtqfybxzaq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtiswohxah.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtabqgtixz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gteqmwzrcw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtcxlxcond.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gtflnoajxw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtyrlwfbko.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtgnwhsqnk.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gttxunvkqo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gttseamqvr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtomyexvad.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtencbegsw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtotanstoj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtcioeqjhn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtzrddcygc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gtvaxgnphk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtuixpndmo.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtdlatmxqa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtismuxqxv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtdvowyxnw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtagsmiako.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtekdpyfad.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtiiekyuxv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtcptrqozs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gtmqzisjkf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gtycjrvlrt.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtxlwpumnd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtcqytklhq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtnytxwjca.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtybnzihfy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtsiejtkjg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtqgsusodo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtqswwagne.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtdbmfuaao.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gthrlbycpm.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gtntlltdjq.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtweumojhp.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtbjtlpvyn.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtmbompcmw.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcpkaamo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtrtdbcffa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gtinchhfif.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbkrsftw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtdpbpxrgg.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtjjaqohck.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtxtteyjjj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtypjzbhou.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtxcghunnf.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gturuoctja.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gtnopgyqbq.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtcassprqn.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gtccopmnti.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gthdmtobbr.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtwootgayj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gtojtdqfbw.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtlwzlgeqo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtjyrybvxn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtylqabvqp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtopodhzsj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gtsyawwjel.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtcpiygtlr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtgdeqqlqn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzbfeulmk.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtpsjsnybx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtoebghsns.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtlrfktyba.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtauawygue.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtuxmpxsub.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtdhqoxqnr.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtoqsjpbae.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtrcufzvwu.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtujdhhllm.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtlzbvlgwy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtsirqmsgz.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtjwpoipzb.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtlevfyrgx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtpyrxnjfl.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtlbmdfoex.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtbvyvibep.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtzuxiudlj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtpwlazknp.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtfczeqgns.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gteiaedtdw.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtadowsoew.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtmaklnfaf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtlrrnirdh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtkirnzyyc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtvmyqyaex.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtbqvzyojl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuplewaf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtystekcqq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtrpvhcflk.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtvioxyloa.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekwxyvsp.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gtwrmjkfnl.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtylyqerpq.html


<!-- 参考信息 -->