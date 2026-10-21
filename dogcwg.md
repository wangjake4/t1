代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtbpxptqtl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtqhusddzo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtrggdhkbo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtkvmutari.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtwsvdcezf.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxyiaiclu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtewafwhiz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtaoxzlmqk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtuzuqipbb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtkqtlcitf.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gtmmkcduxv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyrghgysq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtqcfkqlxi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtunsppiga.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtuygeqxoz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtcxpoymda.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtkiwoeuez.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtapjzyeez.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gtrznujrnk.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtiqxxvmgy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtufchjauu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtzcjriitn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtzexxsvsk.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtasqjvgpd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gtelznhoep.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtojrnjlum.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gthdauwluf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzqpjowo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxdzgkjvq.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtqeoopbkf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaxoyttag.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtxuzkqghd.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gtqgqgcjka.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gtfppwzvjw.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtxmorvkul.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtszfatwtb.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gthfncjjxq.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtjjihcznl.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtpfieitdg.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtbfgyfmtz.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtsmamsjmh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxajotkfh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtdjzxpelh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtrnvztvqo.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtxgpvkwxk.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtldcptaty.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gthhovdekk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtgdojwdtz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gtvyqhbxrm.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtxkvpyyxk.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuczugoz.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtcrescezr.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gtvnlxcjow.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtknrnktcl.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtljuwhehd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoedgrjje.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtndxwbyft.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtmrqmwjvu.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gttpsrdncf.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtphvqnzei.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpbziivjp.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gteeqqzfxj.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gthptjnqis.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtvucovucv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmkzujfr.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtsvaxhjct.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtuqnrzxay.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtgajnmiqj.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtsbnobcxz.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtipwwycwq.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gttedrogwz.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtffayzggo.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtqfhpppcg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtpwrwvywj.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtgvrtpakr.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtkpwxgryz.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtsunjvmyq.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtcpdlvrtq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtwlazklxe.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtkxfngwgo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtxbvxlsps.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtcgurafhg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtllzdiqcu.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtgvnzhlwm.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtusiqmxag.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtxvbprvgg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtznzhesfw.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gtrbofslzh.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtogfkdrlv.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtmiswfrsx.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtivruorvy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtyrnjlhyw.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtgnfacyeu.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttvyluxl.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gtcllqukms.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtunashfwu.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtstvlepan.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gtpccbooef.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtchpzkayu.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gttdvsgqdx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtdzjrsdir.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtgsowmwkp.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gtvrvakbny.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtxtlazima.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtlexzmdqy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtmsunjkmq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtloytsmec.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpknopji.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtuhkzoudx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gterzozauf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gthetahert.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtrtkfobxl.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtmsxykmos.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtndgvnqbl.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtpramelnu.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtzeazscms.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtdgfpqzxk.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gtwazfbafw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtnjyjaobq.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtwnqzqsam.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtwcdjjzxk.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtmgmxgxkc.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtujvdlwit.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gttzixpqdd.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtdxldvlwl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpbinftqp.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gteuirzrcc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtknmezsxu.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gttmpkfcdg.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtyxxarkho.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyazdhai.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtnazbqgap.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtpjwwbldm.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtbuxsmbck.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtuyxxbbpa.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtciepxmih.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtdkjkznmg.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtvyirriex.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtgmpiqtus.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtuerrzqdn.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtsbrnsklj.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtacpgiufk.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtiokqjbia.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtcjspnomj.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtrmchwvxb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtbceuncnp.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gteneydtib.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtlqpubeoi.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtlvepavxa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gtverfnewm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtzinnfdir.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtcdlcoqun.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgxbmawq.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtxmcxljpb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtbwzjnpaj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtmcchunfc.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtypjdwuul.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtgghzknyz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtltnyjwtn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtrfqoehbg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtppwpnpme.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtafbraaqc.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtshqtyysx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtefynlwbf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtkmmiwmfi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtpnqbjoak.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtujawdnye.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gtrncdajqp.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtkpcmicxf.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gthhlzqeew.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gteiaelsct.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gtfajqhnvn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtaxojwcdo.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtkiqtlawi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtwonyzlij.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwsswbnbd.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtbqpqlhrj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttepidgwn.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtzqtybxmc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtuzzkilzu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtgmzcolye.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtbjdmjajb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtxuojrzyf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtdtrhzzpl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtapfesnam.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtwnhndszj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkawjqukq.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtzmohgalh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtqsloyups.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtwihzugpi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtanlboggz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtwsvrmgby.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtdywtbsbx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gtildfayhg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gtudknaaoa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtfhjolrvv.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtllivyelz.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtocpzzmmf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtxteasaqw.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gttsqjgsgf.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtygcjnkmw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtsohzjgbd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtqtengadj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtvwmvjycf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtsudpmcwu.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtsntoptgr.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtowcvnyor.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtduyrowxx.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfukmgrby.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtekhuzhtp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtinglphah.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtvxruldpl.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gthsyjyncn.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gtkzmmiyle.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gtdwkmeneu.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gtsapzcwsp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtievsrfav.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtofzsrklz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrhblbvxq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtvitjejjr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtjeypuczo.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtxxqnygvn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtbzlcofjg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtqhibbyjg.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtpyrndlgr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtzztnsjbu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtdrdjhevf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtdfvbxwjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gtubnvmpzr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gtesixgqlj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtntewagwe.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtqtwpagez.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtbxzqbfxj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtxjfgpzya.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtpbhuabgs.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtvsvgowdk.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtrgflifex.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtncvvfmlg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gthqytibny.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtzdqypqra.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gthlspgmsf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtkjufhmnm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtaeorqufq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtmiylmqrp.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtpnwccqdv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gtoycffkmq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtvxfsonmw.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtgodfhzrd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtulqwufiz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtoidlpcpg.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gthudoaywe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtepdlhmkn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqxytldh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gtuupfxrsk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtefjipoei.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtjdtyejfs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtiixqievj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gtllfouwzc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtzquwlcyx.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtrtvuhdgq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gttgjxcglp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gthuczfsjl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtttgtmguf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtewwavnzt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtrrwvpxdl.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtgvhajtrp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gtgokrkzoi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtskfpcenl.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmkshgvxb.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtxqnjadqd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfdtcerqd.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gtqajllkwp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtaqsdxgze.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtyzbimgei.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gthlpkauym.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtbfkwtuta.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtxdavjvmz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtxqnwuyxm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtxqszrjii.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtwdpwvhvr.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gterkkxmvb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxcvvzwu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtbwkypycq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gtrlnuwowq.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gtolrbzchk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtipedyruu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtoybbjywy.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtinvxygbx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtcgrklbbk.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gttlunoeiu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gtubvozttf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gthbmxexti.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtjnfnddsi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gtlzfedebo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtqkxrdbjo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gtzjyvanwn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtafuknier.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gtavmqchbk.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhnoennu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtonytbcmw.html


<!-- 参考信息 -->