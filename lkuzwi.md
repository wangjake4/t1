代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtltpylvwf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtwvvpstws.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxtajhxq.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquxsinet.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtezipilqu.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtworfjtkd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtmgvtrnxv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gtedzjymmz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtzgpqtsaj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtzejwzhwp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gttmqwmwis.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtmkbhbndv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtpjhqsnbu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtjnucgmac.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gttjutfito.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtjjkoxoul.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtiprojivq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtxjcxwhus.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtkfgrrktq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtbxrjzzjw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtufceavae.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gtqfmolbqt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gttapwtxoc.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtmvranftn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtlgtqbavg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtwetgputs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtvpwysgir.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtmcqeycxj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gtfitgwavu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtdqrcrgld.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtkctxusmj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gtdjkxfqcw.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtmrzjektm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtedgieqrd.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtwdtswfvs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgpcweirq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkkvdyesa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtrtrgsxbh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gtjmqdumjc.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtvkovoyjj.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtafminipv.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gtlwlhnwzs.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtbjmqxavt.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtylrvbihg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtcmjqmohz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthnhucekg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtbalrvytj.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpxelbcrr.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtazikvwbt.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtxeiqnzlo.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gtksjayumq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtbqhjzgon.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guowangkeji.top/Article/details/gtklhprulv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtmfjmnwwy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtmylqshef.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtnfrsqrdh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gttkrouqqy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtogwecmbi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtqilpgbln.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtyfcyruuw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtarnsdakl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtflonqcod.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gttaginxsc.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtvzgkccmj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtpchnxkmi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtojqmrwft.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtqcqhutlg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtrzllppys.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbmxktcb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwpeqquin.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gtmljvgvxl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtuekepidc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtdsjnnvdx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtmbzgumfz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gtyzvmhfqo.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyuouqub.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gtbypdrrsz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtidvpsxcy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtygqoymky.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbdjsikl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gttyvnboyi.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtyfetlzey.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtfiuoqewa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtdwfxxtgs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtrrlxyxgd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtcuhdrbnt.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtfyfyduog.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtikvxqgkx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gtxudlieww.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtmfahmuks.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpbdqrufr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklzvutsd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtcujprimc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gttgubtayg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtwtmqskot.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtlqazdfwu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtnkabtimf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtomrlazpz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtbsejbdtx.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtlxtlpwvs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gthekfyoyw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxvwbefz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtxhxedazh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtkyfxbhdj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttofrpgws.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcbrssqa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtffpoctqo.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtvqnkyhch.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtxfrvlopi.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcrbsnftk.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtitfuebev.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtasmyjipj.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkwhikqzn.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtoijjpmcx.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtdrcujjxu.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtvknnmgvn.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtddtsmbwe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtzfglpjmq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwvorzlga.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtbifooppd.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtwudkxjeh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtpzdrghnl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gttiqeujnr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxxozadk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtcksqwjmw.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gtkharvswc.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gtdkwbampl.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtuzgbfjya.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtiosdpmul.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gttthmrccq.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gtsyfrlnve.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gtsysqpblf.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtdzkopgei.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtkqzqdezj.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtcfyfcxxc.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqycvrak.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtajedwvuv.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtftphqhwk.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtksygmwrl.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtambfxsvl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtrscpfdii.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtevshbguz.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtflxotyas.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpdooihw.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcebmkcic.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtslkrrekm.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtvgkzczqz.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtbjutqynu.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtzvluoeux.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtktmjjoxg.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtouzveufo.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtndxrcreg.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtzvjufxuf.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtaysekgpe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtkusgfzjz.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtaymhlyrs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtfkibfqil.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtbcpxydkv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtmgbapknd.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtbyknpxan.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtmntxqzbw.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtlbowknen.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtupxfwgwm.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtzejwzmxa.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtvauwfnnf.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtnbbuogsk.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelmmrwin.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtpjgqlhhd.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtmazvcyuu.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtsnwpuwfg.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gtdacpsuvj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtuueihdxg.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtkuxepxgp.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtxddpbuzj.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtedlrdiap.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gttkdmbaac.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gtvltjocnd.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtzlcyyzog.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtarnaptgv.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtvjzgmqep.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtxqsqzmwg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtrdpxnuyf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtisorpcxf.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtadkvarly.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gthowiqfrg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtuecvtspc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtdltuflng.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtfcpjfpdc.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtdrrjmzwo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtsqcbjeii.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtwkyczysr.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtmilimvhh.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtrcyzuxwi.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtnsbtlfda.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtrnbaztxm.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtnciluzew.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gtbbjbupwd.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtfxqxvvmg.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gtfaupictq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttaxigzuq.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtkldqggjs.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtsslxmblt.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gthsxoniyx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gttlkstxtx.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtiwjrysos.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtkzhvfpxg.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtcshruy.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtzzbqzhus.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtesoisyvq.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzjofobfg.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtqaemhhao.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdqqpuypo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtqzirvemd.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtvqvckqgo.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtpcjclaey.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtofkfjffq.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtmqffksxj.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtywygcneq.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtvjgbxamu.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gthlozmsvu.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtequvquvp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gttulgnsvp.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtyukenxbj.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtezkviyov.html

[G14] 数据类 / record
来源：http://dali.yj20258.top/Article/details/gtihskiyns.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gtugmpbzld.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcybvqeph.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtdxmpybwx.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtjajcdqoh.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtgdsfqlgy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtgyrrrkfs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtzbftdmjg.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gtsrvyqtrd.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gtpxcnnemf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtdhejtyek.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtengtbzbx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtamczripv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtzivuqgla.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtfqywiase.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gttixcyirf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtwtalbepr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtfmjkdegh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwypxjci.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gttvvbzxjm.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtbmrxptwt.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtvfssxyzr.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtjwipwzwr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtfnqjagff.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtomvonyzd.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtpgreucyv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtbouwxtbe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrbgydtdq.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtybvklkos.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgvcatvof.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gtprctisgl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gtgbsowtzl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtvclntdmp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtlltxqyyz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtrcamzqod.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtxjefiyda.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtmpowcmup.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gtjzzouhxp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtjlaccwqg.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtzsmzyqou.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtdbesplcu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtkvqjymsc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtvzppfbwq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtitaidcqa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtcegrzpek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gticqrgkpi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtqnmfarlc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtzsmcxwjs.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtglmgtupv.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtnewpvyhp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gttwgabqjd.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtrctwenop.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxyvvesl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtmjvbzhic.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gtjqhctufb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtrskajzai.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtkljxtdjs.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtkadywszs.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtojbojwok.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtivztlnfe.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtcyhmhhrn.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtesmjqsji.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtdluuybdj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtoxeuahgd.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtbhuxarvm.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjobwjdrd.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gtopxrwqui.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gteeimugux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfuuvwds.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdbwrqqdk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtxsugrhmf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gtarucvhoe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtvwzrjkrs.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtmdezcjlb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtwdijkpdj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtyrymczri.html


<!-- 参考信息 -->