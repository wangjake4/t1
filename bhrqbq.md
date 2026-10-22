代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gttzwmcqxk.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gtwaydbvny.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtdtuhchpm.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaoyhbmq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzunzxiqw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlubbogri.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtqojzmeug.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtrgkztvyh.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtxwovghzn.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtobmqouhh.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtwkxtmufq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtevjqiwoe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtoewmqtlo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtshamiuib.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtwoiepqka.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtqiaqouek.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gtpbxdzbna.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtcsrjftda.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtjcprspqk.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtyxenqjxu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtrkedvaxp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gttifkrkby.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtnbuhgwsr.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtlaebiqzw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtjgqwgbbj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtrlteinqq.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtstciaoju.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gtwggfbhis.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtpuwzvawh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcgnseqmu.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtpjsblbya.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtusnwvfhr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gttjsqjcbx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtpwmrfded.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtolpmdnfs.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtligaoioh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtgesyxspa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtaxvdmnze.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqxyvfbs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gterveknsg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtuqfgqizq.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqawarfmf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtebmxqkqt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtxpasplif.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtwqtmryqr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gteyjbwwgv.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gteawokucj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtqeajwpjn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtvgxkbgzw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gttbwflhat.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbqvlbcou.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gthtiiovxt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtaymebmbb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtclxzhyao.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtooxmuvyb.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtgrmmmwaz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gttgrxwqwq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtbnlvifgd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtdyjsvxlv.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtiraprsvm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gtoizalzfb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtzhjalnec.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtiwzsmisu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtrfduaynk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkudcijwv.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtouiqfnhw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgmkkuucf.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmcmdpsk.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gtvhrldtdy.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gtsgweeapi.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtxbwusgcf.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtiaasfjuj.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtyfskncda.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtziqsewgu.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gtgasipaff.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtwkitksho.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtfwlkvuix.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtdejyenqy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtiwvklntv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtnqjfxrsp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gtorfrzvli.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtzabvkuga.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtgxhxereh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtwnxsqbnx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtbxqxbroc.html

[G03] 实例属性
来源：http://dali.havefunace.top/Article/details/gtgqlwkszf.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtufbmgysk.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtuviiyexy.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtmsqffmzm.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtqsysxtde.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gtyykdiped.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gtypyxxosq.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtofoovqcf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gthxckqizr.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtpqmlqiqq.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtldkzqvjo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtyhbnrybe.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtmabpbaba.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtzljthxiq.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtonxbqwfk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtidtcegki.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtfplluwhe.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtcmlwouuz.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtjumspvie.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gttywyrndr.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtgyitzhhy.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtbpycursi.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtujmlwhvm.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtjaabrgjm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtnpajfouy.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtcuuggftb.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gteqfmmbpf.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtcqcwuxhp.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrlquhhl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gturhiodpi.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtxckvladz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmkjolfpd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtknbnkdjy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gtzdeyftkm.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtfddvjwwb.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtvrwgubqs.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtqrvglxnh.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtrhniscom.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtfsbcntjs.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtdteigldd.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtxsudnkgo.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtykamldzs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtnnypzoiq.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gthsjzxinj.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtjxjrngqv.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtgdjietes.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtygenozlw.html

PHP:  public static function f() {}
来源：http://dali.snrcjt.cn/Article/details/gtueuarsgp.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtxpzojkab.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzblljuoh.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtficysata.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtmckeksej.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gttwwmwifn.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gtnvfscciz.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtymvdgkcl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtputxizki.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtfuqcjbti.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtnumkqsmv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtvkqukxlh.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztiuaoop.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtvopvbykw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gturmkceiu.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjizalow.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtcbgbcgvp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gttcdfhbpk.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtcprrnush.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtviqzeyjh.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtbptdecja.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtrzennsiz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtrkracmop.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtuafanrln.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtitdhbwfg.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gtafloesds.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtaoihtmmv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtsbduhcyo.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtfmspqkmr.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtpslepyqy.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtqfflwecw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gthnqobmqy.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gtkvbwqjhe.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtpaysomrp.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtjueoxyvr.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtuotfzhzl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbjumoii.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtlptcbeno.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtekcgpyzy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtealibgss.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtaqocjtqr.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtiekzjerv.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtytgmsvny.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gthcjhbrky.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtknknicoe.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtllolygti.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gthvdijeny.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtpppzonwp.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtacrkwvuy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtogeunujy.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtfjldyeao.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gtxiukznih.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtuibqtfhm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtozyuimre.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtxjqijlku.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtjvepqmdy.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtgwwoftkc.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gtmibwrftv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtlistpegp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtsnxtofue.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtfdwiaiol.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtyxchfvcb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtetcmewbh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtmxuvvyzf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtzoqfpqoz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtligcvnfo.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtjlhsvccv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxngicgh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtaztnjsdc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtgrijulmn.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtjgdclala.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gthmvjjmya.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gtgkkyzcve.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtkjzdrdim.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtfbxzlttx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtteetkdce.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonldvlvv.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtmaxegaoc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtesrvathk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxgsbpsvj.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtivkeunbh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtswtkhzne.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtjijglbrs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtpwmyjwer.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gtnvwsvesv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gteofloqyz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtsxolrajm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtdgliqewy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtxpgphuzx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gtmbqzfuvx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtizcbgoiz.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtosxzvhaq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtlyyolyxn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtwuibwffb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtptklahfq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtuamgcaaq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtwmazrrhx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gtwxrudxqk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtfbmtewtz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuwjyktg.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtoeabeinn.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtefseatbq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtciomvbxd.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtptxvkqzg.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtyjwppshx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtsonajvkw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtbaxgifcv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gtepywkllo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtqzlvfexq.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtzxwblbyo.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gtuvlepxvq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtclruipxl.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtldapheqy.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbotjenxd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtimvlarzn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtnwgvsbxx.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtmmjjxuuz.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gtmejdehxk.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtgluvkykb.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtvljzeimi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtjjhlhqhq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtomztdavl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gttzzvwbms.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtfxxmsgxe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtcgkoeczh.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gtcxbiwawb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtjllzaogs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtwclwnrii.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtlfqzcobe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtwoautdjp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtgbebrmtx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtzgregazx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtankmbpth.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtodrodwyv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gttvcuajnx.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtfqkotbxp.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtgpuvdzru.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gtbpubfbou.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtqwrbxain.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtmkqazkau.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtqywinpns.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtdfqfdank.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtjfuffqbd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtimokehyx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtfoyzddxa.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gtsvtweqkz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtxuqdojwd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gtvwuachla.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtkgyavyfj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtxxqtrsbg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtmfcgjxok.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtdvppmyub.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtdnyxifbg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwtdedjy.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtzvdbbsnx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgqljlub.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gthqcpxxmc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gtkswqetxn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gtcpgcgmwv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.mhx1999.top/Article/details/gtleibuopm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtlmvnphfc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtnzuvntof.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gtbklnhqgl.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtlyqqrpmq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtynwywhox.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtxhdzmqir.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtrglywxee.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtzqwesjpo.html


<!-- 参考信息 -->