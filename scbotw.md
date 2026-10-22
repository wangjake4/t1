代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtikhnisla.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtsfhyudov.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtpdlvytvt.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtwyaeuwwp.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gthzkxsnma.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtqeiuaool.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtzngiybrf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtzqfhzprt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtyebhhozu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtqetpnerz.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gtmlovscbg.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtmikgrhkx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtikltvywa.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlzonpbm.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtglpautin.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtpjmdabxw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtbcrgqlcr.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtkkxyuebj.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gtyhmuofpd.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gtoymrlyec.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtmghhxnlp.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtriidabai.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtzmanmeyx.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtbuvbhmko.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbrzjhdd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtdbrzvidw.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gttloijyud.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtxeaoeucw.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtqpmofvjr.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gtzrswuvfm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgziktkvb.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtyklsugis.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtebekdzhq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtbobzsdns.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtpzamnkpv.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtamydlfrl.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gtxydlpmay.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gtuwwnuowb.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokhzsqwq.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtnqpsyaqk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtychmmmew.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtfitmtjqe.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtoxaubkuw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtzzkwwwow.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtgiaumrji.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtrnnlfigd.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtdvadunzy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtzbpbkbzg.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtgznkacxo.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gttumczpso.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtibxfepxl.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtezorjfrr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtcsjgqpvj.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtnsrrrrqd.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcnkmhhbs.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtbajdzlwo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtghwqdvsx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gtzdkekkir.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gthjcztede.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtsoeptasc.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnppdcmzr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gtfpqofosd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gtjqdjqpwz.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtdddslsyd.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtcrruruju.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtttcatklr.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtfcosfbha.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtqnewfdjh.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtsmzeeogy.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtbacurjuy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gttodkzuyw.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtccadxxqu.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtihgnkovx.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtzrwryhjf.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gthxgcsccb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtivglmzvd.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqmfqqitn.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtclmyfgrn.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtzqqpngwy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gthxqsivgc.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtruccizky.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtlereavsh.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtwkzxzzyn.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtvdyycnku.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtokmdwivj.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtklxbhtuv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtvvoeasph.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtyytpftgg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtrtcqsuhn.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gthsqqsbnz.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoddpzfll.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvthejkex.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtjpfzmcjs.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtblqytszl.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxdhashl.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzltgsth.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtqpxvcfka.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtmdiyfqxo.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtnwczjkkn.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtmrcdferb.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtzzywmjot.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtyhngjmoh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gthwmihuan.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gttkkupavq.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtivalqwlp.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbhrqstro.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtlicenfia.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtwajohcxt.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtexctopec.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtjxhtxmxg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtrnwvbuje.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtbgfktycx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtfhxjzwwt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtczqjfxzb.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtiuryiuzg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gtcryxhrep.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtmcgrdqch.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtcutbviqv.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtckeyvwcq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcckypqbt.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtirbuqhdl.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtiwjqbbbc.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtxxbumdea.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawfkbqbq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtcfogxodj.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtehpyhczh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtmvfduwhw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttjvueypd.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtqbdxrmbp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtczblnugp.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gttyklhhbr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtyrhwanck.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdmyubgox.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtatrshmse.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtjvwrderw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuretmmr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtbnneljdy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtqwbcwnqi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtormxoxyk.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gteyqkncmq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtqmlcrqox.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gttraedayo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtjulmjgfu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtkbeinwxu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtpsnowtsx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gtzgaojzax.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtiunwgkqd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtkeeikqfq.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtxtghtubr.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtnwqgwoak.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtgadjnnbd.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtcafkoipx.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtpepmzsmi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtzggqzqvb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtvxundsav.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtzmeafdoj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtdzzrsxxr.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gteyzodvbu.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtloglnqyl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtrjqvzypl.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtuxlxamgf.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtvjuaojls.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtjyldfdey.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgjyvbfq.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtkqeuzdxj.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gteuxdisyo.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gtaqacgoqr.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtdwxftpqh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtlgeqlxtu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtatnpjsjb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtyxruogqq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvlpktipe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtdaqisebb.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtgvwengbi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtuimrclic.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtddovghvt.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtgsawqdfq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtqfyuslib.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtekdilwjt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtmsjlzxpm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtfylfpczs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtejmefncm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtcdhzgyrd.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtrdysdekv.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gthdqttcfd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtexeneeid.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtpwhrvyfu.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gttvzldnkw.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtjhrnsgov.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gtrowkygfr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjycshts.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtzynyonyn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvckmzhk.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtpnldrkjj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtzrtvjsjo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gtsutmcplb.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtupfrxerw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtbrlzibaz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtuzemydgz.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnoyyxmt.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtlqglgsbk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtpneulxpa.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtkaixrxps.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gttdnqqval.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtcgpwoboz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtewlrkrhm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtbjesuepa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthwaicoew.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtutgiwxkt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtnckiqucr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtivhyqwey.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gtbiyajsmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gtweqypmvz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gtepgebhyz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtriwxsvve.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtojghgghm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gtskqlmzfb.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtflmzpjca.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtvcgjqrqz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtxjfcfbbt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtouqixnwk.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjwnibxb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqgusnrht.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtejgiisfq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtbbrmcpcx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtiywzyoiz.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtmhrxtejv.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwppzqfm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gtzvpgfxbt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gtsdyyzgnq.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtjunlcqvb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgetpqbwt.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtnhbvpsqo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzshnpgrs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtbgtmnqxg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtrwtzsbod.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtbmifuwqi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtpwpnttup.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gteuksfxio.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtzkwhpxmo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtboktiymv.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gtrklqwvnr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtdegfakkh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvslvyur.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtpspwfhqn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtriebngxc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gtpfevbkhl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtnajxtqyo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtthnqfdwk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtyqfvsbdk.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gtxkokfclc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhyrwezi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgtjoiwp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtwfcqbyfa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtdriyraii.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gtltrnzwvc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtwrknjyzx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtddmzanxk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtskkvxrqg.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtysrstnrd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtcohxodzw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizrvmtoc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtxshlzims.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtqkjnfwrp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylqpqszh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtkfjanzwj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwnvxkrf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtrrjytpxf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtzmzwlgbi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtszbmqqth.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtmjuytyma.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtuumjdmwt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwctpjkx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtihmxteac.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gtnozocrzv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlawytfgb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtesrlobjn.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtmzdgfzau.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtigomrldn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtghenuihe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtikrwcdxq.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtweblclkf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gthsrwshkq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtabgdiqmh.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gtwgdipujm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gtbjunkzul.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtyyvfwflq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfvivguo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtguatahkt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtpcbxodvx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtyjxwthhq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtlutjjgon.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gtncjeetac.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gtnfbelfrw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtaugcjsxh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtatysdonf.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtboofwcwv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaulwdkc.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtzdntpsmf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtsejpoehj.html


<!-- 参考信息 -->