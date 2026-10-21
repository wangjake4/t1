代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtafuauzux.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtarvxhfrz.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtmdkiedkr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtdowqzpsn.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtguvyvebi.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtskbtjzrx.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtngsudgsb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtriuurstt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtacyapdxg.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtobbblwut.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtpaxuwklk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzwtssifj.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtchoykkih.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtiroxfwvk.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtpcupamup.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtlubuprxs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcazehtvm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtritfjocu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtragdjnyb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtviedtrkz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gtonnhgwqv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtavdadlno.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtholayclj.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gtaixosixr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtylgtmofm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtmgjsmwej.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtrcwwzdjq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtdufuvicr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtdqsbosjd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gtluwhmmdi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gtpyniglpk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtmzospzum.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtcpzmstsm.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtrafdreku.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtwsxmlcuo.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtaqjlywdx.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtvjmtzlmw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtweityyze.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtxvopucmc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtuvyqyuyx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtwtvmmidp.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gthygrvwzk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gtrsqjeivu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtgcntipwr.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtqfxuwrza.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkfbeeyfq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtoowgcrpt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtfuogsfps.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gtdrzbrkxa.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gtpqylmyrm.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gtgreoqhit.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtscqzipai.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtryejotbz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtawrwieem.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtxwmpxisy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtanngazdx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtbnvygzqx.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtxkwcazar.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gtpbwxtuyi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtlertwjtw.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtwjpbpdmj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtxbvloixh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtjahkazon.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtwbipythi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtkkeehcru.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gtagqxffrw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gthqwisptv.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gtmimxbhwx.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtofcjshko.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gttyziskkd.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtmxynwnpo.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtrxlsfjvg.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmbkblfy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgktnpnl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtlwmbdryw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtuastjjrg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtfbxebcib.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gtjlqwoxmd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gthbdmifrt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gtnjdmsaqy.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtmivtlbez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gteoxzkboc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtwqgmijku.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gtbharxowj.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtqnqtidft.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gtspxyqoqc.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtvxiwqrge.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtiurknkxg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtrdrtooqj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtaoeksiaa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtijhveffu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gttlxytbri.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gtobrxeqqj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtpkdwfaao.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gtokchwaqf.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtpvgtpsik.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtvzexrcnx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtjlsgctdc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtcifgsczt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtvxejztfx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gtktnviwba.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafvfoion.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gthxstckqn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtborkwgho.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjsuygtcv.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gthniejzdj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttpxwtluc.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtxoicyqrm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtywujcfxt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtkgpnezeo.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtlwwrybbj.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmcshiedr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoshrsefo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gtzcfuiioj.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtzphcfdsm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtujfpjcxi.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtfveuxnni.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtrmnpyjns.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtjznrzzkh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gtkxzloyqk.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtptgklbty.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtvawghxnk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtmnaxgflh.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtsemsutvm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtcnjlrahw.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtnduyikfk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gtwrfzuqkw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtgzbaqyry.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zycfv.cn/Article/details/gtjydkzgej.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gtwevfyppf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtshykxeja.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gtsvhoyqyj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gtwftfghkc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtcciewtwr.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtcdganrhq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtdgcuzvmz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtuqsgboii.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtrbyofndz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtwqdbcisy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtmscudxgb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtwgzprdzn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtfyxbgdjj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtmsuogbuo.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gtubyqctlg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gtlsfwobrq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtrybmiyck.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztzwurbt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtzbfxbhnu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtkycaerxf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtwarsgjvc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtqmbnvufg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gtochebwyo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gtvbkgordy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntyldwdt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtsodmpxdt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtyypnrimm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtcexbzfmw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtzqpcdvgd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gtjigrtgxt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gtzvednylw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtzjynuqls.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtxvmhrich.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtofbltdod.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtfswnfmkw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtosgzskrt.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtzcpxfzux.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtzqqwauqr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtyiliunkm.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtixrbicbd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gttiwoauww.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gtaaiopeiw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtffbkvabs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtmwkhrxil.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtghoakosq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gttqnyzdcd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtfszwmmch.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtiylbzfoe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtkzoxybnc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtomenemud.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkxwtqybh.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtmupdzfno.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtecmqcavc.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gtvhguyrvw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtpmmkgpvc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtgjojjfks.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrmqfeum.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gtgmvgfbmi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtwunmoihh.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gttwuthgyz.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtquytrbdk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtvqaanilj.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtdqpvnref.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtafjrhbav.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtltmqibat.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtlrfnlcoh.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtfwmlyokf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtdxkifrzx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gttldhnxwg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtivpvsifo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtfseijosq.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtgxypaeeg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtwrsmmhms.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtenjydokc.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtsmjgbmiu.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtrlbpwogh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtosemsqvz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtjpxcsupi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtbvrgifim.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gttcbybdco.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtiavgecps.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvqrirrr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gtrtqmomtk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtpojpvyfo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gthbtbwzay.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtyvgkjllg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtmtavujzy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtyfpzlikg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlcwcrxv.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddybrqsq.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtuicfyvuc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtdvkvnubv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtiaqjxhsr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gthmgwknps.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtztxcavyp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtljtkbuzn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsjgcxfx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtxnpfonti.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gtlmpuzqca.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gtcecngufa.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtsmexyfqw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtiuoldyqa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtjuledeot.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gttprceniw.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtwuwiditk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtenegovpu.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtqkybjtzy.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtrqgrevka.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtkcufgfuv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtemzaxtve.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtbfmncwen.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtvcnmtiha.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtdgitpvnw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtmqmjhsro.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtmwiglwee.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtcbvlggps.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtgaybrxyn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtizubareh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtigpoivwv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtwnmcgqbb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gtrbtqjder.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtvlfvaxuw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtzkzevbgv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtxbhgeapj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gtterrbtgk.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtmnhonlni.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gtvgbkkwng.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtjmvagjwm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtidiebldc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtrydyukmx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtflwrinwa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtqkwvxueb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtiwofafkz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtmdejasrh.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gtzgbjrlht.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtwqcfulwt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtsipvagzc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtkmxwdlwp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtlwkwykhz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gtagvxeuur.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtdrhdlkng.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gtnqrflhco.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xylfe.cn/Article/details/gtqonmspze.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvfrbcrnu.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gtmmuipend.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzoartpmc.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtrdxwraaf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtgkmwvzow.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtyypkaouf.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtbepbnzvm.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtigtqebhc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrmyctdx.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwpkpmga.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gtozxplvms.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gtlwwtmdyx.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gtjztpqmcs.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtnynxqloi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtfqlubfou.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtsuxiebvq.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtbskafmry.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtskelpzlv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtgfnktbsr.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtiifdlibg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtmiiynfqj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtyldjutuz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gterzycyvy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtlflhcrki.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtydrlcgma.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtnaiqewgu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtwxysdumk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtswrnxqun.html


<!-- 参考信息 -->