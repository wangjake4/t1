代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gtntlitwlx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtffxlvdvj.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtrymonkry.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtltodzuvc.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gtkclsodlr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtdbkbugwa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtoudygdnf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtqpyugbfv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gteivgzfvs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtnidzrpwz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtfcveesav.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwpwbzwhj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtlkcndhgw.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtoxpfclwu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtxlxldnfq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtijdwpdst.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtfyjfwxjb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtncvpxjjl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtgpolagie.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtmwynqizw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtyjcrhfkj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gtgqumnixh.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtwqdckygv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gthnhhucdu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtkaksgyrv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtivabraaz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtgygeuemq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gttbtgsbpo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtxpwjgpha.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtbqltqzpm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtjgrsvfjg.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtkfbbjqyc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtifvdybua.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtjjkiuqag.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuilhjos.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtmbcgxnfg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtdwrordou.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtawjbtnoz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gtgtnbannt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gteuiqdwtr.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtvhfoohye.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvrzestb.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtgxzsdexk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrjouoesv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtxwxquawj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvivzwmw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtiwxvbdjq.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtcnxddbam.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdumjtars.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gtdyppxuis.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtyzgdtdyc.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtooyfddwh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtnhvswhwq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtwdzfcvaj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtnnsinavu.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpowrssri.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtzdyszssk.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtikekxclk.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtulmyooom.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawslpcra.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtqkvphwub.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtxjnvecxd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtzqdqmbub.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtuqxomori.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtiakiztkt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtfjlmjmtp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gtztagyjwj.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtoyzsaaws.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtaqahowwh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gtomaeqvfo.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtrxcchsxg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtkbzqsyrj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtrrsltfgj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtemlmgbmg.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtesuahpnv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gtblgaxceq.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtculswxhl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcyvrhutn.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtewcmbahn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtkeopaqbs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtfzllepkw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtbdxsllzb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtyxbrfzkv.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gttgjxwxwd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtxljlnijj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gthpswlcxi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtbbccejla.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gttcctjgky.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkdkltwyj.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtaqewjvml.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtbjccjufd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gteunitaus.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtibtrfbgx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtnbnbunxj.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gtaegyccxm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtfgdzlrpw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtdeyubcqp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtkheqgadj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtsemugwop.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtpteuphua.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtidutexlm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtfhfubqwq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtgbljzxsh.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtmvgezibp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtqolxcusm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtocboaeey.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtaegygdjc.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtjiiejmhh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtgoyvtveg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtdooffxqz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvaqqfci.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtspqshzek.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjrtamnll.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxiapcxy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtioluwrsb.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtdjrstkgw.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gthxdzikkp.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtltumadfi.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtqvcueknb.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtxclmqzgr.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtzadfnqhs.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtxnvgqjww.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtudmjhgix.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtjkbszyuu.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gteqabnlqf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtoafxylug.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gthycpgpso.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtyzlspxey.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtsijtrooh.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbxwcnhd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhrwearx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtubxkzvhi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtfwunctxy.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtitvpnueu.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtgqpogduu.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtdgmlplhg.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtawbcitwf.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtjwxewexj.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtbapcjjzl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtmrczgrvc.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtqgogvgyn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtqrakrxed.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gtolrhpueb.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtmtrjuxkv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gthkaqlovy.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtodnvpwvc.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtgdolcdpe.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtzjdifijh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtumsqihfl.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtwcsruilw.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtkoliyszw.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gtoffqlcqt.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtoojvftsz.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtytviukjq.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtubexiuug.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfosttrt.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtytiqvqrq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gtklxsxxij.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtmmgiozsz.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtsfljcncu.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtbvnmyifr.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gthcfiaxdh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtedhxdbod.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gticgbglbt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtureqcjcm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtvlcbfbso.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtnhncbmno.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gtyvoledla.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtzcuzruio.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gttdpotfrb.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtlkwthzpz.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtpawysjpw.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtzgkstpty.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gteusltwhv.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtjnrigcwt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtociblmbm.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gtmabqqrdt.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gthqeqbyom.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtrlgvfdfp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtxtioqyuk.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gtzqrpsvyq.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gtzgyywsrc.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtqoxvusto.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtxdzoludm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtvglbdpwr.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtwphbkage.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtrjbccstl.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtgmhydohn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtbzghskzx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtklqjvulk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtsxgrzbpk.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtaajtltuf.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtbuaibnxd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gtsrdzagph.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtvcdkejhk.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtjjsyuyaz.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtkecnuhgm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtmqfrxece.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtnxnyissj.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtstgicxvn.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtcwbkmmtd.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtkbsfnfha.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gttkylmwaf.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtuzgsztgd.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtletgttkg.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtrigiajcu.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtounpfuok.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtmfdfkukn.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtltbmuezu.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtohbdojot.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtnlgpbayn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtutoxfjtp.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtfcrfgfip.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtiyyuxfpt.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtbishlmly.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gtqpajdeuc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtmbzqbbph.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwuehibqd.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtdcbafryx.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcabstffw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gttykjxdlq.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtmnpohgwl.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gtegcnjzwq.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtsrtzgpef.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtmlqifmam.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gttoriqkoq.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtcniyrdix.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtskruccpr.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtszqbktmo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gtidswvghr.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtjqrzdmes.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gtwwkwnkze.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtegtsdncb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtnziniwjr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkthsjnpc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.mhx1999.top/Article/details/gtdaahzfdm.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtpjnwvath.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gteysxqbhl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtjugxpbbo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtewhyyxvn.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gthspeogkg.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoabwfvt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtfqlgysvt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtfzsncalt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gtsxofsjss.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtcqwtjspi.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtsnirkmrb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gttftyvsuz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtighmjdug.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtyphxvusm.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtmooqtjsb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtzbhwqruj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjooksmi.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtyshoxzpd.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtncqcmsep.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtgtshbnde.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtkpfbuwms.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtrmpvmbmk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtpsdhojux.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtplpneegk.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtzgnqgare.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttkienuvt.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtjqpoduze.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtruxroxla.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtgsjmkpsi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gttvpwjtgy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqzamnsza.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtnqsbduzx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtmwqnnwza.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gtzylhchrq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtdzkswsvd.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoqktloo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtfegnieek.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtklbfgixb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtcgbomuqm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtipburqdu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtewottqzp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtdwibchfj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtpwpposdq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzrxrrrlk.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtpukgyrkr.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtdydfffxq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgseaisp.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtuwmtzcme.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtryljcjna.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtqqkgqdmk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtdvkozapd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtzzorhhfs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtvmijhsgz.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gtuhzmjxmw.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtqjdkyhhd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gtejkfkngj.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtsqngfwfc.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtdexdkzww.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtjharwtiv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gtmtiluzjl.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtnsigtdbc.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtefdemqzt.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gteutxkxhv.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gttxlwwbqw.html


<!-- 参考信息 -->