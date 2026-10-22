代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zsritazx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyizzrrp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gt2ccqbjslb.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsiekkhu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gt2fwzlwygf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ypsborjo.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2xiqukkuo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2idhcfgyt.html

[F01] 读取整个文件
来源：http://dali.hnqzz.top/Article/details/gt2dweowzab.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gt2opcezojr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2vzspztev.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntsatbbt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2vhrgulhe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2jcquvmrh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gt2kgrsqyvh.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2rkbfkoyy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2icwtjmcn.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gt2uktybbnw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gt2zdewdcnj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cjbzwmig.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ayakfqom.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2gapwmxqe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2wcynoecq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuxming.cn/Article/details/gt2bvoirwdi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gt2nmulurok.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gt2vndjkyev.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gt2vpemmkxx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gt2akfbvwpz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2vrrhwebg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtmcyrxt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2iziytcxx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2yuirjbjd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gt2jkxtvddw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gt2ijmgtvlo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gidowoua.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gt2ntkmrzxd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2skxuquqy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gt2fptxyxcx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2asigrrkh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2igpnmdbc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gt2fchgtwcd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2flqtemus.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gt2hhukrqom.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2fogvtfgi.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2zttbfjdm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gt2pjserotj.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2fesrbyxs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2xxjmzbzt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2cxmnzlgm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2ynwixryx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gt2ndisxmzx.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2adqflepw.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2clhatatm.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gt2rdvyeejm.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggilqgqd.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2svlqbicl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2snsjumom.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2uztmtkfv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2xxdqjtln.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2djqzpweg.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2saluujtt.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2egmrmrdl.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gt2chljlinm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2blrpqoye.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smozelyz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2hltgnzdq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2nfxkqisw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2jkzzklww.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gt2wrixxeds.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gt2xncszicr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gt2xzwrcpuq.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gt2oowygjjs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gt2fkooonyx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jfccnvsk.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2kfzvatve.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmudvzjk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2zupculog.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofwhmtox.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2uulnawlp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2bnaiorlm.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gt2ylkonbtj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2povlliia.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2yfbjvsyq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2iyxautal.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2yqcuzrlo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkponsqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gt2vpbmuwqq.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2kbigyzrl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdiykrjz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gt2eovghdtg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2sjolaysl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2junskbzu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2syceezes.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2cdwzsojz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gt2iccefpgi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2yighawdw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ttpkzjos.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2etpghfrd.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gt2mrjikycn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2mqjsqpzd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2kamvhvkw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpskxyje.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2lpxuhuvj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2znzdnpyd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gt2gffvttux.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2qigkeqgm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gt2euuiktkq.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gt2txrfjmnx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gt2docmbcyr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gt2acejsqfe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gt2mooiuios.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gt2zcirypvp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gt2udyokmuc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzeukjkr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gt2bmcqzlnh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gt2hxffhhui.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zpbizrlc.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gt2ruyppbtj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2qbxdvvtj.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gt2riaatrvm.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gt2izpwrndx.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clhbkehb.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ziekkrdr.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2zbnzmhrr.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfmizzeh.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsjsuvik.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gt2vxkylsut.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2bkqkidue.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2jzmqkzai.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2ukcbyjfi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gt2ycjrbrss.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2nlzdrffs.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gt2tnbfqntx.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2hylewthk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gt2vqpbusbl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcneawx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gt2tjawnpfe.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gt2ertotibk.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gt2uhflrwzi.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2tsnonxeg.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2guxenhbr.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gt2pfvzetnk.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gt2zqeuqesb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gt2jhnceitr.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2imtaatpa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2qsyznnqy.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2avfqfrwj.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2eqjojlyb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2bhnxshkv.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2cturumme.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2jwhsycdk.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2tbpgzjjz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2foswudwc.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gt2gdmuqoyi.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2jimpwwdi.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gt2kttsvckv.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2mzeedbbt.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2dhcvcqjk.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2xrfptgwv.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2qxzhjbvw.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2yoteejnj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2emlhwoal.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2oujjerqk.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gt2tsjqwsbp.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2aqnznhxt.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gt2dkudwmqf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2ifutlgir.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmkmwejn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2qovlpqxc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2uydksooc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gt2gdabcpkq.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2cfehoiru.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gt2lldpoahg.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2zqwxtokq.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gt2avijaklc.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gt2kketvbpf.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2alhclkbk.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2btzaairn.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2jraawrtw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2hqoiazuz.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gt2wcbrmmee.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2htypvsmw.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gt2hxbwjogf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gt2lwvgheif.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2jwqdckty.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gt2acqdadzc.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiubsnxs.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2lcmgnsda.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhweqse.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ouevldxn.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gt2dhhiyoea.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gt2trzwmqia.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gt2aytdjkxs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gt2izmoxiem.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gt2fdzmwzvb.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hxpvjjsr.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2zusadhmi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gt2zgidwaxg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gt2wqcrlqak.html

C#:   interface IShape { double Area(); }
来源：http://dali.c1oappe.top/Article/details/gt2myrzecnd.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gt2qzybxzoo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gt2vuoitfef.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2thlfwaav.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gt2jzxwolyj.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2ntpndlsh.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gt2ynoqdckm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gt2hbedbjnh.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2pfbbrpmj.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2bjximcox.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gt2pbethtyr.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gt2jxeakjdw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2eebfpfde.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2bjurkenm.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emmytboq.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2dkkpvzng.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2dxfwirzs.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gt2psrevmng.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdbwgtvz.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gt2skuyctta.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2axtdzfqr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2wfyqwjen.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ohxkipgw.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2tgqaqyde.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2sjjdakgj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwtnlrsn.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2iaspxlxa.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2lpocejsh.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gt2ashbzjrv.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gt2iblgczol.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2lmugricl.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2izmherqo.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2waccccev.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2ushaykao.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hgikfvof.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gt2rpduxwhj.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gt2yzxnipbc.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gt2mvctsdkr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gt2oudblnlk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2qsddpqfo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gt2zfkiqsin.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gt2azssqrux.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdfzwjkp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2uspifqcm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2jdizcxvr.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gt2imtxukni.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gt2yuuhtsuf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2jizgaskf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otzkyimd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbuhmzlw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2ydjnwkuv.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gt2ragoqssf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2rwwmltgm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gt2wfcdtcbs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2eqdxhdaf.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gt2ofhpivyx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zstrbpkq.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gt2rynfglda.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2nwrchsbl.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2lndpllmv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzzqfplr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gt2zlwtndza.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2eelgquna.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2maisyjov.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2frzfnrvl.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2kmkumyni.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xffctzsh.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlmclbmf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gt2ngiezqxe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gt2ztewjxoz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2vletxpkd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2pkuhhncr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gt2psklggnz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gt2nxjcqyhp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gt2isfzsmts.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2wvljueps.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gt2vuffoznu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2nhnzaaun.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2drmucvxk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ijayfjrt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2vrcmurnj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkcyfffy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gt2pivmptpq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2vsbxzlnz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bofxcthi.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gt2yuyvducz.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gt2ncqgiuul.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2sqznywgt.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2nqphdckr.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kczhuoqn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2myasgpfm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gt2vpedxnrx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2uvclkyez.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2sspvmtxd.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jiqbzqkq.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gt2yrismofq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdpbbnee.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2ntqqceto.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2noywyyst.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2grycsuvw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gt2nnkgjdgm.html


<!-- 参考信息 -->