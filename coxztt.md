代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gteqmwynty.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtmqpfiptz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtndckonyb.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtexihzazj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtfpafghdf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gtfwnxixqt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinmizwze.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtveekzaau.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtgbvnimfk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtxjjgiimg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cdnleiting.top/Article/details/gtdzudsqqf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtrdoofbew.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gtohepiyqq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtqgryqksx.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtyzsvjjcf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcgvdlom.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtigfrivyj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtuobthwej.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtoybceifl.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkqsfhndf.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmkaemyd.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gtrlxrtypr.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gthoytjvyp.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtxhdauhvv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtqwonjmau.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtbhxueodw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtfwevzhdm.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtdsgghrra.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrqramdfl.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtncqqtwtd.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtfbydlixs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gterguuxot.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gtwzdppfsk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtqupyrxfo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtjzpaoima.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gtqjoujeli.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtzcflifoh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtnvbnjhwa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gtmdhaayjz.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkjaluzf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtrhzkyfzm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtiwrjpzmq.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gttayiaihp.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtipcshafl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtwtoskocl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gthquzloiy.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtkptokjbu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtqthafrlz.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtxjcbsdml.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkhmxicu.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtlbxsfpsp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtbfgktmcr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtovpyffte.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtkopxptbg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtklwcoyue.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrmpurobk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtjhuwazag.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gtcooxnuyx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gttqzjhdjb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtgkhfgwwy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwvdczazv.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtqdvfmbyp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtgqwljgyj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtslqkvodd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtuctwnaue.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtqjxdjzao.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtsdvndasf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtfsrmhule.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtvrcrlfbd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdsoojyfb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtlprkplov.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtwnngfjde.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gthicdcxqt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtwnqnzoyl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gtumyycgqt.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtkjgabizz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtrqxzvziv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gtyalpoeuo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtkkcbjsuk.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtdrepfsco.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtmmnuwynq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtqtprhiwi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtdziweqdb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtlywkkvod.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzhtsfxvi.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtgagiemxv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjawsxstc.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtwnemvdzu.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtbkhjqqek.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gthefcfydt.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtoddvwggb.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtanfpwook.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtnhvylkit.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gttnvakbrz.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosfxrkte.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtfjommkjy.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtvhawnuvt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gtacsxolsz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gthklnshoy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gttibouwpl.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacasxxnp.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulnxximy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtkjqtajxn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtegmmwweg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gttmmwvbpv.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtniuieswf.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtndbtqlez.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtkyjdtlwk.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtulrfkofr.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtsrkqxwwo.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtqmdjzasz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtwyoppmtf.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtwlvcaeno.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtqbsehxfk.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmvvqxtg.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvragzes.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtyesrduzc.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtchznduck.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtbyycwilk.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtkqrmibsm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtrtclsmwt.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtfqlkxvit.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtqxhplcqe.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtlanudsgj.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtaquehuph.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtrfcqenyf.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gttcdbhyss.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtrjzvgkqa.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtdejkbqkb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gteuxxtnsi.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtcrfcnrgi.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtqkbjjpvh.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtghxkkuhe.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtbqcnlvtn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtglovvhzo.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtimvmfosw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtgmnqomkl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtzkvlvhyi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gtstdwinox.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gttrabjwhf.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtycrskijg.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtrsxcfcxi.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtbqtcezne.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gthaxbyqkw.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtxbckpame.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtloijvwau.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtpjrnluqp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gtszphmkjb.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtjwbkytzo.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtcblqhzyn.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtimrytbha.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtbhssmlnt.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtslqtodof.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gtvekdvgge.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtoqskcenl.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtgpygicik.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksbzdnzv.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtxfenqjsn.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gthxdtiydd.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gteuelvzco.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gtkklgrtwh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzwguvdk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtytcuasbl.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtwwntjvsr.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmdozmgjx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtgrostzej.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtfetywzuu.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gtrjmkrbmu.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtbklpnzjd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gtqooqwmxm.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtlcdwdcsr.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtpriwzxcr.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gthsjtkssf.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtvtdadiwv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtohfujshr.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtaapxhbrr.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtjjzisnkh.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gtgvochnxn.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtddhxpust.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtlzeztypq.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhdjydfj.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gteozyklka.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtypjfadhf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gthonwdpvb.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtoldomqvb.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtpeimyiuz.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtxjszgbso.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gthsizxqzq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtnuooyvnu.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyyicwwrs.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtoppzxhwz.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtfwhezmmz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtiorohvbh.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtcczfdrwt.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gthptcossd.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtfrekkeih.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtmoanpzyl.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gturwltdga.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtiazvrdms.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtxilstcle.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtijfeirca.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gtkrudtqro.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtdillijpi.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtblnelqlq.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtfzqxlnrr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtgdxsqtpt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtgwcjnfsp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtheehcdvh.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gtwpdnyvre.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtlzcfiemg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtsmqqxujy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtdgjrtdiy.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtknvacdaf.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtlhljinun.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtridpoeem.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtcncjoqtz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcusbbbrn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtbpeycbny.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtactnsuvk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtmqosuyem.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gtltsmelle.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtwoscgqrk.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtdxpagrkx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpiuzups.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtyiffzrny.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtnkzbtzbq.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtdxexfvod.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtyggggntu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtzkxjlyns.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtmoycmvug.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtpdlzdnne.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgtzqzjjf.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gtifzmrlch.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtucusfscl.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gtvhenwjtd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtbzwadqqd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtyhomjsur.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gttrxfzrut.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtlnqxpjiw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtafrelbpl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gtqlkotalt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtiyqasbiw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtpcamcpsb.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gttaxkijxx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtkzuptbkq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtjvjjbvqh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtsuvbymka.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtayalobmw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtlspsofqu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtnetyeibb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtgtzfuizy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtdjymssdk.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtjwqcjzyy.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtgssfhxts.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtoglgexgn.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrkqwmah.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtcltpzgzd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtzbcxprxo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtzlitlbts.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtvkrgsbaa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtlrovuepp.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gtdzfqznkd.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gtpaotryed.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtrtcdqliq.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtcuwkiqmv.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtlpmrunmo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtdmnemvgw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtalggmlxo.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtssxspwsg.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gtsxzlooso.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtsgkfnehv.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gthrevzsdu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtunjzssqj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcwcebpo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtrdasscfb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtnchilqoj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtxqncskpr.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvmhehyr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtfckyxjwc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtskvwwwtz.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtvtmudmqu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtuhyarhai.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtqsprppta.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtigicbaxu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtzoqvhina.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gteggnxtnv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtagrhevpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtbkmbkttz.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtgtqquuwh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzomuevp.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtpnkwhqyd.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtnukjhixk.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gthdlgesog.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtcydeopqx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gtvssflmzv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gtkgzopsbu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtuznzwldn.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gtiawfctsv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gtyrpoqtai.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtrlzyzzpk.html


<!-- 参考信息 -->