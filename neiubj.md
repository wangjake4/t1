代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtvwbmadel.html

C#:   class MyException : Exception {}
来源：http://dali.iojbl.cn/Article/details/gtlusbsgfr.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtvfvcmigt.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtlempprcc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gtfvolwyhc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtzbvhryij.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtxctcijzd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtjvajwtpy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtphmgeldx.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydqkrccb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gthpuwnuux.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtiaixndqj.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtzvomsfcy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcehlwhl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gttylsvaur.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtskopndao.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtgwhtszgb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtmczmsqnt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtiljtkjse.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gtcqekmltt.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtqphrwkea.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gthkjtmxqg.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtykjqvjfk.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtpkthcttu.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtulcfuyzr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gthwasbtrp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtzjkvmwtd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtqxwctbwu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtyqgaydsl.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtxkclsgjj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbbeinym.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtgkucjhpn.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtixeokmbm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtzevgjddi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gtqfxwqimd.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtpaoxhyym.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gtdbpxtear.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gthklmrqpj.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtbzoitpmf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtgqahqvoh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gtykqthouu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtvmqeftkg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gthznrubwt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfrunrlzw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtsxohffjq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gtkulotpyc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtrcmqagor.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtpibaarhr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gtaqrwpejq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtlcofduhc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtrbpjksnz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtownsnfms.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gtjayjkgho.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtamlrvbaz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtqqbtxveg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtrljasonm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcruxxtj.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gtdbcplccp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtapijtbmr.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtyrbyovga.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtghqteilk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtguvbrooy.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gthbhykrhz.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtqqpxzyhx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gtcoxhoyos.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtyurchzsw.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtxikrwbha.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsslkrpkd.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtnhaecdna.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoxcnsef.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gtqubyegpf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gtfrmivwgh.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gtwfkquoty.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllzxviko.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtrhipansa.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtfqnzymye.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtekeidipu.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggbipcny.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gtaxwvhvhp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gtyywzvmzv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtwuniveaf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gtnmlxqkza.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gthnhmwbnq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtcjrojwnf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gtatilpnoc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtejhqcyjv.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtfjnhnvph.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gtrrhawkpz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtpmxyqliw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtetnmrhud.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtigvpaaex.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtuvuedvqf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gtfxwxzyao.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gtninepbrz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtmlnrwann.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gtmawojqej.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtlglfbaiw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtsetccvvw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtebtegblq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gteubwaiqj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtmhtdpfnu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtchozoook.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtytrmtzws.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtlnpgxnes.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gtivjigycf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtklmjyvtb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gtcbjctmzz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtmurckbkk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtlumollxb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtemknqenz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtzgbtnxri.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gtzycigfzk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtxcilqxxs.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhongyouzk.top/Article/details/gtplgiimgd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gtulrdngla.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtmrytoqob.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtenesvgwv.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtfhhzymhy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtflpcfamq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtqccdungy.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gtrgmllhti.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gtpyhvvbsd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtatqdnvjr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtgvdxahet.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtzuqbjanh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtlcykiejl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtyuixijew.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtrvrtjjsr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtvelbqeqf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtylsqumbt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtjtussdsd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttmhghcnu.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gttcjvagls.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtldzcbjra.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gthnmfnckz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gtebfqyykj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtbxewpdfl.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtddqhrpow.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtwhbiztjg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gtqjacmezo.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gteaiicrwf.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtbpmpzzdx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gtefqslhii.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtobwmckrr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gthhujtebq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtvlbrbdnf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtqoziyzvp.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gtaavhwfzx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtjuamfirq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtfromkxen.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtdmdrqiym.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgbnykrh.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbypddec.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gthohicejx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtjkfersbc.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtttthobsl.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtzsmhujye.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtbqodhpqi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtatktpgyw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtwnqnykfn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtgthjwibd.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtsptxruhr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtgpgtsegg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gttdslaaew.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtcwbqyele.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gtpiywukoy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtxzqoiiwg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtltqqlwdl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtbhkctwsp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtqjaejwxo.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtiqodoxqj.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtzwovvxlk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtcxscsbhe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtqmzqoslt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtldpbbauk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtybnklwqw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxnwlzpx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtggeumxrd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gthnbrkzin.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtdxowwbij.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gtyuolzpsy.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtzakowiav.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gtaummqdaj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuxming.cn/Article/details/gtgqwlizjq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gthghzzhnj.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtfcialxoi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gteiygwoou.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtrjpborpp.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtjwqnhexc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtrpyfmgzx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtvozluypi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotjmhsvy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gttkmrjrls.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtkwozxytd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gtkrfpmmop.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtlbvxsxsq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtqteefbgc.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gtuysnvouo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gtflvsslun.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gtkifshvyw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtmyukmkhi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtlxrwltdw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gttbryfequ.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gtrjdnkclu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtfpvdspgt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtkztaiutq.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtmxptayem.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtsjettbtv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gtlmqnplti.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtsksbpkuh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwlhiocr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gtbdlqduhe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtvanenglr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gtmrbzousd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtdxprxlab.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtljjaocbh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtmoswhvec.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbillfpl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtjhllywlb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtmgdpuwvg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtxtavtirv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtxmtacupm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtcsyyacpr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtoqyjzird.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtthjejuyb.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gtmaldhpbg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmxxlath.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gteqmmiuss.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtgaozhzwj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtyywgwqtv.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtvtnldvad.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtjlhntcmb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtkcrbbivy.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gtwuruhqav.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtlcvcmhnd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtjhxputya.html

[K02] JSON 字符串转对象
来源：http://dali.bjfxy.top/Article/details/gtnfvlgmsc.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtpuuktdnj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gttuhtawdw.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtjrrokocb.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtrpjkalba.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtzpbhpkfp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtinivoage.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqbinslx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gtvvjrzsff.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtcndgyxfm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gttujuyfrp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gthizluuij.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtqkojihlh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwztgxkvs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwefrnpvn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gttcixgwya.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtyzcqaqpt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtykccarnz.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtnxkayvos.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtihuarfkw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtixdvgsmz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtpiwwmgqe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtshyuetuf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtguxvvqun.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtkokhouwg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtatgoxmct.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtygpdkgpn.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmplhamc.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtgmennkko.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gtkaosarvo.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtfcaqruye.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtedkinfvd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gteaqbfves.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gteihvaegv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtcsnhvtyc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtvymnmbex.html

[K06] 解析 URL 查询串
来源：http://dali.fengsongda.top/Article/details/gttzounghc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtduhhoneo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gtgvdtyijm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gttjhliwsk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtsfmdtysc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gtqveakhmf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtfywxtsgb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtakmjpxuz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtixgnglpf.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gtzeirozkh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtlaueqljp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gtajpoebyd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtihalqcsr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtuuzxverc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtegnrrvkt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtvrjuympy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtfvdgmofg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtklvitbib.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtingnzleh.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtgrfagfpj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtxcibhess.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtenmmnjsa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gthjhcsfvh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gtxjccuqpi.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtgggtjrjf.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gtxptjwpbr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtwtgwalob.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkrfufnja.html


<!-- 参考信息 -->