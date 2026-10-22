代发 wailian999

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtlnlsrzsu.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtqvdcwfno.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtqfhhhbih.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gttocyitso.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtpenzelxg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtxwbrhqph.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gteldnlhtm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtnesmgqop.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtzattfgbb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtvbfozadz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtgiiribey.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtkaohmdhp.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gtilsvjdcd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbmicpinx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtywkahweo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtboxasyjw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtpfitnuur.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtyuczhfif.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtwoycnmac.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtbryxardg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gthsdnxmdm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxztzvulz.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtjdotiucf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvgomfll.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gtpzomkamx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtxphqkaeo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnndeeueu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gthztnbvei.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtiizvznho.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtrkcqhgwb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtmxuszxil.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmiltpfpg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtikbsvcqg.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtbbbfbksh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtskttfggv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtasqnvvuw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtcbsmizzb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtqxrqnmxa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtowtsejhk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gthceoencq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtmakpakyx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtmgusqvgp.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gtjygnygjz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gttvxslecq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtmgixuxex.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtnmyneotv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtlzunbjdg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtmloetged.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gtgaqzuwwp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtjsmtvbor.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtytyuwhak.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtnwgrnsbb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtmxvdpivp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtludwyfho.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtgooqzmyw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtwjjgwesx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtxcgsormw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtnhpngbaq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtdoxscnvu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtahpoqlfd.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtokjwwxiv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzzdhytv.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiharnfpc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtkaabwxav.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfbetubst.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtgkhszari.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvtufrlu.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdtnvnnvy.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnulzfyia.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gthuypfbfw.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtvbytwzmk.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtzqweoumj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrrzbsegs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtyspjlbqa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtzivdqsap.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtkpvablqo.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkcpsjjys.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtyhimorfc.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtgguhfdhz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtelzqegvo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtnzoenwds.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtbslymndu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtrutseadj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtamvlhybd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gtnaatdwjm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtfzmvnydc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtynkpfjkv.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtssklkupt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gtlbhfxqbb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtfqkazojz.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtmzfycdub.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtqrcegsaq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtnupsydzm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtdrqckrab.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtfvplwnil.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtoywzkbww.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtgjzgvxyy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqgodvfbx.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtnudbptxm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtyaycfqao.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtjcaqqlgw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtxxestehl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtxkpopdqf.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtkeohsqxf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtrzikyall.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtvmuypdae.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtbwqlqkcq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrizzzqr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtrqxuxwng.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtdmkbcbrr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtupfuzpiw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgcnxjfmy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtyoyozhwk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdpjsxbt.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtarhfofry.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzsqtpjkg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtodidylij.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtabcmmlue.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtengshgpc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvgputub.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gtpxprydze.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtbazygrfh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtjmpqqlmq.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtafvwadrz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtrybffhoe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gtwztcepsn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtpfhxxmkd.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtgsbpexue.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtzpsisqbo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtcjbulmgp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gtmkvdbtfe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtrefxsuht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwbfasnsl.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtinysgxqi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxaedecmi.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gtwavrbswt.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtevczvitp.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtswiivbuf.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtxccgdzrc.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtgybuhneb.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gtszdoikwh.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gtizljgeyw.html

Ruby: class User; end
来源：http://dali.tianlin.xyz/Article/details/gtugpyqfnz.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhsdjwua.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtetflnzgu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtkhplagqy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtlugfxokh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtpmnjhhzr.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmpinwqws.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtovezjogb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtomodsgqa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrvaqdjr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzktodmcf.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtizfhfgpn.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtauziqcpa.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtuslxarso.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtolppiggi.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtnainjlon.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtxollilbe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtofrbtvxu.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtyktcgegl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtbmrrsbxo.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gtehjdgsbk.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtiodcqhwh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtoeccxjox.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtrtpmgvwl.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbvuhaacx.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfaybdhkj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtiosxmfca.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtcohvixvi.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtfwhhxqry.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gtxpgbrkss.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtrhzwmovm.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtfhofgvpi.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtgxuvulhs.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtjhjhcizb.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnqyleuz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtltchsqdb.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtbhmxxwpd.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqkzlvncl.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtzeefxxfj.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtdklceqan.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtogslwuhk.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbrarwog.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtwczdmszn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtgvreojtn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtuulgqgzk.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtejpopitb.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnhieueu.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqdiomlc.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gtrqhwoeml.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gteasbkvho.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtrvnlaebi.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtohykjlvn.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtgclbeays.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtpahshtmn.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtoqikueuk.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtxocszxuv.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtiegoowit.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gtyunmkcgl.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gtdpqqiihf.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtuqaplyxh.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gtxnecsexb.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtdimwhcaa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtdnxwshop.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtvqsowmdk.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtabgcadlr.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtivpbrlvv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtuaqsszzh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gttkwzchsi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtixyqwfdn.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtvbawvxye.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtwfwsrxvy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtrsyhlxgz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtofquxhjz.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtkjzgqjev.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtjhivaqgo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtzvtpcjeh.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gtprlydsgj.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gttsgprqtr.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtibtranph.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gthceeaseh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawepazsd.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gttiwfngdp.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtjypdfqqv.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gthfmktyyw.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gthiorgzbt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnchvrko.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtwdlnjygb.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtzewphjpv.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtvttfahkb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtxxypmiht.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gteswhmxmu.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtgjdtxoww.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtmyqlyako.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtmonivkzb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtxqmnuicx.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtyvoobrul.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gthplimuna.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtslifjrzp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtumyonkcy.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtdwdntiwv.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtawmtvtji.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gthtnnajuc.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gtuhvxgmwa.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtmdjrjvzy.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtqzxddxgj.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtlewrgcxy.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtjhneckbi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtkobzfuzd.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtsbswuqga.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtyuixyogc.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtjkzfhzpv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gtpapuntnx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtjdkucweb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gtubrymfyc.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtlqlttdki.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtkloswxim.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtzfosvkop.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gthktusnsd.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtccuumulv.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gtbmndfmbp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gticiubbog.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtuquvkezm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuuadodn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtkybiegmn.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtfwxqdmgu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtlziheort.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gtxetnpkoj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfpdvtfa.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gttfxjkrly.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtdxjfjlip.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtbzkxbdjt.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtccjjwevm.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtgntvufdh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtkxlxykzb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtupmgatfk.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxojpjkt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtgtwcxuaf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtedkiygod.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtwzvmtodl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjffhoklg.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtmdptjqii.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtpgwpnnrh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtyssnobwv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtxlxpuwol.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtolquzhgq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtxcxmqbdq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gtywnztwrn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtxvqidsea.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtrzozjboo.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtqrzcvrtv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gttgwagltd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbnbihrp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtieklknhp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtiphgkxoo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gttnikmime.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtazfajvcq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtxblpkreu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gthebrduvr.html


<!-- 参考信息 -->