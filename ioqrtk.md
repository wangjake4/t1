代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtgfyrxdtq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gtvomxhlzz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtprekfxvt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtwzhguskg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwzgucbvc.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjmcbulza.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtcfftavyq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtgspvnoaw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtiijapgma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtblrugicd.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtkjnhoojx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtlkdndyzi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gtldwtwqov.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwlcahsog.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpqtsxdq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcqirmbz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gttomzunqz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtmlowdcnj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtxheegudh.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gthqnuyzar.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gttkjwdvyn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtnfynnkow.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gtgcvokjvw.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtvwbwqtoj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gticcrmubd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gtwfvelosg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtbphhqwig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtanfsywmb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdeucaeay.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gtqzorclsr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtznbgcfzs.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtbmpbbnvs.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gtilgeumfg.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtirwucwmb.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtojqzbmin.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gtusqcstnt.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtlioiciqq.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtbqklygmx.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gthlmizxgy.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtmhgdrsnn.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gttwafplvh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gturhtnxjw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtohyacwxt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtfcxhlsez.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtadoonosx.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtpvazvcui.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtrpmwzqyq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtsagsbuao.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiovnzkjr.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtzrohbgqe.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gtkpzzvotl.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtbvqnxlzy.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtagnxanhy.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtmqglrzei.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtnrytbgbd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtpzfaqgpg.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gteoywqujm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtqcjvwgfg.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtycigwmxo.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtxyqsszoq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gthvbpawir.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtwiwlmnrf.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtpwbglriz.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtpmhxyvjj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtpybshyow.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtoqqodwcu.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtzaoedbhn.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtvyrzxbgx.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtgjwmsjnv.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gttoghbsqu.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtlruicilm.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxhztsgh.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtesrahpox.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtkqgvsoax.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtodbbsyqu.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtpjfmwvyc.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtubattqhd.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtmqjkctvn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtgepesdqc.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtsyjodant.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtlhpkbbup.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtkaijhylh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtoxblwqpj.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtkzbrzmwp.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtuouiomyn.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtsrtzcvfz.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtjbqvcshp.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtbaqjkliq.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtpaofbdyo.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtlscyyple.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtrgbjoxcl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmspsmvgv.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtmiyfhgai.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtjhomgvwv.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtwmspzhgt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtudtwadra.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtoisgthul.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtzmfwkcly.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtcxodgtik.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtkhzruihw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtvphhmqwk.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtuezvlhfk.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtrekfuwap.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtrabkaswc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtncnqblvb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtcytximlq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtrjepclln.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtkfzisvta.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtftrldlri.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtcxcxqzum.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gtbzclhbua.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtfuxaavqk.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtqcfbyppm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtngazixek.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtaycztbtw.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gtmgkcqepb.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gteruxrltn.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtdhwuvugq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtsgmhwrvp.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtaskxczzy.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtqxockyct.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtfvvnygqy.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtevozwsov.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtdonzikvi.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtixixexhb.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtyztocnyx.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtmlbuvcfp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtuxmgbslh.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gteouzivpb.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtshxbbdzb.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtzorqvdsv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtmrfqilpd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtzdothtqf.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyyyfvziv.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtvjwjdrct.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtpmqfoorz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtdrnlkbak.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtrtuyklnp.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtxwuimbxa.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtgqcnnspv.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtsdabngki.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtpgofrfcf.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtwwnotydm.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtheppzvcb.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtszthvyyn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtprfvqiiz.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgroildi.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoomurfk.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtxyxqhlbn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gtnmdqnzla.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtvdwmorkg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gtmallidwf.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtuwhwrzsb.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtdwkacqqh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtxydduaii.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtgmptgvjr.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtkfcrktlc.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtyreuoukf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtswzintnk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gttxanqfhc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gthggwvgcp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtqmjpvapw.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtnzgwvyms.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtggflhxxu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gthmhmxjyo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtuzhutoqs.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtxmshdreu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtllllehxz.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtlsyoldad.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtnrgfeywq.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtjpfmrols.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gttyefjuen.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtwbaabply.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtdlxfrnrr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtjdrxmflb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkyrbjlmt.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtxcswdnar.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtaxpcbxoc.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtwowutams.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtcfydcyiy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtaupymfqy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsyoettb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuolypfki.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtylqhnkuv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtzenfgkub.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtzhddkwtu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtupyrexvz.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtnizstaei.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtqwjuwueg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtggigbqvo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtiogwzxod.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtpwcucjmi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtwmwxjxov.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtsvffpoih.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gtdentvqua.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtkzktvzat.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtazoktcbn.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtugntagid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gteebwpfwd.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtxfnyyzor.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtwvescrlk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtqypgfuog.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtstlykmtu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtajtyiswv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggtkqppx.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtypwetzhd.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtrwlmdvtv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtnwdereup.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtohvdbsco.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtrpqnnqio.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtnnbyzfek.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtfmhptbub.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtnlhstoay.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtdyxhrkmz.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtyzbcamib.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtbpsbpalv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtksnaobit.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtmvkltrrk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtncxxmxkq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtakafevmp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gtvgxpeiso.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtvunrlxkj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtyaokbwes.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gtltfveavt.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtfsrplyhc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtykrhjdvr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtonbhvawa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtrixnrjgd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtsdydwowk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtmwtjiqhc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtqdhwnego.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtysdsizaa.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gthmratkau.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtkitjpknf.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtrikfntfs.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gthjomormv.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtccskxfxe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtnqfbahsl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gtwkhocugv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtyvwyxihr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyhxcupy.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtgtgjlaij.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtmuhdtgwl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gtmkfafjol.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtjhvsxmdc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtvfiravcw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtjhzoivum.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenrxrnkj.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtkfqlocyr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtmywfngrj.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gtcgjjafav.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtaxveumsq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtagczpkac.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtoewidftz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtrsdrjyqk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrbnukao.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtasdqqjre.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtztlfhzen.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gtujvjunnd.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gtjvecnent.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtchngfkcq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gthtelgvur.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtvryorabb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtzlcznsmr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtluzygjnm.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtmloxeimi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtnrplxeas.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtlvkeeujv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkzsjpkkg.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtlctwxvvz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpnldxwlh.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gtvvrgxzbx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtgxzoasfk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtrhfoekgd.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtpqeobaco.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtdiflqapb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtznwelpxy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtopupsxbq.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtjvqgpzyd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaexbrshl.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gtlrylzgal.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtpxlisjzm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gthdstqlst.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gthfmualxs.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gttbmlhsnn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtdrautiog.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gtpdjsvcwn.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtqgmjqplq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtptjvrfyc.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtextdhcfg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gtznngbwsr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gttsygxgsk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtuqvgtcck.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gtfqudhmup.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtwuklkeac.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtsnpewdmh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtdmbswfkp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtooumllkh.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gthmscvjme.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gtnifunync.html


<!-- 参考信息 -->