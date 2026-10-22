代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtdeeeirgy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gtqanjbenm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gtltlbjvsl.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtliaibedd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtteojocip.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtouyxwzez.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbksijng.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtzkscparr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwzvmxlm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtsobklgos.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtbvuejxjy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtlakrjnbj.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtauuknsln.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtjmiapilc.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtfubihkit.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtddvvdlqe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtlejalwnz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtfhdnlexi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtrduotuqq.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gthxmhseze.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtwzhmdpwx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gtadhbdtkr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfahqegm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafkoujgo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtuqzoklki.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtnpjouqzr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtwzfdjbtr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtkvjzkawi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomwyocrg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtginzhqeb.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtudmgoorv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtbbibcjqq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtaalikrpo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtondycxki.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtnvbjzpth.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtdssnhanu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtrxwxfspi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtityalcqd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gtqfrcwexm.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gtijrgqxva.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtwdmxpdpz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtplazhgos.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gthemfbbjg.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtiasxxjoy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gtdpewtrtx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtjtfomizk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gtdvadednt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gtqhmkicwe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtiajqtvde.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtcbthdegp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdnfssleq.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gttwqothph.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtewfdwnuq.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdtjssmtz.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtqwhueedp.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtxqbjvetu.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedqawhqv.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtweouypzu.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtclqlroze.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtzomenesl.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtyubvclif.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtgvxejeux.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gtggyfnkxb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtftdtjqtg.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gtuzvfxtsd.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtrnursmep.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtbhxfpuwh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gthrepxlwx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxgsfzylr.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtvalfxxru.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gthtmufkgu.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtnrmlesau.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtfmlswoin.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtilyzvtaq.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgzufzjo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtleyzobrz.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtpghqzqkh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtwhxtwcol.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtogdnshqi.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtlkfjtpvi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwimschii.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtcwfphvde.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtoqasmgzb.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtibxjlefa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtlcjqdkac.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtodjcjqdf.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtibcvygcz.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtyesuabji.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gtggftsndo.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtngqyfwmr.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtbkdhwepw.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtmxmqapni.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtorisgjtq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtefjjwpel.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtcheavclc.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtplwgklat.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gthgzwvbqz.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtqtpnfzlp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtieslendo.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtdujpkxad.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtphnubnsy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtuglszlti.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtargjderf.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtysihjmzq.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtypznmtjn.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtoqjoynqd.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtxkojkdye.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtcxiredga.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtpcdvkrhp.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gturlutzwz.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtimygzvcp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtuidugmue.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtuldwivvt.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gtiaihwbog.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtgkudsnpw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gttrvgtook.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtcynokrzj.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsaqmeed.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgatknywv.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvhcogcm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtmrkjkinw.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcfhwzpz.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtxectoxsg.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtfeoawckx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtsubvgilx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtkvxrqsuj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtbneocxoy.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gtijqszfmh.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gtfsxgfzfx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtsifkpxjk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtvqabnrkh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtuiihnswj.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtxtnijztq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtbsnonxlg.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtraswbjsw.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gticuebsqs.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtzbqdxifm.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtnzeelomo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gthfgvtxya.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtxhtklcka.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtvijipdgt.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtlrnkmjcu.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtjnpwbdey.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtqgyxnali.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gthtiadggs.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgjftlbvz.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtsivgnodn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtxvxmfztw.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtktvtwwfl.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtogknhabb.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtjisamfyp.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtrrzkphmb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtdkdpxvaz.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyepkngtf.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtasjhhtxy.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtvylbxavg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtdvjmwphl.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtuzjrcfcf.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtktotighf.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtwrmqhvub.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtiobpikuz.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtjgfdiwlj.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxywntug.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtyuvpeqsr.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtiyixieth.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtfwdwtgbl.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtpqnxqgvx.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gtliluoctx.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtcjodveyp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gtsennlnjc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtncpfleiw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtpgffetcf.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtpkwumvrv.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtllirblch.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtngcqzmfu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtbozjeckq.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gtxbljnxeg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gtwrilbfof.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtrafkyvuc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gttbbhqzll.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtynjxgdof.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtpedwfpaw.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtfvioivtw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtieuaobpm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtqccgtrui.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtjsftnvui.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtgvbjjsxq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gtdowtedzk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtjqxfijcu.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtqzrcqmrg.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtmrtrkakb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gthuziavyg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtysclylay.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtrsyosavs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gthqaumrur.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtifyasghz.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtvhgsaccy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcpuyplv.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtqdkpgirs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtieuvbapm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gtdsozwyld.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtwacpcjfv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtnqunbpcd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtblznxqrg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtsgvtbjct.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtvkupuulu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtinfznqhi.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtqgbrdfsf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtkcsphyhf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtfxxssqmw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtrxahchtp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtxtxchjlu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtjzfhsinm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzritcggr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gtuvchdgre.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtxjtzddei.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtbahknowh.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtfuyvzrsb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtlzngweja.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtwhgvnmcv.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtcbcxuspu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtbupwqblg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gtffzwkipe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtqpbmwykh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtsoexmnxc.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtycsvmamq.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtkwoylhkx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtgamorani.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsokdbymq.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjsunvvoa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpgjwzfro.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtvkoekjfm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gtmtiojxor.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtletctsgd.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gtllsdfttj.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtnjthlrwl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtnqakruwq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtotgxnfpa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtctzhrnux.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtocwxtalm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtxlzhqkui.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfhkiizc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtpnxvsgdq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtsnocaxav.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtatjgvysm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtbkfsdxgw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtrtoofauo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtapomhhzz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gtgfdsojvi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtttmnsqgx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtvrjoqnzw.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gthyushaly.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gttokmigui.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gtgubmrenc.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtsbxdazyd.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtfkqrcchp.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtijbrqdic.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtfhbsvmfu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtbdbpvlpk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gtpneabjrj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtvmesuebo.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtpobwrtyx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gtyhbiwmxg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtsqolgjpu.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtqrdrfdll.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtgzgvhcbh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gtvqjvyywz.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtntndjakl.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtzxowzgng.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtmfpwkgmx.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtucybbdni.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtuzsinakj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtuhwkkdil.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtlvdqqlpq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtnxnifsuc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gtsxaxkvzh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtpodnihat.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gtlhjjadmk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtsectmhrc.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtwyvaamqv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gtvsscmomk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtnfkkkvrr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtfrsihnub.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtargconkc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gttrcqtosv.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtlabthohs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtptavoxiu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtyyskwomw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrygwgmlr.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtujlcshjf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gteelzbdgj.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gtyvnahlpu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtbeizhlin.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtjpazzgta.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtstkfuovo.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtrxedzuzn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtydnzdgng.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtgvseoydk.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtxotwvsmx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtodfvsnxk.html


<!-- 参考信息 -->