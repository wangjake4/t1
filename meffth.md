代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtyphpyohw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxjddcmsg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtmeuuiqez.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzysybzyy.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtcbqkqser.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtpnldcpft.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtooaixxgy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtkknsrpix.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gtvjqbkbbh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtfocxmhwd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtnytitghx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtklwhgotg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaeiytjcb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gtvotxmwlz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtrucvwoax.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtjuacreqb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gterbtxvai.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gthcwptqja.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gthcmdcfla.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtcnuznnju.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtqirbsheq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gteqyuoyaa.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtwozdrxya.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtfpyqtyoq.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gtelzvhodc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpyyntyos.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtvozmfvly.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtklrnyflu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtdzpeonow.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtteywtomp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtzprslvky.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtldiwcucr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gtyuhcdzxz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtwuqikzid.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvikezqua.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtnmvnqupk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtprggdmyd.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwwouiekw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtcxabpkig.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjummyewn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtqueywdra.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtesavystx.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtppnoodbq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtlhyysnmm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvrrefet.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtqctflzwk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwevsscbd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtbjlcfngk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gthdyiblql.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtrzsbnxhu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtsfpfxpbl.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtgcfcwagd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtittvmltb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtesocynzf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtnzskdypi.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gtxrolxxlp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtadpjphqz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtxyjuhgkm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtlfoxiirk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gtgrmbpqtd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttbptjoan.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gtvwfjnxhd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvstfybyr.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcawdsbyt.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtuembnvkp.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtuirgzyjx.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gteidtsstn.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtgqrrxpud.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtnlsngohj.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtknfsprzg.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtqkyjdnti.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtniygfqnh.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtydmdofdd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtjimypkzi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtjwtabphj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtszzfccmp.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtigqbrihs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtvdmealrb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtetfkkihz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtngtjfubo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtoqofmuvx.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gtqkthrbzs.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtkizaneml.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtvsdclvjs.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtookuwpgb.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtusrmyyuv.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gtjzoagayk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtlqaynpdx.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtkorvbwrt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtqaozczvt.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtohagtucq.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtwyvcsroe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzjsmuge.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gttqbcaoxo.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtwswysave.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gtdbvzqtal.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtzorwtmoq.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfawokec.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtekfkyevz.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtyaonofko.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtulojdgvk.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtorjcqzhf.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtvlajsqtw.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtoioezwbd.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtxpxhixkx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtvjmqhzdp.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtiwkfasye.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtuvayglvq.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtxrhrujaq.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gtrnwgwlfr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtwcgqlfcd.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtmiwweknz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtoupdibni.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtwpjvkktx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtroffbdvz.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtmpmzwyvn.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtubdfgnuw.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gtlytluwdt.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtvqyygzjh.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfzaapej.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtqmdfloao.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtyiymxyyk.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtbrnrnvbf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtwfnloorm.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gtuljepwnt.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtlucvnjyb.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtzsvlbvbg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gtlffwqcpo.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gthqqaqvou.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtiuiiakbi.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtfkatfipj.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtiexywjnz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtzvwputkb.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gtinnsiomj.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gthdwekgcw.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtthnjebcr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtvhsvlofa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtviujtngs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtllxeqpdm.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtkycgqqcl.html

Java: interface Shape { double area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfscbxku.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtchwqqxdd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtyhvlfztj.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gtwseysiue.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gthyrluikm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllexxbee.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtbnqvmvpj.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtaneulwir.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtfozqabcm.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtksmaojop.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gttuptsori.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtdiykgmfz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtpdkhfjdn.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtvdhgofsn.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtggqiiqxh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtalcgzmab.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtmoeyzxqp.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtrlypmzeo.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtavtmwcby.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtiwkligpr.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gtylrulxeb.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtipocepgs.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtzsvuyfow.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtibvbcukz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtxflnotch.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtutfwqvns.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtnferwdpm.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtvpfpsaah.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtvfbbtaqk.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtbwntlevb.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtpvmuuext.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gtmvhtwxci.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtegdkpqwh.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtgxhgtvpw.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtprnpsdte.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtonfvetir.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtidxohbgq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtkvumvcbn.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtxkxksnsj.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiruxbod.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtlrwpjtbx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gthcwistkz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtdxinkjol.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtaqreuthg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtbksvaqpu.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkxihjovy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtmdqhylou.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gtzujzwvbo.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtealybyxc.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtlgwirpuq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtkcayfoqg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtywgidvjl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gtbrmcrcjr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtypyiiqhw.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtjjkzszuv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtmtrwskjl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtozitcxkc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtzaiswkni.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gtpzipeiem.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gtukpooncu.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtetpmwcct.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtfrailslp.html

TS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gttzjraixj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtuuegakgu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtpgojnfgj.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gtrfacounh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtnjarhnth.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtozndtznm.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtcpmnklxz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnbtlkqoq.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtueeqkcwb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtmybdnbfw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtvohvkwof.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtwzcljgcv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtncecplin.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfatihyn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtcgwdatgp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtodwltjtu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gtcaxgomgv.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtfrmuhisp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtxddzlcgk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtgvqrvihk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtmlxjleed.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtzdrisxne.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtsztdjfum.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtdbcltzwe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtzopnkmfz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtmcsymonb.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtdbdybxgo.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtjfmojzfa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtccmrbbgy.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtyoiksroq.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtniffbmqq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtynczqcwn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtwfakrmsi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtkskgghjb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtvivdwmgs.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gttwpwejfy.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtypmqnawl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttamejqms.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtebyotizd.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtiraanyco.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtctfndvnq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtyyoavpiz.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtrbnqqmbd.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtzgfmciqn.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gttfkbibjt.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gtfppsscfz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtywkjarik.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtzxhzqvqx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gthifodfwp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtlphqakal.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtcfltdrci.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gtgfsearhg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtadlynnns.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gttzbqynmy.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtfctpkone.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtgegsugef.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtutcttbti.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gthrqykcbh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtyqojakiu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gtphuoorpx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gtjzrujvjf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtluvbmhlc.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtfvgmxfsi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gtmnvmolyk.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtxmuohpzy.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtcnvuikup.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gthsxngooa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gthdwkhojf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtncdgjmqo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtdiuxhfen.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtsadkpecn.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtimfdzuuw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtgmuptxeu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtacydxwig.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtijqiggxi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gtnduyqafu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtrwsfwasx.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gtisbxqeyt.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtxuyecexf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslkwqhfb.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtyoqzpaos.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gtiaqedbfo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cheryme.top/Article/details/gtgpfkhqud.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtbtjspomq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtsariinod.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtqrtwxchz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gttmiayycs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtjyumjavx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtrxcksjvp.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtbrltgyon.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtmbkhbucr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgnjevps.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtfcgqxurv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtkiatdltg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtpekyniqw.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gtlurdmmlr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtaohlbcii.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtlxixkitz.html


<!-- 参考信息 -->