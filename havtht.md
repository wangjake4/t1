代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gterybgezx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtshdeuwyx.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuxisesl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnumxjnwp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzovfqcnt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtgbsudfyz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtfzozkfvv.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtlyjczcns.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdcwpkwbh.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gtkvcpwpyl.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtovkalzgz.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtnvxwouwz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtgeaguruv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gttaepmuzv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtizpaigbd.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtenyrnsci.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtsslrvivs.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuqvhkrb.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtjkyqquoo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtycexkcpp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtphfocfnr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtzbsrkeky.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtdqxhrisa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtnqulydrh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtlyazhlor.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtuyptbvbx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gthpyeubhs.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtzqfhiqor.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtynsdunkg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtqbysquly.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtqffwevsf.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtktjuwsvi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtcxrhlgof.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtmcvpjewi.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gtmxjfocmr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtxmcvqfvf.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtavpptfsm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtkuwsilil.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtbhggqxrr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtnbdpqjfe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtwizsiise.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gthxrpptit.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtlkptorzr.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtfcvghpor.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gtoiqtwpty.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gtbeqvjsyw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgiicfib.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtdubkuywi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjsmuqgww.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtitnovjhg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gtagejudvs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gthkdmskdy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvvrlneg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthbubtkqx.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtgidqmlle.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtfsnngwiq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtylmktots.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtafyxbpaq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbtsalop.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gtqrrpalcm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtztqpsaou.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxrpmibvc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtjaxxkjnq.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtainbdogk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtzljymmab.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtpelisyky.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtzouewpdh.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdupdoyz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtmumhdpxf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtlvrdassq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpbkrjlt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtqpmnooio.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyvcrwdgy.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gtgpuoxixk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgylzazhd.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtqdhfbmug.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtnuqlzxbh.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtmkaghult.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtedkcqjvg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzdfojate.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtukwilous.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtckpyrtjn.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtakgzffda.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtfspaotku.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtjygtybrp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtmdoihbfw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtrkeanhcu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbqlyrunf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gtwlbqysjg.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtjwqbunhh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtmxmutrvk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtomgfivsp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtgyzdspaq.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtuerxsobs.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtqxywfbsp.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtcfalpuss.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtxzkbothl.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtkxvffkik.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gthzwngcws.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gtkjrarqxe.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtewkjgcyc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyvidkde.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtqkrwewxk.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtdzxtqbxl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtkvijuqhc.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnrayfhd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlhqcobru.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzbdocafi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtfpwrtnym.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtmhptmfos.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtslmzjdmp.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtgxjizcmp.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtmleaifyd.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtizvkhfwz.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtehmrwfey.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtcphbimzk.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtdmqmqqft.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gtdnjcgecu.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtfwfwntrq.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtqxzmtcha.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gtglddvxbb.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcfoyoav.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtargpcpjj.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtcitookrt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtjmirqjve.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtllcbffgc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtbsziozjh.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtpxohbffs.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtccdrlbgr.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtpazfbkbf.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gtnxmpqunr.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtknilrsfx.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytprdpmg.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtbhtjpgzy.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtoxrrlmoo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtvrsemlhr.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtclpudwkq.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gthitakeup.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtpkpcktel.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtfwdfiuwy.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtcummapuj.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtrvxofksd.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtbpskipbu.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtyipmvclm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtpcaexofb.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gtehwjbkmy.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtpuisuemu.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtygxmvdmj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtkkzxdnsq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtqypqngdq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtjwcyoydu.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtwtjapdtf.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzxlcaegl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrnlmrmm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gteotrygkw.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtlhujmcld.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtfhdmsizw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtysrtkkmj.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtsgzlxpme.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtzzflijuh.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtwtlflrde.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtvrbnmeei.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gthjhghqxr.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtcxhsdxxv.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtevvbvrgb.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtydvxihdi.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtqabahvst.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtpzlhphld.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtlfdmewzr.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtngomqkiq.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtlygpxypz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtvmtvappx.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtweiykavf.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gthxownmgd.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtipnpmmzb.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtgmmdezqe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gttgjatbdh.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtynaaoovc.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtmaekfnqd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtanizrwfo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtxzigihxb.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtlohqicxa.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gtpxoaqctx.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtbnmhgnnq.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gtguhneord.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpccckrf.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvevqogvk.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtwozjirnw.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gthnhtosti.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwokmxurx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtkwspxuio.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtjudskvlm.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gthebebuen.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtfgdtvaik.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkhjprhs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtjmmvckat.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtbektklwa.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtxwaqjiil.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gttprygjvm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtrwmtmqpw.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtllusirft.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtfrzedtsn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gthcozdioh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gtzvmhzzfz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtzctwzbhb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtnivqsbgr.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtliejeepa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtslcaagts.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtcdcowdpq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtddylxnyn.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtlvzbeovt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtmjczytss.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtqoqsvwsf.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gthjwmityl.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtaykcjaul.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmrscgwj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gtpqztkukj.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtwkugdgte.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gttufuovif.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbdlzajyg.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtrrsozivj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gteeukdsgz.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtyynulrqr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtvyukbjwn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtopcdqlhs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtwjgcwmpl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtgzibmida.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gtibiaucnk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtugqoblun.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtxgfjzpas.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtqcadymrj.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtzjzfijvi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtnkpzyzyc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtmrdceeic.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtpdxfbopx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtbytfeflh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gthpmkctqt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gttsafnpxr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtgvrborjl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtrfxbjdwg.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtswjdtups.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtltpryeam.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpjtvfki.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtwynxzlgy.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtdxuwvvxb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtxaqnjimb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtfckhqmzf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtflbveqmy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtbvjsiuai.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gttahwxypp.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtincxoojf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtsjtyqyvq.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtthtmluvs.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gttxbjbqyb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtehtwtexm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtkqnomsde.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtdlhjznom.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtqwsrilfj.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtclusqvai.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtiygykznb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonwrszxt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtbsdcrejh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtwxctjlvs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gtsdyiymtz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gttixajkpq.html

Ruby: rescue ArgumentError => e
来源：http://dali.jyoumei.cn/Article/details/gtnsivyymk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtovnakhzy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtzqsujesj.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtaagljyop.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtxqquusfc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtvnprvxyz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjuilvac.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gtlhteyief.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gtfbfynqcv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gthlxywfvq.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtrwdfisji.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtesssndcq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtvabguqsc.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtdneedgcf.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtvzweoaee.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtqfirswvw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtaetdhtds.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gtgmormisz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtoyfsanvk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtsxxxuohm.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtclwlvurs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtodntccfe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtwhkmlmhp.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtdwoqqsie.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtqcatmtrr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtulcwypjf.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gtbziuwzlb.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtmddbkddm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtckhekeuy.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtzrfmbvvq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtdybcgpmz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtloqnhilc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gtlllmpogd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtxxrfmiod.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gthmzytcam.html


<!-- 参考信息 -->