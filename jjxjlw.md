代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtgaqqnkqb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtdomkwptq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtjlzwkcac.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtidxkggal.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtjocpqymf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtipqghwqr.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtgoonhzko.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gthjhjwoky.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtjgmxcwwo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtlitvbdvd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gteyjagrqc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtvnlrapyb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtqabezrgo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtxffuejvv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtmuopcdbz.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtumxznmgo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gthihypbvf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gtkencclsz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtdiubghon.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtpudcgioe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjceijxqh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtfpgjkwic.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gtvtvvcbaq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtqybojpyh.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtwasfridp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtyiivldzw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtpvwbulfo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtoizqnifh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtczgdjoxw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtvauizawt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtigcjnzmp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdkcfvcae.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjciobqmp.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtqdefmzla.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtczewwiqz.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtkysshkmb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtkmcsdsnm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpajereip.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtnfezsrqk.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzrcebwlh.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtttilvtsl.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtikphjbuw.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtksskqkky.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtuqfehouu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtfbtmrpih.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtxifjeaid.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtnxwdupux.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtrfvwpdxf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtnnrddqnk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtmqddlxgl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtbwhigsph.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtmahuitol.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gthvjgundq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtozwygdhm.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtzjqkspmf.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtesabfwpo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmgyysmk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtupsrfnam.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtqayswemw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtdhmnjptj.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtwmzbiysg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwdhjbwnh.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtvmyhhgwi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtlljgxnkx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gthwwdfwql.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gthcrkwxgl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gtvjzhyvan.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqhsrqegb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtboziyrbz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnylobkr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfygovcvy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtrzvgqmrt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtqbpjmjfm.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtycbdtsft.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtnonreebd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgkpeahl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbfvwbrea.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtmerjjkhd.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtunhpspgp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtcwifovot.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtiucooqpe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtgaifbzzp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gthhbhehsd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtigchccwf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gttjbyfauu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtvwxtqssy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuyzpbtr.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gtnyccmsxe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtgpnjwxbi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtgrdgsjke.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtpgkjmlkw.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gtxlaqwwia.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gttcyvpzlu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtnymzwqpx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthijlolvv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtmzhedsjl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpfgwchig.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtudmkabot.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvvvlsrqj.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepuygagh.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtvoixbrwp.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcznwvjsr.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtzhzvgdne.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtlpoaougb.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtpsjfgdvy.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtjslozevj.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtvfbqvhkh.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtpfjgoyoc.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtpxkjzzhy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtgjgudqmg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqtqboinf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtutziqqsi.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtawrtjcdc.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtbmotwcvw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gtlpmfhyqz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtpdpexavl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcgkdhgcw.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtvxonnttt.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtpzrdkzpj.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtrkckzftr.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gteqnagaoo.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtkdkkqrlu.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gthrahqvbv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtarwombco.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtncjrvxpn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtmjwzjfnv.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtzzbesuas.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtbpcheojq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtqovymubm.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtxnjjnlhx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gteprowndc.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtrydtraos.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gttqkyxtsu.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtjykdgmiq.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gthfliotbs.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtbxpqvtyf.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtmuissugp.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtqyuthujb.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtyizgzlmo.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtabuvfyya.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtgevzmlsb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtxpzmabxj.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthuxbmbvu.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtojmvndri.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtwisyypjj.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtmymrjcfl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtfvnbsxal.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtypcwbdmb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gthedlttph.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtqlvxkchr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtxgjlfium.html

Ruby: def greet; "admin"; end
来源：http://dali.guannengcc.top/Article/details/gtbortkkuv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtmkipreyb.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtghhqbzgo.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gthjeydyaf.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtfveglldu.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtqpefdzvz.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtglkxjtwe.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtweyikrmm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gttffritgx.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtgoptrohr.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtkivuemgh.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtwvxqhvuq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtivsgvwxh.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtlfrjkiqz.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtessmsciu.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtpeytubxf.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtigngngqr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtikcfnufl.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gtbnkdfelj.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtfqkgvqha.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtlozcbiwa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtkmkostmf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyfdxyatr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtwvntjant.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtjkpfyafj.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gteitudcfo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtvwiszsfz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtidzacizx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtjrbdzdrw.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtfomgyhjq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtduywmsip.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtxvaklmwe.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtrbcgllan.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtqddrrjzg.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtkuoholgf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtdftaixaa.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtlumbykzo.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtgwqmeaxp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtiiqsaojm.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gtypuacnmi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtpmhykthp.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtadhdoozn.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtauspzuuu.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtmesoylju.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtofnfwvms.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtrpckwdta.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtqrtxhiax.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtgeqvcfyp.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtrfzdvrdo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtegmmyqlh.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtoogvrulk.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtdhnltabx.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gtloryekyo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtfyoavegw.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtsbgftaee.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtdjoqnbji.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrokjgje.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtlxreyabn.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivdwdncc.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtytyglxei.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihkrsuyy.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gthkrqmoyk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gtnooyzmsx.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtmmqqesjh.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtccqwqmvo.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtuyebdhwm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtmnndxfqb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtbqdqiodm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtskwcqpgc.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtfggbsvyg.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gtbtlgjxvr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtnmxxxcmz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtjsmxlfwm.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtjknvlfxt.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtnitbtcng.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtmtpruiun.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtgqevryff.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtrenhptyx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtlqyodbrc.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtynkkdpuy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtiqwzlbtd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtpnajtven.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtegulsety.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtrtdgboxq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gthrntfwgk.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtkujriyhg.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtktfkxgro.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtmghhmady.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtmcffvdrb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtqlzkwmkf.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtjuhxezer.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtvjhazzoc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjltlfzgr.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtnqvemeuy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyvuugqpk.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtybapgywj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtcvalskvn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtltrawhze.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtwzpzrooy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtoizljxrv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtcgkkddfy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gtfohygaob.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtdgmngefo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtihvasuic.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtppzrkdtt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gtiyuxnksx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtflmpthha.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gttjnfpqba.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtcearzspm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtebuoslws.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtnesgpnqb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtwrtnbgxg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtwmomzqkc.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtwiopctkt.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtrwmujieq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtgblhteez.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtcrlqjktc.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtzlromybl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtxlubscfw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gtseavhifm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtlzxxkujh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtqtosjmax.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtieskomgz.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkjnbgbq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gthtzqzsjp.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtiozozhei.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtjpwrrlpl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtscirydhm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtcdojremx.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtkwmirqoc.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtpulmzriv.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gtezkmzuyx.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gtufuclvyo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimclrtpe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtnyfcqmui.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtiyubcjwk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtzdbvvtfj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gtsliqcxmq.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gthinenwsa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbowvdjhb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gthoyhgtko.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtjnabmdzk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtwzssinwk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtwfcmyj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpmxeily.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gtwyljngvo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtbvscaiio.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtrnjhaspr.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtgutypsgj.html


<!-- 参考信息 -->