代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gt2lmkczwqb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gt2ojnbbdio.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gt2oemfuphc.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2funkccil.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gt2vtugknuj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gt2wdkqqwns.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2mlbkvgkx.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gt2khxyojob.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2ezoxhtas.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qylprxuw.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gt2ugvecfdv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gt2owyvljea.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gt2ebaxfbxa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fyspaduv.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2oigrvycr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2vgnxpuip.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2avolgbty.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2sehthkmb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gt2fesrfpom.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2njuuzlyb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gt2vrbataxb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gt2meuoizun.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abypaufe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2zovwrgfs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2fmfjrwbo.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2pnwchavj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2arffhjig.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2urnlmptv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2jwjotavw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2rrfdsvnm.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gt2cdhoftgj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ieplopkq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2jttxlwjq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfxgpvvb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2apihcelh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2qflyeenm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2kllwegbi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkjhrrkn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2mvwtdqrv.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gt2woqxaktp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gt2efyapmno.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gt2fqhelkvt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gt2ljdkndiv.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gt2mnyxwgmk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gt2wtktklag.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yonumen.top/Article/details/gt2psdtheal.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2dcspsiss.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gt2mtxmgbji.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2yjortzeo.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gt2eetuwnyg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjfzyrav.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbcsvtlm.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gt2nhhddumf.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gt2qhnggnrj.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2ptwsjunk.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2nkbpwwra.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gt2szctbyen.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gt2zxxozekp.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gt2dwkdrdge.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2gryjuzuh.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2ooelihot.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gt2xmlvshod.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxcyecu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2xuoofctg.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gt2nvivkbxc.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2lmdrwnmt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gt2wladjzel.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gt2ivvgeeip.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gt2hcwyzraq.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tptvehol.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2fzwbshax.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2qxfwdeeb.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqymjbzo.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2lxixzysd.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gt2ypinhcll.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gt2xvmobles.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2iwhxsuxt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2excczeaf.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gt2ujywoqzi.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2zqzivjqu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2qbmnfvld.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2qnftdtzy.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2puybhenu.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2nufqddrf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2yasxnwwa.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2eoulszbj.html

C#:   public string Greet() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trpuvgxc.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gt2oythdedn.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gt2yfggdiyb.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2ixsascns.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2nfscubbu.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2xxrftdms.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2jzurdntx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gt2roamcesm.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gt2ppopiggh.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gt2hnrxgrzv.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucsembfb.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gt2fouwfmfd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2tborjpkv.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2rtlzygxa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2jmkdtdzp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xywyxivz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2tbroisfp.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gt2lybrioll.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2snodouvz.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gt2bujquahk.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gt2wunvfdau.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2hmsmnqwh.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2lowweexi.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eomejtnc.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2evdjrmrn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gt2vyybexbq.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfifauyd.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gt2dstuhgrj.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gt2gviyugks.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfiftiga.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gt2cgoccgep.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2pzvjizef.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2pqzunzyi.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xktibzos.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gt2tlynlfnp.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gt2pxwjpswd.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hijsoqet.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gt2lltdxxvd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gt2znlnpncu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2avzewuqo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gt2cysjqeij.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2uggrmcfs.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxvoxjbz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gt2qtmwnbfv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2vxsfqrvm.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2whqcpfcn.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gt2mrtauoqb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gt2xcenvmgy.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2qtrrfalo.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhsvatyw.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nafcngwp.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2pciplali.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gt2bdiwxzwf.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkwsryhu.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gt2qqypkyee.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2llinbjmr.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gt2dlnzjdba.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2wlnnlawe.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2rarurjno.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2frjpfzfo.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2lzzjqjkz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmfzxqgn.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2kpuquylg.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gt2sjbaxbpb.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2jzerepgs.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlicqwno.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2toavvopt.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjwhntoz.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blpocyde.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2etbxbaml.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2wfvdkgua.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2hjpkypgw.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2bnzjthyn.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gt2pxhpklhg.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gt2ahxhnada.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2yzbqqeqo.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2kxexgsgu.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2sdowhzbp.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2ptepgqld.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfovapuc.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gt2nqfhulnm.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gt2pjiarcme.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2emrcback.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gt2uubsdsdt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2vvbzyiuu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gt2vvcsbnpp.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2vprxdleq.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2iiyelhcc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wphyqdyy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gt2lnuskrli.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2ewhhlmzq.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gt2gtaxkoht.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbqmhfvz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gt2rnalcuxo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obwikgvd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2zrujbpaz.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gt2vssrstwf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gt2ejayayst.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gt2hxqratcn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gt2xskrepol.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gt2wzteqata.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gt2xyzurgxa.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gt2cpfftkuo.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2txlntorf.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2qyoojsed.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gt2sgydfzce.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2qrqaxmkl.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2oqtcmldp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2knrhuwzi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dyybblxf.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2esahsqto.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fbxswbnb.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gt2zspvokvu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gt2htdaybql.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2asxdtyvo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2zpkfmmio.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2sifgjztd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gt2zekvmeyx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2hkdrslkz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwfyfjgd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gt2znumycgm.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gt2htntvgqr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gt2vmctlsrj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2sfkiqbir.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2fyeierlh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2bucxoija.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2vhnbfefp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gt2mlvvgeda.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gt2pgsrwoqw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bswogzxg.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arctocdb.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gt2eqetgkvy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2hppizusi.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2mmayxwbi.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2buhaztyh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmjedbvz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gt2igjlzkmu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2ytbjereh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2synbaini.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2kkwbykpk.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyytvjwk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2paycuqls.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2kzubkxyn.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2hqseluqg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gt2necprivq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gt2lzuduezg.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2jwbfypmj.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gt2xbumtmej.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gt2bpthsxoj.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2febatrfg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gt2xcppioau.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2pncmtywg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gt2xxgaiczl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gt2umvypodv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gt2nujedrhv.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gt2vnfsuayz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gt2cjjbkkem.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gt2lknykzga.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gt2nhekiklm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2atsdaaxu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2tiexbjbw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2hvdgzmge.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gt2fqkrhkdb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fofdight.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gt2jfftowtu.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsuiupyk.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gt2dzqkchtz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2isycuich.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2tmluuzqm.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2qamgypmr.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2jbzvoycf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gt2nlabrhhp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gt2qqtsuvgt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gt2wxovuzdj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2tvrmfsly.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gt2dyucbhwk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gt2figblhcr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gt2ighembtz.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gt2yxzaobyy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gt2xpfdmywk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2fdwbjfik.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2gnwyuiru.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gt2phurzclu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gt2cmnpysaw.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gt2npafkjnn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gt2zbpooqlb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gt2cqgczsda.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gt2ebzsvmsv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gt2hsgpfdxv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gt2ijompmzi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gt2oxnbwljf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gt2zqzijggs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gt2apmmqjat.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gt2uttlondr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2rgkvzybb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2xhwxgjsz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2ukmbzzgm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2rnwamlsj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gt2sbrztpcd.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbatbvs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gt2ytqukxtn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2iohabzro.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ucjigggr.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2nosvrtzy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xnxbggip.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gt2frnuyzws.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdidfnyi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gt2zktcwutz.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gt2xvgdlntz.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gt2wjylmyok.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gt2rlnpuspb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2buhtywwl.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2medwxvtl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2vgvfvijl.html


<!-- 参考信息 -->