代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gt2cncxhmda.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fokxoesx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2zjtarwcb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvxfzzlf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2kpucyfhh.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gt2extwijyo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2thtugshr.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gt2nxwradcq.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvyghczn.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gt2snslazkh.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2widihomo.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gt2rjpiuerl.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gt2jvjnompy.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfhjyvpp.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gt2xtmspves.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2mabkycya.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2oxofekww.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbfddmft.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gt2wjslbhpx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2dlauxibh.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gt2okddagpx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hgacrcth.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gt2vwrougnb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2ckpmqcku.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2fzvajqfb.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2mkeauxrp.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2fcujmlha.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gt2mzhwrddz.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2ieijohgh.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2rlpsofgn.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klosfjir.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2xqaudvtp.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gt2zttwqqdk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gt2kzrcanut.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gt2qlvatvim.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2ricmoiwq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2vnctlkpw.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kgggqdvi.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2lhtlcjjv.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2onacdpex.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2bixwlwfq.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2zsyfkeab.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2henmvagu.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gt2bagbuvus.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2wmizuofj.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2pcphvxuc.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qnoyypan.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfcmfaec.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzvwxkdj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gt2eopyfqvj.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gt2bkvxpxfu.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mchedtqg.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucoqwmji.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2jyzghkhp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2fbwiqqtb.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2ehlrvzgn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aibdlsoy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2hatjfesk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycekpopx.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gt2gtqtbjqm.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gt2nqwqftmu.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gt2szsaabhg.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2fvcedkwt.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gt2fqpgshgi.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2jcpglryt.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2wikoegbe.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gt2ikwzjdpe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2urqfwnbj.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gt2hngkocrq.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gt2dhljgkbl.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gt2ntsiqocm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gt2eplootcj.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gt2vyawtgkn.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbhpflgf.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gt2pznugepn.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gt2prpgbxka.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2mcmvbajk.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gt2jpteocnk.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gt2pmhiqxdg.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gt2jasqvzym.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcekblr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2nopmkypj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gt2svciyylu.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gt2oqmfcevg.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gt2aoidwhwy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gt2gcuhdaht.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gt2uciatelu.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gt2iscxawvb.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gt2indjwiig.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2iybyrpap.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smmjksmo.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2bjucrqrr.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olvaeshk.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2barcgpeo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gt2avdutwwa.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2jsynvuds.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gt2khrzhjne.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gt2cujbyqwc.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2aylipmlm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2fnxvbfsz.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2rxtydlck.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gt2uqqgipam.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2nyfzzcvd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2ixrrlrme.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gt2qmvozdnn.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hoozgbsx.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gt2krioecgr.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2gtrqlwkl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2xjrtswvi.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxyyxhen.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2cvxnnmxj.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2uwieicdz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2cjskbetr.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2midqtcom.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bynysgxw.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2wxonammn.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gt2xclzzprf.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrkcwhtm.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwmdchps.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2xdhvkfdd.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2ttowsgns.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxkznuuh.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gt2noiaevdx.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2areshwvq.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gt2zijimukj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgtnwlld.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gt2ytjkbmfw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2melaoilr.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gt2lzbkknbg.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gt2dbxvvvhi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gt2mdmjtkts.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gt2giexfwjg.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gt2khiphazi.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2gsxzlgdf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2gzuretgu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2omgmcvpk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gt2yfglapup.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2obkdfurk.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gt2aqjhgiad.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gt2quxzchpx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gt2uusnvega.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdqybvea.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gt2oxhioizs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gt2zxcnmhfd.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gt2npzpqjqa.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2hojgrxcg.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2cpuguorg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gt2jeiofllz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gt2ijblgnzx.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gt2drwbicnh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2nllenxlw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2lfcgnpbk.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gt2otfxhgwl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lzdtavjc.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gt2vtezugam.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gt2kectnbcs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyyowqdm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2zxewdmka.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2gfjflpla.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gt2isvdydjw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gt2yethpcas.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gt2njltkkfd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gt2ehovifqj.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gt2tyndafwv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gt2gsmsohrr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2uhoxuumz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2mjwoxjjf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2txhnayek.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2toygenhy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcvczlyx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2hqvtwvfh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixjsrciv.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2rioilrho.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2cqinxzxg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnnchmut.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2rtjlyhhb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2foxphzpb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2rshipidr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gt2zbovzpqj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvsmglas.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wukzcpjs.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gt2mvnggspg.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2axgnjdyb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2amikmork.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2cuppdapo.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2wdgzljog.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2gjxzhrmd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gt2guxhlikh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gt2lqwjlthu.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edehwlnl.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmevkjw.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gt2llbgzrfl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gt2xnlautqg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2kupmhlnp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2fgkztcho.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzwpxrss.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gt2mmnziapx.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnzkkmzu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2irhkpvdb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gt2ortergux.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnfknauj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2cudzyjak.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2epugkyig.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2hthsqmwx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gt2xjclrxln.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gt2dmsflfnu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gt2qdtjkjcz.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gt2amhqgjhg.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2axmotjfi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2gqjfjcii.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2qbyyziaj.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2efrtzqhl.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrbquggj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gt2wdmbisxl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qiuqqnof.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gt2pttujmuc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2jinjdyer.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gt2lwzjlnoe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuwjxaza.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gt2xfbtyaeg.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gt2emqlyirr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gt2fohkuuwa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2tzmzpqsy.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2jveceznl.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fuhcfaqh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gt2leusnosp.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gt2avwvxvff.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gt2vcpjzpiy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2pjddvvea.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gt2csdoigzg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gt2pkdlrpqn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gt2ejilkqux.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewghlkxj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gt2ezcorrgw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gt2asowxotz.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2ogitwzqk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gt2ejcmlvyw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gt2zduqvnwv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2dwrwkriv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gt2ngglqejq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gt2otfzreri.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gt2qrjgdozc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2xelqjsks.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2vbzwgvnn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fkhuwvng.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gt2oszeauzl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wxufdfls.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gt2uxcdiyvp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2cohxqvke.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2jgqvtkin.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2cqpcadee.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ehoyiooc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2wnhqwhid.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gt2atpinfub.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2aldzagqg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2yygipdfx.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gt2jzgevalq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2ceobnzwk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2avneandp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.316326.xyz/Article/details/gt2jjcchbgd.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gt2siunsbqa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2zwbunwwk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2taantbcj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2niylgczl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2bkldadac.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gt2kpcpwvfi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyddnzj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ufgnbwvm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gt2vmdtsdgk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gt2pcuqvbfc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxqnwnrk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gt2zwywnttj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gt2mgvfwyve.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gt2tncwmpgx.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gt2othhjiwr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emspftja.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gt2qjynlies.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2ftekflsk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2vxgoumjs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2odrthdoh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2ihooyiqh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2zckfcbpe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2ocxheamt.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2osrsgvow.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykdwcwjv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2rndfhrmd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2pcaxncrw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2vehloryb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gt2lnmbyhod.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2xkvfilgb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2bszruivv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2uhkuaxou.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2yccokooh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2zmvdwgnh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gt2raqjhpel.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2iyxrwvgk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2urcyznrz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2dafqtsir.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkffbizs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gt2gblxkpnj.html


<!-- 参考信息 -->