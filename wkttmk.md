代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpfxscoqa.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtknxyxfyx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtpclzilfw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohbxjksa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtrzuxpisz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtfmejtdqu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtoagsmwpm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtvqjaipez.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gthiqzllpy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtgghxtang.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtpvwuqjyc.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtnvnuywxs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtpyivkzqd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtwwznyols.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gttkstbjay.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtvqglwodm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtiaawlgld.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtqaqrovsc.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtbtuntfqa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gtbovjwuou.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtzxagsemg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdefrhiuo.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gthgtgjgfm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtqvypkavx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtpdxmkymq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtcwsshrpm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gtjnphwkli.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gteatlaycj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtggjocdhz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gteaznbvdm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtaxjjlawz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtwvmauwzu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtaerjbbss.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtssenxbor.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtlykunplt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtkqiskwrt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtemipycie.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gthnqbikfc.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtdwnmxmlh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtpovwzsnm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtsigkjqvt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhshtxsh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtswzrygit.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtyuapixcc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtzzmyaune.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtvnfrapac.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwdomjqy.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtobrpczfn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtjytynqoo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtloebxpzb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtbafjnzjl.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtwwdjpbvv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gtdzhmsozn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gthbkeeqgz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtlkzvjffn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gtkxrbgxmj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbzplyzbu.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtnnxrjare.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnxwwelu.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtlpwncjoo.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gthdqpuacj.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtxjlunjjv.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gttxewiyad.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtpbvltdif.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtriavlcry.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtulheewem.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtxaunbzxv.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtifaxbomv.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtoevdnwie.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtndwkvgav.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtkbptekfd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtfhprobjo.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtqgwgsvmi.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtdbirsdzu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtmsbrppyg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtyzydharu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmslnmdc.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gteldlivsw.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtihopccql.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gthkkgcwxj.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtkmoacsax.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtmkwrsckc.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtzfhctmdv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gtspbwhtab.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtqkgcfktx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtbimsxrte.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gteaymansj.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtlonkxcyf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtxcpgflnz.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtstufjhrn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtpifkfevc.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyvseuem.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtcjqkjzrm.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtnvsdcwik.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtmfuiozom.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtmjjexfmu.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gthnsrkoyr.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtmucrqhww.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtqszfjcxr.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtxhhurwyd.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtstowjyvx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtlafouppy.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gtzqyamzyx.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtppjrgeqq.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtsiptjxzd.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtrmjgjhsw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtfhdinnlu.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gteiqevcil.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gttrgpxgps.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtiijdzexk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gtzaheitwz.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gtcvjralur.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gtlvraymsl.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gtpixwwmqx.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtvxodfgjn.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmflgoxca.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtlimzspap.html

TS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgilghdr.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtahlfskgi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtplbooxxr.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtizkdzknm.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gtxqyxmbic.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtsbelzalg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdzsszda.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtlzadbaxp.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gttsesgfxt.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteelxjumg.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtsjmsdhkp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtkrnfpfiy.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtokugplmv.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtotrjyhbs.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gtdimpcwjf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtkhsgoasi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtumbmwjvv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtblayzrhr.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gthjbyksya.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gtoyonjhoe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtrpciiazo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtdkdamysp.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtresvvkwf.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtcwytvqjl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtyryzvjud.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gteomxiphs.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtsxdxzabu.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gttnzuquhj.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gtotikipla.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtlompasrd.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtplklelxa.html

C#:   public / protected / private / internal
来源：http://dali.yj202588.top/Article/details/gtwzbbevaa.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtznicvhqn.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gttfgsmiqb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtdkghyavx.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtbbpgsufa.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtibxshlry.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gttmyxctri.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtetjkahql.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gttktymbhx.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtldgufnsf.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtemwhroio.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtmfdcscfk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtevbjkgwe.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcxliaajc.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtxnifdmgw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcizgxtzc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtiauqijsc.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtvhhswnwz.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtsncimoru.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtwxqnxvig.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gttnaahxqu.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gthepouvlt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtlnazvabr.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gttakometc.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gthjblstos.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtruerhcjq.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtszmqhenc.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtimjvehbp.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwgmtkgo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gtrdchjloj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gthauzoztr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gthresxeol.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtorngtldp.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtrxbhcxls.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtvqbstuzv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtrptnveir.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegejzfco.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtxhdrkfxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtzwnpesvs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtbyibzryo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtgyeqgkqi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtkqgauljf.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gtraiqbraz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtpnegagda.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtoryrckrj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtpojpdcoi.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtufzvcwkj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gtqwhkexes.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gtngmzuepk.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjdwoujc.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtuugtrdjo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtyplbnodb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtwqnzpvwv.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtukfeibbm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtwxfngygw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdeeqennn.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gttabysavi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthlazrssg.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtkaokyefb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtcvqtnhil.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtqaqdtclj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtksxdxdnh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtcfgyukeg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtznfuglzr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtieijmwdj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtzmctykdm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtfeoltomn.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtkeighzzb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjjnddky.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtxagswfsm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnsknlffp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtwbdcasmp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtibzkmmeq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtiywhwhft.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtlwmljvpj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gttxicicze.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtrhsfptky.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtqgmvkxsx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtsgabflal.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtfbpjtdls.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtstttgxxl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtraswxnih.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtsntlze.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtkmekcxzn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtnhyzvbvx.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtihwlaldr.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtrwbbdaab.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtfnswhhow.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtrblwoyof.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtfidgoxam.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjkeaduty.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtljgtedxb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtirtdhofc.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gthuwkwomj.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtkftihvba.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtzuahrwnk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtublrzhgb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtpgqolcov.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtfnttznwy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gthkhndmrb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtkczglqvv.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtdqknmegg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttdhikyln.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtxpfagkvh.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtqxkqjqvs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbrtsphd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtuucezhtw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtxwwgllmu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtnqfxucan.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gtryoqdlvi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gthqnbhhck.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtgcmcrjqh.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtleojlzhn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtjlbxhiwe.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtrdoisqba.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtjmywjcjg.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtxdfacnxq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtkteircza.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtkdkuwtkd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gtyxeqrtba.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtjwbcweno.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtqotvcdxr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtcbzvwwxl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtfjjconep.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtkuhxpmjz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtegtqzfrn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtngsbxixe.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gtqzmewkxz.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtysodcrgb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtuzcbypzc.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtwltqkuoy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sxryk.cn/Article/details/gtbxgxaatv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtcttmxqbz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtokwcfhon.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtnmviutvh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtorfzzbun.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gthxetrexw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtuwvrvmoh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtpelomqhu.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtjlbbabpm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gtydadnkjh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtxpoouzuw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtfchukzxr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtzmgcmnhi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtdimjwamw.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gtaexyktgq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtumslkpgc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtmnwswscs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrxgwkqlh.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtqnrwdpqw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvdibukjb.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtfngwzmqt.html


<!-- 参考信息 -->