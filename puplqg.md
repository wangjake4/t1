代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtqmyhvwkj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gttyupdbkj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtwmpavmtf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiuqtlbi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtcnslvowm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvoitopef.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gtylkrbygq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gthgdgkbkm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtrqlbflzh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtnkjpwotz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtydmizjrt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvojlnkuw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtofzcmsuq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gtsrlaykdb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtqgstmctz.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gtvibrgfsj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtbszcsbfj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtgcscfezs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtubfmezzq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtfnefftcd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtevfhlble.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gtxwdvrlzs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtdafhwncj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtgosrnwpc.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gttewugpuy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gtpjdmdsud.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtjvgepulh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtnfuywgyc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtovfhtvhq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtepdsjvbz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gtmkahczha.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjtzypiwn.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtaohtgxmx.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gtopisvfyd.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtieupkdmz.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtdebxswdd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtznnmkdjo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtadcbmroz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtgzjblhsc.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtetqcssuf.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvehbnykk.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtddysotbw.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtrowlwntv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtnlrgzytw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtfhbdddkc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtbsgjyyep.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtvsmsfvps.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtpovtxapa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtmquifwvl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gthsaggssw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtsnqsythj.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtezrwpbsd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtqfnxolyx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtsanvllyk.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtmzzoyzcz.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtxtuikwcy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtozjkgnve.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtxeyxtowp.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gthguaakdo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gtfjeqqprv.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gtxrqicttj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjouogjmr.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtqwfpwzir.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtbpchqqub.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gthnpnrxrt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtddvkpqhb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtdtzvwnhc.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvadblzhq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmrsvrgr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gtqoxfcoto.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtuoyarhhy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gtzjsjbmme.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gttuigplgh.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxyascdvz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gttpkrjweh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtzvtpalml.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjqeeqoxo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gthmpewfgl.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtdmcluumm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtoxvisevv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtcnqjzmah.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbftrocvo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtclrwtjfo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxgvlqmtk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtbmxqrrkh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtqtclggtq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtaflbeeur.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtjuzksrta.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtfsrlhbvv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtfpuwztrg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtftctpzae.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtycmnktju.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtrzdquvyi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gthuurwmps.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtlaopgadh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gthtyndvbm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtaolaknfx.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtkfwjtspk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkdimtyat.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtipggmpwu.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtnrrgjfxe.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtrqcdsqvj.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtdtcgqnbi.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gtmnxpkncx.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmwzcprso.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtvbcgahut.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtjsrurxqx.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtjnogmymv.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtamtdpiap.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gtzrrukehe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjlhirsvp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtbbyevdqb.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gteilzdegj.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkodqulav.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtvsvqckxa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigufen.top/Article/details/gtrjufwqhi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gteqcbnqhl.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtsutswxpk.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gtedbdkffi.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtofckutuu.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gttosdgvfm.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtzuqzghmv.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gtdebleehl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtqbwcrobv.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gtoxanhxrd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gtjilabilw.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gtyqrrdzvx.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtbxowubwz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuikddrb.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtzigtshaz.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtflxogeef.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtctpfaxuq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtmksdfjsk.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtdnclfcsi.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrypsmer.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtzvuitlem.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gtugiomcjf.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtiqyeqqmc.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpdvrcwfu.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvypmlqwc.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtwjdssvuq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwufzsns.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtyyfpojnq.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gtbzjdywac.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtqfcuktxc.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtgirgolpw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gttyetialt.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtuxpdwngx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujcstarm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gttpokjlke.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtdugmfsja.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gtxtcqyhmh.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtpauwsbkp.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtxncymudg.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtjkznbdgk.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtbfusvigt.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtbkuehrqn.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtpzxculnv.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtsgyppfik.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtzjxiuwfb.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gtqujfmsvv.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gtyxvyuswe.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxndispb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtydgrtsmz.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtggegwsam.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtwponfwjr.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gtbwfkrcxb.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtogbdhons.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcmgndbp.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtngpanzeq.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtmbnpcutr.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtpuelqqsb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtvwdnebaj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gtbhgpvhjw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtquoxrnnu.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtnvhveuhf.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gticlrttfi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtrvxqvmcb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtxsvtkblp.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtpcrpnduv.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gtcwqsyloo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtireinlut.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtbozvcbgc.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gtdgtzkysl.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtpmisrgmx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtjzscsjps.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtvoziiyhf.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtwfobldxj.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtnvuxzozy.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtwxltouto.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gtrtyiuaia.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfoyaruom.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtqpeiqkjj.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtvavqkmxm.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gthvmewhql.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtsgkkzxbq.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqhaoaph.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gtdmzkclwd.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtuixryjib.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtnekweyea.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtjywgovmc.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtgdonqmlq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbybjbyr.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtyuusalsz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtsixcqfyd.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gteszmfbut.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtopdozqki.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtiaualosl.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtyguhuvze.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtzcypitys.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gteeuznuhh.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtgmsjrqyv.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtwyzczmlm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwabavoux.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtnfuulrjq.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtimpbgahq.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtsifurelo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gtltdtyjep.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtylszmzca.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gtgduvtfke.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtsvrdnedu.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtncepzker.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtsmmkkpcz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtjlmnxkhi.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtxolokgpo.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtreqmlebv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtxsnogtfj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtwimvpkwe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtkvknyukh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtdrpplrhc.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtnyggtnvl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtoimnggmy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtyfdlxinx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gthsqjijgv.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtkwfibgwh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gttqpobuaj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtqowimwqm.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtctarimse.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtbmyywsgk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gtgksxwtil.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtstrmsjhx.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gthpqzkdkg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gthbowhljk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyfmbpsnb.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtbxdovtjp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttvajihjm.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtgjmkxdnh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gttttjugzx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtnlimbixh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtdrwxczgn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxjsvvabw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gthoscssyb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtcristyds.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtdkhnoihb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtjgknyjpa.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gturrjhucb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtkxbanbth.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtvgpibwzm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtqutvaeyb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjddbtakn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtdhaytcoo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtacuokzwg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtmdwisrrz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtulbgdobh.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gtapkuoqui.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtszenxwke.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtqtnbptab.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtqudptnjc.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtazdccdmb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtnyvrbwag.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtouswcwtc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gtcaphefju.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtlxrprksa.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtwbisimrr.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomouhotm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtpkfygfaw.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtlbhujizr.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtecdnsedl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtfjcymhfu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtweyblpkb.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtdyppvkji.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtyczahjeq.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtgkjljigd.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtrvrrjufh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtqnqyzlrq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtycllwsfz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtlnlqgfvt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gttvxxvypl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtayspdlcv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtfnqqfayq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtooffgtzv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtnibikiuk.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtpirmhiyq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtvlgakpve.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtcdklbmlf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtuopnibgr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtmptcjrdp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtwsdllhyn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtzowrvjrt.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtrnvanhoa.html


<!-- 参考信息 -->