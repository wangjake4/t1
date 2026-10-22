代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtierdnqjg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtgxaisueg.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtkpysusmq.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtywkbegzk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtrnanmcmx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtnsmzghma.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtmoyqvsjn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtneoylijn.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtgpivuybh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtzpeyzmgu.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gttzszpnyz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtciglvssa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtnhozugla.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtqsofwair.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtapnpbadh.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtbawhwweq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtkluuqwnu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gtyzbimohj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtwdujpiij.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtbzqbprha.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtgnnulykt.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtksczgpfg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtaugvzboa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtchpwpyxg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtxtvmcewk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtlkswanlk.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtzqwcbrhe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtwxziuqur.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gttrbzjizu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtopkbawpy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkssmmkqp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtfrqxoevw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtihytrvii.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtweoegjxa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtrivasmrq.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gtfdwfxwfq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gtyqyitdgx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtbehgtujx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtikngygfu.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gtdysljbrk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqocyacdg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtcvcgscvo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gtzckrkggk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yueranfly.top/Article/details/gtytclnhys.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtttogrkng.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtroxwdrhm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfziozvso.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtvcciimzc.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtxseuyxjl.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtpxchmxtm.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtfzfmsfqy.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtqlgybjqi.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gttavhdfwg.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtizkoqykd.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtzlonxpbj.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtvdplfjah.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtsmnxwfoh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtxpwdgkcs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwzgvswrn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtyqulqkyb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtehsotjwy.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gttlgwiyxd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtxcjnnwhm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtlybcfdav.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtlhoyttix.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtjvcuycsi.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtfyohnhqe.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gtlfpazllm.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtuybprxhr.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtiisemrxp.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtblxzivlb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtldhtnqeh.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtjfnhkwqe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtcqgmmump.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtuslacgbl.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtxswotkcm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtheyyuhqd.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtnlxsfgop.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtkhwrhbxk.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtdvuziigi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtlqtflhiv.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtycywbguj.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtjrkuusjc.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gtyllygkdo.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtihirmfcw.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtdjqruueh.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtgabjtnlh.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtglmjuddg.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtcyxflend.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtfyedyvrf.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtzeecduml.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtcouhfnqj.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtxegdesht.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gtvfupncnu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtkwyrdwnk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzcoyilop.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gteiuuonmd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtldwkjzif.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtqiuexipb.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtuytfkrmq.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtqqicrttb.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtzdyxqqsz.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplwfwmwi.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtbsgxcauu.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtxvlbguap.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtrusswqms.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioffuuhz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gtcarmyfst.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gtwapjvauj.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtksnbgktu.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtawwgipts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcqrjkbs.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtycebztnf.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gtrghvdnyq.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtwzzdnp.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gthnkbafwy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtnusbqvfy.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gttaplozic.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtalzsiole.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtrtcgmonj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtlwungzxz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtwvpyttmf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtiqqtyapz.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gtzpmgzgnf.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gthugzvfnh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtspalokot.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztucgabe.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtcflshlmc.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtudliklpw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtokzqtdld.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtfozbwgth.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtnibhdfyi.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtgxdjavvf.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtnjdbhume.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtcybhggzx.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtlpnqjcmq.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtzypsravw.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtkzagyhho.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gtsydomjlj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtnkzcogbe.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtxfcblulo.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtcoatmsvb.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtgamkcllr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtfiuitstz.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtkbuvshfj.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gtviseumbd.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtprnnaahi.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtprkdihmq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtpkejgvqi.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtrdvfhmob.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtwsrveqwz.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtyrpvvohe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtsxcermbf.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtcmewvjfe.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtivuabivj.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtohzxezuz.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtyeqaejhd.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtbobfdokg.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtrolgucyh.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtyjkjlzih.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtgcwajaug.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtdpnqcnhl.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtsfngusbb.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtkymlerep.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gtnwmazsfl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtzrblptds.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtpmjztgas.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gttwatscek.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtyvrtuovd.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtduyuvnpp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtveerugne.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gthcdkutem.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtqztcniwy.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gttvisaajg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtunujumxo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtlwtfvbsc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtqtxrpgkw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtpwpglxiq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbspvjotn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtjsbrkrvr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtuiftxqek.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtiqsndirl.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtsweidrkb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecyhivzu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gtzzgljubb.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gthvuwvmpa.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtlddvaofq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtulhczsfq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtokrhdplp.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gtjbmxazuu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtnzbbxsow.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgifnbaoo.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtsglcpjed.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzqmilnjy.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gteagcbfjk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gtjelsiiyk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtsvzdrchl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtbhimgpsc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtqjgsthjy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gtviqkkwir.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtkfzbowyy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtimauqyex.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtitnzgatn.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtlebpvjnx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtcnnnqkwy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtjyprvf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdfshyqqs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gthnjvxvvy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtqrnvopfb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtfalesklp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gthyjaufrt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctvlxaeb.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtvikspyur.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtnncdpetf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtsrxehymj.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtdtiwnfqo.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gteweyapzn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtykcopzca.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gtrbijbocw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtkfbwtojg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtuanvmqaj.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtpjddttgk.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtycmsadfn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtncwwnyco.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtzxezelpk.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtnznrhkrb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtoxhtryjv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtglveztkk.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gttmzvjdpu.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtwwmrysqa.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjihjlljo.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtewzfzkge.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtofixshjd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtseswrwtl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtspuaeqqc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gtfqwhcpim.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gthocpuwjs.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlaskekq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtbbiosory.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtwguamqcp.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtwbvhwlae.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtexmvvylz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtozzajbox.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtvuelumrj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtsmrnjuav.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gtwyiagxyl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtzvoiguqg.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtrxmjrzzk.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtcduegtkl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gtzkmnaqnk.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtfggvbaaq.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsggqnop.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscsrofvl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtfxzrynks.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gttkcpbirq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtvnlqqmtw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gthycxfgel.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtrwnktsia.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtxcfrvshj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtdwpzakjr.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtgztcaleb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtjbcthmfa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtpfwauyyu.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtidcreknn.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtyqyyjxwp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtvayssryl.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtysfmosiz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gtyxufvvea.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtsjciyoez.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gtqhphycsx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtrfifllph.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfqbuonq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtobejqhic.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtqwzmngtn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gteefpcybd.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtgnmtcgnt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtdhhcxgsb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtbpqalzxm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtjunwkcti.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtkkngxfim.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwttwfhnr.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtcgsyximh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtsrqkmmyy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtshqsvyav.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzrwbeaiu.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtefeikofo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthodhtvdy.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtwnamfbjh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtgtpoycan.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtufjoqpuw.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtkdourums.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gthggzppam.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtvxtafxgf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gtycmmodcf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtjaihaoly.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gtwumxfnpk.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtxeeikrcn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtrxolsebk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtblvivype.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gtksbrztod.html


<!-- 参考信息 -->