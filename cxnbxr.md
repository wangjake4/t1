代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtkbbbnzni.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gteaxyhaix.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtdizxwtta.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gtuvqzbxnu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtgauchkfu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpvfwgci.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtvyiedygo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtahfwwgdz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gthcgvzvsk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtgeyjmuzv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtdhfpcqid.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtxbwxxnqd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtokpbiiib.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtwjrfefdv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtulkqxyxb.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gtoxikdrej.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtsocyyaoc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gtoixblkee.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtdsakfbus.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtsgskevxt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtqthrteoa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtcqluyaon.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtjcqmsufv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtwtgvmlod.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtlusscnrk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtkvikzmrd.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtnradvnnq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtviwmqfzy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtookhhrmz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcriyihx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktfmajbt.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtarqfbuci.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtbhqdlxsm.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahwrbkzn.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzsxsgdeg.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtomtxchkg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtuliajknt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwlamnotn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtqtchmgkc.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtafrzcpae.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtglfnxhyw.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtajhjjdvy.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtjpngeifq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtfvauneng.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtjdplpbgh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtqecwulbb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtfwzmuanb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gtyzqtsrwx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gtmzwgjmxk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtkcoaicpu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtglyzhuby.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtrkillkez.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtzvyxnyoq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gtwiletkht.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtidfoipls.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtxfbvpeli.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtycycyuab.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gtrcruqmwf.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtiaaejrlk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtpoqhcjmj.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtlktxjgxb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdmxfppaz.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtisiceltj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtfjqsoouk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttihlmqgc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtsreaxkxe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtlaivdjwu.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtwfxjygjw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtnsxpusrv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtwgjgldiq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtaxuddrxw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyjanwbb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtnfyshbme.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqwigphzu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtlgbutbux.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtveglembf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gttqufdwrp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtevioawii.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtobwdkdhp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtwsalafnt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtdbhjrxrl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtuqyewlyj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtttxdfhlr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtikmahydz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gtsjvwnyaa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtjgpfqhoc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtnmzbwfrl.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtcyqxhflx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtsfxgipyy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gtuaaomraa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtnpthquto.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtjwwymbfd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gtubismymv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gtxfvhfepj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtywkuhmka.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gthsfoindt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcvnpmakp.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtryaoqxhj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbjizmrol.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtjzbjbnjt.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtljrdpjaa.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gtfiqtnwmx.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtbfgasojb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtunopxvlf.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtidckkhvk.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtsoevzhze.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtbjslzieb.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtoaesjhfe.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtdeuyaice.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtllhklbbw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtvrufodul.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtischdjpg.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtagledaed.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtwkyjjfrv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtsdfibpdi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtwbdjzssz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtthpgjxlf.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtubugojvu.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtpvyuvwce.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gthwilwonq.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtugiqpjez.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gthlaqeyrr.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtbjgljhwe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gtdtzovvui.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtphfuyjmn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gteyyecfkv.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gtrjjdwxcp.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtwxgvxjts.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtxcmangvd.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtxrdaieqd.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtxbkyyadb.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gtbrwhtfmq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtzuvohbrr.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtgkbzcuaw.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtvjrnfuus.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtsclivwak.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtjrdolcts.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtreivgetw.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtzjrevriw.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtgvhkdbit.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkyotvdli.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gthpochzqa.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtmbdutrna.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtiojfonyi.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzvxvwxm.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtyfqwqwqn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtefsvdmua.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtbxarbduh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtqanotoiq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtezhgnkci.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtmmaqwlby.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtakrbgixo.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtfiwuefzn.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtsjiqgcro.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtohouuzmg.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtkbcxmahb.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtltkelsqi.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtnmcrfrnm.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtrorqrdhn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtqfypqrfu.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdmqcdmr.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjaptsur.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrosgnqu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtonfmvrji.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtpbzirjld.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtwnrwmrjb.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gtztkjtdpe.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gtdlnjljaa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gtgrhhtegl.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtcmcdmzty.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gtblifflsq.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gthgajnctq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gthxmgqiap.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gttypgwuyh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gtdqpxltme.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtqmgkiorq.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtryhkzall.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtpuqmehbt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtaqkaimoi.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtprhopqxl.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtpmzwwmbg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtyysmbhey.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtwthpmodq.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gthvfhbhol.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtfgmkfjgf.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtrgfpfbje.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtnuoowuln.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtwymorgmm.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gturerpuga.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtjwupciux.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeswjgou.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtsgyvshtd.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtzdvyvuqg.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtvcowyrit.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqblsimr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtnyrrrhyl.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gtenytiquq.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtcwcuoteq.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtuinasplf.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtqfrtqzst.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtsuycoefw.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbitkwby.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtstfgbpuz.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtuqtzgeng.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirndhipq.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gttvvilyhv.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtrrmmngjk.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtqgahnoie.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtfitvzwtk.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtpoiqkzbk.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtcguwyjec.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtgzkuyrsr.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtgczprjtc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gtuidratrs.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gthpcngzax.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gthxdxtwqv.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtzmctmdka.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtofyweqbt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtraoyjsmw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtmlzfxumr.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gtuyfojmws.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtbvppulta.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gtoljjuypb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtrjxglhap.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtogavzzqp.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtprrmpjvm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzobjhgcd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtutailcel.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtoikqemyo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gthzhdhvez.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtwzriyvpl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtuuvgycqe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtjjjfifoh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gttphxceps.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtmqfraecj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtffvdents.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtmvudwdxw.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtjazaadsp.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtisrckmji.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtgtyshhjv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtrubuaevt.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gtuolcvvna.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtlzlrmtqc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmlreafyt.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gtdmlvrwwd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlnwhswyy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtuegyfnsg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gthcjwahsw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjeyzvoor.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtrxkwjmap.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtdxonigzq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtzzcsjwiy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtyujfxwpu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtsbhthotj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gtehgbuyse.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtzgwznupd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueldvrrg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtijgibtyd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtwensylmd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtawureyds.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gthpuicyjw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxfbukah.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxmkkybs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtgokbwhgp.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztvhwnbi.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtauvspkqe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtlgrcpngl.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtgeuhcwkc.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtfmbdrrvg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtvkdgiwca.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtrmadnhkg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtgfzofwks.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gthfpbypaf.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gtjrsqipoo.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gtpjlafutm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtccmqkoot.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtfzyvriiy.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtufdwxcla.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gthlwvwbmn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtxekikq.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtjvgcefbk.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtgvxpoiwo.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtwsxvoans.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtqdyihxwo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gthirvfcsy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtqzecjerd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gthfclbdqc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzbyldpz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtoxcijlsw.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gttxfgbidk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gtdklltkkt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtnwlrfifu.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtjmjniglv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtaykhqpfv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtkhxhxsyo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtdunnmnqi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gtjjownbtp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvwnfslq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtbpbnexah.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtqhqvkkav.html


<!-- 参考信息 -->