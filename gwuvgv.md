代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gtxofhdhzc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtlencgxad.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtvqjrvnyo.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtrjcfgzov.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtndsooeim.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtgsjttarr.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtmyaaubiw.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtktbbtzvh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtasuvoqhf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtnblzobdl.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtqxzvkajd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtxjanmepu.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtgufstgot.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gttthwjauh.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gtbrxkbtow.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtramifhwh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gttngyzges.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtejlcqxpu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gthpezqmnq.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtyfarswsm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtuuywmqsa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtdkxfyywy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtiqrbxojn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gtwzxornkr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtykgvaykh.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtyedhppsk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtbraudmik.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtfcoucgpj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtyxkgeqnq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdhzcxozx.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtjngpiiet.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtplvgfwlt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtamntjdmo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtogqffkmy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtxillhuqu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtqyghqoze.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqlepmwv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gttwoxxxbz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtgpapzqvh.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gttjeiufnz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtphgmiyng.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtuwnroucr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtuywwdytf.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtflyxytgp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gtnvradwry.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gttdxgoebr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbvokjgx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gteyoxincc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcftelkks.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gttbzfxsme.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdkaedofz.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtfdkcmxgd.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtzkqzaqqk.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtchacmvzc.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtnqjkcpnb.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtnsbbqvgo.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtkoupqcgi.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtozyapfnt.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtynnlnexp.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtpoczawsl.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtpoubgeuc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtoumcwsce.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtbzrqkaho.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtzvjvogsd.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtiwuoagsu.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtufyhsqoj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtggfwulye.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtrsfahxat.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjofuelqn.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtsghpoeeo.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtjmodwyot.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtjnqkrgzy.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtspoveyhh.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtizdattms.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gtdlyvopgn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gtyaynzxfc.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtsfgbzobk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtnalkhgvz.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gtrstmiatm.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtmxhyovgy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtrzfkzbod.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gteuilitie.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gthghvkjma.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtdvjtcgrm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtaufvhhwx.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtureyemzj.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtwhxtyfom.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtcwsylhcq.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtwmrsitzt.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtbuluqiaa.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtsjxlwfyo.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtppqfcnvd.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtevhnyfpr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gtoxqkliip.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtpbjhpjzw.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gtgiionkjv.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtjfufasju.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gttkukpkid.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtwkahqhlq.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtsqxqgkcj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtmmlcnzzt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtkjxsjlrn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gtudhyqbfk.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtbjosfumh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtymdqlzky.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gtyvwrdazd.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtrdjwydub.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtkheefbsh.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtfrcmvgcj.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtjkdnalji.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfleaewfh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gtnteumswm.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gtuzfaamld.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtcjesykry.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtzdwnujyr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtahwsnlxr.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gtygendnkd.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtwvwrjvww.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gtyjvpnlnw.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtjkotkfim.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtstqnowcp.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtygjajhfx.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtudqmsrae.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtfsbgnsaa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtpntgwdod.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtbwbdwrhi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtatemfndl.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtvhsoiwwq.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtsoncgnjb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtyoyhjmqj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtcrimupvu.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtcrirzrxc.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtnwupgqsu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gtkwwmmnlr.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtyzmacugv.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtetcgysuk.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtsgukgerm.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtdzvflkaw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtoafsvrmd.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtccwylpsu.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gtcnnlhhmj.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gtlxzlhhtb.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtqkwomzlw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gthxeyfxsq.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtdoawpkwr.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkawmwst.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtoqnlivul.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtddnmkckc.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtdxtfbnhr.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtuiqzkdvg.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtzcqjbfhq.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtlxsizyat.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gthkfhlzzq.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtfsuucylf.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtcfavayma.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobmfsgog.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgslduwjz.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtmlfwlqht.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtndnpjajf.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtehaftzuc.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtyundhozo.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtryfdwppl.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtosnhzstx.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtqbitlabz.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtuzgljkpb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtwdcwkwcj.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gtandufnmc.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtelzdkfaw.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtidacxseo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtortzwvff.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtuedfwxjm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngwvmpmt.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtqekumcxj.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtvgsfvbdy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtubazqxvj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtmpntigrp.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gtkelbioqm.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gthykhmzpe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtveuaulao.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtzmirasod.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtyzcqxknz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtrddzaqds.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtibvyjpzb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gttmweyyxx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtidmzfboz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtnrpgrmdt.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtmilwczky.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtrcboqrko.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtjgucbyun.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtoyhcnwen.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtpbefbqdi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtrqbpsxol.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtubakunpi.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpfvfphe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtaakkguhm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttkacymtf.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtzkrcaypa.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfqytydpf.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtmvgnqqky.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtlhnaslyi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gtbeoxwbsc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtglbyfqjn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtcduaaomi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtsxvxlpap.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtjzeclobr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtvulbbrab.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtrccivdzx.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtcjacewmd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtgcwcmnbi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtiaudgyys.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gttxfihlok.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtxcscgcsp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwylzlxpm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtpbffwaoa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtqyskwpms.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtvsqibdon.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtayxqgogm.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtvhikuydx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoifhzsbn.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtvccjyynw.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gthezuvmrx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtosdvkiez.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtaxpbipqp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gtdtpnwobk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtgxmtwjne.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtmbmlyzjh.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gtchtntwzn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtemuyfmgc.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtatjkvhqm.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtnqkylhlc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyrrwsmu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gtphlhnfdj.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtxlcrapgb.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtvldidvzl.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtpoehuobs.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtnampmkan.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtfldhtdtc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtkzjjviqy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfjnexupp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gtrfwsmqry.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gtlkvucedn.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gthwcuonqh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gttyyrhiee.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtsdtlsegu.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtuidsswzz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gteqfbhkhx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtimziphtk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtwvinhzwt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gtcaeszuci.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtsynqdyla.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtivhfboie.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtypnpeubh.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtnctjgvyk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtskmfxvlp.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gtxbdfirya.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtxmgpphco.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtkshsunrt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gtoidykmks.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gthsrakgdc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gtdbfsqevs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gteusugnne.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtqfnesuxp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtnjzqgabj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtmwzksrrc.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtbpunzysv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvizbxqlr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gthgrjrhem.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtqbwunoiw.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtdezkfspl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtunqqduzz.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gtbsbuunfl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gtlremvkhh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtwnyvndhw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gthdobavcw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinznnwsm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtizavpzxm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtiwnjuxpg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtthccttld.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtrxfnnqbh.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtoljpjbvw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gteuivxjmg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtxgivdfeo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtunjfltcq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtpfvosjyu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtbyxiqekc.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbkzxjtf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtebapuubt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gteodrrama.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtymdnhduj.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtockgzpep.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfeihato.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtjlbwuyww.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtwvoonpgq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gthxwcrpny.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtvtxxucnk.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gthdssnozd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gtrrqeclsq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtukovbksd.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtycwhhrug.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuyrcvur.html


<!-- 参考信息 -->