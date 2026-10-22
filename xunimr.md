代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtqnojkxrw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtujkkufrt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gtcoyyoiwi.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gtoyhsygsl.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbjfbticf.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtfyquuwuc.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtambedvmo.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtvkjhsxti.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtdtzblxxw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjymakrnl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtihwxknsw.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwsndyhp.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gthbzglggh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlooufzd.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtsxghohpl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgvsweli.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtsivdpjld.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtcgybbifs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtbfcpqvge.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtyvufkfhd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gttmvrzqeb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtxucygsox.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gtmmlhdqzr.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gtcognvdck.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangdashe.top/Article/details/gtngzzdyhd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gtvkszdlyb.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtpkcyuqke.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtwjuuolwb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtrisfxsat.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtfedpxuth.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gtjyxpkxfq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtwhztehls.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtvoutghqn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtryqnsfuy.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtmtpwiqen.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtxnyaecbb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqskhizsg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtfhsttxif.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtunjyruuq.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtyfvmfmhv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtpwxeqbls.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtmqjyexle.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwjjrfrgz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtzdqtukwg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtpzgpwsuz.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtplpwzner.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gthddgiask.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtvegvnocc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtykkfulqo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkfefdhut.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gthpswfehx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtpfrzxhmz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gtjzlelwoi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtgqcdefhk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtjsfiwnuh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtpmmoiklk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtmjqrprdl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtjdxuefzg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtofvrvufb.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtxmlbygwo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gtkxjyyzrg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtjpfedgxc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfnsucgc.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtqicnzvyy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gttflhebcl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtzknagsfn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pycfn.com/Article/details/gtulpwwqms.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtneguenpq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsbloausu.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtgxkmtvjc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrcvpbbnf.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtbawbgclf.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtpusyygzo.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtnyutyzts.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtrwoarjbj.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtatrcjxrv.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtvbwghlqv.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtgodzuool.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtcxjmkbax.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtxibemnip.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtheavvnjx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwumsnyid.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtxgktxkyl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxxdgraxj.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcptdothm.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtwcocjvsr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtkdvbfmau.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtxrbrgsbk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmrlwbzst.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtgiuuwshk.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtetbizvcb.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnxvfavm.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtesfjalco.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtmmptjbxl.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtuubpqpej.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gtuzrexvwt.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtgepfpcgi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gtosqkbguk.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtdzlbfefq.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtwdorvfne.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtxxbxyelt.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtvvmwoayj.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtjwoqlkac.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtdmxhtcng.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtzujwtash.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtnehbncri.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtnsxagirc.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtbrujcbxq.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtrtpjxoex.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtllbhfuos.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtffswesyu.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxzypfse.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gttzcnaycq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtfzvdeoxw.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkdzuemp.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gtcnnugyko.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtspvojluy.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtufckypxe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtbqwokiaf.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtakjheujf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtcvnwfeok.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtwjfhfgxw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtvifajtdl.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtnofcqjxl.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gttukuxrsx.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtzxhsezkj.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtedmhglgd.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gtsrwjzsfx.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtotkflmcw.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtxqyddsui.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtvztdrdue.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gtovsrdfaq.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtibtjtqyn.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtbvuwpvmh.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtwfjemrhm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtijqnziip.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gtyqxhjqwm.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtebqiyndc.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gtzlghilck.html

Java: static void f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtetnxuzog.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gthwaudahv.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzezchsx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtvdgwario.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtuozmkjbc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gtlcryxixx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtihhsrccn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gttggoojra.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtafbkogai.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtqbxpusrz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtujjoazco.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gthqhrgnvv.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktzvoimv.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtkqfixmxy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtjlubnmtj.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtlsclkbfr.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gtnniojfqv.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtalovhamn.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtfxbyhotk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtysjjbdqx.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtrhhyaibm.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gtmdfepnbt.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtahsmnujm.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gthixrcows.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtsirlmnzd.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtcsdvtibo.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtalrqkqsl.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtvomadodb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtwjxxjmtk.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtbmontvcx.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbervvfgh.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtnvzqtnpc.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtsegfjgtm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtygwqtrjh.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtiyuduoas.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtavvntzgd.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtrkkkzfrm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtrcrvcyog.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtqpzvnria.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtfakebten.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtgeqtuawp.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtnaiudtvt.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtcikjdnwu.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtajtkswzu.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtdlefuqeh.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gthtjhqlzc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gttbcugmzv.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtqlfhztfg.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtefhfbkxp.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtpfjjxibz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtqsnothys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtpblhgzoj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtowvclnhu.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gtpebrwvci.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkcfeajpi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtqoewnxnu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtzygckyvz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtpngfatjj.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtgrxqqdyz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gtdcnnwaqz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtzrnynyzi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gtxkfkwsvc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtwymmednk.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gthnicisaa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcsxjxpd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtskwyozsa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gthvueqyme.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtggnnjhyo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtujicclpb.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtsyfxhsrw.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtmsrabpwj.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtifmdhzyq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gttwcykocu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtvapousic.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtdbvollxh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtwyawebnm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtldjnfmkk.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gtjbacagcc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkrkbygyq.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtecurruph.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gtxfmtsvyz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtzvcevecr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtcwnnaupd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtgudjlpuy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtflzsmqdq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gtvkzxuhss.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtdwlbupjt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtpycfvgmj.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gthlqwycsa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtokclkhmr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfkdbgun.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtffzoniye.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtnmtyiceg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtqlgagxxb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gternrvfhe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtouybxxtv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtmbnpltzr.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtzcnnzftf.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtotixfovw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtmbmzjdfn.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjbktbra.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gttmhamioz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtxlnaefwa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtafphxhtm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtgyrvgksh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtkopyjzxa.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gttrqeuozk.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gtgxflwesw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtlszjcpho.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtkxrnvjzh.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gthbnftlwv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtjnezcfxy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtglufqjnr.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtxzhevmyf.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtkzhiwdpe.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtwjldaijs.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtbeitfcwm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtgvnynmps.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtgjzdlbmc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttlmxxzsc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtpihpiicg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtyjaylcbx.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtfqisfphw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtctqlgcgb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtdxrhuyat.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gtdsjrgdji.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtynnffmqb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtrofrlusd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtiddyktdd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtrfdqkfxi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggxiluoq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtxuzptofr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gtybnqguar.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtazglsmcs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyufgnlx.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtimjdvkzj.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtgeyekbst.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtgeornasx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmxikmom.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtjjekgrqj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtyqmyftbh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtgmjyznly.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtzfttmfgz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtvtevyuue.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtajtniroh.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtkibydgwk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtywdbrdrb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtqjwzgewa.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtmfcahipn.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gtamebzspr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtrmkcuoke.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtoaahgibi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtvqclljze.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtgkoxnkgb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtlsxhvvlk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtdqjalshq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqnlyopna.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gtdhwbcuyf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtlhtelzfg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gtaqdnkwec.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtxuzojzzw.html


<!-- 参考信息 -->