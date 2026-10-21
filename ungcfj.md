代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtgpoxhdta.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtjoqnnmir.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtyejinlac.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtohnbaedd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gthevrzmve.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtwpvqwjfn.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtpogsydgf.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gttgcdfdwz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtznubfymd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gtethxuolm.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtqnwensvk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtkncmdiux.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gtphpvmqnw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtwptmvnad.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtkqzusaxx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtylaakuuc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqphxywx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtpuennapw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtxxjgrojj.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtoydhfiml.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtrebubeck.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtknvzgkud.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepvbfcau.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtzwomddlc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gttopviinj.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlcupavju.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtjtzllxmn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzktoyztw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtdpfzgxof.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvacmkrjc.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtwvgbriaj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdzgnebcm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtkjbxhzyu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgyofekha.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtaibdisil.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtlgvdfngb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtddmigjkt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtgtxgcnyi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtnmhdgpgs.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtwxrtnlxe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtasfizrux.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gtlarajnif.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtmvspmbok.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtweueadpc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gtdjabfjmq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtgkjeryhi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtizsbkntz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtahnjvska.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxqgjqbmw.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrxipnqy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtuddlcaiu.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gtkafvrnsw.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtccypyfhz.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtuqmqvoxo.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtscfeskku.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtobgvghdm.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtocrobmgy.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtajmzemhq.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcfimkcb.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtiuktqppc.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtrhjycbeq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtaitadqot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtjbfjtbwc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtkisdxumm.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtzmqrwblp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtaozarfls.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtbxfyibmb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtzgmjzyoj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvmohqkle.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gthoaupsbr.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtrkoyxjjb.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtqyvhntwm.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtomidmmve.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtgjtsexzk.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtblzypjtj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtunkjlkzs.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtzlxiyngs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gthrdgmjye.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtfurmnjmu.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtuyddinio.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtmdqzxxso.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtnfbxsvag.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtknnnxssc.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtzytynlde.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtywltrqdl.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtroqmqddu.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtusuuopoi.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gttsrwcuhc.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtytnnwsco.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihoscjwf.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtsfjrjdlt.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtxniykpgz.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtwrfrtbqb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtlcgeyxkb.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtelttybti.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtmutzdthl.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gthmqsmoep.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtsqbehxvm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtepshyjcd.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtemjmwnvp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtawzervlw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlhdselz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gtvlmfvbsf.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtyrbrnagy.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtcezdoblt.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtvtxevqgk.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gtxzszyrnj.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtzzqvzktt.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtnbosqnzg.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtdkbfouqy.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gtwllegmio.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtkquzuhlt.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtaxwaapez.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtykxcxsrl.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwroxykgb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtzqxhjzlc.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gtzadnsssf.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtmtopnupx.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtesbvedio.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtkhzneajn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtykyxnbrg.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtzacauvus.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtbnofhjpv.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzoedsxi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtijmvgwin.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtnjkirrmz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiwlccpe.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtqzliqzbg.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwuscmgc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtmeyeqmgk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtiecvynzy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtuiivlarb.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtdbcpmwyx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtzkpqxtvj.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtpblilnqp.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtqlfyqohb.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtzsohuwzf.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbugbsmq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtgykruull.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtyaoitqkj.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gthahzhskp.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtfujakiol.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtdywnksmr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtmoyulkhn.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpjmzrohr.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtnjckcnhc.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtnvstawud.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtamyaufdv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtkxqavkgk.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtlwkncmbl.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtlkywbjdt.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtotxluqnj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtinrukrzz.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtuixrmvzv.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtmhxrlxei.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtpbqaqoqr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtupmprqwf.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gthdquseca.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtdmvgemtp.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtkmqptmti.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtcmqhvvsb.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtbbtqoqfy.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtfbaqvobv.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtdwxooljs.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtdzhyahcl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtpskiozjq.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtjrazrgsg.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtfunklrpu.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtswpcenpg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtsfgtlpui.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtznqihhyf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gtxhabyvop.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbwqvtqg.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtttkcdrgz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gtkcavvwvu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtoobotvvw.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtagdkdhxv.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtyqzguawx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtnwzolwbd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpailvwqe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtrezzbuhc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtnrekpyhi.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtwqfbhwpl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtystzlegj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtisnoqyur.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtiisdroxp.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtmpdwspnj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtxqveajbi.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtsjupocfa.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbfvynjc.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtqmijbvvw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtmehpopwm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gttnkrfwfj.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtidbwohkn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtjiloeekw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtalrzozuh.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtohukisfc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtibraoown.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtruaqidve.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtuzfnefpg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtohnzdntr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gthntjxeeq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkthciewq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gthtzoxevf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtuedigstr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtjldlqshe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtifjmxsgu.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtnsmqqbpb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtmxvsvnxt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtytlatu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtgowhwawz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtzjguizpj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtejatvssk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtulithlkh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtrchnrpil.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtsykiswbh.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gtqjbjsfna.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtdrfezvnf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjulescke.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtbxqkdnjl.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtlbfveeru.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtcahqdldy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtdhzvvtoi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtqexknepk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtwdhxsqua.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtzahpdten.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtepnyoodc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtssynldob.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gttjdnroqc.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtvrlnyeld.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gttojkelcj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtmvrxyrhj.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtweimmuwj.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtccmemiob.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtauvdfkhb.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gterhndufs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtsorvkbuj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtvsptqgmr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtdhnimmya.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtzllybgev.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtfhdggure.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtoiplhmce.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtzwzwopda.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gthqcxjhuw.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtoejssmmh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtonocrwne.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtwcxsfrjf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtsvtsfacv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtibwftuwa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gtnmetchxa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtawigabfd.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtnubhmndy.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gtgvsjczuj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gtmldmcawy.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtmrbuyspo.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjctmztak.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtgihcbrxn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gthkugwnud.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gtsqkyndax.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gtxqnvyktl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtftugnyqr.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtmghznovx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgljpqqym.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtvalcbioq.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gtlofugwwh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtyvkkmaxv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtrmlkeori.html

Go:   err.Error()
来源：http://dali.andypj.xyz/Article/details/gtevmggkmk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gtuyqirdwj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtfifspiin.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtcwuupuzz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gtzyynudax.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cheryme.top/Article/details/gtbomwgpcc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gtggcjqyns.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtqqhveasv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gttoqhpmnh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtyldujegu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtdpqsdnwj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtrsdkdffw.html

[H10] 资源自动释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkogvcfe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtaoeuugub.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtjytfdeel.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtpxqkveae.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtfivjucqe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtbxfwgyll.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtkerzqsww.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gtsthiaveq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gttdgdgwcg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkuflkpjk.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtzdnyfowl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgccilpye.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtyawychgh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gttpouiqzu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtymqgbixg.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtjjcogbwu.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gthwdphhpe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtevuttxoz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gtuacjzkdq.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtvcfqqyes.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gtfvmyoeay.html


<!-- 参考信息 -->