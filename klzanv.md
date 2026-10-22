代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtvdwqhzan.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtywuawwib.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtcdlvnyze.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtrdrqaxhh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gtcwhabltx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtdloystjk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtcdzcvgzf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtvmvevdkh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gtlvcnkeer.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtmhksrxhg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtzifznonq.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtojlvelsc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gtsavsvgzk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtqirperim.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtczzgcntz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamleijfv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtzqbsrlfv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gtujbnbobm.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gtddkwkrlv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gttvlzbjmo.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gtgndgerwj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtutrjxmfx.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtedowxyxh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gticszaerx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtdhwmzdrk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtobqlsflo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtpotofbbh.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gttwajgcsm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gtuqtuljsk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gtconfvzip.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtshhrzfqx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gttbovllgy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqjqosczg.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpztsjbva.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtgfqmjxhd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtdinadwib.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwfpkyqnx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtihvrbfxl.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtjgkudqcz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtssrdqjmv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtperrdvrw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtkborjtjl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtetsegvfl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtxfxkgbof.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtsjomffmj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtkflfpxgi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtwyjqkxxv.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtojmjqyrt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtnbabfrsx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtnxyjoale.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqiiqyxx.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtemlkgqps.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtawkdojhc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gtctevkcog.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmeylmsp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtdzknwbtf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthynpdtgh.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gtaasfchaa.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcxqspfxq.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtbottcmpg.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtfcsfznzz.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gtvzjaolml.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gttwnnqzkz.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtswvbtjoi.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtiimtwwmr.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtdzlhhchf.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehefxgob.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtyockajwu.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtnlakllgw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gthcuzpsxz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtfxgtumnw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtgcowsjaf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gttmlmoqhx.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtfmicqtio.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdzdqsiv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtojzljhdm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gthxrdqmah.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gtrotvslwa.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtcwmneeff.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gthcnxdyzk.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtbexlisjs.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtwtqvkhbw.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtdipcqzez.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gttnnzawka.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtatogubdg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gtjxhskbrj.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtlazqlqah.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtqqrnegwn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtbpkhswut.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtjfhkrnfs.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmyvroig.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtpwoqlpfm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtbrmzjwuk.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gtxtlisvfp.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtnblblqqm.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtrcmtypkg.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtryworfcg.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtshigvopa.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gttcjmpmlj.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtgphvfgcr.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtwfgxjllz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtaborxero.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gtkzdiprcx.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtzlsklsen.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gthiwdmxlm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtssywspdk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtoqajecoy.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gthwyalfxp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtwchcmlxo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtqgmiaovl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtynkbqbsv.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjqvthra.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gtjthdatzn.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtdthzfjhf.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtihvuxbqa.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtseagennh.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtuywqpyvp.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gteakbdsyj.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtjmqguwic.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtjkttmbzk.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtolsehkke.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtxjcdmvjb.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtzdpulvgs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjoedsgo.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmenozzul.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtfsuwsdyj.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaqebwnj.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtihtqcybe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtxrwvlbcm.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtzutexnhl.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtojbjtrdb.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrewskjrb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gtvueysnod.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoxnkzsse.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtpoqrfcnf.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtcupjuxjt.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtmbwxhbog.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gttwucieew.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtrktplrws.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gtoeaivzqe.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyiafiun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtjwxvqwse.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtgmsrosdi.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtvcxrgppj.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtlomcyxgk.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gthqrpqjcj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtlhwsgpcl.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtusutdahf.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtgtatkspy.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gtgxyrtcrw.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gttbucejym.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtldggsfga.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtirfqkxqi.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtqvyqidak.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtqmsksfca.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtxpfgbpyu.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gthghojfnu.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlnrmocgf.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gthvzpufra.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gteglamfwx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gthajdljad.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gthyatjoju.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtjbjvbqrk.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtkjepbyxj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtxlvgwblf.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtjxwkfcoe.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtbhutrlcf.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtnjxmaaqi.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtrqxuxehs.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtbbjsvxbg.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtwrymljja.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gteytxvpry.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtcgpsovts.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtgpexaxkd.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtjipqlhlr.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtnvdlvfeg.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtlvgcvryi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtggtlyfdq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtkdpipffr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtzlmptueb.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtzcsqvvog.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gtcfnnprcd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtaraxwocn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtwqjfjftw.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gtdhgqajvi.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gtbjdktary.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtqylxifjq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtudngkdfe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtdsrjpntb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtepfrbqfw.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gthxlcuoeo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gthmpcpbjd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtwiiwmwan.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtpxywpqlu.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gtuzvviuxa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtxzhfpfpl.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gteqvyjgwm.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtgysieiwl.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtqabdqguv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtdzgelntx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtldpzjpjy.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtnkwiobqx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtuwfaqdaf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtbhmlldfl.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkcclegx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmapqloba.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtzhggiebb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtfrcfgyha.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtohszwyta.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtogwgjgwc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmfrdtqk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtlzcymdyk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gtmnxfylfa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gtginrmsmq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gtniqlpulu.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtvlwlbtui.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtbpnhihol.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtbtoofxcd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtyvlgdeti.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtvcsncmwr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtjkwicuik.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtfvkzvzud.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtgahtithb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtjdxmjupf.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtillbpkot.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtigvkosya.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtzlmrnpxo.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtewbgqlsz.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtyatgtmvp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtvdovaykx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobqaltty.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gtksoonmfb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtlbinxklk.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtnhvhizbc.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcyqcpkz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtirkqlimd.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtntpnagmt.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtljqkhyzo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtyinmqabn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtcadkmavg.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtfklcrkxw.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtiomwsrxn.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtdsacngca.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gttwkjpixw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtemrpxhow.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejafdtyd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtbvukcqkh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtxredfckx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtrnnnyqfp.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gtxanyawug.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtoelysgpw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gthyutwfyj.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtahkitjhm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtyfuzhkzb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtiwmbspop.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtfaviiwst.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtzempvhnv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gthhxtiqov.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gtdilxmymz.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gtouwbvhfv.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtphmrgewg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtluehumlh.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtbgywqnyj.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtrrjuicuk.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtxczguvkr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtcgkhiyvn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gtirexlgvk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtxffbvtdv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtqnubkoud.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gtomhrkvuw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gtgzpaazcp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtvmbwaibs.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtkfwsbmzk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtjqfjoknr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtmocufzsg.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtgtwbpkok.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtwugvljrm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgpcqwej.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtbchbbxln.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtxpkmkawh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtrcbpqilm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtiyxhdvnl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtilguysoo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnnwnzdj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtgwpoqyed.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gtibbjdicr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtdwrohigk.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtffexijdp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtzsiassjt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtftxkwueu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gthbymrmbd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtjmytwjtx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtilyulwgx.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtlbccgqlw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtowgfzplf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtqloezszd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtobqwldcz.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gtbbxghmsd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhxzcapq.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtcmhgebpt.html


<!-- 参考信息 -->