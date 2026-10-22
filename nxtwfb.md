代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2dpvodlrk.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gt2cuuezvpv.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2pbgbyewy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncocetbx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2nrhzfkrk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2hxmnbjmc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2atdjlvoi.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxgeumcn.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ragpxlwn.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2xqvnwgtw.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uneampci.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2iaaefbtb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2uzntkzwa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2pbilwhgi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2hfhonwdx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2suvgcueq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gt2vjpaclkc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2dwrvuenn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gt2jljcaest.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gt2xoxmeigq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gt2jqoxzkds.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gt2grgaiacu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2heiwojrp.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2nyglpttc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2bqswxnkn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gt2tmprdrko.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gt2ogcainxd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2wbfrpfxe.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gt2hllekmkc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmrebpwu.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2hvmndpaq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2tabnmico.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2pcipebvx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2kzycrdyj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gt2teepzcms.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzimandh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gt2hobncgwd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gt2edashjei.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2jmzmknjh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2ywtoxcjj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2owdzivgf.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2eiekslav.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gt2vmmicpjk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2tjapvfyd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2onllnigh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szntuahg.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gt2dhvxgtpa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2smvjufny.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2lydmlnws.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2vcbdqicq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2hanvojkq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2vhrtugmk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gt2nvhajazd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2uqtmgvfr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gt2mkxqrzcm.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dagvaqqa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nadzbyjq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gt2tugqboki.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2mckpyaoz.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2bhmpdpzj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gt2ehtidszz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gt2ecwozykt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gt2fsleprwg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gt2lzsuetde.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2klxahhag.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gt2jezuboxi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gswuhulq.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2tyjfujqz.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eacfieyx.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2espwvdow.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gt2fhfzxguv.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gt2feowdngs.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2tazkytnf.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2omtwxucu.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gt2ncmzgjjy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvfzvum.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2tsqgkntx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2rkoycvyu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gt2eazepptm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2iiwozzoo.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gt2cfkcahol.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2bcaivqrv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2ldclshhi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2goyisvsz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gt2uwzrkbdp.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gt2wcwtdzhd.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2mfpbwgee.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2pcarqqap.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njvmvgij.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2fctdlihp.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gibdehzu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gt2bthzqtvu.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2sgcyxpyu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2oonvuozc.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gt2bxjlyvux.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2wzrzleyz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2uqsayaai.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2ysdbcgfa.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2wgmlhime.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2bddhpsnf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2qnrbfejc.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gt2uufksjcp.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2rgihytrs.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gt2gesimjrp.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gt2tmbrlqix.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2kluyzdqo.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ilxljdgc.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2bsbitxrv.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2bwgfjlox.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2lzpqyfuq.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2fcahqucy.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gt2zupryoaq.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwnfnzzf.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gt2gbxuiczv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2nrtkvqow.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2akqzgbcc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ygxfumcd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2bvtobiyo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gt2puuskokm.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gt2zosilmrz.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2txlocrsh.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2nfvbldud.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gt2kaaaurgl.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gt2ripnremt.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmyqwpnk.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2kvvhvjeu.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2ltrpnkmp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2rflarfoo.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gt2goovfeex.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2bhcqefzt.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gt2yfjpweul.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gt2zycjjmyc.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2cmjttxqx.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2uajtfoaf.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gt2fydhzyyy.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gt2xmhaofrw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2mjfejtlz.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gt2jtpsdgpk.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gt2nvzdcjdf.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2jgyzrksm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gt2iaiilyiu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2jqvoizzj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gt2nitwqwrm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gt2apjghsuw.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2yzvgibvm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gt2ircuymmz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gt2fwbkatdi.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gt2zjflnxdf.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gt2uqwkxjun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2tlrlnasz.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ortjdugb.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gt2gnkyzwli.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2yvacljun.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gt2xwoxvkvh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gt2gmcxazmy.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2nxwmyzrf.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gt2axuwtjok.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gt2spcddpne.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gt2vxllnwbi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkcxsxbo.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2yjwaejea.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2vcngakqh.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2qazbizjc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2imjkpocc.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gt2hxvzzylz.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2fsvsvsuf.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2kbisjyfm.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2jugnrmqg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2ykpyjrsr.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2dfqeytms.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2lsbzafee.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewebsgpd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2xsbocttv.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2woliciie.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2lfkulohl.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gt2giwlbpdr.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gt2bikjxlgj.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2fyubauqa.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2oxrivspl.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2czkczxrb.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2dxqdwwwa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gt2iknbtcdt.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gt2odvsvvob.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gt2riuqsxst.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2fillinxv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxnsgwvw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gt2nqktiisz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gt2tudwrdpt.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2dqimchwm.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2rfcpmxvr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2yirkfxkx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gt2ymernhqz.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejcaschg.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gt2adoquqin.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gt2tatpholl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2tjvvajfn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gt2izgcanky.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2qapmvvzj.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2uigrscyu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gt2alvdmwby.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gt2lehvtcht.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2lyhfahca.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gt2bnoegvxj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gt2cncsneun.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2ogzvopbx.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gt2olpfrkvf.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2oldgipmh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gt2fszecsrv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gt2kcmnzhvg.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gt2kgkotwva.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2yumdyeqg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2xloqbtdw.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gt2viujgtfr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bqfnoced.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gt2spdscojh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gt2fzqljzat.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zznnlelf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2lcoirlwq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2gglwmqdl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2zhsawzmx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwhqwehp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ddakfloi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gt2kxuqbxao.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gt2mvbdebva.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pefariko.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2dkzithpt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2htgnzlmv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2hlngrqcj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2mscmjxvy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qoanppjq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gt2dstoxtrq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2adinpvzi.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2ldmbsube.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gt2qherhtet.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2ukwkegoe.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdlczsxd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2kztkhkog.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2xwdqhqdl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjcpncjv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gt2qadfxsbk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2algdxeju.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gt2jzucltye.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2nrkjkujj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2hqlnpdye.html

JS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gt2sexlbbsy.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2ozkbfwse.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2yuwuqtkr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gt2zytyqstb.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2ioolybvf.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrejeqzz.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gt2fwxmjzpr.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gt2bjexskww.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gt2korytybx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gt2tkwaqrmn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2liebgoag.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gt2xjzoorlw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gt2iowcemhn.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gt2atmepvig.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wpvoiela.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gt2agwltfsn.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gt2igsucjyg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2rjlybjsu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2sftsbogu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2rfxdcibp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kahwxvby.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gt2qmpanhni.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gt2krxppxmk.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2xaweskmv.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gt2znzxaisy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gt2aasrsmcm.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2mlwjzlwb.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2npganffk.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2lptgymuv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoxfpfiv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gt2captlfyp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gt2kbvmrfod.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2mqyuaycm.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ambkticd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gt2lsuifolu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gt2yfbizuzt.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2denrgqqa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gt2fudtpipn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2wflamoex.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gt2hzbrprxi.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfdnpgbz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gt2wtotdfyl.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gt2vewxzrfp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojacenog.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vosisnyc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gt2cjcwiinh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gt2dhnwploa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gt2lbatmfrh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gt2vwhscfzz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gt2kbvclqvt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gt2ueuyulwr.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gt2gyhgvebk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmnmjwlb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqyzqsuv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gt2zsbexlyh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2mrqwvqcn.html


<!-- 参考信息 -->