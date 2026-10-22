代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2tlnpiqxk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2tglyebcz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gt2irvmbuyn.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2fkbanouh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2lbdeyyjb.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gt2vluiqwpf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gt2pwodjfpf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gt2iwmsvipg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2boeogbhs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2aqlfpwkk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2vluwehoq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gt2eqlkertx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gt2rfelofga.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gt2juwnjkrv.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gt2mtmsuzfa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqminljp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2anvclbat.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2ykckcsng.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2iekvojlo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2ugugfouj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gt2ajyqjvyx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysfctgtz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2amjnchke.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gt2brcfqknb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2uztnubyy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukutjzss.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2eqcjkxnj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2mpruyuxc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gt2zykvwdyy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2vchmkyyk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gt2fjcprcyb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gt2kelcprca.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gt2vokigqpt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gt2tsqonwon.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2xngcrlqc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qwpssblc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ynjznxzh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2zznudqvb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gt2asdrsdcw.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2wywifxfp.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ailajyvs.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gt2dwdsotcv.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2rjnxgrbd.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2nthclwkg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2dannlbzv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2mkomevic.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2fkfgtfsj.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ljyaphqk.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iovipdvp.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2fofmnqco.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2gppndgcp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sawbllfm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gt2rtgepalp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gt2lyhbjuyc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2iaaaioft.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gt2bksmrqco.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2xnkbmfjy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gt2nzqlahjp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gt2rmwiehej.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2tusroiit.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ueqnafnw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gt2cmdbawkw.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2orqstnwi.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2rbelckmg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2edfugprv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2ikymfckf.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bikkbcac.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2sqsghxza.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2vsthqifs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2zgsopwgv.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2xbhherov.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzhqwnkk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2vdxpuhcz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2rvhxlqjq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gt2smsayoyh.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2rfovklog.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gt2ltbvaonu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gt2guhyvusi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2daswgpid.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcsduyeq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2behtvcmm.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2nhogijbk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gt2vybbughy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dbcxjdjn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2qafjjmxh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2yyerwjny.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gt2cwtcbqyu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2cmrxophe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2yggjkwgi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2cgwvyefu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2vkhpdhbk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gt2tnnennhx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gt2urpbnmok.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2svpemoua.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2bjlwlwxw.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gt2mvpevgyq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gt2xmwowicu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gt2qnxyepqf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gt2lbavddky.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2mymsjaqr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gt2pnfocusn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gt2dbngczbg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2ptbqhzbv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gt2pmwvwpaj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hiovdpzm.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gt2fhxugocm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2qjjfttki.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gt2fzthvyan.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2hvkwcmrt.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mknjyqgt.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gt2wzxrflvk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2bdfytjgy.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2tnsfjteb.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqxpiwyi.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gt2ajthtgmo.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2ecqfafwd.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pavuowpa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2wzvanrgm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gt2iyjpekwy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2gxgjuudr.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2viigrpwg.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2vhovuumf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gt2kponmlol.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2nlrdgvxy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gt2waiwtcvo.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2ombterca.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gt2hhqaqmmv.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gt2sxujkysr.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2rkyabyvi.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywdbetcx.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gt2fcnaidor.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2qmjyiecn.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gt2zjolkwia.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2mxthkzop.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2wpwvmciz.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2tsklphtb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2izpkuwfs.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2kxaorjvn.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2xkcyjyvo.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ducooigt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2molhlfzk.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2vyhjicut.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2lnbwfsbn.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2typvhwpa.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gt2dgnvauhv.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2yydgcucb.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2uqxskbue.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2dwwdukmn.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2tcfeymyo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buyxrklf.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gt2fpqqvwov.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2paqraukb.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gt2ssacbilv.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gt2dywvlgwn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ysvxlmav.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2saconsug.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvctiavb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2ybkewtmu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gt2hdjxhpjq.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2qvwymaul.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2ilabqitm.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gt2onmytimt.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gt2qlvysfsr.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2oepdtnrt.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2fyznubkz.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2udjjftds.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2frldaqxq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gt2usqayxha.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gt2zvursbtg.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2cskgupee.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gt2trbxefia.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gt2maaywghh.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gt2kwhnllbx.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocqrihdh.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gt2dosuwkzk.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2docuznqm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gt2qwdqmfts.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvsiyyiz.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gt2bcadipid.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gt2spxhkdbg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2dxrofzqi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqrotstd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2cqwhdrwl.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gt2mfydfujj.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gt2vqvfvorl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2jaqrrklf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzxnacez.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2hipkapqw.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gt2guczngzu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gt2dshtolhz.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2qxnyjsag.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2apvluuzt.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2mrqzpdje.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gt2yuixtbik.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2oeduumeo.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2xvaryuyo.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gt2ucvwevzt.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2dnozfylp.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gt2kjpakcwt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2kljbklbp.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2shqlnwuh.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2cvlaqxae.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2gsrpzveu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2rgwwxswg.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmahyvdl.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gt2piptvrnh.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2fkxbtmjc.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gt2jpziytyo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2jkdwepyo.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2kbdnnaln.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2kfuqhliv.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2frtisfwj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2howazmdl.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcczdsyv.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gt2sxuawkhq.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2ugnrtdpb.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gt2lvtivpnl.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2zdgbatsg.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2qrffzchx.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2dxocddok.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2hxbtplhd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gt2pkoqvqux.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dulwjuxy.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2mkztrbin.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2finnmfiu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gt2zejvvlcu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyrjzxae.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gt2qttsazsa.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gt2trecrecl.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2vezxopmp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gt2socwdrba.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqrbzkxp.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsumkscc.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gt2zmukpocg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2htxpdiwc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2rqwzbieo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gt2cfdkrqqm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2ispkckiq.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2jjkqwxog.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gt2aqjeoffp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zehlhjkx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2zxksohrl.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gt2egtezimk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gt2kvpnilfa.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gt2hvlbgpei.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2zbkostsy.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2iohimafj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gt2sxcjhdqm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gt2cuzeajet.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2ptelmbxt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2jwtcrbkn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2idvsfcnr.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gt2lgtndely.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yekgspow.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gt2bdhfjqqr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gt2lnfekotb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gt2etipriwp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2odzwlwts.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2mzpmqsjm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gt2nqrmakas.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zecqfifv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqstimry.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gt2udwmzfyq.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewulvusu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gt2hrwbduoj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2cwnojrwn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpnlfoet.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2lheozcmy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2tegrchjv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gt2pvgqgyuh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gt2phhcaukn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2tgjlnqqs.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2zmfhzsqk.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgctgafd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2yvyotdrw.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2hvpdhlfd.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2tfhmpbye.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2aigbikdi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gt2jjicxgzx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2qgwyijow.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2pevbpppf.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gt2aqefvrxm.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gt2ctrixopc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2tqhrwtll.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2dcgggcou.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2ukgopmom.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2hquaszvi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gt2clzhzemw.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2xaprdhfd.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gt2optomvla.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsdfvwgy.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gt2lkmdlkhl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gt2kyhmmsyr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2eovcyjap.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2sdfmbpyw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gt2gduiijxx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2xngxthhr.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gt2baaczyif.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2olechagt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhvhflx.html


<!-- 参考信息 -->