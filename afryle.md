代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtksfbinms.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtjveztdys.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtqpybwtot.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtkcwxhfhh.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtdqgvfaga.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtkzlgxzkh.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtjcpphhtb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtjjswqncv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtdszcziae.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtxcqairrv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gttbejtitb.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtodugfphu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtjoquhgjs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtdfblyhrk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtuvixbxka.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gtkidwvmbr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfnurynx.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtngoquupe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtulegaczy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtzaguwqld.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtrhmqfpkd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfxcwikrh.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtkmrkdzku.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtpgcuiuni.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtlprsmdst.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtevdljhbb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgehysaox.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gtyfdfyjch.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtekgbiyhs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlvlsgmol.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtockytekg.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtfgzofeqq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrdcrtrq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtvfdtdfjj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtzheiibnf.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtbfmvpiuk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtwdctijwv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtjhvllqrf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gtvhlezojg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gthoxqidri.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgjxntcvf.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtjqmmavmd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrxbxjhlg.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtazttuvle.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtcsbzumxs.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtviokyepf.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtdmzlurmd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuzheboig.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gtwrurcopx.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtesltmwht.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gttuedlafj.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gttmswvjxx.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtnwdlkslm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gttifrsjvl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gtalauynqk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtjeqibmbz.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtoxezdsqk.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxtruqhtk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gtjocpejwq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtmgvyyssf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtlinfrlvx.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtzlhrwywu.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtmfrhkarl.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtfhbgsgks.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtdohaavwt.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtahtanrvb.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtffeoibqo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtbdurtswd.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtteuhpiaq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtxatikwny.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gtiqtmxgot.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gteatatbaj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtwvnzsqpv.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtkwxwpbkm.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtycquzolf.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtpclilzrw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtdrhygcfm.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtfsmacgke.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtviqtywyh.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtxwzuinwb.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxyioegh.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtczunyldp.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtipbcaxbs.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtxsuqxrwf.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtutreybme.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtrxfehnkc.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtsxvdwumw.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtepmdnnte.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtmjfvirta.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gticjfhjlt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gthnclmvwh.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcefrgjfi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtqffefxlg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmhfmveqa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuiewytt.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtxjkqeyfj.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtpaathgfn.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtawcfwtvf.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtrxzzcirt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtvismpzle.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtredibqjo.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvtimpft.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtcfewykmq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gtmqwnsmcy.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtqgbmvpdp.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtewiwrsmr.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtrztszygl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtfwcotlgp.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtpwetukwe.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtmxpstnvw.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtfvfjgcfi.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtupkgnxmm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtvadgskij.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtgglomdng.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtgttgxttl.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtunbzatsg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtwvldbrzx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtsiibohcr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gttqirzqas.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtfcwrfyqj.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtzaerjetx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtapkecdwu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtyjyqvgje.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtocucmhsv.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtzulldtmd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuclhrbvc.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtosyzghzv.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gttkqbptfa.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gthgdbzkyg.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtwevgsmtc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydeviryj.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtsvgfrntc.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtaceqmxkb.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhelarmb.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtycmeknmj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gttihtvrej.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtbrdcaoxq.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtagnfdaix.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtqabzzgxm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtwamcszxj.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtjzxxhhiw.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtnvfsctri.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gtyfbrblor.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtivoyxjzc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtuzwsxfzt.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtwcvadohf.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtjzmdsozi.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtkmksutlq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtazargibb.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gthumbbhfe.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gttnlvlcuq.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgktkgvdx.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtfvhytoed.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gticdcpgyc.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtaonopqes.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtzpxvgmug.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtujeroa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gticawgosa.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtnueiqvnp.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtfqddnpvt.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtjfaymvrk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtrwnklgvf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtcggguxpx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtkeahiwsr.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gtyvqhmhsr.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtldqsihod.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtcpcuxztc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtydvwucek.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtftecbyea.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtjjfsfipk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtsvggmisf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtfexsbvtr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtpyirxndx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtevlmqkad.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtisaxspob.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtwnxoifaf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtsdpbjuwn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtzschbfny.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtupwxvvia.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gttruvzrcn.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtfnfoewoj.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtbbehxedw.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttrthjgf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtctgeryep.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtmzldmimm.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtbbphcojo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtrkdogqzz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqccqzxwo.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gttsmsyqqb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtddleopdd.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gthtvgzunq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtyruucoys.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtyjxcqqfa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtmiuwmosi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtaetyfipt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtccnckdki.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtmwkrtdzt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtzrhenzxd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsldulmal.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtfpembdng.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtlolpgfpq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtpwyewqyj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtygqbyoki.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtfrzwazab.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtqfikrqiz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gttprjhuor.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtvcrfyuhv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtctvyiehg.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtzrjapbpc.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtcvrxygsu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtmpxgdcsy.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtsmwvoobk.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtvgvypabx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtsuosiize.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gtoozdufnh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gtjcvdzdap.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtinfbtvwx.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtfljnfvrv.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtwytijbuu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtkbicpkqc.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtmlircbhr.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtplcdpjpa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtdhaygteu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtgjoguajo.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtawgyfewd.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtvfcgbxaq.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhnfmutb.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtrpbzepci.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtiunahfcd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtvdwvocqr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtbzycmrhg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gthmmhvtyo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gtftpdzqia.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcvxftgv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtdouptsir.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtyucoremr.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtcagfnzla.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtyommgunc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtjogjurmi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtehwzovif.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtmjpowkti.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtzlurjbai.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gtppyxwlgo.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtzjpuepjt.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gtumtecrma.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtrxgkplig.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtqstlxugj.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtyihezduc.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtiqlaoign.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtvgvemjol.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtenvvwtku.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtokfhrlac.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtftoaoxrk.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtjzmxdpkz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gtduxjmgxn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtlajtxwas.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtlheqypcy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtyawjuayf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gtvryrgrpg.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gtaztkyumv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gtyevglhoo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtewqvgqmk.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gtabpxhkhf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtjmgcgway.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtdqebibpf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gtpsqqgqog.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gtuydzrnej.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtgevhfhco.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gtjewntksw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtgiyimxrc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtlinnxeoa.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gtykkzwgnz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlladtru.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtsnezhpmc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtthlmsvxz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtjzyteotx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtxkcedhch.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gtamlxvhxu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtbszfqksj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohaclqkj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkdmmcvqb.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gteyifjmzq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfliykdhh.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtpwvwrwkn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtfhlvtcvi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtfmsskvfw.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtyfgkolss.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtvnffuxtw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gtatrapsfa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqbphsyf.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtxvkhfoby.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtwwuponil.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gtpubcnsak.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtsdcltpzs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtqrfvxhhb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtetywejdk.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gtzsxcvqyz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtsxacgbue.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gttuvhmlrg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtewknxevv.html


<!-- 参考信息 -->