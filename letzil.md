代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtnykikwln.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqqhorln.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtvuobutqs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtoqftfptq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtqxkbcrmu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtkowtxozk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gteomqjirr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gtmsnnmwga.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtnkrucfgt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtigfqhmqp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtaxisonpy.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gttbevojpd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhcblxsa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtosdaojyo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruyxoiuq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhozjski.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtbqwicxwj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gthrxhhqvy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtrucnnqeh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtgchtkcpm.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gthtvkvoae.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gtunvnodix.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngncodai.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtuliovgra.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnjazpcxa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtsxfhiefx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gtimzocbqb.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtevneqdmz.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtklkgpjgr.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtjxfwsavz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvylhbsoe.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaevsisy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtkpdszaao.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtflrqtmvk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtjlcbfyce.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gthcmcawdc.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgnveefut.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtwotmxqep.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtcydmxeuo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtbrzvjxpm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqfucozk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gthnoxbmem.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulhzffzn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtciuhbgiz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtbwkjivcn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtvlkcjdqk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtdileiyyx.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtvwtrmrpv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtfqswqzol.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gthsqnquxg.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtbwtzgcdt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcjlfgkr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtuukwmaeu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gtxznlwebx.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gtoyegibpa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtlsmexjho.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gtclohehvg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtkdabhulv.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtixhfinlw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtchwppisx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtguqoxlhm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtkiprvxik.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtutiorseu.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzulfdlrh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtihiwkgjz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtplbnvszq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtoaituneu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqwioyqp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzbyahhdv.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzxstctvk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtitqhjaoa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbsqyzour.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gttfvqhzhs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gttbnnvjbd.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtooivgxqj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvbfbybkz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtvslvjbbq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtadethiox.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtonlymtwo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtzxzmqytm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gtojfbinye.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtkbymgjfg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtdfpozdtq.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtadqoxvcp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtupomffjm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gttfbjclfs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gtjdeqfjml.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgggnopk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtshkgkhpg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtnkfflukc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtlwlyhfuh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtepheziuq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtzilwxaed.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtcztrtmuy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtllkqoaca.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtlkggzgwz.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtsiqxtzpq.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtjuwjwnia.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtrqgjikuq.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gtapgvnbul.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgzkuujn.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtrpikfmfy.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtvxbtrcsw.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpworqtyw.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtxurjecer.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gthbztsabi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtyihrmypt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtulzeocpq.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtpxgykicx.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtzeshbukv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gtmychzgmn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtyfsecjjw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtollmwuvl.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtdpgsxiqx.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtmpxvelai.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtaeningjs.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtxbcyjund.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtfkxxryhp.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtfkkwrjso.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtiqynbgde.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtvmdiqbyt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtsyoqfcdr.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtmcsdnlns.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtbrnwlsye.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqdsyogc.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtgpbflenl.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtigfsyigg.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gthbnidvbr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtyzdmbpic.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gttarfyfec.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtaeejqgzs.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gtevvlvdnj.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtjxzwntru.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtacznnuih.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtdxzyjllc.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtazysaxgn.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtfabzpkbk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gttwyvjenw.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtzfzeubgs.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtjinhgjgy.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtgfdscksh.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtoqjrgawh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtsiyvvoic.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtkzytsogr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtxxzxgack.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtxbtmuwpe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtlpfhvgjm.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gteavokvtj.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtudifcqkd.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtxafcbstj.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyytbjde.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtosqbwplf.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtsthxycgk.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gthiclmmgz.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtzakdotzq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtfeetxvcf.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtikiksken.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtrfmpjiui.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtcmgxsqfh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gttxrybxio.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtvmislgeh.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtbfjturlx.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtibizmjvy.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtxlwbwqms.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtquclvwcp.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtzxgjjmaf.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gthsmriqno.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gtfpwilcaw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtfhntonel.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtdqdzdbsn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gteoklncgh.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtlndhfwxa.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gttuavisrn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gtcqdlpaht.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtxhkftsui.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtmoyuynmv.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtedypiozb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtcjrabvsv.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtfthaoulg.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtvzvhahcb.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtqhtidzsx.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtnizmqeri.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtseziitfk.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtezbmlyme.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtkoyrsilb.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtkcnxmztu.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gtxhvcphdl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtxfbijumk.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtfoxujkss.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtgcgngyso.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtqcjdaseb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtxeafpwqs.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtqutxcgmh.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdjldtrqr.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtezllqipj.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtoxopttsn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gthjhyyspa.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtxtphqkvd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtjwkpdopi.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtngqnrvwg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtsniblhbi.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtjsischpa.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtqoivglrf.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtwchagyce.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtlpvlgpmq.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtoeddbojk.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtjkmsrxhp.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtwtazubta.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtlevnpjcf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gtnnxtfyem.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtjnekslgv.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtktzmwmgm.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gthayiyghx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtatljktur.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtuzeybsxw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtoieiyyoi.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtpxblexmo.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gthbwgbouy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtgplmmixy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtpsfxqibf.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtcrurfkxb.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtsuamiuma.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtxsyxeroo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gttaqezkpj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtfcnbwdmp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtaksipqmf.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtfedhiexu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtlydtnmzo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtvcwcworz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtbeqmdkdm.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtzycfkomt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtrpsqatbi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtzkjcchgt.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtqjvuvatl.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtaqcubajd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrrjhbaj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gtgkrpyvqn.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtleuyaewp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtkxghkkzd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxzgovaob.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsxnuiqc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtduwsiaof.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtryjuapei.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtfcnovxmc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtrjdiujfm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwndgvnar.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtnqmfyghn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtdwwnydci.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtptayawxe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtwhihbjin.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtetyepawx.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtijcqidpm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtnprezyjt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtrbdgnuge.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtsoritpke.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gthrpatmet.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gttjbgomzq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtukdquutr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtzcdhokqo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtraehrzha.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtsherfevm.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtvhiwrvsy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtrkcxxkki.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtipthxvxv.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtnoavouwg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtgeonjbsd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtzwhexkyf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtdxjcnlmv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtvqfwyomc.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtuwpihfsz.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtboiosowh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtruajunue.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gttlisihbj.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtmwguatsb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gttkhejtqm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtbliuomvi.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtgqysfcfl.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtdimwetjl.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gtiqmidcry.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhsqbvzy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gtaswdpbhy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtttumherg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrnwdqkvv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtuxiqknnc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gthezyjihd.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gtzpzxeofe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtmbftnrmw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtmzrvoohc.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtvsaecihw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtmonxmrvj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtuethuvcr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtiyotdcfh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtwiuvrwsm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gtdvduhwvd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtdibjtdkl.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtzxexbdfg.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gteetomigf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gthscytndj.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtchskhfba.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtjepsyfsl.html


<!-- 参考信息 -->