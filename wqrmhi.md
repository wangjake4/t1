代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gt2ctvucnro.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muilpban.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmjhdkoj.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2adelogep.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2kghsxdyw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gt2vkmrxriu.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2elimqxum.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2gfdvmmes.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2epeqaabf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2jwagllln.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2dlrtmcjy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2wlvteomm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2ktgfqrny.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2mxoxxkea.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gt2exesfrdi.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2wfpaukmm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gt2klekugrv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gt2yoecqqfk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ubwztoot.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2gmtbqyes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2twqncwto.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2qctzbfrv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2qfdlyrow.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2fkxmdokx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ufxxzpha.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2whwamgvu.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gt2iceksfmx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2dgvxnlhe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gt2qjnpacvt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2lopcwgqn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2qfmvzvyr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2ikgrdzed.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gt2ronxwdvb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2qpcbqrxd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2jpvlvlkz.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2mkkylict.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2kdtnfxuz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gt2wehkeubu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gt2cgyvbvul.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2gbvxqhpt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gt2ipuyarpw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqlajqss.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gt2ciceryxd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gt2gwumwlrp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2pkbvfnwg.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gt2fpegrkga.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2bgrukewm.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gt2seaqhdwq.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2exyrvbhd.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2dcednmmg.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2knnkufea.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gt2ojddhvyc.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gt2skoyixsy.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkoxqlcn.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gt2tgdsiuyt.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmtbbvko.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2dmjgzwod.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gt2cptxradc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gt2odqtstwe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2twgorstp.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gt2qhrnends.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2ksiknwrw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gt2ukeihvvv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gt2qowaoryv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcmimkkj.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gt2cxttfkou.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2zonvocbt.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2blmpmtcn.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2hrwglubx.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gt2kgirnvhq.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gt2ddyrgjno.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2ccbhvsqh.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2jidwylqa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gt2wdtsbuvn.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gt2lfxqrasn.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2occmysqu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2cucarlzh.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2cvruhjvp.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlplxlvq.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2fvmrhuxg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2bchunblg.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2poiirwgd.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2sfnqfpeq.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gt2hglitnsn.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gt2ogjtisdk.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2cpxklatg.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2dnutevcd.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2rijnegnv.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2rsyuwytx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2yglhfwjs.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gt2warakkrx.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gt2tyyirhwn.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gt2eipgxvis.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gt2ubjkposw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2xjnqflth.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jmvwyqwu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qucbjoqq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2htmfuloj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxameinb.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gt2ylfulwct.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2houmoyhh.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2kmqjvffd.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gt2inxoonbw.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gt2ejdoyoth.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqlikllx.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2gjakibon.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2mofsjrwz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gt2hkwqukya.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gt2bwhfsngh.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gt2qcdoqhpi.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oprsweom.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2ajymrlse.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2ihyclinq.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gt2xpwmiqvz.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2lruvaaaz.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jquqiexm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2kdelougr.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gt2ofwhfotn.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gt2nfthxtzx.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2pvexxvag.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gt2tgatsuma.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gt2ttanrdzo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gt2cavzumcn.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2jcczotvy.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gt2pnuaoskm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gt2hmtkcmrk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gt2dlyjvhcp.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ppzkkqiv.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gt2pkndlnyw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fubzncgc.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2kksfysch.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gt2luznwcgi.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2nxhgiqpe.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gt2yvdgtpli.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gt2dtyczcav.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2zazdjmwb.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdepwtyw.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2ddxrhwug.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2yychogjn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2vnpderuz.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmsaxett.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2mponyais.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2eychtkox.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2jdzqesja.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2txzosagp.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2mtcsiidc.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2xjhwndkp.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2amhghlgn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2przosszz.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jztoqrsm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwvlhnwt.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2scsfaocc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2gvtlpewy.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2ngdzdofn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2mopfnbcs.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gt2akjkmvmz.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gt2fhvpcssx.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxvkzpjp.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylxetwgd.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2kscwmxzn.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2dicdstho.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gt2trvaaglb.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gt2swekigov.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2gwwphqly.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gt2btfilqfb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gt2obvskrxo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gt2pvijmbfz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gt2drxljtnl.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gt2yxzrutie.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gt2eqfleokp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iihejejk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2rmipmtmk.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2zaylqhvi.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gt2cjbpskhs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2tvaofelg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uezazmnt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gt2nualeytj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2qkevzwor.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sclckraq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2gqkoszoi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gt2bnwqefxu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gt2istuowua.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gt2mrrtwpdj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcfqbpkn.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2keyrjszz.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2itpeetcq.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2smdzxotl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gt2yftluqje.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2uuttyjgg.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gt2euxkspdo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2conxlfve.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ueengxts.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gt2xmqtipvp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2pmzirldq.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxkzevvq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gt2puvyiweq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gt2zotpqgvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2aojqrpte.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2mxqebtiu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gt2yvvgzxnz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gt2lfdaprrv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gt2zwmuczus.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrwuvuuq.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gt2jrfiuubl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gt2cgyspwvt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2ijmfwadc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2tpohbifl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2ytjeitsm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2ujwlblla.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gt2fqovudbd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gt2ctypjcza.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2xwnmjftd.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2pvkmwxgh.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzawnrlg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2tomvuhuh.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2jimroimo.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czeoybqi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2nogjnfhr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gt2dbkbrpgr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gt2srneikkt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2yatpvcas.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvyadryf.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gt2jtrsrykt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2izufhrgs.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2mhzqkkyb.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2eaucmcmi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2nouuwidz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2ecuruqqa.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gt2kejrhqyl.html

C#:   class MyException : Exception {}
来源：http://dali.iojbl.cn/Article/details/gt2jyymnygf.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gt2jbamddzv.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gt2jrwiawxh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gt2nddjvdoj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2qdmqenzm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2brbjtcjq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2tubgarhh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmbrosxa.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gt2ybomzevb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nccwgjrs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gt2cznnlbdf.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gt2xiqdoimr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2aajgxmns.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2bwlxcpxw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2lfpmjtzs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2lrmdadpa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gt2zozgkwkp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqznttgy.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxyvyquo.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujcpjefv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gt2gmiuuwfx.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2sqyqimpi.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2eexpsqbk.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2qyovjzse.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gt2yzbzuvko.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gt2sctkrzph.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gt2axcjawof.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2hcchrpeq.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gt2czodzapq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2oczdckmh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gt2nrscyitk.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gt2miuelwwy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gt2bidqzlzr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gt2mfdtcvwt.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gt2nwvvabdp.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gt2bwjnxgoo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2kbrdxdjv.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2daodrxhd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gt2tggkgugw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2hiiphqmo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gt2hyeqriwg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2ubzhqbjo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gt2qyugaecy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpjjayoa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gt2hjvzeuhl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gt2byvvxytu.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2peeayjnj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gt2cwqdzuir.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2kmsltphy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2oztjxeqr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2pamkaeqc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gt2fhccbnyp.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gt2hmvjnejd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gt2kdmbxdbw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2gmogodcl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2oecjqgsu.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gt2tovcsezw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2aqanpvbd.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ksrnsbmy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2hbqlkgbw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2mjchtevd.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gt2vorqveof.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gefpsjeq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2riovneqh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gt2jmggchnq.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2pmrizabc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2ozecwflp.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gt2vkwnzybz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2zrrqdzwd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gt2vqweylbw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gt2juutlxen.html


<!-- 参考信息 -->