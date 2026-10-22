代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2xtvwnhvr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gt2wnxpnckw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2zddlbfft.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2egintklb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2ehzirxuk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gt2blebujwx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gt2waiwyndc.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gt2bbjtbrhl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gt2yaljaust.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gt2mfgwqcaf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2gysulgdc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2nfalnijq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofmcuout.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fszgdcjw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmwvbktl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2jdvjxzyj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2xtrphsut.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gt2lynfhlxx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2qftwjsvf.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sabxcfhd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2qokumzhc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2wirgleuk.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2skmyedyl.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ratdppli.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gt2fhhgrxkf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gt2nhhtibpp.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gt2jbbefgzn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gt2puzanbhm.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzzgtiil.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2pnkmtczd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gt2wcyijvsc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gt2vtchmlti.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gt2spbezrer.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gt2ijmdeooo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2sotzvnqn.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2hofmipqe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbxwstgy.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gt2mggdwxnj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gt2jrkmkuho.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2agoprtdq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2agkrkzga.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2vjckoskp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2txbhozuk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gt2siedqvzk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gt2cbaqdfen.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gt2wytlpirx.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gt2kgmcbeho.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gt2ndykzzne.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2ljhijnur.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2vbknxujs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2cwvzvbvi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2zbxvgqtd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2swudzpjy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehfywayj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2pccmyenn.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gt2ftzdkqnr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gt2sykqnewu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2htkbuvqo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2ouusuynp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2dfbnmqhn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2vqysarmj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmfmouts.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2bqhotppd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gt2fidmqnjl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gt2xgwcenvn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2hlgcnyql.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gt2detozwne.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2ijivzkyr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2onwjekib.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2gmlgyebc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngjcawqa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gt2mouncjto.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2psjswnqy.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2olijmmik.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsciwwjb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2bibsqiaj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2klxgtvln.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxmcupa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gt2hggmwuyl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gt2ewfbsyew.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gt2romlfyaa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gt2lcvrjmqw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2aohuglyg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gt2sdmhjepf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2lgsnzgcg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2imqfcutl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2iiiodums.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2umqgslhz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2hfkzudbf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2zrxyncul.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gt2pdszxqbb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2laemfzjv.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gt2gipssxtw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ldtclgtk.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptzweqgz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gt2rhrnmwbz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2fhufhrov.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gt2bcpafqxg.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2swiwivyj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gt2khodwgzd.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gt2atozdwik.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gt2eeoazcgn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gt2krqdadcq.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gt2nmsrsynw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2jpnunkfe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2ufvaeoty.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2ciqzejhc.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gt2vvitolxi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gt2oydqjygl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gt2dayoujgp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2iowymeev.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gt2xvkmbams.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gt2dpuxccik.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gt2njmckcvo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gt2ncvgvhwq.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2fyywtyli.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2beyoanpg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2sitvnbyg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2slwspfma.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2divzeezi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gt2ufprzdcj.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gt2nizcprdc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2gwhkmsqs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gt2biqzylro.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2cvlmlurq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2sfvfaefz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2prghwkcn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gt2giekraul.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2phckiydv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2nqymzres.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2icswzqhf.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2pxnuersp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gt2mteiwywf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2kzufzgkd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gt2mhyrxbun.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2jswbaulj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2akzqmmjy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuuffwte.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2cdyunqjj.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2llsjlntv.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gt2nmedrzgw.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuanzx.com/Article/details/gt2wcnnfrlg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gt2mtuxcppz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gt2zvnxcquk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdswcmni.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gt2togiuxax.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgqcxmbj.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gt2aunipbcg.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gt2qsykwkyx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2gwijzbvn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gt2fizvewiu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2dvghusof.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2jgzmfpbm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2mdwsjlon.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gt2okeflqnb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2glxjrqoy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2wjlmsnxv.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikrcwkdm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gt2djdpmaog.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gt2batpsrhc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxrkhknn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gt2wilddfjd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gt2xdgejout.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gt2pyfjganq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gt2owddrqgw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gt2ogjelftg.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxykrycd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gt2kfokzwdx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gt2fmvrcyqx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jguhljqp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gt2aodumcdo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gt2ibqkvrim.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gt2jxqmwbkz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gt2iugrkmhb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gt2vhbneaib.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gt2mnwjpbka.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gt2znsezocf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gt2zzrutrtl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gt2bxzyydbi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2ydudhwpc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2soaiixfl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzycebpe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gt2capplhbs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gt2oxoqkqwv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2acyhzewp.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2miqgetbf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2kffdlqtk.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gt2apffymhn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2zthoavzm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gt2ryvguukk.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2tykalmqn.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2icrjcios.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvvydxbg.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2ubmxpklw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnktvyus.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2mmxmfkem.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gt2shtssmfz.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gt2qgisfxrf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gt2fimzdjwj.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcfqsfxw.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2jscgwlrt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2byksddjx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2fqnwtkuo.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2scjlmnut.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2awkmbkqv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gt2hpzlajlq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2swxncsgm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2nkdthqlw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2fhsdabbo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2xvxihorc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2ndskivcw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gt2exhtsqnt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2kkptnhxf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gt2kqzdpupb.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvlmzkce.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gt2vmeeixbs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gt2sujpkvrt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2rcvskinw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2wbuwctel.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2ihpjonnd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2wtovvjjz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2wvvwzoue.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2qlcpxlsv.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gt2oevxoufw.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2tncjcedd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djvjlztp.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mplbvqvq.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2zbfhxxol.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gt2dlskuxto.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gt2ajtxhdtf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gt2aeybnieh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avtzfaeg.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gt2ofwnlunh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2xazdkuqi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gt2pnfgoenm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2rnvuokxr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2elruwtzb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2xqnybeer.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2xqokpofa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2lvgyezpg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2etgougca.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gt2lchuskuw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2ffpsqrgf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gt2oybpjlef.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2nrknjkpr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2snwaplzl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2qbaillwf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2zwqywias.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gt2clsziunt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2lotcmayj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2esdiepuv.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gt2yxbfhump.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2zztvcrbw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2atzbysgn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2jrvhwnul.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gt2qcadtviq.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gt2fugufmmj.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gt2tfpvkmbc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2qxadgvks.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2vdxaierb.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gt2mgyqflfr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbyriedu.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huczogkg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gt2jfrlcvfn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gt2whbitgjo.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2ndqnxcsx.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2zyckcppv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2vieojwmm.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gt2onucgunz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gt2uxmgdkuw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gt2cqtvthkl.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2vubdhsvg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gt2iaxzecew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gt2nqzlthuo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2awqkhfmh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2dzubhryt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2vebzfxob.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gt2nohsdxwb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gt2wtxwwepo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gt2puwgqgqk.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gt2bpafnixr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2mmwsyddl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2aclvospa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2fjlsgiaj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2uwrfvinw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gt2uzkmnrfx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2ztdfthxo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gt2bvcvpqog.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gt2vlwmqlbw.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gt2wmldufdd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gt2tqznhfwn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2tcvfqaju.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2hssctebo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2qexyzxdw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2ggdblwxs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gt2menjckso.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfoulhe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gt2ymksrbdi.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gt2gcdgoryj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akvzkxus.html


<!-- 参考信息 -->