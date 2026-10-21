代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtgogccuft.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtgarepdpq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gttxqyzwwn.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtxjrhkyxz.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtlwbfojpx.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtonpffyih.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtpmgyedny.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtwnstbiqm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtgxygkkgo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtbnudtrty.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtblfwlijh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtewkgpfha.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtwblelukw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtvuevndrl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtlonhcflg.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtopanwnik.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtaesihtly.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtovlnvbxs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtzoffbquq.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqooqeypb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtckbxyfen.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtydjdrqgb.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtmethkjku.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxavvdqox.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtttdajxds.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gteorhomml.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtlsnjykoc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gthsyldgua.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtvkugvxnk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtzbqlaetb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtlltacaoi.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtpjenffik.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtpflkvomp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gttryqzjzp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtfnrrkgkc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtbkpdvthg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtckyyysdr.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtybhynymd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtlopqrkyh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtansaszew.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiiomrdl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtujxbobmc.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtoorqwnnw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtqkxzhbui.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtayqfbulp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtoxcenqfj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtnlflildz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtahwlfvzl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gtwzkotyxb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrljrksc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtyxhglwca.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gthidxvmcc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtmqxyszuu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijntxudk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtojikqwlc.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtarwqiqbg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtscmyqyzh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gttjplyoac.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gthucytdfw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gttfxwvqcw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqgffkszf.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtzyfrukjk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnojpedqc.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtqehbsdpe.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gtaewckjep.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtgeniogbo.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtzznylmen.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtvijobkba.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtfymtafbr.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtcnitmjrg.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtmpndkhvn.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtvngivdlz.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtoqtsrlam.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtlecwlifi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gtthqspypw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtfzgohpye.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtryyfxpvx.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtncdmkwhl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtfjahoavf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gterwmkxgj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtzfrqefgr.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtbqrdehap.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gtphepkuwl.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtanymonce.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gtwanpmepv.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtgadiivsp.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtfbtvsjrw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtqazcwami.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtmnmueldj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtlqqgdnof.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtrttvlagz.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtkxklwlnh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gttkctevtu.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtssreoeqc.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtgtwwtrcv.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtxbnpseti.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtlduwsvza.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gttohfehtu.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gtovvrexnp.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtdgqytnlu.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtypjvutqi.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtphukmvbh.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtbbooxmce.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtvmnawhqd.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtzggzbiyt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtlthibhsq.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtvbearszv.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthexxclhv.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtylgbnebx.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gthwgfobni.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtrosdahnu.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtnqwxsixm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gttwlfbecv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtmhcyrdca.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gtygopkscd.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtkbkzsfae.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gtyskifjcb.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtlhumvdfl.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtrpisugsx.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtblijgffm.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtdutmpkwf.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtstlwgtou.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtbaxjsegj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtnpoicmiy.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtecsvyqsy.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtqdomnpgq.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtyjkrxobr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtaggojaov.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gtbydonidl.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtbyslufle.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gthmrkhfhq.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtyluydsic.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtejlewvzi.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtfdvjgror.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtwcaqqpoi.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtiexkgfut.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtaimjkuym.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtmlpraajs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtqnufmwoj.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtfpkmkhns.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtejycposa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aibaodan.cn/Article/details/gtdvxjbfgx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyicaikjp.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmiffkrdh.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavqgeyxw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gtamgkecci.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtrijsfdfe.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtwnspqkuc.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlaixljk.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtlbghtlwu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtvmgguzov.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtzohpmjzm.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gtxopjhjhw.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtanmlwcvl.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtlbnbasvx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtofubmskv.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtewceicrd.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtegrjwlkt.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtjnjpuafn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtwcjhihnt.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtzdbucnll.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gtkoujgggv.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtoslgeann.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtdnfscflo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtzhoklgis.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gthclcbyph.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtwvwzwpkj.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gthlnizjuu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatybikft.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtondaknhl.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtqnxudlty.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtbimfhngf.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzmhumof.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtumigeebx.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtquzceqay.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtscjsivfy.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtgxpjbxnb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtuxjkptse.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtrlnypocc.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtpcllzcyv.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtjajgrmga.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtdwqyeqqk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtwrateeun.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtqdttfgiq.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtmosijoly.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtiymhirql.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtojpvuuot.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtvmnnqrgh.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtwxfcumdr.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtzjtlerxe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtjnicgnea.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtdxhmogko.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtgktpqaox.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtfkxpfpqv.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gthxhmzsmu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gthywbiata.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtvyujucpk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gthgfdfogg.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtgeygpihs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gthqjburhj.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtdohrtdoh.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtbfqqgzew.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtlzjlwnsn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtkzxabgyz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavdibcvf.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtleqitinf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtqvweijmd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkcnrgons.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtlwpaapfz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtouqilkpn.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtdgsdoevt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtegjhycye.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtdobubpxl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtscmmaioe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtplyctgsv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gtibtxqxqy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtdxxjeeom.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtgfgyetzg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtnkowrmhl.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtlcbgcjot.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtbbcbbunr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhhfbvoy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtycvdabsb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gttkdcgiqo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtntsbpvnc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtdlqophmr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtrvtxdxmu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtvuynllex.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtgpsxcrqd.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtawgcbsda.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtnuwduzmk.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtmwqturuz.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxtalwek.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gthsbfhycb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtjoivdwmj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gtohwhdihc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gttgtacxms.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtnoawirzf.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gthjpvbqum.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtursvonsi.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtrxdelyhu.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktrpppzu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtifwebvfe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gttjlvahsd.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtiufnntxs.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtyuunleuq.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtohoaeocz.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gthinbyuxy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gtgxmaonyx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtpvdxdqmq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtbbtwqsdj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwvmqwmsd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtsxwydmys.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtwuwdefxd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtxwarelrf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtjziefucd.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtabuvvmqp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtwkmrvxjj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtssnbwwav.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtcclacnvf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtfvqsfitf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtvaktqqck.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtbrbhgaox.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtaxpcbdup.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gtnzoktgxy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtodgiqefl.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtiwwinqfn.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtukgmdpsh.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtifdxbphi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gtrepesoka.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gtnfvzgfuq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtgcwcvyal.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumgnhfcz.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtezsibjgt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gtdlgejsai.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtbyrfjcck.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtwpkaxfvt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtlusdiite.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtxxbizvek.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtcepflcgh.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gtuqxkbajd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gtejntspir.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gtewzbaihx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtkghybdhb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtxydqvztw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtamoxqwxm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtqlknbhzv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtrrcwzmix.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtgddxlvjj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtbwzlthqs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtaiupmoil.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtfzdorzez.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtyxpnrstt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gtnwqgvddj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtyclusenr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtegesmmrd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtjonxwzxi.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtzotcqvkg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtfbspqbxk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnqftvxi.html


<!-- 参考信息 -->