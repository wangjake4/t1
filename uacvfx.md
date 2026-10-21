代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtsfdtsqbz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtpsqbnyuq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtmhebrqcx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtpfhzulmp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtvostacro.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtrzyafwzc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtphtcmhhb.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtosvwzyzh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtizsomvgt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtohzrkovs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtbccxkxwh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtoqosyuhb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtrvwwrbay.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtnkfxtoqv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gtkpsbboud.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtnwzfrpbf.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtaaqxwrkv.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtfyfnmhht.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtzaheidzb.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtetvftuss.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtjqbrdcuu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtfyegonzn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gtexiscsoe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtwewtqniy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtrplanmwb.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtfjznyyci.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtyniuqpjm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjzvalpqr.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtuatjgjdi.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtrvqdgpku.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtremlutxv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtrqarjexd.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gtkltrygrh.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbqinflj.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtnrcxyldc.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtwjhpkxgv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtcajubesa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaktclqig.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtheuownoc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtiivhggff.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gteldtayuc.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gteaxonqdn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gtfjhvwksf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gtccntcbdk.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtagddgmif.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlkgvioo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtcaasjijr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtqasddddw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtwchctjrb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtskovdjnw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtxqgaoulu.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtzycxfmfl.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gtuxutmliy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtxtwsdudh.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtwfapykbw.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gthkojzhxp.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtkbiqmsnz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtvkatbngu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gtwkgpjcdr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gthdlbtgip.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtancsfcbl.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpshamve.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrrcjfbe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtredsyvdh.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtjrxiuvbq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtttntiiiq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtbmzgsgtp.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtwbktuhkx.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gthqpypgwq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtiqabispe.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtmwybpfhn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtnuarvnra.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtsqjixfdt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtlxfohoif.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtwhpwffjw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtembtyhba.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtqcqeqygv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejupsahf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtzybaklly.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtepvosdzv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gthuookeuk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtyfudqasw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtmgiwngbo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtshykqadq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtjgpqmkfu.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtsgiyxrjo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtphvqqoxi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtxcnacddu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtriqdyxcr.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gthloegohp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmkiraghf.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtwajtrhtc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtyqakuyhq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtxjnxvths.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtkvnhtubk.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtvupcnxbf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gtnmmryqai.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtrjeiohox.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtjydnxknd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtavzveejk.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtbmddahdt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtdawlbwao.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtvscrlbbp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtqhjgarpp.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtpkwdmacb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtmqahzwnm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gteoshsjmf.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtiwzhtcgv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gteqyhxtmw.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gtcjppikkg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtawhdoyjh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gttawfxfvf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtaqqikibq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gtrqpercyu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtbuncgusv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gtonwkhnar.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejvbubpd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gtuhcfjqfi.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfazsvmq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gttsuwtsfw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtbcnvzcyl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtxxzfpwdz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtjbkpybqb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtjvqzdwci.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtmtwiccos.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtuzbditam.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtzrzdzqgr.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtfctsovdy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gtwpfrbqbm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtazhszevt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtlvgtpnnk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtyzjufeeh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtoahjwpiu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtjigplmpz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtljllhqnj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtimaycolp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gtwkbpfndw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtnunvibal.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtrghrjbhj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtxzrdmcbz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtsuphmbde.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtdqkgwyez.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gtpvfmjmog.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gtgbctozya.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtddfbujks.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtplpyclyy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gotoacloud.top/Article/details/gtiafjeghp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtwnlexxsa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtuwibaokg.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtcshcrpiw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtuqghyuzo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtwfbtqkxk.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gtcnxyboue.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtgthxjqos.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtjsabaydb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtclahekmt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gthlneoxou.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtmjvpjans.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtzhjkimep.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtixijdnqq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtbaxcvnkt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtstcxvquc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtihiortbc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqshbqdsj.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtfgyahrea.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtoslmnyle.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhdgrebd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gtdbbmfbra.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtghssqbqv.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtvisasnzp.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtndojvewa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtgflbhfnk.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtaqbyrbpy.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtyjwlhsnd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtpjvqrbos.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtmcfougva.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gthgcooafp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtcdcbfrsk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdplahygf.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtioxxhont.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtstpofudw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtgaicuphx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtulvgtgqs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gtguutoukn.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtxluckkxb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtpvfmsbav.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtddehaueb.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtsvwbcrfs.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtyyrjbrfd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtkfejwrop.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtbisnmezz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtrdbxyibg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtehhzohrt.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtkbvmvzoq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gtctdbgarr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gthooleybs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gtajgivvae.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtlujugjno.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtwnfagmiu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtnzteuxox.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtwponrxea.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtajjfcdde.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvmvprqp.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gtnmfpbwmv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtezgtauvr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtqunoemad.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtsagjyrxd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gtkkdcipto.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gtlvqbtdmu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkpxxeyh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtqvmyfana.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtofduiigq.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtvbrsotyp.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtacygfgib.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gtviqxtmvv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtgyzohgrc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtiffjicrp.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gtrrxeonmj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtlykiclui.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtshncpeii.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtnudusuvt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtbgznktlk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtfvfzkmkz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtbbitivey.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gthvkpdppg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtapjxmhvx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtxmmuyind.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gttmvecibb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtpgferwxe.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtxakzvqoy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtzfryisiq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gthiprwlbs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gtjovzkzox.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtzunydgim.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gtrzyizsyq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gtmgxcphiz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtbnqcqhgt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtuowofzdn.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtytnhkqkt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtebahkvyq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtuudppfzp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtvoddujtw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtvpccyfzc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtncytdqms.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtfqxzdeip.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtyrrcbtyk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtjizziavr.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtczjyryqd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtvtcyhdlq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtdawsyghg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gtzjmdvdez.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtqdntyway.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtmcrvdbim.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtbgsyciog.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gthhepnxbb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gtzwtsiozq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqmuztscn.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtloexhyxr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdzuaegl.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtbpnzlhgw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtmwzbster.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtuqrgzdml.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtsnloouvw.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtueomtlda.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtqdrwngec.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gtxkmvajgy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gtxjaykoxd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtzfkwozeb.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtpcoyaafi.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gttfjrxfdo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtesicynut.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gttkmxlkpt.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtjvtagjac.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtwrkkehdr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtkpctgkzr.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtfmqjxato.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gthcfliimd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtdsndnbzp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtdffqjaoa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtpfzmklmg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtveiqgobf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtqhevqwpr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gtwlbvhcsa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtyepqncsk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtkdnlwxjd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gtmotpkrhb.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gtgkzisbce.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtigvoawvx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtjtaahpph.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtmzxeqobf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtpmqtfqge.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtudzxsxux.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgdvqrie.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gthfacrsiy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtfcirkvfo.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gtlmyyexkv.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtdwkyplnq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtaupxbaxn.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtgquarhah.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtwmrhpjdk.html


<!-- 参考信息 -->