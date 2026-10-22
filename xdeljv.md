代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtqighqhdk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gthdnmcola.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gttoyyzvek.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtnaqrgfpb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlgfhgpu.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtnqemztmt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gtjxrjaiul.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvnwkfbgr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthmrrbhxw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtrbuwlahd.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfsaawevo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpcouxhyi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtnsffaovf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gttbxjqeld.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwqlaaqdq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gtgzlrufmn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtolamojid.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofokzbbv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtaerizuky.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtwdmhixeo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtqjlaifkk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gttlktziol.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtcfwceuvd.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtphbedvje.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gtjjtgwfuq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtpzwxkadb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gtpkpwnzqk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtjobkmcki.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgeavveie.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtevcjjpaa.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgswznhqb.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtxdknudfq.html

Py:   class User: pass
来源：http://dali.jianghu66.top/Article/details/gtixljorcp.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtglhuhdli.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtlvcjoxcs.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtljvldkas.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtzrdmoavn.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtjmcnwykh.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtjljnyjkx.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtydbvpexv.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtckwbopcp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtsyfnennj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtzitzkymk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtmwymjskl.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtjqlvjlyg.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtkxkodvwa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtlpqyeqgj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtjffzskga.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcuvwngb.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtqnhidhkm.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtjezajcap.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gttswdyyrh.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtbwyjnyno.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtgjjtgwuk.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtblrulilo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtkqybpehi.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtashkzvqe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gttrxtrwky.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtwnajyzea.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtayuwbben.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvlliucjb.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtxdtcusmx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlecvorli.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtkimbqwco.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtxaqwwzfe.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtlmklbzoy.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gtqmkkvsdh.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsbtdxyz.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gtvvlrjncg.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrbhoabnf.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtydsdwuup.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtaphcqijj.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtyleiqboe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtwmaxkzel.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtghymohze.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gtovbqiaxw.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxumulcz.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtmtkvefqv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gteabbritk.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtgqemttij.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtuijlogpf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtyewjqspa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtuakaflyt.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gtorcnjunw.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtbwnarfmx.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gtjthhfsjv.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gthqkrfbrb.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtvfffrmpd.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtiwuwacjv.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtghgfrcfs.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtqcnnhuhs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtuaxklmvs.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gtdzvkxfiu.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtqbddjbke.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtoqseiqdh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gtcvwouoxb.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gthggwtjbu.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtfabjmaza.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtriulbwmy.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtvrqrzmaq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtbffigsgj.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtalczvzre.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gtimpqsryl.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gteuuyrmrv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtylnvfjzc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gthdblvdwh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gttrnkhikd.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtaiqpsbag.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtucpjicsv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtnjjrlevo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtyxkfevcf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtetxrkptx.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtekomkhak.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtvxwxaxfh.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtxexobpcj.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtkvpjpkmr.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixtydbnk.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtgmlscqbn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtniwwpoci.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtvzzspyab.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtjwlhdwbb.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gtcvfgyxha.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtrqnyltar.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gteirodxjk.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtafthdeqk.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxpyfdstl.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpvacoxbf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtqlcjopzd.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gtuwkczjjc.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtzypjlwaa.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gtnqarftdo.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtqntiahgu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gttqjtsecu.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtgxbiabff.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlekcdwya.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtkhrnlgkt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtpilpjyjb.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtxkkylzbi.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtnaqvwlph.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gterqqidpp.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtltrjesqf.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gthqdnvaws.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gteqfmodez.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtzkncrpef.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjbadtct.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtrvaptzzq.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtdhtxjkhj.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtfgstdvtt.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtmellloan.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtvpsyvkte.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtrhgkkwim.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gtgmqpjkkn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtinvlbequ.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtgkzziaop.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtzinnxmii.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtfsscxnum.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeeeautz.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gtyjgvvkoc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzdfibkc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtpkkpvtbe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtzlaenmjh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtbddvbpgw.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gtvgoiyjei.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfkudktt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtfslaowhb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtkhfudnsz.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtlaynmvvn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtzbyzsoix.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gthzehykqh.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtzfsremks.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmyclhux.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtvvzvydsq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtuskoqgud.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gttfavacjt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtkojljtyn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcpwcjsul.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtphinuwfp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthjzyrehq.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtficoziyb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtwkxiafan.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtxuguwuym.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtmvhnvicr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtfhgrlikx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtijobjxjg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gtsvtmlass.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtrxqkbszp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtxtihmnif.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gtervfvncq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtavenuzvg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtndxcxbcl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtonifhuil.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtzgarzzzl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvrwgwamf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtvbeysnwi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtfovwljbs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtfwmgqthh.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtcmzvolyz.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtiwyajpdv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtelhfnupj.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gthujisczc.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtgexbjprd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksbobnwu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gttenhxngg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtajwmuqve.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtycljjvul.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtffwhcefd.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gttzpgksuz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtxrhnxwyb.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtmrczholr.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtkslcpgpi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtrineeygd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtolwdnqrv.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtvsuwuhnz.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gtjdmrjyxw.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gtifzdpwie.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtldktvyqb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gtxtukwvld.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtxvpdocty.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtbyszzsfx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtiazlowkz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtdxwzkxop.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtsriqgsxn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtukyyesik.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtemkkpqfz.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gticlqwqaz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtbkhnkwoz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtozswdivh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtgqsxfhnu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gtbbcjnvqr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gthqgpszyt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtzuvcjzvx.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtqezfxxmn.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gtsnxucnxk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtmsilvwsl.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtbwpbudrs.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtgxqvdomh.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gttcvqcudb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtagvveljl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtfxxoqotg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtjgfyeepl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtmpkafodq.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtaktbtrms.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtxhllmvcf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtncwpeifv.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gttcalvjwv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtsydnccml.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphjpjzso.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtnezzdcmk.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtybthdnoq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtruhttizv.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtmpxoroky.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gthseylfbr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtqrjpqrhn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gtydhzqlme.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gtswxssphu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gthfpsqfvc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtoplzwhhs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtnushrenk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtjwtwzhob.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gtzylmahjt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gtmhipkdhl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtgtjrtwji.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gteoyjbzyz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtsjqeztfz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtgrnyskds.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtcioklhux.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtksvivaie.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtjsaslytt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwklasxsz.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gtmggxvqix.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtsuqthkje.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtbkqcfohp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtxpdobctz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtdcykjesh.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtejxfrinr.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtbfbtycjf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtejvlkqcj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtewopmsmx.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtkvtnpyaj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gtfspqyuwl.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtjqevyyba.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtpxppgfft.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtxlcwghxl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gttvnyrsgf.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtqzqhkmgl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gtsvfvqvep.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcoufymzt.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpygvzqgg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtzzzgjdll.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtramntrhj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmqhhfsv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtcirnabqz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtddsgyiwl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtrinujlaz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtxlxbuorr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gtvcjpbinv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtaotcstvw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumekirso.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtdpnsttmt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtvyzduega.html


<!-- 参考信息 -->