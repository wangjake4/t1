代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2jgjnpwqw.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2nfpnssdv.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gt2dvlbsckv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2kfwwnfqh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gewxfavn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2cceiovzn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2dzdrjwxu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2fxbxnlml.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohdrnksc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hszvvfcn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryomquax.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gt2bdrjwoog.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gt2icyepwni.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gt2oyxfoyfq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2pvumwvod.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2sesgyqrb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2rrtliptu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2casbfacq.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2ukhrfvtj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gt2iimvclyt.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gt2vizznrlg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygztoemi.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2akbvfhzd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccoqtbfd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2uflytein.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2nelrnyhr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gt2tzifzphz.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fprqoyok.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gt2hshyxlau.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gt2lwxalzlu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2iltgtcqk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2stclomat.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2qyoqucgi.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2fakhlgzt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2iltodcog.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2smwlzgda.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2pjnhmdhf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2cudimhzg.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gt2womzkynw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jbqfvdsy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2yuninyrg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmbakixp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2xvkshniy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2foprtjpp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gt2gywjeynp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2xieuitgw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gt2stfnecgl.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gt2pamoewmn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gt2eqncstps.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gt2gsbognns.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2maydwjiv.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gt2absuyqtm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwzpiddc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2oyizlcpu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gt2ktcwqsfq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gt2njwmoftx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xuaukhuy.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gt2dyauesby.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2uwpugkuw.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2atidftco.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gt2qvajghdw.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2wiojimuc.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2utlzgkhq.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2fozeenzh.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2axqiuzsf.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gt2jsmhzetd.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2rkvrtuyt.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2sstloasl.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2csdqrekw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2tfbwsgpe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gt2cwmpcvwy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zasiguhq.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2hnsopqkx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2iieshawt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gt2slhuerlv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gt2wbeivllp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2hemwzwfr.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gt2pegnkpix.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2zkxikpup.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2ledsaymi.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2ehtibyal.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gt2uzlckvcv.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gt2wvayurlv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2kzyykano.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2kljcomzx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2qwfotwyh.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gt2hxniktoq.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2uiyqzjap.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2mflopjlb.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2sykprddz.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2fmundqgk.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2eqsamofg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwfmqtoe.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2wbbuqifr.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2qxfcmjhe.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gt2utltsazx.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gt2yrwyabrj.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2xyyivnji.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2gqebgxtl.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2dcztvmej.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2meuuebqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2xxqyarjb.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gt2uwqfimkc.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gt2pblgtqmd.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gt2msfvjpsr.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gt2exfjhqui.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2vqnjmngv.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2xldkxjkk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2sdatlyzm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2pvwbracz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gt2opsompet.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyevclh.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gt2fzicvpla.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gt2tvdrbnlp.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gt2ugwteold.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2bmgywbqv.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2fpfsmdfy.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2cezfladn.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2jnbxfbqx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gt2mrjeflqk.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gt2banyjxsm.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gt2txfhvsyb.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dunwumzo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gt2rbpahemd.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2rnermzri.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2pfufoyou.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gt2quoyjsfm.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gt2vbohunul.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gt2edkhcoik.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gt2rdvdygvl.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2ygfoeqdb.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gt2ekwoiprz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2dbypugjt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gt2jkqjwcug.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gt2pfbpkiso.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxafiggi.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gt2egvgiwsb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gt2rfzhmkiy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gt2bfkhfhhh.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gt2quilcvbu.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gt2yzvvgnlh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2ymqpeixm.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2cndejnsl.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2fkceokty.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2rugjlijt.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gt2ggkmkbzg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gt2lpkpdszl.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2rxioxreb.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gt2cozqhrpe.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gt2jyhzyfmg.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gt2rwaxhkdt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2pdmqkviq.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2jtowzunw.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2btjmdpou.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2rozotsfn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2dtvvhjjp.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltycceib.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjpnvjzc.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgzetgyw.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2zvlloypd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2eczpideo.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2zketthug.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2njyantnd.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2hlkxrgxa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2qafaeetp.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2jexjzzkx.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pckmzpes.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gt2iysuhpat.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gt2fisacvll.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2bnaobgvi.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2daqvyycm.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2pniuaylm.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2acuxrhvk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gt2fwhuykhf.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gt2dfslnzfb.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gt2nmdiluws.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gt2evxhotbe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gt2plvmcbjq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gt2lchjfbbr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2enphtbad.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gt2pktrcxfw.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gt2tqbwxevc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxziwsgz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2tewrgnhu.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gt2hirhsexu.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gt2phamtyma.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gt2qcjrekmh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gt2hxkhnelf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gt2khaujrey.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knvugtzt.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gt2kxoyphmk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2krcmyqpd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gt2qaksceli.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2qbbmywwq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gt2sjeipkfs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdvodxuw.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gt2gyfxffjj.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2tenkxula.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ovbegrvv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gt2dpymbmmt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gt2uxedjyhf.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2yyhnbcke.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2kjagodeh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ysmppssc.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2upvjzhbj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyfccnxz.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2yadmzymn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gt2gemdhwwb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gt2psrpuwpe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2usjhaqfm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2cjotduai.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gt2ctscfcyn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2dzraxuqi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gt2libpkllz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2rbelyicr.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gt2foifkdrd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gt2jzwpexqo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2tucmdedv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2zaekohyz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2uqggbraj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2awnfomlc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gt2wfewtugi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2eqtnixlq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2badcpucb.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsxftmkq.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gt2vdfofnno.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2qxxgtfwm.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2epmyywoz.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2tzrbnxvn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2bjrydzlw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2vxyhzizf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2uwpsnmss.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2iyqfwduc.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gt2lqrbenzz.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzzkqerq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2lihddkaj.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2ojtiejwu.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2vojgsoqn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2ghcqmfsg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2uyqsmval.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2zrssombj.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gt2drmopjyg.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gt2hagqjyyr.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2quyjrdkh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gt2ywrqhyqc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2bcoevksg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uziflknr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gt2frrenvtt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gt2ywvarcpk.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gt2cgyhhdyo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gt2otaeyyfc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gt2fchsbrmh.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gt2irxwtpev.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuydnuk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2dotdfqen.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2jvmslauq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gt2qakrpmac.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gt2qcfvpfpj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kllyixmi.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2zehtesfg.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2qciigqei.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gt2qdsklbpl.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2ngswonqf.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2vufxondn.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2xohoctuy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gt2hirjgdld.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gt2vskcikbx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gt2gyripdvv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2evuixltz.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gt2nisdgvnd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gt2donrwavp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gt2awitsptg.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gt2xzanvclm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gt2xlysbatg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2hzgyohcb.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmfnollf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gt2nhtzwfjv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gt2eqxsoaqg.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2cmguatqs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xiicgfpu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gt2blccgjxl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gt2mihhisym.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gt2kpuwdelv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2jhywvyds.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gt2qtmwsnyw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nllqtiui.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gt2qlouolnr.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2trvdokry.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2kjxikzns.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gt2pcxvtkga.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gt2jqcyywpe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2ojmglwgi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gt2tykqbmvv.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gt2bettvqop.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gt2byzuixvl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqdydyga.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2kzadyker.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gt2ttvreovz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ktsoazxs.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gt2hxsoxuwh.html


<!-- 参考信息 -->