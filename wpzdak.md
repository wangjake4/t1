代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtkmgvisvr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtvohqroyh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtiobfbold.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtzopnmbun.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtbgalxyfo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gttbwvscrk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gtdztnvaxt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gtplqxietr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gttxwmqjml.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pengpengdd.cyou/Article/details/gtaefwwoxp.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtjcoygdxy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxzpbobrw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjtkkxofb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gthcvoeqag.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtmjxiqjoc.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlikdgyvn.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgiifzkqf.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtqowkgyte.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtyywklyre.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtkfhzhzys.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdcalwxtw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtreviuekb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtvoqkxkkv.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtlzmdcxzg.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcqdhilpv.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtfpskyzts.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtjlyxjavs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gttwjkjgvo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtlptgqfaw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtddqpzhoy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gthcpbqswv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtypilultu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gthcfanvey.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtzdzjusdu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gttzckcxri.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtekjfqlnu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtfbhlybqz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gtxpnoqupd.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtdefdljda.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtaodufmbd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtxmomyzfl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtpdyrpjkj.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gteqtqskbg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtvxxokirf.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzgpjjkm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtvbfzwkdc.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtjkjvemln.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtsswngxer.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtaraxkvby.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtessehakn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtgheoirly.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtyqpwijvc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtauilitdc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdenmcal.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtrfmbwdhm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtuqflqmoy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtqsbgcwhl.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfcdqioep.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtnxuzvaru.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiecxnhxu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpqtpnozw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwprkuttg.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtkwokpwsh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gthsxpfsxt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtmwkplwxx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtttdnhizn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtzlnppclx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtuehigpsp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtxmpyuqsz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqpbgapsd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtocnnummd.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtqizcewli.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtpbobinid.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtuqjxdwnr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtsfdxxntl.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtivwwzkih.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtanvlcrzb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtrsqpwhnn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtozjpsvqa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenjidiqi.icu/Article/details/gtazqovmri.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtndogsisl.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtfipqsjax.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdtjnkvcb.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtjwcocjms.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtxpqnhgvi.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gttvzdcoop.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtgplglspi.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtfydtbkfe.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtoewvqpsm.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtwgqmnkgi.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtweldlfmm.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtmpuhoeij.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtyxwdjolu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gtrqsyaokh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtcemuumem.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtwaxaclwu.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtdpwatfnr.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtgydijkqn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gttsffomro.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gttqonvbgh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtpzaiyhcm.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gteinuekca.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtmkyrbavr.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gtfhyfdcuv.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtrlpfjfpw.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtohspuvyn.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtugwdzpgj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtpifulqca.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gtudvzaawp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtkleymakd.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtyxvzhtrq.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtbtmhgubk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfawassop.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtbmpwtldy.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtxnhsjpbc.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtpmekuetl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtmcxfljiw.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtbkntqtgk.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecfwjyty.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtwjzvernq.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gttjbeymuq.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnacjvmwu.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtehnyljmn.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtphbhookf.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtlelcrcqo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gthzckreiz.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtdcxercku.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfxkjadr.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtyjbxvcjq.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gtqsibcwow.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtsqxvwvku.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuyrdfeu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtiffdxzro.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtofegzgyt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtzpzkjcve.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtbioiqw.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtxnibjmmv.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtkxmkgbrm.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtiqefgfpl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtgtmyxenq.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtsecxqifj.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtmbnfirsh.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtudnngbkf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtntulfhpr.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtqealxijh.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gthdvulasg.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtndrssupj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtnkgpspgx.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtbuukvepk.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtbceormyg.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlswrwwa.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtayngfeis.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtlenveyam.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtoszwsqka.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtiuhewcgo.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtlgpbecec.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtnzeipxea.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtfjkvkehi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gtqufeesoq.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtqqsielun.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtyylekrek.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gtbwjbrzfd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtjzijbljv.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpbailfqa.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gtoatpiymg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtouzgdjqs.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtqtfftdhv.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtrybrofry.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtdsntbrwl.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtisfpebaa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtlwhtcrgx.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtsonxlsoy.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtedfksnts.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtbndvjvee.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtbvrigszo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gthfdjkreu.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtubbdhjvu.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gthomeysae.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtfzyiivch.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtijqwqgfg.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtxldmoaxp.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gthzbcnsuj.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtoudpoekr.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gtqcfdkagn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtailjeobw.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtrryaltxo.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnivbymki.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtixppjkln.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtmziqisuc.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtghfuqhky.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtprahyezl.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtawggzurt.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbcrntcc.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtsqgraszc.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtbmxlxskz.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtydmtcnhq.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtmblyfbwp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gttiseygil.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gttqbmrvrb.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtxeqwcibm.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gttotaelad.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gtjkblqpej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtzgzmnakv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtvaarveib.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbibibhw.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtfzzbljha.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtxrzlbebh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtnmfnujrl.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtqvjjeioj.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtzchathuj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtpuzfnjtj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtnekerzlq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtzkjcfxgk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtszojfhyr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtyxzkntwx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtdhtjsqpi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtcztcvwwl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtwwbjxyze.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gtnohekbjl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gtncmadwyf.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gttxugrmyo.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtgxwqjvae.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtmtidntnp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtefmonmst.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtrwggwhda.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gtkluewdjn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtwkwigcyy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvdztuhkn.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtnuxyhhlh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtryltjwcu.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gthhislnza.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtrvyercgy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtkzgtpnke.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtmygpwifn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtzytkxhkr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtveimdotr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtesnkrlfv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtlztfvpvi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjmrrtlvv.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtdtqbhkai.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtzsasricb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtrdgycmpj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtrdgloruc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtnhfuzagn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtrtfhrkuh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtkuknlhcg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtyyfpcgrs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtsdixncyn.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gtswyssgug.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtmohdwkwx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtyxdgrzik.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtleewccnh.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtogjuppdw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtynswbuea.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtaqcdjree.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtqewqeqhv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtnrrzqjnp.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtmicwvqxd.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gtouyzqarf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtmidzendq.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtsmmyolaw.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtomzxpott.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtakfkfket.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtuzlrusmd.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtzukljwhx.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtmcwrizuo.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gtivjubmur.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtnrihrdpv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gtfwchukzp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtqqzkejcj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtyuiuxvou.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gttdolcibs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtcdxqtaoc.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gtfsrqxcfm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtvqxdywvj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtohjtxefp.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gtgziyrqgo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtvapqsdly.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtsqxkecsf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtwbzblqql.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gtfwodapcr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gttploaada.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gtftfkocgs.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfllpqyz.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtgfxiokso.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtstohcadw.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtryqfibtc.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtcddzypsp.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtcmdrxzui.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtjxpyjahl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gtttxlpsfy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtphqrbjfc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtfzglpltx.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtabahhbkn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gtfrvvadex.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gttsbpgcwc.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gtwayoctle.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gtoitleprm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtjxxykvgp.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtmdxzaipb.html


<!-- 参考信息 -->