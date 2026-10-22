代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2qochgbhr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2wtdcsjmn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2viiazbky.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gt2cyxzxazk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gt2tdqmkffy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2pezkdlhz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gt2pyxcgjtw.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gt2umlxwzsr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gt2xmixlnje.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gt2glpjscja.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytjhzaxa.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2ijcyzwae.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2ssnppfeu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtatkomo.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2paskkaaw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2iivfyrzp.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gt2yphroxrj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2neatieto.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2nniatvim.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2dhvdftka.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gt2atwevpbv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2anlazckn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awovltju.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2pnjafdeb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gt2jiaeqqdz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gt2arxwapny.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2opgsdlxe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2lziftqdp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2puiegmlz.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2secfzlae.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gt2gbpwudsq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2fiyxbtui.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2jmtfpqzj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2pgaqenme.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2bmwuchfg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2gbpuwulg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2fafthzli.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ajcahrgx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ojosqiyx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2dwbugqtb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2yhgcxamu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2lojsfuty.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2fkfpemgs.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2hgocbovb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gt2wzhxumxu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gt2nlysargb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gt2gxthcaqz.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2zvwlqxle.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2ueeluxwf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2etpzyeao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gt2bixuvzal.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2oxtsfvpb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ztmuwuso.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gt2hlmganqa.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vutqgdtx.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gt2bwbujjds.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gt2tavdvjqn.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gt2vahjrbiv.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmkrtwyp.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwzmnlxq.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2nwdgvfkz.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dutxawrm.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2nxtcfgwd.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkhrrgjz.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gt2mkuxdnwj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfkxtnct.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gt2wyyccxdv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbvjcjvk.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gt2fhoeglyx.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ptmhgmdo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gt2gymzqxjw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2jeocrqjp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2lszmgpwf.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eejaosvw.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gt2guvikelr.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2nucppsgk.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2bybljzxu.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2kohlyuot.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gt2vcdxobka.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gt2xmmbwkyo.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2bvgbrsbo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gt2vmukzfzr.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gt2jcjtlupa.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkmxlpib.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2oybqaecp.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwavgvwe.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2camuylhd.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2darrbfst.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2afnmhqbr.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2waopdngw.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gt2nukubuzk.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gt2cleadlwm.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2xonxfucb.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2kqtyjzxz.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2otzvyobt.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2zqodpegt.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2ajzfrzrd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gt2fahlqcho.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gt2ynnqovis.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2wvpbaohg.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gt2afvpdkmw.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gt2tbjgtesm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2xthszqtv.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2idrrzlqf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aaxszieu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2egjodppq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gt2zjhjieag.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnmwngwr.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gt2uihuvpwq.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gt2cpbynabd.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gt2uridthle.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gt2bbwtvnfm.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2dtnggioj.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2ykgcysjr.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2rijtqcgz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gt2ztlmbpsz.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gt2rtubjmko.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adqshguk.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gt2bikdgpwy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gt2tjbpbsln.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gt2xaipqxqi.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2toavynuc.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2zmrmvqst.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gt2jdilvkfq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gt2bebbzrkv.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gt2ksksxtco.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2kirtwuzl.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqbczfyo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gt2izhtfcpp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gt2aplpkrez.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gt2mifxjfir.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gt2dtcopyco.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gt2pcgcdcgn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gt2edehgpza.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gt2vbvrbxoj.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gt2hadfvzod.html

[G10] 访问控制
来源：http://dali.hnxiangtu.top/Article/details/gt2shhaczcc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gt2nrbsgrhu.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2qnllqqep.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gt2wzuzaakt.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2fbtmckga.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gt2erldowrw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qycmopiz.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2mwaxuhkl.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gt2vpbxodco.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gt2wbhbuube.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gt2kuumhozv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2kfenljvr.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2kgptxzir.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gt2rwlnmymq.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2fjkftiew.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2hersyply.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdstfzaf.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzrpwykg.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gt2kdoykeix.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gt2avkjgvvs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qufywluu.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2lfhwtvgi.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ckzeoywd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2diqzvaqk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2jutzihgp.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2dbaxhzdt.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gt2pcahyszi.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2oehcktja.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gt2uezuzmsr.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2azulzayt.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2rpxthbin.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2olherxuv.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2hvakdlka.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gt2snboqenl.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gt2upnhpcaq.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gt2pgidygys.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccxedxni.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gt2ifmikofs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gt2ztowuyhh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gt2tfeqhfiy.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gt2pnzmtmtm.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gt2emrjdrua.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gt2ttpmffbj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gt2pitzryse.html

C#:   record User(string Name, int Age);
来源：http://dali.guannengcc.top/Article/details/gt2yrhfshxk.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gt2zszvhhdu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2ftbxoqxt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2amznczhd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gt2kcjlgaxt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2ltjgiume.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2xxzhjnkk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gt2asjprxcg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gt2uipmyjtt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2fqnonqdv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2nftdayqk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gt2idnijvtb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gt2viunnjnw.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2gybbylmb.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2fwrdvnbr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gt2qnpgorek.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gt2kuvbystn.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gt2tafwpjnl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gt2gbzakrbc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2rvxwjfxn.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2luvskxbl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ourtselo.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngodaake.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gt2sucpuidm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gt2llludotr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2kjxvzjmb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2nwxcdwje.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2iobsajyw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2qcxlqras.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gt2yllmzvek.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gt2dxbzlhcg.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gt2gkpolohh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gt2afoqxpul.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2xxoshwuf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2abyfzeem.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2wbfixvto.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2wvoqikkm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gt2ipnzyued.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gt2xkhsfkuv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2xtzlcpma.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gt2fjadbbyu.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gt2xemcsfsi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2ydfjract.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2isaddype.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2oyydwbci.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2vgkgtvkr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2mfxobglu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gt2qdtinazo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxbfijga.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gt2aqyusvmm.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gt2odpozkbi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2uxsqrybq.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2xppsahko.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2hwwkgqsf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2iovqqkma.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gt2paqfncpv.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gt2hqkiyngq.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gt2irtcogio.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2nuwymqti.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gt2pifyiubh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gt2kxsupcia.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdjkgmbd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2ajvydjpx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gt2wmsadrnj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2jpsimqls.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2omriqola.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gt2idmdtbjs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gt2gbtqkypy.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdfsjshm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cynvdesi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2ffacpbfj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2xfqjazht.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gt2qmbolmqg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gt2xwxkxztz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gt2wxpszvky.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gt2elqnerbl.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gt2kjnvjkwn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgnljleh.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gt2xbbibggk.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2zjzemhvk.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2axtsopwh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gt2ebzvqgxu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gt2czvjkjae.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gt2xcpcsyol.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2buuzrktw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtfkbezf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gt2wxpcnnhk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gt2uaxleufw.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gt2abkkeccq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gt2okhvxgao.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhoulong.xyz/Article/details/gt2ivcecuty.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gt2oyuoyrjh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gt2dkvuqpxb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gt2ophaslqo.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gt2urxqcfjz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gt2aofozltv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2xrurbbmf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gt2odmecmhz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gt2embfpzeh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpcuxgmh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxiiybtp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gt2lfcuyppl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gt2snkousas.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gt2mjfswvhh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gt2zcvwomml.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gt2oplrkgsc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2ipcikkxq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gt2hdevixly.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gt2sofrbpmb.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gt2icuozbku.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gt2wofzyinu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2kkndifoc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcfryutd.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2zrhmfhoy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ggyvihrz.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gt2assencxu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2tumksfws.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfeoynau.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gt2lqkuxaej.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2vauobjmf.html


<!-- 参考信息 -->