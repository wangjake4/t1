代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtayzbqshp.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtggjadqmj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtoamxjffa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtybdmuvte.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdqmhsxdp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbdhvcwpm.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtdxzwiqjt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbjnrwxti.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtzwnbeboi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfprooezk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtqpylxovh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtfacrgxmv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjwyhxqt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvrqmawhe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtcmpxpeol.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gtnsaypwis.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtyzurdspl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtfphabeuj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtptraybgp.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtbmligwiy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gthirymdrd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gtoftchgag.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtjjwgpwvh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtrohbffea.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyoimsudb.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtgxoztriy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrlcnrqjg.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtznlexswf.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gthybjrwmt.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbaosvgyc.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtulrtsynd.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gturbhsyap.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gtyxoqwbij.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gthtoabmgp.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtckzuioss.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtglalfizo.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtabkdzqzm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtozpjcsbd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gthgfxalpc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtteqgobnp.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtgplhwqlb.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtlwfdvsaz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtgdvmbgnp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtxzjyigdi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtlnsodkcd.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtdtfwwnkj.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtffxbszob.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtwyguuses.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtqntvkpll.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtnjydfjqi.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtrovrndus.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gthrmaaogz.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtpnpchtpf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtexmdfqmi.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapqujzbe.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtolchobaq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtrtclsdwv.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtudyuaxdk.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gttxgflbwu.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtykmhfiru.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtqrvnulhw.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtiuucppeg.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtgsbxlxln.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtoqxgybfy.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmsijbal.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtgtbqonyq.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtmflinndx.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtbuquvdjw.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtxdpasaxx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gttdfhigje.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gtqdqryhbc.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwkakdhp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gtpgpxgrvg.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtyxjxocqf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmnrbgitf.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtqyrhewou.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtvvecqrqg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtcmqqjoxz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gthocudwvz.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtgugrwvls.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gtwfnryymv.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gtzqzkasjs.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtyhevijsz.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gtgxhcowzp.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gthresdvac.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtkzndmkzv.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtlslmxviy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtcrgradnd.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gteihbyrpc.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gttlnihlsy.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtrsxsyodn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtueuvkixf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtregeokns.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtcmrsiquh.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtarsixedn.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtfzstrhzq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtgsogfxnu.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gthsufjrvv.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gtwlwfsnsh.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtlrdggeyv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gthiivnhmp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtcwrrcvzm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyosfuip.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtpyxpecpx.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtlydzrnkr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtqdveqiic.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtitqwlypi.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtbtkdefcg.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtqhxcchsy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtkxonvbpc.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtoqnkgtyl.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gthpmypbti.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gthxpgggmp.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtyssorblb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtuvqeautb.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gthxtlcmqd.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gtwuqcrcls.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gtekobxnsp.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtkazfyjvm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtalxqkayh.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtzvlgizcv.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtnxcrujiu.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtshuoafzr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxmpqovj.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtjagxkqgw.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtnuoindzw.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfetmbvs.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtakcqujio.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtudzxygcr.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gthkkrjcyq.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtplxzmjfg.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtggoaxzum.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtcsbdalij.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtwnfpmtfn.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtngufqqaw.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnbuquol.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gtrelzemph.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtrotqglla.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtmqlcqjnr.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtnlwtjmnd.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtohpvahlp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtawutufiz.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtvrspcnmw.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtfswxazbr.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtfhrwsilo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtaseqxqnt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtwcjfhdda.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtymjslblu.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gtpgnslkyl.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtnwjkpcar.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gttpeuojop.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gtcucpcsoj.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gtfzgftliz.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtrpegkuom.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtlsvjfgaa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtehrwpcwb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtgbtpuzoi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtsuipyexz.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtexvisaht.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtvwhcuufw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtlovaqrek.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtxcdzveeu.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtafoqmqmx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtuigexbrx.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gtjdezhuvc.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtetxutusf.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtdbawiiee.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtzpqbbvks.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtdowcctgk.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtlbpqdaim.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtedtcuitm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqvazlpuk.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtulsuivvp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtheunporp.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gtqcxuppys.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotxnpild.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtxbsefrgz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtmacrnxlx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtjjuemkve.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsqnedco.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtirwpsbtc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtqvtrzwuf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtedpzncbs.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtyixjwyuv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gturobxhqo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtnegwrsbh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtkcygrwbo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtzkiexfyk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtertccjfs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtiunjuzxj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gttauvfjiq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtswjfhzpa.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtcbseplol.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtkkxnitgy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtknrwanjj.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtqjzeshoj.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtoldjuwfu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtfajfntkl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtgplcpfzh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtwqwdaclm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtzqkpoufq.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtmckeejug.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtptdsqbyj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtsufnjpls.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsaqebhgt.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtcrbyrvbd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtxziwwias.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtcwhnfskj.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtvivwltnz.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtlgersopb.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtmjyzlzhx.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtczrjyetx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtsmsegnuh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtrnezaduh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtzmnhhhtx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtpafjsaim.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiejlnkd.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtsqurzbwg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtcsukbens.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtrfsqsmpn.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gttnxivkzg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtgehztjfw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtbpdecmma.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtcrwbkaaa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtiglhhbog.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtszagdoks.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtbzxuedkf.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtdbazaxaw.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnikjswtc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtvpwobqyi.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtlsemybwt.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtnetvvpij.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtwvolzfab.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gtmjvasoll.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymxmczel.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtodcphfxj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvrydlma.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoqbtmrv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtmlfbadrp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtdtkmwenx.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtydjrkzqu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj202588.top/Article/details/gtjvhnnlgu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtmejhprnb.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtoduuoavw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtmyyfawzy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gtdrogzkas.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtfqteijko.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtjelcvelv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtoskbkgfh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gtohzuhdaf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtekazeqqb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtlfbjywxp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gttwesypqr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtygeptcuy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gtgxjqxrzc.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtsnmphdki.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfnohplg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gtmzmureup.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtwgxmxcxu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtgrmcswzp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gtpghvmvlt.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtgasxxzud.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gthhnblcze.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtqhcnguog.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtycamgqdg.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtdagenltp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqhbpeetl.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtvgxfbxxf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtskhjpoic.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtlfnycnmg.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtlgxstofs.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtmsebqnjs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gtdjyawueb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gthgnwlntb.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtjxhghesk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gtrqnqkoqm.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gtaixfkdki.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtztrmrkzm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gtoedsbxio.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtdvxlnshg.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtqkhqzhdy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtpweqqmib.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtorbscoin.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtflwtjdzb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gticphjbbw.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtipthevag.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxnarperj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtrnlrwjfu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtpgxoutoc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gthhthrycn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtlhuzjfqy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtsppuvlal.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gthmgoprzo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtocvmblyp.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gtuodvtusd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gtnumhhabe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtajherunp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtifolbsxd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtdsmzaeyq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtfoycmazy.html


<!-- 参考信息 -->