代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtnnppjfft.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gtehrzpmvo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtushlwkgw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtzjfocxcm.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtuftwybtn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtyatbiimj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtxeejofcg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gthyogvzfd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtpfzfvnef.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtrttiqvxf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtsvnkxiyq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gttpjykleq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtmhixyhrr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthntauzef.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtqbwgjcnb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgjpniold.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtedemnndm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gthcszyhst.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtryrlfqpj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtygmuotvy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtcwyoddir.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtgscttvmy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtnzsubaby.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvrwosvf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtfniqszog.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gtyidgdmvx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gtikqzyiec.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtwalvyzff.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtkgzpptju.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gticixkuwf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtnhgoemyn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gtclkohvrl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gttarjvoyz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gtehrhquhk.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtdforlkmb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gtkzspgdcl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtuhuiqkpa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gthuydprcf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gteumieksk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtvliajwth.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtnlhnwmue.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtppfikczg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtafobxxjy.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtswdgyhxw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtxutenwjw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gtiaufdpqa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtxwqhiwyn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtjysnemzq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtrgzxwqvi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaotvhai.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtcutnzkav.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gtqcvivswf.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtoqmushsn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gtkhyicapv.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtkzpykmnw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtuvobqepp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtyestivtv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtreqhrayp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtaasneyuo.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmeqkfmi.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbrlmtswv.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjoogrcv.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtckptclxo.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gttutlvnnm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtykqnofpf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtcbybmclz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtoywastvg.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxswfmyji.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthktoudws.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjrlgcxh.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtdyhlrpkn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjgaxfji.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtfxzjxbqj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtstxsabai.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtlcayjkuu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtoofihggb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtmorzjbbh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtflddzedj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtwprjijof.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gtkoljcvuw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gttspdllso.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gtqbnlxybo.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtvqfnzxdf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtaozbfsbb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtvqmpvtih.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtetuxfoyf.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtxuwpcjxm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtbjizrutg.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtirqarsce.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtpuhwgsvq.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtchlvrqkr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtoxfaprox.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gthjngyimf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtxqyuvcfu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtbuxbiuhz.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtgienarka.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtcuglsgsg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtxmtawevo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwlwcrsjk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtmpwdnjqq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtektpqpal.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtslhwxjyz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixoqrbck.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gttovqywns.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtalyufegy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtysyddmnb.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtkenzkcwv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtsuqucrcj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtueacmnkt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoovelim.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gthkoijlgu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtxrupwqyx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtlutugoji.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzbrgmhgf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gttzyvcozl.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtbloxpgjl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtnvnqtagi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtkmdezjhg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtonudydiq.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtxiuclfpz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtgkvxlpkg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtcnleyuga.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtodgfmnze.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtluszouyz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrncykqpm.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtopgqdcuz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtciunhhyz.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gthczdtbap.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtalrnfzls.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtfcsmatzf.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gthplrzfjw.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gtofreyfde.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtqefnnxtf.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtqldqvzez.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtjtravplc.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdieuajxa.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gteeixiuwa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtcyhyserd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtkxdiwval.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtkgxhxbpy.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbvngzaya.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtyffujawl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtzekrdqic.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gthmprbxfa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gthzapbeex.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtdilncylj.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtceuaxkye.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtexmnfade.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtuuyyjxfx.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtnnjqsjpb.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gttizepsgm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtqdvkhjar.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtgkjodsvr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gtfayfkhav.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtfqubhlrg.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtymwppcrt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtngsomafl.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtcqkgbxww.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzhdknsig.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtgoamemyh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtqojwdorv.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtamcdkxte.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtyovbfmhb.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtqcgypmhf.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gtzcpqlbhu.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtffryzbri.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtikhodixt.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtpdykchhl.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gttrticvrd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtbxovuico.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtcuxuwvxr.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtzjuturjv.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtnvadfcva.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtxjrfifhy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjgygmxqd.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwtghqqwp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtdepngear.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtwyxxtrzq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtwticvreo.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtemqaevrw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtdacagyda.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtrpalypmw.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtsvlhtrbr.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gtbgniiqqz.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtasespafd.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtyjcsdgsj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtegmcnibf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gtuciutkjf.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gtskvsdaqg.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtglmabcuj.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtxuixsejm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gttkpkahkb.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtougjkczl.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtfdmwcemw.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gttzvxftdb.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtmofwliyc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gttpiyjnrc.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtmpnnrniu.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtmqnvjnfx.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtgrbutvic.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtexrbyyra.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gtjtozmqwb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtlhbsyzdz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtcellqmcv.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtossndeng.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtyrzbgtal.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtfvjtilfg.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtshspgdtb.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtqsjjkvcv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtzbkmcgmk.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtolkligno.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtpffvmdut.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtuwahcktb.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtlfnrztww.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtozzkbliv.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtlkbzngyr.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamajhfqq.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gthqzsqted.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtnerhplxk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtakfgslov.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gttfwhkqci.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtjficiony.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtboohlkpy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtqsbzpqej.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtputoefjp.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtvkyqjbgt.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtaplebaib.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gttsqyauer.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gttnoofqgc.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtceiputrb.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtqxabeedt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtvvyumuwk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gthnyjkoab.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gtgtytkswy.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtbpbwfwdi.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtrsmbzave.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtvviwkpxr.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtsqunzeyo.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtfoxyppng.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtxgtsacel.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtfxpacdag.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gthgdbkskv.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtcrsqfems.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gthslohkzz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gtunrgvjuo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtnemxqjua.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzozftykn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtmpmxvast.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtnnxnewdf.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnimyclsw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtgkbmovkd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtqsmjmpqw.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtosymonzn.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtqzptfgke.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtuhukhorv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtlkvoozop.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtwspohagw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvzxncgi.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtyiidgbqh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtdwsoczff.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtayqfsyhh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtunajsuhj.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtpamruffl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtknlmuztn.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gthtcequzv.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtefzamagq.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtfapcdxvl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtdrlwbaaq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtxzqhvuqq.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtkdbcgjfy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtiwaexwpq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdqpclccy.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtqocvweug.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxyuihiju.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtfpsjkmxe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtxuohdyng.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gtzdbtuwko.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtifcoujxe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtiiacpmze.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtehqsmhov.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gtlevtceml.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtvwgbosxm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtahfsgcgz.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtxahwgwlt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtkscimacg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtfghuvzho.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyrtekhd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtyugmmooq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtehziolrx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtqdenzqah.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtbxeqwfmu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtnlkdkkvq.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtzkonrtgw.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtftbfvlvb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtmepyylei.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtkuazwqqn.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtstunsfdw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtqdzwawao.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gtkbylltva.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtwivpbfim.html


<!-- 参考信息 -->