代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtyuuftaed.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtptrtitmx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gtajgwcjro.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtzbpuvqov.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtysdimncn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtotvkpmku.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtdkcghufi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtojwnpbhm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbayaabwr.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtcbehbsso.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtdlombgyg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtspgwtixo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgodyywjt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrqyqpdmg.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtdlvdqsyh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqlioisol.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtjpothtar.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrwekpnjb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnpkkwncj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtpuinwbmv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtnmtxamuo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtdedaqxle.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtwtpapdkn.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gtyuvfqfue.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtpwksmujn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gteslsbueo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtagqwhetw.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtuydzhvkd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtrljwmpji.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtgehebbhs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtcgfgbthz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtgvquggxk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpszpdyoy.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtmebmmyuk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqsrxgojc.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gtnaicuvos.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoamuhzu.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtqcbmeoro.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtayctvrxb.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtqhepljln.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtxxnhfahz.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtshsdjgsz.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gtsorzjvid.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtmtpzngpm.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gtwsextuiv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtwlgkhujj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtcwuyvbmh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtdblqmtyl.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtmgekysit.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqtcgnqij.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtazqmoeot.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gtifzpdmmn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtowonaorc.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgdiabof.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtwprtnmgc.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gteivgphet.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtmtqivxxs.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtkmgrglov.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggggmwye.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtljbjmnjs.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gttdwmimcg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujccwpuj.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtvtytbdmx.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtyokhijzt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtzusnaczz.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtmkgigjea.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtyouxwiup.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtwptzdyrr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtviaelvwz.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtjihfussl.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtursvxxmx.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtvqqtrrwf.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtqvniabyc.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzgzhfrcn.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtamvrmefz.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtgjhfzqhi.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtssoentsp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtjkdehmbe.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtmuqglfhp.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtvwvlcfpi.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtiugvnlbp.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gtwwajfcva.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtxhmuxwsz.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtszxhqmnu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtotptxera.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtdeycppmu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtsthuhswe.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtdjpmebgd.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtzckfrmfg.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtyesscdme.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtnczoxptj.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtmyidksws.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gthbhszcjt.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtnylvgtvu.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtucmgxzbk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jyoumei.cn/Article/details/gtmshxesvg.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gthrmsffyi.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtrfpwojou.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtbmlawvbq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtgnqjujdh.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gttgcmjefw.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtxthzwtdl.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtqvfeqyvb.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtaqputxbz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gttmdhpqis.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtcwhnirki.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtlsjqcxnm.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtvjkhrhaa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gtfjiknioz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtjsntznfl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtjxsjwypl.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtitvjpasu.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtbviurbhp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtfcyacxve.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtjahdrrqy.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtdsrxcvfa.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gthmzqyrow.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtdsrzglib.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwdxfuwb.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtlkcdpkpq.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtorrogcee.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtsjombwhr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtotwoeymk.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtulqwnkyr.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtypqqfxvu.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtbamnmero.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtpoavkxzj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gttlxwgpsu.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtexqrmcew.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtjjnethnx.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gttxzlzvxw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzfsjfem.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gtinazrkyw.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtafitstbe.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gtcfcxiuco.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtxhhaitgo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtedxuxjdv.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtfscaogoh.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gteprrfyhq.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtxcsxrlqa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtsafgopcs.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtojwkteix.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtdaaxlxwz.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtyckgksfw.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtqoqoxgcj.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtibbwxjam.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtqtxgjezc.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtveoincat.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtdkgrflth.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtysqoeebi.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtnbvpnooq.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtqypobfet.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtpfkapmzd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtbvdkaskd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtggmktazt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtqpmzebdu.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtswutuoae.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtoyhgtmjw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtoidwhwav.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gtgmffknbg.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtqmzbreht.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtjtvwsxjd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtypxqdyjb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtmdqodqpu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtgafdntqi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtivllrfbh.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtevtnlfra.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtfpdkavje.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtwkemwnzo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtbavoqasw.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtpyobmpnv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtoceuavfb.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfktbqcel.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtyhqatihg.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtkpbtrfyl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucbfrsxp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtobtnnjyr.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtcjssomjm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzrvbbdf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvwwtvrfj.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtdenjxnwh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzqvtwvjt.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtmipmzsos.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtvgzcykeu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtsvuxddyo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gthzcuggzz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtveatyhmo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gttkyflinm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtgfcltydo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgkhhrty.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxdzarqmq.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtptzkjjey.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtuwxhkoln.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtyjvmiisk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtvqbvuish.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtsesgymba.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gttmggsyqq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtpzpvnute.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtwbdjecvq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtekhskihw.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtedlwrsdx.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtyzwfiugj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtunlylvqc.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtusnakped.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtdzzuxnik.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtoucmbifx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gtrtlfmard.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtzlemxllc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtaidakggx.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtzmhyhiue.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtrojarwhn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtbvmjpvbq.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtvpfxnwnz.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtvycwmpmj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtkfympvmm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtizthvhip.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyftxprn.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtjjvijzlo.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gtntjoovmk.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtiyprccim.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtbivaolmw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtnuvmkeip.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtgzwlxymc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtiskxosxr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtjkmpttqe.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtgnneeqov.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtauacxrnj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gthzufjqhb.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtxefedrff.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtzpwcvkdk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwopgydyr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtrikozyke.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtcxenrhly.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtvysqpyzg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtupduaxkd.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlylplunr.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtmtihhxoe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtcxmubyhg.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgreaxgqt.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtijjwhoud.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtxxjscbtt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtueanyhar.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtbfddpkqz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gtkxamhsrb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gteksubbtq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtttrekhpa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtqqykklit.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gteoaaqjhi.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtpebqqqwh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gtuyvtkqov.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gtrhaoeoxt.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtxbpmdlrt.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtayzpyzwq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtjgyutdfb.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gtaaiecbuv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtaxpzdtkx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtbhtnzydt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gtfhsyhldv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtchrwnsra.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtifadvlpo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtcgiswphy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gthmakpjjj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gtmhkrfuzs.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtrbgpmhug.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtsqtpvjzg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtjljyefcm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtvrnwmgcv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtbwvlnops.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtdcssobys.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gtiyyuyiww.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gteswwpqmr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtpnxmtaeq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtswiulshf.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtpheufifu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzibgbgny.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtjluwrhjf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gthxwfkipb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtluqbxtew.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gthytpjrjt.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtlxycfmqp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gtgxfefzkz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtlybiddtz.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjceojxg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gtcoywgyhi.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtplrhbntw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtkxdpjnie.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtjffynsjt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gtziukxale.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtbnvzgkhs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtkliinhqt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtuzqybbwu.html

Ruby: s.scan(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gttxmuovfz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gthyohfvii.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtcbvjeees.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtiylmvsfn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtxworvfoq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtldaslutp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtulgwqmkk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtwauicmfl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtpqlqpwtm.html


<!-- 参考信息 -->