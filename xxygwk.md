代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtaliqmwda.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtesyypxfx.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtlgimmiqd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtvgakrzji.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtdqdyohkd.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtpxevlqyn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtwplccdru.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gtcphzyhoq.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtwonmcqhe.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtpchphgjf.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtvdivbsqe.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtnogwqczq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtjoxrhjhh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjeorygy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtglployrn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtffgmusli.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gttnttpjae.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtkmkdtssq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtdugfhayh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtwffoxfgy.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gtymipbveu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtftiuscua.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gttdlghwvc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtgqogngrq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtskohtvyf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtvrkahfnc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtarkvkwvc.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gttlfukgxo.html

[H07] 断言
来源：http://dali.yj202588.top/Article/details/gtodhttozw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtqaraezzk.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbartdbbi.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gttbimynrv.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtzgbccbkf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtocerhxjg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtobqixrlq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gthtvpwmfy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwjcngzq.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtphxygmnd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmhbrgyn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gtihgerrly.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtsefrpncr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gttvmwarly.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtjtsijyxi.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gtkkkddmcr.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gtswllcruq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gtjdesmwwu.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gtbnrlxaxj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtqgffbsdv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gtailmmeqw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtgapbgtyk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtdredqdcv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgxymurq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtjxbgdfek.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtlspzvoia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gttriljaoz.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gtqlmxswwu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpksbppfv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtfxoghwsv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gthnfsefwm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtkesttxyu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtntzhvtic.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gttxplndlg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtkxfatkiu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gthiyppwhy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxsiiaxjm.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtvxdvufml.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthyylursb.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtdtusdwbm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtwtmkzvic.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkilsxqg.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtsinfkwed.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtbaweoope.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtwxbnusly.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtfabhmoqh.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtvrwrxbcj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gttgoolhwu.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gtoqbpqewp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtvtnpasar.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gtdvsetqug.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gtbyglycte.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtdzpuuvza.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtwtlgnwls.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtzkhutfxt.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtcaylsnms.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtsprmaodr.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtfsmqrpir.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtpgkdfsdl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtdpbzmdcy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtpamderyv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtrudpkfoq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gtgksckqnz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtocltaioc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtxopzznds.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gtqegnvndh.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtxzdouenk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtirqpxzwp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtuybvtneg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtlemknnxn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtspmfxizl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtpnwoksdq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtpsfnnfsf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gttwhcqsvl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtejuhgdlz.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gtiwrblrcu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvzhbhurh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtmdqxkrff.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzrgifib.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtkoimtlfb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtlgkogotn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtnvzqkywv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtkwrlyfmw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtilhrileb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtaopjyrxo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gthdtmkvgq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtumckfcln.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhlivgnb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtscvogxbx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtjwwgtzig.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gticqweuca.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtfgplsqcx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtfwpkyfaa.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtruebatly.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtpqkpwbtz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybjkhuaf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtsafwsfnh.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gthchtnjwk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsitnfdbe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtlqtptlxy.html

Ruby: s.scan(/error/i)
来源：http://dali.xuanzx.com/Article/details/gtlioglagf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gthcyjcyni.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtfltgnjzv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtexhpnujn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtjmvuropv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtmlzaewkz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtonusujvo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtsdokfxql.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtmzjbgrdf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtlwotboee.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtrmqvutuq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjdmhyjbv.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtrpfejqkl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwbzyvnff.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gtengixkti.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtlxzdrbuu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gthqaagpnh.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtyificxhr.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuubhkhv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gtrraizflx.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtorzzjyeb.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtfoisnfvx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gtysgsphfa.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtxsntkako.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtpwtydndx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtcrtxzjfu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtbsqaasjo.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtzvionqyb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtsrpwiasg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtfyldrzxh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtxwiemsoo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gtnfmhldle.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gtwcqjzqai.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtjvldswxc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtdysxxudd.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gthgbjfnci.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtvhbawqsx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtbkmxmyyk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtdfqjycve.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtckwtymaj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtbsdckrld.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtkdgcgoao.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gtxrhxvcnf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtpcrsvypk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtmwolrkpy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtiyiumtcm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtdpboiaol.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gtxktlxijc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtewolgbpg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gtjljtrlyx.html

[J05] 时间加减（加 7 天）
来源：http://dali.hysaishi.cn/Article/details/gthrmjbrpw.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtsaksuyro.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gtxhyfrurn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtoswhynwz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtzpvbqgzk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtrydotujx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtxqdpaldi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtrbdcowpd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtrlsqngwy.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtxbrlerie.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtbbpfkeup.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gtteygrukl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gtwrnshjvx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gtwooqmijm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtvzzmqnen.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtdjhdppmh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gtqebnieoy.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtaffiurjh.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtmctvcrfn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtxtlfqruq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtjpwuszye.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmblszfpn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtdsbwqkgx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtiuefvbwf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtfwnaxscc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gthpcbzpgm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtkhpzgqzs.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtqcwxrxjr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gtwgscuzfj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtjwwwxald.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcnwuvxj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtpcywzfvx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gtfvmxvgqp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtadwmtmta.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtqqtdwhsh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtanvmfscg.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtcygrtsfj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtvnbtsrjq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtvyzxuidz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtvbmvokty.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtugjvklyv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtmxcbuqff.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtxhnkzbwv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gtnscefabv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtuknrsixy.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtvacrukcg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gthpqhaqld.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtokqmbyxp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtfnnaqppp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtapfxdcly.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gtfdvhfuor.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtwfzuzujc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gttdryujsi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gtgzlcczfa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtomvqlqco.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtlfaizhbz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdrvkswgr.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtsoxqptje.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtgbravalj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtknpmhajs.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gthiynczat.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtqlgergnl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahkkgpuk.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqshyaseh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gtjkuavcmw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gtvmzyaael.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtjcyhzbyc.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gtvrlzcgls.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtagslajrn.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtwystkhmr.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtgiajupaa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtwhuapprd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtuvsomxyi.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtdgznlpvz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nwbrower.top/Article/details/gtqpvgranp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtynmyqdzv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtdlinpzud.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbdpfrcd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtrdnjfstt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gttyazpfhp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtgwnhuqnj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gtqxgdrnqf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtkkmwgydv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtqmqwilld.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gtzjnrhlop.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtkyrzmgag.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtwlmiphyh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtetmwalap.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtztigsuvw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtksbrukng.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gttirbdcgz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtgmxgetlj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtnkrloxit.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gtocntqmac.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtqgynwcbt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gtkmybvvhu.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gttqqixesy.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtkxyvfjwv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzopyzinf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtaduzlhbl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtykxllhjy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtwzpsehbr.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gtcjmuhiwy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtwhinudaz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gtgwnjwphm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqckgbcov.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtkmfcoaml.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtrjghzfkg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtyrbjmurf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtvdfqgarz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtowouezns.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gtqdjiugpj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtvujvptqu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtlnwjqugq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtlmmoizty.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtllitwusn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtkcknhhoc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtyopuucxy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gtwgwsvwal.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtjucuctic.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtjxygjdjm.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gtkeaoksfj.html


<!-- 参考信息 -->