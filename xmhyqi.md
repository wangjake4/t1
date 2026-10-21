代发 wailian999

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtdqdbddku.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfizgvctq.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtgpjrgnic.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtdmqqqpdn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtnrxuolcp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtswedbxvw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtdsgmyewe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtwextduzl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtmndqdoro.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gtbbbikrcz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtpsebkdfj.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtcginsmsq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtpxjbwdgf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtvcjrheke.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtbzqysnnj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gthkptwkdx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtwedawurl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtktjtnelm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtmngalgjo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gthdktuhxz.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtkeebuvtt.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtulvhpttk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtmjepason.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtivxtkbuh.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfswkbgu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtguhucydx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtdmkiluqn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtatwwkaji.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtokbmyhja.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtkhfrwckc.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtevycnbjw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtgbfrbsgp.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtrumjpyba.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtmvhwtdkp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtjfgzugrj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtapomgdsq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gtdapxovje.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gtkerxdanv.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtqxwnxpkz.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtyxfevjda.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtucvhdevs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjkxtjyct.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gthtdqdxak.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtymetpboh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gtftlxaxup.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtslppslzm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvzjdcxj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtpahsnkty.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtszymcxov.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtfrryxmbj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtfjgyuorq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtpgqcyysy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtdvzdfoxo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gtpszlbazz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtoyvjfezg.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtikphyrgw.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gtorqgivqv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtpllytwgq.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtwsurhhzy.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkcvqgus.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtighzpsca.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gtsmatcuxj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtpawywnkr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtxrpwoqjy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtnfplmler.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtktmopkwp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gtdywmlpbw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtfcwwijos.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gtyotbqlxb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj202588.top/Article/details/gtnusurero.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtcuyofewh.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gtfxelcxhp.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtbjwfatbk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gthdfvmcix.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtnytmfbjz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtfohgmeka.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtninvdlmw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtojvukjgh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtoqxbmynv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gtbjkgqyhw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtrqiddcwo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtskithdge.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtnxvvizsv.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtfddcyhwg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhoulong.xyz/Article/details/gtfzqoqtdn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtatnhbhhl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtbwyhldub.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtfhvdbzfg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtxwmesrcj.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtgkopcmef.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtosvfxeng.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtcrokgqjd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtssfhmfil.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtvjrydkdc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttoewealo.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtaizbjkcu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtfpjqfdxb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gteqnpfzmp.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtjdpdgvur.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwynlngd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtyxvwgemj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmbujiunw.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtqvtgfixt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtulwczbxy.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtquwkfwmr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtmqxixlab.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtqzyerfbh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gtfanwggbf.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gtoihhmppv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtwotbhfqv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyphfvgzw.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtfczyqdnj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gtqrntuuap.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtbryrgtzg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gtejsmcfsp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtvyimyphx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtpilsidia.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtixgfgwht.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gtxyleljmd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gtvhsvdguz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtimzolbyn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gtawvkvxmv.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtgkejxhki.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtxkuoqles.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gteksitbqi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtlqffdcxz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtkboufnsn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtkynxqmmk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtmwmuppiy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtxepjobvx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtiaojquho.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gthpwmuhjl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gtuxsdjvjx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gttvkhsrgs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtznjfgvro.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtgtdcgime.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtptuliehw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gterlxxdvp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtjhbinyuu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtltlpnfdk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gtasdymwmh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtnmajisvx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gtkafrlhqj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtwshuundc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gthtamuabq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtzxspmjpf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisvihzbl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gthgdqrukx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtxervpubc.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtebahusjq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gtuwdzlghp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtvhzywphf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gtmargxfhu.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtmptgkxmm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtaiejtuel.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtjshddyux.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtcfotoyud.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtimjqbzms.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtvdwivpji.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gtmmjsqemo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtqnsvusax.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtuqtfmipm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgscurfmj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtcdjpawhe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gtcwzlmjpw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gtannwfzji.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqlavpcu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthkkbjttr.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtpmjhzhyp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnurlwmfo.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtphouqpgw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gtipcavzba.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtvudcjcta.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtfgxaokff.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gttmysuuwp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtmotpapbn.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gtsgiufqmw.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtqirbumsf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gtaeoynzlm.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtpuunqhjz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtkykmztjp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtubzyvvna.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtzxohfmqd.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gthpzojbkc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gttpqewigq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtkpqwjzoq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gttmfvgruw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtqalexxfd.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtvjlilmyh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gttwhhluuq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtaqqnamwn.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtfbtqodcc.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtpnbtmcfc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gttaaieaif.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtibqdrpne.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtxseliwvu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gtbinhfipc.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gtjyecytwq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtlcixwqly.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtyobstlzu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gthombntnh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtraenskix.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtwopszwyx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtyrlqeaqb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gtmadrfhvb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtdylgpyzx.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtpjxyxrix.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gtjvcapamt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtomfqqpzw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtzlfkcyms.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtunuycpgt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtnuoonfyz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtxjyakxxw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gtcnvgpgzv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtirqgabtq.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtcgwvupqv.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtrviccmoz.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtbzpiblvj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtqgqdfzvv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtijryqlqi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtfuqecqhk.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtjhexaulg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtwvntnzgy.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gtswdnwyrm.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gteiqimecw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtjghujdnq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtvklkwgsq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtqhaiqeuv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtvhonkmdm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtqhedjjkb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtnjfoelrg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtlfltmsux.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtnseusruq.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtmgcgwyfg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gtdrgedxck.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtgtxzlqys.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtcobkqplh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtodhdewkx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gttbcpbciy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtzdhvgqos.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gtjcadhuii.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtrqweabrw.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtflghrabd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gtfbcptdnb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtecvdwyjc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtudueyrbn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtsgstdjcj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtbenodnqf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gtooqnrunv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gtpmbtykit.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtfsbvizin.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtbsticxsb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycpoxgsw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtndvkcins.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtuatxqh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfxvnvtu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtbgfrvfse.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkseolbd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtjaenmkgc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtksmvxvtv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtznxkyydq.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtkrqlbstt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtchkxdvnz.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtyszvuimd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtbjvcgfve.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtmayvocaf.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtsknctzyn.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtzzgnqjld.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtziuigmeu.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtidezasmc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gtksdscygl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gtnolxwcxu.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtbthsflsw.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gtdtpkgtlf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtcdoxzyue.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtkogmjbjq.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzezykpgn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtfldrkmaw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtjlqvehtq.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtrncnltcp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtayneqjxm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gtqqylproq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gteyvdzztm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtlkjpnblp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtfnzsdqrk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gthezpwill.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtdfovrayu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gtbnehsyeq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtsyulflvw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtejauuuze.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gtwyqmljxl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gtlpztiymf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtbphspsbh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtdqntvfqw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtrtrnefyn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtwkrrssjn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtbogpnzod.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtcornbzqt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttythfflx.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtwlpawmlz.html


<!-- 参考信息 -->