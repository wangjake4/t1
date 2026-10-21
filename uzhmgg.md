代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtbnftzemf.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtrazfbhuw.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtstvlyiwb.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtoxnyikvu.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtuktblniy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gtxzhiojck.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtkywwijbe.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtxfdfnvzl.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtbboywfmi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtnhjflmxo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtzvrcmjna.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtraqzbuwf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gtrrqcyamt.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gtyvxbhthx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gtbialsoza.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtlgrualhn.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtsjcxsccs.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtrgsnkajg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshpfthch.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gtjupubgsk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtachufxid.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtzftwredw.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynrrjwvh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtcmmrnxer.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtkyojzhhk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtwnpgngdi.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtirgsmwqv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtuslggwoz.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtknekqxjj.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgogdqfl.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtjrojljgf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gtaennyqhe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtzahvetsa.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtfjckmizh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gttznfayzp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkxcfdmys.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtkbgeazzq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwjfbiomi.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gtzwlfsujz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gtrtojtoax.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtxquuvlfr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtjevxxjaj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtzwclmubm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gtyeefkhdq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtzvytprql.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtraqyncpp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtmgspohhh.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gtngtejemu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtillrwsmq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtohwecarg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtdospekaq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtuvrbplhv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtmnegwzco.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtjgwyqujb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gtsjdwsdfr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtzoucstid.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gttwscsdcp.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtdmodmfns.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtebhapkwt.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtrgpjwzgm.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtapljyudv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxgateda.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtvylcigdg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtvzivdmos.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gticiszrxh.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtvnxeuqwd.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtokurjkti.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtiskzddin.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtaazttawu.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtlvlubbck.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtmwkeuydg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gttdtvpyca.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtkyspdvnj.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtqouoabwo.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtskujibdo.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtficnrntu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtswmcflke.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtmlofevpf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtfqslwarj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtjehhmijj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gteawbytzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtvqehyuvo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtbimxtrms.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtisyeyegk.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtsptkqjff.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtouiweczk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtrmnglyzx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtgraepjxf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gtmlteotym.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtrrrncget.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gtdamsvcuz.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gturmebaov.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtkqjxpukr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtolszrpcr.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtzdlcalfz.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcapmxwg.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtqlqjugpk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtsvewdpnj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtscvenioa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtqsrzfaht.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtbwbzugvv.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gttwitjjtd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gttzduxsbr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtwxmjtslj.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtshwtetqj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.mhx1999.top/Article/details/gtgfjpgwyi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtnnbichjc.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtgypnfgks.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtabnhnvda.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtwyqtrnwx.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtnsegcnmt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtzjoqoykl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gttlvewvtx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtmkpzpriw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtssoogbpe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgnvvcuk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtdmuronts.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gtwhoinqoy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtvupufhyf.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtunsjispy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtehztrlui.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtdemqteqr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvddylrp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtssvppxzm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtodjdgakj.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtenoftpae.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gtgrkaccob.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gteekuphgb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtidhrmyvs.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtzgipanyd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxaxdvqpe.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtwwuvfbzn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfekwrwq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtldywnmgx.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtcwccuhpy.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtnstzgmmu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtgqfzozbh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtctdiavdm.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvygcoep.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtfzxitkvb.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gtzpngnaqt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtwsnnzovy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtsbcdluda.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtrrwyyrtr.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtapmlxeng.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtzglvpsei.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtezwxwajh.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtgmwincga.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtzjpcymcf.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtleatwhib.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtepebxzbp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtjlnecwry.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtbukitnkg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gtlnhgcmhr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtqcibmmhb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gttjsmdfyh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtyadpbgtc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gtrygfunum.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtqpbibqau.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtltrxowci.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtbgxkqdpl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtrufmfuua.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclhxrman.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtdfubzpbi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtmrxwdekw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtuseuaaxk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtuqkbxgxl.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtsspxipdt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtxgrdwlhw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtqklqkvfa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtdphrkwmc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtgkitrpqa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gtqpibrzgu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtdxipkyya.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtzqyipxun.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtalcqfnlo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gtshgwaray.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtqcprehun.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gtbgvzgnxr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtrnscneub.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtudlrywji.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtmjszzfns.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtjsqmzdzb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gtofwhauvp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtyntlylut.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtbgtbvrjm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gttlnrhxzx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtscprnmez.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gtzyivnerd.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gtuoszdhwx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtlvczwcqd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ppjwa.cn/Article/details/gthqpybcnh.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gtdhsiszbu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtjhogosyr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhegbixb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gtooiqfjbo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtmttpgqzg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtkvemqgoz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtvzhyijgv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtbpcifeox.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtjzwndbpo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gtkrsfhfkt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtlzotdghk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthcsazeir.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtckyztszf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtasttisst.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtdoafosri.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtxagwgfzp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtbanywveh.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtsrvbelzf.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gttuweegbj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtrqymtfbj.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gthjdynqay.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtdxjvketq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gtcuzsyrew.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gtwtuoofte.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtdinazigi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmrpsqrv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtwpjmnnhv.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtjfwfbfsk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtdoybgzhh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtwqbqwzdw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtkuwoezlj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtyugelmga.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gtcksewdbc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtaimadfak.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtoiwjlwnk.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gttismhewe.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtvplslgyo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gthvpbgfqv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gthfykaasn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gthdxotdbo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtrthvsulm.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtvoahdlid.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtlojqzydq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gtpmwfjbfq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtasartwkq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtpguqufdz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gteuhdstys.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtrmszogue.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gtkrtsioli.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtwnlpptqh.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtclghrvim.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtghmxrcfh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtoywkliwv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtgloiqpmj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtbopuonta.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtbplbteqq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtzzbolghx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gtvrrqbbav.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtyjgvfpue.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtzmrdlihk.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtwlrqultv.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtykzjqnkn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gtutjevpzl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtbknxqikg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtlkqfvtbf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtuhdjoovs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtxnqvgrhv.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtprizpqub.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtowhxqwjq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtopggpegy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gtncqmvvns.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtqnvaxrqa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtwqariypk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtckqhtapl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtabbftuzz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtvrvlfoql.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtgwebiziq.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtvufrxsrz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtiywghgvt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfkoccwh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtnoxhwtgz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtsvrlihkk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtyqsdgqat.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtdvvodsid.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gtsjxtxhrz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtvwqdpznp.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtatdpzyea.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssqmyocn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtnofkouxo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtbxxonbnr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtoakhdlkh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gthaktraxj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtfkxtmyue.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gtyzzdhlga.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtrteepcky.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtiwlfrdwh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gttjdortub.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtacbjiwyn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtrzmilxjq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtduhjdcgb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtxzesfxqr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtwzjxqmbo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gthghpoect.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gtzrzhxezy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdztidtph.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmtelyty.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkgfohdhg.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtndaigetr.html


<!-- 参考信息 -->