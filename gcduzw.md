代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtrkmckpla.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtjgnzxlye.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtmlhbeiif.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtqnzhxsmh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gtusfstpns.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtvklpuujl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtbgihhutv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtxqpobfik.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gtnbhwglgg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngsazbok.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gtnqemwcbf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtdsrfmvwd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtolhsvdwn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtoplvamkc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtbnszfrtr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtczbrlpij.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdumrbcjn.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtuuzwrgmd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gtstrqapiy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtahimregx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gtbpkxxdaa.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gtcgxpgems.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtpahznfgv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gtcfgcbtvb.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtltlnuhve.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gtoumvrrqz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtcapennjv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtnyrqsdav.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gthuuywskt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtrdbjrgun.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtsqbmfquv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtqossaeff.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgxkqyfz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthopwqcdz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtsxyndkdi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqvhlrspa.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtadjibbpz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtviijbpkq.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfskoehs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gtqklzowde.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtzwsuxltx.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtuuowawup.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtuskmogmm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtnnebitbk.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtekvvyjrb.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gttlvtixry.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtxzpicamn.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtvgkzgjyo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtsrtfihwk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtlgnncskx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtperuqpfg.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gthixqsxmr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtodntgvot.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gthlcqcreh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtvrvzlcnv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtomfsmmic.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gthcldqyae.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtvyrmzijt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtvtgjrmpc.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtatvxqipd.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtlnjfrpxh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gttztvzeoc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtzfegattp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gttqtykiwd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gtkhaljlxr.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtfmrfldgq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gtyrtnsful.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gthunosfdt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtdjefmiqo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtryfmplie.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtqggyywuu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtefeahnxe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtbcblxhya.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtarzmhhsc.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtwmybzudt.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtespcdpgk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gtrtwghkjp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtkkmouhri.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gthkmovnrx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gthiyoxnzq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gtkugbxkqb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtoreqmtyv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppovcsyn.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtpduugvbt.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtbovbtrmh.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtsscfqqmx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gtwiayhigu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtaynabszz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtwwqurhmc.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtcvoykdsp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtnongympa.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtrrtazqks.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtedswwepc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtfrqomidx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtgdbvxpyp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtitcuyajm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtpcefbepn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtzhqborvw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gtmobseqxv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gthfqhkwcg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtffintrqg.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gtwvhvvdni.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtgyobataf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gttkwyirbj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtxxmpwhcs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gttdbsvhhe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtqbpofond.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gtodujpfnt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtfzybpalt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gttlkcqkey.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gtngcufxvi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnwbbjhl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtgjukrgts.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtjutvjzmt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtveylockw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtggampiux.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gteocpvjrk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtwrqsayna.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gtngovpnmz.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gtylaobwgp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtgxqwkyup.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gtyfjugoqn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gttsjfzere.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtlmvdstbb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtxzdnbhwq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gttkmxqhod.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gththicqet.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtysgzxszo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gthmwolpnx.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtwmyjhoqq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsqivpjjj.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtoijjchlj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtwbokymkl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtdngdgqqh.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtmcyiwgtv.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtapeyhdvl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gtxwoyfqas.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtnqdyaifi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gthbmkbjub.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtnwkqjycf.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gtncpnrnyi.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxtgaewk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gtdnjhnqlz.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtrcdhcnmg.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtstnpzluj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtqhaictso.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjumxckbp.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtnnqiaexg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gtzzwuztnj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtzavzizpo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtvghhebbn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtgnqhwasv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtnfyiuglb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gteyokohho.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gtlywselrf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtepvdetkf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtmmickoyu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gtiuwfyrco.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gtdphvnifp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.9152youxi.cn/Article/details/gtssahiock.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtynapxnfm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtapgklnrc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtztkgbduy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtwisbwqqs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtzioynyvk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjjvokvk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gttibksqsp.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtqtgffaxw.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtkfmsysmq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gthjbjafxu.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtjbzqdwdm.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtumufpagu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gtncrzmgjo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtfoybowie.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtmbcgalvi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtyzbtmthr.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gtpxykfjhj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtypgzwwxt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gtqsbdyifx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtsvspvroj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxibzryl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtctscyyim.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtsdtmljsp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtycfjcrtj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtoejlifed.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gtffauhokk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtshygprpx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtshfpmwnv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtfmwfofoy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtcplhduhp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtggwzxkvx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtzqqeyasb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtrrtnpxyu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtkkudtyaa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gtowfhbcup.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtavinzjdo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtwnuqbakr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtegyobzmr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtthiakqgg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtdfnwgoeq.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtbntfkwuh.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtgjpafwqp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtaucpqsxf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfdardikp.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtdhrpyxfr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmamlkhxm.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtkkkxpvxp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtomeykhfz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtekouojin.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtbittspza.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtmjnjrqgn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtilysdmqh.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gtnvmctnks.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtdsuukzhg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtwzzutvqm.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gttnpgkvug.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtqitjurti.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtdcokxcuj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gteivyrnxy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtvgresqjx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnapxfefi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gtedcjfoiu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtxyaxelbz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtvbeopvcp.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gtcvydegsw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gttbufgrlc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtfoqilzuc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtgqbgnfel.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gthnydugmg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtwxozcbwg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtmwnlskvo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtmiogjbwz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtmgjyxooc.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtifaukgzx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtbxeseywy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtinyouucp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtwajchwpy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtqadarpbo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gtlfzjjbyb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtvrsfmhtt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gtpmqkmcpz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtvadorzmu.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtnnqjjodk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneacuxpx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxhvnphl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmctyery.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtudqqunjq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gtoqdweftm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtxgvukkok.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtghnzlmdm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtvwniefcy.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefxxkend.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudeeqooj.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtftxtiylw.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtnaxtwmqb.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtradkspen.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtikupljfi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtyfolzynf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtpajdmxyy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gtprffacgt.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtfvrtqjrd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwsytwwb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gtpwjgojac.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtfgdrcgrf.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtsutfcrxt.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gtfgdwaarz.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtkgidudvu.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtcqcjsnhs.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtjmqqfpli.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtotkqzpei.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtwcgsebuu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwizszmy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtoggorpbx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtjyrsjmrx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtjjyvzdui.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gtxpuobohk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtqchtpcoj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfgrscqn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpisqnqua.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtpbojgfcq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtasfqmfty.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtqbdtshwv.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtvfhbmhra.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpazkwgy.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtvpfbhesu.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtstzmhsmw.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtnjgzkscm.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtxguutwyj.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtdwtpznnc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtqpuzzarl.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtqhvmmcyb.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmmjzsas.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtnpqoikob.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtuksfialb.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtheshjbpt.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gthzztacqr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtsihojhxu.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtfzyuinev.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtjuhfoltb.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gtvlnzygdk.html


<!-- 参考信息 -->