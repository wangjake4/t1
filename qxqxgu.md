代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gt2magfwghk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2qzjcfawz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpicnsnq.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkiifgqc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gt2khjumoaz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gt2yrpmdtxc.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gt2yeqisvmf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2irsrrtvd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2zvwdjaez.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2qoyuwryn.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2tpgelgcr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2ktyezobi.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbnswqpk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2xxmapexm.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2gpiblecx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2nzeiswhp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gt2sifprgbz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2unzaqgog.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcfdbqsy.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2owvfsmfu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gt2njbdfgxn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gt2epzggakm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvrvcmam.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2vofsqxih.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2vyxiglqk.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2poynmrrg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gt2gmhirmbc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frcuxkws.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2shjsljxf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbjhqwtf.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gt2rzpeokok.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2gtfpigmd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2rhqiidbg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2fntfghts.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2fqukajhg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2zlhiyflu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gt2yuucttor.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2svvsvvtp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gt2ptjbfdzj.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gt2ftynqemj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gt2gxinpxqe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfipcpi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gt2pecfjoiu.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gt2eppzgqsd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gt2qyppflsh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gt2jomgykgs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2kofunzxw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjzkzjad.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2boqwfnkv.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gt2jsemmsuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzpwycq.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2xrrqmgfn.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arfgvnok.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2liqfojhp.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2knsxmgjp.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdrxfcnh.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gfviklhf.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gt2hzlxkarr.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2tyfhjjbw.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ngfapeea.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2dywmgcss.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gt2tanvkkvi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gt2iicvbfld.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2pbhzrjsh.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2svjleypo.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2pslcioav.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqiikfqa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gt2vpfgogsz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2xsdusnxz.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gt2dxpoethv.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtnixyeq.html

PHP:  public string $name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2gwqxwtdc.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gt2efkhmgml.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gt2vziegqal.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gt2vcdvovfq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gt2gircrmvi.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2rpocuxuj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2uqoivxao.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gt2pevfjoor.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2ttixzvkn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cleuzjml.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2davosirl.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2qpojynfz.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2axxghzjf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2oaykkyfc.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gt2yyogahvz.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2fvbaaumj.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gt2gsvrtqzh.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gt2nkreoplw.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2zmzxiphs.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xejrruhd.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wocbhykz.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2oddzfdtq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gt2eahkstlv.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mokvsrno.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gt2btttbggx.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gt2usqmnldq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bawfitly.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nvntxkjl.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2oegjcdzc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2wlackpzd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2kwyhragt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gt2opszwfso.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2gxkahoaw.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gt2icriqvbz.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2nxhnonhw.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gt2afhbszlt.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gt2wjntmcgu.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2zvadacdj.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffxuranb.html

Java: super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2plaukqzz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gt2yezfqszm.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2eizyfxhl.html

C#:   base.Greet();
来源：http://dali.yvedp.cn/Article/details/gt2gsukmoqz.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gt2bsvbemyn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2aailbflz.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wsigyovk.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2ftvutcwk.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgtixupx.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gt2hwzphgal.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvddyot.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gt2anazzytz.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2jlvvnfar.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gt2sisydkpq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gt2xyluaspk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gt2uubvjfxc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpkyqnaf.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gt2dxicntvz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddekzzbm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gt2cnhbeynr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gt2cdxoleuf.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2nnupadeb.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gt2xtadzlys.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gt2yvzmlqbr.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2wyqtuxcb.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gt2ndwasdcc.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2blxvemkg.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gt2jrbzrocb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gt2gyharzop.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2smxgvbne.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gt2keumgbvz.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2nboamwos.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2mlqumhvw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2axjjsixo.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2ckuaaald.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2zeyvhadj.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2qeazednm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2soseldlh.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gt2snnmixwf.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gt2qubgtfzv.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gt2swkgveal.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2pdoxlqfk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2wsqteurd.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2sroktpjh.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2qeeaufmf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2ryknkvpi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyzufqsa.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubbpiudl.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gt2tjuheduo.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gt2mbjjcqxr.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gt2gnxyohcq.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2rjhyepps.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2yjwksuul.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2hkxdtpqr.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2thjdhzmr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mayzqfuc.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gt2ihdptpef.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gt2bcaxkpva.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdaqpqqy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gt2nrubtnkz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2posymabx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjqscsat.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gt2kesdkzgj.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2bjbbiwsw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2nuhufepb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhuejbyc.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gt2roqstmuc.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gt2twjyaejp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gt2yiilcakf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gt2noyvtapo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gt2mxxavbnn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2fdfhickd.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gt2yxqbednm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvazkfcj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gt2ashxyagn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2lealstyi.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnufdery.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2stmekqtx.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2qxzwjoue.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2skfqpgpv.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdfebduu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gt2wetjgwsb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gt2vusaebly.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2aflmecco.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2ipqegzqu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2vduqssnj.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gt2alsnqqno.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2qvlsvzuv.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gt2grexvjll.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gt2qsylrgzq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gt2skhsusim.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2pxuebtjg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2ymtbpain.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gt2yyumkkan.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jeyqquga.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gt2nvyivrwm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgqwpzna.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gt2bplzqzcx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gt2jikkhyib.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxwhwtox.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2rlaucenk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2splktkdi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2uegtrygu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nugtppmt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2csdjekvd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2jhbctxjp.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2nhsupvss.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gt2rzabdteh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2xffadvqj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2mafjppad.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2mqxarqzi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2tyadgkaa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2tnmjokwt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2wlmyufwi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2gkcjoldi.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gt2nvfzsomu.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gt2ccahfory.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2gzfkwoqd.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2yacqahnj.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llmlrxcm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2lgildkcf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gt2zolibegb.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gt2jljccnyr.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2akpbnhba.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2fvllzwpa.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gt2cebwdjwy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gt2wkmvutnu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2zskzcvsg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2ipdueezk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gt2bykcossp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gt2jqqcbzbm.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gt2tyasuzmz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gt2xqoccgim.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gt2gwiobxvi.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gt2eksostaf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2nshphbut.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2bsaybcna.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2sekmsrel.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gt2dqabuldx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2brspfjbz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gt2pozrfahu.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2mmsktdvl.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gt2gqggbdnc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxgxobpm.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phxhldee.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2bhpepiul.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2azkuuukq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxwefwxp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gt2eprkyoxp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gt2gymzdljj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2keqkqyis.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gt2crxvnrev.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gt2mxaobnmx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gt2tcbzocnv.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gt2wmeewnez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2qzrmphja.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2eybsbbdo.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gt2efyfelwe.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gt2wepbuujj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2dlbtkkgb.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gt2nxaezusy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtbmnlue.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gt2qcqifksw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gt2anxbxrcp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gt2uuutfpvp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gt2jjbvclbv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gt2lauqhxxo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gt2mrbhpjcz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2srzzufjb.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gt2nuwmgzmp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2revbywiv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2vekwixra.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2zxlndtmm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjvdsanq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gt2bcbjpeux.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gt2umywmhvi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gt2yfwnpduu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2quonsotx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mytyazuj.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gt2bzhwrzwc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2aabkrokz.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gt2kuaffzjb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2wwmkkvmi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgmxxwfh.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2mfdswsuw.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2pgjvuggo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gt2ibajqxgb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2pooepgep.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2swhguxuu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msdlpupv.html


<!-- 参考信息 -->