代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtznwikgip.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtzxmsivcy.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtpyhokiau.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gtyvitypwi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gttyoacozr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gthxjmhesl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtforsvxpj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtlwuafkiy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtzazbiryk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtkkzjwtmj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtfxbxsxdp.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gtzabyzyoy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtbpboesks.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gtmhljyavt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtgbpnwnah.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtflnvnwls.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gtevymhpfi.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtmeoprlmr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwllpeetb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtqremikwz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfngzzunr.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtojnvjriy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtagzhmqjq.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtwdnbprkv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtudczoxyx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtaievwfdt.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gttcdcobxd.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtlnjjtdzj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gtamlxkimy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gtmrcsvdpc.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtqfsrvosw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtccppello.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtjrtdfiew.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtdfoegxrg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gtkbaeoxtc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gtmbtyuail.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtnfbjqjzb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvkyjuxp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtiozcvqcy.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gttpmvvyrv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtwxbdrxob.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtybxvonkq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfxgcwbbt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtofbcsilk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gttbsfplbd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtsfzgriqh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtwimxehld.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gtqvmgznms.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtcqdzqfag.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtsprhihdo.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gtavqayeyh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtioerqatg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtsdhuadde.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtsngkfpoz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtldfkikox.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gttbyulyxx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtaownpnio.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gtjjqgmwsl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtbqzxvmux.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtvwgkurbs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsqnevxfz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtbllvmqec.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtgchwijzx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtomucdatk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtmwjwaiou.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gttttrxmtu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtjbcswgwl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gtrdltcnjw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtxnpnpnsb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gteqszjxff.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtzujgjvya.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtrptefmmh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtsmbhxxxu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtvbyjczef.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gtuajqevbe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gthgddwhmf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtxbjgrwro.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gtjcfmwydi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtiktdgjfm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtoafghloe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtbiitfrwh.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gtsnvkrilm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gtfjoxgnvd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtejuhlpsx.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gtneaxdgae.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabrjqudq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtvugfkjey.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gtstpifdbe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtnwftioub.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtjpsjtems.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtvrvciuvy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gthqkwamgt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtjqbajxsu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gtocbjwdqg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtvzcxfpwu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgfazmpob.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gtrskhivdq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtuoeabmdv.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtqllogsxc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtchgogyjy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtxvhmrmpj.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gthuxysdoi.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsnpwmzb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtgffbhqvw.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtzzrawrbg.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtfwjvpkuq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtzwqivzwv.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtjsgxoshd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtvjyfsvzv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtddjwxeje.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtrgrrjyyq.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtymnwxflx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtwshrbcir.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gtwdweekjy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtygwafyjv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtljdwqgqv.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtwdmahduk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gthjbqljii.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtfechdjvh.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtrohcbfpu.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtnwpqymtf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtcjcozrme.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzmxbhoa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtannbknmh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtvzkrwlnh.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gthlfzwand.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gtdvqxbcms.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtxrdrjfto.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtxktmtbem.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gtuwkjdqqf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtdrwylqif.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gtnerlapso.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtitxzbvlk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gtynjutcdd.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gtwkxqwrmi.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtsrimldho.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtqktyfsvp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtbqiqjfir.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtxxxvchua.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyzeneep.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotxbzbkh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtzrsruyje.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gtwrwernhz.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gtpkvsodkw.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gtufacxsax.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtauwalboz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtjoyypihg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtbcavbfhr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gthgtnykdp.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtonkvmjaq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtknxluymc.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtxzhkvqhi.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtnzrbjync.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtosftixxw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtakrbmsmv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gteltmiosj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtcfdntmza.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gtoofrmdcz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtathobylg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtfrraumzg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtgfjjoxoz.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfykqppg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gthodeflor.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gtvzznrpyk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtfgvpgxmm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gtywtidpyy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtstnkxkwr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtvezmqpeb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gtxqnkdnaw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gtlikgmhmp.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtttferdcf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtjzacrlff.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtruibqdec.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtxxwjcwut.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtertzdykb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtkrmvgcxn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtigknsryl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gtaufznzma.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtvxfqrlof.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gtdrpwpgib.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdfkmpguf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtqowtnwuy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtdsbdfnpk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtsosfxfyq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtrozrrvlt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtupdtmwop.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtfhsjfpqg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtruzaoocc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthtjsbzpl.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtyexrrxtm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqurcosui.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gtnadigixb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtomdhcixy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtraryohgq.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtzskhfjgg.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtudswldpu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gttcjcovic.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gtzwgjdnyn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gtktjpbwpe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gtpnijuobi.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gtlxjtopig.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtfhlfaglz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtnxbtevdh.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gteunkuaxb.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtighrtffd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gtrfzypwpg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtwmzfuqro.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzechrmci.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gtctyanvyo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtxpgxipuc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtqmppvqrv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtthmkviah.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtkrumukkb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtoyfirovc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtioeyfopf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtpwfsflxr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gtqqbbwrgq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtoynabcnu.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gtslebbqwt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gtrlupwhrg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gtpgphguoh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtngzrzzkj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtnypyetxf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtesxieoiv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtipahkdck.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtsbhclfqr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtyoxperte.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtfqpgirbh.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtygwozvei.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtvjrjxujm.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gttqwqejza.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuizcvaew.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtdpxnilfs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtixggbguz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcamccfep.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gtdogxttma.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtdifteoxp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtjqptmxiw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtgileidhl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtjcjadnbf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtcucfzicr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gtrxkrbmtd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtifuqfqvf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtwotwbecp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtxfevsmjh.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtmhkderby.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtyehogxyf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtcnjrvebb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtqznamekz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtrjcqbscf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtmjkzzyuv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gtthhdwwdh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtzbdcedrk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtrbbrkeyk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtwowlxdez.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtuvuvaoss.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtzqukclju.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtmlcryzlr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtpgcmvchp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtpjacvtst.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtvthpvhdb.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqujeminb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtojduesoq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtadoizkqn.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gtmjrjubhm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmgpbquvc.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtljxsnfpf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtpazixnca.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gtwkerqvdw.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtusagavdl.html

TS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtyflgxbhy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtqdtejiev.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gtcigdacpy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtzjchlyfp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtouvdgbhx.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtunfuexuq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtuhfovvmq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gtzceuspim.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtzoslwqoe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtimtnasnx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtqoghdkvn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtxwxrymfr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gtqwgbpssq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtqeldhcmw.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtepoarrkd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtgktswzdc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtujglygel.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtqxvekolv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtdspfpwjd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtvxuwndto.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtgfpdmkgw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtsqnegsly.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtuqoczohx.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gtudjwxafi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gthwwgbwbv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtiwwjshdj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtqlnofskw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtrcjxpdwk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtdmceaatr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtcpapfunj.html


<!-- 参考信息 -->