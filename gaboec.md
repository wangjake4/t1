代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2qtjtlhwf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2jyavwmbk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwbufffd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gt2hebmpjhs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2ghlzfets.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gt2njafhpdk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dscglghd.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2sjeyzwmk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gt2ldergeip.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gt2qqnoalub.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gt2eeljmgwz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfntclzb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2etuxzebk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2onfinbuz.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2byvnelln.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2vvzxfmmo.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gt2qscoltml.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2fbewidvq.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2xgampljp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gt2xvyfslay.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2ggqkihie.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2eluopnic.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gt2siohfplr.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2vwyehhqj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gt2dhthzjum.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2zbbgxkqz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2eibatdub.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2palbobed.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2vjxeyuby.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ftjvbwoz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gt2ucacfamv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2qmtjcodb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2alisqagd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2xkogsjst.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2vialavub.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2qxfyvljb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2axvuiuhm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2nvzeyzuq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2llskjdek.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxkjweeg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gt2vhbpleno.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2gytlchds.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gt2ufiwmqcd.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gt2adlpohfb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gt2lttgkvct.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gt2ckmifwds.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gt2jqqmqhze.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2qidqcpav.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gt2hmlwuevo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gt2rezumsqa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdsmizys.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gt2ieidhplo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2zmflnmuk.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gt2iiwmljoh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fssgxlxn.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2givjrqvc.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2tbmwickd.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gt2tnsoqkpi.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2igutrfij.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gt2dlcihnjx.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2imlkbyxc.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gt2jrxluuam.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gt2ithrugzi.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gt2fzotdfmk.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gt2wfkdjbhg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gt2wwczedit.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gt2tpzdpqsp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khdaoqhm.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gt2xljfarzk.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2raowvhdx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gt2ovzususs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gt2mqskuxjl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2pwgjxaqo.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2sqkdcxup.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rommesob.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2dolzysms.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2trfxcgot.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2lfssbmip.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2qlzswofs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2kypbjqbs.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypvfwpxy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxcnfvyz.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2lljtecrj.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gt2hnyuibfs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ggbgtmhn.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dbvhuemo.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2ymgjwdal.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ofvgnlpj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydoadmpp.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2fbtidwva.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyvsjbwq.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gt2zkfvkiib.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gt2ygilrbft.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2jqqzzdpz.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2zrvuwgkv.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhzedico.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2vyehlnsu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gt2durlndvq.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gt2xppyxjsx.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gt2pmdekkcs.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2nfjczyrp.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gt2wrociyis.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgpyniiz.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2rqudxsyb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2tfhcunmm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2knwfbvkw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gt2gnqtevua.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcqpjtms.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2hodqgdfn.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2daqhaufw.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gt2jvsxcffx.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gt2mgfqqesa.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqdsxmhx.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2osgxrhju.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2fujdcaih.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gt2uiukyeme.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkoxsyve.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gt2plffqqbo.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gt2ijjtymen.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gt2xhoinygn.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2mfixgkfo.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcqstreh.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2sdenhlwz.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hdkqzcll.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gt2yuumacyp.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2vidnnhcm.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gt2drliizvr.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gt2ferycxdm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gt2jzrtqnnk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gt2agucdusb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gt2mypbuypt.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gt2siolztuc.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gt2jywctyre.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uncgjonr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2nneuwjdc.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2jfjzpgtb.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzswbovf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gt2wwueabji.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrlkumpi.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gt2pmyrrosb.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gt2jnezawek.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gt2kacpptai.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gt2izeorugj.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2vzotozaw.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2zthzwlbn.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejbrixkz.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gt2ngvhcuuy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyxaqyqv.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gt2fyewkfkk.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2qqypclkm.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2goeovnaq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2ipptjytb.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gt2npyyajqy.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gt2jgyknaer.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gt2prxyjdak.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2mzpsilag.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2gjsypjbd.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2egfnghpw.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2gmvvsqrp.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2wdfgxipf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2yiyealwh.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2udqvmhtd.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2axbmnkvc.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gt2wsrqfapd.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkdmbxat.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2qtxwnywi.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2qmscword.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2bpjovbhv.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2iqjvgtgb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2zokdbpez.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gt2wsrozlzk.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gt2wcpgfucf.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gt2xjyuxogn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2cdgeygcp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2uevvrqtz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gt2ehpvgjka.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gt2exwlrgiv.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2rowzemvj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2iqhqbnfn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gt2ixvmufpv.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gt2ricedjtn.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gt2cpstnokc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2lwohkvjv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gt2wxvaxyup.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gt2mfsdprbs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2zfrmahsr.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gt2oambsywi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2essrzwpt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkuemehb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gt2lmcdzydr.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gt2ukiziity.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gt2eyqyknnh.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlxkjhoj.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2ihxcpgpw.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2vwdoakmq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gt2ogaqgxps.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2irlhoceh.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gt2loiapclx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2zawaoijk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2tssjgtou.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2yreohtzz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2gesebari.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gt2rbuxhspo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2zprikyrq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2qpysbqfq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2ertmtyou.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnfnrqqd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2eitrcjih.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2paqcbjvn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2sdvqkake.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gt2lsxbjtmk.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2uzcoavxc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gt2jjhjyuid.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2dtpljacp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2rayaapzk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2lhurevql.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzmzdgbg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gt2apdhjdmy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gt2ainyvcgc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2wbctpwxy.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gt2cwizlnpi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gt2ehaxucit.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2ejsbdels.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2raegxdri.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avpfsdqg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2nlmqqxam.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gt2kaoglfwk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2ugdspujz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2cqzjksfw.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpsnljqz.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2oihilikc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2atctireb.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2rzrrtrbi.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2ewgovnur.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2amwhunle.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gt2dufycoad.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gt2nqmejupt.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gt2rxnuijii.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gt2doxhnygp.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2jumkefvz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gt2xtrmrubo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2eywwenbv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2yvlehdgf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gt2zuqycaqn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2cocxtsbz.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gt2uvlihnta.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gt2jlvwnqsq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgezaify.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gt2osxfpbhq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2xzrqeroh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2zqsmqmvw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2usslhtux.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2rvviqong.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gt2vfkpjhbk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gt2fbmryilc.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2hizapzhh.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gt2ufnqshwd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gt2qribgzbl.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2kpfpmhiv.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2sqjgjutm.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2ojxdypbj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gt2ryznafnm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gt2qybqeunv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2sxmyvpqs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2finyjfpn.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2uxunfsxu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gt2btknmbvn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gt2jiewmxcs.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gt2tmcsordq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gt2jxhjfpzs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gt2pipnpabb.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gt2zlosgzvl.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gt2zqxxhcyi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daeuhvlv.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gt2ysqjamqj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gt2hpfngpxm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gt2mdahhlfi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gt2ebrnuwbb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2uwdgcytt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gt2gqronnrd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gt2ydhhbaup.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gt2tdbrutwz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gt2cbqhvkxs.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gt2wwmilmmk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gt2brskjwkt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gt2dkdbfpoz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2mmvmivlr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2xgasiqou.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gt2enaqpikk.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gt2xkcffcvy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2txuexjtn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2fcestpry.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2rygxtryg.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gt2jwihafet.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2itouvnkf.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gt2suoxpsck.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2pigplokq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2fbwsnphk.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2efgoydjt.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2uzcnusvg.html


<!-- 参考信息 -->