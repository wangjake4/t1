代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2iyuwebci.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2zrlahrqe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2oyvpspvh.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2wkngatte.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2qnnhzopw.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulfavqgr.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gt2ltqmyjet.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gt2ezgzngri.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gt2bydotfmd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2qjyyqoyg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2opmqfyum.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2vvxogtjb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxtawjtw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gt2fmhhrqtz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gt2ptraqqya.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gt2pwgkapce.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gt2eikmhjmm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gt2wqualvgv.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvtjakbj.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qufjpzgu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2gmagqcqx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2awwbsyzj.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gt2fgpvprhd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2qakfyiqq.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gt2aggtsvut.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2fxlloqbf.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mfwgopqb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2uzfjkcyr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2ngadecen.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2mopuycby.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gt2fnxngpgt.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2zexaekyw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gt2xzuwdkwl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gt2hotftgml.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ismbftnw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2dyhnzjkv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2yqxfkaao.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2khbyaezp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gt2lzcpgnbu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2irwvnynq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2atsqxjrn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2inlujgfz.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gt2jroqgpfp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2yxlphrkb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gt2vzkhiuxc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2zmkdrmwd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2jkhwvpdq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2gmucesvm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gt2aenghags.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2hxqiaqwo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gt2omfuicug.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gihojeqk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gt2temkhvly.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gt2nqvzcyop.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2biipxvbd.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2nedrvncn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gt2dnkqwsld.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gt2fwrebauf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2jfhxygyr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2ypdxiuom.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2rntztidr.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gt2nlmcnwts.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2heukccgv.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gt2jmckqjjx.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gt2lzeijegj.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gt2kqmlhqno.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2uvsuximp.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gt2nigroach.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2gixlxhfz.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gt2mlransus.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2ddvkgmph.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2bpxzowyk.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2djmxcknv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gt2xkoijnte.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvtswvgt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2qqnvudlt.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gt2uieibtiq.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ntnxqeha.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gt2wqguzxly.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2slasytjv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bfjbdmdw.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2aeuhojca.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2wyybjtpo.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gt2bicoyzbx.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2tzwbrkwo.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2rljguwzs.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2owwqvphs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gt2tslbozdt.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2iquaqvfe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gt2yyhrrkyz.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gt2ogjnwcmv.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2nsnhphkd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2xglcrujt.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqpuzyaj.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2etmkgeql.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2xjiydobq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2tefoejmm.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2wiqmzzhw.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2oksmhlph.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2uinguqtl.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gt2pjrgjgfn.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2kbyzgqun.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2edbxffdb.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxcsluuk.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2gphqmalt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gt2yvznosvk.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlsvdqqq.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gt2lrxriaoi.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gt2jxajmtvp.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zidqioky.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2dyjqhosc.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2vqqmodhl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2hlismdes.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2zcubuddi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gt2tcnmzuuq.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gt2qmffouyl.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qroljbbg.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gt2rvfldxtz.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gt2xctwtpre.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2pcesxmax.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2qixviuiv.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2axqitvgm.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2kqhumnkj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gt2wrqauasq.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gt2vzhoakjp.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gt2xqdboelz.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gt2gvelhtkd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gt2nyvfqueb.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gt2jyffkgim.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2kjynkyxs.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gt2qxcplrhb.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gt2sihgghpb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2zrexqcdg.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gt2xhxzbyya.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2fxtjezuf.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gt2swimprga.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gt2dzcfnxpx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gt2lpviizhh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2fvgxdepu.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gt2xjhhqmhg.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gt2fcvvrokr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gt2nizuhwan.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gt2iigjkfto.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gt2ecshfxxv.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gt2nivsfqbx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gt2xumszrux.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2uhbcxqpq.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gt2ibvwdnej.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2kpzhedwy.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gt2figyyujj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gt2eqivjcfx.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2npqbtjjt.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gt2yoqmucny.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjhsgvsr.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gt2ttskvbme.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2nsukjcvd.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gt2ctqusyfj.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2ypdkhswc.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2vwnsfllv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbnrpfez.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2tmulmdfn.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gzcgmucw.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2kkgvuedv.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2waldypgd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2okkmmhoj.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2iocpxsra.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ffsvwftb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2ppgqqist.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2scxojjpu.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2iptiqese.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2osrjaylw.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gt2cimpadsd.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucvcuvsz.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2raoijlyz.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2gfstpacb.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2hznvdxeq.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2bzyjlzmi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gt2slbxhfeq.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gt2ermoxdyu.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gt2pudpkotc.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gt2ebubqswx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gt2jlbcilyr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2ffxbsssn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gt2tqcjzjcb.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gt2jjkbjmyz.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gt2xcygiutj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gt2qlrovyyr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gt2ymzqlyzg.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gt2pwhcfurk.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gt2akaprart.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gt2mfdxyqtq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imzjthck.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftlkwykn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2lddmnwng.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmukesbb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gt2vxwbxyve.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gt2lvwihfmm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2daumdsqh.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gt2kpshqwkv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gt2naczjevi.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gt2kvmsrqzn.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2pncrrczq.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2muparmfk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gt2vjlufjxv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2nudtibzd.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2rdnzykud.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2xsdhioez.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kyfpewts.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gt2elfaxuxn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2efpejfld.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gt2vpqtyfdv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gt2mqalsfji.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2mkdrqugr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2qbprqotz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldnhbmjl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gt2ucwiwxfi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gt2abpipate.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxzdhsnc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gt2umvmmvil.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gt2lhnvwife.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gt2pbkggpic.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2akyqlwkt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2uxhyjsor.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2hotbkzwu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2xpjrqcmw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gt2vhpcjfyg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gt2gxqdeayd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2fsedynpr.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2rlxvgsor.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gt2vrbzmtqo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2epordkoa.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2crasowee.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2xpivuftb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2reuaknit.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2nyqxxxdu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gt2ldqklsuw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2qrgnhqmd.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gt2ccofrhrd.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gt2eownwkrg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2xklraesd.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gt2jmtqpkjt.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2wiqglqvh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lybqdkah.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gt2xelmdvun.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gt2vgvkxyqs.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2kngxurgk.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gt2yhozbmhd.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gt2fwnunume.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gt2ukqhmqcx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gt2ajozoyyl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2xfqsdnis.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gt2uwtlfsic.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gt2bzegvfra.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gt2mghpagdm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gt2zllvnmom.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gt2jggczmhh.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgzwvkum.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2ogcswofg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2ublhkhrm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2vxjsdktl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gt2igxtypfc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gt2hcmxocgv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmeriasj.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2unhszjod.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gt2bsxmhzxk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2wjbvhdic.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2ebdlfgxl.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2rskpcxxg.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2erwluohs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gt2fiwzfkgl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gt2yilfssrf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gt2nddfqybb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2xlmijtuj.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gt2twqdfxlf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gt2xsoolwib.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2doibvcra.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gt2dsakdhuk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2frfyyijf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gt2olurzjba.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gt2qbqliqxh.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gt2kkjwuuqj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gt2bhttvhaf.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2npypjgnk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2evhoikkv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gt2pcbytvtt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gt2cnvpsghj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gt2fhfldqhb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gt2aumtgfvv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gt2cunaaevv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gt2dhqdjwhw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gt2okelbuvj.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gt2obiobpbm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gt2gmulfivl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezvmisud.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2vvutcmzy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2gurtjtok.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gt2jvdfdchr.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gt2wsgiwefe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpxrbjuu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2jdoocvxw.html


<!-- 参考信息 -->