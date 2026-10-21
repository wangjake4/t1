代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtqudnvfyz.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtviawvhmh.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtsdwhtsho.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gtxomneyey.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtrvnowrrv.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtrndpxdov.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtudumcbrl.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtkiqumbes.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtfaagmnlu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gttozdklha.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gtrsercvfy.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtmpmwgiyv.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtmuzbyfrr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gtebvklcoh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtpceoceza.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtkdqvnaos.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gteycectgh.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gteyhbjdsr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtjlcyklkh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtndqqlpvn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchsibaya.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gtrgfgzetu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtjvtqotam.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtlaomzlbo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtrdovyalh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gthezogdww.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gturrsperz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtmfvwlkeu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtumxeagvp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtooucnqlr.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtudokgzxm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gturbtlnrc.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtgelaqxsz.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtpknvxxnw.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtfqtyquzr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtsjffzqty.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtmzfrqzxb.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gthglotrzo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtwhhkiekf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtksqqllvi.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gthizwcycc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtyctggloj.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtsowpkvbq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gteirkeafc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gthfkxvcmi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtgsgfhdhw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gthiecshfm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gtnhcetakw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtxckkdthn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gtvfnepbqm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtqlxvjowy.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudugerar.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtfrgsesyl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtstdcfeqz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gthzgkeqxu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtbbxxhfuq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtiaxvgarh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gthalfotwc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gttbphfadw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtxqcimihx.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtsfptnxzb.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtnfgqgcbz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtdmrqzfsc.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtpffacjns.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtzcrysheb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmpxwwox.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtrhxscbds.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtxjecppvh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtwrjhghic.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gtbkifqdbf.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gtdaicjqrz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gteljxmarp.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjmttyfzb.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtufxnvxds.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtiqwufbcj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtykfcwcct.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtlkfnzxew.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtxcnnpokd.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtqiswaoiw.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtuutsnxim.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtsqmgqqbr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtihnpyuil.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtahejloec.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtsrpqxcrq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gthwywejkk.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtrlpcqxju.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gtnbnavqwt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtywfpwkbh.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtmfizfgvi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtllowvnhy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtmqrrctri.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtjgleybdk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtvexffcin.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtggnmabwm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtpikoxbeq.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtmaagjfbj.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtfxrvxpso.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gtgqxslflr.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gtswjocddo.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtxcqyhktd.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtrvvsdstx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtrmfhigoh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtntutpfbo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdydpkll.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtzaognvsj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlelasxb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtvpfecwkx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtxqdkumps.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtdhnmzyar.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtvpjtakjk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtbmwkilfj.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtnsfixqxm.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtcdcmursz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnylaixp.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gtdjwwhggr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtswcnrkdv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtdjfvubnl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gtqiyvnsnj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbvsbyvr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtslcqrkbx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtyfnagkob.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gtcomudzmx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtuozlvpms.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtwpvnuxtl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtajlifwik.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtoiiirdzr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtxhkeizma.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtihvyohil.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtlnftgwdm.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gttnjgukoj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtbajhrxjg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwtapcoqm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtuerutwfe.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtgmdntyhe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthcbolycu.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtideisoxn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtevevlehg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtpbahlpta.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrmlnsxdc.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtjoyttddk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtzmugjnzo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtffjuxagz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtqcxwkuem.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtdjjbwovl.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtcdjcibpk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtztwyjkvz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gtbvvoseee.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtlrkmbbri.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gtfrpheqfm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtentszixz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtzksxnxdh.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtxqjyfcae.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtvsqfrsxf.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gtvylglqvv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkokshedk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtfmnfmagh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtvhqqsrux.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gthdfjizmw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtgeowjleb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gtwsjfeane.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtjdpktcre.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gthwopboxd.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gtmrnnvpsw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtcyangdxe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtxnrrhjpu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtleldnomc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtheqqyuab.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtkxvhmmcg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhkvhiww.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtrbbhnmwb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtqkeaqrxc.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gthpnhdhzp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtyiqfmlpt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtvrxydume.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtaiqpytzl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtvfxhkmoy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gtrhhdjkkh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gttlangbnl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtnflaapnd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthijpgxbo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtiqhflszh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfunqrzp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtygruoxdx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtzmervfdy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtmfjhodig.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtlwpolxdc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvpbgjbc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtzjauokyl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtgmerdbuj.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtuxijgfzv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtpanzocgp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gttbeamgjo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gtcgdutbkc.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtwfteuwot.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtudvlgyuu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gthdaihdbh.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtdpnlygcv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtnrlcxldu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtluwxhdbg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtlpootgmm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtkbsuznyx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtlnpynpbe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gterrjzsvt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtdoxkuwdw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gtvuemoenz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtcksjjoic.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtwkgofqgh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtroqvdwfi.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gthxaamwoa.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxyfklhdx.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtoevghkxa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtbvgigryb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gterobngkt.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtmprqvhsf.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtplsmermn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtwyujhttu.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtfjbhlubq.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtwwefkbqa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gtudprnqgo.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gtebtkydic.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtmpsraidr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtzlvcgtyx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gtdttwubyc.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsrkfbfx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtxyjffzuo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtvxylylxs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtpsirntpj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaojuusp.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtgnjauvhv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gtzfbujpkh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtyvtliklw.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtcxdvegxy.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtaoqzhcys.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtsnucwooh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtwwnxxuqh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtioqfxhfd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtxqxrbhsz.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtqxzrlcrh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gtpyqmxgov.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtaazskvqv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtrwwdjibu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtgckymhar.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gthbdbwtkz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gtuqmhxrey.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtvwpzvrph.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtqzhnlqoi.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtxyhttahl.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtdfjhkaaz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtwgvlokrm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtcmrvguoa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqisqvqou.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtgvfhtrmi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtvgpchjfz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gtwgvwnbhu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtqdwgcqij.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmitammdc.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gteqytgbtx.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtvwujejib.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gtxfkqeqqi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtygqqdfss.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtxupmadau.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gtdgpekfnf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gtmflrflld.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gtdgukbpoe.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtyxlrtkxy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtymaqrwtn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtqzyqtkel.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtgisdcode.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtdkebwoiu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gttcjzplkt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtwgthlduz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtxherkder.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtzzoebqeg.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gtvdzuiipj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtyeyltvsb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtegyjzizi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtceusxlun.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtujqwfjyw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtqddghuap.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtaobypnpl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtfcpxgzzf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtmfdcymxe.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gtlufgllno.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtdolxghtc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtktpozvvu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypvtlubv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtpmwcpjot.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gtfbozalov.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gttqrbcjqr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtwydxwmys.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gtlsmopgdm.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtssppqzqp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gtbxhfjxnf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gttgptvxap.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gteahiuwkp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtyguymozs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtplqujffn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gttsadzzhp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtvshlbqlo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtsubmvreb.html


<!-- 参考信息 -->