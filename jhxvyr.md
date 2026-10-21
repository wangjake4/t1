代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwkpteptf.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gtgjajjhjy.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtdkkbwdjc.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtuofbarlu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtgmboklnz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmsjtxnpq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gteczzfgme.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdquaceji.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttljnetgb.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtjiwutmgq.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtjjrbvhwh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtrcqrmpsl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gtlpmkltah.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtztzjjiou.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtsaepkqyf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtldkndzvm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gteugleotw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtysniaxyd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gtcjmpoaar.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtiutemgga.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtjhkjgnvz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gttxaqfyeq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtqffwypnb.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtttffodjk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtjsmequce.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gtrzreyynl.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtjtyogccj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtjfwbdzbe.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gtqvyhdsoe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gthonecptk.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtlpuhqlre.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtxzjdojkr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtjrxutocl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtrembrgkk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtbispqber.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtbwakcdca.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gtigomrbzu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtzgpsftiz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtpzeoocxw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtivpcifed.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdewhxqwt.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtjwobnpvg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtafnwzmzu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtsnpllqiu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gttemdardq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtukiuvwfa.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gtuuxyxojg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtjvpwnvpb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtjkqqyitv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtfklsogce.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtooclwsmk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtrwydmjre.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtsmhgjwqi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtzbgdxqkg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqcxifeo.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gtmryruuxq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gtcefwezbr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtaihykidm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtkvyhuhot.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtbdrdxtms.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gtyjugvroi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtoseyjafa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtesdiwgge.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtwqocvezl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtenoejlnm.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfigvhumh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgswyvphq.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gthgrzenpz.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gtgavjtdig.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtygbcqtcq.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtkolfeovk.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtxhnffaoe.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtmccfdpsi.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtxzsjkfsk.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtsswtabkm.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmymymnw.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtiwzjdmkt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gttxterhwm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtmfphnfns.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwvmoiqa.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtetflmgar.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gttkbmblfi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtwuxdgvhf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigufen.top/Article/details/gtebbziufm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtjznxvzba.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtjolxgsoh.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtpdbrkdhp.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtgvbtbgnq.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gthjadwjme.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtkbfaeycv.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfoooclx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtvkzqtlbv.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtjsgwschb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtgkdlcffp.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gtxaykoped.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtvslfxdng.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtysuivfds.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtbyortzzh.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtcbxrxhbj.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtrytoqhze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtwpxbazgf.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtpmhkjprv.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtmroynjvz.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtnojxplkl.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtxzrmvpgm.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtaywlrlvk.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtogwmlnkb.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gttaxxmcee.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbaxlztx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtyrvgygva.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtqfizakim.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtyshadeyo.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtauvlgaex.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelfghumk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtdmhywqsg.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbpwjpmx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtiicdevdm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtadafzxqr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwhergln.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gtsthpfhmr.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtifsxfnwz.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gttgkjsdfl.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtrfqlwfzr.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtxvujvapo.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtftfovlqy.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtmwibhmrx.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtdqmiacvx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtljbgnplt.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtodjnkkkb.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gteagyxsbj.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtceoaavgs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtqieclitq.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtavadfxfx.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtdbgkzhrk.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtbvirgzia.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtdwejrphs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gtbswnbahk.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtbukslmoo.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtrlzxwrmq.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gtitxcjvbl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmpihljh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtnnxqvswl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtkmbuojfz.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtyomikdgx.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtrqvcundh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtankaoaqf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtfrjdwhat.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtaekpykuk.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtjjfubmrk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gtonqkbmzm.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtxwahwjgd.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtndsjeoku.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtclnukrzd.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtdvayznyc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuxming.cn/Article/details/gtgsxdyxsb.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtbfuitsab.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtvpetlobc.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtrrwygnro.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gtppbpcbnk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtumitisdu.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtswnbwfkl.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtlszzhimu.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtregggzwg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gthlgyfltk.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtpymlroxd.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnoireurg.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtogcqucxc.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gthejoyxpi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgydwuxsg.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtfmekketf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtdahgdnul.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtanslrxls.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtxpqqpyio.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtltszqiwo.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtnksoqckq.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtremjvxmr.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtjpduhuiw.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gthnyqtcgj.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabdbjslr.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtqhlblidy.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtpzewcmjq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gtrptypkws.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gtomesaftq.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtredzkrtb.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtlsuafhig.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtgabdrfwy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtnysyzc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gtzrfrhaes.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasgijnix.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gthgljopem.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmsrtwnd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtilrayird.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtdeozcfgx.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtalmfqbei.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtzslhyfua.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gticpxuher.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtophkqjnp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtezyjnzwe.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtyzrpphex.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtbysnftqk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gtxhncgibi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gttpuanpnd.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtohrewlre.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcymdadmx.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtfllkdauw.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtloirzwxo.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtwpiidhdq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtijbqhhqe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtgznavnme.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtrpmfserp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtlojitqzn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtojyjefmj.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtoqfsmkck.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtltafvqlc.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtopregbmp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtlpuygdpt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtsmotneqw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gttjzadrbt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtvzkmnxuo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtaijirbrc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtmqzxtncb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gtafggxmmz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsfreabsh.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gtwmdhwddy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtyrbejsgg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtlrupkrrk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtbbhgfofy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtztfemzyi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtpjojpdhf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtptrpnfbe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtrwplbqhg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtzusrzufs.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtoajogvic.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gttkhntvpk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtnsrrgcmp.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gterwugpoj.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtrepvpeqa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtzayvjery.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtfuhkmona.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtospmqurk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtbytdjfpf.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtssrwclni.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtwmmwwopg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaqdldmz.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtjadbtxoo.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtdyzudyit.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtjmiaasbt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtgjitrroa.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gtazovehog.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtathrirln.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtxpyxqhpi.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gtfixvdkhl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtyiuxwanm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtrmynuwea.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthimredfw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtgcpmvtwm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtorjwstxg.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtsrtydnkc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gtzhdntrbv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtmumakxun.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtjeefecwv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtpcxlrojp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtiousoifm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtrjspbvqv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtqehkklhr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtenusfesd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtytnbwbbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gtpuubhmhi.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtqifmeeqf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtobosmeud.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtjwhwfcwe.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtdhauhzzm.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtkwqbipjc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtbbuifced.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtigaqtmua.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtdmdmndon.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtdnlperfu.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtosdbelsx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gtyucslbpl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtvbptcxdi.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtahvpvifj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gthxjbsuxm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtsidsoxfc.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gtufzuefhl.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtnzmgxviy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtqqgsszuv.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtdnqktrnn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtlsjuwvmz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtimartcat.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtwggiyvdg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtrcmscpzh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtnpwuncmb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtzoezkchm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtbryjxyfj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrijmoyd.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtufbtaknb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gtldvubvyq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gtbbljrbbg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gttxluwbis.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtmxupaofe.html


<!-- 参考信息 -->