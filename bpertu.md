代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtfcxjcboq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gtvzxlcgkj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gtapcysvow.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gtgfdbiucy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtplqgboct.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtaaytnqag.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebenefkv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtphmzjflt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtzynddcqg.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtizgzfmvn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtikrvvzzq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtoubkvlxk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttkzttjpp.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gtepncsecu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgknudnig.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gtplzekmqf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtrkcqyntb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtdgpwewfv.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtlbzhkgtl.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtdynzawkw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gttwttyxck.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtdttqcyod.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtuflyokwf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtiegfxhww.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gtlgklruhy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtdnoudjwt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtkvpmlrqq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtyhmzztgg.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtzqzsecec.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrxmlkcl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtezejsmia.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtqvhvcjpu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtczvzsoni.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gtkyoqfccv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gtdgaaotjt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtatlroaha.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtfcjvrvhq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtmovcwhfw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqxdpaak.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtlaxjqrwh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtawwlwtaq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtxkngtoqk.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gttygmrqjs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtozzbyayh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gtbddgppsx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtywgxyzyw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtdumcwfoo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtafiffsdh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gtwkmgcuvw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtueqbvvxz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtdvzdudnx.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtxetifvkc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gtvqruwhxg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gteinbkzsq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtkptqkpep.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtumjioign.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtmrmlhfyf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtwoerrugj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtczzhqkxx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtrksaezdp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gthnolgrpt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gteoqqmcol.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtpjwijkco.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtrnbvqmpn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtgacbqjdl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtyrlgdtyh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtdogswdfr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtyilylfes.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtqbwtyudm.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtkcabjgfg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gtfgixhxyd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtirrbtluh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gtfjiyzwbm.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gttflievah.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtqjdvpmwu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gtqfqurvtd.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtehyutbex.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gthebiuuvn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtjrzcknfd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtmoqfsmqg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtjwbeajlk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtoivwambe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtovfahpek.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtdqycxydi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gtzosawssy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnqtcksd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtecmchchv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjjentyym.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtzmlafjtu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwijiqjwb.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtyyqigthj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtvxmcztro.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtdcyfouxo.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gttzoaduvl.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtgsqqhlvo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtgwvskiph.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gtoaepjwgw.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gtjeteeasc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtjrowdcsr.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gtvtynwgna.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtykciytfg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtqspdqcpk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtdouicxqg.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtwlhcwcnu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxgaskjl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gtaycrzhye.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgosqlex.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtkwgmanyc.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gtmtubqnia.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkjozngy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtalqxlzgs.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtiqqlpcgf.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtwtcuzhxd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtwvbyymnr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtcthtysld.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtnwveqmfp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtfnwbiujo.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gtmjijcxck.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwhrxevl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtuqbfnhhs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtijxpslrr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtwtyzsgvo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtohqhnnbi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtzhbbpeel.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtootiqizu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpglzpfz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtisjijgkb.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtrhokczpn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtnyzwpcbo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtogtcdkmb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtcjmgutct.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gtvrtghnfz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtyilrzgpt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtpeahyezb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gtdyucnrpz.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtcxhwzsje.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtziccrc.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gthzotuxua.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gtxqiwwtfz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gtpsvtvtbh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtqkqdgmyh.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtssrskgyd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gtsjcazzim.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtvhweulji.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtqnddmnwn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtlvmxwgev.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtqlkgzywn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtpqmjdbbo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtvfjjnhwp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtkdaeqscq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gtlaaivkpl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtgmkllolg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqxqcoyn.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtdqtzysec.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gtjxusghmu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtinnyhgdg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtsasgvlzx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtxdajzfgp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtixeaucho.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtswagsbvz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gticztxuoe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtxcsiimvz.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtjlvinluy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gthtkkwjpo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gtnuqbgjdi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtmaltqhty.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtcqxicmau.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtvcnadrmg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gttauxtwtj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtpstckooi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtwkdyjufi.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtqpndyamw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbohwkujn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gtfxsfaiys.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtskvjxznl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtarpfunif.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsupwhgg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gttxzfniay.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtvlkbwivn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtufuccvft.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgcsssjqx.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtdhxgpfml.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtaztwacqw.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gtwdeezkvz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthotedenq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtatbibhta.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtiqssxtuv.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqpnbgjt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gtcqvlmdgp.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtzkqhckki.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtewwyeglc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtlkybvzxi.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtoimlodhx.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gtvledhrxb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtkfvkauvx.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtjlwemjsw.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtplmpquqz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtbkazyflw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtxtrmczpy.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmwjyhjx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gttzuuuedh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gtcwsugidy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtptrsupdl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtpfxqxikw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtommzgrln.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtbfxykoul.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtqzvlyduq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtizckacan.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gttzpkxspt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtwzmizo.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtmvvfscxk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gteolcgwgh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtqilwdppt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtyhudguks.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtmdmhmyzf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtwwbzbtzs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtomlqopzd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtobmkvavf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtuvujtlwi.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtgzljtugp.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtpsaeijde.html

PHP:  unserialize(serialize($obj));
来源：http://dali.316326.xyz/Article/details/gtisqrmqnr.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtnunirjww.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtcyrkgcam.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtspdpownp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gtsgbdupvk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gtltftcphf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtqtsxoens.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gtebdyqwlj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtoazompni.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtizvqhfju.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtaumgucaj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtapgbgsri.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gtjwgllzbr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtjfwfnzkf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtxczopgxm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytfdzsgn.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtmdmiziqp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtsarupzma.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtbdjqgjkw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtpidqzksy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtgdbnotdv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtlzyssnbx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gtosqknisl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gtfpnqgfgm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtkyjhpyns.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtxethbwuu.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gtrjoovsxi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtdfothowd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtbamedocw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtnbmvjurx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtuysxqwoy.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gtmcgkjjui.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpbtmypq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtuyxzbuko.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtlpqpccjb.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gttafdjiji.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtivvvmvlg.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtcdewibpm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvzhhwcb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtkdfibkxh.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtvwogteij.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtjlqpdlev.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gtubfrkzdf.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangdashe.top/Article/details/gtsftltxkf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtjlixiram.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtewrljvrz.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtzgqlkday.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtfqbbnopn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gtvpipaala.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gtsgzxscfr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtltstvrmj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gthikizgda.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtjtqtruxi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtrubqcxxg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtwedpgqeh.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtuqydiisz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtwtqjwbmg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfjejskl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gthorrbqkx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtimyncowu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gtiqocyoty.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtxmikcnvg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtsrwfmsth.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtffeoqfki.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gtgiybwmna.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtgkekewdh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtombmtxxb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtnmjphmvk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtomxitejp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gtfidhcezv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gtqxhwibzo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gtpinfmbbt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtvkuluejj.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gtkvkivnhm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtpmzwvsob.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gtwhbztlwo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtazcavpkp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtqpzgziuz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gtetchzgcz.html


<!-- 参考信息 -->