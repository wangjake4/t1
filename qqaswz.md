代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtsvkvriub.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gtlsaxyuny.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcggzjblx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtdipngxpv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtgqgqgydh.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtapxavtrm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctbeyepd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvsvtohgm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtldvgbedb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmqnnlvl.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtllunoyrv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwbowbmvp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtjkqyxfil.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gthcupvwli.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtszhrvuaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtewizfcba.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtesztabod.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtmuamhpmk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtkpazxsbl.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtnyephhdv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gttrjnxuij.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtmcdmhhkf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtanyhoyex.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtjocwthnx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtdqgzzwps.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtionvgpzx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gtyhckyqfj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtkencgjre.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtijhthtfq.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtrxhzrjsr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtasnvirex.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtwhdytomw.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtztaltfcm.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcxdscdmg.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gttwbqysfb.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtumdfjbzw.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtaasmpvum.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtwamddied.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtmmqaivlh.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtbpltsjhs.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtybkbpecx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtgmapzhax.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtsukvddvs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtuixupxav.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkehcchqt.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtskfwsouk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtnhsvtnpf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtghdifyog.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtgziomoke.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gthlzauddg.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpontfxps.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtslboujpa.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtbkjlocli.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gtshncqjbl.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtzodxycbo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtdwteggym.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gtgliliodv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtljhfpiuz.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtzrggziku.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtzezlxben.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeibwyzz.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gteifmnuai.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtojolhiod.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtmoqxpptz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtbbdoalqr.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gthzbldojd.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtukjqecgc.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtnqnydpfk.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gttsnwngcv.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtnoeunaxj.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjkobwcs.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtnjqkgdqn.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrfojcop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsadnohg.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtkmqlotxq.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtnrouimhz.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjazxcrbg.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtleedxowf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtigsgoixr.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtkbsvvrdg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtuiatcjyt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyjcgtdny.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtkbpnojcz.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtmuskjqji.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtfstbnazq.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtizaulcyv.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtglkpxbxh.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtiielrwqy.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtgaapneiy.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtekbqrcnz.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtsslpfbce.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtbgphcsjk.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gtrbibysqz.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtjjujkprz.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gteidtdlmp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gtsmgpqbin.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqpbclgwn.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtewevnkjp.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtwkemsrti.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gthgufpiae.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtcopwdcgt.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtzttichlv.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtxfwiqlaj.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtdpgmspbi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtnhhkzeqd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtmhmfemsv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtighgzugr.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gtluxqnoju.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtspwsojaw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gtafghhdhr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtfvoggqkf.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtaddwujeq.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtsgixpmdz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtlungjqwv.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtdyaodoxy.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtgarecwdp.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gtnpfryejx.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtnseabodm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmwanqqr.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhqmiouc.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtigszheks.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gtwmxswjfl.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gtthcuutgz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtielvnchv.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtdqispfof.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtddbscspb.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtbrjuquqw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtutjeyxmj.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gtvlpctoqd.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtfutfeaag.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtadcurfrw.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtexzlfkmf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtovdgqqhg.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtfmdivsnj.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtbvxvtwji.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtcsiphzzs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwmmrdim.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtdcnwtaiu.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtisrmiayo.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gtpxabbciu.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtfcbfwrfl.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtxktdcnwa.html

JS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtgbjmsafa.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtiqhrvwqg.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgykqkpuf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtooqdbtxq.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gtmrciyykj.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtvdhazaos.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtdguspogw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtbfoyugnl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gtolcqtrnp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gturweauwx.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtfjjzdnta.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gthlrqrodm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtpigjaukm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gthjkxjpcu.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtlnujxnkc.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gttttqhexh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gtunimjubn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtusqtcemt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtneoifyan.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtnvzjbvtl.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtlyjehwsg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtfurxreve.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtwwxkkazq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtdqpjjuky.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtlkbmgqml.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtxecrpvxc.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtczzugihm.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkkznqwcf.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtwlrebjte.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtkhssgiws.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtxlauustm.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtkndfuekz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtmqaqodjb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkrzsybot.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtrrtdqstq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfutluknn.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtkmhcsgvt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gtmcgpzlnb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtkzwatdse.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtteukxclq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtjfyxqhtm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtnaqsnzwq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtbrdizeli.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxohnghx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtcwuvcydw.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtceeemyjz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtoeyfowxe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtfvysghsw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtcarvngix.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtwknjaqpv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnbougttz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtmfjgwhvr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtqlutauhy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtmkdfzvyf.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtpxrscpyd.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtoohbspxe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtwccafjqq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtmbxnyggv.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtiizpbmpr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtiukokkjq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtfhtqyhwd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtaczqixpi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviqmwdjs.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtxslpnerf.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gtjwkjgizo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtcwkqcval.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gttgrhxkal.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtjhadzmpa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtoucraops.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtywbclext.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtctrcfxoe.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtswyspqge.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gtdsdoafxa.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtmoacsefx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkaabifc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtslsieezp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnfilnjxw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtehgdlnip.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtwifihmew.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtephcpmlb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwhiivuth.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtytcouqjc.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtaryqcguu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtbnubujoh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtcyfrjnyz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtaloyeqlu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtgfczgurp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmocreslh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gthxxrgbhw.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtfpfpihmo.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtfnfbbptx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtyomsolwa.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtvoztapfi.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtnhixoesa.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtxzenaxcj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtrtajxokh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtuphkmvgd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtfmbtyzlc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gthidgwgix.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtbtsvaoci.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtkqenrjcu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqttrutf.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtmwqexvxc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtbnzjosnd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtotcadugx.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtwezfxgfb.html

Ruby: e.message;  e.backtrace
来源：http://dali.quarkkingdee.top/Article/details/gthncyejti.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtfdfltnew.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtntcbomef.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gthbsmmahj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtdpynerdw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gttpfuupcw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtzxqrlvha.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtcpnqrjhi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtwffiefzc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gtauvhbzqn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtnlkipxoq.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtojmhjppt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtlbplkajs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtvoybyjlk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtdikyrovp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtjuwxwxyj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzrxbpeo.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtfwrfesxu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.c1oappe.top/Article/details/gtumfpbzms.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtotdogzbz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqnzecjeo.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtugcjipjm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtieapuwfd.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gtkzvapxcw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gttphzaeqh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gtgiecixlr.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtggtufphj.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtkbsjcqmr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gtouhsngnx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gtrlndsqwb.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaixbzyef.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtwhjyofak.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gtljzyttkv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtdgffqpsr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gtvmfvljqp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtsuapxouq.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipwpmtxo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gthrhubdtp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtwujgmwqn.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtivhzsjuu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtkldimqip.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtofytzbqh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gthfpgtyxw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhlrtgvq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtzrchfpeo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtbrhmjebk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtgqdmzirw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gtgsrrmutx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gthgvifeow.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlsfueuo.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbhdyjzf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gtuiwoxmvn.html


<!-- 参考信息 -->