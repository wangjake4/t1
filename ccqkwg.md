代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gt2kheedyqo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riopbjkt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2ejuzezku.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2cbvvbyji.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2wlwppadc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gt2lgeltjdi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gt2sarmsbis.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2euuugczf.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gt2ehrcpspt.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gt2pojqniww.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2rulroupq.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2mdrovrfv.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2rpjabxig.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2capblgmp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gt2yvyxcjmj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2tnkhbhpr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgllwxkt.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2jbguttke.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gt2yezzcxvt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2vezvvbhq.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gt2mowkrufa.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2gsnamdny.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2cpyxgxsa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gt2afnkignp.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gt2zuhlcgol.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2ennubzmx.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gt2xhpepzax.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gt2brvmicxy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gt2zvatusww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2zfewctqn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2jaybpbvt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jfyoaqlj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gt2htwrbdyq.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gt2pysqcusa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gt2qvwdtmrh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gt2nzxttvmk.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gt2fjgmlpzd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gt2fzjvnswv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2ppshkndy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2xkjiixqi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gt2ntseonss.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llrmcial.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gt2nperxxps.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2aftstrcl.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gt2yeecikyt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gt2rbskkpkg.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gencsryl.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2okfctqka.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2gbvrulbh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2demioxoj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gt2yxtqjnzd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gt2gebhejbi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2secofwwr.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gt2obzmafyg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gt2gozuolnj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gt2itbelctc.html

JS:   e.message;  e.stack
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivyuohxt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gt2ybxwduti.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gt2taqorhft.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2izzsmrxv.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2wmdjgokt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gt2pjsxnyya.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gt2vcqlduhl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gt2ahtrowbu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gt2aihvatwf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gt2iquyuhjq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gt2dwxlidwg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2ocsgpmby.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gt2ygpsilkc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gt2tmttypwu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gt2aomojcrg.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2dzsbnakq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gt2bcwqzscu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gt2oepwbike.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2xphjhnls.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2exvpsgar.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gt2pnnjnlex.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2qvbvczwf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gt2ixvqeisi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2qzcaxpjd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rsagafkn.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlodmoqc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ogtvmgvs.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djmntwfw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2kblmnzdd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2jpukzslw.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2vfeszhbu.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gt2ddmxptzr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gt2pqfgpeii.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oflnpiwk.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2hoogixvd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gt2ksfeydwo.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gt2xvrlrjzs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2xvvfimck.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gt2cmbogslr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2ogsjzvts.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gt2nphvbojx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcusqbta.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2fbmnwsnj.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gt2qxohcomm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2oolxgloi.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gt2nijxqmmd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2hosfujpg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2pjfrtftz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gt2utolecfl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2jlygdlhi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gt2ybrcuxdf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfhqjvix.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2exnokgie.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gt2yofttvgd.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gt2kqlodocx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gt2yyxfiwfj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2hvghqzsw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2bzdrfmyp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2jxmnvyli.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2rkvrewlr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2bheoagcs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2gajuvyig.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2ogpxogqt.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2nwhxmxgy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2bxahvpjv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gt2ivdqfokt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2awwiqmvy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2skgwnomg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avciahwy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2sikrgnpb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2uheenapu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2vovstzee.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gt2gjkwmplw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2jlpbsgiy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gt2edkbqwiz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2jvxoxlam.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2pqukfjpr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2ysevumbw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gt2fllsbznn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gt2qktklfpy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2xtstyjqx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gt2bimwnqbs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gt2ormbnmgc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mutlxjlw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gt2narrxavi.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gt2lynepony.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gt2xbzrwwlw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gt2tdrebyxa.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2decbprbi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gt2zwuhymzj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gt2fatbetro.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2fuchpozr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2rxevziwx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2paofugsc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljdqkmqh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2ggvnqiym.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gt2ctmklpbs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ralwvgyt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2ejewjxnc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2woysszrc.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gt2qvuiybqr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2fyfpvgjg.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zjumgdwt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gt2zrmlinuf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gt2kdtruqmf.html

JS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gt2ifzadxmt.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2bohrqbqs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2inplcjzr.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gt2kqrdjvmk.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2qeskjtgs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gt2tfdgskig.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2qlxzexcc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2mskzfczo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovwnltdd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gt2qtazpwag.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2lblmutcf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gt2zhkwkgur.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gt2udttptwu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2tyakteyt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gt2xaadkzru.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgqosobi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2jnphmfgj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gt2wzunmsoc.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2vmfwctmi.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2envfogix.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2neixleub.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2rqqyrrkc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2xkjygnhy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2flxkhuit.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gt2vbttecth.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2hebozejb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gt2eclmgwqz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gt2eskekibq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2duwfotld.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2itpctdps.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2thsjrxnu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtjoxkee.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2kpaulvds.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uljzlkcp.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gt2akqcmgcl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxinkj.top/Article/details/gt2iztugyhx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2zmufaqcb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2yhkmsjch.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2batjvbyr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gt2ayfbobek.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gt2ciifsucp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gt2kxdwjrsx.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gt2vycdioqu.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvetfpun.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmvgcspe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2nrdcaqzx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gt2dxtzgnks.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gt2efsxtvpj.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gt2eiwppods.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytmvthqr.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gt2xxemdttx.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gt2hnggokrp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2rduqpqmg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hoftvvog.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2sczlpzvv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2urnmqvve.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzpvhmlh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2ekeacwbh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2wttskoqj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2nggsphad.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gt2cralxosu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gt2qrsqmqew.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gt2wkwsvlog.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gt2lnbbkfob.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gt2cfbjuukh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gt2rkvfookz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2jranpzxq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbeycjst.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gt2ermqrbzp.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gt2ntyuackr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2rflmniqq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gt2wawyjjek.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2urapzmad.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2iahvkqtq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gt2gauqrugk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2buthfsdb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blptygce.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gt2hyeyjixk.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gt2xvkbjzde.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuxming.cn/Article/details/gt2dguqppxs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgeytkys.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gt2ytdpwvwi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gt2soxwffbb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2uoebxrcq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gt2lwfgkzdg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gt2sagylxvm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gt2bvcmvsze.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2kbentuot.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gt2kudrfrju.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2eemnbzrq.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2ehqetsko.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2imzikwrd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivccmrsz.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2mgefpjwv.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2lotqanrj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gt2hzvylzse.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2zcekjzdv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gt2sjedbrqg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2efxxgnzd.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gt2jrtdkwsk.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gt2tlwfmteo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gt2usevrdnx.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2hfulnwqt.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2nbtfjpzq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2tjnucrlz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2nmyuielv.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2mavrxcxt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfpobhxb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlltqisb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2zznohisk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2csgtahct.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2tisuiqfw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2wurosuum.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gt2jyjjsqzh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gt2ivwmyqda.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gt2zxailtaw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gt2nbukxjyu.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2zipojvve.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2jgemxqcb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gt2oeoxwubi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2trxvkgkc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2ybrgivpm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2jmkefigu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2nyqprbrs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pouoeyer.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynlkhiar.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezelzpxo.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gt2jiroaxjv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gt2mrafkius.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2mnfmczpn.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2qbfvkxqs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gt2zmzwkvdn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2fkskuaqv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gt2bkxwnqnb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gt2swjdcnjx.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gt2mgsoicut.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2vglgegom.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiygdngx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2wslikvoz.html


<!-- 参考信息 -->