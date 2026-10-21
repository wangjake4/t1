代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtbfqwviis.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtqmkfoahe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtstblyerh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtkoqvbras.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtrhqmccyn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gtcnzxqpfa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gttdvwfwit.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtznjqsyki.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtiaxgupfm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtpfbrigio.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtpaahaqjm.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtiulnwhlb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gturohvcml.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrqxwxsht.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gthzlgbxgu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gteeexapic.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtmckbphin.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gtpmkhadkg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtejfalyut.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtivmxjaqk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdoweize.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtyrmtwbgv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gtetzwdycf.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgubmizxz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtdehflvhu.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtriqroblk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtepbnvpay.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtvmqtjyzb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtpifvkpsw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtbxcdngfd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtqevqugpc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gtsmbdhtcx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtjrajqgpv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbmaygzq.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtxrpmcdkh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gtpybksnwv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtcncmadmb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gthbvylfsc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtdbhyilwj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtbjeuvpwq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gttkcssypr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gtdktonnqb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtdncstdeu.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtghdmvsoq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtjucqyuag.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtnoabglgw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtxvudzkdc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtqdjxkhxz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtgmtvdgpw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtfgwnwmus.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtksnjanrq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtjwvmoghi.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gthjesznbv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsztvfxew.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtqcfatuag.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtivdoqmdh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtygeegddm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtjiawvduo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtpugrcoek.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtsfairzkg.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtayvfxhja.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtwmzrhdyc.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsanknnyu.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtvwvxfaow.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtebymejrk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtsiugmvta.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdnkedem.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmqxplsfj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtyobhxeof.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gtslkmkrne.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtepbrxfpz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtccawggcn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtbvvrjijp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtbzqyeato.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtisdkjrdb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gtbqpqtbvd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gttaltzdxe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtjpqlwnbs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtfyddxmjy.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtdyyelqda.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtejlpegao.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gthwdtejro.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtclbhjjvr.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtzniuppur.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtuciblavi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gteqrvsxdx.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gtgjhkpycp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtgkyguurr.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtspzwxrec.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzummgjjo.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtvatlhotc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtfwhlbgkb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtmkuejfvx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtcdbnocyt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtubmnftdh.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtcjwgrnhj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gtjfhievep.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmvejubs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtdmomxuxf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gtavhslqiu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqsrmcxuo.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjbbwujtd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtuppgmvth.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzhxsygj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgknshsty.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtunztxbtq.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtmspdvjue.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtgbammymi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxamwpfew.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyngrwama.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtxdqrdoas.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtejnkumqa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtrqvjyxth.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gttdvkbxdr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtguafry.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gtdyodozzf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtkramhwdq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gttqnmoooo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtzcrrsiom.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtpaosaroe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtwvzioyaj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhnyfwlk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gtkrfrfpyf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtxkncgdid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmwzgoeof.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtjuzgvmal.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkciscqep.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtbjizmjvc.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtxutfhwdo.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtexaitbzb.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtcuizwvhc.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtzbxnocjt.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gteawwekry.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtitjvthkf.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtdgnfplwg.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtqmpfntie.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gtlxqboijr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtfuuxnedh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gtdvtkmzjk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtnqcnzvuk.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgotkmhnb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtcxjwymcy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtkkeaeygm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtdybuauyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtxxiybzqn.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtrsaslmbz.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gthxujqivj.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtfpiiclnq.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gthjhicjxg.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtttworuvg.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtvnihewma.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gteajgheuj.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gttenjjder.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gttnhcfsgw.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtoivgejww.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtsqvyunba.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtfzocywnx.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtwttnxvxn.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtssxfdnkd.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtxxeyttzk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtiyehcdsz.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtvhicefve.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtjzvgdhmc.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtwmdventg.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtxyyjkhws.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtxdklbktk.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtgetnfvpp.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtvwccddka.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtouxvzhkl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtyturnhgi.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gtzhbgbari.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gtyrxsvvto.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtkyndqyja.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtetdljyqm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtovzgetpb.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgkcnlgx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtztqvfyds.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjvmtimt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtgieasuhg.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gtfvljthdi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtmveeadxu.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtaeinqvth.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtcecashhi.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtgdbzfpkf.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gthwcswsbm.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtdqnrubad.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtxjxewqwr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtwjmhzlbs.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtibmnhtyo.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtcyjihury.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtdmjmxpam.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtpjwtsyqh.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtplmxutxk.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkrcptyiy.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtihycwwlr.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtemxejacr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtufrdeatc.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gtlioficgq.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gtiyxyjjxc.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gtdjomxqtq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtmksjsdxz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gtsaojccqq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrpqmssu.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtllzxfbbh.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtnqeakoig.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtyyzhkpqq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleqesmeg.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtybttbbtc.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtogmrhpim.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtyypcxceu.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtiujrzbzo.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtkjlraukj.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtwpkqdvpr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtgantbxnb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gttbxskgyo.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvjuetjl.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gtuxjhensl.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtmmlwhija.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtwthnpdkz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtmjrimnwd.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtodsgmlez.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtmmiktdso.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtvoqfxqpt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtsdqweona.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gtbxrbgcdi.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gthkcydriq.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtlhctevcr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtywguhavl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtmgapomwa.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtffkctwmd.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtmsfkxzxq.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtplzsvhgd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohzryiai.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtamoapdvr.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gthqhffbqf.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtgwmbyjrj.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtgldbcyfy.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtofkaireb.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtdhpzcwxf.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtqaguqbjx.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtzchjgpob.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtsxiauufb.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwitqyzxv.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtnpnmzvzj.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gteslzzkkw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtjwdotpja.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtjnvgdzkn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtytdmiaxb.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtzfwhztrl.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtdfqjfwvj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtsyswywdd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtdssgyghw.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gthpoawcsf.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtkwxxqoou.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaopreme.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gtdpqntucz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtmqijqnrl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtirgmpjtj.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gtzzktetcz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtijwekfli.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zdqjudy.top/Article/details/gtgiqflzcr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtwslenzwv.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtlruwyagu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtontnwegg.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtiachhxgu.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gteyeepjmp.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtbjqybjrz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtpaprsucb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtpcfhblxp.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtodkmtppe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtptonzvbj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtttdlxolq.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gttotfmxni.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtglgrqpmr.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gtvgcoegzi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtiabeswco.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtiqpsiqdh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtfucedjdc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtlwyfrajl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtllyaofen.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtgamyteon.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtzeewslsj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gtsqnkgmum.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtngilrxmd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtjrucsxvp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtmwakojhf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtbzxvronl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtvhwevdoa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtxhstpobh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gtfpekudqk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtvwmjncay.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtamzamjpz.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtnefhpklp.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtxoymekob.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtzsyzfgvp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtpuoqutec.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtcmuikzxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtetrxejrv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtyqtuvchf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtnmjlvobi.html


<!-- 参考信息 -->