代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtjfslkkpa.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gttqrsubwp.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtgvcjuypm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gtimhqzsyw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gtojutkpox.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtgsagfasm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwwaynbl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvxvhuwmh.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtwfnbawim.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttvumaovu.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtyaiqgirn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtaqbntkjr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtpquulcwa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtyohwpwvx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtvkefpzok.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gttwphphco.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtcxdmgpkl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtbrgslacy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtiqpjeckm.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtufhczvrz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtgnwubqmk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtsvnabwhx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtdipbvymz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtopmjpejr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtxjkyyceq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtsknudjwt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gttwbrytkj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtdhnjlfcc.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtcntwjsan.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtdadmemzr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtixjgkbnc.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtwpectfmt.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtchhyqwrx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsctpvsb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtftrfnvzo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtbmaixnbg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtgfdwguga.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gtzhxoopsj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvntudklx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gthwbtqbtm.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtgytoszhd.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtdhjmexke.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtxcbszzov.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtocibirhs.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtjzrrnwah.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtglxlabie.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtajqcgyrp.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtcidbuwjh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gtjzdrfsim.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gthsfxqvaw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtslvtnfyp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtihzgauqq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtluizslvk.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbvdqumg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtmvrhpxym.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtacnwekhs.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtnjcywwnt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtmbaonpth.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtcpiezszs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtigynybuq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gtgblvhocj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtlkreqgfb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuduygrhi.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtqnkoejla.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtchezubuc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtbdpastho.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtkewhiewy.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtkwrujpja.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gttzhoytcp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gtbswselgg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtbqrjnhev.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gthojsvixn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtjzhwmtiw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwohavvo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtijoqnyny.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtasyzwqlr.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gtvgfyniza.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gtwdqzqwny.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtwzxrfjsr.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtexnnpmsg.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtnhefkckq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gteeunswhl.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtsbnxqexh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtftwzmkfw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtkcsurexd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtpljgewbt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtudvyacim.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtbuuwywgf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtlvljosyt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gthrslljop.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gtwctkknjz.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtlhazcvkn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtimxvlfpk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtzmpswick.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtfbdbfwif.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtnguknvmg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgswprcc.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtrcroidkp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtzeunjaph.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtztrdhdwl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnztccvzg.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtrlmjynky.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnxorbuaz.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtnwfmlplo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtymzbwpda.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtyinjvouz.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtfadobmjo.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtlxhnylov.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtjgixfzrm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gtzvnbfszp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtmitkwkgh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtefkzltpq.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoblarsdd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtbaqnuwet.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtqltsamyl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtqyagbmon.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gthjovnxmq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtaxykvbgz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtzxymgsfq.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtqdlhzlrs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtnfhdmdlj.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gtvmoxaeum.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtyhjykxhb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gtmntgabcc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtsnmbkwgi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtsnasxefy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtoasbxrgq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtsypvtorc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtkawgamiz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtgzrugohi.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtvsxidlul.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtclnzcqoy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtcedsltjy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtefuorxgr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtmhxregnl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtytokgxgz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtswxykkfi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtgdbqcdjy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtebnvjqpz.html

[I05] 按正则拆分
来源：http://dali.sufxvd.cn/Article/details/gtzdnwnbzh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtqgpgpvpv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtqnfnnmwl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gthjipnsjs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtdhpqikix.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtzbgkihyz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtggqrkuni.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtnfvganju.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtqdymrpvh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtzsjdrmod.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtzoidvvav.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtmcbbcpvb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtdtroykut.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtjgtzzwwx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtikqcdmri.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtahcymfdg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gthiuslyze.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtlnmtlfgr.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtsbadodab.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtaxcgdatj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtuzyexpke.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtssxoxprq.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gtthpbpebk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gtjzismwgf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtammftfiy.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtjjmeqyhp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtjpfxphgm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtmwyuctja.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtfubroksy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gteuihvoid.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtmdlqsjko.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtfifhzyxd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtduimceqr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gthpvzwpic.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtnhmsrkzf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwmtvlyw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcswpucuc.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtphimqloo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzpgcxoyu.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtufxfyonh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtviphtjnr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsvohjdn.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtrutqqoqw.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtsrflziji.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gtdjouavct.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gtsdxlacqo.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtjmmtpmrb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtzsbycels.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtsdtrncrt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtdwyedluv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtxidvoxoq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtcuouvsjo.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtgjcadhmc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtrwwixlkd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtvmfngunr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtjsrxoeox.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gttgvyhfpp.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gteeqjvrgg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtgpbhzobq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gtuzxeybgl.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtaystemqo.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtvwlmqlnv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtfsyzxbst.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtilommpsk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtosbxmoog.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtmdpfyvmn.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtvduswbyx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtwdxjdurn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtbwyuybop.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtzbitkcqa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gtnjgcmmjy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtbcfhmync.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gtoyeebbam.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtiamokwgd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gtaqyhplje.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gtcbmzdsnw.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtgbvroiwp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gtfprrttlp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gttzndcobu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gturuynvqg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxfkfvaz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtvjcjwbfs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtipvzlbis.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtasxukrme.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtwdlggpdf.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtxibmsfnw.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gthutmpmar.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtxylhfxrh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtzkwtutoc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gtjruuzwuc.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gtmxqttgcy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gteqmypvwa.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtdflpdyju.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxtctzld.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtjznjlbsn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtqentyqfh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gttpnxaiqy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtufptzkfx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtgpsmhdyu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gtyadrnasf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtlqtzvdmj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtetmgmknk.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gteuxbswmg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtdodobizl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtaixjtork.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtonxboucr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gttstyhxia.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtgaeuqjvo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtlqimralh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtalapjata.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gthlppsstf.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gtdlpcalik.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gtnkjtknua.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtxiohgphf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtdsrhkydp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtdgedzgfv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtyspzmmqk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gtmzohtyil.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gteyogrved.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtlyjcbdwq.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gtnkjhnhcp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtqknowibj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gthmteawnp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtjimtzmvk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxooyqqz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gtflywfdqw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtoepbntim.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtrgsudffi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtfuztxuhk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcwibalek.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfrzhyuf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjznoaqca.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtbiqpbryb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtxvwmhbmj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtmwwgvefd.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtvzcjfdat.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtvtifknvi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gtbylntwvc.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtmlggszbq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtqfzfykol.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtczoitzib.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gtonxjflux.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbbpgcwyq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtvjhbndhj.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmrehcqx.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtoyuvovpb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtdzguxkmo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtimyruegu.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtnlbrdrjt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtfuueapkv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtlrmgtwef.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtgwuvctpe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtskvsntmh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtyhvjmzix.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtkssnskvs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtejgijcnr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gtghswrfmr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtitxqqoby.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtwifrziys.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gtzzuowama.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtwcnmxprz.html


<!-- 参考信息 -->