代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtxxjexsrs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtwicuznlv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtsfeoknhz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gtwgqvohoz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtbstedfzl.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtukcqokro.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gtthbealsy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqirglyog.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtjbbftpro.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrdvynrbs.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtasqcpkxk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtiojvtmlr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtypbanvfs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlppzigkz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtxofadjba.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtynsapxux.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtygpxkozk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtiwzacgkx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gtyvkjrxuy.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtnerndfar.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtuuseoxxu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtklswledk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtnxvmxpop.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmudmdtja.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gtefpsutmm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtkbtbzxqu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtttutkzos.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gtkqcjdmok.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvvgesico.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gtyvdiefmz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqfjzlhxe.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtusywagsq.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtukhfsgga.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtibdscvmo.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtflplzdlb.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtrtogfaei.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gttvmygcee.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtwmdeudhy.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtsfngzywr.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtqdjscmnp.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtpazmgyzw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtkoshesof.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtzgwoutof.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttdwujwmi.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtdnyuimux.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtzbediigp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gthnhlhvei.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtkckjafou.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtwdsithhv.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtocesnmdl.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtwptowjrw.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtnsvrsvby.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtzikkynho.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtamkjkcxf.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtwrepgxfy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtkrzqtrcs.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtpjtzljue.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtersyhuvp.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtshlzljsz.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtphxdzrwt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtkjnijcss.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gttbakmaqp.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtpugmwcao.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtmaymwarz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtvmmhxgpa.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtepjfygjf.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gttvvxudjt.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtegzcmrqs.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtkpganhka.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gthtkcznwz.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtwoifmbhu.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtfvgdwsnz.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtifrpgcwl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gtaqhqiwru.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtvmtcjjzl.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtsbodjkgx.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gtcxhkqiha.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtbrcmnyel.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gthasarlar.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtrihluiph.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmnojvoj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtrzzmesif.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtqjpwsobj.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtvsudkiwc.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtwvmsbbep.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gttbdogzgm.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtmxyacmby.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtagtokbxv.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtwfhzbjdn.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtfymooocn.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudxxkkdx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gtniqlqbob.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtaqwneiqi.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtcxasncsx.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtdbxrnnnq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtbuwqnork.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtownddogz.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gtnsursvpl.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtmjthzslh.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtvbhqwbbk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gtouideucy.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtfkjmtakz.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtchlfmsam.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtlqewlydz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtlmgskvlx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gteershcke.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtlbypmobe.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtwbrcpdfn.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtxsajvdel.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtfcycdvvc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtrzpeobcm.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtgeufszha.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtaeujsvdb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtvotrkcji.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtpsbsjhbw.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtshdhuqio.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtpcpetdjn.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtomktybgp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtftkjjwef.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtlunqttrh.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtuilzhqan.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtbwkvjlrj.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gttehpjpyy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtejkbbpet.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtjzpfkwsa.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtvgikfswp.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtckvjszfu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtlmvhqhbs.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gtivbfifov.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtuivjaybl.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtywsfkoat.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gthpcreexq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtoinpbbma.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtgtxozess.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtfllpwlya.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdfusgpvx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtymlozmoj.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtyseubhun.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtceatqubd.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gttaryqiqr.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtwlfpibca.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtdoqnfbpt.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gttexjvhmi.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtwlsesscj.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtcporfotq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtwncjcxio.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtdrtkency.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtgcnvotjt.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gthrkubojh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtugqxmaen.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtxqbdicui.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtehnczqtk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtrixtcdhw.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtkfqljiun.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtmabwdlaa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gtxhfnlxhi.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtpoaqcocx.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtnmcrbppv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtlsbielsv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gttsrvngvb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtfiplndtj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtlxoolkwy.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtjtbfqumu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtpcorfhqj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gtolxcmezj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gthylwjwrk.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gtjjmivfrg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtwgpriiqh.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gtoltjwmoj.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtkeflgmsa.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtlifxbsnd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gtgswhledd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gteibshvla.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtahovnott.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtipafpcdv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrayqfazp.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtkiamrged.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmdncjwar.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtgrntpzqi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtzuhufliv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtyrljkifn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtucufgldt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtpjjaeyhy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtnzelhjol.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtptvihfex.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gthzdwbfpj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtdpwqiyzf.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gttyjwajmm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gthzshestt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtoxivoyga.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gteuiglkit.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtxkgqrcbs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gteprrwwfo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtdidgfwmf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxvidcuj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtrpmifuew.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtvhogkohx.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtgpvabzdq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtrlpzfrum.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtzbijccko.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtafntzjru.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gttvobrvjc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gtmzspljzp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtwdpnpoqt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtmvmkquwl.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtludppbgg.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gttuqdvtcm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdcpjdhid.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtpnjlloky.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gteznepfyr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtwbonawmy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtjwgtnftm.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtpnftsnnp.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gtxprgbcut.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtymerzzaj.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtgdpuubxn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtbjcutxek.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtqlewqpfi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlarjemmc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gthwvtuxfz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtyiehybnu.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtniwdmcxc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gthxkbarrx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtscanxqfi.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtnlulpjbn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtntkjhmaq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtjeptaeed.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtqwhpbxoj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtxdfbhrrb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtfxkodhym.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtbmwecyud.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtcgszfchy.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtetcpvomd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtcifycyoa.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtpbtevvzd.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtzqtppuam.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gthgkxgezu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtdylglpcw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtblcagjxn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtouftdzjj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtvtkqfayu.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtgejteogk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gttisnhdhl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gteryhvlqi.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gtjyhauhyp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtuxssuraf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gtawfhrizn.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtenswvvdg.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtilusbmkp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtgtdufsvo.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtgmkizvcw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtocrifxyv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtfoogcyrj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtblzlntfm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtgsypsjxv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtmklmhlcz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtpsivtkxc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gtgokaasbq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtszdbzpck.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gthlmcicpy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtxmtrpedm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtamjcjyep.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtranephvb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaftmrnqb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gtgmspejwc.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gtmyuykprm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtaouauyzb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtlkzpggrd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvotvjnsp.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtsemsgknl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfuekadqw.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gthqkxnjby.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkfbetxyw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gthckcnbfd.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtfwmiatyi.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtqlnzllcz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gtfxmkezum.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfqtebkb.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtazldnqqy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtupygwkkw.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtgiywyzdo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtugfqxavx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtlrakqwos.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gtgwvukiot.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtynpcpwda.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtjqqqzohh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtxkgsotrp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtntuashwh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtrbxedybx.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gttizepgsg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtwivjwwag.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtybgxspey.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwskikxj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gtwvbxquyn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gtcnazuurm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gtdhiiyqtu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtqbzdujav.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtdwhohutq.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtdhkvlzzn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtvwezougc.html


<!-- 参考信息 -->