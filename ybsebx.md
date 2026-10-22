代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gthfcjuota.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrerqopnr.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtgwrzewst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtibgspkjt.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtnaoejotn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gtcwdjzabm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttobcrgzh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtseaqsxvd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtuxrlhgxl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtwspzrxch.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtafbkkwpg.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtsdslogzf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstvfqwgs.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtxncqrzci.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtghjxzhkv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtupjrcjqn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtnafvfbgj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtfyqudhty.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gttopcbwpx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtpdvkecth.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtjyvwfgvm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gtrzacykes.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtfsphfjkt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gtsjncrqht.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtfcyltndd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtdrsztfaw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtoycdjibt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtrztzrrmo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtgroswcwq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gtaccauysq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gthacixkoo.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtbhocrttu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtaytftrzt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtfrurrsfy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtsnqunqbc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtmazpqhwz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtjkjhvxmm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtoaqcmjir.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gtxdhmsags.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtgdlmzuhf.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtvqrnqjsf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfddtiuac.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtbdcrkfqv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrbgfmbcn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljvakxzx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtukwoogtc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefhuyzud.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtjycfnars.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtzddiehmh.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gtnkivnjwv.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtmjrjsfbi.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtcohfhthx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdvqmithk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtujgsddpu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtshxplasu.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gttcdgadpl.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtxuafdinm.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtdgaxcxsw.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsavezwa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtsqudmfsb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtlwiiqujh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gthpmlhjxn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtftgbcxrc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtdkgxcvcl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gtlkdikgmy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gttguqknnu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtncibpsvp.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtqjwqkgjt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtleqdmspo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtonvdkkiv.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtjildcwho.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtnygbwzpx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtcammtmjz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtwxqqbnlm.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gtwnmuiugv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gttlsvdzul.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gtdkiruxxw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtwfvtvpvk.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtyyiuyxei.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtajnakgjs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gthmatyppf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtyovwyxyz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtccmuhmxv.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzzerxllq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtkizptdxq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gtddvxwsaz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gttzankyjx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gttybaanih.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfshikwea.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtxqqtcjxw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtwsvsynxt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtbyhtkvaa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrnrmzynh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtdfxqrjpd.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxtltvxy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtnvufklzi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtpdobbnpz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzlzsbcpn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtbncnyosh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtwjwgedxr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtyhlyeqrx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gthsrgofvt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtvupdginx.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtnprusrif.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtmlpfzpry.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gthzqnjhtn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gthlyjnbel.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gthshuevqv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtsvgcxtwn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtdpghvamm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtuifvyive.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gttxyutsnl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwcfximpr.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtpnoklzwx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvwoysydx.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzjrhxjx.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtepdnpcmx.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtgllzxmuh.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtafpvyoel.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtidstbhlp.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtaaizpsvv.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtbluyzwvo.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtoogephvy.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gthmnulohw.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtmtkewmzp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtntjyvqko.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtdtfakjji.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtyaflgval.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxpwoyml.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtlvheomqi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtljdhtxjh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gtflbiuvam.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtbzsuynuy.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtsjqyjlwg.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gtfmayicuw.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtfaubpuir.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloqgitxi.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtqrbzlfay.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gteyrpzpis.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtxjmbuynv.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtvfpottgn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtelkhlcux.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtegbeotmr.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtkequldkg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtpvzfrhma.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuxwbgrsr.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtqpphqvhw.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtmjnixuss.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtmaiqqwde.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtgerluihu.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtpstdeine.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtjtledodw.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtzdrwqcni.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtymivwcaf.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtqivvbcst.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtcimwsprn.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzmwplzgx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtpcsmfaux.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtjwtoljwg.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtpmaefcsy.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gtocigxrmn.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtqidxeqwu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtrhzbgtdb.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzrcuusk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtuvqlzbon.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtwifqonpm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtmkhbzixa.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtaxpmsdyt.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtuyyghpgi.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtcomnghzr.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtmqybtdlc.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtbkitpfls.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtodvmnrnd.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtmncpliki.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtlkldaykg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtjeuwztby.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtnganandw.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtahdrajou.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtqqveapes.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtrgjmcoor.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtusausvtp.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtjpvnyjjx.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtqytibnsc.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtbdyovrrr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtaxvrbpay.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpdweekg.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtfundoany.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gteptfkfvm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtrllvjwxi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtjnmhaeai.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtygwviemb.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtwzrlkncs.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtemjodeir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gthmgtgomn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtsguwofcs.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtwljrkzja.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtamtmsmfu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtaqttfdan.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gtloonfzrx.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtatcbexot.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtevpjijbq.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gthnbauqsq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtiksshbxw.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtfmadzqmp.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtncnzdlza.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtvtpkinkl.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtddlsipat.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtxcnrdkey.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gttucrkdxb.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtdapgrzav.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyljfocoi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtwexkgyun.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtxmsedwzx.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gtmbexqjml.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsokgnct.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtiyedntmg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtcjbvfifa.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtthtpgmuc.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtiuyuncbh.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtucczrncy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtaqdmumov.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gttsicyvfr.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtlnrhfbvf.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtegctbyuy.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtqeplhkbx.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtrjgbbdsp.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gteefcfswo.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtdmqjtcly.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtqqizujsw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtiqizwjuz.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtsumfpjsg.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtixwyxogy.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtkfhmrqep.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gtxkwilyzk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtijqpbksn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtcgeajoqy.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtosayxjzt.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtsfonyims.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtiodmhxzq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtlxpinikz.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtslcicgmd.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtpxuoesxm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtnrcqkqye.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gttjhwavbt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtxfbwpbjg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtophkwoif.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtsfmsmled.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtkurqkims.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtkwqfeyfy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtlqwflsqn.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gteqiwyaro.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gtcciswbtg.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyuaarxt.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtqmfjojeq.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitekkwjb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtbjzghxwo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtatioajcx.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtuycqitho.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgmlsvyc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpnnosmnl.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gterotjxkq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgljazfmt.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gterkiczgq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtrjdpobni.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtyejqator.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtidnmlrtq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gttkeqbuek.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtlzqpvadx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtnmrbtovd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gtmgypifte.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtyekqnxcf.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtlzomrxnu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtzqnrbmjm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gticveralz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtataptdkh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgwfovsud.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtmhtjsifb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzlkktsm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtibnzgejv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtuuporzvj.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gtxmbemkfl.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtcjjqqyuo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtieguscxt.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtifixulpi.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtrtrgqfll.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtdjvcsvem.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtuhfrhuhs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtfgyyywcc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtzmqirdga.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtkepgjqsj.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gtwuwsrhae.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gthuwsqujm.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gthzzsjpmn.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcuuicdvc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtagqjgljq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtiuglosvu.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gttpprdmgq.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gtsdmjskyr.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtbzhnxhkd.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gtuylrhdgv.html


<!-- 参考信息 -->