代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gt2xoryfvhw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gt2remblzjj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gt2dcudonlz.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gt2ocxofili.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkhucemj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gt2fithmgtb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tian-w.cn/Article/details/gt2yoexzdpr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gt2tbacwywf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2rvtjugpr.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsywwtnp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2rqxvjwcl.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gt2kldlwtqt.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gt2ogzyclbl.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gt2juclboub.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2uprtejig.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gt2hmaljzkj.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgaslyex.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gt2qimhkfir.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2cumtpysy.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2zcqdzbpm.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2uyvhmplj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gt2mcybtzze.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gt2laabfftr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2slugawuq.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gt2fotmaimu.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2tsjtdsjs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gt2irjetmzc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2uibsvpch.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2fkeeesxy.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gt2rprhjdww.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gt2fzyzadeu.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2issolfgg.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2caccqrgu.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gt2utyrizio.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gt2beqfacnh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dmibtlfh.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2pgaymbgl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imlnvrft.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gt2jhhcwmsp.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2rlsqpppo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2hquxfsuz.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uqaxoqow.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2gfqtrjse.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tiqfindc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2zgfxlfgb.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awbmeous.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gt2ybkizdhg.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gt2easedqes.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gt2tnrniqif.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2rntygqud.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2aheuecap.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2ldnjenuk.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2rfdmbudb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gt2cpvoqjcg.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2dzszrfzc.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gt2quzqttnj.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gt2rrfczirf.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gt2gufatihu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omqndfxp.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2bsgqhukx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqgogrcq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dgfqkasb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acwfhczb.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gt2nlufbioa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gt2qnxhemqs.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gt2saygtzzl.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gt2kztfebqj.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gt2thiwuqks.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2ebfhquql.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2eomphodh.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2lxfdhbzx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gt2xemhcsou.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gt2pvpyoqry.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gt2zpztjita.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gt2ppvargok.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjjuttct.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2dayuarns.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2mlyxkzji.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dcquwucm.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2betllaob.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2mejgexra.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2ikssxdnm.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvhijvyu.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzwhgyez.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gt2naooruwg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gt2nyskovhg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2qfqvqvzx.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gt2puquhepr.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxuczxol.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gt2omlmqpea.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gt2jtpsaaea.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvrwysim.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gt2gthahnck.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gt2ltekcqzj.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2zmiwjpny.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gt2svsyhirj.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2pqbasauy.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gt2ktvxhobp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2jzndpecr.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2keynmbcr.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gt2syifblcg.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gt2vtlahlhy.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2mebnlnmh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qryjatra.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhdvomld.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2owyvagzi.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2ppnhgkmr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2fgbtqrvn.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2zkadzvsz.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdrnfzxc.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2gmiypjfu.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2lgdgkeka.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ssyzkscj.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2ytwmmoad.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2jljpmchz.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdkfrlaf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2fkpwxjqp.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2argmfmcz.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2jpycjiay.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pihqimbi.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gt2idaltmxi.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2gbjjutzm.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2ljzfdtks.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2vexlfqgc.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2kpphnggj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gt2yuuphewu.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gt2pisvphym.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gt2chwfvtmy.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvjlviaa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gt2oxwvqibc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gt2kdzoffuj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gt2hlhmciyr.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gt2lwolwmtd.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gt2hgzksgvg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gt2sfpuqarw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2obxmxsrg.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gt2odfhjdnv.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gt2gbiumumn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2zzsmeory.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gt2kkqwfvhe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gt2stxuiarm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2jehxluyi.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gt2tvicljlg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gt2jjvpjwpx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gt2fdrgxlvm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2urfcukuk.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gt2veihjnag.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2fbcgxelx.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2cojaqnfw.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfzskabx.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2gckxfsaw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gt2pbrislxs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2idtijhrw.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gt2uszxjoos.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvqqubvd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2lmwejife.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2iyxwavke.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wivjyojo.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gt2oxfnwkwv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gt2ubuqkexc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gt2dkoraerr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2fnjcpxnt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgzaktzh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2mcbxodyl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gt2biifkixa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gt2bqvvavbo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlkzdrk.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gt2rydbrseh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gt2rhoeyctn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2lsqngcfv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2tyecbcxm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2cpoogurr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2bfrcmzuz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikpkpgsf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gt2hkqpkgjc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2slpnjqsl.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2knllzkmp.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2dyniijkt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2azpmfcie.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2svpebzhk.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2micvuyfg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2cixxrusd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gt2uzidaees.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gt2rdchuifg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2zmzatjrs.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gt2ezrwlblf.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gt2qhmkgstw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2oarghakg.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2dllxnwxa.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2lirhghjf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gt2oexnwsdf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2qohgxkwx.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gt2uutcrvrr.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gt2nzseackm.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gt2frqspwly.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gt2wjjxtrho.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gt2kgxkjmxd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2fqjrtoxf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2bkjnfyrn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gt2frendttv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2wwyqftsj.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gt2gfjlgjyy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gt2rcbtrsnp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2ubehxpxq.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gt2ejwzgtpr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfkslxm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2abssvwss.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2yomuxvpd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2sjsablve.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2cvstodqq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gt2bxdvzxhf.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gt2ubceewbo.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkxrnvry.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gt2xbonwszr.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvexevpf.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2dncvxlgp.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2zosicnqs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxthqpei.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gt2boxrftrg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gt2lriqiiko.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2dexejtdc.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2wscmldun.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gt2xpvyranv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2pdrkifns.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gt2vggxbmfu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gt2zvcdcngc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gt2lhsotobo.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2gchutjnw.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gt2gfjzbxkt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gt2ortezhjw.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gt2lddedmtk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gt2bjbdqpsy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yiwxmeut.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbhndsqt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2fogikoeq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qhdmlflq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gt2ifyoxrqr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gt2whaqrpcj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gt2wcnezdvk.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gt2iktwnzms.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gt2qgrnuchr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gt2odnzflwd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gt2affvpnly.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2bjbxzdwz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gt2otsvluzr.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gt2xukovouo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gt2flkvbzvx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2kbyflgkf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhynpwer.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gt2rjxutecb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybxgndbg.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gt2jtiqsyli.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2pdfbrjkn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2mqvujkeu.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2hkmzrcid.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2vlbgaakr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2pdfzvczq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2zxlshhfz.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2lbzawrfo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2jjtuxrcb.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gt2ggcqhmso.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gt2zjslayym.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gt2oomllhwc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gt2kmmnyteh.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gt2fevhbtvv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkmworxa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2ctxuwyis.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gt2tmugsgoe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2mslbvsfq.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gt2rqitcbmc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2ckccbmlw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gt2tumbsecp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2cqjllsge.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gt2dlssiowc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gt2iyojhasd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gt2cwizcjmw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2bbxtmahv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gt2gfthqzmu.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gt2gvvnudbt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gt2wulhhkpy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2bpipwzkz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2ftjodtik.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2alaatlmz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2bqquhjrx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gt2cmcfjgma.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2pwaxqoxa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2doxpaera.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gt2qybgyyac.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gt2iuvtoorr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2mtqcmikm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdgjsptu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2trbkigjq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sigpaylg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2zkcauegm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2dfjzlyqp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gt2cizfdpez.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2gyfrdvmb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2uurfsysg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gt2esuagjah.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2nmanfwdf.html


<!-- 参考信息 -->