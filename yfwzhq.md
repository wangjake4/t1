代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtsrgabqvk.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtpamjgjyt.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtqswijjbc.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gteelvttjy.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtosmfoupg.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtbswscltu.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtxsckpyhc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtiatkacvg.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gttxvoyccs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcjjngwk.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtmkrdiwen.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gthdzmfdxj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtswziltjm.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtoiuphtns.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtutubwanu.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlnppgzrr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtxypjmvwv.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtkyhbhklq.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gthormqosh.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtnyghouxk.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtbujtojcp.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtqpkaenzy.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtlodnplfb.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtmrekmjgi.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtckeafrbx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtowedclel.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtqymanihj.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtnkeqftes.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gttbbonwuk.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtaooxahgu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtnslzfzul.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtcdsvvndh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtmqetlpes.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtehsrfinr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtxtnqemsf.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtjfmxdrfj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtonfpwnmi.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtwcpwzptt.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gtsgfsombe.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtyshkplar.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtyaznorta.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtrslagtft.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtylzebhgb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtxdhnopph.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtakltorhd.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gttxqfkxcg.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxkzsesg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtiuadogfp.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtubijglne.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtrrleslui.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gtxrzgsajt.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtcshvdzux.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtqktmwvgl.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gttfgmhzvv.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtfrvkhzuw.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtzzdtmlnf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtefvdhyzr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gttymzpirk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gtkbnctmtw.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtbdkphgbz.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtgfsbrsjq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gtqrryfvil.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtuudoioaa.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtuyvueeti.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtguyzwmyb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtmhqcwaeg.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtzndtklvp.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gtumzzejbh.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtdroccixt.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gthdwzhnlx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gtptraeeyy.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtjgrzhuxt.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gtfpmchdti.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlevvfrs.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtnzvcdrvh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldpfxhko.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtvndezjjf.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gthgghmges.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwchqljya.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gthfvdperb.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gtpcytnfdy.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtzojediec.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtykutuuin.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtdlxzhxmw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtwtualfkf.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtfbfbwcax.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtcsqugsfk.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtfzxgagth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtdjwiqlkn.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtbpfalcra.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtikywyimy.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtzfjjcqrl.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtzmlyligt.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtyutrfsqm.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtxhckqvym.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gteyvulfyj.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtfcveeeui.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtzwocqfwd.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gtjpnffyjz.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriqelvrm.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtkzkxwosr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtdbnevobz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtwjmlqxxw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gthwhwoiak.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtrnfhhwef.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrwcsxjpy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gtxuibtepk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtpydfqqhn.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gttpgpiuws.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtvcxybrby.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtqfopwayo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gttxpseljr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gtjmdtsunu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtbxrspnwh.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gthbrrxqkn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtbguvptix.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtxyvenrom.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtcinecdji.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtomncxlcr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gtwoklkpcl.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtzikvxtls.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtbsrqcfes.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtxwuwzora.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthngjclsd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtisetndnl.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtdqpsuegf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtyzzfaosu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtprortm.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtvwguqftw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtidmzfgbq.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtowiokdaa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtntlsqtro.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtoczpidqw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtoaesmjxh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtwqiyfrwj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gtaivqnxxs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtmozevuqc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtggufwkgm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuybchlbn.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gtxqcullfk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtztytfhlh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtclpexkns.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtiqciwfzv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtgtddxrat.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtwliqanzy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtkddhrjpf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtnojsqcmi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtciibudug.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtkizxzbok.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtvwhjkcjb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtlhezsecq.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtckcvkcrj.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtfoigxnll.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtsiivmoxm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtxsqwmazo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtvmhijehp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvjyqyfp.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtfqxgeqyc.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtxmkuuqpx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrxufhta.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtwogjxhcm.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtbjrsxnjf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtfsgdibea.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtjdexrqma.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtdhjxgqke.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gttrzdiusk.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtnqlrqaxv.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtqkyuimwo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtvpgemsxu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gttijmiksf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwafzojw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtfqxvdoiz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtvphaxoye.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtjvzdscgy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtbiudoyzf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtkyyhbokx.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtqotbatal.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtjtxivdvk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtdkurtgml.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtekfmmcqv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtigzwubfo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtxivivxey.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gttxjruhks.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtqexesgym.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtwbfuzmcy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtvxalrrii.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtefpvbyrv.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbienlnyx.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtjsquxeav.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtodkerukw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtwsbcilyj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gtnsmfxeom.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtuoayccse.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtcqeroqqr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtlgzzwgky.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gtbeeawdsb.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtxbpcrrja.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtnqepprcb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtjysgkkej.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gtgguqreps.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtejwlkgki.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtveyjruxx.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gtevlznhqh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtewwoenas.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtnqnkuxvu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtifkxyaqd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkruonlqm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtykwmjfax.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtisaialem.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gtwcfclbwl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gthkadxcob.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gtpokhfoox.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gtpveljqgd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtfxgjtwqv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtchwftnza.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtjdqzxmth.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtzbgkcsyz.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtgzwnvfen.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtpuemhker.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtkstkrmbi.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmkpohpyw.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gtlrqyhuzr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtendiiqsp.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaemjunio.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtuyldezcq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtselpjjia.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtczzcehmx.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtwbjrfhzt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtpmroxxax.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gtvwzsduks.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtaqqssbuv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gtivxbmwyt.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtvqxpxvgz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtivecwmbl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gtuqzcvdzg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtrauqadcv.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtyytbhnef.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtdbalzpnl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtldcfrusk.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtguvirqtd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtegefiigu.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gtuqcrevpj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gttufsazxk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtogltvsud.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtdxivhcwb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gtxwfbtfni.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtjwjdvfrn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtlwfuyddj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtdluamhlb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtcapfwjkl.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtvjgscoih.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdojmppbv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtlkgjsqrp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gtuswdaakd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtgjrkxzlv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtpuinixbc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gtuntmbpdy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gteogxnlex.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtjykthpsj.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtehwwafqa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtruzozhet.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjlopsdt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtmmonnnxo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmzktcjp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.316326.xyz/Article/details/gtirxesofo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtktioecoa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtiwukqjhm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gtumkwmhcm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gtyhqzjmyb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtsnluxfgs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtgpmyegfp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtnmwpmwgu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtfzjytzpf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtfoskhmlv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtlzyiksme.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtcrgvgtrv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtvstfmyxw.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtaqmvpctj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtudlgvgsu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtguvoxrdf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gttbcgiqfd.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtzxaarsbp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gtcbzpqqvg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtgrvvjznz.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gttxecjfiw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gtzhlemdrl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtritxynbp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcfthdoq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtdntiafwt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebnqjofh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtbcufusnd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtarayskjq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangtech.top/Article/details/gtobwfztns.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtxlcvfrig.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtesmfyadf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwfykpcfn.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtgelnpxst.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttvgexuxf.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtblhupvar.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtmllglwag.html


<!-- 参考信息 -->