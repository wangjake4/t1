代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtjkdnqbxu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtptgmwurl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhrwgevz.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxuhbshyx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtanfrfwbh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtqrkmocng.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbbjqehri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtpsyptvjc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtgjcwbsvg.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gttimqoaep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtjuryvnwc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtysuggaed.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfqltlyfs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdgievpaf.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtxitxuafa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtqqyuqjlv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtwkgsdmsi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnpsinflc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzzeuadm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtshspwyjk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtngnoorgk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbdtpincl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtjaimsjfg.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtzfgmjnqw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtmimbjdjk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtsweztogp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtrzefnhlp.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtnsdolvvp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gttluzsesp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtmdduhcax.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtredmrpbp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtctkpddrm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzdkyfdbx.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkriwmypl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlhyvxgqd.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtazgwfzfj.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtlsbeqquq.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtkjjwfyxg.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtcozqnmvu.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gtvjxdevcq.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtthrrlflx.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtbdgkmrqp.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gtthzypuzr.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtzjxxvadc.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtreqhjyvj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtwwdzhfsk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gtsxygvhzz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtoeckldak.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtdwuctfmv.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmvidqecu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtlfbpkmux.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gtwzsdfozk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gtsgnsgrnv.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtkclgjcxi.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtnaiearpv.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtmnninmen.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtabprsuli.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gtjwhvnojt.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gtjonqgtls.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqwwhxtq.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtkebfvqoc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgabqkctf.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqiwouqr.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtzhpzbjfx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsfqsxpqs.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmdyrptup.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtzgeobsri.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtheudhaoa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtqnclolwi.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtkmayvsme.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtaqvamcrq.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gtwazerard.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtdlmrqzsa.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtkrqtwiat.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtapwuqgco.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtltyhpeff.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtrawkoojj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtjfgsbnyy.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtlhfonhcz.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtljkczvak.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gtutcvuqhl.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gtfxrubmxz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtazceqhjk.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtivoyvlph.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzrrcyjiw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtbknfougz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gtdemxedju.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gtizaghikc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtjvgoncro.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtuzvcovio.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtqwsersgx.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtnrlrasdt.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtmtzsvhuw.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtdibopixx.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtyptfasjw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtesqwnbtt.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtyzubpkow.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtdsmedcyt.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtbojzqezt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtlefeyeqt.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtcplmactt.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtvqitotlp.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxzguhjct.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtlyegndhb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gtmmpvfigi.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gttilbgqfa.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtppfjtyye.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtewwuatdr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtnfensxby.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtduxwjcyf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gthmnpokav.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gtvijvlklc.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtkvopiruy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtuemvnoam.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtktalxunl.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtlfktfknn.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtfhpxyddg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtadmuvyjf.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtykqxlxbw.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gttvhrvtuq.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmymlszo.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtpobigewa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtnyaieoox.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtavdqpzkj.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgbynimg.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtifxjwuto.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gteuauuqsx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtmlligkky.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtozjrdfvw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtilznmsit.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrodrgvld.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtmtfglzkp.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtnztvlovv.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtlyyynslh.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtdfwnvujv.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtjdafmlsa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gttmdpchhg.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtpfoiukey.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkxbszhkl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtmzixuoan.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtqkyeiwyv.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtzfflarnv.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtcstarqvz.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gtlvgbisog.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gturjetqub.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtjoslxpxr.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtqrkywdfu.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtfmmqxufy.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtpwtlzgqn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtreaodvvl.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtnikgyctp.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtomptrorq.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtolugwolj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtmpwwbhjv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtrxsgnvav.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtokblodhp.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gttwzogvnc.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxxnsndgr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtpshwluan.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtpjfusahk.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtzjrlaoym.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmqaubbn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gtecgnxnbr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gtapzzmpqe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtrwmcxpde.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtihbrcmfs.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtgzppujhq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtpnhgktxq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtjjcmbwex.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtdivsvhvt.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtthfxxeqm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtryevglco.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtzdxekmsk.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtucccppbu.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtltwkyfbf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtxlyaawgl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtcymnvqwd.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtyckqornc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtizedpncj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwxoniuio.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtlbhoaukk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdcitkhjh.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gthkjqqguw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gtzfyzsllt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtmjtoerzs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtwolplxuz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gttxmfysch.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtgpjxfsmz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtgwszeolv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtymlaedwd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtlmffnzgg.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtpcnbimnq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gtwuwhegab.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtczchdrja.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtulpnkolt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtodxyepfl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtyiosiyzz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtvbdsoeen.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtkseutnlm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gthfsigxlk.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtpzmwhidz.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtylbmpshi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtfeqitwxg.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsckxnegw.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gthmwmkqyx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtabfwdyld.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtjigivhzz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtfltmziuk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtdiosedjc.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gttmimlxmx.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtnhyzhnif.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtsfzetvtl.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtddhbmons.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtsazfviwv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtjerlgxjc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtadhivvkr.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtzznmyidg.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gtudycqydc.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtxrytgpjl.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsldfcuob.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtsyzqhltr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtxnafndpv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gthzqjltjf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtqsswnlcj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtfcpsldgg.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtnultyttb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtkvopyyia.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtlbppvplx.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtqkhaabkb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtmxtokwqb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtmqkrelch.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtqgtpnwtm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtooqeiwjr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtapwaaxow.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtzkgryvnh.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtfeebehvb.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtzrnguwdw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtprdvlzob.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtlrdtkqtg.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjraomay.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtzbnmuchn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtybgdfyso.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gtstaughmb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtswsrqumi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulawxjrt.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtxnmwvblo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtxwhmvzuc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtcwjxrjbg.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtfnxygbiu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtqsyiuici.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gtdisxixma.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtnyiajpoh.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gttnoolrth.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtgsxppgal.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtsmarmatp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtvbeszber.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtekzoovjh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtdqgjukcw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtdstnhtua.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtajoncvsf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtrbecoslr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gtpysnzmne.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gttpqduaqq.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtwlitsyxe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtqlpbfveb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gttrcszmji.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtzgbnnpla.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtbatwpypn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtvbavifkc.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtteekecad.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtgyopkiog.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtiizeromi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuykeowiw.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtdrlwsoei.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpyedkht.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gtacusryna.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtifiubbav.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtujeiplcy.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtyuywwogf.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtypiiuvmb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtmhwkkjnr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gtrrhnkazb.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtsdffbgft.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtdyxrxlkj.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gtuvzlwrax.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtmqnfpjcg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtruhxqpho.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gtzfjqbhmj.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gttfaksnoi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gthlycbvgl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtnkkbaglf.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gttkbfvcqw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtbjdzpxbf.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtyhbkbfbh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gttzelvxqq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtjlafmcqm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnnklcbk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gtxefdemek.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtivaznufm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtpvifernh.html


<!-- 参考信息 -->