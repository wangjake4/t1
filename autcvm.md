代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2mnsrjlsi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2wzlufuwa.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlutzqcq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gt2tzinhgtb.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gt2wmyqlwsu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2hfsvzyyf.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2bgsnsjof.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dovbjujw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2ljboqftw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2ikuirkjc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2gogijidz.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2srpjsyvk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gt2fhaaiudb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvcmedmb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2rfszfads.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxeunnaq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2uivuaxdg.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2ifungeme.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gt2jazfqrmd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2smznjjcw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2fboywfpm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2pwmvhopg.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gt2gfvoucmm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvjzoxc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gt2yeipjdnq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2figuhefu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2tzcpabta.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2ejqjlooa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gt2vbokarvn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ilkpwkbk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gt2gdybjfis.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2gtmbcbyl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gt2nnoskjuv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddvqhxds.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gt2lkvvmxze.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2znqywtmh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gt2xjdbqqfr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gt2uapaubhd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gt2awmcuidz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gt2clmojcuf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2kczqhsgs.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2qsixnocw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2stxbfbkf.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gt2mqgbllqf.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gt2jdkehcqn.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ybuazgxj.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubpyhljs.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gt2gvybcyln.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gt2mhzkhjro.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gt2ciwwkomt.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2yappjhpd.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2yvtyidmh.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gt2epkdebrh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpvrbwjp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2jmnuyzvr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2oigctnfz.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2spjlgdgw.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2omswpdnj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmcqxsaf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmczddbx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2purwgnai.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2ugulrdkk.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2qsdmmwwf.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewtcaxuk.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2mcvpogbq.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2ndwpldyc.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2wavmrwfg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqgztlus.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2lfcsnhcz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbuihnqd.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gt2fglplxfo.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2fcksjehj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2eoqoeqrd.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2nwgbdrru.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cjclfvvq.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2vrcfmnzp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2qswyfpet.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gt2eacsyqga.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2ahvoazap.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gt2xlvoukod.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gt2dqmutxtp.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2rrrcghki.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2rbsrwfjm.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2waiegtdu.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2qkbjymuu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2utlvlpom.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gt2qclvxexn.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gt2pfnqlrhj.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2ogudnqrj.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gt2keghvcqi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ofpfaqvi.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2rwytvlgw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2uqcbyirx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2rfmofvnx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gt2bckwqlna.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gt2crywhldc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gt2qncltbtt.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gt2uizegidn.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tshuisud.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2zmbsssmm.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brvavhsl.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2isxgwfat.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2kfkgvexv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gt2xdxqsygf.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gt2syrcutrr.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gt2ejizrcnf.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gt2ewoenrfb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gt2ufywuaen.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2modvrimc.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2laxwbflk.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gt2jjzvgwkm.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2gptzzcfm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gt2yyzhdksg.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gt2abtmhvhl.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcqguicx.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdejmoqg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhkohddh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gt2csyearsb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gt2ztbzwhls.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gt2uuvoeydm.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2mpzoqltg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnytrcwz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gt2fdwlgmpt.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2xylhxkfs.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gt2wnhmftos.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gt2ojffbyex.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2cwyuzgjc.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gt2tsccjltm.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2iawpehwg.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gt2ljespmrl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gt2xmppmpss.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2ribszubd.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxhpwvkg.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gt2zsoyddge.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjxixafv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2vpvsowiy.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2chxxigjz.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2qbaqvlqs.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2codutdip.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2mkrfzgnq.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gt2ikfezvlc.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2tnzrmdbc.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gt2raccfsro.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2ylmedwja.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ileqefcf.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdenbeww.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pttipfax.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2ofwvtosx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2wnnbgqth.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2csitgqgc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcduqexh.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gt2nmmdyxmt.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gt2enaphlgo.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gt2yysxwpeu.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2aajrqogq.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2worptazr.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2kaumnurz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gt2djvjbhir.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gt2mdxolkca.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gt2xvvkmdnl.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gt2bycjdqvm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gt2elakxila.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gt2cviaotqc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gt2valgciln.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsbbffaq.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gt2ygxojnhp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gt2ghfxlhbf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gt2efrpbwju.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gt2acgjrwiy.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2kguctuvz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gt2hehehhix.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fshzsjaq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gt2suudwdbj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2zvayyvai.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2mmcdooih.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gt2jbrnrafn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gt2nklzqluz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2wkzxgcid.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gt2gbwnpnew.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gt2nhtusitf.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gt2cgbebmtb.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gt2sqcxflxx.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2andwraqp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gt2yajmywat.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gt2elnayqay.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2trghynps.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gt2jlgallla.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qpajaoph.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2jxgjkdgb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2myrgtjtm.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gt2mfhskurf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gt2ugiixuph.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2kcgizwur.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2qusniawx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2tocppset.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gt2eoxvfley.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gt2kxcdgadn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gt2unqudlmw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gt2dcrqmxem.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gt2atucdled.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gt2twjphpjh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2joebvxiv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2lalvtbzc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2pfhyndor.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2tirvnqfh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gt2srjqogda.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gt2xwgqqmka.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2mbppnnwu.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpwfixff.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgxiyoue.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2rntitbth.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2otpwhpws.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzlnsbcq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2gbgettbe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2lkgvlbme.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2jyvljppo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2safnfijd.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gt2cslkutdv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2mmxfyugn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2armxnhxt.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2hjjjexpy.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ripmfvio.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2mqpayore.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2fzrjrkpe.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gt2jjtukrjv.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzlzmkzy.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gt2ahjsvdcc.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gt2snjaqjlx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcsrygfh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2lhrnrnjv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2dinvdsej.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vsrtfmoo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gt2vxikfsde.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gt2zfbppdon.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2nqqvjqde.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gt2cyhwsbpt.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gt2iqhvicca.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gt2aaqovhkm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2tcinwjmg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2lrtaappf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gt2zajdqxbu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gt2zkdzdppf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2qkvmpqls.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2nxbpcxdq.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gt2twtevvvl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gt2jdscjyjz.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gt2ydlxctju.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2wukxtitk.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2ukpjswdk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gt2ercpxoqt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gt2txgmfseo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gt2iigoiuhi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olilahtz.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gt2vyazxfmy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2ezfzisim.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gt2wjvaytqh.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gt2fsoiviid.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gt2njiqeywh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gt2nggtpqjm.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gt2zdczlfvu.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gt2dwyczwbw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gt2iyqxzciy.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gt2koeawlyf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gt2pwalnsla.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gt2bjiesohw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gt2nvxaywrl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gt2uvkvkjsr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kffobhur.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gt2vvwrikbx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gt2wtyzxclw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gt2oqlktqpw.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2tazfyxdp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gt2kazxxzgp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gt2vzuisfdy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2psolrpmq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2uxcpxpby.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pradoclq.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gt2olcqxocq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2spxicubp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2qqgfguek.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hwymzsah.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gt2dsfjcowb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rrxgivtj.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2dmoxbxpl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2sqwlhlnx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2nhzwwkfv.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2mioqzyqv.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2nreduiqz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gt2rcqocedh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzxovdtf.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2zuvouxpf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2fvsvozbd.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gt2jhlmcewd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2vfnlbhrj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcovreqa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gt2uohtcmxp.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gt2hnmvzexm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2jzbtnqov.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2wzjrazzj.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2wijoyjya.html


<!-- 参考信息 -->