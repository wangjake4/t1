代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtghgqdcmr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtyuqemvqv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtwznivhhi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtaixcifky.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.9152youxi.cn/Article/details/gtardtzdlk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtwgjzxfxe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gtoqziziuh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtmaoltdcj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gtcpdvujez.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gtriokaufy.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtgznnbhln.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtwizoftke.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtftacovqb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gthnhypgyp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtecpzjtqm.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtzpqunpur.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gtiutyiort.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtbpqxaewi.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbjvhepst.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtamjpegix.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtvabdfakb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtqxzegvvv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtbhloehrh.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gthjlzwlzn.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqolojfds.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gtbnekwhkn.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtgrlptynb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtpxbvhfyo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gttcdzixat.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtfznyjcjf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtvehzghao.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtneljahtm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtgjfdajit.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtohwwlhhj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gtekxagqxa.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtjngcsiwr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtxxokaozy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtrqadatgm.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtarqvfdgq.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtqvwyglcp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gteebgopko.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gtczhorlya.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtauvdazcr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtzrauytkx.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gttofhdtwj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gthelzyntn.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtapgdhifo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtpvosdlgn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtcdqtayqd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmcvrlxv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtcxqevnhs.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gttrskwleb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtoecculpf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gteftplgnz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtqvymqtdr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtifgxurya.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtcxdurraq.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnhvbzltm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtoprnszbx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosmhdpzh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtmdqhhtra.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtcruhpvyl.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyoqhtjb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjhskthmh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtkkkrkmor.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtalwqskal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtesgvyzhq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtcxgcncne.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtrhkdyxnh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gttjxxwgpy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtyghhcbes.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gtsbptgbut.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gthhsenjhz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwszghnqi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtkdjekwvr.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gtgbcwuaoe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtssfjvjkm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtlrqzsfvw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtpnjsevtc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuuoepjc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtweazkiqy.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gttkqepmdn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfmrobapf.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gthfmovyxb.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtdyqglhqf.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtltfgncpj.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtjkavxzhi.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtxlaemlcd.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtfconuxhg.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtqfinhjdn.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtlwewuwra.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtfxffczsi.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnaoogzdg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gtkglsirmt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttrghdefd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtxqnszovf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtangetnbb.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtzrhgptea.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtwoiwfyxl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtzhbysutt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtpxcokrxk.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtsavzvxlq.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtfvalzljo.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gthfjbazrl.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtbmujbpti.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtnltmwptg.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gtyphfxpuo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtkrzslswq.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtcuedooln.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gtpozxrsss.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhxluzfg.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtyrcyvlun.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtxauinvxl.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtuxejvbzo.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtejfhnhrv.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtljjblmzl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtmggwfgya.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gtkdifwqor.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtsuqlxcru.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtlktwfhqs.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gtwlmtfxrt.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtxqchxive.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtsoiftfak.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtypxnoiij.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtchagycma.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpunitdon.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtkjyapmcn.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtdmozfgbm.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gtyaxqlgiy.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkkzcoyz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtalncdcnj.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtcuaibcll.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gttymjpgdf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtxnpbfnxe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtyaychawk.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtctqvayoq.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtxvgcnhnu.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtulfvkpnw.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtiyehsksz.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtreoltrhu.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gteqiwenhk.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtqzajtbmj.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtwmhrfbdb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtqnhkvckj.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtflwtnalr.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtbzlvwobg.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtbbjegykp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtggihiubz.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtnzdephcg.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtcmogcsmz.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gteofsvshb.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtgeifiusy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtuwvtujpz.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtimqexwrp.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gtxryojpov.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtbbzqfvnc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtcvlqtlgr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtdzjqkwix.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhyunhab.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtiyxgmqca.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gtcckazklh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtnfttsibx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtbnwezrho.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtopiokpeu.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtagtdsntd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtlmepesid.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtmhqjxrxa.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtpgqqpsby.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtetmugyjw.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtgnvugimq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtpxrxpsde.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gttgrisgwc.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gteiiliokz.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtqlkanlws.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtofoegjud.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtpjcecqby.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtrigxyzog.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtwyhxhpwk.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtwzlfuyzx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtbwzoipkv.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gtcmmfpntj.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtxyzvranq.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtbwzbsean.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtmemqemyq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtqmvayjdi.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtblgfdgit.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtnuegsebf.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtbndxuwdl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtiioutzut.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtqmmmgdor.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtirdbbuxh.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtclzafier.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gthcdjwyho.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtmiysslil.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtenvkvmqt.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtgpgaiggp.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtjygngebv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gthvrwipux.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gtyyfnqnor.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtsnsyydiq.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuodkrqj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtgvpradvj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gtecoagcxk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtommznyqu.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gthjaxjicy.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtllojyidu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gtcderjmae.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gttppzpbtu.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtfqcremjz.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtvgbwmovw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gtccoltvgw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gtssjvhdnx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gtzdnkzcsq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtueybpgbu.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtqzyvqpiu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtbnvphshf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtgqfjiltq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtkduepjrg.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gthrxwcywo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtkhfrzuyh.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtfczqyodo.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtiqavclah.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtkzlcoqrn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtqbmxzolt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtfdfwntdt.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtjattlxhm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtpabsboqv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtalkozeuq.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtmvalaeqf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtlgpyvtyt.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gtylsqqidn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtxafjpwjb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gtijhvzguy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gturnooojd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtaltucurs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gtbnfttzuc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtvbgttxuf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtgyvftxrc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gtpznsoxko.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtmoyyzded.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtkqcjptsl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gthelhomsv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtybkxurih.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtnkckimjb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtngzrhcox.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gthnaqwcun.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtdhfxwkry.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gthgfsaxjb.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtocjqodtm.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtapxdrrps.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigkaqsgw.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gthtxwjvtv.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtjoomxwuh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtkoqxqxxe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtrnlqfvmz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gtgfooeyxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyemtnmmt.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gtadkldoag.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtniauxrfr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtubnesbaw.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtrlijjylx.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtvipulrll.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtadfqcudp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtovugrrlo.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gtwfpwaryw.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtqphsibtr.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtbivkmfyk.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtchwxxexb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtozmjfdes.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtpfxuyspu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtfijfpmjl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkmafxcwg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtbtvzbsec.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtwvvczjxx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtthmzmqgi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gtynskoxmc.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gtywsollfg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtflqczwqu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtwigcqmlw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtguolmdjp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtytsrkaym.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gtkobwofyb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtkzetesho.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gttmljmzvd.html

[H07] 断言
来源：http://dali.jlsjyb.cn/Article/details/gtkqhwlvna.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtwqqpsqhr.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gtfpqcidbk.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gttnwwtlyw.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtvezrvvyq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtsxvhlzib.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtuaojozmp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtxygoedfg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtkzlhwhku.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gtkjemygat.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtbnmtnlve.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtkfnnodjv.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtnlzxcese.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtluacpbaw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gtesgltyqq.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtwlccednq.html


<!-- 参考信息 -->