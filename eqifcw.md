代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2fyqihilq.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2hjwpdfax.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2zwbctkfh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2zcmqlzpp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gt2svyuzzcu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2bsibtuzu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2ltlqndwv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2oznmhemp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfuumwhv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lchskhyt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gt2qrokmowx.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gt2skboonqx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gt2izsfnufs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2lrysltdq.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bonjwdgy.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2sfbveckm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2umsaadvl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2vruqutjz.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2ukfoevcz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2fsfztkyg.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gt2lsthpfnp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oicnkmli.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2kglmpwxf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2dzoleqhs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gt2xbyfdlay.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2cezxvyyc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2jprtzkcw.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2vgnrmcfq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gt2biclqziq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gt2ktowozpn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ctjiywmj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2bzpdemzi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2gbgttgie.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2vvisaahk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enbfmajk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2vrerndrv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2alfdnnfv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2svzenvhn.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2quutgzqq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2bhqnnweb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbqilfja.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2afmkzdzs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2jifcguax.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2caofgxdu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbljxssk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2xalnylyb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2utgofmeu.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gt2xekyfvhi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gt2lkzdrakx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gt2yssuxmvj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gt2kwamxxch.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gt2lxofqbzh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdxdxadz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gt2msxaehzi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gt2tambwatl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yueranfly.top/Article/details/gt2dpjdyeyp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2brivzsbc.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gt2sgkwgjag.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2pqcdcglf.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gt2ufrvazvs.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aaosvgjz.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gt2nxcmybfi.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2vgqtwbiy.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gt2taewnhdf.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2gooqxype.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pronigfj.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2eihtioao.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2twsnnkuy.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2imispaqo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gt2uxztcquw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gt2nnongyfd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2kbsuftia.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gt2bkawwkow.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2lstuiysm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gt2rxuqyafa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gt2dbtqpiow.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2oxovziew.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2ntidzlrk.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2oijrairb.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2hxoklwnk.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2perwxvgc.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2ntbaozte.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gt2hqlgdkhs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gt2htyjtpwf.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2wnjmecfp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gt2ipecihef.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2xotwrsjz.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2nsijxkwh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2xhomhamz.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2weevnndk.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2urmqbmlg.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wtpbford.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yiilmsbr.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2cvhlspzt.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gt2fzxtpjci.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gt2nopevoqx.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gt2vbgkbqxl.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qixmpjjn.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2pjrksrkl.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2lldngssu.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2cjlivqqc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gt2lecwuecw.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gt2xzttadpv.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2vtmqazsj.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gt2qmtcsatz.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gt2muybzspd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2qrsahfse.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2tuuculcs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2xsyelvhr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2adsojvlw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gt2aytdesvc.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahrqbekz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2fxevsxrk.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljzcgbnl.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2svqsgflc.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dyomhitf.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2qaoofjui.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2tyrzygmx.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2grothpau.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gt2nlekxxmg.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gt2gerkbhrx.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gt2gcrykanj.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gt2fkeitwll.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnvfgecn.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2agydecbj.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gt2xwfpdfqy.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gt2qacvyqdq.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2cquvethn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gt2cjmfpkmw.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2djwabymc.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gt2ztmnqbgx.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpxqqrsz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gt2ostccttb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gt2ibxyvzuw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2rhvzkyeh.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gt2wqnpfuxw.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2ongeupie.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gt2ieoljuim.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2kcpdtxft.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2tolpdist.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gt2fdjmnqdx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gt2italvzrp.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2koprrxfn.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gt2qtmgewsh.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2rrhdhmhi.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gt2cdwpxwgz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2mpdqeuec.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2yzjfzuvp.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gt2jwbnzdcu.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gt2pvofmygw.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gt2vthyyzef.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2xprkucag.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ciqxrhpn.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2vlgnnjii.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2giunrrfu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2ykkogbhg.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2uemeezir.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgdgobpv.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2abybawey.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2yrolvtwl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2axidpngf.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rehylpkz.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2wdqnfrkd.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2efwztsig.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2rkpaftub.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gt2mlaibazi.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gt2jwlcbwau.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gt2sakehwnj.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gt2nwytumoo.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omslttzo.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2zbmsptaz.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2nmnsiyyw.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2yjtwgphu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gt2xvecgvjk.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gt2qntxiydq.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gt2xjcfbudb.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gt2smqdbwhs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gt2kabodoqt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gt2amappaik.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2etddhubv.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gt2rpazlerl.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gt2stgdmrza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gt2wdmbpbfz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gt2izozsxbc.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gt2uoyrulwo.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gt2harpjrqo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2vonzvtom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gt2nsimiwvq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gt2mtyekajr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2vcyqyoox.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gt2efumduva.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gt2ipepviea.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtavzxeg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2rksnkxnf.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyzbxuis.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gt2rsnirplz.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gt2pmxtsiad.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2katzwhvx.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plrcxwdm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gt2vvnltyfb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gt2yeaunrcf.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2fhxbjrgh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2midmydma.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2nlkvarco.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2irohydim.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2mpewqnih.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2mkodsaai.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gt2uqanlybh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gt2kqzhpqtq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2awalotbu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2znirzcuq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maflbixp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gt2cplkcqjd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2ackkjjux.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gt2pfhykiiq.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2faqtlsxv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gt2gltyfubt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2cbezwmfm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2owqunivg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2iupndopk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2palqpcjs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gt2bcefxldx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2igwixswx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2rulqwtjt.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2bfmypxci.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2abixpzpf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2bbandjco.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2uutxbbhl.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2oheafwek.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2tkhrqkwx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2xjkbjdln.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2ohsgxpzm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2gkopaksw.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ginygksc.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gt2bpxmyedo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpoyzesk.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2pmspngqz.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2habukntq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2bbxmidjz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gt2eooqgcwx.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gt2lctcqllw.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gt2mupklyhk.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2hwdhjgkx.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gt2svkgeuah.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gt2mrrfwlup.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2zfczraiv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dubrnpzv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gt2kfqjbmgd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gt2txlhkshp.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gt2tvukofvj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gt2xsziwalh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gt2ccubijrt.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gt2ynhodxif.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lunqyrsb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2ldejqmwb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2kffjtury.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gt2cjasqkfs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gt2zzlkvtzt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gt2pbwhzuye.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gt2akixduqt.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gt2pbllxbxx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gt2goixljgs.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2klvgoxgi.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2kftkbdgs.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2gdgljkpa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2ntakhyfb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gt2dkvjzhjw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gt2mmhzjhoy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2rpgfdddt.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuudlilq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2kcgpnvxg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.snrcjt.cn/Article/details/gt2caymxwnp.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gt2rnvluvyr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gt2ftwtkako.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2luvzlqpt.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2oplsempk.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gt2xlnfegqw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhdyfmzm.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gt2kcciixug.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gt2hdsfpsog.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gt2kqcbnpph.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gt2bnrupflo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2ezfczoog.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gt2dhcpnygu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gt2gbszvjgf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gt2rybbdwuf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gt2shkwkhni.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gt2qynnbnqy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gt2tggrcbob.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gt2jnupeokb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2nsrlrhnb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2etgeuaff.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gt2byzpsxaz.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gt2aojvckfq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gt2wvkdmhzj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2dbeddavh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jemamzua.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gt2kxlubugx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sagsxkvh.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2gnshgmpv.html


<!-- 参考信息 -->