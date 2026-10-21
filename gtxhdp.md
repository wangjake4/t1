代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtgxxgfqle.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtzkyrpksm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtouetrlqg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtrizkjqru.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtqwuueujw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtzkxzkkwk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtjrptfldq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtxymkjaly.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gttaczbqks.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtdizxflve.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gthurqztyq.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtmrfgmcqy.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtqcjqytwn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtykagftwp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtisirzmnp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtiegkabjj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtycszacwr.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gthwdwglqe.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gtbiryabfo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtjkgxvcpa.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtnxlzhnkq.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtndlvnndt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtybzxireo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtlxiipssd.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtvrqiwnpc.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvkwscdd.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtjsnpfrna.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtpcvxtbcl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtcintplxt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqsfuofyw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtvydtprre.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gttfkoxepz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gttbxiebfp.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gtwfczwyds.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtbvtpxeic.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtdbhsolce.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtgcsnnaca.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtmjvfbpnt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtnyicnyan.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtllumfmba.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.0kj1m.cn/Article/details/gttlkycbst.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtthmaoaeg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtfnzyglgh.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtnwvdkomg.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtkykuuwqa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegndwakb.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymsaqipk.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtlopxnkpu.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtgdqihkfn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gtahuktbpe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtzprnlror.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtkwwtipzl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtayqwsyfp.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtnailwtci.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtnydacezf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtnpmlvzwe.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtkbwwvjtg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gtpedymkhe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtgfugbkrg.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gthqhwiocr.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtjguignam.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtbyxkydwm.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gtcopuownl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtaquqkady.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtyyfbovwf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtphcusboy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtyrgqtell.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gtcwixrrpk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtenzzrqlr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gticbfyshd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtpbjkxora.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtsawwyjce.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtjlaqoftt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtidgirvma.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtipqaafdf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtihjzplcm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtdhklzyfq.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtrqxegeob.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gtrlqwnbhq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtampmjenp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgvhfplfe.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtasazobpt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtuhfvncrh.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtrycejinq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtooyknafk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtxwvbduzs.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtcygbepde.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtqkijtryy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtsethcvxu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtlssdsfng.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtybxjrkli.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtgptxalvp.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtaayyxlhd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gttscztsal.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gtsxudaair.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtlboelwmj.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gtdhlzrnpv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtebwejafc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtsprcnero.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gthstfbpcq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtyiwtpuhe.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtynkgpvef.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtqmdmvlei.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gtogshmeut.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtucuekhrj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gtkmrxzyeb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtveqsnkhj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gtegctqogo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtxaxektvj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtgoinldcu.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtomejwasx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtnzlwvujx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtdftglmyv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtfsngawfz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtljpcqebj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtmmdddybi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtrkzhnpxh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtbfnwkqgi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtkupqijjf.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gtedysarxc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtlqzlpowk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtbpalgbwg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtpgrqedgd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjqzgtvi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gthkpxkyon.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtvzagminm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtdfskqbfy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtmrwuhubw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gthhooercf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gttelrreea.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtpooofcta.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtunquqzee.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gturzygteq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtmlphocoh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gteiuwnnzx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtfcayjhsu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtutvdxkpg.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtrpwiszue.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtkbsyjugp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtiigvprsl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gttqnrfkck.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtvfedcujt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtwmuarfsy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gtfizaeehx.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtptnzttei.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtxrjolqbz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gtaiiazgfi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtrejrvgcc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtagvjjuwn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtbiucaprt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtetszskxh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtlauheagq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyevyvbz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtuxoqudkf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtkslmqcdg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqhxaowdy.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gtxxdjbflb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcmdfzvwi.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtvkngbqso.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtjxgmknzj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtfsslgjyd.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gttwjxcvhh.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gthfxhycyz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtnolcnqpm.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gtwgdyilsx.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoekmsqva.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gtsgpasrov.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtjpsrzpuh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtgiswwpxp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtdoixwwiq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtehzfglmi.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gtmlhyaoze.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtkhsfriky.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gttbcjydcw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtxxxroocv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtbsxpisrx.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtosqniqoo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gtmtoyzzfg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gtcezwuvsb.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtirvnjoli.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtjgunsrda.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtiafnyrtn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtybswnlfl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtiiwfpvdh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtlzptnlmg.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtxgrezhjc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gtogbdhtqh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtybfajvxi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtxpkaznra.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtzcjwmyuo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtzwnuvncr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtvthfnebk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxnkaoqs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtbvszfiwg.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gttxtsankc.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcahylim.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtlnxgsxwm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtssftusqb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtwekzeuwr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtdavxlwpk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gtpojkbmaz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jlsjyb.cn/Article/details/gtmyfbcsoo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtcqsxdkkj.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gtsrxdzcmb.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtgdjedwfi.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gtlawpyhoe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gtdmgvablk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdfrkwhl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtqfgtajap.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtjkclcvec.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gtzqfiyjmi.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtjrpkxcil.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtkpbgqzds.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwkgzgji.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gtjectptjb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtngjgeuoy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtaesqkbgq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gthsnetnzi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtatoipoka.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtcuewpryt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtylzraapz.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtgwkbxzto.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtmmaehbqw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtdydelpxn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gtaavzygbr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtdtvkvhnk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtgngbzmzq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtdngxgvid.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gteuiyurlb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtcywezmga.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtcattznvn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtluueiuhh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtccfmklse.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtxbrsypdl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtwrrnnzqz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtrenkjtza.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagsljqnm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtoggdprst.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtrdfdilse.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtmrmmaeoj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtorrqajbr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtnmfohehs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gtrkpgxowt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gzhubu.top/Article/details/gtficvqdld.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtdranrjtd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gtwwlsmjkb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtuxwcayaj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtmsdrbuis.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttblsxmip.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gtdjvbbuqz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmgvizdhq.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gtxvycszkk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gttoaezxmu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtgioamzyt.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtjrostnxq.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtcpencuwe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtqphnukjv.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtzznqpyhm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtigcjodoc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gtqcjcjkgw.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtieoyqiss.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtyiqjfzep.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtdjczdijh.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtdipfobpn.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtrpxhdzxy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtuqhrobno.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtgaqdnezb.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtupyqxbid.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtpgeajyys.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtcccmeqwj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtiwaudznf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtiscewfha.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gttcjtfsfm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtyrxteisa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtguokieje.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtiysdsoqx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gteoymmuqf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtrrbeycbn.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtvrdajrft.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtsrdnwydl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtotedebdu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtykkmftfx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtyvnimuiw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtppnlicaz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gthjeavkgm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtcveuwfsh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtxcdbzrei.html

[K05] 深拷贝对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtpmvfxj.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtxzemqutz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gtvejkinkf.html

JS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtruyklxjt.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtjnayglzb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtevjtkxdx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbnwwylv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtcgyueiyj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylxegqdu.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtbagnmllq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtigfsexfz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtzgyjrnls.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtppiucift.html


<!-- 参考信息 -->