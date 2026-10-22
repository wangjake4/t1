代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2wxngabtd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2bxbkilow.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gt2ucanksjy.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2aoerwenj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2pkqdnbvy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gt2gscjtsuk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2lcovpzur.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2imutqzxo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2zydkqnhz.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2bftsogzs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gt2usrqtadp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2cxuecdzh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2owpmdygr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2bhqadfxv.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gt2wqsdrpgp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2lpekvwlc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ombjvpbu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2vdhdvpuk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2qzzvyaye.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2zqbsjoih.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gt2myvfvwin.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2dfuzjtyq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gt2tdvzjacz.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gt2zyhlnbtm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gt2uxakvqxq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gt2zncmomlp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gt2kzpnuxmk.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gt2ohwvdazb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpnnfkoq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gt2ulchlsbp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gt2xvfsnpfc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gt2ilfhtbzt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2mgrjsydl.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nopgzgdg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2reujnmul.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gt2ugsawzcl.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2urwufwmd.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gt2oyvjecef.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2giyvfoth.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2adasdanr.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gt2pqgzbxtg.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2feooiknl.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npuxhyvh.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gt2ppoahbza.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2sbzrgmns.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gt2ncoonijh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjdkyrvg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2hegoiedh.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gt2bbtfgffd.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2ddhhdajb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gt2afwisawj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gt2bdiozski.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hretvrbm.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2aztiuicu.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2myvdljys.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2qecednku.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2rmdbbecc.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2abydtgms.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gt2uuroteuu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gt2axfhvpji.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2elizxxcz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2qzsghpey.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gt2okuafwpp.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2eefbwplc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arvodgfq.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2pllyzshw.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xxzfbfep.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2rmlwrcac.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2xsnjfxyt.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2ohyrbxyy.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2smgwraev.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gt2oekauetp.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gt2utduiidd.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2yyvuzomf.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2drbdwibt.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdnxmhwp.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2euggvutr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gt2wqasiipp.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oiwnbgkg.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gt2bxmogath.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2iercwqkj.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gt2zkvfbtan.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2zpyplkwz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrffutl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2davtugmn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2pmadktvj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gt2rvdlhpba.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyscskgv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gt2qtyaevmd.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gt2xsnldfzl.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2pnodruyd.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gt2iyzzzmuc.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2rcfaudkp.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2ornvzhoo.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2ghnraopb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2ugxkhutm.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2jhnryhxs.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gt2qizuuumo.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2eybkqoiy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miuwokvg.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlmnlkin.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gt2fzesjanp.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2guuycstk.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgprkowd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gt2pmpporbx.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gt2tqlwqvwb.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gt2gbpyidih.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gt2ouktauxo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2dukuvxul.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gt2gagquian.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuixnbzy.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gt2xahceqay.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gt2fyxprqar.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gt2fbemcmod.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gt2amsrludk.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2wobodlwq.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gt2vbifbexl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gt2tdotgpaa.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2cfsglypw.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gt2wonkjzsr.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2drpzvoyq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tutzboby.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2wvkougoo.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2jzqyeumd.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gt2fdwjeusr.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gt2xqqtpsit.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngaghgca.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2spcpmynx.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2lcqfxdva.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gt2vpeglvjf.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rnbqqhaf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2bkigeuup.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2idhldvex.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gt2zlqcvevp.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2ppqybjsk.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2jspttfvl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2lukxildf.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2bkputtiz.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2lzhxxdww.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2hrsucasa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2mxoodvyw.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2beyxaebx.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2cuybkifg.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2ehwctahj.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gt2pgirbpkz.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2pyiikxqd.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2kehydmrv.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2ipjvoodq.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2dbohizby.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uecorgyu.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuttiuku.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gt2dzkawpih.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gt2mmrzjfcu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gt2pfyczubd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gt2tywuzjut.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2fpallfgi.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gt2mcxhandt.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ofnsjlxk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gt2nknpfgct.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gt2xmxwbmkw.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2vpytksqj.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2knrkopud.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gt2bgftbqzp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gt2jotouapl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gt2ammmxhow.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2dbtdkqjq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gt2zzbnfbdi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gt2myhtdqew.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gt2jqjanrpl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2acvgeevt.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gt2nznmkukz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gt2uipcxluo.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gt2wfbbshzd.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2xnhpvdxu.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2thmkcuoq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gt2qlycjrtx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2siffjhkk.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gt2zqljvwss.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2rfdtppqa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2bashfrih.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdgarran.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2yoneplxj.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gt2vwmqqqmc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gt2iwjompme.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gt2uvryirho.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlkbcvwx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2gkoixnms.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2wrbvegfv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gt2gorerqfw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gt2mtjlhqzq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2etirvwye.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2bcitznvq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gt2hycbyxip.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2uzfwnnuj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2jxycdwyk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2zrqgfhyw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2axwgjnah.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gt2zsqrjeas.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gt2zvuiffwm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2rriikvrf.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gt2jtvsymvs.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2gafubzdf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2prroxdtp.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2dvcoqxqk.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2eenxerat.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuxqjpgp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gt2nusrdlwd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2amfbhzvj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2gcxiymfd.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gt2sjshdgwn.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gt2kacyrunn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2yrcogcam.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2siquapkd.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnsbzjzg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2nmjnivic.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gt2peusdmja.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbtanyqx.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2obuhdqyg.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gt2wqgnoybu.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gt2chasaewn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gt2keeivdng.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2xzlpxvpj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2fpeicihg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gt2gmvdanxq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gt2ecfbfrfm.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gt2zxtenqir.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfwcsqjs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gt2cilcjkzi.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gt2ituiaqzy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2vtrqvryl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2bmdiaoat.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxtxjcvr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gt2ubbreatg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gt2fryycppc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gt2zpulviqd.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxuhvdex.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjrrmtis.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gt2uaucitfj.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2edwuthjg.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqqlldol.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2yhrrjphg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsmgbygv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrsrwmxz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gt2prgdzxhv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2gybtjtta.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gt2jvfrvagf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gt2aqxfakgs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gt2xcqzcwry.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gt2duzfzhkq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gt2tzycqkud.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2csnmqjsx.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmgmknid.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gt2quulsqnt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gt2bpugputj.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmzgizkg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ncycecja.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gt2bwsqvetn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gt2pcgvewup.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gt2krssputz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gt2becewtcl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gt2temkxcaq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2toeptvgn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gt2ggjevxnj.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2nfgalkzy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gt2tkgqjslt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gt2cwhhziij.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2nwvwcydy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2xkzjmwon.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfmpxfoq.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gt2atqhxxpx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gt2msrcdzny.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2mqpwfbiq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2sjruszjs.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2uzwfnsao.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jvlnitnz.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gt2modpzfbj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2rvoiunim.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2jrknhtoq.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqnmldbt.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2osbbsgoy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2gggxtypi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2nshqayub.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2vqtbecmt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gt2rucfqeqe.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gt2pqmqzike.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2mxfjxkcd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gt2gblclacx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gt2vzvyissn.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gt2mnnyehyb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gt2onlyqcxi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2bzzdzoer.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2vztjpdbs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2lfdpeqbl.html

[I03] 提取捕获分组
来源：http://dali.tianlin.xyz/Article/details/gt2yxkhlnxv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gt2dzbeubws.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2trsxzjrr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2bryhdayt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yangfankeji.com/Article/details/gt2jloyxlia.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gt2zdbjtznx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gt2nzbruttf.html


<!-- 参考信息 -->