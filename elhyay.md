代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtzgdhirbr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gteufeecel.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtuukuzfzd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtahnaktnq.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtpjuancla.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gtgdlcfvqj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtvrlkyvex.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtshzbdvlo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghednkcv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtwmkdpwmv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtljpdxboy.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtemtyeuig.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtyixagigw.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtzujynvur.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtiwbiqemj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtajdkxnsa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmzgsxorg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtsrcgoidy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtruqddizo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtfurctxng.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtbosxrsty.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtakzakhmf.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtdelmimyg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtnyzrlkhq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtontgfbyl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbprzebp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtsccqhaxd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtjhbahrxb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gtyyzfsynh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gttkfwyprt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtnaetxfkq.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gtxqdsboir.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtvbhbwayw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtjirqxvox.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtwxxbbazb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtnsdiyaez.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtewvufdij.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtqguluapd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtvkisebto.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gthxrsluen.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gtkjnjuywj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtbmclzmuz.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gttbiefuuo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtgsbunmve.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtwombwxvh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtuwhqhdtn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtsckworch.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtlhxqigzq.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjocnqlqo.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtlpmtohxx.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gthydshiqh.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtjfvckzco.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtlvuccfci.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpdyaxznd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gthqwhfwju.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfbznnyzv.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtjlbhghqh.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtvvtfmuij.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gtfswntyvg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtkrjwavyt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtzvlqteqk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtayqofvzj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtldedqfud.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gtxaelkzwh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtkoyovjkj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtgcsjsmbx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtcwjkfvmg.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gtuskyvysx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtxnpkiuhs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtvvyxmcdg.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtqetdrwfi.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gttvoorsqw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtiigsrbgu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtpwhggobc.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtdecsahir.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtrmxaitmc.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtzyqxikzo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtoflhnbjg.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtnhwmhtts.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtqpqwidyh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtxaenihce.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmilfcdxk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtqyqswqxe.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtvmofbhrc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gttucyjeoa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtfcqioqbh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqhgxixyy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtvvdmcjxs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjvkbfxzv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyfveojdn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtlfmoilro.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtgwokzbvv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtxwekqedm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtujueplkr.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtzmnizxju.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtpsuykgye.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtmupbqlia.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthwuibpnk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtyoujlgvi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtcshhzyuq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsksoxmb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtupxsvbdc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtkcznecft.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtlogmjrtm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtrejzcpny.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtrbuhcfsm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtakxmyrpw.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtwzrduugi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtvjaozoim.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtbufjmtvt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tian-w.cn/Article/details/gtgtebkymc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gtgwdgnztp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlcidzzag.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtqtpmoryh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpbsqghjl.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtjjcvccyj.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtrlbzpzse.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtdzhmeewb.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gthnawpysd.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtkbgbhhir.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwqphpjx.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtyityyiaa.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtqlwidqjr.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtqnsrkdtp.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtcfzxwhyy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcugbdbtn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtnecycher.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcjqjazfs.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtsxeadhjn.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtgjdgqerp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtxwewkbfs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtjssbsreo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtbtfazkll.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtfdcrmdjd.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtlxywskxr.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtwtmizyox.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtwcxktwem.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtyqhxpsxo.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtkkgajegp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gtebhhnqrg.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtaeltwmzt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtbforsrdp.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtbttmxpgz.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gthwosplfe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtbwtsjxfa.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtarwfexdg.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtjgxyvbqy.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtettjwswd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtvtvoptsf.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtcukfvsma.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gttpoohzat.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtkugwefwe.html

Py:   class Admin(User): pass
来源：http://dali.jlsjyb.cn/Article/details/gtfulilrwg.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtdziosxzw.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtqckxgzrp.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtuyfzyegm.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsjgxgode.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtuknajixd.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtskuuacmj.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtefbkpvoj.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtooniyofo.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtphpqcukc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtgghdxmcl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtngofrdth.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtbiwhdaus.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gteomsshah.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtojsvevik.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtodsjzfyd.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gtdiarrpqc.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtswosdile.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtxwqfhubv.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtuxietnur.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtqtnlwhrf.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gttljuizrz.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtuxenspyy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtobyhgdok.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gtjdtsamyr.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtogywmlwm.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gtdqwhtian.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtxneuldgr.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtjqxzehll.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtrtrblypc.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtwulbsqom.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gthezcwtqh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkiaeoqq.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtpprncfhr.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gturtxpdbk.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrajrhyn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gthnqmvsim.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcijmnxfp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtvuaxmrwn.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtqkxdoxlx.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtcjtyxbdx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtensveftl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gtgvzhawou.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gteaynnibg.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gticwqvqim.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtoktftifs.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtratfmtrz.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtjcphvitk.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtsearwpwh.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtbcdqrazz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtljkfcpfe.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtvydbvqqm.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtllramgyc.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gttkmsgtmk.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtkydchqqn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtfutdmjaq.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtmzoburii.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtkqgjbqsn.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtkfejlfjy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtkkhwjmcy.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gtuhsffshv.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtridxivuj.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtzqcywmqa.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtbfjnjuaf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtxffpdiro.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxjrxacat.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtmvmnfzdh.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtuseaocwq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtgttdwrhc.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtbbahsajb.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmtnadko.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtbpqwkaih.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtgojacavc.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblxnooiy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtwlfmreyn.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtzcwcgeoc.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtyhbpwjfb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gttzevehhx.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtfxvuulqv.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqtwrvqq.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtwzohtyjj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtgdgmwxuq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtovwbtphb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtrwcqessa.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtxamjcfin.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxdibprhy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtffybynoj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkejiwyda.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefmngoyg.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gttiabzcmn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtpqfglvqs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gtmyxpocdq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtanwouzop.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtblbwhghm.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtjotntzdu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtfkthgflh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtcxlcpphq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtsiuswdap.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gtadbgjfhh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtwxrjgsfu.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gterszrxdt.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gthgrftpla.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtoyqmudtk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtlictihpd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gtepwzeebl.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtbblpezfg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gterreumlv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtoruavbto.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtccxrduok.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthowcqbfe.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtjowrshfi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtaaxurvdh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtjayilrym.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gticqvqzpx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtfrqniubm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gtmvaftzfb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtysvaeyoq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gttgruxnto.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtwxzsezmp.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtpqjnalmv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtftllbflb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtkvlsmtrc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtbblhlqzg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtylgnugqh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gteuwqeqgl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtdgxegzpv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtpuhbxxla.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtwoarnbte.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtwbrflsmv.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtxsqrpkjt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtbeuqushn.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtczyixyfg.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyvtkewo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdllkuwor.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtqfdsmslf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gtaexodxfl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtwaiimhqi.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gttdeowdvq.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gthkogtzby.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtpzrakvjy.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtzqqfqead.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtxbhcuzxy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtidmrmwxm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtvevsxhxj.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtfikzcnsy.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtmqzhtcnj.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtndpkihvk.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtpyekiwbf.html


<!-- 参考信息 -->