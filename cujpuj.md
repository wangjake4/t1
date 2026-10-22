代发 wailian999

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtlikzvvus.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrqiovbv.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtkvbrnkmq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gtmeglfpgj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvflhyuav.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtyoiuonro.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtrtewnljs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtechqnucn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtzfabdjpf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtgeacluif.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gteplrrjfq.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtzxmjpscw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gtapeyfeqy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtzbouytzu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtsenppiae.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtifdtwqtj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtmaxclikj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtzmcoasbc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtstwlexwz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtimdnzauz.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gthznyebuy.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gtxkczboui.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtwfcibrjp.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtvkhvbnkr.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtchnncrzc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtweepavps.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gtlkkkldcr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtlvatsxct.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtbpwetifh.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gthhyocsan.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtbgkflgjm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtnsjaoalc.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtjmlbqgkk.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtxroezmud.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtwoblomes.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtafamzozd.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtusceibml.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtceerfyjw.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtnakwuunf.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gttjegabux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtuutplxxg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrkdonodu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtjmhrxbtg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gtibjgykxh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlrtbowp.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtlnlyaayv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtvtvyrfcg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtmfstixov.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnzenswp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtnpfescmi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtzexdgxsy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtrpydaqss.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzgokmbh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtrwuncivf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtasbxshlh.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtznlszqfj.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtnyjzuybu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gthribzott.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtwuouejel.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtlewvrrgq.html

TS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtnfiykiba.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gtivicbmhr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gteahezvmu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtzktrorvr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtwhazdikt.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtgdacpzsr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtikapuoxt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtyxylmxqz.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtyrbkrglz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtohizldfk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtuykmlvvm.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gtxkeimprd.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtuyhgbopn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtlctvinsb.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtfxfjckiy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtoatrdgeh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gtnychqqya.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtnukpzihw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtcmdpndvr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdjaedrw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtdbxwncqp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtuogrjcfk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtwoltqpxw.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtmwbqjmqx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtersghnvn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtehwkvitz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtmlqstvdq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtnyzupvtx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gtgntvjmho.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtbycyqeqy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gtiauqeqvh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtgadrtdsy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttsaxpkah.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtwhrzvmpt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfpjkfmre.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtprabderb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtghbevdbg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gttnkohldj.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtukdcfcxt.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtvwgszkis.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gteawggeyt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gtzdshumlc.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtoffdhvna.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gthrpepcpx.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtjeihgqzh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtxqdgycuo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtdoteiiyq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtvocgvumx.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtkoymunmz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwayfkavj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtspawrksw.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtojfcbhgs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtshrxttww.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gttpuxxxnf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtoiqcwuhd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gtiegyeslm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtbwsztzvb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtzqvfkgiw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtkkfuawtw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtwiobayed.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtsubnotgl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtbsesezdr.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gthakpdvwp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtojhztluh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtexrkloyl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtwgygpvbe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtrnsfxqjn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtkqtghqsb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtiyumdtrf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtebhvfzzv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtdenxfniw.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrrtxjev.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcomuycpt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtfhszzjxg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtbueconav.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtjhyfueyj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gtmdjzhnof.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtmdacawux.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtnkypwgra.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtqychxcex.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtzdsvesod.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gttuehshaw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtkasidcbr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtiloiocyj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtjfcgniol.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtzntzbrys.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtyyprjtfi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtooqeenvh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtbkbplmnb.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gtsxotmlib.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gthlwfblbf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gtmsnzrhwt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtshstruny.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtzrngqrnm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtzbbvktmo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtatrwdkqs.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtvjihkdwu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gtwxwaeoai.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gtpfmbwufh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gttpkmrxri.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gteyrzbjqr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtrxeykrrt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gttytmfvuf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtsatzrurp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtczthhtjc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gttfwgwait.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtumqfpqty.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtiuqaeyix.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtpcfipvbu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsnnevpcy.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtbxwtsjzo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gthyldgvkd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtyhprrtgf.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtmajtafyo.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtuxszriqw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtgbqujlsx.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gttymxrqlc.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtpdhrvicp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtrcwtqcwd.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gthmzheblz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycfpcawa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtbsipxwik.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtjxhxcwwq.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtikqqtbcv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtgaoarytb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtdwrrnfij.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtrsrjsjta.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gtvbfabvrd.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtjtmugmbo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtwdmqafkc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gtbwqapdzf.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtmqjawpjs.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtkgwnkkdp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtwxbbfpwb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtyftqaxqw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtzcpayejm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtmngoiniz.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gthywfhkth.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtaejxztob.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gthkvzqzum.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtjkmhbscq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtiqeniwhi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtwveapddl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtqdlceoiw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtrqglcwkb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gthzglxnol.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gtunptqdbl.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gtysmpjrsu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtufcxrmxc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtuuzgrrjc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtsupscgpx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtzwnqtlxl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtswmpdiex.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gteqijkmxs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtovccmfsk.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtyaukaiqr.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmqdzcdo.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gtpswmpjzi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtgalfcgsy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtcsvktkeg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtfhaqasbb.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtjgfjdgja.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtetwhedhe.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmzovyem.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtbglulmxj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtuswmqnav.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gttrawozva.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtmpfvtxme.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtwomkjrbq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtolhtguiy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtrojcypgo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtmiekurtp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtxffrojye.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gtovckqxtf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gtkywlqwyy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtpjvbwaga.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtbycvsiad.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtkhxptbeb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gtajvbqjts.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gtmwahalxv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtdlplqsdd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtaoqskehk.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtcjynsnba.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtkfskwuio.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtczrmsrha.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwadmkor.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtgalvmite.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gtdrxgopcp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtybhoqbre.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtxwtcvygo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtkwqlvkcg.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtdxgkutnl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gtluuisovz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtxodnstak.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtikeyycui.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gthzzcktes.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtdxoqjebw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtuvsleche.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtainxdllf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gtcicazypq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzznuexpj.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtubdyihgi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnvuchrch.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtyzygbavv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtwyxxcsqs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtcusjswuc.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gttknbkqzk.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtdaiharnb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtjtgufppn.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gtauynjgey.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtzsualmov.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gtsnxbwiqr.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gtefmmfmoz.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gtlzugzyio.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtbfbptugs.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnylxboar.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtlgspqmre.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqqffzgg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtrtyzegvc.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gttkuadbdw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtidniwhgq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtpmncrhcs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtpoqqohfm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtliphuvtp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmosfpsha.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtwfjtqhyu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gtuarmabjo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtwjldnktv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtdvvralub.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtoekfpkkt.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gtswvvmuzx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtvungbevz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtailzpaon.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtlwecfdpp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtdbvfllaw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtigjxkdjc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtfamejnrw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtiuyystya.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtztknmeyp.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtjgusgejx.html


<!-- 参考信息 -->