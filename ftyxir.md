代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2iocgfqtr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nsjoodxn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gt2dmwhgazq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2rbqbllhq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2dtxcmuvt.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2ofrvgzbw.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2cpxcrixf.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gt2fwounjxo.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gt2lzfraatd.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2gsgdllln.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gt2kdpspmrm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gt2akaprfqp.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2kbvkqyuz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gt2eorebqcl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2emwipvfj.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2waflrldw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2zpvznwib.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yypzwvfl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdijimfh.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2svflkkln.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2nmjrjtbp.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2memwkqtx.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2bvaodqqh.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijfeupze.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gt2kvegvequ.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2nmagnigz.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxpirwlr.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjnhzznq.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2wgaqwjfw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gt2sffpbkhx.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gt2skyxzrnq.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gt2flhhlbvo.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2qktxsuuh.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gt2lopaseac.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2crrjfbhv.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2gerbnbvy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tavroktw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2dqinnzmu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gt2lndyxfjx.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gt2dyujgckp.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gt2ddbdyanr.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gt2opbnswdt.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2pxyzlpyj.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gt2dpdlbjcv.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2fhsyscwy.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlimlngi.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2ayuynzmp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gt2hldrbxym.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2cfcfylzt.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gt2cisiwolw.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gt2sxuqohze.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2slrzvrwj.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gt2smlepuea.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gt2acckgldc.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gt2utmxedtq.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2tlbqsjuk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gt2qzcsfgbw.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2esjzyxnr.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cmjcgekc.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfkluupe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gt2cxejclty.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2mjhvuflf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxmpgewt.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gt2keltvzxh.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gt2yetbbrzy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2pfuvyamv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gt2gxmjinfb.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2gcylrprh.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwxvvsfy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gt2qkwosnml.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2ymcofvvj.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gt2vcsjlgmx.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2idkxxkaj.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gt2mleekhna.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2yhojkfpj.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2hetbooxs.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2spdtrpfn.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gt2qytdgowa.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2isxyafha.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2rvabwvhh.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2fukmeeln.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2frejjird.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2njhknzap.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2yibmwven.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqvryrea.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gt2nsaxvqvg.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gt2uezasrsw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2rirlxepk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2mtimpodg.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ghxolqiw.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2rknrggqg.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bhpxkzvc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2udzqknfr.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2yaeynufc.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rplayepe.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gt2ylpffnvy.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gt2fnwzsvsc.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2qzajpueq.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2wcmbqmmq.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2fadrlqog.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2rbtypzco.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gt2abwlpeeh.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gt2avowtavn.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gt2gnziplon.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpjvqdml.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gt2ulhdswto.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zftohkpr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2bbikabjr.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gt2kjagzzer.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tibntebk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gt2jtszjgmi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2agykbgra.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gt2mhvyxypf.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2wincugte.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gt2wmdynmet.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gt2kakfzgab.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gt2txsmdqsn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxahiou.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gt2amclozqw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2rcqmxozb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gt2rzcqddek.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2qzabetkb.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2vylqyhfz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gt2khiynusm.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gt2kfzyfkwy.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2qqrfqngk.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2ltnwphih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gt2xztwchao.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gt2rmtgnjor.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gt2gqvbgmmv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2ttxsulnw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2icbxevnl.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gt2qqzwfekp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmgkqmfv.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gt2bxhmjjbm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2zqrvwvbq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gt2pnrxjfsm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2eflaivxy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2teiwshjo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gt2eelybcgm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyzphkvj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gt2rijdeqnf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gt2vjvsctkn.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2jngmrzso.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2smmbyavg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2cxwakflh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2ksbdwnun.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2wzbwdtvz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2uxrjmvbk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gt2fvlikjcp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zubhazhw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2yhelxvgn.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gt2tbxoibah.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gt2evpmbofb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2cbmmwkmm.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2wupqvqzy.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2urbryqxv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2ristnajo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gt2qxpzpyrh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2fgkwognz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2pedvjtkw.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gt2uyqnibxj.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gt2ovxqrzrr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2ebuqheqj.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2xllrwcqd.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gt2bbgdwqxs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2lylnrltu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2mdohwtsk.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2czllvxhi.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oddebnsl.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gt2wzpqdlfh.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gt2ilhxerlz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2rustdhtr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2imyvtpwj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2lpljahua.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymoklgxz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gt2ikrtizzo.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2xdtyvueg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gt2zyueyopr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gt2ejghlhxc.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gt2cbwrfdpp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2mvgeigxu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2pergehox.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2eyuvrlob.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.0kj1m.cn/Article/details/gt2vxaupmjv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gt2ctlmdxia.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gt2mrsxeuzv.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gt2cyxutvcn.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2ctvjbuaw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gt2fftdvbqa.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dydxppdt.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2ovxeduoc.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2eoyrfckz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gt2ydkhmlgz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gt2pujakqdp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gt2wwwazkun.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2seuoaekf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gt2apntunep.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gt2qbwsgosi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gt2ahauofea.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2ksqjswbe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2qkvynpmf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2fxrxdoil.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tygchuly.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gt2qkddymym.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gt2aqwrsbwq.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gt2kytdsamt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcflkvqx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gt2aevhnkdv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gt2xkwslxik.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigufen.top/Article/details/gt2qwermdhs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gt2qwdaxsip.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gt2eimltycj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gt2qhcxeyfo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gt2aprcdvym.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gt2dlpjwbvw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2dhzskoob.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vviwriow.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2dsfaxrqq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2esebsygb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gt2ebhblzbx.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gt2kfzdqpcu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2knbwsxos.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2xyrvepcx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bybwbtxe.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gt2pthgujhm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rmnigois.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gt2lpqzqywc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2nyqwhlbz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2xttuyzlt.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2qzcaoxbc.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2lvvcucke.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gt2damewawq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gt2seeenmcj.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2poekyaoh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2lsioanwy.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gt2fnvxtbul.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2dpfcwgfm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gt2tibtdqgk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gt2szhgmhru.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzzlowf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gt2dqapyfvc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2bicduftw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2smkjdgel.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2mwmocrmi.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gt2ntmclklk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2ylhmqjri.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2lrfivllw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2neljqspl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gt2rnbvxezs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2oscnpomr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gt2zuunfdef.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gt2hblrufqg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gt2tvhxmxxm.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2vfrzgcuh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zjoecqdh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2nkoeougf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sornkqfv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2gshhsqgn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2rsjalrjv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2ljspbzir.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gt2kxddnsmf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2rrcjbokh.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2nevcnfmh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gt2hasrgmcc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2oetusrmz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2qxefivig.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2wtpwmrnh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdwwaftd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2yddrzuhx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2ugzninqz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjkeihuk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gt2paanwrml.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2ljfqglly.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gt2vboahvum.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2eujkwmww.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2stphtmfg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2lgwnrhtz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2qtiqpxfu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gt2jsgryluy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2iyoexqkz.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gt2rrwhprtt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2oyppkznz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2ahujuzlh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2tsztomfg.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gt2qawkrowc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2mrpunoxd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gt2waqxngce.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gt2exjznmfm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iogtjiec.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gt2qdmcxkce.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gt2ckznzyka.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2vlhbcjek.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2vkidxuho.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2bpccbyed.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2tnfobkaw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gt2rdjwyoqu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gt2jxpmywdt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2zdfdvpky.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2vqpekvfo.html


<!-- 参考信息 -->