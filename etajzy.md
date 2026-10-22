代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtpmsynczr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtaprafxrt.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtdhaqupim.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtpqkjvrjs.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gtrlnlkhnx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtbviokdrn.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtwlphtuqd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtzfnuphgg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtzqbwfuoa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtkzzfckpb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtrhcqlcpn.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtkwtsnbgj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gtlfmxflhe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtbtwtpxzn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtknicmyou.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtwzairopu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtyxsbdlzd.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnthbqrkw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gtwhhehtbn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtowpxvgih.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtqefnhpgd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtiyncxact.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gtgntbmkwj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvatajlnj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtgltoiwhu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtdkecyvrb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtewnpajyz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtbgrnzown.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtgmyzyavd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtbnozayrx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gtvstqzjgx.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtbiquycvz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtyjarzndw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtoophfmwp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtfrlrobjq.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuenxauqf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtzskpkzeq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtyecjqhaz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtsxesqrtq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtweyuvtwd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjgiyummt.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtsinezqvz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkiqwtaob.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtuewridxg.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtbzqcidlq.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtfrxgzhsl.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtlxvlcpnh.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gtftgvkdkt.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtgioqsslu.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtljyfasrx.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtvtijnaku.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtisaeuyig.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtyqjnubvu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtjbzmxvrv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtbgzwxhhc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtgxqlpqbr.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtgujkruya.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvydqhku.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtkhbsggzs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaubvhtkf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtcuhdnjkb.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtwbryusgb.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtlpwfaiwn.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtqhfnrwpg.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtoedwmfdx.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gtjkjzxlbv.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtrxurrsrn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeqrsuto.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtlcxphftz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtkknlerkm.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtmlumvxnv.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtjzxwkuvf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtvqpfplmo.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtzxepgqgc.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtzvxsoozk.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtqxosybua.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gticigyqdu.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtshfvoxbv.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtzteiewvr.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcpqihtn.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gtzvydwcix.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtfdxqqusf.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gthliemvhs.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtizbfupkj.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtgububagc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtaqcljtui.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdegdxnnb.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtvcorumyg.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gtjjcxbtxj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtwenfmzft.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gthyprwofx.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtmnohttrk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gthmseqfxl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gttxuyhzsf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtxvkbqxaq.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gttzyrpzld.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gtxhphddly.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtkolysncc.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtphwhqthu.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtjmwydbik.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtwzvcpwby.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtwyhnyafu.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gtazamuapz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtsaqthgsq.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtgnxwjrms.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtptmgkyly.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtvyspegrn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtwxjybcaa.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtedlaypwq.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtekskhfwd.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtfuqzufzg.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtqmptgaxb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtxeuvtiia.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gtihetvycr.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gtfwooqjqq.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtxbndgkrc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtpvlndjfc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtyhojxxpc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gthxquvwug.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxdulwde.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtiopuhyab.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtixwgzkye.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtxrwlbtku.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gttaekuict.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtspobynua.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtkusmhxih.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtzkcnkbnb.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtoieeccol.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtztzwetwz.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtnivfglck.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtvgkikgfg.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtljymuycy.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtlcamntpp.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtbkyqklsw.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtlqngexcc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmfiqeofv.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgcbnpyeo.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtwonmsfic.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtzcqercmz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtqzczlvid.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtyppfmhes.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtbpqkmkbv.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gtoyfptidq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtdqlsthip.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtqsmbdxcv.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtlnhznecc.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtxpmjycie.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtdnfbdrgk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthysxxwma.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtbjzubmwr.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtlkzqpipx.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gtlfpzzbsl.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtxvmyrzyg.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtthreeoqs.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gttqyujzid.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtipmjcqmx.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiivmkpa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtsskifftx.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtosxmulfr.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtkiivvmlf.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtrwxwnbvj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gthiwyrsyc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtooqdjjse.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gtozpdtpaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtlrrmpaoj.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtpulpeurh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtcnclnyjb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtjtkincqc.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtstrcwpuy.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtinqaxoxs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtidmaiqcc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtlgclgkcb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtmigyskva.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtnfzeslxw.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gtbzxcjtoy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtnpggcdnz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gthzbwvudy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtdsuelhmc.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtejyiqhuw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtkyuaocyp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtsvcztnly.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtvfaswphw.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtjgrgtoyo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gtgzdmldrl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtklhqdexi.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtmnqbtxvn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtkttqduqy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdzdxpdkj.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtgodfvzkj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtwqhgnpzn.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtnodvyblj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtjrcbpavk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtlllxvlsi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtrapkbmmf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtmjyfwkal.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtornjulyc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtelptdguu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gtfzeycczw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtjntnxqgb.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gttbtewysc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtcgsncbqi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtenjiclrg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtlqxslrui.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtxnyfadpr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtgxqwehma.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtyygeixnw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtjrfdrvme.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtlyzbokqv.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtqtmizgmb.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gttaximzvv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtmyynbasx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtbhavfpxj.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtgunakpor.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtauxakanb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtdgckjspp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtgawfrfvh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtlwftpvfr.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtlyynwjvm.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbmkgenx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtdxoqlwyl.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtbjokdrhi.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtwcwrhdmh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtocawftgx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtvcidukji.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtdsbvvorb.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtytajpxoq.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtvtumlthi.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtahxqtpmz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gtbvrjmqxj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthxnhklay.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtedvdzdck.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtlnxtmxxo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtmctekkfk.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gtpttcgati.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtipoiqqjz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gtzunbufmt.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtxeduuedk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtxdeynbir.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtiexrcqce.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtxeduozna.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtnjckjtzg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtivspzkob.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbescxcrm.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gtohpnblha.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtxqmwdgok.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnxmmehq.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtmkmswzet.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtbzexoeae.html

TS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtjywrtyps.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtjkozsjxf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtjxsqoufd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtobeygzbg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtgiubamwu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtzoowgnmj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtpglaraoj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gtippqrskd.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtjqyikzae.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gttgwklfeo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtiyhrkmiv.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gttmpzctyf.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtbteulaxa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtvewklnlc.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtzyujqplx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtvkuqwtte.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtvbnjisnk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtjyakqppp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtljagtbzj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtpvpeypjg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtusidwdog.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gtadrhsimp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gtwdopcuhe.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gtqiatoilm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtjjwslofs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtdiwntmkm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtxedfwybk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtaajxhdjp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtqrcceeud.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gtxcceqzut.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtgoqhdcch.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtaexmbghq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gttqsnxdqp.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtiniadzzi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryoppkij.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtlwtsrydq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtnaodcbel.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtfnfxfivg.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyzyftar.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gthdadnsvl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmltuptuj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtduqtfzay.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtispgmwuo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtmphkskco.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtxfchkuig.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtypouqamf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtnusozazp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtazqunbuf.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtipnqwhsu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnacbajwk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gtrrqjyfym.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtdnuzyela.html


<!-- 参考信息 -->