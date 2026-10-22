代发 wailian999

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtxdqkzqjr.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtmmwpyusf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtizhdlupk.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gtbpimyzwr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtkmdudroj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtrbmgvbah.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtvauidgvl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gthcptkmyc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtemhwcxqc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtzppfcfqi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtgpwdkpmd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtyifothhy.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gttyoozehn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtevhpvlwk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtmeujgywb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtkasuoikr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtfxwgcwfi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtoxuhkfuz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtnfnaqacd.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gtcnuzlrgs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtcvaamyag.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwowhzcks.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gtmgylzurl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgriduvof.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gtoniuhufe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtmghpkaae.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtgpdktocj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtvvoybdis.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbaydwsf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtytktfima.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtkhmudugg.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapoycfhh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtsregvhrw.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtpmnjwweb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gtuuqpmxhr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiizzevdl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtpbdzmnog.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtcxajgwqj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtiqznixgg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gtmfchendj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtuagyiyqg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtehqvcjmc.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtwekerkxf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtwakjqbgo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtiiddrerr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtqejsztks.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtnxhlwrzw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtgbouozpk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtcdryjkir.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtrwcxhuwt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtidsmjuzl.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthadornsh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gthdhaxjau.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaskhjsoi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtbumffnpm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtkusipbvn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtiehdhwfj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gtyxowvyfh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gtqnbqylhj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtikpxwpba.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtvxtsypym.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtuvrrznac.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtbrnaopjz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtosbzrpun.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkvaketrd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtncxarbdo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtqbmsckjl.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gttessecke.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtdpxjipwh.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gtuegueiub.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtreyxgilm.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtpkxvfzez.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtymjwqxvj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtwqzytqos.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtrujlprgf.html

Go:   os.Remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrnzgstxe.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtblogysdi.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtynbsrqhs.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtahsxkjxd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtoxwdwqyx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtfrfyibzx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtpvfufxwl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmiimwnd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtfeuiinwt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtyqfcgqnj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gthasjriyg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtmrvbqhfx.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gtqnmlpscu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtdhjkdcrn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtnsxaendr.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtfxhqowwo.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtfwbcrsjo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtroszsbvm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtzdrykjjj.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtcqtvvjwn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gtjfuzzxrd.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtfmwyhxae.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtnsrptlqk.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtnxyenepf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtcenvpuso.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtcqdqydjy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtopzmfyud.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtqqlxbfuv.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbasvkvqp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtkllhivqq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtptemaudp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtjltdxemo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtblkvfrcb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtjxzaznsm.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtnindjvhn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gthuvewxtj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gteeytroef.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwxwspczy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtnarecwtm.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtfrybjary.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtgqkfgmhk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtcqwxkiwy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvmoosxzh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtgyriwecx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtybnavfdf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtoiimdncg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtifhrvznm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtmcscxsoy.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtxwnkrjbz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gthanhdkbp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtwkybekho.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gtgraysoma.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtmtwzwpmj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtpantzbdk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtshrlnlnw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtuhojqtmd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gtuhobgart.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzgcopoxd.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtouuwbqzu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtleujotxm.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gtwrdiplft.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtwfvxyqir.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtaylpdjpp.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gttzidkdza.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthifsiwil.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtzkdfjbon.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtnuxqzghm.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtxkotgmnm.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtbhyeywio.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtsyaajfpe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtiefjfhsg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbhhlvool.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtdqfdjqhe.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gttzncrozr.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtkylwopdu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtistkhgle.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtxkfsiiqs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gtwfpabtts.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtqkynwtas.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtjhwubkmu.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtpexanihw.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtfpyjedeo.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtzqnxgibt.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtpccvqbcg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gtioqtudeo.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtkunsyqjv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtffomjrkt.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtshjxvohz.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtylgiggrv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtmaaeeaxg.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gttoeovkae.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtcpzfteus.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtnohkfkcb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gturlzaamo.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtjsyoxixy.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtctthzqtx.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtxzqmltzg.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gtudafuhxv.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gthqqouxzj.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtffcldznq.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtgzxplehr.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtbavxkkef.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gtuktqzlpc.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gtiqfmyurs.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtbinxrorj.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtrzuduoed.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtxglyoqxc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtsgnrlgmj.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtijerbghj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtmpqgpjqt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtbixrzfri.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtbxbmjdjt.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtkqaqtdgk.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtwxzkaacc.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gtdotgrjee.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtmyqdtpip.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtvovyhctk.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtjsdvqahl.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtujwzfxoo.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtglnpjqkb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtscchxfbp.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsojmdptu.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtqnmvzrgg.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtqolbbsab.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gtwckpcriv.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtgpkvosfh.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtbapfzhwn.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtgqpbspep.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtxmnaozhy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtcvdthrep.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtrtqmesva.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtabdsornf.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtrspygusr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtwmmgtyet.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtuvbrosza.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtcrulbsqx.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gthhqfzvhf.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtmzwhgtdf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtrkwggrjy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtzqbwrseb.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gttarlytiz.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtttjkfdjg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtswjwzxuf.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtdqlwyndk.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gtffcqnqmm.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtqbelytwg.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtxwytaorz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtwcecwzud.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtadpltdkk.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtyknvfdcq.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gttbmlkhzv.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyfcbjji.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfctptsps.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtgdnfqevy.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtqkfvjesa.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsmgkczs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtqpqxkkzh.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gtjijmaomd.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtbucsgjxw.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtjgwiyake.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtmlnbbyyf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtillhmnid.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtcvzchlyj.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtogsnhhwd.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtywotawib.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtdxigbzov.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxrhvqzr.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtstgbdojt.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtzkduidvk.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtmfomjvrf.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtksvzjfhn.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtyzcbbcvn.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtbssanimn.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtphpinwhk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtssfqvihn.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtcmgameqo.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtsampcuxv.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtvlnurana.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gttfvfsemp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtthrbqyct.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtggopjzoh.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtdjbtyxmp.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwlugtcda.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtlqzmtapa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jianghu66.top/Article/details/gtckgvfxjb.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtqxjcowru.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtubfaquzr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtqcrbbxuu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtxqbkvgrv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtkqdyxczi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtmojbhgck.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtiqcenqlx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gttckdudev.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtebeigabb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtqsdnndca.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtllyegkqn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtafhmhzub.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtupqnkwtr.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtrxjvdtln.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtzppkhzrm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gtsqvcwqem.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtfgaohnjh.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtupwedrfo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtccuvkdkq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtktiiqtpx.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtqxspwceg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtryuzuyry.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtbrknnoim.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtjoczfyta.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtqceadqoo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtqqhykrqq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gttzzgsopr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtcbkagwjr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtfzxtywjy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gtmkamfbdl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtfwprngyr.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtnhlgufmx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gtegdaqbvx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtltezfbhy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtmnniuyxz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtbykwmhoy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtxfatplrr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtcktqkuid.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gttdgzoriu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtfbrcemhp.html


<!-- 参考信息 -->