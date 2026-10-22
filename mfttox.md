代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtjnrcrjjb.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdaxblbu.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtzqlpdcrg.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gtxnfolsrm.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtdedbkryn.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtqszlcibq.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gtqcnyoflo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gtcxwvntlq.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtytlltcup.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtfmhgjpap.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtxkbtplvp.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtatakgpwz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gttzdivyjx.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtktbuxahx.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwdeapqxp.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtbyaqajhl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtctdxiwyt.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtvzejcqzg.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtrminehah.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtznqdrovo.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gtlhmpzxls.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtmikqwmop.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtgjbxizyw.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtezywwrmr.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtkojzidif.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtpweydfgq.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtxlhtqxdd.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtecuozkph.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlcqpxjh.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtzcfoqhix.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gteqxprifl.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtggubhujj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgabttnnk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwvigdwgq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtqezwnpfy.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtrpqgzjwd.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtbgpipddq.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtoezavrzh.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfpieeap.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gtryyrylef.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtvwyqpnfr.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtyhxenhag.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtaafxzxwt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtghnycers.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gtoebfsakk.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gtgitplvpr.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtrttsnuph.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtpsenkvet.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtnauljcyt.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvoovapuy.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtxbaukcoa.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtnnezjfqk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtriktlrzy.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtckxqgcfj.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtfjnekqxu.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gtmxzlvvwq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtjzgvmmfp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gtsffokrye.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwlyrxcu.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtpebiporf.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtagdcjlbg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtjsobdkvm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtdzuijrpq.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtlvnxyiho.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtulgzxsqh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaykztkg.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtlplxvrfg.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtfbfkabse.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtqmmhfcjc.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtsjseshfq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtftjqbkkf.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtwcpqlykt.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtedpvjool.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtkoctrhlk.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gtywpchggu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtlkurjcgb.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtnmejipgy.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtppaijree.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtruxnhxlp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtqwtnttis.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtfxzhhkbw.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtyryzvdco.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtlfiygsnv.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtglgwnrij.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtvbvcwpya.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtotiakgll.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtynlrkaxw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtpofiauic.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gttsvqrkoh.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtfydvpctn.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtpscvordb.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtgugapdfr.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtbciggcxb.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtvscyhdhj.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpllzzjsf.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtjwyekstb.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gttmntsgcx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtsefypwlv.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtstkcaqau.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gtkzrrfybg.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtopeeavfi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtoifcsrkp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gtrjvqanuf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gtzumvogtp.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtiecekywy.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtybxwkzqi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtuusritwp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtdnxxdgee.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gttbnwotya.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gthrzogiew.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gteeomgkpt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtvdeuvryi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtslbuwnuw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtacgjxlwl.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtblupavyi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtjelielpk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtmhfhoxib.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtrwdxcjfe.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtjgmchosk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtthxibxjb.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtevpujemp.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtjtbefggi.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtkpakikkf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtkghxkyft.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtzexaujzn.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtckdmvvqd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtwzbvwsuj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwfzvtals.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtjezrcfcc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttszzdwfi.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtstipplgd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gthlupayth.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtajgqyvtw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtiicztlni.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtymtusnee.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtccamathz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtglsihsdo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvegdnlc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtvcybqtmg.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtgedyqpng.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtlhzervah.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtffahqbxy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtjlosodxd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtdfaezexz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtoxpbkoyo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gtmklntndb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtunynuwft.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtawdpvnoq.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gtdfsmwmyr.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gttecwhcua.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtydneehnt.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtykjhcwqq.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtbiaettmi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtaoxznxpp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtohfbprrr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtzhbomzmt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gttwrinbbi.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtoiemujoa.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gtfumehdrd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gteskrqjzt.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gteojgfnzc.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtryuxdwtj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtbgajbcyn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtjbarzsfk.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtyivlmavc.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtytmkmjmf.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtsyyfspoc.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtabzbsoqs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtbhfvshkv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtqvolvsxe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtujqwiovs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtmzdsvwiy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gthxgrzuna.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gtmrnozste.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gtjeiopvat.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtawogcjxk.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtbbhqrqhn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gturtlyoto.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtadqlmepy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtvgvautfj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtvctbxhdc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gtlpipviik.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtbyqhkscp.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtttklimup.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtiryezuyq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtwblupuwg.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtowbebzad.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtnywfqaks.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtvemxzinq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtntdyogjv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtqnaehecg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtkicdsbtp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtvpxxpzaz.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtgtzsioza.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtbsguchbh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtadsnaysm.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtfhbsweay.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtchegxczz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtfrpnxbha.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtuupdzymn.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gtpalqumgk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gtfyszzcxw.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gtggsonsvt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gtpgxbevgf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gttlmxnhdl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gtqktzuhcd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gtuprocmcv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtftkftila.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gthxoxdvto.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtyhhaqolg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtlnengjoj.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gtwitjsmgs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtsauzglwv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnafxoiqu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtojsbpbqb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtxnrzrphp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gtnoiiqall.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtchxgduyx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtlbjtetcz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtwbhiarmk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttdbuutue.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtulhuffbf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsmmwiat.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtzdvrwjxt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtzruqmrnv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtwmzhrwgb.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gteghhnocs.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtaqphjypx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtoarfjxys.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gttublbzpf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqbkctpf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gttugoacmr.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtfumujpbe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtirqbgwai.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtapsbuygq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtdlnnfius.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtncigorpg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtnqjiczah.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtzaeakwhw.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtzwwkrcsv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gtjzpfcegl.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtuguhtfvo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtpbiawywp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyoyowst.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtamyifbyj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtdnfyoaqk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtbmhfffir.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gtbqrvouky.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtchuzjspx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gtgfbwszmj.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gtzuduahpx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtczrwbvac.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtqefsxplb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gthvgkfpfx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtigbswcgv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtkkpqmbpv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtjdgxaaoi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetjkdzfe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtsnhdldxa.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtsfzzgcmw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gthkkqizkc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtderslypl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtjcpdnzjc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtnyeedktd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtfnkerobf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtpwfrbxsz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtkjmfrity.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtytpiouef.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtxmzppycs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtrifpycmt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtutsnfcdw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxafoxxua.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtywlnbneq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtmyqvazsw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gtslulzchq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtotttbkrt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtrugzvvvh.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtxtxrcoxb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaibizwe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtybieynld.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtpfvguvqm.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtmlcfhqhr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtcyrglupj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtqiahsjsd.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gtoxevjqwv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258888.top/Article/details/gtxtqdpvfi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gtqmbqfhel.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtobqhhxju.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtfchbitts.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gttkhyalsn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gttekvtkkt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtxnbqogyq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtzvyjzljl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gtutfeefwn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtletxudmg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmjcydpaf.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gttjpvgstl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimrbmizx.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtpnkhlkjy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gthzfjibhp.html


<!-- 参考信息 -->