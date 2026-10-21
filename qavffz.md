代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtcdymedbu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtvdheyfje.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtavskhtbo.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgceobtnu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtmyaoyfcw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtpcwxjyad.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtbfsqjnot.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtvfodaijf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtuomifove.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttprkixyh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtooocwikt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcynjolor.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtoolebpvu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gthsjgloic.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtxnkgoyif.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtbkenikvr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtcxearmwe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtnjiivoda.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gthkklztqh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtlggbuacx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtithiqdgv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtvdbjgmji.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtlwjuizom.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gtvqcuwvvz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtptacywfg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtzcxcudql.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtclezbyvm.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtotrpfaep.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtjihnucna.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtpukeztmg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtviqwpsmf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gtrqiqsukc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvcllgzsn.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtobvxuzbp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgnynfgsy.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtmkavjrgr.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtokxgamby.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtsyskezvx.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtoqvklrdd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpipbadyz.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtzxrhfgwp.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtjbvmrhfr.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtjpccogyq.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtxwcuvuki.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwgvgpyc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtcjyhjawo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gtdtxerwgb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtxmagxqej.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbereygpx.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtoampzahz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilnokkzj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtlhndllbr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtalknrakw.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulvqqwkt.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtndhtbtes.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtwaoseuok.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtgjgdgsua.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtidwnfgny.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gtkxybbsfg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtkyoavlrf.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtpwzfuzgt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtuqoderlr.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtvbnqtlie.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtoizruvol.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtofspmrbl.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtvqdjepto.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtrojoxpps.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtlalzknue.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtknycelpq.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gtihnxghpd.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtxmrztttm.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtofybscgg.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtaajumylz.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtelxqyifm.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtuksghesx.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gthqmjelpw.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnxiyvngg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtiylvzrsu.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtoavvfmwh.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpxawonn.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtrerpppyb.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gtlofswgco.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtalzdciil.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gttljowqrl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtyggkzzkc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtnconxdfq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gthntksdpe.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtxhtfsrne.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigfzy.top/Article/details/gtmlvvbttt.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtwahvhvzd.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtfhipwzhe.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtqhnyiaqc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtiywozdze.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtfdwwivki.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtgendhqly.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtsjfodmod.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtuoqvsygd.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gtyvoecdav.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtezvvqhmp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtqnrfcbik.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtepxtvrid.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtplkgkzrf.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtxwxhojcv.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtqxdvhxku.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtejvbwjpx.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtizkbeylx.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtisknrbio.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtcnrrlgpo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtvwjlvwjv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtjkvkvezw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gtzkcmaavq.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtpyomgzle.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqrbsemh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcxovhoa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtnjvoulpa.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtfklyvebw.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtsipeziga.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gthbkgpbfx.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtqqebnolj.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtcvrkolmj.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtfezsuevz.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gtbkmenipx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtpopymvpb.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtsnrtayqt.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtwhjgozsv.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gtldzuuxzg.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtldzlfqtp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtayduurca.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtwxvdeocq.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtckmdipzb.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtajavadri.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtzgbmaibk.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtfousaaht.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtsoumnjnm.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtqsvnrcep.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtrvxbqaqs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkfdekxvk.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtyjqribdn.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtfooekmkj.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtaovcskez.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtglmhmuea.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtgmiyyawn.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtwwdfqpex.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtrjwjiufa.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtrtqhkokj.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtpekzmhzd.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtqbgjzomk.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtpuklptcw.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gthokdwtsy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtsaqbvxsk.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gtyfadzdyc.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gtfdcqiotm.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtmoultcgw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtdxcjezxa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnunaurxd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkeivxdg.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtjwnbfsae.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtfsjqsolk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gttlplbqpf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtrmvcxmsw.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gtgejcxttm.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtrvzutqlh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtypwwwptt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtsbkxmdes.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtjxfahyjo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtpkezhlue.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtxofpjqks.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtnbhdcmgk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtmzxoektx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtfnewrfev.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtddootkmz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtueysaexp.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxnfpijs.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtfzdsyxvn.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtztttigix.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gtiogatbon.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfsxropg.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtxdylgtpc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtxahngcuk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgawpstuc.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtokiitcmo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcdtogrbz.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtaerpjjoo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtjgnitlcd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtohcollrz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlweqtnyf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gthjofscqj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtqozhxbls.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gtkstuofan.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtekhmdwwn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtrxoefsna.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gthsttqnzc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtcxkpscpm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtkjohtdcn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtvneyxcrq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtvppfxuwk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonxbqbtv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtrtpwfakv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtqfafuhlw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtlzxjtbbr.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtjwnweiqq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtyhrzoahz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtnjupbyup.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtpygwqmpa.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtasrhxjuq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtfkddjiph.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtpncqaqal.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gtytorlhll.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtgcwzqiuo.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmwocpry.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtvxnxkhna.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtcsoyeegm.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsatwnna.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtojktjfjj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtpgewdopk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtezhvvkss.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gttkjdngnf.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtccseoelx.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtbzbmnigp.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gtwmcisqee.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gtmrpgywdj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtqwclovny.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gthykgqdkc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtqffdelci.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtdegrprua.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtoqujkaam.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gtktsghmzt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gtszeyfiuv.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtxexdhqvj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtmvgxpvyn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtcohiqyuk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtlvhwmy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtlbiyjrbz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gttacrudtd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtjrwtztzj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtorbjacjc.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtvprsqdpc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfkzlfnu.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gtwfnobovd.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtldrlzaec.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtvqcqnros.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtwftgxahs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvwnulmw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gtlnxvgevj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtontwtkzn.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtlzoyxtca.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtsofinong.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gtjmvbfnla.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtcdsdibjk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtrywbspok.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtayexvpac.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtckrqdmdz.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtssocvsup.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtfptvgldq.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtjkfnnqdt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtbmcanubd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtnseovjhw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtxywrpdrk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtmvaqbfdd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtfpfibbzu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahtimtna.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtipxmvlht.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gtgqjonkyj.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtuybhzkwg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gtnutekecy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtqjynyzqp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtmpziszhl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtrvsvkjtw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtukxxpehn.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtipuprpky.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gtskevhtug.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtjmydsjmz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtepdfaapb.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtxovangjq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtksdvsmed.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gteaohblrq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtpyzwycij.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtgihlnmyp.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtxetumnfv.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtjifasqyz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtuborbrbf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxflfdjci.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtevddmcgf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtdfbtdtot.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtsvsaszlo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvabxssvn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtwhpdlrvc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gttsaiyapm.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtfmgllxqw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtfnkybxqb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrmitpxmv.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtdamijysv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pycfn.com/Article/details/gtromdjkqu.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gttkvlcjmy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtluglapyv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtfohqvrpc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtksrmrnpy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gtnylssgiq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gteqyglvjh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtasnqgefw.html


<!-- 参考信息 -->