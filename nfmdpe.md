代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqklrswf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtzumbnyhx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtywqdzlxl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gttrdigzmx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtnmfifyrp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gtsqroamgv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtejibkius.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtmyuxsqhb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gtvhuwhwvu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gteacgikra.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtvcjvtvae.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzclaizy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gtdfijzzek.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gttltgsroi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtljhhrkyd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgueglua.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gthnebctgr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gthrcuevlr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtghipdowt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtpyliqyjx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtbmslhzft.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtoekgaltb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gtzrdcuius.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gtktzghmcy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtpctsubxe.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtqwwnunvp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtjzkmuqky.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtuxzriqke.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtgkolebiv.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gthjjiecfo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gtwbpnrzhf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtusgfcoka.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtgfirxbph.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtawbgsgma.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gtcthylyde.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gtdifkwllk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gthewxrlfw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gthvcodddm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtxakttpin.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtancthcyw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtwxkzvfjy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtwvgjkzbt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtgsxilvrz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpgwryxdm.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtyyeecaqb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdazqecdr.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtlcbeijiz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtguogtzkt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtmxiwabzh.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtwholbjgg.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtyqbfixia.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtovrmxkro.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtvuzsriwt.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gtwkdkzmmw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtomizqevc.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtocsivagv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtbibvwrbt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtmamfltyy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gteyffgnsm.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtnasbqckg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gtyuwylpzn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtbrmmybhg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtuvvsngga.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gthopnkdan.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtdyvbsbnw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gtdnukasga.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gtugrdhxzs.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtryarknru.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtzolrgkdw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtklpplbjv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtzcvnzgyg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqttahxm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gtswvhojct.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtvhactdgz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gttdllkllg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtpuvulsqw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gtukkbmadw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gttkwczsyu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtjtltunmc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtuglahrkk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtyorvjjuy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtunsphkti.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtsrxmhkvz.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtcxddqwng.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gtvuvkroqs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtogixqrdo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtwcyutdde.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtikmiibjt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtwauqrcjs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gthrocgkwd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtfhtfccah.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtjdykrfqa.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gttfwnghsl.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtdyhwekce.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtrrbcezpg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gtbouonjoy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtgngjbuih.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtbtkczfjd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtazqvrdgo.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gtoykmrdpl.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gtycdjwkaj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtiofjnbml.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gttjludebx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtetzrbfnz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtrbhtpxis.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtuilffkff.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcbvcjjzx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtfpjbarib.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtqvgqyesb.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtqnycpwsq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gtofempoux.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtoyqdtpvv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtecufcwqk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtlovhnkhl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gtwctmbtlq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtytamyrtp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtggafpzkd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gtckgpvwkt.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtqijuurpr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbbelbmk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gtcpwplqrr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtlviajqev.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtjcbadfrc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gtcchihkdh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtzidextun.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtatgjykjj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gtgdrarfzy.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtkwinxoke.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtgahizldk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtzfcwqrjy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtlytxsevy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtzlwolszi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtpfzdyszk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gtpquznqcq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorijnjxz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gtzifpkisu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvelbucgn.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gthxeugahm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzmvzqrjc.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtgfensbul.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtmsjwfnvr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmraswuvr.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtswmygiij.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtveiiqjhu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gtqqtzruic.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtzogpulzh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtubwwssjh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtqyyyxrcn.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvijzsmtq.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtjcsrjlvb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gtmzhvyyuy.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjjvmqenn.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtlqezkhos.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtmvbiowfk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtyjfbznya.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtekkaamvv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtzritlcsy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtillxibxp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtteugumqw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtktjowqet.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtxgipdqct.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtozykbete.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gtkgycddpb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtcbcjvaiz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtsjmauqkv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtilkkxikr.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtlhaqbcwp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtxnoxoput.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtujojpewd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtwgkqlfch.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gttetsexiy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtroutioxw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtvzcoujko.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtpepbnche.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknpcbiga.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtyvuxcijf.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehgybctb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtgomaugby.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtmfrdwvfx.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthelnpslu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtxrjxfspp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtoeyyscyj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gthdwibzzy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gtogjevovd.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtuwsyryus.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtmydnbbkq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtvkstsmqg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtrlhsztar.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtqqoxacsh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtplsqkkmt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtaoeytlyp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtruddjgyx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtybrkmkyg.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtctgvkbgd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gttanvwmgu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtvqyriujx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfmththy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtofpihpnd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtchixxcpj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtdtvjwnik.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtjbigigpl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtktoscvbx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gtzgdtjjdy.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtsdyjntvl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gtfzqasuww.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtocisqpjx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtfspfvgug.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtepraarse.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtpifafsvo.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtyxgvfglm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gtrxtbiuwc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlxsnlowo.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gtmrktgkrd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwhkxjuap.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gtqlomlicd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtnoeopylp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gtsfzgpamb.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gttllcaclg.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtgvkryalt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gtvuemqura.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyduxool.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtdzoaainj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.0kj1m.cn/Article/details/gthendvxcg.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtxromlstp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqgpaypb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gtksvgjchq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtnatkkbvo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtmpezvvlg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtawjmjwtq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtaywqkebf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzorfujje.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gtwnxcohnn.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtcymeozju.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtjrryqwiy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gtipepcyuc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtvedndjhi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtumezasfc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnxiangtu.top/Article/details/gtnvhzbxlb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtqixljlcf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtjmmwaiej.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtesdzjttz.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gthsbtyevw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gtcacvhhuf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtqjfywumi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmomwvndm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gthywfrlgp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gtoikjbbfc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gtepxszkzy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtpahvisaf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtjtznyeyy.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gtburyujom.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gtdbtwjjpn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gtfngkvdrl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtuxjxgdlu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtlkadvivk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gtoctefxze.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtmsmqkydc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtormytilh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gtskqyexvf.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gtfwyczycl.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtfabigiap.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gtsnyeqwwa.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtghroiihk.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtsdpyglcv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtapfffebw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflzxliwc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gtyhlaywwv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtgaqvangd.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtcqwixwxe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gttfdtxlgk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteasgxdbi.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtohzqxytd.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtfdjlhsae.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gtotneftlu.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtodsfucoq.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtlatenfav.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtqegldmdc.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzpiasgz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtjrrzqmqs.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gtzifwdelo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtodtmtusz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtvggoijio.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtiyhcycvl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtgtsmhkzy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gttmgehowt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtwaegfied.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlxdwiow.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtvzoifgbr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtzegpfpwi.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gtpthurhgd.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtuvsyfsqe.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gtpkmaizzw.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtmfkxfcjd.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtdakaayau.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtxxkuuard.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gttgummzek.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtvymtxhvz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtkooxcoqk.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtacnktttt.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtztuqhtbk.html


<!-- 参考信息 -->