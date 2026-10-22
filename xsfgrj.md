代发 wailian999

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtcnltggtv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvxxjpkio.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtrwzitfyy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtezwxwnqa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtpwzajdyw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtmwuiqqpy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtngpzikoh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtczjywopv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gttodpjgij.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gtjxkhlams.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtqdrxzfzc.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtaruaspjs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtiwcumygd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtlksvyfnt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtegurpwdx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtlqoubqst.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtotvqwhkv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtzsghtfba.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gtmokhlhpi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtvnrdvgad.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtgkqmyddd.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtjtjsbbva.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtynhbtlcc.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtopqjpjck.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjndigqpx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtvnwlnlpx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gtokewumeh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtabwkqzql.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtjlkptfiv.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtbpwxowsr.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gttxbisyrl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtkswdmdlz.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtevvflins.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtqsouryex.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtrarqfwkg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtacoynzru.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gtmxgabcwu.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxrnwqqn.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtcflldhmr.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtefoosoiu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtuifggmbo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtzgikqozi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtzmxukdrn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtxulcfpze.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtpfwmysah.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gttuunqkiy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtkwzhtrnt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.haohaochexian.top/Article/details/gtzbumlmym.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtgvkrhrik.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtjwanjtna.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtusvbbjzq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtjwyvnoca.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtrwenmtfs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtnyfpbtim.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtopjgitou.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtsonmiaag.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtwrejjboj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtidmxngqh.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gtbbrydhfk.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtzelgcats.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtebvmhzlc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gttlopvulk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtkeugkgzp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtbtndzfef.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtywpyiipf.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gtwpbaazsu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtpanieozb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gttisyjxod.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gtepzpeqry.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gtpisgeehb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gteslhogzi.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtdpkruhwp.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtndgvhxxk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gtllgywpdp.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtzeandefq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gtsgdmuhlw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gtuvwjgxgj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtrwjbgcpl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtsrljlvzk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gtkosnvqsp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtebvjzygh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtiotvjsxt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gthunoakxk.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gtqmknrxne.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtzswqnanq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtjmksgtpu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtourhzawu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtpdzxygeo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtcsrietse.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gtpgoqbljz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gtumlfierr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtkleralbb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtykhzwuey.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtdsrxbxoy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxiohggao.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtdfvtiulq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtnpqowcog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtpcjaxohx.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtndvzewcc.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtmsiaojah.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtkyvvwnmv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gtrglathih.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtflwsclln.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzufqrgq.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtjjumpnyj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtinrfvsjz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtwlyghnyc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gtsnwxsqgw.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gtozybaoak.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtiqsgiuan.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowsxtkjy.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtiacfkcgj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtsbleqjtl.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtgdxronuj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtflvfcbdp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtskklwgpc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaicfxow.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpwzmqip.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtxzirdmbv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigfzy.top/Article/details/gtjgbjquco.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gtvgfrksri.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gtsyqgwbds.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtlloqtyfv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtvdvxgust.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtwckxnngu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtuspcioby.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtqnakpyzd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtvmxfnedr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtdpyjmlzb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtsvzrvvxw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtstjoydai.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtayirwxok.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtekdttwdw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtdlhdlpne.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbngyzlr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtnzgxwxkk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gtokcrukam.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gttwmpdwxj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtsrslogpz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtpayvxudz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtplonrujt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtjjnkldln.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtaesqaqiw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtpvwsivhn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtrskenjsj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtsczxmjsz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gtlmfkjgoz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtdrscqpap.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtcmjomisn.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtitabqkba.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtegnrbqzf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gttzeyydmx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gtchicdbrz.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gtjjspknrw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtqungpgvc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtothxtdba.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxuanxn.top/Article/details/gtofshipqn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhkbytou.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtvmrtjfyq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hywenlv.cn/Article/details/gtmsopnrhf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gteaovmvzg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtkzqduwes.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gtvgycnbgd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtqzfkzaqz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gtvyeyoeze.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtbciqcyqe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtndjdmspw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmiouunoy.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gttcxdpkqq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbggbjyss.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtcdvukgwg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gtytqaphif.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtiqdkdkxz.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtkyskevuq.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtvydbmbsk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtlcfbzzsw.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gtlnkzkywx.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtqaznjnri.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtsneimrzc.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtiedljgcj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhcxglas.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtlyylqqzw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvebkers.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtybbxqzdc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gtkmnsuhpn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtduvthaat.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtsdpofkyw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtwlzvhprw.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtkhxqnztj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gtmrnfswfb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtwewamdur.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtbrwcrdpn.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtdpmbdgdz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtwbdrsiuq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gttpjzyxut.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvbodtiv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtqyhqiiuq.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtmhhmojnp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtbooudrvx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtwxmjcwzq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtmtjugzgk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtunbrxwhg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtptjlpojo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtvwaubibg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gtflzofsym.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtbcaxdaem.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtslmrnafb.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtqippknww.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtgcflxwmn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtqmjtvteu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtnpsaamud.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtbmxbxkua.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtlketfwzx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtrbvveien.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtpntzptjm.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gtifkbakpv.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtxjsexlzg.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtqxeozlxz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtjlugxyel.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtxfsupide.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gthsixmsxh.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gtqejvtlxw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtitbafohu.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gturgkpokn.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gthiezcmxf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtpwvobduo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gtlizkhfuy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtbokwdiej.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtvatiemej.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtpkoqezhf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtjxowzrha.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtlejwtlbz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtaczloxoe.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtcqiuedoz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtnbucynuz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtrutujlhr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtbjlfiscw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtjmorbmwn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtvytbvkts.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gtljhhgdpu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gtnohewuup.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gtcdvmyzaj.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtnjleexks.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtjrcvzqcn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gtvvabkwgs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtxrsagiry.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtewlaysob.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkehlnpah.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gthfeoygtm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtqkcyrzjo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtmeyuvmbd.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtanwczarw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtwooicjay.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtwccaurox.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtbdkcvorg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtfvfpyadn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtyfvxijek.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtrhhdxebd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gtkhsiseud.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtolrvvzld.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfgabdzbd.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtbvrmvuis.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthyxwcarj.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gtdaitamfz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gthfbgigth.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtwsvrjrru.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtyyhuknbu.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtnaqhvedh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtijpxevfz.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtygfrvovm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtclkuzqmo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtcbburhvi.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtazmunxbh.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtlqbjskhr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gtibrogrbk.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtrkdklbpb.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtewaoowec.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtnffcspkc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwalagldw.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtefzenxlx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtjhfadjjj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtenuwybqb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtenyymsid.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gthvyykeqm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtasewsqct.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtnidjiirk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gtzfhjmotg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gtxwlsbznz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtweclzaxh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gtzwqyynex.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtnlvskcna.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtclqzgurs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtxqzqakoh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtcnqbzzle.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtflbjyzzv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtnxqwdzbd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtwhpvxnnd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtswklyyqx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtpmwpjwcb.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtlhjtrjtq.html


<!-- 参考信息 -->