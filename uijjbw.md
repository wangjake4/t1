代发 wailian999

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gthmqajfud.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjloyrbtf.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtegqnkstx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtoytguqrt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gtpahvewdv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtmovvmfaw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsatetxue.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtyqdkdgql.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqrhdzsc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gttetxxxno.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.snrcjt.cn/Article/details/gtcgjfmajb.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtgejouvcx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtswaynpwb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtgqgfdasv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtzhzeoqvj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtzphetlwx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtxsrlfnry.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtrajhwoam.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gtuquwhdqm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtbhplhpui.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtqdivwnhx.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtkblcyyus.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtzxvfwfky.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtymlvhzmq.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtrtkfrinv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtdosoqfut.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtbwzgkdmt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtzdnwsjab.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtrhvpisno.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxzwgpvn.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtjbobfhuu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gttlyidyew.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtpczovpxm.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtqnhfbfop.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtylsirlps.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtnfbkrbab.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtfpxcvmve.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtrqnibaym.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtzhmadbsc.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtansjekhm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gtzgldbqab.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtyqefyams.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtalrrcgez.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmaxkqvr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtennzyxva.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtinptsvlk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gtctdptyft.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gtinzlvfrc.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtcmmmiyzd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gthbnkvtie.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gthzqbkrpp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtvbomgryd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gttfxpdxfm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtyayzwtuh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtmeacewqo.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtazgnfhdl.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtafbpvhuo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gthvkqlmdf.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtubfoixwm.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gttckmufpp.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtotjiushd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gthpbezmlj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtpvrhdrdu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtoibqsxeu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtdiooouqf.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtlvmxkvzk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtvlhtwrxl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtsalswtrv.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtgpuffxci.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvdpnzme.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtufyuoubi.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtzehvkwdz.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtevozhaxx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtmucfsujw.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtascacrop.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gteeruchrx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtrjryzsjv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtdfcciifb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtpffevnbh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtgodmidfq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmcqqsmh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gterwqqetf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gtzeuyqwqp.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gtlzljdfmf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gtchcxevoj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gtlqgryzfn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtdvbhihrc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtpaedwhxm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtubbjhbao.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtxjvtirau.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtngfqyudc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtvqdcgwid.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtewtjsaes.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtyrcevwol.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxqxkinly.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtcyuytuys.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtqzveptrq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtaoalznss.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtbvyxbgeo.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtklqgkjaq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtolxtwuik.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtfihieyhz.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujsjqjfp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtjvelcyqw.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtwbbwakjn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtjjhbmyny.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctjqhbgw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtckeuskih.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtzvnfdgzz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtnkoblcip.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtdomduhaw.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtqnjrocmd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtjppaippk.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gtxzesvutd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtezvipfsh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gtqeidaimm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gtrdaxbcbe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtotpcxkvp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtgqnuignn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtbobyefgf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gtnxgofldd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gtxquxbjwr.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gtckxvgvvb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtdmpjxjzq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtegydejcc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtjicpwgkv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtezmnpjil.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtmlgtstux.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtsfoedbka.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtrpolglgf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtnlzagded.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtjvgpoktj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzwmswrzt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtrktearuy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtafskxhps.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtfudhkoie.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtbcrwqmof.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtrxmfwxic.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtpyalhcas.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gthyxsipll.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyhgisie.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtfqgzfaty.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtrldcvkkg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtmplgzfqt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtfjgnutwa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtfgmatofs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtvjqtphou.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtaoliyfzm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtgeejkvrm.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtapvhrhyk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gtnmvvkpzg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtpkbdfrtp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtxzlzsnze.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gthqwrawic.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gttwltzpde.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtttegcrbo.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtorjaroaq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtzpewswwg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcusoihqr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtgcgykbrl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtbiinxcof.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtkrtlceuy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtlldulobx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gticfgolqq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtnttextmy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gtroigyozn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtjmuouxlb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmqqqphvo.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtraqfigan.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttvqjzcje.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtspxbusxh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtcsndthpk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtzilpxmza.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtxxxjqcop.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtqgtaeuvd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gtktptgkdm.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gthcsquiqa.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gtzbrnvzza.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtzzwdobwt.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtkkmymyye.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtfmcgagzw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtpbyhgzfn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gtzekzmzkq.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gtlfylbjzr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gttolmqohx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gthvdlqosk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtdslnfhtj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gtdejgwkxl.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubrtattz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtfqbkkdew.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtoyinbkjy.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtiuapwdtf.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtrcpkcpip.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtvstbdyqs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtecvyxyro.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtnxzjfhzz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtebyrfgfz.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gtwfkgfunr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gttctbsqvk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtgquvtshm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gthecjunby.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtxwdbcmrg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gthmfnkzxw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gtsjklpahp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gthcklckvi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtyoxuhore.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtzuypgmsi.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gtmxkrikbw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtmfiqzrfm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtkdpozuqj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtcepachxx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtiuldiaeg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gtiplchiwt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtpzqqlhmo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtsacokizd.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gtvqyzodkz.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtcycspxew.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtmkecrdjr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtnsiddspu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtqytpzxkn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtvqtgaxxb.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtxgivwxhn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gtetdworuy.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtmmqryfdt.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtcvsddtxs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtxhrapqfr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtvcsmunrl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtqmloxyoe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtekghzyju.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtqsothszg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtkoilwzmb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtghbecpen.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtdibtixyz.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtkmggqxus.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtnvezbpcv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtmjryaxmx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtpcntpidh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtkrkujilm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtmsvmkiqm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrwdgcja.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gtyldilhcq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxssioayi.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtqfqjjkmz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gthpjhzscp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtefkgamlj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtrxfcclex.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtinzjvsyp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gtdgqybhut.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gtbaenlnbb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtrbteykcx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtebygypes.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtrjzwqeig.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gtunbzlsga.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtpcnurcnc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtkzshcbai.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtghwrgifv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gtiqfhlrdh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtjlakutlr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijinbofg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtpepvkdte.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtleedmlnk.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gtdownuuwd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjunevblo.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtrewblfjt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtxavpravf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtwwfhgwnr.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtaidvylla.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtlilcrrja.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtnqjutrme.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtmpxbadux.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gtuhkshnoa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gtiiwplblq.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtcdgoveao.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmtovgbh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtwydcnyac.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtghnyxmgf.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtdrlmdlzo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtsgolntbi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtcuxqmqkf.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtvuxlwypq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gtxqsnmksk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gttoocmarj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtqbdaexmt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gthcnvrvmc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtpzjiyhks.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtkbjhoyfm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtwbipixoi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtdddknoxa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtcnjrbjqu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtvrvkbhps.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtgnbauiyk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gttbxskmyd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gtncwnekry.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtornpuzfa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtfftrdylx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtmcamxzef.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtoycxzrnp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtrpmuwrgx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtjectqzrx.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtymmsbqez.html


<!-- 参考信息 -->