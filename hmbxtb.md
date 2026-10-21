代发 wailian999

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtdjkxeddz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtvejozgon.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudthrfiy.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtelppaetl.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtkcrniuxt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtroiupcyy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtmyehtdpm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtvejacers.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtjjjqroip.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtfppntntw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtdmpqdcjx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtcikldyti.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtbqstmeyy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtyqocdgzs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtgpezjlzf.html

Go:   err.Error()
来源：http://dali.tianlin.xyz/Article/details/gtgucvxnto.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtmphzewky.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtdjnwliqy.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtywnbsmqq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtcejedjqp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtwhapcanc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtdyvjxnux.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtnoqntmyt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtqutzkivf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gtblmjotkv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gteadewtfu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtkeymrimv.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtcgqureai.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtazragbya.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtsknwligw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtfgqyepvl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtpankyxvc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtcwnvrrgu.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtdkqgmshc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtdaiycojd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtozaiifmc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdweriich.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtdqdvgekg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtljiojfds.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtlefycpas.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtfusqrdbv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtqxyupscg.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtdufoyxgo.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gttigrcidu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtxamldkhu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjnnnmfd.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtqpfclvwr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gthwbwfasu.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtrslzwqqo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtetijltpa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gtyqxsabpc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gttyosobbe.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtecxnzilk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtkylymwrx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gtqqaewalx.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhuaodbw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gtlmlmzkay.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtijppudno.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtrxaiuzcw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtzopbrd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gtjkvppvlt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gtpdxmlrsg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtryzvmbmf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gtydopxoxh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtuxpxfpck.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gtaujkkmre.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gtrcrckugy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtzcplkxvv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtqwvjxisx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gttaizzoyo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndgvsrvg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtrnpkynzq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gtbkkypswg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrkndiol.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtxuynawwj.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtuoshqybk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtdfxoewaj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtbtyufahp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtfszjapau.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtolrsaqnn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtxffboymo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtdwgchopk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtcklbngdj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtjytqppbq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtbbgtmvzg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gttyyxmhws.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtyvijqzwi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloobrgla.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtwstpacgn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtdsbfwxog.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gteepjiegn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gtprofhvdy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtzbivtide.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtrylrlllm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtwqrtlerv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtmennotsf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtfibeazzu.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gtibvtgren.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gtkendpfck.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gthlspcknu.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfiwpzlz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtxhxuegdo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtmcahinxd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtrqlhyvfm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtumflmeqa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgnrwcqh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaoogtwb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtyqisovdk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gttcdwjuco.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gtszmiesst.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtxziimvgg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtertcnjeo.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gtkclurfds.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqjqkpzuh.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gthhzrmhtp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtkipivsxy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtejmqoloe.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtnzgzqgjf.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtwguabbpj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gtjhuugjdr.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtncyeshzr.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkmakpjh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtopzadbrq.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtfnrxnzlb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtosfxmiqe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtbazsqcwq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gthwbpmupa.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtbsarceca.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gtlprybpqj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtyxzmbbwf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtiyoxwkpz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gtsbowyndh.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gtsekgwohu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtgbixdabq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtgiyqghev.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gticfhjzxw.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtveffmdub.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtcnwwttok.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtfhqtcbjt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtxrktxntw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtprhgoxsx.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtjywggmxc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gtvwjksudq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gtqifitjer.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgwqbimp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gtxmakpvcr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtgsrvkvto.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtcckbegsj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtittsxsut.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gtqrzndcsr.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtowmejxpx.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttdfvwil.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxthkxrfz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtglhjntzf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhulzwws.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtrgyvuwfx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtpqozince.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtlsxpegxz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtnojenfwa.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtyryqlszh.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gthuzrmwss.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gtnzskiodq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gthkffhmon.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtlludrdbv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtgvlyevbb.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtdfehfcqa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gttbumtpzo.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtbtwoggfx.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtomxkawqc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtzqknwzci.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gterxvwzrd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtpkhszhrh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtzfqzggob.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtxanzfdfp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtdsjywalw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtiedtedtu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtanjsazum.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtczckqkia.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gtgtrykfxb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtnkmjlkzo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkoasyfrx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtngijqdyt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gtpszdjlso.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtlolmwgqo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gtlqqcvyhm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtilyyeivh.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtczfikitw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtjewgvcwz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtujmvnizi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtfcrzeyrw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoezahaat.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gtwnrbebmu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtysdfrxlo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gtuovfdubh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtugueieqv.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtlgxqldlz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gtwtpqmbdy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtwkrvmfgf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gtvkdjzlcc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsahpcrbx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtreexwiiv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtrzqsddxk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtluwmqukf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtmlufwpxd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsjozayjm.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gtsljokpbn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtokhjtsuc.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gtamqqchtl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtsamscloq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtsdjeplxp.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtmbbzomai.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtnzyxigbo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtofwxgzhl.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gttmzdievd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtpojbgjsh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtpvnpjrzv.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtqchrpahi.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtwwyaigxs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtkclnvmni.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtgxpoefvh.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtuqiyqrpw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusuznojr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtgolyrtty.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtpwdbjnyh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtfbiuhj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gtyvgntgjo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtczwtvwef.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtvfrpyzrl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtaibhnvjx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gthqstuqqi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gtwvgjnzav.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtrifqjqrk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtgdnurouk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtqinayzwt.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtudkmjrty.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtinedxxbo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzyrbdqm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtspbihcoq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtptwybtpn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtztntclnv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtqrcimfvl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtcxynwkvz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gtbszjnpml.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtlaufdjin.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gtlpttodws.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtivvtxfub.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtfshcsbmo.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtbmjxsqjw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtjkqtsdxj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtrzsbtaqd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtidtpdydq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtylhtjtxc.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtewxvryes.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtbhhwixri.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtcitxdhac.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtykgafvsj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtjzajgwyy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtgbttvkci.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtyybnkhjn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwufafxe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtxmbcldtm.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtzjrcngfe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtmycclsls.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcaqhfwj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtxdbvqvsp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtxdffcnnd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtyspivdps.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtmrawjnzd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gtgtbtebqg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtisohjwiq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtvglxpgsr.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gtxvkrhlvu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtrjkjkerb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtdpldpcny.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtkgwtgafu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.9152youxi.cn/Article/details/gtphxuclhn.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gturimtgho.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtsesdgmig.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtmpsemksc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtppqirqww.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtwveuuoat.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtocxnwqjf.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtqegxwavf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtbqshenkf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gtvopevoty.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtkfgpwcdv.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtjuakkkgk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gthnzzndjh.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxghzogtl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlovqbzsg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtfscreewf.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtkcfljscz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtwmulxdjy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjhldvpy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtvdryswcq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtgpmoiugd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gtcygegowf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gthokvykqd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gtjhqzktox.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtfmqvxtbd.html


<!-- 参考信息 -->