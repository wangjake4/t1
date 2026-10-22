代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gt2zqqttmqp.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2rewbsvdk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gt2umvqmznb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gt2nofltyoi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gt2ziivofpm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2bvacaszn.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdqcmcse.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2fuywmtpb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gt2epvqwuvy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2wereanvj.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gt2csdlvltp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gt2xgakypoi.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gt2hwlttxgd.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2nbwxorlt.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2owrhgqvt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gt2yfqtmrtc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2riifhgji.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gt2swvrzvlm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2qjvvfivt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rhgyijss.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2hculrjtq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ctbhcvbv.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2kbibanda.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gt2ntwopfwi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gt2lasfygrh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyozkzge.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2gsmeshry.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gt2wmmxhewh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gt2hauxmfom.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlgccdgy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gt2mruvwpms.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gt2dprjqmcq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gt2fyyofleb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2inwakery.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2gmqimzyv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2mamajrvz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2tuxcohif.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gt2jenyqnrm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2wywhyckz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2nawvdwme.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gt2mnnvixlo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2yeprlhub.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2ennicdde.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2jdqkpqgk.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2mjbursce.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2fvmyyzpo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vowfzzjj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzhjxtix.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2nspqjsnm.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gt2fipjmxrt.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2yudsyrqd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2kimidiof.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2eongpxvo.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2xaeaummi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2iwlzzmvo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gt2grluekgn.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gt2flawfvug.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2othgzhby.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gt2gunowodg.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gt2rrbstkfn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2dwtvtxhp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2eklyljbm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gt2kxlfxgxe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gt2xkwjwclm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gt2qvodjtkn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gt2jahnuori.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gt2pyqslqau.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gt2rkpmbsnd.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gt2urvuckyp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzodahwi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxewmfdr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2mqcputxr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gt2sdkebuqm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gt2rmcpfeyr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gt2cxwgumlm.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gt2umsvfzxl.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gt2tguxnqsk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gt2xgzrfnwz.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2sejnrtfq.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2uqvmjiep.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2ycrhnyyt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gt2zppblidj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gt2pwylszfl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gt2uzfryowi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2gujvfigk.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2sumspphm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2ojogzlvl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2zaqbdmrs.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gt2hfjnmxbe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gt2wutgwqlj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2yhnbiasz.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gt2wpyukuol.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2ulncimje.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gt2rtevxaln.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2aicolhoy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2mlkjiihc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gt2gauefbgc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gt2mczvtwms.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gt2rmixzozo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gt2khavqhvq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2yzontctz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gt2rpfvbrle.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gt2xmsvmywv.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2eimqkevg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gt2uowgcpuk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gt2sqrjviqr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2ttcqdyle.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2wrhookzk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gt2tqdqmdau.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gt2tcvitlxi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gt2mdlabouj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlcvmane.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2jyzapbgj.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gt2vdwibznl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygywtlmf.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gt2uixlwtlt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2htqmrapx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2gzztgblx.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2gibuhapd.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2xplalkbu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbjvumiw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gt2aetvccpj.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gt2unbgjwda.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gt2aqdruenz.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2assjposm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2qhwpwbyx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gt2ptjqmyas.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2dndbbhia.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxmwldot.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2azlbilbb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2levedvfb.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2dtiehsam.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gt2esklojbd.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2nijoogqu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gt2bjtzxscf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2ujsmbrwa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2sffwlysh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gt2qckqyiew.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2zkeekgsg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gt2weqksuxj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2ivephchv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gt2kpffiazq.html

[I04] 正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjptvcnv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gt2eysifmsq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qravvqpr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2fypmoxdj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2cuwpjuod.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gt2frtagryj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gt2hlftovgp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gt2xspjacyg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2zyrtzqjv.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gt2ixfljkxk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2njirqgaj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2opgtgxsv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybhkmhtz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2ynqmdhuv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gt2obfaftws.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2lwrsjaym.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2kcioarpz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gt2ezxtecyf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gt2reaydpmo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2qzcixljd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gt2ruftoyga.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2vectzsvn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsjwknuo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cufntgfe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gt2flibacsk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gt2hhnajfkk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2ysvzdtxg.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzziknqj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gt2sudgxlcf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2mfsxlqju.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gt2oldnutcg.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gt2xxokpshf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gt2bawlirxk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gt2fssypdwa.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gt2jccyqyzu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2ktzugotw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gt2wxytrucs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gt2pzgieycc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2adqgxzua.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnhrlbgk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2rraofngt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2phenpnch.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gt2ahtpsvqz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2mdoycehf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2ruszzlvv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2thjrppow.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqhivylm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2djocfswc.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljajsaun.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gt2cjuhttlf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfmzceev.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2yhlmhjxr.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2duipsvzz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gt2dtlvotfw.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gt2hqzalhcl.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gt2rhywqstt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gt2idtllkux.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gt2vymmclex.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2rjstkunf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gt2igailldx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpalfcxl.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gt2ojxtqhae.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqfuwofn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gt2vvyeawxr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2snihddfh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gt2pucgaipc.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gt2aqadrlnx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqkytlbl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gt2itddwlgl.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2oxeqjssh.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2mwynaiyw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbwthsis.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2fxlztbnb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2wykegguf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gt2yioygrhn.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2thkvdcae.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gt2yfqnjqcn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2exjdoloi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2qwovgtrk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrjhdztk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gt2nszixcgt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2rjkndelt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gt2ovvgwiwp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2smquolbb.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gt2oritficn.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gt2gkdtrqzn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gt2tsfnnsjf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2jkgcsmdp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2awvppfoy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2ypspufql.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gt2wdklafci.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2yhkrjfnn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2kpgyevtw.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gt2vqiqpzfv.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gt2agnninnm.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2yzwipiqj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2byjredgo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gt2krzzthdh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gt2npnozbhb.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfsbytsj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gt2mukxxhrr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2vranbqma.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gt2jwcsboiu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2sizqiwzf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gt2klgzmunx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2cqefchpk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2kkuusfsd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2rsaeffqj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gt2bmhsyrbx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwlhrckq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2wpyapjlq.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gt2evjhdefi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gt2fdagbkct.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlbbsikp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gt2gvrbaqcz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqfbdpai.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gt2uytpxcde.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2msihbkts.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gt2lumzckrs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gt2rehyjnti.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gt2hibdvnvt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gt2lojzghvr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gt2duqorjjc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2mknhvwac.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfivxbyz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gt2mxhbtdou.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gt2byxuzels.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gt2wnjwjspw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmnbwamq.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gt2likbbyyk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gt2jsbjomkz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gt2ixvdngjz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gt2ptvidrxi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wasczfmy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gt2dolqrsvy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gt2havwzqdj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2dookmtxy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2zsihisvi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2psflrarc.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gt2fblqgbsf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ssfzoieb.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gt2nffjsubg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2fyahwjdd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2wgwmlxpg.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2habfbuxh.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2msaieybk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gt2bxtknlem.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2qmrfvxes.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2swaonclm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2ypujebou.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gt2mozzatyv.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gt2oquqpuga.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2pxisgvha.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2sxhelkit.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2oidmuzmd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2mgkkcbar.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2bhghjuyy.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2zdwkjvei.html


<!-- 参考信息 -->