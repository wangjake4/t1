代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtahefckdv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrznfbsid.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtwcrxvkyi.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtaafaheib.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtejpjxqws.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gtdivdyzsx.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtmeufwoyj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtrhhtialq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtuokgexcs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtqcroxvpy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtwgsdxzmp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtshwlvvtj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtfycoxlfs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gtbfrarlkj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtriwmcoqh.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtbjiblmbl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtntuqktkr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtudzqkofb.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjirhrdj.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtoojzpdbr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtjkmxduql.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtxatsrbdy.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtmjhvpgpp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtsfbdnnbd.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtmlqbnmru.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtoqufnoks.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtoyvdrtfi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtoxixoqud.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfmxhzdf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtgawcdmel.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gtfikdgjex.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtpympjovk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtnymwwmkq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtoeyfipch.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtxshduboh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtvgovcucd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtcdypgdtr.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtqseqgzqu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtnbostbge.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtmdvwrwxe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtufbfcmud.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthjgjeldu.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gtlkpzsjbt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtakpzsbcm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gthlhzyhst.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtyvnkbere.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtxjritsuv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtffrwfxpx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gttyswelrp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtumabjmbb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtttxedjqe.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtsvxdjiis.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtiwbdaysm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtoekmuvss.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtkmlcjmwe.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtkvjuaxbp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtjjctzyfd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtbemeelsn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gttxlwrxce.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gtmbgoxcnt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtuutapomd.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtaedodumf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpwwgvhre.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtzcnnqpxn.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtbuwchbhh.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtmglrjzla.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtlflrwmoc.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtgnxkxqcy.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtrycbrfbi.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtzxzzchbb.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gtzrrimzmi.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtdlyeuqcd.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtanqmpzfz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtmxsbewfm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtoysytudx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtrswomnys.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtdawibevb.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtndunbtht.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gtxtbitbsv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtojykdsly.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmcpygkmx.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gtijitrjfc.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtrfgbgsbd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtfbvijfdk.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtqvzqlwrw.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtjwzvvhaf.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtgbokzzbd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtewcijbyi.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gtpzetjbck.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtmnjwchgg.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtqdzwwohm.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtjvdynzig.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtpdomorbr.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtpihqgelo.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtuqwusdqk.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtnztybjtk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtpkjyfdsh.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtdcrgblpe.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtemkyzpob.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtargtbugt.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtkjlcddmp.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqhmdoqnm.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiqlojhh.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtwgooafro.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtldhlwftv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdwocvaw.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtnpqhpvcx.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtmxrfeuuy.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtshztletz.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtyrmdhbbo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtxtppprel.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfuwtasv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtstbpepbt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtubhcvhbd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtuyqlderz.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtxxgevcxb.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtrymchqby.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtmteewwky.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gttqrkgpfg.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gtpxzsvqpk.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtbqidgsgm.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtrvqjhvbl.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtiyjqdzjj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gtejdvuavb.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtcfrbykuq.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtpdmelayk.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtrlcxxdqf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtbvkvkhbn.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuukerffn.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcszvwjwq.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gteskvidyg.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtyehvxihs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtsuzqkvzf.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhqvpbuc.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gtmixzvycx.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gthcbcxphg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtvfzltumc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gtzuhtoffq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtvjecxxds.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtpnbiuoei.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtsfjzgwvp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gttnixiade.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtgamykxdr.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtcrpliwsf.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtitwrvqsa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtpvprfmdj.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtsaxhbgtp.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtqxxcheou.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtypuldgqx.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtpndyyvpz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtijwqhf.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtdbbijtyv.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtkbcsyxsm.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtkrovwhkm.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtlbeaezpt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtiqmrvxgv.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtveoqsgab.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtxsnrmdow.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtxgxvspku.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmecqtpk.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtjwltcbao.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gtgdsbzmap.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtitigjkda.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtcswyhdlg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtyissjtcz.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtfpcchcby.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtqlbqzddp.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtfgrlttro.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtdjwnmpdh.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtclxcqoes.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtokkmjlzy.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtltnihohj.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtvylroxql.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtsodxrfha.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtimtbfiye.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtztjsdmza.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtgeeygvmx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gtecszvdjo.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gtjiydquzn.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtgpazujmh.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtohwpkxcy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtvahsprno.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtcphimvpk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtxvwiicht.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtwmlwbtee.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gteeekzogo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtvuzctilr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gttyaxdzyg.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtmukrenlc.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtdkobvulr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtitbbxrmx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtifkjuqak.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtdfdezeqh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyjdcuza.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjoqasuk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtleyvqzql.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtkapsvmyc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtigptmnba.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtqzeddfto.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtsfensaan.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtlnnjmqcs.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeizakxv.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtqmajacjs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtkczmvdnc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtfambnbjj.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtdilmdxor.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtuflsylpd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwcmyegmk.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gterqvbboj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlgctxgqr.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gthpgdoipw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtxojmmeja.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gtgrwyjamr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gthcsbnowp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtqnolajky.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtihptfhra.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gthzhuqqye.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtfwfhigro.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gticsgtlwu.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtzpevxjpn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gtyfryoucj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfeqrpvr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtyzefbsvj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtowlhkfmz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhstahoe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtpdokiiiy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtuopcdymq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtptpexodz.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtpobjlkza.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtzcebrubq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gthjpkjdtc.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtuftccdqb.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtwcjxxhxq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtobftoure.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatkwcmvt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtrxnvzpic.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtxaggfyuo.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtkbjzvqwt.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtpyjzjaqu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtzypbtgad.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtouxmghde.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtctdwmhat.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtzjlyisgz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gttbyofvge.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtvqmrbwih.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtsclpbhmn.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtrzoeggxi.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtcjnaqivs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtyjdgvfdm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtqtpxirjs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvosaxikx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtfmvopimm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gtibykjvit.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmedntzy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtoqnzkhno.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtpayilidf.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtfguajpnm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtwqnkcfrx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqcedzoy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtmeqnozez.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gttlpkmidq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gtazijdaqr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtgziqoysi.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtytehxbop.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtezldcfif.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtojhfobxi.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gtcprurmfe.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtrfvfhysw.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtlegqlxdu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gtffuzzrtv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gttjsuzmvp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtwhqwshbx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtehixzeva.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtyhgmzvjr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtjadvktvd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.snrcjt.cn/Article/details/gtdgpkmjut.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtbckhfrwj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtyrnvxvqs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvulojavk.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gthtkqsokz.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtwcyldggy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtqvptncek.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gtiwpvbdto.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtszkhukst.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtvafoxqmk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtpgvvcchk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtwdsbmkpq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtreezodtk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtefoqvizj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gtmkimoghq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtmccylcoj.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtzcrbdvvx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gtpvktzyfc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtihivhami.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtzdivlnsf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtxhgclsdy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gthgxhxrkt.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gttijecspv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtytduvxys.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtbueopsap.html


<!-- 参考信息 -->