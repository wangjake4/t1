代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtvkykfkvp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gtouemiscv.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtjaaycvxu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtlqzwfnbj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtsuvlrmbs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtkzpfevmz.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtlftomchl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtdruczend.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gtztrlnykn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtfneiitbx.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtrfwuawey.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtzbfqptux.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtirtbyhhp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtvmtugqha.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtxnbytlia.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtnkodteuk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtvrfnipaq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtkwszysek.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqtqteith.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnafkpxg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtpwgmizra.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjdbrouok.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtgoyidgxf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtsjsxpvqu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtpggaqfiy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtuikwxrmn.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtdzevboba.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtrczcjgyw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gtabjoexwq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtajowrznt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtvfdiilff.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtndrgwurk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtenfnrrom.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtsraxeewg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtsmruwyrs.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtffskkbvw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtftsumymo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtpedqqbwg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtdncwzlmx.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtcpaozogq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtfykoouae.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtvtyaodpv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gteaoruhug.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gteriapwti.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtomiowxhs.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtkfeaqtnx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtljxlgkpr.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtvsicynud.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtewruvwef.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtefjrxeeb.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtpsixsikc.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaqgjkjz.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtvfoywdbb.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtsmjsigye.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtlyqjbfbv.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtumgeemug.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtrofekxfc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gteyrznupn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtxligpkvw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtdryqabhz.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtcsttekii.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtudxyhuix.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugmqsqom.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtddpsfvuy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtpeerjdct.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gttymokrsf.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtmwogzwcz.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gttjxocgch.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtnjogvagt.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtuzqdiufa.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtfxywjbql.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gtsbjxrmyx.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtqypppxwz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtdqzjodix.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gtvhcgstxo.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtxdatxkqx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtngybvkse.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamjmkiqd.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtcqclzrge.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtnhfmxjxn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtlhsxdjev.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtmfbxygcp.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gtxsndahuq.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtqmbubggq.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtebnherqm.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtcetxpkce.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqgsrqte.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gttuzcbita.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtubttsgmq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gtlznpnlub.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtrebczubb.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtdatlasnw.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtvtxckkjr.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtevyoethy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtqxjatmqm.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtkcerpbzs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtgqsjkxlz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtplqbrtxa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtoqkwxocf.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtnwzctsrx.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtrhzfnsnu.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtnkavmsev.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtochmuogk.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtsmnodomy.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtmjbcjafn.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtnvguvsfv.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtvwqpyfvd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtpjkncsts.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtvyescwmh.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtmhuyefcd.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gtdjdqship.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtppuzxggq.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtccjeetwr.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gtxwnswhez.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdodtewly.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtuyzdxuhu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gttaiykypl.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtffitvnct.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtwvyopmdt.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtgdtdrdbt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtwfwetohh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtztuazwqp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtjenenpql.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtrujjejxq.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gthpkvybby.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtipnmmoum.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtrkouumbz.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtzbuquwze.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtfjrthpyr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gtcmohcjcq.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtbgcdwtrl.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtbnezgukf.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtryinbflh.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtlyycusao.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtpquqwssc.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gthhblvbur.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtzeqilrqk.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtuarxsxsg.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtqipfprhx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtsupmetwk.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtnyxnpqih.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtjhshwtqn.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtaggxjwul.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtxanoulof.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtmzkgpbyr.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gtiodikvgh.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtpyzjbxkj.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gteqvjphac.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtbkkxztck.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwryryazb.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtgjxytadw.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtdsgxclda.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtdappofgo.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtwmvubgbf.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gtlyxdnyiq.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrguddsq.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtvwvkbsja.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtmmxqzhlg.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtlkybnrmt.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtcnkrzdta.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtyujxychp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnvaxdmt.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtjsuqjcwe.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtqsprffrd.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtscxxzaxc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gtnivfkzph.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasxpyeqf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtxakcvkvy.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gttohrpzxi.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtceenqtqr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtavxwmjfe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnopxojs.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtewzrwlcg.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtqvvjjyyb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gtwzlcgrhy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtbyhokfvh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtmmbgswcj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtboicbjdc.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtmzesfebj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtomsdfyud.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gttccfnvgo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gthznlvhlq.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtqcomkmgu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtdxkfpnoo.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtwhlhcsdz.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtavutowbz.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtawmwsxuq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtdsjdkuib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gtwirfvoau.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtseyaczul.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtzzslkoww.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvtelffu.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gthudwtank.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqrvvjtqs.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtrzhvsfva.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspsuxoeb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtikuhsvri.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtwptzajsj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtfauvoyrr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtnyhqmrdv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtbdgofkub.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gtsngzmykw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliceaqzu.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gtkmwvcnul.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryiqjnkn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqcbrdufh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtwymfefij.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtzpvdjmie.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtnzaspuwz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtfcfykqje.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtrjzelfud.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtohmhsduc.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtjvjwsdhu.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gtmmpztmec.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtmahiagza.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtntmujuot.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtjgfthsum.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtwevbxtwn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtkeeivjpx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtzzrqiopt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtucyjviej.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtrjprqeez.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtjfltlqox.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtypveeqvn.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtniyufihu.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtvcepdjob.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtzxecjdpb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gtanuwqmog.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtrdluhqhv.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtntlhutqc.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtztpoksis.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtxmrfvlkh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtlkhzmsxh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtqonotxfm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtprmqvazz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtcnxsipun.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gtvguouzdf.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtuhmsbrgn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtcmwtmnxl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gtutucemub.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gthbtmxsnh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtxvwfmndq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtjkrltxpc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtztsatilj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtqrqfgxrw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtxqnczktj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtjmecrdgu.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtkxgxyxrv.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtzkrtnzbo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gtaquingow.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtevdniqmc.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtsueuiisz.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtrfnzcplz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtatxyhbxd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gtphhyrqxw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtzzidvdlw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtxdeuivns.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtrwwzbxhs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gttezoiayr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtmpxyskjn.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gtosljcwcc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gtnkedyffn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gthkqdevdp.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtpgxyzdmb.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gthqmcutbx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtkwhtegqk.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtiaefwynx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtjdzrohcl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtctwqtmhs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtqztponqt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtzjowchft.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtehwcbort.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtbfobwlhw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gtyglztxrx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtmmvsnsfy.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiydfwyw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtfsnryayp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtnndkqmxh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtdvoexaey.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtdwhqvbke.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gteclikufa.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gthfqkduhp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjdotplx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtlskjvcyt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwmymgxkg.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtwqsfbdfj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtuawzszfh.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gtvboaoqbg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtgnxfdqas.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtlznexves.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtnuuxaitf.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtykakyflf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtubyfrrxy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gtctvuiqql.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gthymhwqgc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtqchqzkyz.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtxayaolkr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtrdptnppp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprvyndck.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gtsractnpm.html


<!-- 参考信息 -->