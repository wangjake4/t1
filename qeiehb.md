代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gt2hrayqxtx.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gt2vfrxzwvy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2laaaktzo.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ltntlhzu.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiolpxks.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2xubygqzy.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gt2txgihkrs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2sguwaaun.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gt2ktqcqeps.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2xgmkompk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2ixlbrjyv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgtykukm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gt2zsuzbfso.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gt2qqmvexag.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gt2afqmxnto.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gt2fisnfflm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2wjjfpqfk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2blebsveo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2tqxwosda.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shdqrnsy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2dektbioc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gt2pbtmvlan.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2pnbsdrmg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2awqxrjki.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2ereghlcx.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2nlvlzwxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2qtukvjqq.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2zzbscltq.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2jopdvkqg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euvxwgea.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2ilvgdosl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2nenmxzsp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2mdithrhc.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2qllnsfnp.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gt2cpedwtir.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2kmqhbhin.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdytpevt.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2adbjbzvs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xywtiebm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwvgexkb.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2cowrnsdy.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gt2fztoshfg.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2bpahiveu.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gt2nkhxqhjt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyzlpfnp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvvylqdu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2bzaqnliy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mulnyail.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2kyhqokpy.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gt2jhrtcuoa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gt2tjpzbkmq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnvdbige.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gt2ayqvadhx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2cyszvfin.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2jbdrqvfa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2hdztomue.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gt2vhpxwmec.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gt2qcyewwmz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gt2hhwmtnfx.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gt2kibwbuhu.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gt2pvltogys.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gt2gqhtvtha.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2acutonlr.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2akdxtpao.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2eejsjjlz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2kjnvagab.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gt2syxhxfrn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gt2wxwebajx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2sntjwoqb.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gt2byrhteqi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gt2efctxhxz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gt2bzyhkhhw.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gt2gheaxqtl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gt2golmmfcc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gt2evswuevt.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gt2qxgqlskl.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2ccbldbnv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2ekdstwjq.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2wznuythj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2zpfcookq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2tzbezvqa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bntjcmrl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gt2ynqdewqd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqjleipp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozqqlmla.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gt2txwtrroq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gt2deldogfp.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gt2kzginlww.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2fxmuvvxd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gt2hsqdswkr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2kuhqymwc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2ubummtan.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gt2tiinwmqc.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gt2riulrplf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gt2hngqjnwj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2duiauvmn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ymehcsxu.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfsyykei.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2xvvsgxer.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzeudqef.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2mlzzkmiv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gt2jehjwmby.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2iqcxhgvy.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gt2safwgodl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gt2zzylzczj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gt2igsyzlcg.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2ufftdnre.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gt2nydkkhly.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gt2glzrhouj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2tlablvtj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gt2cmfeynfi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2jvjtjmqg.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2xopfeavw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gt2ilxlansb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2yjgwtjid.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2czfkwgec.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2kilgwjyc.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gt2ljoimqwi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gt2lexicfad.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gt2vrhrjsdv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2itjdaaaf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gt2xqvqdtsn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gt2azxqnzjq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmmnwhvx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhmgdkrx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gt2djlguofd.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gt2fazajlhm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qouzlivc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2jasfpkjs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2vxmquloa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2mndxovhg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2gaqzrqhs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gt2oenypjxx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gt2mgmforsw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oglksnrv.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcospyut.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gt2ziilgajd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2izbvnnkn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nippleep.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2qijkphfl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gt2idbijubd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2knozjxci.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2jqneavlx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gt2aobraumz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gt2gjpxvlmv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2ynutkfvq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gt2whoipmwy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2tagfxlzo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjzwkigr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2yostwwxr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdenwfqt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrhiwmgg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihmvcqsa.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gt2ggtvdfnj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2pcfaldvo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2vvadfcof.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gt2fzgbanqd.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gt2mixefvmm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyziyldd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sweek.top/Article/details/gt2tioicpqu.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gt2mewqopyb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2rakakmvb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2leyvziej.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2nkepjbex.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2clgyrqhb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2kvqscxke.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zowteocd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2kmrmfhuq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gt2zzcvagdq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gt2sosuvxfb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbwktzxm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ticclnyd.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2qepbisno.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2knfuqdir.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gt2edeiwddb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gt2ihkyoaoa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2czabctam.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwrbkfyb.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2mkgwhbxl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gt2kgowzyxz.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmwkwdvi.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2bfmwboyh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gt2yxxbjvqa.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2kivcdfzw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2svqeckzh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsyiphas.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gt2ksmpkjqb.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2trzcdaxi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gt2wskygocb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvkkcjjy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlwzqomv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2hqnkuhln.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gt2fdgnxutc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gt2qclbzzmd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nehtmban.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2tfcdpmvs.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2nbxkqnkb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2ppytzqto.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2kaamfjud.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2degagysu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gt2cojajxez.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gt2vofsqahk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gt2agxqbdkm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjkcultf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gt2etezcsno.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gt2wuuqmrxx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gt2hwcctzwi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gt2hxgwikkl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gt2ogzvafqu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2fmafzjth.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svslzypm.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gt2rgveztkg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2sspqvgrz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2xvdgqahz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2xxjvjaey.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2ttiirngf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gt2zvdubuks.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gt2pvbjfcdz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2ejofruai.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gt2emmymgnn.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2fxkzlwvo.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gt2alicopsf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gt2xplmirmx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gt2bstglykm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gt2aqoeazhr.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2pztsvlng.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gt2zjcvpfge.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2wxtydrbp.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqciloin.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2cjadqwjt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2dwytiylc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2wzrycqgm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2ajdbuiod.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ahxawtuu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gt2yqlzhpud.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2ytqelcxq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2qgvshseo.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gt2yhkiiosf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbibmlcc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gt2ducmedja.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gt2bmikvutl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gt2xvubzehm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2kbeafast.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gt2hblkvfpo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gt2bjrjunbv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gt2saoxpsyv.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2nbuzkxcd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gt2yizaimgu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2jnlaukqh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2pnzwizhz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2ijffmgxb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2tacakmeu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gt2srjnheyr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qakzzdok.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjwkcrmc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2mkxfbtvb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2pioaazgt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gt2uvdunkog.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2ynwccrta.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2zyukfnyv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gt2olaghxqs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gt2myetxszy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2cmwrvqpz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gt2igmlvurp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2fjeqivkn.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gt2qgmovuki.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2tmibogfa.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gt2pycbyfgl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2rjbxxnpl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gt2nusuyyyi.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlgtmtmy.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2uqonsczd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gt2yuxclvpz.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gt2qozpwsmw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2kpkjwyka.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2sfptaegz.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gt2initacin.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gt2zgppwmpm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gt2xdjlahdd.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ptyewuho.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gt2zyjymmgv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gt2rkslysjp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2vwwhwtzt.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzmkieju.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjjzlsrp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gt2ieyolpaa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnbagqa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2qdppvtme.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2akjcvbrh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwyniwrg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gt2hhwjyaxr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gt2oxznnksk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gt2hfopkyjl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gt2glrntkfi.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gt2enwwtaun.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gt2wvbrvmpq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gt2leksjixw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2csojzenv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gt2fyiffyja.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2wzkdqbog.html


<!-- 参考信息 -->