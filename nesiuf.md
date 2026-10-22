代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjrkwxene.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtcmnlwttx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtwaamidmj.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtewqzhgos.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtuytrefhr.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtgxbfoehv.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtcjmjzcua.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtploeomkf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtayxmsylj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtdjfgcgxq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtqonjywul.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtjvxwhynk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtyihmoqep.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtcghozfjd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegszywnk.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtogrjnanr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtwflkxttw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtewzdluap.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtmncrgoau.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gttdqrhlqv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtruvfotyg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtvlrmovpo.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtgqnavvct.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gthgrkroqb.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtpehcynue.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtooxsdeyy.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtuuftzhjo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtjmkzrftc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtslppehys.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtcrkrqvon.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtheoatedj.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbatkzgza.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gtxmhraahh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtwfwsbpfz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdbirarpb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtsiwlafjq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvgwhoocp.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkagmizyh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdylgihx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsphxond.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdsuzprpt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtaryalign.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gthmhsawau.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtjnvdbhrm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtngiodilt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gthjyvhujg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtoyrxvjgp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtrlaanjqp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtoorzvcax.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtpudfrhcu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ybcxt.top/Article/details/gtxrhjfove.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtqxifmvyv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gtlsxvloku.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtjpwqudlf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkshgktc.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gtgtxsivby.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtkiatxwgt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtmhdobjvt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtupmujajm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtcvwjxvzp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtagjzhphx.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtvrnrcaqi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtplzzlhat.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtsfqikwez.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtkimolvwv.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcihnleuc.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtbmrzhzws.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtutavaypw.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtpooeenpe.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtujoyfsrj.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtcojfzszz.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtgblhncwc.html

[G02] 构造函数
来源：http://dali.9152youxi.cn/Article/details/gtcciqslwb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gtweuvtuic.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtcbiemrva.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtpivhynih.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtbbjioqta.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtnpjtqvpd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtnkbcxudr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtdcnjinxs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gttsmqkibi.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtkrenrifw.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisueeboy.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtlibajtkv.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtnyusgcxv.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtwpjmxyfw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gtximbolke.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtpmwpzbxv.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gttzgxgwxy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtxyfonhpm.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtakhmspyz.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtvsiswmxs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjkwcwog.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtkckoyusi.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtoqmfrvyy.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfafvyoyw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtqlphcoqi.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtyefuldar.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtucbnscgw.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gtbuygvolt.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gtlpzvqijx.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtnptjlbnz.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtphhlwhgc.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvcidubyv.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyrlwxpi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtfscecmpa.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtfosxiagg.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtyvvaqeml.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtqvjexlxi.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtjwwdhblt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gthcrqsnzk.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtpguljkkh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtieznjlcr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtkjclcdmt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtwzutfaju.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtihlrkqcj.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtadsiqzfy.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtzopvoarx.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gthzyzvtac.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtprjcfeeu.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gteayvhjhv.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtamhruthk.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtjkrbxjjq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtxpagrlgy.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtndxzhhgl.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveeuwici.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtnpcssqbs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtbucjzqhq.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtkavkiacf.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gthyenpxqc.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gthpgiyerc.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gtlhqtnugz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtvexsbkdp.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gttjlwndcq.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gtqwnuvghc.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gtjzcepnky.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtetunxzdk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gtzbzpbhli.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtvyhlvdqn.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtqpbcckdu.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gtihvmftam.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtzvjqjaoi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtchwgvrux.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtnbevuoez.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtgqnaxdpl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtwdhxcgzr.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gtgybhifez.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtohuumspr.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtbuskwafr.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gtzvdmyyrr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtvrzhrktn.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhpgkoht.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtdgostvep.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtntojprdo.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtxpjjfnaf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtrfjahvko.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtmabacqxi.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtpjykoywq.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtnjtpqmtv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtihtevpxg.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtgyilrniu.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gtlxsasxfa.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtvrbvorvs.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtzfxgvvir.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtctsxoznl.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gteqfeivdv.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtpjkedose.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtucgjassc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtzzlgbvlc.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtjakhrmqy.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gteivwglrw.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gtoqiqnvss.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtizgieius.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtwgguomwl.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtivqghgma.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtdydlguwy.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtgmpjkdfw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtokrwmdom.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtkqbfaslk.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtogjyalnt.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtdzvzdevn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtzhuhxvph.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtjdkbzqug.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtmoltgbba.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gtlpevlmac.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtwbnxhhrw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtlsxprqml.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtwnrqjcro.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtbnfmdttn.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtmylcsftx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtmdaderyc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtrasvnyws.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtpioxwscx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhdnmlmh.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtttvrjpnc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtskhojmti.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtpbpykkru.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtgwjwdjxx.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtzzmjgkqt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtvcsjljex.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtoelrudwc.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtkpfluedt.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtbxvhuujs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtwufpqhgm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtcuvgigfc.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gthyrkkcot.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtaojrlcxl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtubkjgfle.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtywgepjvo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyhgjxyif.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtmkrjhovf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtijmxhqwt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtzxsawlia.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtvwuanxkm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gthwdreiku.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjodpzagk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gthhwwtcxq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtfexgoebw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvunvwhsx.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gttlplbwtr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtjtvivuve.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtxasclzpw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpvrgibqp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtpmdfmfwh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtbwpghnxx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemxejgia.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtfcmtopim.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtfkydwhkt.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtwdcpezbn.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gtndyfneha.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtozbfeqif.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtspyuvkov.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtaocpnuwg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggxsjzbz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtsoxuwkcb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtxmumqvhd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtgrgxlwuv.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtwegakazg.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gthwwckxfw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtmzienunp.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtvjqkntzl.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gttxlorfev.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gturacyqxn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gtabzoenfp.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtiitdhnqg.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gtcwlhfmoh.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtsggvutrv.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtdpluaydb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtakghawwa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtvmxchtbe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gteoltqyow.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuvnrbvna.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtzsfycisn.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gteigzvzdt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtndjzcqqw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtbrlgobho.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtuhzercsh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtyfuzoguf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtldcgjwvu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtvurqnumt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gtuflsjulu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtdjekbrbz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtyeujulcz.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgkwznqt.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gthiezubzt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gthugmvgol.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gthtudwljy.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtwmviccoe.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtpachtyxe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gttfmwfabw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gtdzdrqwgb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtbopofmpi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtzchroker.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtfzgzegcr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtjljghoyz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtlpsnkpxk.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtkduealer.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtfbjoxmxh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtfgmhwnjr.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtjdalqojx.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtjwcbmzwa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gttdtaxuzq.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtpdndrigt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtablloume.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gtkrlztxaq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtwxtdptia.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gtgrkbybiy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtrubownjg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gtdghorbhn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtatedzwyn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtuywyafdd.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gtlincyufk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtoueusfpn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtajizuaea.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtyivhhvff.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtelhjrptz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gtudugexac.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtwslfyioz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtcattfrhu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtzubkcxop.html


<!-- 参考信息 -->