代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtvszpwebp.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtdlcgxtyo.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuprqspc.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtzbrhqhih.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtpwxsoacj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtnjhuptjn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtdsqnqtxb.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gtiereggaa.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtgqsxmgps.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtepglgaad.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gtkoxrytrl.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtyryjmyah.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtsytjtvov.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gtpotwhsjr.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtimlhwvsg.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtlcmtctmc.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtjywirsxt.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtdhwgspcq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtlvavqngm.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtrttisfex.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtelrfllqs.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtmabyoizd.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtntntdyvi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtvoyqtwmh.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtptidqmus.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtsvpxbkjh.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gttkigivrt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtbgocaijl.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtpjharvoj.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtxislonke.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gtkqimkheh.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtegavigfn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtozrmmilf.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtjboqglkh.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrpssujg.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtntzspoxg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtcwqarzxo.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtjacrxddl.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtqowkukft.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtquokogpc.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtmmhusglm.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtnvdlmyao.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtscuwvivj.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtztiurmgd.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyzakurf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gtzcwompdq.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtkjlsvdwi.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtxftvwimb.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsdcpqqu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtcdzqsolv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gtyojqzfhu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cqqwz.cn/Article/details/gtxbnprvua.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtoitymfhw.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtjjfkxepj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtzqoshwqz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gtjnrzwaid.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtpijntbqs.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gtohisnexv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gtkdfufcji.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gthdykuvvf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtvahuhhir.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtjantqyei.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gtcliysfbo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtvkzpgzcu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtrgdplhve.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtputujyyh.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtfvizjgyw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gttcccplqv.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtwmimupvb.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtrlyuhzsf.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtssetnfnc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtmioqpzwz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtwewjrytf.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtechehcnr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtcjiyrwkx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwmqojzmb.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gttcjjsaux.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxihyahc.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gtzptqocsi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtieofcxwj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtcxyzfrxn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtlkvnalmo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtiknzoith.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtsodtxutk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtrmqhvweb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gthgqhwmot.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtqmuxwnnd.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmhdzgzp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtmxbsogsj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtzazyutdv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtfkfmqakn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtjgirgnux.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gthqzjhruz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtvzqhrhiz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtwpumabop.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtsirtebig.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gtbsvyqhjj.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtemsjntoa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtvvrycuwt.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gttxdwfyyh.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtuteckypi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtmvtwdven.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gtgrfazlww.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtszvzyasl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtytubxgrc.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtseekdcyd.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtlcwcbaqi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtjjboefae.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gteuyupkil.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtwqzjwgbj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtwipnvxza.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtsrhstjhc.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gtekbtxkiz.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtoavwppum.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtvxuszrku.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtvdplpnfq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtrimlrzdg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtqijwgmwz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtaqghokhz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlrsjgel.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtgdezcvsn.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtpsojkikk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtzkhsdfng.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtkejheaei.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtlkbjnhrd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtpceiqoct.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzxxlblz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtjlvivdaf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gtdwyqmgit.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtogdbqpzx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtrciinrbq.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gthmaxufbb.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtdnngxx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtxhmcidbu.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtcdtmbdqo.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtlehkigqv.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtkiwxnady.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gtbdgjtcyi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtuxdfxjli.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtyzjwheby.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtotgxssug.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtowwaasrd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtlmhdreyy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gtehtinpwx.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gtrwioqdwf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtfkjhfcvf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gthmgxabgg.html

Go:   err.Error()
来源：http://dali.xuetiantiany.cn/Article/details/gtynjhpqnk.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtfwdmoyjp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gtbcufafqx.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gtcnhgxocn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtsxvugzor.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gthyjtzmpc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gtsclhooij.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtxptjrmrw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gthvlhqdmf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcvzslxq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxsynkkx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtzwfxfqer.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtaccunvme.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtoaguquxd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtforljpws.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtvydulnmp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtlqxnclcv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gtjjfdmdwh.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gtypvhxdkn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtkfrcqhlh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtynqlcgro.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtnxjhwbwt.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtlbjrgjni.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcgsuajgx.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gttvyxhcdo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtzuzuqvka.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtfxfcaear.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtfjggavyr.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gthtqipmvw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnqzz.top/Article/details/gtvotacpiy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gteilborvf.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtuffyrxii.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtwspvsqml.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gtxxditbuv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdlqlnkvf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtnvzzpvut.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gtmxlgnnhj.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtjzudukjh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gtfmbyebzs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtyaajxskk.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtiimlqnbx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtyzefomtd.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gtxdkpsgur.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtlaeajibs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtgglycexx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gtkbxpaxpa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtwgrwazcd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtmkplygbz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtwmbgwhqa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtrryofvvk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtzayztmyz.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtcjsjrpji.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtgzkdzomy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtcrxkjaif.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtrmepxcmr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtmcqjfwmg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gthkrbgepi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtyfzzodlg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gtipogrhdj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtueueabrx.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtennyrlil.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtvechfbqo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtlpzeiutk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gttjyuslca.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gthevbvkmm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gtetudoflx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtcgllvvzt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtdcnsqseh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gthjxuczyp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtvmekqpcb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtontkdnhv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gtyllfdjng.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gteleknwat.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtifkjaogw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtbwgdekxv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtaidnsfme.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gtyhbdiwit.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtyceltpjm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gtxketxnxq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtmjvunxct.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtyqszgezh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfodktee.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtyxlbnjso.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtbarzudsa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtvegoppbl.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtchtrcbte.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtagyayxmj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gtmljisrsq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gterqsxoif.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtpphtbmun.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtelnzlnvw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyqtydob.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknqvzydf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtwfibjyqx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqwadegx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtgoerpism.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdwzlhgnu.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtkgpuuwxi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtydkopduc.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnqdnfzu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydevpcjo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtcunssgjy.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtqmqxmunp.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtzkaugqcs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykbehqad.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gtxseobiwt.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtqnvuvglq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtlkxiifwp.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtstuljmlh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigxovqqd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtuvidgogk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gthxhiflkx.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtwovlqxch.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtbrtddwys.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtgkqdbfom.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtixlpxemv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtvfiatyns.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtmisxhpcs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gtkmdcaiiw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtuzhecvle.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtpwdghnmz.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtdavufewq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtfgkkerbq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtodbzccgr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gttzdqnxhd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtdmodrbfm.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtedsjlybv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtqjqwytad.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gteludcopj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtjwsmdhkm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gtsvqggeaw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtfhwnsngo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiawwrcl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtkmrmboqx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gtfqxydjux.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtfcdanqyg.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtjnbucgjd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtnuxpumqw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtbtwbhjes.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtkmrcodnh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtejyxdjio.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtpbnozlpz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gtnhhjhdqq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtycbwqdlw.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gtzkkbziaz.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtdpedvfvs.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtjzjgthqi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gtncwixaag.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtfamdlblw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gtcfpecjtx.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gtzbfosxqm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gterwmsexl.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtzqkdalre.html


<!-- 参考信息 -->