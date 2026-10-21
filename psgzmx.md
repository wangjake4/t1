代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtjvoxppxk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtpxfqfmwi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtxgmavcas.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtsovzypnq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtdzlcphat.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsvsjaruc.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gtsgltpweg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwwksngcv.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtkapiwdlk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtclepvlcb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtncbxhbue.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gtelidvdpv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtxzafofyi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqntfaccs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gtactwudor.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdhbwklnj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtgowvkzxh.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtlhoevzdd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjwnipfk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrmeeppz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmepctzqy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrckkctwt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gteziyrrju.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtdwznrtcm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtrracbpum.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtjjkomedx.html

[F03] 写入文件（覆盖）
来源：http://dali.hnqzz.top/Article/details/gtfphptehl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtkyauhrgg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtnirjvzkq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtrgfvhwgy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtvqrybmkb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtzkkrljwe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtixivmmne.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtofsrtgnj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtpuzapllp.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtzztcmeyx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtxkxihhdj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtoheothfn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtaffgnvlu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtzdmyzzha.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtlekvlotc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtvjiypbwq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeqkgjvv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtdjohhwzr.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtbaxuuzei.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtsijimoct.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtnnrdwzjn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmuignkez.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtpznmdees.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtmrxdfzbf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtyfriycvo.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtovbrnbrr.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtpaqwvhty.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtncblrwpo.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtttkgiget.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtfeilcmbm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtguriooap.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtggcveanj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtzajaanbk.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtqtabbddp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gttnxbgdsa.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtnvhtsoia.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtmrygrmvb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtirofqlqp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtdwnvkqpn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvjeuvst.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtkyitxgqt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtcxvnlpir.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtslkqxvsx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gtjxmunhon.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtracoitpa.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gttewajauj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gtqcltbwcd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtakldtzkd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtsubwbrgh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gthssaobjn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtbuncrbcx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtobfonzvu.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gtjdgcazyz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gtzlwamnte.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtfdwrqpip.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqddubfgl.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gtcwupgxtl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtyjmqqelj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtbfwtklor.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtopehaybf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtuoellvzo.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtulyyiltn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtgowfiiqm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtwmcclaxg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtskjykwtq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gthnthmrxj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gthhwjgarw.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtuqsfqzjh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gtgzivwruq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtamzhqddb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkyyyyyvs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtlnughvja.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtlslwdmwm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtsgmjldhk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtihyfrrih.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtotejvhjb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtrskggybq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtamncecdz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtyslhxxzs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtyzbumask.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gttawietzf.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtzhupevfi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtrphkphoc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtvhdubuxb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtgxlatkmk.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtzpnsjjou.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtgqngckfg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigufen.top/Article/details/gtdxwtrvdr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtlraqlris.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtguhuhprc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwmrwtar.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtljxnvxnw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtddsalkwo.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtdhfywjok.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtetycavzk.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqhacprlr.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtbjdgbecn.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtpycufklc.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtrpzepudk.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtvjleberj.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gthxuxbwft.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtbjnywzgh.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtdmyolphx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnhpgurp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gtgmjslsfe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtlomsvyfo.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtbidqxbfi.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtwhfmhqvy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtgvlyfrti.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtdxvpxvvz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtbotvfwmi.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gtvskowevj.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gthnljmcjx.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gttubhenem.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gttpguafvt.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtykostrzo.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtzldoypjy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtmrxbpcrg.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjdxldza.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtpfdkruuw.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtlmiyxats.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtjynjoiwe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxmggnsjj.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaxzfksh.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gteyscfvcq.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gturjanyea.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtloismuac.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtctpxxhxr.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtdjxvyyjb.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtkedutyed.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtkkbfdwva.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtpgyojvdz.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtckxlyret.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gthqzduehn.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtblywoqts.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtvvbohgtp.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtzxnmadbo.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtmimohgld.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gttghliril.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxawogrta.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtckridjvf.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtpvbvdpkz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtqpusdejs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtxvvljwzq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gtctowmjgo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtkjfiqplo.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtjrmdlwtp.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtfegspuwd.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtqeybtjfy.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtfsgevejh.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtucnnoggm.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtooenhbye.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtjcqcnrbx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxkyfyxp.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtxcnldbwc.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtzkomkldk.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtcwxcdfws.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtekbrbows.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtnrhjfkwc.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gtddxikcrd.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtjemnmpbo.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtdmmycctq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtehlziukx.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtitypxazq.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gttxnavdcf.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsshtpty.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtwhlfxpcj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtfzqwzxcr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtnuqxutaw.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtastucxel.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrsriwbh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtpappudah.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtpgcpgnfn.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gtuzxbcobh.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtjdoqljds.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtzkpdzhqg.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtodnbxehs.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtxwxetknt.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtydzfollp.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtratbxeic.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtztzdibre.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtqayrqrcp.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gtehmzbbsb.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtoybnjsxu.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtozginzlf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtuucrnruo.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtwffyihyk.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtnnjajxsg.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtpdmfttun.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtysmmdgwa.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtnlebekly.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkhcvvxx.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gttvwncbkz.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtbjagbksz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtldfmiaut.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkzsguyvw.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtmyqmnqsc.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtwrdrzwmf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtnhgckelx.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtqwbwsyok.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gtyecdtouc.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gthrtzmcjl.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gttizfzllb.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtjzgjdcqj.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtemadijko.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtetvrrerf.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtykoqlglq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtuayifxrl.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtgrybdqjc.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtbygrspus.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtflidyexa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtrlridokq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gtwanxmohd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtvmrlfpao.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtmrgbxsdq.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtlqfunjnx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtyqtwsuhj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxclrgik.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtazkznygk.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtlsumnvna.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtztiirjei.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtqvlcfbzh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtaeqkccja.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtyfjfvaqi.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gtjfgmhmzf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtsfdmuevv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gtcmjebnno.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtzjinyxyq.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gtdwahyqnw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtstvvooqy.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtlwmrnvpd.html

JS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtjndjmmhi.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtgxbfidzi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtgzdghflv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtxzkfbvhc.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtiobwveyz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtqgaryhsb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekpgblzf.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukfencut.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtioegtshz.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gtvkbkdyvu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtsnkznsen.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtychoxqoz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtidibdskt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtjsuglgvy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtcpnqwdoh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gthocbgfcq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtumnkfwza.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtczdrkcet.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwmbcslu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtdjqmqjzu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzlzbredj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtfxnimmrb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtvjlxuqhm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtskdqidbo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtrtkbyzph.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsbgerfk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtltogygcq.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtlhghomix.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gtjbvxkltr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtnqqlsfxy.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtcvwkvgjd.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtcmrbqrnm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtazjncxiv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtcojylizy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtkihberdc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtxyqxaenn.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtpcrvqsas.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtyfperfvg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtrptcudok.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtxfobgzkk.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtyddoqchz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtnnifmvxi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gteirtyknm.html


<!-- 参考信息 -->