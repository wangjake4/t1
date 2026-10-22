代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtyiyrdxeg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtqqteamtu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtxvmvpgqy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtrkjkebza.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtxghpkfef.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtdwmdudbn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtjgppkhyc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtfqdycbqy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtmmkadxwm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtiyfrydnx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtdntjtowg.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtvfsjorhg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtrlkqcmme.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwazkigi.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtvbouvgne.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvgapsvpm.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gtrmmdeqzl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtjtffjpjh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtjiiadzfc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtsjtrdjfv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gttxcizsga.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsucbxvld.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gtorlfiodw.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gticvdmatu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtgzbfkmfj.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gtourwtwsb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtwusyxezy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gtsyudikhw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtvcvevwoq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtnaizqdxb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtjinhlokv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gtvqzvmnmg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtpwstyeib.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtsqkbndsw.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gtlaolirel.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtnowctzxy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtvmvrzdqg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtsnktgwmi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkehcoap.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gtkoiabezw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtbsmeugfx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtnbwhiuai.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtejqtbpyg.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtvcofptsz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtctnkzjbc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gtkowjcfbf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtcaizlvqo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksdkkkjc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtvokwhebq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtskxviyva.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gtnkmohrpn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtvxrmbvzd.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtdhjznzdh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtxmvzitxs.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtgasynzij.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtgsvhspoh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzamrenxw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtbvfvelov.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtxfdyjpxb.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtdblenkfk.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtywvprbqx.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtgcqqfaff.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtegjxnelj.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtmlleidxe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbdmukrkq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtshctaxuq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtnalxlubq.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvidtlidr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtckkacoct.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqtcwquxe.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtvbhviwhe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtnayszjlk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtesbzxrex.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtprfodvlv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztiqpdwl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtkeitqgbu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtqnackqvt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtmtejtvbc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtejbshmst.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtewblvthn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtowimklop.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gtrmykgixj.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtwawchplp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtysmnfjzt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtxsmcycdg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmcdjkru.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gtfetatcjj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtmdmlwmqa.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtlciucjvw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtmxvyvn.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtmqnohbww.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtpmnpdjpx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gthygfaynd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtqsftifhx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gthtcprpvb.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzykspdid.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtvhuwiivp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtfaqbfuyi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtzinchssn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gteelpheiq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfjoxsldu.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtoshjibma.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtbrrfiktc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpwqvfsrt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtiwdgmanv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtnvnvqjdd.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtulldkita.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtmkoxqnsr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtruazaswv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtzztlulkc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gthrqxohwi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtgtrgtgfi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gttnidinuo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtepgojteo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtirfpvyhs.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtsrqlmmfc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtzajrftwf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtukfgymsu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gtxhqmqlpc.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtruisaqaz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gtxwwizlgi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gteqehdile.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtedszdwex.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gtynvieqpt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvsdacgcs.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtdpdbmrpw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpklnhfog.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtcpdworhm.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtndnmylbf.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtybpmxnmt.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtiwryzlnv.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtxwibwavc.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtjoqxqqyw.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtqneoctui.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtmioloczd.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtiuuprroh.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtovfgigdk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gtpenqfrqr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtovnxlcbx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtnlvloiya.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtlyaacnzf.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtnpnbfhaw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrhgnfqb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtgzjvirjo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtuwllwrsh.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuxfmhln.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtdjvljxle.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtqomablsn.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtqjokhpbr.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtlcvwajor.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gtqkvdhqzg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtebvkmufv.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtfxhbpmdp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtdoccyrth.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtvauyeozv.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtzbrxhfbl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtwuazscuw.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtfncfpaef.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtowidlayp.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtqqqzfjqu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtxijhdzvk.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtldldgtpq.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtqvrrtzjd.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gtfzlvgdtc.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtcoiulfhb.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqupkalsa.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtkctqibjt.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtclomrqsd.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtxyepsgdc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtuxomunjd.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtrhoamivv.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gtolrsvkhq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gtrtjybzlw.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtxjykfrgs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtbiepgoio.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtorukcvsw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhxejodu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtvvbthake.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtivljsqjr.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtndrhdovk.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gttompmpdt.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtufwhrgav.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmsougsj.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtzlmvbudd.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtwtfjjsjk.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gthpubjcwv.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtaobssjau.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gtnpkwmlzx.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtegswbtml.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtwamqiknh.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtjrkoyaze.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtjnrkchix.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtcszkhupr.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwcaqizp.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtbdcqysuz.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtofrjitbz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gttdubmgdf.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gtpjkbhqre.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtbgnadgql.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtmimdxewh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvejljbh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gtccedsowv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtqxmqbrrf.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gtkjfnzosu.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtioqjhcdv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtqwvpdmns.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtdmesxlww.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtyhetnmjl.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtblqydqva.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtrgiroyej.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtwgrjubtt.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtagddblbu.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtsichbygq.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtlbemoqph.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtagpjwdbf.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtthpleqoe.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtryschtks.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtuhwqxxqj.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtnzsqtjjr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpgwtrocq.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtncwltyrk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gttawdyaqs.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtfuyyebbe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtsrgmehbw.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gthdexhrle.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtawxrozzx.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gthroifdup.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtoesjhtcw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtofbmtfbb.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtogxyzqdw.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtlmhuniwp.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtciwctmbo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtyxiohxkw.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwiarjgz.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtbycykjov.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtrkpjzgcg.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtbawpvzko.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtgiabeidk.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtfkvuyjpz.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtpwgylxgo.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtwmcngixq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gtmgchvsqw.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtuebiqnqr.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtnankrcrq.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpquwlus.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtgwjmsrhy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtjtomxbyb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtaynkkbuc.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtercxdpjt.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gtcmjywety.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtpkonojkg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtjndbzkyf.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtyzjrjmsg.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtdzxhkrka.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gttpcjwgdc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtwvejonqj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtfxgyogtc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtyhsqkpvf.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtquohryby.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gthaskimwn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gthijerruj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtvbophyum.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtxftjficj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtqrwycipb.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gtqhldkzap.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtwqkbqmbp.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gthsnszasg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtjwgtwdhi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtvipqrjlg.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtgbdfxeiz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtlvuubitq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtabmiwyri.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtvgwqipqy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthoctcjkg.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gthhqnsfgd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gtyuevfxaw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtofcycdxq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtvtrxnktj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtwrmstaet.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtoyqtfpmo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtclfyfmep.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gthceycmyz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtlpauxohb.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gtfkxuqpif.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtxusmshen.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsigpuyz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtydlgfvld.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtgimesuoq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtjllvjlie.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtyruxedgy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gttvhnarzc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtyrezdxzm.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtmdmarxcr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtklzdrkff.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtknakbhia.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtisyzjjzv.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtojdcjece.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtjhvflylt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtjhkrehks.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gtqugamwjg.html


<!-- 参考信息 -->