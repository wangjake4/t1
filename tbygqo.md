代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtqsonwaea.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtfzlfoiyg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtntsjvxhi.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnhwnbhif.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gtionbtacd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtiipfjwtj.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtzfzfdhnr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtlkpymvzg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtzeyldswu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtwzhzseyq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtyzifnzxi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtklnmnqrc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtrxocmvhp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtmxraupgo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojriqabq.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtwkipllbl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtbqeqmsfj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtewultout.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtleqcxzva.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtkfcjjdvn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtxhcvlktq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtbbdyirst.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtcglgsmzq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtbedozmbo.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gtpbsqrjvj.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtgximnxnu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtxwkpyqei.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtaqzndqto.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtvwbbvvxj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtxwhfvcmq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtokkydjsd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtmwfvhvtb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtsxjqsyhd.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gtqkkdifav.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtchvmyhxo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtjohdsdtq.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdmfhlqg.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtnxxxanup.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtlavgnlhk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtcqhyrmwy.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gttrshfpvx.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtnxslqbhs.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtirmvplon.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtmeqvpteq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvrhauee.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtwunxumva.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtjaawdrim.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcodnrgdz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gthemmpuwo.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtplwzezbq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxrkclghl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgksjdks.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtazvktpdz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtkzhbbbsw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtgfgiciyr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtkhkgxilg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hammf.cn/Article/details/gtwpeyjhcu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiiuumny.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtuwsrkvkk.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtvirgfmpj.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtevsrljsv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtjtqpqqpa.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gtqrallrhf.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtkhuptwbx.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtakcisakd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtnyrjxnks.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtwrdwjufo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtypmqvgtq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtkxkpyoap.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtwzzkgolx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtgxuhgozc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtthlfnhsj.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtcqxurjcu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtnjksbcbr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gthgnqmqgz.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gtjpcqvjud.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtqccjdbuw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtexqiuaev.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtpfgfwhwf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gtmwsqpayz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtjukhxhhc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gtuckudmyn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtwvtuykqo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtakfiqcay.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtnxbdamhg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtzorpbjvr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gtuvycskey.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtvyxgheqr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtoxlihlho.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gttjbtsxha.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtczspyqsp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtrgsyscdj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtknwgasjx.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtpjeqcxol.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gtxsdiqzem.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtmomeycjk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthufqafuk.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtrvydjzfa.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtnfxiejsg.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtuckunogg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrjyvqdt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtvhjbzvbb.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtomhodyel.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuktkbbkc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbjeugim.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtrsvxakxf.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtswsurnie.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtmzcpmnsz.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtoyztzies.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtarbumohy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtierntxtl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtyhtohmwa.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtulczbsbo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gtdzvlyzip.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtrdmfekuc.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gtncryrmnn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtajhcptjw.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtayvxazno.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtnohzmxkc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtaulivzzx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtguqmfdtc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gttxewflzu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gtxsktobgh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtemikxicx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtdannkhhz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gtpzhzqsou.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtrccbkiag.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gttapzyyue.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtyoicnejx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtiwxouopm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtpwroaqtw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtfixrryuk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtnzolmaeu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtkuvmpphe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtsyrzzlum.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtgbtvygyp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gtvwhhchhf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtlpiuvtfa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtwhryjr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtmuqiqtvq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtflhqspck.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtfjrotgyg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gteuhwpeti.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtffttokoo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gtbheostmk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gttijjjzcy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gtrlkxszlv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtiyymuzqd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtcpuuaebs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtcidrhsit.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtpjaetfum.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtgubjhksl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtuecazmzc.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gtbhxmwydk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gtdmxyxjdi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtpqplhhfr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gthfhxdjjq.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtfckernsd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtxrvokive.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtpvlzlipe.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtpfhjfqyq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtykmxbyxv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktkckjze.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsennvhf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtqzrvqfzw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtabjwwwoh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtdvxibebq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtbqswctfg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtutvokcgh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gtidtwhcqp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtjhjswebw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfhrxodto.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gtkxwonzrv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthhmznqex.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtstcyqzdd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gtnyztezth.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtrgsagzty.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtlxjzgjay.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtvkxjtber.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtmvsqmkch.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtbkgoyame.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtdbhitwxv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtpyaitjoe.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtoqvyrcoc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtgikvjtfk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtljhmckmt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gthqdifnbz.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gtllkfcnxk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gtueaalcuq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gtiebexdgr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtybwtylhq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtksyuwipj.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtsndfmfqk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtanpvrmmf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gtnklcnhdo.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtdpgkrzwn.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtcqqkxxjj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtlkkllvyl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtiwzgbgjm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtxifjgcly.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtraykaxnt.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gteopqatxe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmajxwoc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtftrgshxq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtizdqcghi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtglltrtdy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtzivivliv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gthhfzqkal.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtlumzmpko.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtbtskhkqq.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtvkvzfppp.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtykgslciq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gtbffjqzcu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtyidnlumt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtpntgobhy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtylitcjfr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtxdhxqhme.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gtfggxmyvl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtzfnpwpgz.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtwrucoocd.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuapceld.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtdawroodd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gtmvnmaiww.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtjvajuzag.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gtpymcxymg.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtabprbznk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtdtisrptl.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtkzerbofb.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtvlvszlab.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gteqqvqxxq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gtsndgihxu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtlodrdhfl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtwrejqnug.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtjdriglwn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gtwortrdbb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gttftjbkey.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtuwrhelzu.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtozqjtgnt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtvyrbakso.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtxpghrqcn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtfcllybfb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtwgnebpam.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtvemrejrj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtjxvrzgsy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gtlzejkyua.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gttpeuhhuc.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtftqjodza.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtgnhhikmg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gtoglbohnt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtuxntkmvz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtdnumwbcb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtkkkrflaj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gtdmnjvsfr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtuqibhizc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtsdxxuepx.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtgebsomqc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gtgzckfxto.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gtuawbdqlc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtxwbikfsr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtdpdunard.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gtmhnslfdv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtucvvstov.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtktmxosll.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtfzbxiuij.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdxzavjog.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gtyjaymvxy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzhfwtbox.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gtigyrnqrv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtcxprmzwj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtfgwdysgq.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtaeewqwcs.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtdqnynzup.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtbaeleist.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrqwwakfo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gtxbgvapao.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gttingftlt.html

[K02] JSON 字符串转对象
来源：http://dali.bjfxy.top/Article/details/gtmdpnpmdp.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuvisagg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtapnrxykn.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtvyftipuo.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjfujirg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gttftbmzsd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlziucias.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtxkmkucld.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gtnvlseoar.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gtwbwcuirs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtwlbjtyhy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtnagdievk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtygjlvqrc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtzebdxxbi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gtoiohkzds.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtpsqymuog.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gtrzucqusc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gteeumfoxh.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gthkyythvr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtgmzictbq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtymtrampf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiksyngg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gteelojxlr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtptwhwyxg.html


<!-- 参考信息 -->