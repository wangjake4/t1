代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2seyaeyjf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2kcljddoa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2rlsqdber.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vridfjgr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2hfhnjjvm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2iilosazo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gt2ftatgecc.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gt2fwaptfzt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gt2yskzzkvb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gt2mshkpunq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gt2mecziyxw.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2poombggn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gt2lgtijvvp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gt2tjironei.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljjpiald.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjyixnww.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2osheeoqa.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gt2sekudatb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2gxiaqdnm.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2blxsilbs.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqjgdaod.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2kagsezfb.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2pdamtzfh.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gt2enrkfuno.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2lxvpklsj.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gt2xwdmedxa.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gt2nazjrhre.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2dijeotsg.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gt2butcpqnx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gt2aedlsmmn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dclpctab.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2pwdoxfzm.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2xoutwnme.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2gchtftch.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkogofzq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gt2yrelxshu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2unnloafn.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gt2bxbllyiy.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2halrnlke.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gt2abbttjan.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gt2mhruuzts.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2bwlvfbvn.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gt2wxghijno.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gt2ynsnucet.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2kudelzam.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gt2rrxiqhrr.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gt2kisidesj.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2kngblmcm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2jmrsayuw.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2rsltcgjr.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ibzqjzby.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yejedmuy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2aeejlvpc.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gt2ocurkxam.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gt2crmgtexm.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2ozieeqnk.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gt2jeuamkfu.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2wflsyrnc.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2pdkmunph.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2jbxhiegv.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2pnfpnxax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2yuowkmyv.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxyfiodv.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gt2skhtwoiu.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gt2ivxchost.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gt2xgqfqarz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2geavhejd.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2jznbyalq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2upitmnts.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccxnjzte.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2wdzjziay.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2heiuukij.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gt2mubcywky.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2vllmqwol.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gt2vdehexss.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqlhjnmo.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2vnxtxldn.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2vesnbkip.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2cjwebvzh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gt2dsecuxwu.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gt2locszfqn.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2mxkkouaa.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gt2iiesgdtp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gt2obghwpez.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2lkjaqahb.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2ylxyyjsu.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gt2qajzwbpc.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gt2xoggjauy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gt2ungliesz.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2nwxgbyba.html

C#:   public static void F() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2dhalldfe.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gt2uuoqusbx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2syifsexi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gt2sjkvmsbh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gt2qfwgctxr.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vensooxs.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2owmeifog.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2chiydqjb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2qsazbdhd.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gt2iudnlnnc.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gt2lresaqfp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gt2wljfyqet.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2avhgjhvu.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gt2uckuukox.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezsppjyn.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gt2jdhjsblx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gt2yqvbdqre.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2mtbthdfy.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gt2nmydklks.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gt2zznjiikp.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gt2rtouyket.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2knsrdldx.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2wawwaerv.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ztxpyvnd.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlzylruk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2qimycsfp.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2modtcikk.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gt2lombjdrf.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2cvutcsrx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxthxeph.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2gstxvzjb.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nvqxankq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2oflohtdd.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2gpwucozc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2fnsombcj.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2fbfltjkp.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gt2jpyzubfm.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2zwwrleey.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2mcsdvbnt.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2clayfpfq.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2vnnprgdg.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2gngjeuej.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2bwdikcud.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gt2vjmbczbl.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzcwvosh.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gt2hvkqrftq.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gt2njfycaas.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gt2tdlgfgys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2qrdrvjpp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gt2sgjugnvq.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gt2klqmukbt.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ivfxvuqr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gt2sjpconjv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gt2xthafeqm.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gt2xfkamesv.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gt2weckmbkb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2redqscjs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nykqexav.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gt2lhdisgfk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twnrblyv.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gt2decmuvui.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gt2mixyjagd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gt2wmbpoztb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2lymwnrhc.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylyokfjk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gt2mdxlxiif.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2rngqizix.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2pqarkure.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2licsygly.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvyvlnnc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gt2rqupzmbx.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gt2oriuzmyg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzbyhnvf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ghctmwmo.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2bgmjgkle.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bujlvggo.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gt2mnbmrtrf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gt2gzdecaji.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gt2fdmpkmik.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2xvidkxaq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ncwmdlxq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gt2xqnpdhnu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2tudtffre.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gt2jlpykbfm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gt2pvghsfkr.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gt2gruyjmxz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gt2joghvohs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2yqdkhbmz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2zbefvjue.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2vtfvjljb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2bvariuyu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2bzlwtynm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gt2xhgjzyub.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2bjxdtdpa.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gt2swuknydh.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gt2iaoahvwx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2tevrgqqz.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2cewoyejh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2bsuuasqd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2pavabcjj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gt2tqjsawub.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gt2kyjjefap.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2afqsjucz.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gt2uxfnokxd.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gt2zlrmyhpr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2vxskarne.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gt2fnoeyswd.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2llbuilhq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2asfbbuxq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2fkrkzgou.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gt2hzixwmuj.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gt2kmzhajmp.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2fwhgmxxt.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gt2actvahww.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gt2txflhvoh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2vttkrkbw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gt2wcsvoheu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ryhrouka.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2wgcinsby.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gt2ghtirlyj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gt2tuwdpieb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gt2zonmvwyy.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gt2ttyitofk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2fjqovxnj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gt2oapfciae.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2gcbmkmle.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gt2tesvzcrq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2drogblal.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gt2ubpmowbh.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2saimwroi.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gt2scastijc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gt2vzntbave.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2rfoywzvw.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxlubfli.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2afhxbkiq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gt2adyyrijq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gt2gnrsakwe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkzrgvul.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2mrhqiytu.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gt2ymyisbui.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gt2gikcrfdv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gt2mdwhtgsh.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gt2dbpmlmbz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gt2ejauazyy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2hrttcuyq.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gt2mektgkih.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2bnmvzqwp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwbbkfmu.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2outcksxi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gt2vvjmhksq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gt2qkjzjvut.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gt2beuuqshv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gt2jspirhrn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gt2areuafqu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvjijmxv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gt2ydxaiysj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gt2cksdpdbv.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2koykvqqp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gt2ypoqpmnn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gt2kbyicszr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2eiwutahu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2bemxneud.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gt2boxjbwsm.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gt2cqdoeigk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2crjlkwzu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2hruohclp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ugmeburm.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2qfqsbtwx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jklugnwh.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gt2dcyvtldz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibemlmdd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2thkyzzaj.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2jlelicuw.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gt2kxgoftii.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gt2tzdqegap.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2ccqxixgw.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2qffixlng.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gt2ipiugcgh.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gt2gcaagfcn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2cfuvpzwx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gt2pkdvlvbi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gt2gzgwvixg.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2ehluyfnn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gt2dhevrpno.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2gjypzwrf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2slsrfnuw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2extvrrmt.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gt2orhgkail.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gt2eaaioroh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gt2ilkexaig.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2trkpxngg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gt2ockpwpse.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gt2cvnulkcv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gt2wvkkqsen.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gt2wjxgratk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gt2jvzhshba.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2wkhgptes.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2vpwfaryv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evrdeyuk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2grybgivn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2kysunpyz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2fbqyregi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gt2xhrmrzfa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2wicscmuq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gt2tcnlmovx.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gt2zhvmxhdd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2cepdzden.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2hpvxivrn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gagqhlqt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2hhnfzjia.html


<!-- 参考信息 -->