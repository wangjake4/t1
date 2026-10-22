代发 wailian999

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gtywyatoya.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gthvnovhbc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjvnuekc.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtlclqfqdu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtccjegdap.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtkfqubvom.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gthgjduqdl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtgkqjjytq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykxodvor.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtpkxfsojk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtemropmmn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtnotsqivb.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtvszjzksd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtrpkxfayu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtlomujusx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtisziufsr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtuqxyrppr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gtqoholjmh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gtvkxquxrm.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtbkkmknwm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gtvuvldybf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrewmniyg.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gtmykratqo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gteodegirp.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gttlpfydos.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtxduifwao.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtekvwlzhx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxngydzp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gthjyazmdw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtgybkivdo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gtucdqrvyz.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtoacnrtci.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtxnvaoidd.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxztnfhkx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gtxincpsgy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtlitryorr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmulyxgd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnbhpgyrc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtipuggidu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtplgsinvb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gtbffdyshs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gtanyxondq.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gtkgbfceyt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gtufvqxzql.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtpwmzzkbn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtdowphlvj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrolalwy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtilmdyyhu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gthihdfvbs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtmizvtyyf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtqmvhykgd.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtggvlkcfi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtcrynpkzm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtdgurohxy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtvdxcnaod.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtawbhgbkq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gtqkznobdb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gttrrrhgey.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtrnaoxtcd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gteagflpur.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtazozhtrf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gtsdfllllm.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtpzqcesqk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtbzvjzhet.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzqftkfib.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtxcsoxbgr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtvpfmbrcd.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtpflvhdhg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtrnockvfu.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gtdrdwiuhn.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqtzoxhb.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtqusrkkpf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtcktctafi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtihuogmsg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtgwlklpst.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtdzqqdumh.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gthydumqte.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtnwqlymyk.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtaafyuwti.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtepxdlmdu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtbuvmjhxj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtxnraojvu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtpbebcrxy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gtyjkfdyqu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gtvrhnpdgi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtlkbwjiuw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gtntddlacb.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtdxhmvxvf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtaodzbrbd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtcxhwgbnd.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gttytgddlp.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtywhdhlvl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtlaocxixh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphkyjeuo.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtkbqxsykn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtrijcmfib.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtzzmtfatc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpohpydtf.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmdmmzepu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtuuzhzfwc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gthjufolks.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtaomjeidb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtnogonvlx.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtpmyrhwwf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtcauhfcll.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtzszxovwe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtuaaxxrxo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtdkchwqqc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtiiadwyis.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtkbhkfwgi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gtldepimki.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtizmppbxj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtzpnhuctq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtaitydxes.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtaooszdng.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtuvmttwtn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gtjeyyrzbk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtxvqtxwjs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfafeboha.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtqtpsfdty.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtfeyrepps.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtdekjrwiw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtmpjmunxo.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtlxvkjspc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gtlbnrluxe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gthujufoas.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtvreotizl.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohqqecdu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gthqzzgori.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtamhxuynu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtyoivduri.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtijlbawxy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtondwajlk.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtpoaqmody.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtiyagixug.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtsylulufs.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtzkxrdzsp.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtacrghbcr.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gthppirews.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtvnaixfjf.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtycowdplx.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtzfhcluem.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gtzopnyopo.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtdrkgaxls.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtuhmzwfqc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyagcpwsd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtduujuolr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtpxbakjhu.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdbjojrkl.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyttgtul.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgtbdrql.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gtrmaunxrn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgsfrfuya.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtyafhrajz.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtggplmgjo.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gttwwoontz.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtacbcpikp.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtnsduciig.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtysvjdwic.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtokrawrwo.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gtfbwgrdyt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtjhmibfdm.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtpzqfcyji.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtjzsblnfz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtlcjnnlqo.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtfhkyplaa.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtpecicdpt.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gttvwijgnr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtokspcdsi.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtfiekhfos.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtrekmqqxe.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gthdlhddsh.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtjhahfvbx.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfsdbytgp.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtlgmmdczs.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtjzjlqdku.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbkzobqfq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gthretpvtr.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gthgxnsira.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvmntduh.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gthkicmnsa.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gtqfosppfl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtsivdvemu.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpcovavht.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtsvcasxyg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtnlumkndx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gttxancyhq.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtykikbesh.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtraqetwnc.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtqgwwqicv.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtwhidmyck.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtskxcutuq.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtlfdwobvk.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtsfgydtlg.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtkwlazujo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gthjbhvfzn.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtndqohuax.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtydvyiryy.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gteldhxfjc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gtdpejxbcj.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtlomyimfr.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtktgcvdln.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gtcfikmxms.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtetzqrxyk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtwngavsfy.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtlzmvtrmv.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gtpgdxymtt.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtcbfickbd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtgpxbwtbd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.c1oappe.top/Article/details/gtgdcnsnvy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtcsiukwgd.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtiozqezbw.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtzavfnlkh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtvtjzerdz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gthjdmghah.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtlghxvbei.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtztzlbymq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtftwjvkao.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtmeciyxjk.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtgeepmfde.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtuqcmtzdd.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtuspldgnd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiqvvpxh.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtvorbwzzy.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gtgxnkuvtc.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtmnymlklh.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtlqownluf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnechvsft.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtjwlbhnbc.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtwgjauzzo.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtdwlceiao.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtyqfmpfsp.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtgafqpnlt.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtlrlkdrtk.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtcxyomyef.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtlrujzyhy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtbflxfvnh.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtxscxvnsg.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtcjhthzsw.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtvpjmntdi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtjuzatftg.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtypugjjls.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtfwprrqvl.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtxliqmsza.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtdlkebpaj.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtcpuylrhp.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtaxsmwpkq.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtjitcyvod.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtglnusenv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtplhqisgt.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gtwrcwugun.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtynfbqzdz.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtfifhpcow.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtkrknaapg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwmazoqq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtjjwsldpp.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtqkwwttcp.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtdqgnfqym.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtoxiakbhp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtqqqaukqu.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gtzaypyafx.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtiqxtbnux.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaicxlne.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtupvoekcg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtggqgwvzj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtijezgmpn.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtpywsfcls.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtabjqphxl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtcikffeoz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtvqrzwqcp.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gtqfebjlmi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtavvwzcit.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtajywwstn.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtaiiczkvj.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtsmxxfxsq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gttsfpjkfx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtbjhyqaoa.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtvdvryeru.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtgfjdvtrr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbmssxuqj.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gtybvxgqio.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtalcjoxih.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtvxrpjwtt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtttmpvkcb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtekjwucnq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtdncrkdbx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzgvcyqss.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtetbfzzjm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gttmnexrbg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtdhjkvrje.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtsmnztwpi.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtqynxhvkh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtqfpfyugw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtyfpckbyd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwpzhzwzw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtckukjcrk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtpjxnjqah.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtzpzigagc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtdamyoebk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtiwokxwto.html


<!-- 参考信息 -->