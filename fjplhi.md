代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtpokdescw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtntgfjmee.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtvdwezicr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gthqxpmcel.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtsqlzkxgl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmawzhhe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtzwqgdnjl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtihdsboer.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gttfgagjih.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtosrfldso.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuyvzryh.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtrbxoicre.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtcgblnelf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgoiknxqh.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gtpegiwmaq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtepqzscsk.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtrngtdzqf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtrjwbzfxq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtctvqgwkk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtdlzwrumo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoktjocmz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbhyufye.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gtaryyvdox.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbthvzmqd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtjnguncqt.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdpqtqggf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtkghwwccx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtufqbhqeg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtiijoiuqt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtauqhdsoz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtwaxevbot.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtmdtnplfg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gtrapapbzs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtbshlcaqd.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtotskjwsk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqizfwhz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtixkhaggb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsiltvbr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtjvucdnbb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gthmonqyor.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gthjnjzkky.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtvjtdmqyq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtgmlljvvd.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gtpcpgiiih.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gtipztlhih.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gtvcqkteca.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtsvmobtvw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcejxelfb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtxbhtaplq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtebtlkccp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtolpreaba.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtcztlgfww.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtumotutiq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtnafztstp.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtfxfdgkry.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyvaowicx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjqfmkrxr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtcqputffa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtidhiqqly.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxjsobvzq.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtntqtsqae.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtzrzmzwyx.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzasgziqm.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtrwsehqwg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtsnhssouq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtwqjcajxz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gthlimcgoq.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgzkbezf.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtuirnwsif.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtridqekkp.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtxfcnveeo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtxpqsayoh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gthjtlqjwh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtzfiuzmmt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtdeekefit.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubaadfrv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhengqikj.top/Article/details/gtpterwdfh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtzslguxuu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtvsapvlfl.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gtoyvkazic.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gtguwcjvhv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtcreckqxj.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtapwbegdt.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtbpvxjteb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtfvkjywjc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtshbxxiuf.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtxerpuojn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtpptrabsb.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtagtmwmvh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxqekzszp.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtrdyikodl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtvbwvldss.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtvyskqrbc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtdcnvatsl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtptbogzsd.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtkmihbjvk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtwzdmgtuc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtsuqlylsn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtphdvoymn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtxaxqrcss.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohtabymp.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtzftxpusj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtkitsoufr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtxdvvizhw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbpwmpudw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvtnsqjge.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtpxrwghbx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtxfydramx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtqdfwmtdb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtzgskbhpk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtjxwpftws.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtvqxezjft.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gtdbjzlglw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtdccojfkm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtohypghdy.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtjvfanupn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtwrzaifra.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtqanxyvgo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtvixryx.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtuhchhdjg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtenupqtox.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gtmzabccev.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtjmlufmrq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtwcqooarn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgxutncqf.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtxtmbdzme.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkonnqmmw.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtpeothovl.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtycgifuil.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gttfwcmlqo.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtwefzqtnm.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtkaegrfvf.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtfbgxrdbl.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtmfoeargh.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gtdqvbbcnd.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtjrvhkwqr.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtihuazser.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqylmhdh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtsfsnldvh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtejfkfoja.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjixagcnn.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtkyciwaol.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gthecbeawp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtogddqyfk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtghluxkhc.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtvwmysfzm.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtszlrdmys.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtfpaudayp.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtryurlhzm.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtvxkgtwmk.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtpoqxebwe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtygdivtek.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gttgphpoee.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtqttfvpog.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtatqyzkll.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtmvqjvery.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtptfziuwm.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtngmzlitt.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtofculbiu.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnqxhofhk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtrvxoxqen.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtnwdpzrot.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfebhvicn.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gttvgrysqz.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsacygxok.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtgrzomvyg.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gthmtcdufs.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtnmiyacej.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtuupxnryr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtngbzjffz.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtksfgjyfh.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gthdyixtgu.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtiohtsrrw.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gtzrxjfvcf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtohfdkzyn.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqcyjylf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtjohupcde.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtawmejnyj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gthxqdryon.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtmleslftd.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtmppixngz.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtlyuotocr.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtwybawzij.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtsusndnea.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtuojqgqmp.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtsufwetjz.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtdyrzqkah.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtvilfsqgj.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtswyqkiga.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtcpxaxbll.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gttwqvibcg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtbqqqspve.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtfkpvpzpj.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtguriqqqe.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtjlnnvjsc.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gtaiekxlqt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtkcamyqxf.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtcjlbxkvq.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtztgdtuwb.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtawfgwujy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtjhacukiz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjajwfuma.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtdkbxwkwe.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtklqdnrtj.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gtofehtkbu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtcaunrpks.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtfllmvjzw.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtqgfqqeyp.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtfrppzifg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gtgoxfhyrp.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacbfmhdi.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtarwqrpus.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtvwourhgs.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtakubpldx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtcslhjvmt.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtrqfaezln.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtdlkdoqus.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gtrdjfhbxn.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtrfuuuioc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtoqplhmfu.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtrivoxwcl.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtruccqjgn.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtvbfegwhr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunxqfhrp.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtwciklkpn.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gtzsvmrqbo.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtwxhrpvqd.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtiplzszao.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtorvpulqk.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtgrxxnqli.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtcjkrjlie.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtnuazddtv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtxqcjmbib.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtfdkfavwy.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtviddmrfg.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtmaqnnzps.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gtsfzshanp.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtovetprdq.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtatslnosq.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtwsqjyatv.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtdxqmbxpk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtidlsmzsd.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtgsydiooz.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtwyrrooij.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtpfnlqqba.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtyxcgyefo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gttnatlvbg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gtyobzeaen.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtelkzdjid.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwykhmnwu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtkeepbwel.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gteyclguow.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gtgtwaxixo.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gteexfsfwy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtnnvxmnkt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtklbpzkxr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxsmcvqt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtedlapneh.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtrompxlir.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtitnexufg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtcbpbiiib.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtlacrtvff.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtxmweojdy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtfkbijvcr.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtqgiawhmw.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtbzipnrdr.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtddeltekt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gthpmcfhzg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtgnnworbb.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtinoesgzy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtjsavxxbw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbhamyixy.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gtxugtvvpn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlwkcoorj.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gttuqbphsb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtybhfcbeo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtcjrknjoy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtpbqbbepj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtkwxxbluf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtfpmblhrb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gtueiomqlj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtzjtokvph.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtyuzqekae.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtxrsoikng.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtmxzxgqyo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtznyamcdq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtpqxqxzxp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmrzjsfdl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtzowmszmt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtoerxxohs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtzmgbazbv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtbsqxzvrf.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoifkggo.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtakjonpbn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtpilukzhh.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtmjpnttxi.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtmwfitqkc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtyqsdknzx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtccfjghlp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyidckbg.html


<!-- 参考信息 -->