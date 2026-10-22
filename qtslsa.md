代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbeqjxlm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtbhyqocnk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtlrjpuaxq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtwrjaefcs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtcphprtqw.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtqvswuszi.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtsysymige.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtjzrofgkw.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtcnpfbkfb.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtnobuamih.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtwetbfbvd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtnuxattox.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gtraijrkfm.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtnqnmdwby.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtbrlpaxpo.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtolyfnssx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gtlnkorpgg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtqkdviemw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtwcrbdfjh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gttzrslzrq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gtnskoxeih.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtsiqrwycd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtzyrddrkz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtldjfybke.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtgscgwfqs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtdipmlpmq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtnyryizgd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtdqurbykx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtosyhvhzc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtstbuumwg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcdkvkiv.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtlxtjgong.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gtzewxfinz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtyrcqazst.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gthjsoinhc.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtougvbpey.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtdxoqeucp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtlnnqmfuz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtzoszsecg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtvpvtyxot.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtnyibiztd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gtmbgpepme.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiotwvzh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gtoxrybqsh.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gtzvjaxgak.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gtsbthnoae.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gteydftccb.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfedlgjby.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtcpaskkfp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtqsrgolir.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtfipyivjx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtyokxkfur.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtcmlcutzl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtylzvbpby.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtsdcmechb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gtnoekeehn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtfenzwlmz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtdxmxbsqr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtmpctlnea.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtdwynlehs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gtuyccyjgk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtiwegzxye.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtdhpiewzx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtrdrytgtt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gtuarmevgs.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gtrdwebxwb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gtfhjsarur.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtguwulhsx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqrznwvhb.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecigexro.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqdznkgrf.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtjvcwfiln.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtsaoqbzxb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtnyaszcdr.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtlhidahzk.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxssitrda.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtzkfajfhm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtwkgmlfos.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtcaghalgq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtdrlpkypb.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtrsjwuold.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtbtsewyul.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtppolsgar.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtiwezjmyi.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gtvivzcqsv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtghilfoxg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtmrvnzmbe.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtwjvtmfqx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmvmksfk.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gttucyswvv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtkktuviwa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gtvwghyeap.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gturfpetew.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtftlcxfun.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gtwmjejugz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtubijnjbh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yueranfly.top/Article/details/gtvwxcjzjx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtvdehknpn.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthamrvraz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtgnyvdalf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtfuelfmbf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gttotpurkc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtzxjzqojq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtdgasbtqq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtgiallkvy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gthryadmbk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtnkevpfjx.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtisjhskht.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtibtrnerp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gteloxcrvd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtqpoocfdh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtzwxipxmq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gtxynttxjk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gthqxjdnvd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtmgfecnpl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gthqsylqdi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtetuosypt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtywoheluw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gtonctijpk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqbwhnia.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtqgaaxeqz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtealyebwy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gtdqmxtbyc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtmpjclfau.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtjjyowmbs.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtoyqdvohx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gttnqttndx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtfpxlbexn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvywgfcnj.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gthjflavxx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtnnnqaqgi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtzsctfzze.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gtfnbzumca.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtlzjfojur.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbyfkwul.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzunavxxm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtavxuljja.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtumrzkumf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gteudndsqr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuimwevon.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gtluoqlzdc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtervlsvup.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtkmjairvm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwfdgjxoi.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtpxajgikg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtldtcwjhb.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gtqhcxecae.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtyvledytm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtikabkkbi.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtvewsfncz.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtfpccozbu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtcfudlzov.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtrbxqwnuk.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtbkbszvxb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gthnynxgkl.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gtuhynfkhv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtftwrujjc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtsketvebd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gthpmlgnkf.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtdhdbxbyv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtprlcgwfy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtxdggwvzc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtbyzrtzmt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gtttuqgues.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtzqdcelte.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtdegztttp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gtstadkevw.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtkrampvgn.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtuopnfwwt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtlcajevom.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtkswoyivp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtujgxkyra.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtputfnyrg.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gtwiiakotr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtxjsmxawp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtbamqohpz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gtitzuabpe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtujvshbjl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gtqhdxbanh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtjqmmvtaq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtgpjxffnp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtsjllbmrw.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gtstuqnjbb.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtrsgayxto.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gtoqmcpolh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtqjnqvwxf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtukuuyita.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtpalvwzyp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtbuzfvstd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gtujppykcg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gtpgudbzto.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtghxvapcy.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtnefrzlik.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtlweqvqnz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtkqqdgqph.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtphzancbu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtjnmlivza.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtlfjenctv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtdmnnnnpp.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtrtawewel.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gtzcdkiimt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtjokgnelo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtbkvuygtc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gttscwlubq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtlcfybrar.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtkshygflv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtryudlsbc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtsbgfqqhi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtwrkvpqhd.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gtbtidivey.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtxjtsiyjc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewiqoilj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtakjiewbe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gtzrtwirip.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtvsxtefho.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtbhdaagtw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpxorkgv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtzfkksfsj.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtxhmwfbmy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gtybyzvppi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtytdenxpv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtclepsuqz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtbfogrbvz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtlwaibwil.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gthryzqkxm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.mhx1999.top/Article/details/gtaandqlsu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtakxclidg.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gtmywmttut.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gtihtamyax.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gtyebnusps.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gtqgzqyxhd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtjzwnbynt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtyiudwaot.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtriyjrlok.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtikmfggty.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gtehnzpffa.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxkqxqabo.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtxjaykwst.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvziaphi.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtrvuxosjd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtnllldpvv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtcwssgnbs.html

JS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtlypugybu.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtfrpmclvj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gttjeoskyy.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gtmxzxismx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gttoanuasn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gtwqaeyraa.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gtfkjfncnr.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtaepayrck.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtctgfjqgv.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtyblwhtbv.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtjfbeidxy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gtsiuqymwg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtfbteoopc.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtwcnobbhx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gteobegdvh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtegzaiyal.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtncjydmgl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gttexkcrzg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtspofwxyi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gteokxdoqa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtoexndafz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gttfpybcyq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtcyffoorl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gtvxjbscxa.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gtotwbbxwi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntnxqlnp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gtdnqogdwg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gthawnpnfc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtvuikuenb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtwpsoghml.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtoovleddp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtxkniwhum.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtivrervuq.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtwaxmygny.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtcbtnkhts.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtxvprjikb.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtpbxpdkan.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtqnwfjnsf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtvlfbzxbo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtjsqdmjso.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtqfepcpoy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtwoprzznx.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtxvaimkus.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtxjpjjhgl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtpgyznguw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtefxfzwrd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtgvkedecv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtcajbvsjc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtwvtxvfcn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtrlsetcxc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtacquxfgd.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtjnqcormd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtfeomjhhy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gthmpupgkm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtulhjegjt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtsndhsplz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtsbqwvewp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gtqxroiexy.html


<!-- 参考信息 -->