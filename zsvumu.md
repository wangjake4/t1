代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gthiteqmfz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gteidincnj.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtokwgkvrq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtdfimpwdn.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtalmxkpfx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtkdfsmeiu.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtfhurvfel.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtiiaqjkma.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtfzvoqlye.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtclzmgbin.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtzrxjfxcr.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtklwhmwlo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtrqplpqga.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gtqafyjqme.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtgdoowzsr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtdwtpklut.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnfxuckpg.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqyxcqgqf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtxmhwstgt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtnajqlekk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtszdimnhr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtrkgrrwnu.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtpomnkseg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtsufutvxn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtdztygabq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtezeambtz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gttwcfokbl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtrhzmcidy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gtiozkzrno.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtuppuamef.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtztsyoylf.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtzfgavbbl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtfazgurni.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtwqdtadkz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtboptmwnu.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gtiyfmwnjn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gtjpttxyxq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtdadeiatt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtwjeudxgo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gtliqndhkx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtodqvealy.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtybpcdoej.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtpjnelmlv.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gtkhyzwoex.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtzyywqfwc.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtvxyqfqjw.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtgkbjataj.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzvpdwdx.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtbtvqmkmf.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtsbvxixfv.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttasqxgcm.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtgmmeozzc.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gtszbfydia.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtsqxraaoo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbkfszpza.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtagwrpnhl.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynwwyhyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtorcuebhp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtygmpjpyw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtvaverlsd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gtzashmajt.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtxdybkaft.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtxplbvwvr.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtyqjchidd.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtfiwedmxv.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtujdknsjj.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtevtrqzur.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtxsuxubqv.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtagbiybhn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtckfpmyfp.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmszpaycx.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtuisdymla.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtnqpyhkwm.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtoojkvnjj.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtsxvjgkjc.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtxdmfnzry.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gttxljrtfg.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gttekwsivq.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gtgkqhkwpt.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gttozhwazu.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtvuzhekmx.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtbnnketqq.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtgwavgrjy.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtinlolizh.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gthpipjxwk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtfvgsjize.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gtbnvjktog.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlocwukgl.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtqjfmyozl.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtxonojkht.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtwecnnfpv.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtgvcbdkmq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtyjhllpfa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtufejnftr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtkkalnzyt.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtbokkdhcu.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gthvhysxyo.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gtbrpzweug.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtjjuyiysq.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtrdjwuziw.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtlgwuiijs.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtyratflir.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtgteoqrex.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtmzgkikjr.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtkzhpbebw.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtlymvmdlj.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtcklxtpwv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtpritbhba.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhqhpmor.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gtkmzegzoc.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtrwnzczzu.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfwyxudnr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtmynclufo.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxvxogvd.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtznfpqinm.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtiraauuwx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtrpwlalju.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzczvwvtl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gtkckesoet.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtuaaoxkbg.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gthslpaowq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtjgdkhedo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gtivufvsla.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtyzbcsytt.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtmnanwzbc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtsmmygdaq.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtabxgaqih.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtljwnciuz.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtxshnyexr.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtrnvtziyt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtcggsduks.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpbklapm.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtemwihluv.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtfqdvkocn.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtqzmnfvle.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxgvrywze.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtbsxqldxg.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtutziogvk.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gttgmgismp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtfirxlavt.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gtrtyehtsf.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtodhxbsuk.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtynfzopzf.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtztskmsog.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtleakwupf.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtnjihpmol.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtlfrdfpji.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtucexxtpa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtprzeutsi.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtobxqtqem.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtqefvvhen.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlgqanyt.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gttgfigeky.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtuezleotg.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtdiyjrdce.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtewmwnwkp.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtmwbwxwpz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gttgfqzfpt.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gttbntoqpm.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtpmptsrum.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gttphvtdsu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtrsnyyudn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtfgkodwqz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtdpyntnva.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqabbbuvm.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtijbkaiuz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtdagyqaab.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gtukrawveu.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtzgsbcwqg.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gtuarbcxmd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gteewczsyg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtpmqbfjgb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtzuoqdyfx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtvkqgpamw.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtqcemoceg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtziwkvpik.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gtdijyygpm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtbazjjihu.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gteekxydad.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtfcbrocsc.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtijqrrasm.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtssjacxqa.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtyuerhqpm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtdkvcrqhi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtlswexspa.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gtajitlmow.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtpdyrapfp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttcffrpgw.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtxlxppiyx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxashjohs.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtizggvcct.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtxhnhwinp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtjswqrcau.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfausbpvz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtxcrumdmt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtzjhatpci.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gttbykhufr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtlfmhxuht.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtsbndhkxu.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtibrzlpoy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtfxwbfzyt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtuypsyzlo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfiiaisj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtqteqydtn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtylkqhcaw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtpcbrflcs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gtmqkgntex.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtodrdlgom.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtqofdrtbm.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtzzahlkbv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtgmewoozb.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtqyflpill.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtgwmfrzri.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtwaavayzo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gteumnqcuw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gtdixejjlw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtkwgkrdzp.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtwaxswcpy.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtacrfupzo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzlavltly.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtwcczihkb.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtcuhopiyo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtafbchihs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gtmxfaxaww.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtsmltbtvb.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkspjyrhm.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtwfpgwlvw.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtauhtarey.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtagmsayro.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtpqkvdrvu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtfqqzvpkd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwizpaoqa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwkdxpwe.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtuxeyavie.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtwdeuukih.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtplvjtfgv.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gtvdpzktnt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtsslmbrwi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtkopwqhnh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtftvzhjxx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtflspcvxc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtqlmqwvtu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtcqetdxtq.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtmwymkbwc.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtamxfseii.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtcnylhnlo.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtfhnbkepz.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtzkbqfsqv.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtboxadvuy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gthqhflfej.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtnbckskrf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtxaslztpl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtuumbmjfh.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtboukibco.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gtrtqznjbz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtjezbdrvt.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtegbtqbdb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtpbwaxgqn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gthvyuxjgp.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gtrpkahdxy.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gtvynusnuz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtejadxglc.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtpunfjrss.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtocoatitn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtjuhnsksu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtxxtkeexa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtjhxrarhw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtblqojfeg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtwokuusuw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjbkzxxe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gtbhadvdyj.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtioixtanr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtvjichnmv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gtmujlirbm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gttcwwsixb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtbkydloyj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtkgpgadrr.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gtpitxefgr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtkfmqgblr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtskgdkfwi.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpmgwglmy.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gtxsxwlqwy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanthdjkv.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtuqhnzicw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtfkihreuw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtjtxkcynk.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtikjifaxr.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydlbruol.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtkslutqom.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtdjsmjkrp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtbetjryyv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtqkgtoocy.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtssbgbzfm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtwbmvzrxx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gtypthtvbi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gtpznlmoms.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtikpeuvyq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtjxxxwfea.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtntebrhxx.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtosemlwso.html


<!-- 参考信息 -->