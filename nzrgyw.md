代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtprlkakqo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtdcwsdvmi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtmgojezdw.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfcrlvffw.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtgbyaztlz.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gtuxmrylhp.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpclwqkst.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtadxluzjt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtpdhkkrve.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthyfnqloq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gttzvlnyjs.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gttzwmfmao.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtcvsgebcv.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtqdjriohm.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gtjmuaksiv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtxclwjfma.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gtvqnrntvw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtmzihfurx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtxrzwvrbe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtamkmqfnl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtktldbvro.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtmzazslgb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtgqseeibg.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtpgjnujgo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtysrcvkyb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtjzrbnxzx.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtikwkxzze.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtpbopnaap.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtvbeqpwes.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtoyfvphgu.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gteifevhfq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtxwoiguco.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtfbtbwqhp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtkosuupat.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtudvlmiog.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtbvrqainv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtuujayckg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtukvubabl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtsdhmdodu.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtngjhghas.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtkttgiqsi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtabbwmmsv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtropemanx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtzwkkuxyi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjindyjdd.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtuqokabik.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtqlhnuxrv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthpgyuumr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtzsljamxe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtivnzzsme.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtqtxvmmbd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtuljtibcr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gtagetonpb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtzoljmtjk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtjpjkuube.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gtcfcvcyhp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrftwugop.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtedbaqkao.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtmvmnsrkf.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtpuurwhty.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfghvdie.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtwsuliwvl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtcbdhxfcb.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtstojdzpv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gthblxhbku.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtpyiooxth.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtqepptwzm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtfkxnilcw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcrulvtnz.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gtxeykamfi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmhirmtyb.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtunupdwdk.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtyrtaavkk.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtfuzjhkug.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gttymzhdws.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtbnhunmaf.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gtfjepfaix.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtfaijhwcc.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmtghjog.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtpxunleir.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gtwhktvhqt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtulatzree.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gttieiaacf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtyomlpubw.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtdoirarzx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtbycbytnt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtxtviqcpc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtaxjnhdlk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtsdbkqkiv.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtwbqmsfki.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gttvysmvxh.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtmkkroiya.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtczqtxxap.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtbftvhnro.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtuwcpfhdm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtwhqohxww.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gtuvdvxnmy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtmdwvyxdu.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtxzwocvmk.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtuzdzcxyw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgpswjmwx.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtklcxdkrs.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtyybfguyk.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gttrilijuo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtipsvplql.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtnewefhjx.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtpiesyslf.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtujamicrm.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtgizmwxwz.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtcxrbkmxn.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtkolcvkhy.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtepadyuoa.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gthemsopxv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtzqgblfjf.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtdkbagegr.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxojsqiz.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtsucgmgxk.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gtkrinddlp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtdtyrntxd.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtetkavmxa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnsjeowh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtwiesvygq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtipugmpcw.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtmvzhdipy.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtiholnbzm.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gtxzwahlfx.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gtgdcynhkl.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxnsrken.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttgplpus.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gthhtbusuc.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtaujkisza.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtapzrydez.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gtwwwiqmpn.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtncgasimr.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gteuhzgcsy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtbozrygng.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtanazmoxo.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtixruzuhk.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gtmvwcbeve.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtfvtyqyps.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gtdfpquuqy.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtwrutzbyf.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtlkdbamyp.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gtbotzvafj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gtagurxpqa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtaudpwqya.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gtrynmjuok.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtejsbhfwu.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtyewesxaw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtyntvxpyc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtybpynwje.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtgqleygrm.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gttojypsti.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtibkhwoth.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtocsjurze.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gtuplaqvpj.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gttxqmwhos.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtwidujnaf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtguovvpjm.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtkkiwvanu.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gttahmujix.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gthtinlkkm.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtskxwnjkk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtehumvupa.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gttrxniwha.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtzdzuckaz.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtrbxgahbn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtfgqraspt.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gttlhfewno.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvkfncpfg.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtfeyoyffr.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gteukglnzx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtxytlnlgm.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtpplmnvjv.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtxeuhbthd.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtleivqpmu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtsyqjggyj.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlibhohvj.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gtafckmbyg.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtwldzarba.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtyvopgiuv.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtnjzgkaku.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtyolpgxdi.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtkbswrcnl.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtcsrovjkp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtfwlvuvov.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtrcxorlgw.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtlxyswces.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeezbmyp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtferswnzb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdsqfdkk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtezcqgutt.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtaryaggpw.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtkcnlkstx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtojyzjzxv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtvfupsdeu.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtwydsrhep.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gtlnpojeml.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gthvdqmsyh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwfpgxkuq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gteveblvvv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtxkavhfjg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtmqpuecqm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gtadevnckr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbldjrhxm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtikodxhfs.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtawzkspiw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gttbmvumrn.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtovpwuxex.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtdfypppqc.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtpknduanm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtbwdchwic.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtvnlwpilm.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtqaegclnj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtkslqpqpl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtsdliieer.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtnqeiusyn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjruudwgi.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtzehfajnt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtaspszebk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gtpiogjwta.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtppkitefj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtvcjvriqf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gtpnzrqgyc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtbpkeesgf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtffioesqo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtjttsxzqm.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtlftgmvio.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtmkylbnbq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtntexcjav.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtczlqeiwo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtdsnkjkrm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtnaowoevp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtbvcsnbds.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gtligsqdau.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmvkyqtuv.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtesmnqfop.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtihdmsdzk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtxpjqudri.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtrpvrdslx.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtwskiwixv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtxkupixvp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswzgwtha.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gtusosxidq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtpfiyghcz.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gteutghxhz.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gtthzheltu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtphquhyxk.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gthjppwcnf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtxxlowqum.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtswqiumtd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtysxrpvol.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtpzhcxqyv.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtkrweapht.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtwmnwcgfi.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtgciwgmzj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtkglzkcdb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxqtikzg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtpybkijfm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gtglnlmfyx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtdopigiqb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gtcwwfjvrl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtgfydqjva.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtfhlmprra.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtpcuaqpty.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbmbvgyy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtlsxbdkrd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gthvgywlvd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtqqfxlmgj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtwugzlpfz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gttjaosnhk.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtfyxbmqww.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtxpjpsrcc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtxvsavzwf.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gtqpmndygu.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtbcgetqor.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtdxlzilsk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtnsrduikv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtnfejdffx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gtxzlbtjhd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtbexjmtpx.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtlnwhedkl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtnpzalsat.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcahofaai.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtkvhqsnkz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtogzqzwbc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtfcnwyhjm.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gtxocnhzox.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtiywwexwz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gtggirpbxb.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtigmwfrkh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtjffkxrbd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtwwymqxbd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtbtlwtxbb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtgiwsjqjd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gtpqslbvps.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtokckuvoe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxqpxkcv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtxdcqcqeq.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtlehekinq.html


<!-- 参考信息 -->