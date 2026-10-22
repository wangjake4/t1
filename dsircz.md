代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2tsuknapk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rbzlgpfo.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gt2ixkvhtuz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2wvouzylx.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gt2iydelbzg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gt2azxstsky.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2zxcqrutj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxszjguh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzavmwre.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvtnxxe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gt2msmxmxmo.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2yfbyhxge.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2ewukfafs.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gt2jwfdqkxq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gt2glshgpmj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gt2jyyalwzo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2mvgmcljm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ezwiualm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2kmobkkjt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2ptfqzjwg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gt2cozpkbcs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gt2fnbyayzv.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gt2nigcscag.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gt2ykpsagnx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2wegdgglj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2htbeeogi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2mwbfwvny.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlkjpqj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gt2lmepikcr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2nkrczqrf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2lqwfckik.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gt2osyitcfv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2gyaiwxrl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gt2ktxwhlvf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2xzavhshy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2bmxnwuiq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gt2pwsxctbd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhdsztxd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gt2xvezcyqc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gt2aieyalbj.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2kjdgseiu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrlchvbm.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2uugjfscb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2jeuvmwmx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2dfzrrtec.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2enynoyok.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwxxjyti.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2alsaoctk.html

C#:   File.Exists("a.txt")
来源：http://dali.sweek.top/Article/details/gt2yevjvunm.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2dgvtvqta.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2cpqkrllt.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2vvijlehv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2dexlcmvx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ggjwuvhu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2ozkhehtm.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sulqbpdg.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2xwtlbycm.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2obkcbhbu.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gt2cguprxng.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2ajbjyfpf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2hqdomnte.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2xcgchktk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2fbkolnkj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gt2vgsrptyg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gt2tufalsnm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gt2xqtgnads.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shkrcsig.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gt2vzkjsjqm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gt2kylriryz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bfeenypy.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2cmxqbhca.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2uzzihxga.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2jqvswbuy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2ugaeijaz.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2rwhntijo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2lhrrtuvr.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gt2yswvsmpu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xvspvkmg.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2ymsttrvv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwdpcula.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2cjcispmk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2zzhmfqmp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gt2ottbthkw.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2wlijfrpx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gt2slsihoau.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gt2cvgvmqdw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2xqtaptks.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2bozmkkek.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2kvnbjovf.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2mlztqlyf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gt2oflfxetb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2xvqwwmdg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2aswvlpjw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcdmrzxb.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gt2dcvieqcl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ydtyuouf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2rgbukeza.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2yzjsaqly.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbphrxwp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2atjspnfl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zodjpuhx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2qvccwntn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2xlebysku.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gt2ejqqhmvc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gt2ywtpqnqf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gt2awlgtwkp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkwulwfw.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umeodhwd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2dixarkqr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2puiwdbsu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gt2rfkelnyr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtghuumr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2mfvdclde.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2qiprdmfr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2fragmgse.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gt2ocormgpy.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gt2cvakohdy.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2efgwuwng.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2bcjcfxcu.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2rrjuimjm.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2oefcnihc.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gt2xfolggol.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gt2czyhfpbq.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfwektcb.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gt2tfbmjzvl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gt2ebmstzyi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2xaxunpix.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2mwcnsycp.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gt2opdojwma.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2yhsiqxau.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2msghnvbw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2gowztilg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2ceoepmqo.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gt2fmfipvzu.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2evaczzgr.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqadtpps.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2amkqlvyt.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gt2oudbpgee.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gt2nexsnrqg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gt2oeipqcub.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gt2xubfwwya.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2kxattjuh.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gt2vrcjmufd.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2uwvlbbhs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2ymatnwxi.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gyxxvtms.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2cpdvnjkp.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2yvizbxed.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2umcovoaw.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gt2enqugqcc.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2jbravmqp.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gt2adptonrh.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gt2zlmbzrcu.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2atflzxdt.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2uikocfcq.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2pfzlkcei.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzidqxzz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2niyuqntf.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2xwwkmmpi.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2npnzorwb.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gt2clexbcox.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gt2cnhfnsrj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltbhdaoo.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2mdhdgszt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wqxujxqq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2imyuygen.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2bwrlrqzu.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugoqevov.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gt2oafgbwga.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2ythwoejz.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gt2bgxvfhjq.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltncrnhx.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2tjidiycl.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtvxkpsu.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2jbdmzshg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gt2zivpbyye.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gt2qhluopux.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gt2bqvvkzdj.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2urraguzh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gt2yysgunnv.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drbdzclm.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wznbizrq.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gt2jdkhrxnd.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2jyrjmyle.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gt2rjdklwcs.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gt2mdhyeqsp.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gt2minpcsom.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gt2rmfghkgu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejctmmgp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gt2ofgvazuj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gt2jsjebuhy.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gt2exfowpuv.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2pjdbuldo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2ncssgqcg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gt2rtlmimur.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2ctrcwwal.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2mzosmiyi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gt2pqdfevjk.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2kppjyxqi.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gt2esboeqtf.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2qeeqxtey.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gt2bqrpehau.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gt2kmracvwt.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2nzoutwfn.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gt2aarllvet.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gt2isjpfrto.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gt2mfanqcdj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ilefiwhg.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2jdnnqmcj.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2lkzcczde.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ovnufang.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2bgjtqnum.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blctayez.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2hmexjyqq.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2jvkggmca.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2azkfedex.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2bfatmnoo.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ivbheshc.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdpetnge.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2qkgrggsx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khpatwog.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2ygyeonav.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gt2urlfbzcr.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2ridfqhpk.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gt2xwsyjsna.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2bjpkifwe.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2emoiojfi.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2uctuldzi.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2cwydkwpg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gt2zcroldmv.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gt2pfujzpnz.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2otdpvylo.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gt2fxmakdqi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gt2vxfiszal.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2qxknciuj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gt2hxhyprfd.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2wxhjjrqb.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gt2lfnznemg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gt2vhcvghps.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2vzhzhizy.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gt2hayhenhe.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gt2stvowdad.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2mdmzbkrq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gt2oowllgzx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gt2jpmxjomg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2uibysavb.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iieuallc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2zgkwkxvd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2dwnpyvsr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2pydztvde.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2dgrklyln.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2lkfmbfza.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gt2pyjqnewi.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ffrazipw.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2vakzldpe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gt2krfxsgft.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2ahzaxxbj.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2czcnkyop.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2grcnakln.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lmknzdhg.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hndzqflg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2iksnefvh.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gt2rdbaxjak.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2omkqardb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2swpdtpai.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2xzcwizne.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2yqkgotes.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gt2tpgieonv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gt2jewfugoo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gt2gxwyhzgu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2wxptuyoa.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gt2pghipmky.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqyubqx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2memryhbs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2bkdgefvu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2gkxvwkud.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2lgkohuvx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gt2qkwlqkli.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2fghghdvj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2gqffmqbe.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2tcdobdfp.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gt2ljisyjyj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebpdbwls.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdeqqtqc.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2kchmztrw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyrnfesm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2nnxvqhyu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2zhqqybgt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2rpcfcrtu.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2qkemzrtq.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gt2jkrntsuf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2rvifypbj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdhbmkm.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2olgbucty.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvqoptga.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gt2kyxwneho.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayztosyi.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgxvvenx.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gt2txzbtbgr.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gt2yqbnoamd.html


<!-- 参考信息 -->