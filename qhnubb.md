代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtmmbmqgsd.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtrhbmmgdn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtmcmusiro.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtqitysoaj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtjedmfdul.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtbdhdkcga.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtibffpbbk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtyjxwuiiw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtztfgucrw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtflprarfl.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiwezhol.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gtltzqgccw.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtxqjvjvvs.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtkquxucxr.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtocqqeusx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtwbscpezc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gttocdnzen.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihxysisj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtlbqjvdxs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttxhydnjh.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtptmbuyzo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvbndclwi.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtwombifxl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtvneorrte.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtgotbiczd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtlssuoism.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwqdvygbz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gthgrzhfeh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtjjydudxz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gtzltwoqnk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gtapbjvqpt.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gttrtbjblg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtfudsalmw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtfoycthwq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtvuqycodn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtzpnbmvwo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtdxamaqnz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtfzaaijgs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtvqnmvtzz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtkkfchgym.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtxugxugxl.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gtyvgxurta.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtilqgjabf.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtodxbjggj.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkidkbzru.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtghhtrgxh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtqchobqbd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtblmxdmzp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtajknqstk.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gtrvljbxpc.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtvjditoyp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtkccnysut.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtuakcwigi.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtsamtvmyo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtejnabolz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gthynvfvma.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gtojnmbtop.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtowegdpjj.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgnnhsex.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtziclkzkd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtaqmlzfrd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtphkelfsn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtewvvkkua.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtbtkqkmwk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwuqhehj.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtotffqjvn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtlppqaczn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtfcujuaja.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfmtreaq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtgtvtinaw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gttbmuswus.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtzllwxtoq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtdjxmctsh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtpejdgqku.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtzpwgjdba.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gtfunpndou.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gtufyzvnev.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtcumvdxib.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtvmvkdpqg.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gthuvxapkh.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtsxxdsejh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gtupaocavl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtawpozsdc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaotlppb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtjmszmgxp.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtnrpdeqyi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtlavspocf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtijifplib.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gthlyrfcie.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtlzinwtfo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtlzmkefqm.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtzebmubki.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gtqghbjkub.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gthptezznb.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtfxpareho.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gthgqipwct.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gturalrbvb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtieozpeuj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtbyzmgcoa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtcslbxjhz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjjftkjq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtdhyglvib.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtjvbcsgpb.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwuebihk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtxdzvnrqs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvwkzsps.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtdsmerhhz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtnbanbcpt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtujywvytz.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gttkxoiwbv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkxlcqbb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtqlwqnpgg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtiylgmyep.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtlnkwivcd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkdgijmmn.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtlorqfmgd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtcyggwdcf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtcjapyimt.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtxdnivuov.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtqbuwhcob.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gthkncnepx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtampvrchg.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtutwsithe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtbzpvcdjy.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtzdjadfov.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtcwnezzre.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gtxrddbrqy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtwnwerthq.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtbhqgcmtp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtjykwjqwd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtwuxshnov.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtldpalyel.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtjkaimphi.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtqfdwoqvz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtwpvajskw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gttsdfvvod.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtnhpffvjn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtizobplhd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gthprukxjg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtqulgmyjp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtjvyvtddb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gthnuujxbo.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gtshuhqfoz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtqtybdxof.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtkhhjdgpe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtxxyxirji.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtdxxazdve.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gttxgovhta.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtipzqhxdn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtbgrxzyeo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcuyixui.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gttozgkrci.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtzkrmszpe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtqpefqrop.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtubdavmyj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtkzvojnib.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtslthrnep.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtcgveapah.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtaqhhqqme.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtefudjaia.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gttntjooxf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtjpmbazfm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gtwwxhvceh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gttdfymnzz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtantbeoqe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtulgjpicy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gtzqdehpev.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gtwucdatlj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtfbfejvlt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gtqgsayrqi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtpbnlyjgg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtexgxqjzc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtqjcpptmb.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gtqwkwfjig.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpegnyjkw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gtzvgbfiwd.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtclbcvwdt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtwhfrxfqr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gttifouxep.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gtgwrdmycx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtwnbxtncw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gttnddblih.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtmgqkehey.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtgjrnhkvs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtauhffivy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtovxlzhvv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtsvlhbmic.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtiwusiohj.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gttsoaziip.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqhhjjcsj.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtqhwvvnwr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtsuncteut.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtwhkqcdyl.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtholynyde.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtroczkdtg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtpwpufcnz.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtqjisidby.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtsszpjwym.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtntfmtbhj.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtgzjhbpfl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtawusmpto.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtlomnbbpr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjshjwikx.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gtkuqqjkut.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtasnklmgy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gtcbyvclba.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtvlqyobwx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtfacyiyab.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtudtgvjtq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gtlwsnyfrz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtyyhiaomh.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtdcmyrcft.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbafqgpk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtyharynug.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpvwrhwi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtrhpwkaro.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpepizqb.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtobtkopmy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtqbqzxnhf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gtxsxmolta.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gtfglshtnp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtocrxdkxt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gtfmazngjk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gtmkycorrw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtdemdgsim.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtrrerzsda.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gtsydvrjer.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtsxlskcmp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtebkwvfie.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtwhkecizu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtnkolfjlk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gtpajrzntc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtdojlyvlu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtkdglvwyn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtkrextkhb.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gttazpxogi.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtfwuddhgp.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtjugcfjqy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtwtbpjgbn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gtzneemwmf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtabxjogrk.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtuutkunbm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gtrjgahlpa.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gtuwivvyrx.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gtrpcovgaj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gttdidkmkl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtatpzgzjd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtkjldpzkg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtzmcvccye.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtpjmpysgz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtxgyhllbv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtuubljhks.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtwnwpmwqe.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtpbyrwtiw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtfieiavva.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtazyxwegb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtsdyujulk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtrfcqjzjd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtwmnpqgry.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gthcchjksb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtdcztfxes.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gtfuvytiyu.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gthtlaquez.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gtaifpegfd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtiralozre.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtgwedhlyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtulcndect.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gtymytxnlx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gtndtbosbn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtdecizfnq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtjsopmaed.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gtdvubgenm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszvkcmct.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtknxhlpio.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gttvqfzmdc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtncjjiapf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkuzcumrm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gthuglrwqp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gtqynhrwil.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtouxezysb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfcjgwoyv.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtwomvervv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwvxtqkac.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaubsbqu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtkiuqntnz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzsghbgh.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtmcsdbeyl.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtfzxqcufm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gtzrmdaxqp.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gtvenlfdzp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtkzqamznp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvlylcppy.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtftrpbicq.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gtslbfsdri.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtyvdysyau.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtekzmcjkh.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtsxehafmv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gtfimcnyjr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtapyojgpo.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtemfbbddr.html


<!-- 参考信息 -->