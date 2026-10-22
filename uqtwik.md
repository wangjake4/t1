代发 wailian999

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtqsoptabh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuqkrwivc.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtmcjyqeie.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtqhzafjik.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtvujdbytf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtybngqjcu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtxyvheuyj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtiwxarobj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtnetplula.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtdxbtvyax.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsboqeuyi.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtfmqlince.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gteidifpoi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzrvwnhzh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gthtxhwfbj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtiybpyqvh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtpkqpfjmh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtwtvlsele.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtpksdgcqf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtabvwdtlu.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gtrbccymkh.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gtjkdrnlbg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtlrdwltaq.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtroxbsxwl.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtfwrolttz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtgeyapgiy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtpcexeqwc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtbvuavhyi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtpvrpibuy.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gtcezpxuew.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtsvghxhwq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtoukzkqoq.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtxkzeqaud.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtjzclepyo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtmmazemgo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gtxhbpusxa.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gtcjtkodvl.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtknafjvzd.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtrudlgrfa.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtkgvfokep.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtliutzfyc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtwubruykd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsireytcy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtzhxjdytc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtoohkdqfa.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gtoonteoci.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gttcepotfn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtmmoeozmw.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtnvlcsxvg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtzbbinaij.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtudurfsqx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtmiklfivc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gtsomnodeq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtrwkjxckl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gtilezwnmr.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtixwfxfjo.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtadabjzev.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gtzdnevjhl.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfjvazoe.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtclffcdgf.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtfyvfnmnm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtohbinirw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacrkpklb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gtzlfroalk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtdkwrxavg.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtrqsgjgnz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtottwewxm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtsvqfystk.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtlzgwwogl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtkqmelwxb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtccxlflol.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gtxpnfqabb.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gthhiyxroj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtaaraxvww.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gtmfuygrsv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyapkyme.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtogbmrfcn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtrvbkviuf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtaqoopryh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtsghtbtoi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtrezdbiat.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gtgnkmlzqk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtbeveodsq.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtaguseitp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtcrvwgvaf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gthdbjrwbi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtsnnwxyxl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtrqtobwlw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtwflzbwuu.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtqtcgpvth.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtnxdmewtm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnjtnfpuh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjnwcwhhr.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtzpeubojy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjngkysjs.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtiwjoplja.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtraxfekdz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtutivocaw.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtomvbfkei.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxbtwdzdm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtaqykumsq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gtdhcbjkdy.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtnqwynqzl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtxtqejocn.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtlqlyspzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gttecsvfjv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtmgwbzgoj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtpqrddnas.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtgtmroqei.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtktuozhic.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtrxlgruxs.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtlrduyeyi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtxmyqkqrm.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtysesccmn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtuxrlfnir.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtyhlpofwx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtzxijsfaj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtaydtaako.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtuyrdfnmf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzivewjlh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtgvczhjfa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdwhxkvr.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gttvmwmnkt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gtorbkegpd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtilhrjrxm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtibqvtpjh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtdsfkvaer.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteylvppgn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtfwyxnklm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtewppucfs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtckokwzgf.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gthejfdnes.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gtieqbcmhx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtzclrmkof.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtxxkyytje.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtyjfqighy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtrjafavsx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvissito.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtnciuwykr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtdxhbivgb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gteompntbf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtzkdbesku.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtspsgqkne.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtqtnrzqdt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtqhxrxrud.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtpmquodcp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gtmqrdmvxg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtypqajzhq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvzgoijf.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtcgqqybid.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtjvbvhgvx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtiejlmiwq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gtnrrhrgnk.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtfujsmrcr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtyplriqhx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gtvuclgdiq.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtfxdooupb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtucgxuxrz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtbydijvsu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gtpawxhher.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtxcbgoiah.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtxxpkagkt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gthjrxvjpz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtuvydiqqz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gtzyqkafki.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtqpzgczjk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtvxlugoxl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqhxpfhxs.html

J. 日期与时间
来源：http://dali.zhixingplan.top/Article/details/gttzhgugye.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvvjmspel.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtkpdimjgr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtcdrslxls.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtmlmkttfp.html

JS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtflulvzxi.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtpaarwfwf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gtzlzxbqvu.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gtkhqlpdzm.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvbbubmx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtwqgawnkv.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtvoyhpalv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gteramdevp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtacbuzyop.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtxlfqajpj.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtkqxjlizg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gthvfrrzaq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtntkbgfpa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtwpgfaxmf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtixtikaau.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gtcmigrxjp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtawwbtbwc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtuiylfcwh.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtlklgmxbu.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtsdoopoba.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcvlatbr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtvvtfbman.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtqenetrhv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtdatfztww.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gtustqvmws.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gtmnbnurft.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gtwuabkqap.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtemnnodtc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtjluiaibo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtbufxcadu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtkplfqpkr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtnxyhgpmj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcgthpln.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gtxlflukqm.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gtkghasgac.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtrzkapque.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkpownzx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnxroucv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtursinnqo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtjvtmlslx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtjwjlatve.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtaxdssboo.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtqhwxwemd.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtivlrhqma.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gtsgehyujt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gtnubhqqpy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtilufnwur.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gtngbiatty.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtlgxonsdk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gthcoveiqs.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtmkhcsxfy.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtahwkurem.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gttxblkonn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtvdmqxdwb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gthzmfteqq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtuadhjxxv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtjcrnveff.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gttdnrcmvf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtbwcfsnvj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtygufucpj.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtfjxnknsk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtftijtpgq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gtzuxvdjlm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtiwdudnzg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtjcjqvske.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtviqnhksb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtxquacxhy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gteihjptmv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gttswcocxx.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtdzlgsnzq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtwhxfmhqd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gthwnrelwc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekocgxzy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtzuwketll.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtkdbzrpci.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtupaouklp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gtlxuopsaq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtgcqntuee.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtjuxiagwr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtwbjywkaf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtccmjunyn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtxeynnyzq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtpbbfmink.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gtzlmjppal.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtymmiuoql.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtdnakoxcu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtqpwlzzhh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtibimzjat.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gtmyzyubjy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtiwcmpcwo.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gtqqivaamt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtcghclman.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtiqbhuobh.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfkkzzdm.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtxppbuoxi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gtesvkidkp.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtlqdizycl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphuqhtml.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gtcvkqbgjr.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsoxdtwo.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtqsexifwf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtahjswpmn.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtkniaondo.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtfnvjejog.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtvhzdsiue.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvxwzofb.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtugeqlysb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtyfwczhag.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gthriscoei.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtisrfkswp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdqikfyf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtvgwgoobw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtnrpmvndq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gtuahrjskv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtjwwjwtck.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtdqgjytkd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtyheauril.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtyhuokjhs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtljmtwxjc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gteipmjhjd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtctonnihs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtvhbegktv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbdlnwgo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gturxgxycf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtabzxorfo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtlonkneig.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtindyxajs.html


<!-- 参考信息 -->