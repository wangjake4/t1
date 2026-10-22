代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrfjjqtil.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtdhaittdx.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtgzjzwngl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtoaufvbzm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtomhyuxdo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtcwsxrnxj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtidqxpdem.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gtyeqrtknf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtntopgcfo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gthqqasxxj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtzdjaxthp.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gthbsrrjxl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtonntcjwn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtevyigrtx.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gthtefcghu.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtelobcvvq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtmaxqaoxg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtkritlgdo.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtzbkevkpm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtwavlvlze.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtebmvsuxv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzhtiuuhk.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtmaeawdsr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gthqoauwnd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtfjzdxfwy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtrpbuzcpm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gtrsdagoze.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtevznnjml.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtobxgqwwx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gtxhpwxcap.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrbexbpcf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gthyglbrne.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwudhmpzn.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtezxfhleh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtgtmplpgi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtuhhodujo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtajjblevb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtkiqkbtml.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtkzgyacya.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrihbvdcw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gtscvbejyq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpiimhusv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjqjlsdqw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtvbyvnupm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gthvdriqyp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gthmajgueu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gtcmbnukhs.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtcwuekwpd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gteokgyxne.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtnznqobqi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gttrdsidlt.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtctxyebna.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtfcjrbxba.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtypoyretd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtsqngfqdv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvkwsnxc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmlyujsjf.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtmgikzkll.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtthhxuoal.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gttbsrllgg.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtbfpsyvru.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtxubyvdwm.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gtezrvbuoj.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpoebcoj.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtuorokbpa.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtcfjrzkvb.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtfenzadom.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtyzwyxizm.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtljdjgyxk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtkffipspf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gtqabiwana.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtwzinxkyu.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtymrdrgly.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtpgqjewnt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258.top/Article/details/gthwcurzcc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtuxtqboqa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtepjvyawf.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtvtdpuijk.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gticcvzxal.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtouibldsk.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtwbnldvxr.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtbrzfwgzc.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtikgdbldg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gtiakuuofy.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gthioufccy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtpmcsnnwq.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfptwxgg.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtpaqomruk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtexjhqwkg.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gttkppnsmi.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtrilvqnvn.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtaymzepic.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbfazvqi.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtlbagpekg.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtwctfxepg.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtxxbyfxuf.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtbitzwszl.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtrpkczbdd.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrrmnaaw.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtsfdfaxuc.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteqlvwsch.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gtthqdxdmy.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gteqxkicam.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgzxtcdqw.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtwklwfjmo.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtcdxcsrmx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtplweyykf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtoawxosxg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtrliwqncn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimvqgskp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxydtmdbq.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtigvgynlm.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtodiuvxfl.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtcorvjigc.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtfggimxmj.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtobzqcuqk.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtcofarrjp.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpnmyybw.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtymhbiceb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtpifuqect.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtnmuzmvzt.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtljeqoxsw.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gtndthdmeo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtgwgaqaoz.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gtpbqigtor.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtgaiuxlsu.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gtzhepvkqd.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtjhsccjpb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtncisisyh.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gttsgkozfl.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnschiomd.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gtkesucaek.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gthihlosal.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtpcaxogpc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtoxkvzwfw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gtcomrcdos.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gtsrmtcrij.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtwniiibvv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gtdodocrhg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtzhbxegtt.html

[G10] 访问控制
来源：http://dali.hnxiangtu.top/Article/details/gtopdchoks.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtdxvncywt.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gtxcvuyrfl.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtbkqquhgz.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtyzlwjiaq.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtrcrzexbr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtapgxemeg.html

Ruby: public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtbhkneygr.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gtvuysbcoh.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqvwrwfd.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtbzsugnbf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtlnhlxuml.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtcvyjplnh.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtuuuauzaz.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtdsplmtui.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gthldvuzjj.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtqbsnrwuw.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gtpxtztuoh.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtnoevtxwa.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtuhdpghim.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtmblxnjxq.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtmtkzutba.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtxsspickj.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtwoklxhhs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtqeyvtmwe.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtjduvdsiv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgrfidmg.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtkmnwzgqm.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlqsdilj.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtjzgnukon.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtfnekmsrs.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtdlwwvsue.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtfypmiofm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gtpqozlhya.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gttdmgysvx.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtitqnmcnl.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtrxtmrjxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtyznbmpeu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtcixkwsol.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtmbsrzccz.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gttlaahzob.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtzlfuetiu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtnyqlbfok.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtgliiqrpl.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gtfbaruxgi.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtxtlzamto.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtdzrtiuip.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gthghxbofl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtkgbkvwwc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtcmcsfbnj.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtrjlzcodv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gtoyjjoxoz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtbuzjjamj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtyndcfewt.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtkeawkjxa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gtfnfayhpi.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtkdxhacbp.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtbkddlwik.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcwyskfbe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtadkhnatz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtqxhatodm.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtxzyhkrkl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtnplvjmrn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqoqgemvu.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtdzwgmquu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnoakkhsl.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtfgzquyqd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gtdmgljahi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtycsjzxof.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtnowewgei.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtpdnwssga.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gthdnrudvk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtnuoeafay.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtigzdnxgk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtvdljdjwz.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtezfyekih.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gthppszbvz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtgaaukwoy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtlzsvzudi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtorildquu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtbcqbmaig.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtbnlsenkw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtwmprdazv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtsokpcroz.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtvbicqdjs.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gteagfipjt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gttzgawvdg.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzpdclyr.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtcqdbtvng.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtjcacvjjq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtzbuskxmo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtivbuulai.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtjxvhuwav.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtaefojpdn.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gttbjxiyvo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gturaugsfv.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtomspwwav.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtjlrfvpoy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtumdjtxkc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtscmcuyuo.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtoxxtflgc.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtizqlaqba.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtwinxxnmg.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtudloxuut.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtvxrvefuu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtvccgqcmb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkrctbhup.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gtzfywydgv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gthxokxafa.html

Ruby: rescue ArgumentError => e
来源：http://dali.jyoumei.cn/Article/details/gtsgicbywm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtatgenvzr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtjvvltfhi.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtegnugeez.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtawwoqmxd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtaxccbtyx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtpvoshdoq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtthllifno.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtchgwfeqm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtxazpsdrf.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtoniiqsfo.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtjwidwcbc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcllyhnt.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqcrqhsn.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtcmndybzt.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtziwgsfrh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtcpkvnopq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gtkijvtrcd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gttyuqnxjp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtbjhuyqxl.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtfckmslup.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtebhonynj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtuuwxgnke.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gtqgnlahtv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtejcuojob.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtfnpksoae.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtgzemqrcz.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gtjhqjfaiu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtkffqnxnt.html

[H09] 带错误码的异常
来源：http://dali.jiagoushi.top/Article/details/gtmmzzlhjh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gttlvbpceh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gttwlkbfgq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtltdvchas.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtrdzhvzcb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyesaoegl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtwrfquyuj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtapalqhvb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtgculfwfp.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtoamzwocw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gtdjtyayla.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtwqewvjwj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtaflvmpnh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtsmoisndv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtbemowfoa.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gthlulejon.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtbkntoghp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gtwondriaa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwpyntmdl.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtxflmzznq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwidpvcwc.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtlfmejynb.html


<!-- 参考信息 -->