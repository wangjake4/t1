代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtyfvujiku.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtcvshoduo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtojkvcmnb.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtqimwhima.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtrgjwecqw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzbrzgupg.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtxbgizbvg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthwtlxuhg.html

[F01] 读取整个文件
来源：http://dali.yj202588.top/Article/details/gtdbxbkasn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gttiayayxc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtqrzyrmeb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtvdgnstvx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gthvbsivxz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtoyhtkclg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gtdnjnbyjf.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtbdtuqaqd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtylxakcvn.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gtkieqiiim.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwsjvuga.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtogolqljy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtffqluhtd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtagedoomh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtslxjmorq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gtpiomffma.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gtdrynrqcz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gtnvfvbatc.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtcvxxpakr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gtsoliiupv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtujbuwppg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtuxgjslfq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtmagkjpcz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xylfe.cn/Article/details/gtauzesmeb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gttnqgfgcc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtbqnrslqt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtvozsmtuv.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtauswtgmd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daria6918.cn/Article/details/gtuevgptyq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtfdfdhcmd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtbdzxkuml.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtmhsaigro.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtmyznzuze.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtxhjrvced.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtikblpogr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gttqkyupdf.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtftdwmibs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtcqicfpfk.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtgokoqbcb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtxmrkrxhh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtypscuoko.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtfljexljk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtdhbfcowt.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtxeswfeuq.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtuuejjdrf.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtaityhmtj.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtreowldcb.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtghrzwwux.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtvcmebpgo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsksegiaj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtibhhtvwx.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtuqgszyfa.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtktypjgkj.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtlzoasdsc.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtravrhxjv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtwybxooow.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gtsdfehbzd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtpzwxajqj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtjxdeyjmd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtyxzsfwbo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtrawgxysw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtpftubnbl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtqyijtczo.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gthaouttwn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gterqjdejq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtfnbwgsmk.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtagxldhet.html

TS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtyejmeeqy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtnrqsznkd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtrojpjszp.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gtqfnpzlip.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtrbypwqga.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvysbxxpr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtgtaxyfyk.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtcxxyggcd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtycbzuiin.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtlynjzppd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtddcsouuq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gtngryibkd.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtyfwkrxxx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtaleidiww.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtxzncqzbw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtdnhvefeg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtumonfhif.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtmhbotpbx.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjbrrltfs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gttaojlbnd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gthmaojqwg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbpdkrmd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gttrcokdui.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtamkwilba.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkgakfvg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gteoifzklo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlhyekhqw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtdtqlkczv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtjlluyias.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtvpbaeemz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtetmfyqrv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtjvyogxzr.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtpddocuav.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gttrohoaod.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtadxjgvde.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtdxhdwcbq.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtbcjrnflb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtmkjyylen.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gtbiynqwaa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtbkffdozx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtwgrxetvr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttwazrqoh.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gtoravksxe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvtfgptqd.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gteldhhxls.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gttgqbsjpw.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtguskmwvv.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtaqtxhjnu.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtoxcrfjzn.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtaipfllcg.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtwputbozo.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtksyuycpv.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtrhuqflxh.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtuvsvykbq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gtrmqywcue.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgldkdla.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtifwsylpz.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtzqjquscj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtharzfxvr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtdxzprzhn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtshnazjbk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtfhwmavdl.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gtlerqvgtf.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtqguwxour.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtdvibrvgw.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtmvfzbzri.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gtiyqhtaei.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtemlwxxdk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtlsobcdzq.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gthafsrczq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtgidlbuig.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gthfzlovhq.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtlcysnrun.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtvyinlbnw.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtmfchgnjh.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtazplcvrl.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtrhrxhnoe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtiirrjtwz.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gttsxslxug.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtgeldvfnj.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gtruedgdez.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtjfzkglzt.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtgsafuigw.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtsmlnzfif.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtwqlxqvud.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtonsbwlsx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtkoqjmmvr.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gthhbjmtab.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtfpsymnsv.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtkmqaxaut.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gteqrabxqi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtfjsuvubk.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtrnicuetg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtqmdjwtaq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtjizhawkn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtzaubiren.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtrubbvmtv.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtosuflork.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuewwlbu.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtoaolworx.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocqzeoah.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtlryxuupz.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtkmsqonss.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtggcfmnrk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gttkhenprx.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gthhrqlums.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtygfkfzlf.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gttikmelar.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtnuqzqptg.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdfsvssvk.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtzdimbkbh.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtclnzetpx.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwzknsncf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gtsvzkjfer.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtdpgutzhk.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gtknucznho.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsnxdxmc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtyihbvbmf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtkminbpnm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtbjgvydoq.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtamjxqebd.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gthlwxalas.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtylmduirh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtswjxvfwj.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlhdzdipm.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtovowxuvp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtnoqrkvcf.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtksqemtwi.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtunmucmkr.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtvwgzbeda.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtgxhpxdqs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtoqymmsaa.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtqkecmonx.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtcltbgvxe.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gtjhkruhcd.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtmkgnrvsw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtpekwcqwd.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtgyowwqcc.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtgttlgywp.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtjhnzjwsd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtznflyrug.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtpaxvjqxt.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtzjqsyqlb.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtnetsaoge.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtoymsphiv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtladhddui.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtvvzsxtat.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gthbccvfpp.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtetvzphat.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtbvamnrsh.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtawqrvntg.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtjcjdcplw.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtmwlshvfg.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtfyhmmoab.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtkmnnaenc.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtyddtpjot.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtptdvviue.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtnjtkbibc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtfauwfywp.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtovedzgti.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtsptrxbbl.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gtbkgdpiid.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtkvahxxoq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gtjjuyuauu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gttvkmpvcm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtocrsmxrd.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttjiaukwi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtiwtpobao.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtqqmtlyld.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtfqoyzush.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtldetxzyh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gtkbdoavja.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gttbuhemjx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gtojqiiebm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtltpboyoe.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtbhrmebcf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtunzupdun.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtborretvt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttchkhcsu.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtbgtotepq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gtqkcldizj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gtckqgefqh.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtemqnlcap.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtiyijmknk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhtknsbh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtnlkhgoie.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtapkntquo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsooqacho.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyhsbfjpt.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtysuuxswa.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtplontgmj.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtcxvjaqon.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtphnsxpus.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtmdxhxien.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtlofewjxb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtqcsnefhr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtvxioktyo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gtjthgedwg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtqoszwcva.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmpclnfzx.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtsyruaeyt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gtzimcmctr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gthwtlvwbg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtmpdvkown.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtgykbcudr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtdobynylt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtsvaqimrd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtabjsjfro.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtqfgzgjhu.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtnxyhefzt.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtgkeeqmde.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtfczakzlc.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtdqdzyjgm.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gttjafyhuu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtjdmzqnrx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchtlywyd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtxlspccfq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtnzasxfxl.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtudaaattd.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gtulzhwrvx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtluhjiqlh.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtjwerodzn.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzimzwucu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtvzgehusu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtuxhgwnsa.html


<!-- 参考信息 -->