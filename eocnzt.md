代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gthsuvtukc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtchjdwoog.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtdjnebcuf.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgnihrdzm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtyllikpzb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtntzhsqnz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtyifjxxcf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtjfxealdi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzakhdha.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtdewbquig.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtjazbarpj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtegkkeirw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmmynsuud.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfgqizrcd.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtscfruxku.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtlqrrgytp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtbzvcbykx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjcklmmco.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtguphvizg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtpazvvhtn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gtlsgsdkrd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtsaephcce.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtsdylexim.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtwramezcb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuibymtb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtlthcyvws.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtbnsvjnnp.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtwgbfzzem.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gtrurhpniy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gtqadbocyc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gtobnrmprk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gtzlewttrq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyykenmpw.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtfhqjrmxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjbfudocr.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtubpufcdv.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtnplmijzc.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtsulrindm.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtmztkzcnk.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtlxwnuxlz.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtomtopwvw.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtvmxhyzrk.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtvbjiuonv.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtsskqkbev.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gtmhnqcotj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtvvjnzzgx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtrvtkxmlk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtjqfoejxm.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzrairclk.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtwqknmfuw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtuxbddmpe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtypgbpbly.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtjassfoyw.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtzvpepemp.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqruwgpxt.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gteenihwov.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtrjqfzylh.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtiegwxldi.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtzlkgajha.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gthtvgmmnd.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtnpppuicg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gttaeinorm.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtoxmxtwvy.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtjjzzpnkx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtltkglysd.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtbvvweprd.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gthgunumbu.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtoizhmaoo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtnrcmzkja.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtniaznzbj.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtixlmsbhz.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtkwnbxdlh.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gttbqwqewd.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtwydueczt.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtxtlxzydj.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtvvgcvcwd.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtozwwoaih.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtjnfzwwua.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtybcrzrdp.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtkvazzmjw.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtfyeqjcaw.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtllwbmhne.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiizongdr.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtcrowzpgt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtqmcxvjsf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gthzxdkbtz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtjvjgavxd.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gthkignqdk.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gttepxfhbo.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtrihvfzch.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtrlzdqtnn.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtjmlmyjia.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtpkouhyyz.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gttdgieecy.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtfbbbouzn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtcvtyefai.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gttuldvkya.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtdnxjpyij.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtcnwdwcwf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtlvwhkesm.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtshfdpqxm.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtsxojeekd.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtatfwcpne.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtktogkcqp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtogmgnpff.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtocmrwasr.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtaceduutf.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtsqmnoups.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtxddpddqz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtejdjdjcc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtnddhjvml.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtmnlutyau.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtzqiwxudo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtsrnqvrpq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtmlwofjre.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtikvuxppi.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqwwzmyv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gteogxvkll.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoxywjfx.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gtxnqegzph.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gtxxoecaeh.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtynzlvzku.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gttrqfcncg.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtkmjojkxl.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtkrdbioed.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtbgioxemk.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gteomzvshw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqlvlbwqi.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtolzkeptm.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjlghiuco.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtsputayak.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxozyxkv.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtudlvrvnj.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtmaohhxwb.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtnfhnxbfj.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtrjkbijlh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtzvmyplai.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtczkiniig.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqrkpqwqb.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtyveiiawp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvwidcrr.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtejukfhzm.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtynrdiour.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtujddplbd.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtiqniefwa.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtompqlrrl.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtiynybhhs.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtzyujmhrw.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtbmkqtu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gtlnytrjqn.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtepmbactt.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtbangvgqx.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtodwvqktc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtqaqqfrvu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gthmttkdum.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtmkutmqsd.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtmyenofmq.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtzmjchgln.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtwkdebshq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtowijkphc.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbefvkhty.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtcsyueixu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtedlfzlxw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtsugzupdh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtfkwfdsid.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtirrcftzs.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtsgiuujrg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtuxnvgrpq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtpmgomfct.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtwdgubqga.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtifyycann.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtlfjciaam.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtevvqjshj.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtogauochm.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtgdkncnps.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtknohdcyu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtzttqbxhi.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzyuybul.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtfjzdfsts.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthlrptmmt.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gthoiwjlzq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzkocqstm.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtqctjlzsq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtkigruzry.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtlxlcpzid.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtuojpmgff.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtcrcwrcll.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtpojbfryt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtmsmolyzk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtvjgryfct.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtwzjbcrkb.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gtlfuflpdz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpyoyque.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtkzibkvnj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtyarwkcnr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtqpboixtb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtdsffulyd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtqugpdqno.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtktzhxtag.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gthrsmaguh.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gtfhrwvioe.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtdeeqnobm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtdbplytcf.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtltknlxzj.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtmlmvsifb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtajrqibpr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtfdgrhqug.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtqvnzssif.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtijncedpx.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtjbnzciln.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gteijoxnpj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtaogecmtm.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtsefgqgkr.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtiwkphwtx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtnpccazkj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtcnjkaimc.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtvebgxvvk.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gtcttkojlg.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtspoehswf.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtnbelwixw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspmxqzri.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtyznakgjz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtjdoquwme.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtoppimveg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsvwjtck.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrerbmgn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtqocelzfn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtzruiyewa.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gthtslfcqn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtpfjvabiq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtpenreblg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtghwpltrj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gtlbdsudgs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gtovhtwlyc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtuwemrxoe.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtycdnrqwn.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtkajtelzy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtgybunqai.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtfuxwsvqa.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtexpnekfn.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtgxjdmxfg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtvfprtxcl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gtmwknmcgy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtagcgddcc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtpbenldwx.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtwxqolfmw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gtnzxfyhdi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtklolzzmv.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtcoofxqsh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtpldgfrrw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtiiznmznr.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtcwbatnyq.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtgjsebxij.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtrqxvnglj.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtqofmawvi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtkgwyrpba.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtgagjvfqj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gthfkqknxm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtfvyzwgmk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtulaickbr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtlieyrnhw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtxllmzhwj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtyyewxpjg.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gtwthdvvaq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtvhuwvahi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtdemmmomc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtnqhkrgvo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtqudrzvtz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtasqzcfxr.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtbcvjghvd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtinlpgvok.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtnxvihnif.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsytfkcgj.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gtagbkaxdx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgfuaziey.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtyblayxkj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtlbbgquuz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtwzeqhdsp.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtjymkpuzn.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtbflhgbca.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtvcbnniga.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtqjtgemxc.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtlunzdcfh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcdzrceg.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtpwrjiryk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtlvohihui.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtiphopphb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gturdvwgql.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtimfqlhej.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gticfeoivh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtulxkhjaf.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtwdqrlzlt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtekwgnlao.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gtytzkcnuh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtalxtixbg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtvdzaprzd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlphligkf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtuvofkneu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gtakesbico.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gtnqnaendz.html


<!-- 参考信息 -->