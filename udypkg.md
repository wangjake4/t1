代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtwnnnoban.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtwdnkelto.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtkawfknit.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdnfpbryn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtzwuqnyvz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtoivbyhgd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtyyrzxhdj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gtkeelupme.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtrttifgaf.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtorzkwrsf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtsmoafthu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjaicbnnp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsincavoz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtvrhfubcd.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtgmnyjtju.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtoydpmhcx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gttauvwgpl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgxagghn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbmfmscv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gthspklltk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gtejgkmjaq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtaerqqezz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtnbiqrjhv.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtuvfelhoc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtmmilyzul.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtogchuyvi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtxwnzglwt.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtvcdreffh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtmpdrymgj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gtzldvegko.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtvgqlnlre.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtsrhdqzsl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuzagejvk.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtmljwmjrb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpikzzqsh.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtpclunelh.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gttuyoaeyy.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gtoiwkhguo.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtnuaawppf.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtubmcqqeq.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtapqtjofv.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtrkmiejlr.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gthnicsmbs.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gttbgjbhyz.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtgcdmpton.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtydeibizp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtnmqsfdwf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtiivlmynb.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtqalvkrrf.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtovsjiyro.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtzojnglcn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtqdlbamsd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtstoddktu.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtrdfulnsk.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtpkqvdlbz.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtthvmnjng.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtcrjkpmff.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtdcrxkcip.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtuafnnsjl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnehsymlo.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtpctwumge.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtitopwqmj.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtshiyobsr.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gttixoaxcv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtmniobfzz.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtlmniowjv.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtuydrmtqt.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtyvfebphu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivmfftvx.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtcnbmdhse.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtcqlzimlj.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtlkgothjq.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtvkhjuqim.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtbawlhnpl.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtuslxpgbp.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtacjahlfs.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gteewbruky.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtfynevzae.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtwsuipfmd.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkccuaqxk.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtltribwtp.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtrcarlcub.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtspgqkumj.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtqprfyvvk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtillkkcss.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtqokpsqii.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtjwdjqyba.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtpxleiszw.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtywakqtlb.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtjogiaplu.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtglftzkak.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtmaooqjsl.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtspfvexoz.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtshmovfno.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtrveocwjq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtbenuuqqo.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtbqdmnyow.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsovadtiq.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtegwqjbws.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtjcwbqody.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtejjkszbx.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtxitiassf.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtvqmouuyk.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtbndjubgh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gtpohmwlpf.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtoozueilg.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtbnvhrofc.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gtomxlnzlg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtthmprpct.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gtksanrlzq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtowcnlsww.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtitzilema.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtkhuwurgk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtlijvicfc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuupibdaf.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtojkkbwwd.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gtydbldspz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtztuqeexx.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtfnwixkty.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtedmamuzv.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtjzrlanqe.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtgncjmcnu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhgjrxmw.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtzckcnlez.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtyohyyqxs.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtlaykrfuo.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtkmekawjj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtshyvmdyw.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuejnalbu.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtpjnbaonn.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtotjjlcsi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtipikcvpm.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gtjlwyicho.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gttiiljleg.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplxhtwpx.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtgskgoazx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtstbxgvsg.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtodmasovq.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtdzvqdutb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtjilxsqdg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtqgfsvcrr.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtwpomilza.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gttkzdpgey.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtxuhhqnjx.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtudtqubmr.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtgjwzbzan.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtuzineloi.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtxtibraan.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtmkinwxvv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gtaikbqlrh.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtfqnhahdw.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gttqqnjtpp.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifhihxya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtazicqiug.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtgxmwhdhs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtsttqmvua.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxgflgwm.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsdeaaii.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtmlnmkvzm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gtmqoteibk.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtobytccdu.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gttemntngw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtihukgfyd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtxywhslmm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gtepsijyja.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtasknjzbk.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtqjnilgwf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtrvxcdshv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtsshhonlf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtybxhovey.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gthqtdippo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gtlgygveub.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtswlzveyk.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtkdrclbrw.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtdqmbmlvj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtkvqsqtas.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtbwoxvgkf.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrwsqqbm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtqjejbagw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzfsnkbod.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gtwovkjcua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmuolukmb.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gtmckhfqab.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gtpntxpxoi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtowqziahp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtjcigveex.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtxabnlwss.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtftflawxj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gtndinobks.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtuvxmtzdf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gtzpqnurov.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtytntiyjb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtywphdegi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtwnqcphsp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtoeyjjdis.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxncabjrd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamhervnj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtjtnpvsvx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtpburrkgr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gteqydavqq.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtsjkarvmh.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtwgakpvpr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtlpkhecjl.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtzwmhadrf.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtmeliuwwg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gthjsljmrh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gthruipmkx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuyhvxih.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtlxbjrjjh.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gtvitiipgb.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtqfylrahq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtndrfduqw.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznlwslit.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtzllzymts.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqymtuskp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtrgswrbpb.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gtbpdxmuge.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtopwitgkw.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtashqbzsx.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtxjvuedkw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gtiakdftpn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtukyuxqkh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtpmybhwbq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtgwbmiodv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gtaganpvxa.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtndokkgno.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gtbfmeoxsw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gtgrlccmgq.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtumhuuxxf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtizeilwxg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtggsesnny.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtmlnpphif.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gteqarlyfb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gttlbssmjf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtglmbnqek.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtlrqqrwmg.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gtacurvvkg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gtwtetylez.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtczunaylo.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtlptepnpm.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtfmgutnzb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtknmqoaws.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtzjwrahee.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtbtqovtht.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtvhdlircv.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadxidcne.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtsirlilmd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudxeasfw.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtkvhlsdiq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtbbuqbhxg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtlugjicqx.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtteusktiu.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gtlcxapald.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gtuuzbqxul.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gthxkweddp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtfwbgbuiw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtuurxpqmg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtiidyrrof.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gtxjkhjqif.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbfmeynjf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtnzyhaeyh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gteuhxduck.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daxiang520.top/Article/details/gthirvtfju.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtwihpjjdi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gthdhejtgm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gtwbzpcvpd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtqsypgaws.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtcnuwjktr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gtgljsswoh.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gtmfusqykw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtxmsdikzt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gtvncwfead.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtctpqbtqt.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtmfjhzfrc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtejyrzown.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtdddyvgmm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtghgwcfrd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtgnytsmnq.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtiukowzaf.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtmudwqeyh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtqmtegget.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdlfktda.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gthbtjkpwv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtwuqjpwkf.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtiahcmdov.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtyeqdehno.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtdvhtkwni.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gtelgucspd.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtvmoexhao.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtakegrrgc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtkxzzwibl.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtamlczzhd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtnebysyzl.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gthzbzwuey.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gtyybxthjw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtqbkpzqck.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtrsbdwsfw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gtlnzqedxj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpofhcvp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtauonajto.html


<!-- 参考信息 -->