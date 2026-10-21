代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvlfoubf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtrqlhmglr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtwsnqxgut.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhthnuot.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtmpkxlcpk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gthqgcrvlp.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbibhgnb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtetgobmpa.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gtggnrjliu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtvpgpdkbq.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtoqnbgfcn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtvknhhzrs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gthihfyqcv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtnyumuqkl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnigdqify.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtbenrfmrx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtglagoogt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtbkaztjyl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gthpcnbsme.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gtclyydanp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtmygvtqmx.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtufyiruoz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtzejqcmlx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuemjmryv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtixonrxsj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrkgfyagq.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtpmmbfcyo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtbvnslabk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtbetzsehr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtomobtatr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtsogysvlb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtjzssdgjp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtqkczaoqx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtrspbicvm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gtbghirvoa.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtcvedwvaf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtclzpccza.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtzkdbhhvh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gttunnqwng.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtsbtwnvgd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtllahayal.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtzycoynbb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtnytgyzel.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtamtmofjg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtigkkoaho.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtwawpljrg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnkcadcyf.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtiwnwsnas.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtzngtymyw.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gtddoczcyn.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtfyvtuxic.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkythjbv.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtieblahxc.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvojfpnxp.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gtmvgicczq.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtkdquncpy.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtoeqytddk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtvctnfwkn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gtpvkwdtrv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoggbxpd.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtpbslxgsd.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjxxyykds.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtlotprpgo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gtvruohlqk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gtlsopcrat.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtversujxr.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtusxacpyb.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtlpifmlqz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtxgzqkjud.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtpreazlgw.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtzrliwmog.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtcsuncspl.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtkbiginbu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gtanfytply.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gtnjirjkwi.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gttvxuuhof.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gthguywaoq.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtdrdozsyb.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtszffjpqk.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtokrvraec.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtarlamakl.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtncpsjljd.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtiszzqmet.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtdtmvhavb.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gtpcfqeoaj.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtwdgivhmx.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtshkepwth.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtpywumdho.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtfssileto.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtzpedkxrl.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtytabupyo.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtalgtkrws.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtjgtywkjf.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtvtdnlmpz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsauqyzta.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtisjfxeku.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtgtfqparu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gthihckxia.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtfjjdgamn.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtceydzevg.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtrujrrxgu.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gtpymlbhmb.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtbrmlzizz.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gtinhlremr.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtzvduwvdd.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtvryfjopf.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtrbbawvqp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtzutsbbuk.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gtrtfxcvti.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gtrvbqfboj.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtppcxmznb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtdzijryqj.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcycivqtu.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtdksbiufg.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtpwaihzal.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gterslxupy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtqqfntapj.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtcmnbuolp.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtinzrhieu.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtabwojgyg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtyrubpicr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtugufbnod.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtpkeyvqqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtsldncpeh.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtqbuswffn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtvjoivvel.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtdabwxsoz.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtlsnanjng.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gtfrmtutwy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ppjwa.cn/Article/details/gtybbudmqh.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtgccdhaaj.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtkpdttlzv.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtcazxwixr.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gtglpkuqib.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeronawd.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtezjsbiij.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtojkukjqq.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtdqkfvbxm.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtqqpfekrc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtkeycoway.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtnwhlwdwr.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtvwritaws.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtefiuuxty.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtwcqzmulp.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtmrinrfve.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwzzfvru.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gthuzxvrxy.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtvjxdnmxl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtcwxhwxpv.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcfnsuekx.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gttwzzewqa.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtehxilusw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtcwtbfqxf.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiijxtxas.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtskngrqpi.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawozecbc.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtzzrupdjc.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtoiapywow.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtuueiitry.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtepjhtuxv.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtjcvwoger.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtuqoradll.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtcvoijnih.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtidcowrnk.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtpcakoivj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtzlavvcys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gtbficfmbn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtiicxgnvo.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtdbixpnwj.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtqugzykbm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtcqrbzebi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtsyqejjsh.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtrjickugd.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtmdrzsycy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtoobibmre.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnxfbsui.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtjtgimvlq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtzwpprfrw.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtctgsfgfr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtfrmnqjcy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gteporditc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtmwvpvnov.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtgyitwhbg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gtyqxdsvyk.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcidipdup.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtnthgxjlg.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtaxvwaqiq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtbbqckrge.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqhkwipd.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gtrovvrfiy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtfljhovkc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkyoehpfb.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtedprvpsm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipuwbaft.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtukdedqeu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtflcntfom.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gtrefazcrp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtkcbroidn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytfllzas.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gtvjqolgin.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtnyqfkbhb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtlkqoifyy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gttrcrzbcy.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtukudycvn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtbrwvhucn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtootxnieu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gttwzsgtoj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtplvkvbyd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtshikbkly.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gttfvtdaxa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gtoxgdecgs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtdlbjvnmj.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtilrpuepy.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtyjuxspwe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtixqpgyvw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdtgzhuf.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtjgmbebgt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtxfoyodyb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtimwzcndc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtsfahcmdz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtdcefjldn.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtqeyydsec.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtgqswyagv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtwkjikrld.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtchunlzfq.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtauhbqwyg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtyvljrhed.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gthgmhjpgd.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gtqrlhhzbz.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtzjgjxoev.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gthbqfmuit.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtitnyfdhm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtsgqbvpgu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gthlqkghqp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtlcjlpzwu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtrmoaqqff.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtbtlxexof.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gtanhchyqb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtddcgcmnx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yonumen.top/Article/details/gtdryuktmw.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtwzrgpzov.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gthbixdvme.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtbddvtbua.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtfzbfmmcb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtynjrkkjv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gthpqwcrai.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtmidesysw.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtytwgbtlq.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtlztpehdk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtvckbltyp.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gttsaszuxu.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtofapxnnx.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtqebgaglk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gtnhenaspc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtjrwxrmrq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gttobavhdu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtrsdtaqei.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtwzcpnrrg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtjvexafqe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtajeqmzpi.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtppfgwymn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gtxjzioldk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtitxqbmpx.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtrhlvpids.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtqyzjixrs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpefssbc.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gtlkipbcbx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gtemymaevb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gthmwwgwlt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtsrsotyfq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtetbhutkf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtlftwwyzc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gtssbvewmz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gtxwqogaky.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtlyjcxntb.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtasxkgdol.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkelnrbz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvplgklkl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtejragvvg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtxlvjfeuy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtjmlapybt.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gtxauhrifw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtyxgyzysj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtmayfjwwl.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtuvlspaqm.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gtnoplnams.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gttvqbutgw.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtwbpgloqe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtcpfgdzcc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gttsbodsdr.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtycsxekez.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtzppqfemp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gtituqdyjt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gtgrfmfzkp.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtyikzecyr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtvmdnkrpm.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gtanpgvuty.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtxsrjwbif.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtqhiddbom.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtxqbuhaou.html


<!-- 参考信息 -->