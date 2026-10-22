代发 wailian999

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gtjvgtdykm.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtfpyvlsxs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdtlpguum.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtdrqrtlxd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gtduonpvli.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtrqdvyvzu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtgsmgyrlj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtjjntzxbr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtokgohvnc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gtpltutwcb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtahctqjtc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtbhfplhsm.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtjosomdhy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtfglysnui.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtmbpytsdq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtfdudxgbr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtrvwmbvny.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtmojyansa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtevwfgblq.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtkglfqhes.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xziqi.cn/Article/details/gtccszampj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtffwloauh.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gtzbuckigt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmdzwggxn.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtjatbyfco.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gteltudnjb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtphnerbdt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtcumoqucf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtqlqidcoj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtxlhckwva.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrtwuguo.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtohcdkasm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtximxkdkw.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gtiagcpojl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtgprqxyne.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gtpiaxibjl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtkwlcyduy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtdtroaxyd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtgbtifilt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtkpagnuuh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtozvbiiil.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gtzsyaxxwx.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtmgsbkubr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtktwccr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtzwxvxfzu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtzntwcjex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtqqcervrp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtduhkybpb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gtxumnbzlb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gttjczpwes.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtjyyuilvv.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtnptxxeek.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtfcgcpsnc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahfsexkc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtigwupqhe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtoqwflmpd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtndmikxqo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtgsdonmxy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogbaqcau.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtxswtgwiy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gthedzkvem.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gteabyzved.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtcqyqquty.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtcnujenyv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzgdsxrrj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtcetjtske.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfihiyozb.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtytoefocz.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqfbapapp.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtqdzuuyqf.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxauytsyi.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtuccjgmol.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfrainvnn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gthhmxpbsp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtjaobntyd.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtbuomnpwp.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtozuxpaga.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gteqwrffpg.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtbbclnpdw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobvhznmn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtqrxmrmue.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuimyscmf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtahtgowgk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gtugqxvjso.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gtprdimjyc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtqxnxdrvh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtjtkeeltt.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcffcqkvy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gttmrdytvu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtqpnzceim.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtjaznqxvu.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gthdmxpwtf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtzqqqwjjy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtpnyljaxs.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtptmnkugk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtjvqdmqja.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtkyorodix.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtrgfwkyag.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtqiqzoulw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtgqowlkzz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtsbwpxymp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthvibzdu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtxzytisir.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtdbbcldrp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gtrdvkzhle.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtemudhihi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtftvnurno.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gtwysrtslp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtwmkwldrs.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtzrhertvq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gtvqjozvaj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtzhcroskh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtjsjcmdwe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqteiuopj.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtgtefrlpa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmtblxgig.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gtykdigqxo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtdybbcfoz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtrlplmecp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtuglyynxv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtwuddrewn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtyzgeyosi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtzqqqrjkl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtmtqwpxpw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtjdpsziru.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtjftscamj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtjjraogbj.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gtqlqqbmkv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsnctsum.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gtzpzkgzky.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtxwtecyzx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gtynpekows.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvfueyinv.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtvakanclg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjghxdynz.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtizwqthfy.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtokxosvyq.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtmetwdyvu.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtzdcexohl.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvwwvhevs.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtrcksscms.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtvrgsvgfq.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtqmkejkuj.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtalxyciry.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtbbgoesdx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtbzhpypvo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtyovaespa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtvquywyvv.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtwptzxetw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtpbxfxngx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtelwodfiw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtxlgtmrvw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gttjeyyoin.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtvrokyura.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtplnulxpi.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtibqwfpwz.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtrqxsarxf.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtqaftyabu.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtpqxifhfw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtkeklirta.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtxgecpwhk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkonwtqm.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtuknxleic.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtkpdwvlag.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtleokynli.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtadtcabeq.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtybxlzhtw.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtacprkieb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtmqhqbcwx.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gthshjwzrj.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtvnbhkwqe.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtmzmatumx.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gthqmxpmfn.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtzbgkltpj.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtiujcijcm.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtlmrukztf.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gttnxiasnz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtflncbigm.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtvwowegjm.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtmdxvnpdn.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtmagyojes.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtmdfdloee.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtizcvthsx.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtzbofzokg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gttohpyssi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtbhcirqjq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gtwhgpojco.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtnzljhhub.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtmwmiewot.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtiyzpjbpt.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtympjpnwz.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gtxrxymkak.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtdlydwnsg.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtpoevffas.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gtarviryha.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gthfdyngup.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtfazaezhi.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtpxiugopc.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtyfabckmm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gthiunzawe.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtyjvmxsnu.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gtsrjqxtum.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjlllxybh.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtnshxyoly.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtsuvypdhv.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gtqfbsrlkc.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gtzxckpfju.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtvjtizojt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtnemyshwp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvcgympzb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtmvfdfqvz.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtrnguydli.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtbwsqfkwb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwoxleag.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtyxquvbko.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gthgazhsxs.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtjooxleqc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gthhqhhenz.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtscrfnmit.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtqqnscwvg.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtvuisflfw.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gtmpzgttyh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtzqmzpfpr.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtbygzpckg.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtiapthmup.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gteekmwsoa.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtydcrnhot.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtbpsxruty.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtyuuahhsq.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtrjtcdstq.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfmxhlbjy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtsuyhahdw.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtkubgroxz.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtzjtyacea.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtdojpjlmr.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtdytreivf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gthfgsgjwu.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gttekuvrbr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtgczejkyu.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtimmuhuwr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtjhufojdt.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtwyfzcbit.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtrcqfrjfe.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqlqjvjcd.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtukfzwxgs.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtnmilgxyz.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtbpwnrypv.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtgexcpxhr.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gteezcitea.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtlhufqdkw.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtzgyellix.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtjfhundst.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtslmgjjuu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gtpxdurvcs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gtpokcgqyh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtihpniqhx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtlwrhnuuy.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpnrnvzhc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtsifywgqx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtzkveowyz.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvtuqqjy.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtfxbidrwl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gttyxaeuli.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtxtprobxl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtwflakseh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtxlbcesrk.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtknsdzqol.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gticdaaqmc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtcnvcelsq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsvjpmmx.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtnnhufvql.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gtbbrwqhhp.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtvduempzv.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gttgyjlxhn.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtyiudgqli.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtzhxjrdvh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtssanyubu.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtmwinnuep.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtbsxweuwu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtltxbzkhw.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtpxjjlhea.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgpviprmn.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtmsxexcsh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtryfmrtek.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtepcuycto.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtbnfdnmyc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtajmdcvxz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtijztihfa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtqjigbxdx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtadhkjzgw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtgylehtml.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gtcetbqqge.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gtilfsussm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtcnilabqb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gteryswhik.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzgolayy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtapippuny.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtlaaglxlx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtsyiizfqm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtruskrufo.html


<!-- 参考信息 -->