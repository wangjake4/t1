代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtewdmhuyb.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmzjrxymw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtxyqymsyx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtkuousasu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgiubyhlr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtrwicfycb.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthtmmbljn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtthehyxae.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtbalfklzg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdhamdctf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtxvqoaunj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtiunglqlu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtrtaaatja.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrlsvipjy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gtirgyrgpc.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtkvshujjw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gtxmppmfsi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtasptxsmn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtvelmopup.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtvflgktny.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gtnpxdmsoz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gtvryxnewy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtagmyygxt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuzifyfs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbnbcnvfy.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtgqnxkmzf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtckjdagxw.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gtwnhqrzvb.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gtfzneasco.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtpgculsnn.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtpcxouxzh.html

TS:   class User { name: string = ""; }
来源：http://dali.bjfxy.top/Article/details/gtghwyqgcw.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtgemfwozr.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtlzzlleib.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtjfergvsw.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtcgqvepkz.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtofedluck.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtfgjzslzl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgwryszyd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtohocxirv.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtvdlmpuih.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtiejgekkw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtttzvlrdt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtmkndrrzo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtmtrjxwdo.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtjccflgmr.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdpqkpbp.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtywkyfzgp.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtmdowlmez.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtsonlsihr.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtvlkmmhzx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gteuqwjiwj.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtkutxskqp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gteysqpbqt.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtclfzgvwf.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtvimhjnjg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtlkcvfhnc.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtfvlxdhfm.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtdpyrscrw.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtppggccjk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtnburphsw.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtzyebcdut.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtecabcpqs.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtzvmirggf.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglrmajri.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtsejelmme.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtqqtbwial.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtwesjguui.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtogimyewg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gtgmufyoes.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtwrdbdccg.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtdvtjwptm.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtxjivdadl.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gtcxajopyv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtrwidlgsw.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzbgqzyvb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtnddbgoxj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjkwtzhe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtaxoninod.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtkjpiqhpe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtsxpneiha.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtjcpgzpfs.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtyigczscp.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtrhpntzjb.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtagfegiol.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtzxkjktfc.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtlytveynn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gtwxfnqufs.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gtwkzatjjh.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtcdxennay.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtqqkbtqwu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtaxldvuut.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gteihbxhbe.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtccybaseh.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtbuzucglt.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtnutedazc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gtablfsxyf.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtffxuayxu.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtskyuvhqh.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtdmojbuxt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtlkwwugmq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtuuqmhito.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtetkedzzu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtcjnispbr.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtblggxmjt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtlwjttrzc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtztavbvru.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkbhxvjo.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtwehnhvmx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtrpoozgvr.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtvflwjcti.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtaihzurus.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtrclimqpm.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtjxonuowh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gtavczltoo.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtdzgfworm.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtqduozyzc.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gteucaptrr.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtpkoovtxz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtoaugalbq.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gttaaedyqp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtpeoeseau.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtuuzutbfn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtwlypfeuu.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtdkboxdes.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtvbgeutml.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtsxqavblp.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtnjlzjbvd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtthqukklw.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrhhxktp.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtbsxlnipl.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtcqncszfo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtdmvhiqbu.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtwzzjkuul.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtmedzrwmw.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtgvrlfwze.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtqlizfsjj.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtcsuqlcfg.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtwadffcil.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtuaosxlpo.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtiyftafzl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtyelklqpi.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtyyxvtzos.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtaxreyhou.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtetsyflbz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtbljmqibv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtmvmyswle.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtnnnhahzg.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtmfswgjem.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtnvedxwfe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtzwukzifn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtjljdzcpn.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtomdffetj.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gteajhbskw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtevarkvnl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtwsmvpvgb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtzgiejxxo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtpsiviixd.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtlvuvpabb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtuymzqzbr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtuspdqnyv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtaqsvqltk.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtuuiqveye.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtmloqbhob.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtxajpvfwh.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtoqmfpfxj.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwcxywvmg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtxcstcxtc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtmbvovcru.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtvmpdpxru.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtlhlsensq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtanrxhvqi.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtbepubgpw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmmzniedr.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gthuhhhvsc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gtevayfxuu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtsgselydm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtiaezaoda.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtxojawgih.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtewkvovbo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtfqkihlto.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtixnsmlfy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtzntsdeve.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gtbdbstuqt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtlvavsjeb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrpkuomkv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgevxhiqo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtkzjzdmos.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpedjnduc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtxejlasio.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gtdrbdbwvr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gthngiieun.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtngodewdq.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtkgbwbgmz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtnlqqqwwj.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlhrekpu.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtsmlxuoov.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtvvejjtcp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtwqeypnqg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtmwdpgzxx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtmhuindqw.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtkwkrtxhi.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtxowxvrsj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtaasywclr.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtfptyaoro.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtbbhjjmyt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtqrqsnfmu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtrwbbpnma.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtnpudlqdi.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeawyjie.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtgmybprct.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjclwzloi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gtvancnlci.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtymjzygre.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gthhdwchrn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gthuvrhzwn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtbhghsjfw.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtjgwbmeor.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrplgtwde.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gtqhmsdpoz.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtgyxrbxpp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gthnsbmvce.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gthcwdzlwv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtpxsuvxyb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gtyfbmorln.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtglnyaefn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtblxtslsz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtwebdzasp.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtvuqssbep.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtmhcggtuc.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtkmeadygd.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtecekkwcy.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtcjvhpfwk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gttrhpgipf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gttmpwjngr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtemsdsxmc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtzmgfydkd.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtwygfpwxf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtyhbphujw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtkgqfwscf.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gtipaypblm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtwcadoiae.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtoezqqlkl.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtyvjqhsju.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gthndyxovz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtezuylllg.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtwrtkltvd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gtwiwodcsk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtgygzoocv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtbvxllwge.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtzvuvpkve.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtzxqqbgih.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtapigzshr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gttgjdrkio.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtkgzpqzdl.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtcqgyqkhw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gtyofwktfy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gtxgrvvddn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtqjtaejqs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtxtxfpwsy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtdodyxbbq.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtdylyrobo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtwobtmpoq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckkowyqk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqlxpgdtn.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gtplpoqktf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtriejsvga.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtzfmjbpga.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gthqvhjfur.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtdnbqmctj.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gthewohzzk.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtdgigcrdz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtnreijkdr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtsfqzhapd.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtrthcivsd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtlevodcke.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtezjeeruj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtrljycqjd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtdtsgycql.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtldbsdnff.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtlhwuabey.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gthhluybvu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtbtcgfjkp.html

Ruby: s.scan(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskcvrlhl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtdvmahirv.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtteitbvxy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gtdrurvedv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtuqhtiipw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gtukkayqqf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gtgvvgywjq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gtgdowbsxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtmjbxwfjb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gtgoekqmyh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtakhvrxuv.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtcthpsgly.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtrxwvgydj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtatkjbrgi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtrdopkdey.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtfmtbqbqx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzglfcesq.html


<!-- 参考信息 -->