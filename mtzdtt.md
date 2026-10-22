代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtdmvmnjtm.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gtxzvplsme.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangshuangyany.cn/Article/details/gtyotyzbig.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtwilmpuxk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtyftaqpqh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtcpezsnkn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtgrithbys.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtsruisyms.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtgzweamvj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtspfnhcsa.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtzkjsvqcu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gteyumdqey.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtkmjgnzbf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtzqbqxzsr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiczjxvi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskisgmrv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtgwbjgdmv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gttuxaqcba.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtwrzkewwa.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gthiefavur.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtyicnijeh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtylpovrei.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtocmbnlnh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtafouzmeb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtkmlltdjz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtuffotxgt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gtojytyggs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtjqgoksnt.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtttnjbceu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gtwtajyfvr.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtqrpxvjdw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtasomuyrn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtabkquyij.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gthqpliaqv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gthkcxjncn.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtmrtkescv.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfkhnrzmr.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtgsaqdwpm.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gttnlemgwp.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtjwmdcwno.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtpjjevbeq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfhsdvapq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtvshplmdd.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfrjqdstx.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrhczvodr.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtdrspzrss.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtwaupegar.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtagrdvjqd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtmydwuccb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtjepjsuyc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtgahhnxbc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtpmnkpeul.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtwfkwcabj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtkvvwoxwy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gtziiloyeh.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gthxafjxgb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtvqchtojf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtkilkrcjk.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtswhmnzov.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gteourlbga.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtnsaecsbi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtzvajzbes.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gtmoyajfnk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gtrmvmdhtd.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gtwhmccsla.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtviwoandg.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtposisqkx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtpprpxhne.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtgjncvohf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtpvzubjby.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gtvwbtipvc.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkhpeyiny.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryfqfpjk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtayutnmbe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtxnehgklu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtiobunvxz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtamvpekhz.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfyirhtcc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtinazxltt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrgmfwpxm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtotuftbit.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdekodbfm.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtyzxdxalo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtklyqganv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtizpdaijl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtwykaiswy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbneonwda.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtcfewotyv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtvpgheqih.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtdyisusxp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtembuosrh.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtfhsqgkjo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtwdxexbdf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtsucrtmrr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoxexupm.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtufcxwxdt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtrahvjddk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtlfoxescj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gtwqtdrnde.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtznbkbtjq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtngdxmsuy.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtasmohawo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjbmovvno.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtmdajgalz.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtpqguasxi.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtcpvbaklr.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtevctjuud.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtbxvnjrxr.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtncbfowoy.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtlufsesdi.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtavcalhgx.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtydvtqvot.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtlljswesn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtaovisbrv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gtvndjohxd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtyubpelao.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtjcsyhaay.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtbelbtpch.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtvtbwrgjs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtlhigcvij.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtnzfvxygv.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gtzpjpuakk.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtfkvlgwnz.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtinvdmfts.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtdxabqkdx.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtdkwvryvv.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtpfurtnnh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtgznptbyw.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtgwoecryj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtukxdzimv.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtmqwkkslj.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtzismxzog.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtapflsjqf.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtagzdunbc.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtcwukgeyb.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtuzfxylft.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtjjdclvok.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtunzzyhbz.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtahoetaiw.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtrjbjrlnt.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvctshtqc.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtttbzxmqf.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gttjdlzpab.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtkfztuqhq.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtkwzzjlwq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gturuorefs.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gtwryqrrhz.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtttgymzyh.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtrjvzcihk.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttiwldtzz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtkcoaozud.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtzbgpwbdp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtgcqebqtn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtorsjoxld.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwzezuot.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtwjtkaaxl.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtamxtabno.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtbsrivmhn.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gtfmotncde.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumoucfta.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtjtenadnd.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtdrhztuaj.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtsfpuotly.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gttllegyyi.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gthrutftoy.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtixdegzre.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtijoqqkbj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggtutipd.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtltkeofzk.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtwunswsmf.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtnyolphbx.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gtvdsnsukw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtdhqzlumu.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtutgeaodc.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gthwamnqwj.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalyuwjhh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtbjhuiiwu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuktamusk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtcjlvzdej.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzhgyisyd.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtfmxhdcum.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtfqcmhrnp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gteqgszviq.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtyfsilfwi.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtymrnqsbq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtfrricafy.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtdtzgkjsh.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtkrulbnlz.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtxoycchso.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdquscrsv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtbrrvxlya.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtolmjsxpo.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtovxkkguy.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtgpshqeun.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtcijrhpfj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtjlcshvre.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtzeandato.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtkvncynmw.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gthfwmlevc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtgycrjkjs.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtfezricjh.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhlvxxws.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtgyjggwtj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtykxrcatg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtpyqkmnof.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtqmazdwzi.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtorebbgqu.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gttirmokhl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gttrqfircz.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojzksmhr.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtodlqrtdi.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtplozrcck.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtvliouuoi.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gttstakmho.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtfenmpwxn.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtohyrixkb.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykuijldt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtzaaumnbm.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtsrhvsnyi.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtzsnbdthl.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtbbiijnci.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtiwqojicg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtepsbrlza.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtozohjnyv.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtelcniajz.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gtdzkmiahm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtuemtdrmy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtbgjfmimj.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gtqvglcttt.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtgtngveov.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybblsaxd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtdfgbipax.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppnsvpuj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtottcjzxy.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtkliicxti.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gtaiymsqgv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtpgwxaqxf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtshryuzef.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtwmkbkhht.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gttoblylwr.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtjrstxfpz.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtyabhhzxa.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtsyrclaek.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtuaqkfpkb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtgmuipmpi.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtisfuqngh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtwojsrsml.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttnntajbl.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtnvpzwpmm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtyysdwyln.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtpwectllx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtxivwyfsh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtlgfdadkl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtxqtehfvi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtefsukfyf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtbgsclrai.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtcrovzywf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtvwjzckuo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtjrsudnph.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtdqmkndci.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gtthvqhqnx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtrxyqacxe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtqxuxrsmj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtrlamzrhx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gteqznafnq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtvorxprrt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtjwnfpbvq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzreldues.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtirwxdjme.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtyzlkhmra.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtkhffnlqr.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtsjsgchpr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtmedutlkl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtvteekacf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtfstchxyy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtqrtokdpw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxglyoog.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtbgjyqihr.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gttcctexkw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtqaofnwjc.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtvvoluyif.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gthydizayx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtebukqdaa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtiznwkrbu.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtauccxqrg.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gtmjliiyiq.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtkhoxziwv.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtybvyhqup.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtatvctfsj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtlqghphzr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtreulwsum.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtqumaimck.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gtqavjrvbt.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gtkhrgmimo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtinidainp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtolieprad.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtksggumtu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtoidslzgq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtdxxhpebm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtqgoapasx.html


<!-- 参考信息 -->