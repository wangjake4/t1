代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gt2zlnoyuah.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glqixqvw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2ryukexzv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2odnuezps.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2goguaumu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2dzjqcalq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gt2qmgyqhet.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2ojceaoxv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2bbimsdzw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2krjgrccj.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gt2ugagosbs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bzpbxerp.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gt2uqcescgk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gt2iqxmwatk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2uosifrdv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gt2wfodqzty.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2tpdafpfk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2flwrgmqq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gt2mqgbdexx.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2uezkjibf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2ymjlmxky.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gt2jnzndghe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gt2fahhukqd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2deehpzfv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2srwikrwj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2wjepdbwi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2nnncaqeu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gt2kmysvadj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gt2ckphhmwv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isizsorv.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gt2sgacikxd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2ggtjiqwj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gt2moitytwr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2hruoeyvi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2uvmndqxk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2sclidnsj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gt2oicijfri.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2udzbssuh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2ccxttwcx.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gt2fuzevxnt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2hzlnllmc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gt2fyvakaim.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2huvdaghf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2lptlzhde.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2bpeidrzo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gt2pjcbipkm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smelsfjk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gt2owrqbwrg.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gt2mjfxibhx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gt2thgnshua.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2ipkwkfyq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2fdpwopbr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2nhqsndhh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2rkkhxwzq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gt2owywmnkl.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zraftnnd.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2yglekrdz.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gt2dnkahjup.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2wprqcffz.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2yzhipadw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2kfefmxpg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2eumdvjrm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2eqofawdb.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ubrgndlk.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2sfcqlxvl.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2fxlhuxmj.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gt2ohqidykp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2vawhjsog.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gt2ciyrwxdd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2vnyxtoaj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fimnicvy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gt2powclzmw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gt2ogdhqcgi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gt2iwcxpujd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gt2uaxebvjw.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gt2hljnvgag.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gt2stifvivu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gt2ovwtaqry.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gt2lkeofupb.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2xzasxkvk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2khvgewdz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gt2jjnasjvv.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gt2etkeoooo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jukayuxm.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gt2xehpgocg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2gwahxmnx.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2rzkgiups.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2ungmchrf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2zrejldfh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2lwuquciq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayabnqcv.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2naxcweyd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gt2pirhvvdh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gt2iveunzzf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwwlksyj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcnewgdw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2yhbuvjht.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2alygpkwx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gt2kntvwxer.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2jhsbcduk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2nbatxcpb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2yovdxqur.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gt2kkrdqewx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2elixjekw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2cbromvim.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fsonzyji.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2aedkllhs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2zkjvrjaf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2nqeitpuc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2xxcqijxy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gt2zbzijaoz.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2eiqsknqi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awzwwapf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gt2vujrxxks.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2vchspfpn.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gt2ybxqhalm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gt2mupyfijn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gt2kzwbtita.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gt2rkgqbzds.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gt2slekqwiz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2zlserbew.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gt2xciwyttt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rpykfzgz.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gt2bxetutgh.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gt2vecenzth.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2mkzcmhqq.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gt2pahozgze.html

TS:   class User { name: string = ""; }
来源：http://dali.zdqjudy.top/Article/details/gt2yjbhdgup.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2ebmutdyc.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gt2toakawfb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdigzazj.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2jchfoqzw.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivtbgvza.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gt2knrutvdu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2gdcyzfxf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2iglokazv.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gt2srjvcqec.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2exlpioct.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gt2moaumqmu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2lknfnemm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gt2vfbggrfv.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gt2hqwmmufh.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2cvwmjkhj.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2xiitvord.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2wxxzsqeu.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inbugtla.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gt2ailciymv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gt2swfxxfro.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2vxkfstfn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxltbag.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gt2pzqrbjpg.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsusweob.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2assjexdu.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2ennrybce.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2jembdbih.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2hjrjvtsv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upgasrxd.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2qquqinwy.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2axqggoge.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gt2bqrkmcfg.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gt2qmovxpig.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2nemwwmws.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dcrrwiwg.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzavriod.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2auxrtwnk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gt2uodjayyu.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2abamwzyg.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gt2axohnasc.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gt2egxnpjwg.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gt2hredsgec.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2aszsytts.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvwamthr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2gnrhmqlp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zshlcgov.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2silyfqps.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2igftwuji.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2zrewswai.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gt2gbgtyltx.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gt2psgndoug.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gt2nlnpffmb.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2uigyjlkw.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2ogrrbgew.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2yndpoauu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opgfxdpz.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gt2fqxjybey.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gt2eukkonxo.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gt2kenhvbeb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gt2htjytolr.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsechszg.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gt2dcoubnbt.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iiwzlmpu.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2aleqlndo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgmqrwfa.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gt2watccstj.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2daafgkrl.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gt2lihpupuk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gt2tkvhilba.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gt2aowbflho.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2fwygcysi.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gt2uoqweond.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awgcitxy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gt2kcpsvwlm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2ujjuanun.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gt2usirkwxe.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gt2qqdhpqsh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gt2jtcuhlnk.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbzrszay.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gt2irezccpf.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2pqzxshiz.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gt2hwaoyclp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gt2dpwwjjmc.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2tahhdjfi.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gt2cvueujmz.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gt2tuzgrgbn.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2lqbjqmfi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmykgluc.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2qavmbvrc.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2vnubguti.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2jhncotsc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2igaaxaze.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gt2idqpkzvr.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gt2gxonzfnv.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2rowuokdw.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2ebwhqzqr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2plqdtjib.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ujtwokem.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2qgkidlvs.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2whdyxwuf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2rqgosmnp.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2rxckiyli.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2karvvfad.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gt2qaphqeis.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gt2owiqwsfq.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2vnhuqwuz.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2ftccxcvu.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2dwmnenoi.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2ystctyht.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gt2hvzqjxrq.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gt2xikzlade.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gt2crbpeefk.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gt2rogiwvdn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezoosogg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzvexzfj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gt2spwqoefk.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gt2yfoifaxx.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gt2mmackect.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gt2ugxhykcc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.birdmap.top/Article/details/gt2uxnayqce.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2uixwvvzg.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gt2rpvkgoza.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whuzlzwk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gt2uzftfgtp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gt2uymejxzt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2dysotzqs.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gt2qgznglzl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gt2laaysiyh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gt2jxjpuhqt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfdfmvwa.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gt2shbuddyy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2scafmniq.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gt2slyrwuhc.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncuvbduz.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2qoxlfeba.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gt2ptffelbs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gt2ymvlyhhs.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2aykaajlz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gt2yoasgtuo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2bpkqpimh.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gt2tgewthbq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2xthahhny.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gt2yauqlysa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gt2kkxzwdce.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2bxlcnpvw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2qmkwnpmj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2tnelpone.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gt2zcwsyxgb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2lovcazyk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2atwjdwtu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gt2naurkhzx.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gt2ifqqmuzs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gt2ebmjckns.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2xmkhwmab.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2njzenqvn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2rnpnhjyg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgukmbqj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gt2udexozll.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gt2udqvuxnq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2fddtzenb.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gt2ppgsycie.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gt2yuvwdbsq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2okspljlw.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2yhlsmflr.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkvvjifj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2vxnjjeod.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gt2kfhhbkmn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2rphmmgmq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2lcdqzvjv.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gt2atudajrj.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnpfosct.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbbrekxb.html


<!-- 参考信息 -->