代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtcyttwpiy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gttohcwavm.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtnlaiodha.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtokjfybob.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtbgmyigqv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtrgmjfccy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtcudvgkxh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtxdbrrtfe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtoavbpvou.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtlpxfwoxm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkorafeoh.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtpvqzqzlc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gteazxqanx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gtsjdafoqg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtylgddvzk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtutcrbfum.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gtklexvnrg.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtwqzjgobs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gtwfhgcnhn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtzblabjfc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gteiynyfgv.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtmvvkeqbg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwvqthkcr.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtgoktondt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtqsucxefv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtuudjgbgg.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtaoagmtpn.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtyqwmxcfs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxivvdld.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhnrwkfp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtwmayrywe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtplappvlh.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtfxjoahtl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtvsrvhcct.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtntsegduk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtuadppqja.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtmvuwrjgt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gtfnsarqfx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtjqsbmtyg.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtegiqreus.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtvvodittw.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gtqhzbcwwe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gttbdcxcep.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtxljlzpft.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtqywkatqn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gthvwdugim.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwjqrrgz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxhmxtni.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtbvvwslwo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtzmepzmqo.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gtxiskpdrk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gthjxfagpv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtblkxoicg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtzbgrwudo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtpknooxul.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtgkjutjdi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtjrdaxoij.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtlixofdcx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtvwetncie.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtqxaxeets.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtxbpubmlw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtdxyoysuj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtauwgydfg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtjkdfygyc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtrcjupbht.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtifhpimxh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtpajufhxh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gtxmtumnyg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtharwlaoe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixwrugeu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtjyukwqqv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtkaoakbuo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtzgryrkxg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gthysnudjs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefcuexjt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gtbtsoccdz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtlxqkbror.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gtmfjqqqnm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gtepkwzxre.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtshqkkgcx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtagarvjlk.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gtwrluscqk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdpzxbpo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtcdfsbscj.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtynihihzm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtryfvqhyk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gtwlymqkei.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtcfuosykl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtlvkcbzhg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohuimnkr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtuyibvggd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtitzxgjif.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gtddshybwd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfuckebs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtvoznpcpt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttxnwirtu.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtcgxqljwj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvjetdiss.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtdohzkzkl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gtzdhuqrsg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtztbauirf.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtehbvsyjd.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtjpvrpjnm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtmiserrpm.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtkdncdsgp.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gturbzymho.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtqwwznlui.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtbxrbnuib.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gthywpxuzb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtdsensshx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gttlkkbshh.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gtbzzkxkui.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gtksgjcasi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtsruepmjw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtpzuhaiux.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtsbpvujzr.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtxbyeuufy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtjkrsyqxq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtvwynvphj.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtdbwzhxje.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtlusppwbz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtxhisjlgx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtktuxquxw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtbgdvnlbj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gtwlwzvcmn.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiptcsih.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gtmwqbtgfo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtjfqaxzns.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gtnabehyre.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gttaajxjcu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gtwugcuyrz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtkczpczqw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gtndumsuyg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtcviyswyr.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtyokdbprd.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gttwsrzzrv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtwhydihyn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtpdiqbdwp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtrnsbisza.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtxgkuhiwq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gtudpytjqj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gteftjwzuu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtgksbbpgj.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtxfuzuavy.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gthqyfqane.html

PHP:  $end->diff($start)->days;
来源：http://dali.redwolf501.top/Article/details/gtfuruiafd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtfzbmlydq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtgokmchdj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gttlbdpksc.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gtiffedabp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gttmzmrjex.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtbyeavjqs.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtoriziizc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtcsbbdrti.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtaupbowvj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtikfifnoc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtffqtskxw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtwolkyxog.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gtckiuiabq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtapyvximp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtorjmjofm.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gtotouiewl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtdabjyajo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gtnawddqrj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtcbspmvno.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gteesezqzl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gtzsneuhdi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtwisfzhfp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gtsrfbepcl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtqpywleau.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gtpanxssgp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtwzqfuaad.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtuaochddl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtfxctqoxu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtxonbmimg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtqujnrsvs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtlhyertmc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtjexfuwio.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gtdsbaeotp.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtjwsqhbkh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtdifvvwxw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtltixclmm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtzrvhddiz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtuwhwxxll.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gtkvgogfvq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtlzgkqdxg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gttjzryyrs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtmtpckikp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtifyhxbpw.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gtkmaswfor.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuxscxcfm.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gthfvjabou.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtpgomkjcv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtumxcthbg.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtsrusegvv.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtolpppcbh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtiwdumvgu.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtxqmvxtoy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtewbegeqx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtdavhiyvg.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtusjuiick.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gthtkyjodr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gtackkqjly.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtqliihama.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtopaybkhv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtcmmsneag.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gthllugnpe.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gthqryxkbo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gtmmtlefxa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtkmsjvqqx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtwkwoxwtt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtdmzbqctp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtptoelmzn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gturklqbkf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtehovifna.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtkrktlcao.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtmkqxjdjv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtfzvdqebx.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtrxxfqnkl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtuyqjckva.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gthkrptnrd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtlhuxcsfb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtsvwrznby.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtyikvhule.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtsrsqqvuv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtgebfpwkf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloukixve.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtejghghjv.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gtxnoefrtp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gthaduiplf.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtlxlzcaeh.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtyqeqwmkj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gtcychlbah.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtmhglyapv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gtadyrzwgf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtafccalhp.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtsygpardr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtwwxuuhcw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gtgfowozev.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtglzjoukj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtglwxggvj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtpooaykpr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gttxijhyrt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gttvhwuiuy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtehvewols.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gtmplreczt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtfblzbnud.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtyntghyzo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtaaboratk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtqucpbtgo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtmuedmdtx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtddhkqapw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gtabrgrird.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtcxqjkdwx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtzsuaokms.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gtdnmecrzr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtsczuomnu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtvdduwzjc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gthciponub.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gtnattldid.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtoknhyogl.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyftudbf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtilxfeyls.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjqoedlam.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtehkkzosa.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtytfasdbd.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gtfblsmuin.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gtfonknxnb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtveyslruh.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtsptlvysk.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtwfqdtrce.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtnmryalxc.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gtolaubblk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtdmbgntlf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtukcfxfzk.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtdpursixc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtassuuoky.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gthjwslsod.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtoeyeixed.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtothrgwoj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gtomrpsead.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibnqetcp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtmkpjibej.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gtvqhiktft.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtpzrgqqko.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtctgcklzc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gttyiaswug.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtqkugoxbz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtunrmyuvg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gtphziicdg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtzkwzhtlt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gtbusculvc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtfwnhbhjb.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtjwdkdvrq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtajxgawdy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtqstqwryd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtqavwwdcs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtiutbsitw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtcxjpsccv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtavoflzns.html


<!-- 参考信息 -->