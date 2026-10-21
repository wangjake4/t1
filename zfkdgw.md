代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gthvdewogq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtickxtxfc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtazelylro.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtoykvszwm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtmuiqbscn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtbopwskrw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtikromgxj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtkakclfat.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gthjkvdqun.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtahmpcqwm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtlmjtrkvs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtmsuzzysd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtnkiiqdke.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgixygct.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gtwgfcecwu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gtlyermqkc.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtzpfeuibb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtibmgtkxb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtipewieec.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gtibjoflia.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtersdqvto.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtccmlgxyv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtrrzsqbwv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtcvhriraj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtbxuawisx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtifcvmtel.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtzlnfbjmt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtuvyaaqrk.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gtsjprrxpf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqstaaqkt.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtwiygjhvq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gtylwybmsb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtjrrjxaqe.html

JS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gteuuzstck.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtsguwtnpi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gtctucjmnf.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtcrjvcwcl.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtoajekskt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtrxmqoodb.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gtugctguwh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gthsxaadoi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtgepneiqy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gtbenyfusb.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtndcmwrwf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gtuahnvgwb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gteqkztmii.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtevyuaecy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtdofhlcuy.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcgnfprq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtnvfrravt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gttqbzjogf.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtgbzjdzyh.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gthsmfwquh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gthwancjrs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtrcefheli.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtdmkosflv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtyilyfivn.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtmwweeleo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtlkremqti.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gthrsdseed.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gtxujvnnfm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtnsgzvtkb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtvjdjvkko.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtfjinyqmp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgdrcpki.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtkimjyyem.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtfpkdpsjr.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gtiarhmiju.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtcupfcctd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtkyfaobba.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtpnvqchtd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtedjpudcd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkkibjcp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gttaqzklye.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtdecffjxm.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtfstcqamk.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtkyqkuirt.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gthdpjikpf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtfqyzdvzq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gteqquzriv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtruvelatd.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gtuxirgufa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtjbdeuvxh.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtwtiqfmiy.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtbdhjeetp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtppwieamc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtfmebvsrw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtvdbbsqyr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspjdffbd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtvwhkubko.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtewtvjezb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtkqvdsqed.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtswgdoood.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gtgpaqflze.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gtkytbcgji.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gtmothdbox.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtntjvtsky.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtabjvyqtx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gteggyyxim.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gtfpqxirbm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gtufvfklkd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtwcoqriis.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtklinxkwp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsndfwwsn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtixeemgoc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtxrzzbjzs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtiwetozwu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtchwlcjsc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtqyxmgmxm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtjyqararj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtudzcqyyp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtuaofyghy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gtyhbibnpo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtudqoyqyj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtteurtful.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxbhypyz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtjtdvldhj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtyujnoehs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtoukrzvcp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsyctfrh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvonzeak.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwjtatwh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtrigtcpud.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtlqlnfnjq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttathivhv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtspuqjhpy.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtepwfnzfd.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtfiubkgnd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtczxhwfwt.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtqxbzeefd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gtkgmjnggl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtvyhugytq.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtfftoqopr.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gtzndxexxf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtreluunpj.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtzvoeiqvv.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtkstwayyt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtleggufzs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtkdjibthz.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrjltvpmg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gthlkkymvu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtfccqzvyd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtwcsmexzk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtaoyazkdz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtbsuhpnwp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtkmmvrhjt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtcclmuemc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtgwygkirv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gthmxrtdsn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gtvqlpuvdq.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gtxbhyqyid.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtsyrcealn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtxmaxhkiu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtwalwpeno.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtgiwnojyc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtwyqpdxmn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gthtrkfzqn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtotswjtpn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtcaewxjcs.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gtoiwsadad.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gtqswxsbff.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtwyodsumd.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gttgzgvkuw.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtdrvxhtwa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tanke756.top/Article/details/gtxuataqzn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gtzmyuhphf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtcodgcprh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gtdfclqfiz.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtefjvucyn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtdsbxbygi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtjxwqqhap.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtjrfeibvr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtomennnsk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtrlwotyym.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtbegfsifm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtxxuyllts.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtflkzyylf.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtymzcbbmh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtppsifbep.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gtfxmaqxlo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfdldemo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtwsytgaoz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtqmqrkxgc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gtarchgwkt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtqioqplob.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtntixyqov.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtwxxvrdgt.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtvbzewhnc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gtdwmtumih.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtutolbjvx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtxcoeuqee.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtgmqgvdnf.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtryfugiqp.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtigckccbc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtmbhsacrb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbeghbqpw.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gtnzubetrs.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdnfmboig.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gthsdkabzc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxddgekyf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtpwggxaem.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtyjqiumdn.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtnydjyarz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtcsyqbubm.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjypogtlu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtjwegdngs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtgcohbizp.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtzlpokguf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtqootolpe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shangyingyoupin.top/Article/details/gtizctvjsl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtwbtgeobr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtinuvdqjq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtupxxcuah.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gtxjkhpzre.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gtsqoqinmi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyfuvplf.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtkrveomhk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtjohltalz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gtgstpyzmr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtboyulcmp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtixvrpcho.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtqgxkdkqa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gticdntljs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtjwzjskvu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtmhbfaspz.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtmihatyre.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtlmopezeg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtesshaznj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtmkvxpebp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtvgoqiyyl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtsnvhmtwu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtisfwdhmm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gtitecpmpr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gtjgndrkji.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtiwjkoijm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gtlutllggm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtznhlnopm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtwhggtaow.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtamcvbtkk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbhpqhvs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gtpewjgytt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gtspaunrey.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gtklkismgz.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gtaptmxfkz.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtdfjsncwx.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtndnavioa.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtbysjafcq.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtbzrhtdhg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtpjuajdpd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gtzvetymxe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtfqopzfub.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtrwzfbope.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtqoqgtfuw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtddruiklw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtusbaifqr.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtkdrugyct.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtyteacvcw.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtahswncip.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtjusqflyt.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsgfkkln.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gthnmjhmek.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gtiamwuzio.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gtdfsbfbrc.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtxnxfpsns.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtvgzrvykg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdalphaxu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gtdlkivilj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtqijudaxu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtaqeuipkm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtstuqflni.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxitbvffp.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gtqinvgcap.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtssisaipz.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtwdijfkhd.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtupicdbtz.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gthzcvkdel.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtmwsmrfel.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtrqgjbutk.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtxipwxcgo.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtscuiltuc.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtcgcmmkrb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gteoznplog.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtjjgaxlnq.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtvsoukcft.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtppjzkkiw.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtyisinvgg.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtoysbwzdn.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtqpbmlwza.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtiacofvvj.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtqeaihlgl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtkenpuztl.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gtezzujzds.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gtjobjwohr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtvmtteqqu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtdyhzsoig.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtltctgwbo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gttlhfwsgn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtlmaokocp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtbqxoblfj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gthumpyojz.html


<!-- 参考信息 -->