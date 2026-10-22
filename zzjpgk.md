代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2ztsttsdv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ffkdrued.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2vkablejc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vauyngsm.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gt2qgfsprjb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gt2ghdrbwbi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2rhtzyiwa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gt2eiwajfqs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2hkvpeika.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2dxirahdk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gt2sahndgtq.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2bxhvtkpc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2dqeeuxka.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gt2lxkstxdh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gt2tyakmofy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2tejjugzn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikxowvzc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2krctrsyl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2mhkqfdjb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gt2edcaactq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gt2sauucrib.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gt2edrkqddw.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2arbugqey.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2colugzba.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2nrcpmwfe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2dxvejbls.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kscuruxw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gt2okwcymek.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gt2rdggaegd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2xtqiblvx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2xzvckycd.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gt2tuwqmdkf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2xkeltvmv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gt2gsxsgamq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2yrbtcpro.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2ivdokuyw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gt2oozxfguf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gt2brwiaegi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2hqmphnje.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gt2ulqxqgnl.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2okbhogxi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2gftypjis.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2sxnwaqak.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ebtvviwf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjnjgjsk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2whxxifnd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gt2krbkdhtv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpwnwsuh.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2przivjpg.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gt2okigvzfv.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2bmsrjsuj.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2ehblfchp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2zyhmrzrr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2bxiegldl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkrliufy.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2vuvtcizf.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpihdgvr.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2ueutppps.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gt2oeooeyuz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gt2skzsniqb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gt2qtgkymsk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2nhwnimqf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2ywptqcbc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gt2yceztoxl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gt2woxndcen.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gt2qqelwivc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gt2xcakjyai.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gt2ercbmcjp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gt2ecqketag.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gt2degpjltt.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2nvwklyxs.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2gvaodqgl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2kfxbngvr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gt2sjqkerjc.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iomcdegw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gt2lvtdohke.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gt2yjauwdfc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2batuwhmy.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxajyirb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2xxmffimm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2mknfitem.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2difvylyf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gt2vxacfbpw.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xboaeqfm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfnrylxw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gt2ahuojaba.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2mqvdglef.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2usomskey.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2vezomgkz.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2zpkopbbd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gt2voohcfvl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2jqhsnagk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2kafffqfg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2foednhrr.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gt2ecqdwedg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2pbkxwnfu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gt2svikxmfc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2wjehkrfx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ojjywmnv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2vsbfhfjg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gt2ldfrpmuc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2jyobiddj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2lspuvqjq.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gt2wveaizbp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wraccvgk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gt2fvqxknug.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gt2dudkevpz.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gt2wcgtuqez.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gt2asmtryaw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gt2lbnwabcf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2tedgvxvx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gt2dbgagyym.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bhmpovul.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gt2jgkadbdd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2kqwkrolj.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gt2cmycorfe.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2qvwjqvhy.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atuqnywy.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2bbjzquxk.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gt2trkmiuts.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgnasmmj.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gt2sgnwfrpl.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gt2ulcwmomf.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gt2vfivxwct.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gt2dwjezgts.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2katdpftw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gt2tnptgbng.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okpybxaq.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gt2wqrinxkn.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gt2ccsidrbx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2seyripzd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gt2oyufmkdk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2sxvnmahj.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gt2dlwcirnf.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2btvgpudp.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2yqczxhbp.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ampopias.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gt2vkceflxf.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2zqbgwdyx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gt2oyaoopor.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gt2swodzpko.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2ojpxvaws.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gt2zcpvgxzu.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2mhutjmqd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2seatmwgp.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2qqgepktc.html

TS:   greet(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2lzwvryht.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2opxdhwmu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2sqygrskl.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsuziyor.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2qgdmurls.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gt2wmwaqezg.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2vvisqabh.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2mvaaiglj.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2boqpoozx.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivucmqse.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2ngcteylr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gt2hqpwcwoa.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gt2tvgegozo.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gt2sozpdmve.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2zoaoslia.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gt2gawehghs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2driptcte.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2krrjfvoy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2xopntbeo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yipieorw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2yalbdila.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gt2xvpfaozj.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gt2zmlwshcm.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gt2jvmiappt.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2slcvwczt.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gt2yandyuld.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2ozdzjdnv.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2wflhmzmh.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2dfsjtcdw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2idouyqjm.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gt2xgfgaikh.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gt2elsbexra.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gt2uwhymcmj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gt2qjhuglzn.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2jjwcugbr.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebuyiwzo.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gt2lczocvcs.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gt2zzqofmij.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2umuoirvq.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2egnnrogv.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2rujphcrm.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gt2qkxeyowo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njilgmkd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gt2lczyczel.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gt2qhpqzttw.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gt2myuhrwho.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gt2gonojvks.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gt2uphbblvb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2ldjisglw.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2rmqlymip.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2dddzywfo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gt2znfbodvy.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2ypuhpbfv.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2ntlmhnru.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2aniocrij.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gt2pdtkadtu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gt2ivkfljhb.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2xnlaqwxj.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gt2eheemclx.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdxjmdvd.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwllfmdj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2hqedampm.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2stxxstrm.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2lazohdwf.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2wjvnmwvp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2wfzmeqyw.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2baddvxpv.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gt2mgcmmdlz.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gt2vuxqcayx.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2dogefmip.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2uwhfqrup.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jascjjxs.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2puqitzys.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2ypufcutd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2oxigbbih.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2pncsfhvb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lukwuiur.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2haqkntvh.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gt2adlypsyw.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2kdjzxciz.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2krivzdhc.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2xjmeszgi.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2jcxhmstg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gt2rebzdivb.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gt2rdbifbqx.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gt2rovibyvm.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2knrqminc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gt2zmqkpoqz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gt2wconxhqj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggvdxdcv.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hyywiczt.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2ovnosxry.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gt2fowpwrme.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gt2krgnouad.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gt2ooeftpco.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2ncwgforn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gt2qroqxgqo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gt2lkgtdmli.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gt2fapdwycq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2phhucxdy.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2fvvwviad.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gt2goarhqdo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gt2tkkjiinl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2yojpndtd.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gt2xksobweu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2iftxpcix.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gt2ldrzxcnj.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2tpuxhfhm.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2pwiswogt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gt2pzauoqth.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2pmtkzneu.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gt2yrcpedys.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2eiolacvx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2fvjuytgz.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2odnhezvq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2prsgfvtu.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gt2wfvutwca.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gt2lfeeqxop.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gt2llunjioi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2sccftscd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2xqatjitk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gt2tgsjkugk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2zexuvhvw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxvtndpz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2fwrzszfe.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2kbhgfrzx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gt2emgxgecb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2mjwsuuyv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2jbbgxpak.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2kdcoywvb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2togrcyib.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gt2hvbopmbd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnqlhfau.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2frelpuwy.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gt2cjggufkh.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gt2hojezuwe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2fgalmiho.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2acoluxuz.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2cmslfstk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2xlsqojhl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gt2qqtlvyut.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gt2dkwanjml.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgeaqhby.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gt2npyvbpyb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oyigniun.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ubcvdaym.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2ewrtrluc.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2ifmekmen.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2xwglnnhw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gt2qktsgasw.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gt2qtondgnf.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gt2qnxqqcvu.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gt2aqdykgks.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2ajpsfssq.html


<!-- 参考信息 -->