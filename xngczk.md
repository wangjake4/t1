代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtczlvvxec.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtcylrkwlj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtfiqtnexi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtinizvgrp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtbbiwdnfw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtawuutrdk.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtbtrhkvkk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtcwcvtrlu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtmmgmoxqo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gttdtiaxhq.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtllynbphh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gticgxetks.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gtlsqrqrbm.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtijhjvbna.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtiycsxkgo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypxcpxdo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gthqsvbzol.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtiobhncyo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtwsdximuw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnpzktcws.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtbviqbvod.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmgjklpnl.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gtxeenvpcp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gttjuxpuvr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gtuydkfiup.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtukgujbxb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtxjhbbavp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtxajlcgqr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtevdawgmi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtvifrdcly.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtmlewwksg.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtumqcuyav.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtwxecekni.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtpfesyhcu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtoaiiknxt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtkzltbylr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtbhhezaay.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtzzyjrtax.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtfcixgmog.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtdrrlsvna.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtziwgtcax.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtxlurxxef.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtnnrlyudx.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtvxetslgo.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtowyehanj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtbestxkxf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtpscuzazm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtlujvdwlg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtwbgrrzxr.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gtreebzxnc.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gthcrwytxq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtpctbihnk.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcuyrkga.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtylynlzug.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtnxgyyivm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiikicxlk.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtkgmndjbu.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtvfmaciff.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtrgalypyv.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtwtoayzrl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtpiqfqwrw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtflrsqvot.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtrymbrkfa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxcgliwx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtnzpangro.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtpzvumixb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gtcsjnblgu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gtsenyxbln.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gttthgbraa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtimhfionz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtrhhntoqu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtqkcutdol.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtqytjorqb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtpscrvqox.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtvkzhmdgf.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtxmaygnum.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtytzqjrgz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gtnnoqycml.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtwqkzffre.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtlcykoyed.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtuhdyxwgq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtwllapvou.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtwlshfqqk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtumwikxww.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtuaqyinxx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtxgxctrhm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtjwwdjqwt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtadlfgamq.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtppmskvmy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gthefbmuts.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtmslkrbkm.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtosklagbm.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gtyxwihmjf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gtqjvjlbqw.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gteuvgwrpe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtijzhboud.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtaplojkqy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtughwpjgt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtnpyucrwj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtsdrlstnt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gttfgdjvvc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtybbumibu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtkjhloxrs.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gttmdruotm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gtfepegjfo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gtlaqfvmps.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtviqfrbsx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtvfxxxixw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtsnsbphxu.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtiphhvktw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtjcyyhxai.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gteefqrfmq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtizlwlblp.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtgqbcdvmk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnjcllbwp.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gtqrkdogpp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtsnmfyliz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtxjrkqouj.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtwwuqjwsd.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtehvqmeva.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gtnszgsdku.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtfrgbapns.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtoziekvag.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gthbvkvgxz.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtosyleefx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gticgepvpf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtqrvtlcmz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtizacmddr.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqymdfmk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtkkzjdpei.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtdcwuyepx.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gteipbsaxx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtproggwwr.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtauraeikk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtbwsovccb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtrlssjtoe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtmvzhuylv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gtkokrlsmg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtcpomqkbz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtjdpmkdoy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtbllvvjii.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtylnppymh.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtqzwthfsd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtucliwlie.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtfrtspemw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtpkcsedjt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gthqihzfqv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtldogmzqr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtubuwruhb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtafuslqdl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtqhohqbzb.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtojtbagky.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtmrufwkdb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtxldgusnk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtaknflakb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtzwcuzrwy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gttekcixga.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozqnabcs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtkiprvhmm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gthuhzbmxi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtekaokojw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtkbuougye.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtjvuocbng.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtamzfykhj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtuaobfoab.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtwlwmdhds.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtjoywgdot.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtryvfgwcr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtlvapxggy.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gtngfyjsdb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gtaufedpdo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsdmyhlz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtwvobvenp.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gtfyitqpjj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gtrqqvokfd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtcxeqnkel.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gtkdgvqnft.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtddacgjqn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiinrzgm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtldlclqbj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gturqoiguc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtstxyagzz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtynrcfqih.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtmnmforwx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtoiarmaay.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gtkhawfvrs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtesttalwx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtztdleghy.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gtbrahkiff.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwfalpgeu.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gtretzqaiq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtmxajoxag.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtazckswgi.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtmvckxqdo.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoanguvs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtthupyvqg.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gtxiexqnec.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtxswtaauq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtojqgmipi.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtfnbjnzsf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtbhoyieib.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtkpizxzwg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtigpagvbr.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gttuhrzfiy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtvdquxhkp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gtxdegdhgi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtczubcatp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzwqophd.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gtsnvpsyjt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtcwdqbbqq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gtarumkqzm.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtxcapcapi.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxvcdiaf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtrrtjzvqx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gttononxcy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtvutifbkz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtomwpihmb.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtbikvtlji.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtopcmxpcu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtcpriryqx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gtqrkyvefq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtwsmpccwu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtawjwtnbh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gtsouueqab.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtkpmouegg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtkxgzbwxh.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gtvagrwepj.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtxskjtsyc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtcxlhysou.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtfegykjce.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtfriievyn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnqmzhpd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtpvxbpnvr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtmwxkvpdz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtzyhawotl.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gtoeiyivvq.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtfwpcoeum.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtfplywnvv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gthbzavmyk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gtsusmnolb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtmosifdnr.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtufjbbaah.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtgrapzbnq.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtstokgecf.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gtrcgzemxr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtnnlswutk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtkwvswogo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtpubjbvex.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtjxlqhmhf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtnpthmnrj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gtiqvpqdtt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtfhebaryv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gttbbnavnp.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtxtdfkmvo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtypptfwxo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtzuxhtdxm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtvjvnbssx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtjjslitzq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtyejrmthv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gtprywcvha.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtkkfpxogd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtuikqpnjo.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtzyicrfgo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtjystmldp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gtezscaret.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtkqgajija.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtoasedbjy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtmxqiqpqd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtbdohtray.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtcskwiycb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gtqzeqehkl.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gtckeltgaq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtpxyqnnds.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gtjxrctycs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtresehgtc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtdlwmptyj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtvcmxjlfs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtrouhbtdv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtgfletsom.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtzqjrwrgm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdnelcryb.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtztagfkrz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyhgyzlpl.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtofvjqlfu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtmxnuouog.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtbpkqzuaa.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtpnbalztn.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtebjfuoio.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtsxvubrjx.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtghdrsvdh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gtjoqqzskx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtwfinawxe.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gtbzgozrwc.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gtsojvwqvw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtjydhvgmh.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtjltiiueu.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtrirsbzqj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtpbibwarw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtpoljdqge.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtlnsrlggi.html


<!-- 参考信息 -->