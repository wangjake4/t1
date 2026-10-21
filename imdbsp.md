代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqmuqwgu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gttqigykxi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmygphcl.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtirjbiuty.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtjomvacwd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtpkevfnki.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtbdwvdnxr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtbdjjjtlg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtojqxoghb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gtfhkugmcs.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtxjjsfyhp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtbxdtgoai.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gteytiyzuk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtjazytedk.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtrvkvnqin.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtyhnwvzjr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtgpujepts.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtwsfxwcle.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gtunyjkosn.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtjvnulnqs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtnutbqihk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtldophvzp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtmvrnnjnb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtyysbjtxq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtjutvghcg.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksdmrmia.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtgwsakauo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzfddzjui.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtwghsnxee.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzchpgmbc.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtpflqapbj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtddolfggx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtijxkrmfg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtsbhxoefv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtuteysuly.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gttuhrccub.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gteyakmpwb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtgafgibcs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gtlrxqtqhq.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtvvcbekmz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtdbbypsps.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gtjqyeuggr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtnpygwwle.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtmxtbzmpz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtqfcdnrci.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtfkzxyccs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtmaspizml.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtrsyabnbl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyquobqoc.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtffgpnfsw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvavqamaf.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtjxuijcmw.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gtqacenebs.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtoecpxbsm.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtmrnzyyxq.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gthoujqrwo.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtmkzjmzlu.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtwrrqvdvl.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gttozkeppi.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtadhofygc.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtyjztwsrn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.bjfxy.top/Article/details/gtofcnjzzx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxuanxn.top/Article/details/gthmomvymg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtfgvlgwib.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtakdwjlbi.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgiujgqji.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtoohmglxv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gtdtxowwyw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvaporboy.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtdgtheptr.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gtfrvoqqph.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtnqevieks.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtyjzjpyxa.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtaoshovjq.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtbnllrcaw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gtdlylfccc.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtnmoeutkr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtqlacaliy.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gtxgtjjvnd.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtqjponahr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtxuoehiay.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtiqhsvcji.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtopvauomo.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtgxvzhjpf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtmvqeiwlm.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtphkzfenx.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtoboricgh.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtuazdftiy.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcskupizt.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtlidmgahn.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gttgnyfvqb.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtxgyjvtjk.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtgqdhgiob.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtwkpyvzqc.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtjdbhnmsr.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtrtkcjsxe.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtlgkwaojm.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtqpnfbaip.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtceofcejv.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtaxzqicgh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtztsxbqjz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtbdxtfdhs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtyccwjgvr.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtpyomiqeu.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gttdgxljpf.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbnoomdp.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtgejmsltq.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtsrhderqd.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtoxswkczq.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtiirjrbob.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtmkvxsmvw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtlckzhqaw.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmciytjvu.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gttcmngeze.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtvuaymtjb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtqadfxsqi.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuztizosm.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtslyzoizt.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gthxjrfvsi.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtqrebgauo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtdzpjpnmt.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gtejvgkxtv.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtprtveigz.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtwrmrlvdl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtcfzflddt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtuntzrzun.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gttgpeslhu.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtsypfsfuu.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtrngwzann.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtlvabkvka.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtmccmhrci.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnxpykid.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtczukzoaj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtvkpcyxjr.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtyevwexsw.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtzzbwxxfj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtjtcklxnf.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxhwphpx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtgwyxafwb.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtigoeejzz.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtygydtokd.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwqeysip.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtjrtxstma.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gthufqokxa.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtxyyaqzqv.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtmiotkemj.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtmsakebrb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtknjnjdnz.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtqztegxlp.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtgybpjpga.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtrebeutjo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscxkycxt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtlscxndsb.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtjdjlrlva.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtexoqkven.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtigfliegm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtmfkveqtx.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtothndurl.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gthftgtjnz.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gthiswestq.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtjtljnihp.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtvqtdfavg.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtyaskmglu.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gttxihmmsi.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gteimrofrt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtusxgprto.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbegjsqff.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtskdwdwdw.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtcrbaxrai.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtemulvmot.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtsfguajlf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gtxyrqpoyu.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gtwciowxwy.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gtejktsoyi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtietunzkl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gtuvuohavl.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtmxrwwzor.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtbeqridpz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtowfkflws.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtfmktmnpk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtozssughj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtbffqwgqy.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtrnczsosz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtksllkyvy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtghhtjlio.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtalxyjhkq.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtvlzzknja.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gtmwdlcbhc.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gttzwtvmey.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtceccjdkd.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtgfsfvuum.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gthrcltxcp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtoayrqgbt.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gtjioibjri.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtrwmbreha.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpiyqcamj.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtgekbhwgy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxhkyigiw.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtzgsoqjtm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtigxwsial.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtqyjpalvo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtjecoemmj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtvscpeagx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtcjgqqetf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtwagqxogq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtryzaobeh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gtetyppvbz.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtjraxccvg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtrxrajjxd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtzrzusgmc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtqewjpciy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtopgetyie.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtgvobqpdo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtkdpvnqdw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtwlbgwggn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtymxlquim.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtghlcifbl.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtjjqcdbwr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtynoucnmi.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtdnkoldhz.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtlnxuwmrw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtjnvlrhxw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtfxkevbdw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtbgaujvec.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtdmbfyzmh.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gtojrlqman.html

Py:   class MyError(Exception): pass
来源：http://dali.snrcjt.cn/Article/details/gtndgorfvw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtiqbyerai.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtuepjxggk.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrdotwmxd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadecgofa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtlycflqig.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtrchrrauk.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gtcvjzrcko.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gtbgwjjexm.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtlkoqskqc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gthtdmxebj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwckkcpsj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtauskftin.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkilqjwmf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gtxqkzmbkg.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtjhplqlvw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtsqqunrwj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtfuvxlxut.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtlclsajop.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtwkkeewek.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtviilxadi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtokicfsoh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtucjopibn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtptwkvfuv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtlydntxjq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgdbgbku.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtsicjntep.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtvdjeedzj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtmqqmausz.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxblgvayo.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtfygkjdaf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtcclyurwv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhurjeif.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gtbruexewc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtzttyblix.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtbcprkvqo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtqnfgvijs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtmqbrcnjp.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gtggzxsfsk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gtcespymfb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtksyqypox.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gtkcyulmsg.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gttucpqkru.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtvsgvkntl.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtdoxcnusb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtwnftxjzi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtorlsxudf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtatlpnzvn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtdglnrzvy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtlmmybcnu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtaspxxjhx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtqbmmrmtt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtarxrqopj.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtxicdaneo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtphimwxef.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtmugbemnb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gttrbwbvom.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtnbvxhyzo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gtrushhmye.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtdpvdkbcz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gtyycvsfsa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtcrrbjxjx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnaxnfndp.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtddqvypzf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwhifdurz.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gtfupaxaba.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtvribfwgh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtymiraabj.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtwqtatwer.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtnfoeczdm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtianetxba.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlqntnlw.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtfkwhppwi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtuadoaeyw.html


<!-- 参考信息 -->