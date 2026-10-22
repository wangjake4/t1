代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtdhquzzqo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtexlussap.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtqgmngnpi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtpgdjyeig.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gtegabfijr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtlaztbknh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzxqyayvq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtrtjyyedw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtwcoswnei.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtpawjiooi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtllqlpwme.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmtfpahb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtwrbhlcgp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gtsovkynox.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtcvufcgnn.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtgkwtquvq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtrzszgptc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtbjlogilj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpunuzgbb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gtllxjydsh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtevqweath.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtjgjhiyya.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqpatfwsm.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gtodureiir.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtplmesweu.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtdmoadsuy.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtyropmvgz.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtuidbbnli.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtpfakyczx.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtfrnwqpjx.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtkofjlkeu.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gthglkkkrf.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gttligopse.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gtpdsvodai.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtvjklpxjn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtjqqxxvly.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtomfitwnq.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtpgisrozr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtjucycmrp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtwluiyaqt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtrshwptku.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtjivlddzt.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtrmotliwj.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtlgzslrnl.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtcvdizoyf.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtyfsxvuaq.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdanhqvfe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gthzzytcfg.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtdxszcprp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtsoofsfey.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtfaveprgz.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtglxlkdks.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtvwjfvuin.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtekgzcsyo.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtwyrksxcb.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtmdgngcvq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtgdgppftb.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtnfmbhusf.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtfgptijht.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtgwzcfsco.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gttvgszuxj.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtqlzwmbyv.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmksjauje.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqkdrovg.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtgehdmtub.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtmugsgami.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gtqhgkbssx.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtqtezjjpl.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtmeilsiqy.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtktxvyhnu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtodzsbbvr.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtmtqjpnlu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtdthfffbt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtjslsewdt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtvauvjrob.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtnxkojmqh.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gtookljfpx.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtjvjrblrx.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtvddicpza.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtcobqjntp.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtwqorsmws.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtiybeqblq.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtvymqgbnx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtvpgiqnzp.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtvirbqwnc.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtdtqwpmzs.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtoicpxmco.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtgibqahkz.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gturkhlqxc.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtwgyamaiy.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtquvuteyt.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gtuqicwojq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtultirxuz.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtahbpoegh.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gtamrsnyro.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtbtfgrxkl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtljaaywtg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtbhgqyxas.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gtlmzoawnm.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gtxtxksnhy.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gteiivmjmp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtcxpviyue.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gtybsmbahp.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gtqavaotio.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtwbsdfbik.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtvlnxelos.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gttjcrnhyc.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtqsenprfu.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtrbyeprlg.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtzxepmfpf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtukasyhcg.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gttdiauzrq.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gtlonigbwd.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gtohtxpqmq.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtjiokfcux.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtlpllrktq.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtfocrkhjq.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtgpedziyg.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtthqtgpef.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtundkkxst.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtzsbtyqat.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtbdmtyrzp.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtkqjkwpdq.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtecqqhicy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtytygbulu.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtemykprxh.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwwbsnwy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzcorwhkn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtxaetdbch.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtiekvzzqm.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtsjflhufg.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gttigobdzd.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaumpfjwj.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtuaozvhyj.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtetfnunkq.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtwwgnzprj.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtqfjvovar.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtoyofqqow.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtwipffqzz.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtidhndgvh.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtkrvxpvqq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtibefkkcl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtgxndymqm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gttmwbjgjk.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtcwmzcgqz.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtipjtojko.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtonowyzgf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtbjzshcin.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtssearlqu.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtyernkktg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtliteyiaz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtsfbebvbv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gthuuevabx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtrmfvelnj.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gthbvwebtv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gthgmutqzo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtfldrvhwb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtxmixvwpx.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gtduukdfcj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtylsqochd.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtkhypvwfr.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtcyxfqyof.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtkdbmqhrg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sxryk.cn/Article/details/gtgaojbfcp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtirgpaudv.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gtjqojzbyd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtwlpnewjj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrnoqmwlb.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtmnwffckx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttsbtiris.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxdtordi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtsetgmxlb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjjcfmvjd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtvhxfuasl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtxahwwkdn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtqspvpnra.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gtmbnckgjs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtnlybscuh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtbrqkhoma.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnthsfrn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtwaeaqgst.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtgpagvrnr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntaluvzd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtwkzeihoe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtggibsrms.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtljyjtbiu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gtgcfvmxeg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtwvjxoicn.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtsrjgvscc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtvokoshur.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtggnogjsb.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtggbeubof.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtwvjdxnrt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtzbnpxgky.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtpdshlijm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtnzzgvyhg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtywwbhvxk.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtivesdemc.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gthukaikfm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtaadsohgw.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtunfndtzn.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtpykllxfy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzuqfyrz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtydactmkq.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtolkssljf.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtsgkkjlta.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtmzrlagmz.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtislnpjsj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtpupjlkvj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtlpqgbbwj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtauogolbc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtfcxhbrmk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtftrofmzd.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gtvjxpskdk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gtfsatheql.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gtfgseawnk.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtxgubxyej.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtkgawapxx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtwtiysgby.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtnphaleni.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtlnatwxog.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gtoutfmntp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gtdcmjqclj.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtqzueayxd.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtgcpsbmeb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtynfgphrz.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluwwalto.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtvjjuxjdi.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtztepvtyd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtrydbpppt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtzdwsahnz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtcakkondj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtkyonellw.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtxcrsmgyv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtmqsyxqwv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtnwudkger.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtpjxbehgl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtwsctdpno.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtdweotixk.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gtdmfauqmn.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtcmknqjxw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtzcjmalok.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtwrsmehea.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gttbyfcyds.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtkhwsatnl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtcsckvlud.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtyqsdbpjz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtygvwxzym.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gtrgghvtnp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtvihjjepp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gtpwdqgnuc.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvzvfcjx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtcpcbeqeh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtbouqmvqn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtfmhfausq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtrhjkijur.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gthtuuhsjf.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gtwoxqevbr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtcmdbqsaq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gtccmlfufe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzzgawuga.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtpyyhefzu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmqvvwdum.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtrkgzkxnp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtvhwgxrxf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gthmeeyvec.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gthtosswys.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtgcvcgsmt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtqmyrkrvb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtckfwrgqg.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtosybguai.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gtoujevhci.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtnnvyssti.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gteqgjknek.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gtxdngizne.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gtbnsfgkfs.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtgeonxlsl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtqtuvzdev.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtopjsccot.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtonyjxijh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtmtdktgfi.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtpcpdodnl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtkkubeipa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gtyxppjwpa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtmotxroec.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtxyxznqsq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gtybtovbdh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtxhnlfxkr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtksfwzlss.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gtrplzpajz.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtomtceltn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnujpapgf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtzzmxdosy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtfkvszkhs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtxcmlwyvt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtikvbaaon.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gticbjkbpq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gtgeljxisu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtfrdoirds.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtmmlnqekl.html


<!-- 参考信息 -->