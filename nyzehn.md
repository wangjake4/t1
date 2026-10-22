代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cikaghte.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2eydscyzb.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2drybvliz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2hhytlygk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2jaykdlfb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2ozppzpzg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2jlkderqi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gt2zzsesfyr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gt2wupuqjml.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydyqzphh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gt2nnizuqca.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gt2vfhircsy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gt2flojldgw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2ihzeshos.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2fjizgfey.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2ltghhjbj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2lvttalax.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywmolhgp.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gt2aavpnxre.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drzuycyz.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gt2tgjxcqaf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2bdzdbjao.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2zabaroee.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2wucxudmx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2rgjulzik.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2bijrodln.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gt2kmvszqlt.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2xzcxtrhq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gt2aegubpbb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2ucxzhcna.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2fgytolhl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.birdmap.top/Article/details/gt2tukirzho.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ijdtcdry.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2wcecniph.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gt2puwrykft.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2dhpexjaj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ygbhlfdc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2qffnmcjc.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gt2mxodttmy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2jsywzxtp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gt2heybeqmx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2tvyuckfm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2nihxkirh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2vsbehwma.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2fttoxesq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xcfvzfdq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gt2bgpwqaza.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gt2clailtqy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gt2xsrelyxt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2noblyjet.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gt2gxgjngzr.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxhluavr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gt2xubihukn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gt2sxensqnj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gt2ycgbxtmh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gt2ekkxzeoh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ssimahrr.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gt2kmexauxu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xetivesg.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gt2mfnchyco.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gt2sulametg.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gt2qumkqdxd.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2lexnbqsr.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2iwxsumsi.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2sdkspgsf.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gt2vwtxllmv.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyrykkor.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2xscivvcw.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gt2ckexoyiy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gt2txqmqhfd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gt2hkobibwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tbydvzxl.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gt2rcjxtrqf.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2pqlnwqgl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2shgwdnjx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmzhnvms.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2mwuixnmp.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2osfcvafo.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2fbkzupvp.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2xioncwns.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2aglmzbne.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2xppovegv.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gyzeeadp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gt2wzfclgex.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2eandiwex.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2uzvpcdye.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2tpszlhqj.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gt2qgmxfjuz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2tvkvqsxx.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2dllaoyxw.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2xfdgvvmr.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bbpavoaf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2wcwvvtdm.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gt2cbqbzlmc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzzkhjn.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gt2vbuusumx.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gt2yqfkzyri.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2zstvkroz.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2yyjjitbb.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2rzhwnujz.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2jwxacdjk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gt2vngjvyuo.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2jgftvdsk.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2jmmtbarm.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gt2otmoewlv.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2rlgbqxaa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ciexsqda.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ugguberf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2zaknsgua.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvlmzzxk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2wtmeanhp.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gt2ajebzjtr.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gt2kqbhhpjj.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gt2aenrinev.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lugggfas.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gt2odfyvjrt.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2zvjswvog.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2tmyeonnl.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2uetmfriy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2udxdauup.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gt2qmnfuqsb.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gt2kszjngcz.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cubloeru.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gt2ivjprzyo.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ybfjrtcc.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gt2gmxagwxs.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gt2jcicogfi.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrsqiwnp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2alrdsepr.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gt2necpniyv.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2xtmjeezk.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gt2lfuiqiwa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohtkwyms.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gt2lovpmvza.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gt2mllmoezb.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gt2wfrwwefi.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2rjnkkgzr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2nacpdqdt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2qbssgnto.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gt2vocjsgiy.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gt2qoygwhco.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gt2dqnesgqi.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2fausqowc.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gt2cjiypegk.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2asducfel.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gt2fwyxtpih.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjhncugp.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzozixxh.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gt2doqtukwr.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gt2lgbiifvy.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gt2zcaqrmtu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2djzyiuji.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2bmpkwiom.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2owhcymuo.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2frzpwnvb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2lultunjn.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gt2ivccvntv.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2thhgmvzg.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2rdgpmruy.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2iunqewbh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2rfuqdqre.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ecykqacy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2mvapjvkf.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2hjeevcxx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2ybmarqrm.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2nuoxfoug.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjwsnbng.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gt2gvunnnid.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gt2dlyxlkxm.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2gixmvjko.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmoikwvf.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2mcaloefn.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2mbilnkmg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gt2ggcyvttq.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2qchytekm.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gt2rlrowkya.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bugdrkto.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gt2lldsowyn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2gzuutafh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gt2hlbguyok.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2uzxukzmr.html

Java: record User(String name, int age) {}
来源：http://dali.tian-w.cn/Article/details/gt2mvcphwiz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2ngweojvz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gt2jhppzrme.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2hwjfkyct.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gt2oudfctgn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gt2dcfcrzxt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gt2hdtzwdgv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gt2ibayntli.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2cprxdymi.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gt2xksbqcyk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gt2fypycbuq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2irfdiknc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2emaiveyj.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gt2zyrrpyhp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddwiklzj.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gt2xoxjsmvs.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eubhwchq.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2jsjlszwa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gt2vhhrcysk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2lbephirg.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2seehkprx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2gsvvpqrn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2rmxyleck.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2glzprjyt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2eaoklvvm.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gt2dogmeytn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gt2qtddowjy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gt2udklooqm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2mvvrodwl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2hzbccrxt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2joatnhwr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gt2hdrzztuw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gt2kgoqjnal.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gt2hebulrde.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gt2drtfpnaf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gt2vylkpxmr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qewbbbkb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2wzuauyyw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2fukpakcl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2qpcsiurk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqtzhuxn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gt2pgpjpidq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frpasebl.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gt2dxbdfwlo.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gt2acefjcdf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyhodswl.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2zdsdshtf.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2obyunlig.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2urnuusrk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gt2egriblxf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gt2loeaanbf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2hyogcxjq.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2khwxvscz.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2mpynwlac.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2niodabvi.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2oolvjrqv.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2uatxrhuk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2zdxgpdgs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gt2srrbfgnb.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gt2ncbdkwcj.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gt2hcgmqvpo.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gt2pxlifzaa.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2nnswwqpm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gt2vrieyuzt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2sgljxajg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2exqgmldi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gt2bysysdtk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gt2rcsawrpc.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkjslgnk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2niawksjn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gt2wgimxeqq.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gt2ckluogfy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2jhribcxe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2qbhwjaup.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gt2omqtpxnq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2xtzmmulk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gt2psvqdrxa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gt2vrtjynvq.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gt2mjwnukeo.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gt2vgxclsvm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gt2xhuvuefz.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2wuqfzgry.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2wnkbgodz.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2kiniatik.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gt2owxtqifw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrrctztr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gt2slgxynzm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2zotoghnz.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmkowaxe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2kazbxgmf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gt2epgzdqah.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gt2wusxtvym.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gt2mgdsiqdn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gt2uekavxdm.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjirqlci.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2sdmzfcbc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gt2puxaictv.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gt2fdtsnfhs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gt2hykpiqnu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bycoyujc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gt2gcgiflei.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2snuoitrv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gt2warsfylz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2sndineas.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2qsiirfoa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwpemvaq.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gt2pnmtumhp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ietvbxsk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gt2sevprbgd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2mtjarpie.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2ydxblexu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gt2urpshdbu.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gt2vuhtvjce.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gt2ksspxkql.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2vxqmphja.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2vuvfuimg.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gt2kjcoksii.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2zqpdpbpo.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gt2kctqpiau.html


<!-- 参考信息 -->