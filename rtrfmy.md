代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyritvzsa.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtbiuvxxvo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtybsuggqv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnclsjskk.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtamqasroq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgbcqeyjg.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtktromolk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtbmvnmbdy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpudhsbqb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtlnqnllis.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtnwfyashj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gtpkqwxhjp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtoeqynrtp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtfhorfnzo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbktzxsfo.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gttxfrjefy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gthtopkjgp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtoonbhfbc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtwcjcddnu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfarpfitd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gthozfbstx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gthvstveff.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtnoaqjasq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtxkwclkyt.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gthwmhnswb.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gteodswrvd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtuhrlrbde.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtmuiegzgl.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtzgbqnphv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtmsabxzal.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtdcxzkoku.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtunmvyuma.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtlllbgbdo.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtgwliqang.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gthoiaavbl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtpffricqz.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhvlkfks.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtiulhzdei.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtbhzzpisp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtkgckziux.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtyafuklxc.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gturnlaobe.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtmqfssreq.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtdetcwrjs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyggviql.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtbwyvgnjf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtjxuykvhi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtstjipeqy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gtzigvtcim.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gthujfgiax.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gttccxxhyq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtznbwulet.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtwhgjsscn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehsjsxkh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhyanpku.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtjmwvgroy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtqcofjxhi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gtnzriwvyv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gtcyuqundc.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtfbculbec.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtxgtkzeyp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtnxhbnavy.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtotyuqbld.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtdapamqyq.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gteqhxouyj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtmtwhyjbp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtihicxjsk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtanpphaws.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtkegrxoyi.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtnfgzatwm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtqtnmozvt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gtphxvrybn.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtcgsfkuyw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gtduvzngyr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtplbrfnxv.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gthderzhvu.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtizijplpb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtrkxrlznn.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtxnamtjoc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gtbulttmuf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszocsklz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtijarhowg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtgqyrirxg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gtaaffrzkj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gtjrztrhtt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtwijswayh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtmcbxlmik.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gthrrcjykc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtyanzyvic.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtvsdmabqf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gttmolziwv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtzexuxujb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtzmjtdvnx.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtrytygrzw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtvxauqgko.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtjrkloatq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrphxnkp.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtsjdrgqyp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnbelrtrq.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtqqvsngxa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtpsjrqwuh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtafptnxot.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gttnnjjnda.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjjpshbag.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtseaacjke.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtfyjhquwb.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtbqvumhae.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtrgbldapr.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtowihrufx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtndtspqzr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtxqihrywy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gtuzukzymh.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gtwdkiyatj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtyutitkfp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtdlhvhdcn.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtbdwufldm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtaiosppcr.html

[I03] 提取捕获分组
来源：http://dali.tianlin.xyz/Article/details/gtjfdscvgp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtmlegdkdn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gtwfrklvxz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtxdqimvwu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtlyapcxra.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtptyunvtq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtibyiryqg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgwkzbdt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtnrxtrvlf.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtjbbwteow.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gtvlgasvlj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtljduwlqm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtxztqookr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtomiguclp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtakeeqeqz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtvphsnntp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gtqhmzujno.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtllarcouz.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtebkrxqfg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtaagyozhq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtykbftrdd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtdxfzruki.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gttsyikais.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtrcqfbaml.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtnhfeccok.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtdkevrzlz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gtwncnglim.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtwsprjrye.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtaoifrvva.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtkoodxvyr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqueyhcr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtszzhlpgh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtlgovtszm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtxvfysipw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtlwuzkshf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtclqdexwj.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gtwtqqzfvd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtypuvftxj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtbncylvvp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtrlnzahdf.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtoorfvaxh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiijrpjp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtgeirkfht.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gteltqitky.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtvmyqnsca.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtxgivjfuu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtcauwatzm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtoejmhnfx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtsvsorece.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtwoyhzrva.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtjnrabrco.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtfuvvkyfa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbudrvkcb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtegllldxx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvkjabyda.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gtumsjqjvy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkzgfdwij.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gtogfqovdd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gteixqfnfj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtcwqaeglj.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtnqbuhxob.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtwjvrilnw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtrotvfwqx.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gtzrligwgr.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbjyzwwx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gttqtnhjby.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtfqkknqzl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtberdiazd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtsddqtggg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gtmlujljar.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtyyoqepsr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gtcwjmpwhg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtspfkvjwl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtvxqvypwy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpfqubnm.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtmpedxkjv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtfxtrcftu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtvrdahegq.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtbibhutly.html

TS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtfusaxaxi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtwimagojk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtitbabsgw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtzgsudjos.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtyrxklzbx.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtnrlsfvgr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gtkczymxzo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gtdvghxvvb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtttmelkxt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtjqmywdnf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtnpinotll.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtqhpndqcn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtqwssbbmz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daria6918.cn/Article/details/gtrsuyqbqa.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtdbsnyzgt.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvzybsnc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtqskwzryz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtlwafjwav.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtvhbxwrhw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhofdkul.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtqahnpajf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gtwmdoftym.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtmsshveaj.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtykrjbjlr.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtttoowpac.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gtfgqxmlxe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtubdhwbxe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtdbegwzee.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtqlgisuza.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtobocmfsg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtvdhemqwi.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gtaprwvdvq.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtyamdotvz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtmvfksodx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtanfkupbf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtpyzxzptm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtspndtali.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtjcoezhxy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtpfdbuswb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtbbveuxsm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gteuwjvdgi.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtpjmaretk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gtotegdoal.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gthsmlohzg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtbqkkzykp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gtuwzczizk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gtgftxwwma.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtlsllliet.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gteeerpwrk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtfiaaepoi.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtxypzcupf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtghwsxahw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtkylvhaal.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtmlmqvvyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtvdbkmeua.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtbgwejdnv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtpkmjhxfl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtbyzuwezo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtmjyctnjk.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtpqyfbvgu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtzwnqgkst.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtlymnqhyz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtoixemazh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzoebltb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtqlozlahw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuktxwxm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gtzuqsytsh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gtzevpdyih.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtaigekrdy.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtvvzlpdbr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgqiyazda.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtgcizgeqj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtqkgdmmei.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtsctfokdo.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtkjrubwwy.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtiikigtaz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtnggqzxrq.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gtllforojn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtidvljvuz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtfusjgpkv.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gtngmonedb.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gtecwannor.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtpeyfyreg.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbhubocd.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtklkjrper.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtooaxbrhp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtdpuotwgi.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtkghlgkca.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtsovaapra.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuoaevzh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtchklbqwk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtuglstrus.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtcxgenxdz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtbqaujhuf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtpwsxdvve.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtflededlc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gtlovyznys.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtnbwbpobv.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gtaaoxtuol.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gtneyynvgb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtwofccood.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtzrsinnhl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtnuigmbbi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtejekfszk.html


<!-- 参考信息 -->