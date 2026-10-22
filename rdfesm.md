代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtmrkhjngu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtfclhxxku.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtczkbramj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtnaoitjzf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtkqocnyoh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gtmkqcozkw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtkrqjvvlb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtwrcuiiic.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtfakqqkhh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtppohixmx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtxxhpctjr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtwhnvnvmz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtdajvdtmc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtypcvmipc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gthxwkpbjx.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtdpwdwzaf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gthgbccwab.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfxwacxyf.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtbmoludpn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpaoeopfr.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtfmcsaewt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtzgxbgxta.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeuikfpa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtlevfukbk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gttvhcmgvg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtwubfjttk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gttunvsloh.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtwxxxlvuf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtjfcqfihl.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtbmhlhrkt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtbqheesfm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtwvlrjfwi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnpwvwaf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtsqjkiubs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtmevnybka.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtqjciebow.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gttcaushhk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtpomhlnyx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtsfragglb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gtuomovibv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoiuedqn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtkjavaufv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtsnocykxa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtckgyviwk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtxrixpeud.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtaqifbbzf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtvzkloadl.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtvrodtzeu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtbffhstqe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtdcibjlzr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtcraoyuhf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gttsokdvdn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtfguohgos.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtjffxfodb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gttcvqdwna.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gtcmuzleka.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtchiqwnrf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtdgxydpsm.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtnsscgevk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtqcajgffi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcrnkqfaw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtiwjcpizc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gturkppqgl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtcfoyrrvp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadqexhqa.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfnetuvw.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtsliessqr.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtpuesftwz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtayncqizl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtsspuolei.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtnahkxepw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtxkrdtxuq.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gthujmlead.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtunidyisv.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtzekprchn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtthzyrqiu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gthjyclhpr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtcdezxzuo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtsrfrqsuw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtqonwztse.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtassjjrij.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gtwejrtniq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gtdiohpvwy.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtpwkgddsu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtfmltlilr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gthsnyqdds.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gteqxtxuoo.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtfydilwwm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtxbzrzjhl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtniiwyxhp.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gtwjtpfyut.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqspghhh.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtspfujyyf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtibepcday.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhiykass.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtpqfsjyxm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtdsgekhzi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtgmpanqla.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gttaygenbs.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtqooqkcui.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtxmamjnsf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtwyazqqme.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmzjbyeod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtgztjgpbt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdzctsooe.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpoxqbxtz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtmunyqemq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtctljcwrt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzpjzikiv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtppncirhq.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlsqaszf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtivsbsgta.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtdbyoicga.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtotafzqlz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtihmabrce.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtrvgjewmz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtewcfvnkn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtlsumyurs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtpekhnpxu.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtyzmewxab.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtqxqpqlnk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gtknnrqpar.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtgzgxpimc.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtbnairkym.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugbyqgdy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtvuwwwahb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtnbtwxksv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtjbzizkzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjribmkni.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtuxibpgvm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmikeeyie.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtkhmpofpy.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gtbldtufdx.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtaogfmhrg.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtjwzidhoy.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvnthfzja.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gtxxxfqmjm.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtmiklozlq.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtzqojyqwv.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtiqwlqbmy.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtpoxvxvjb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gtllxjeymy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtmvbpcgul.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcjffbgch.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttazkyzln.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtiqvzyfuy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gtqwtnzelw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtuodqrdri.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtinjtvgwf.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtlkeijhgp.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtouvoztsl.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtcfwukkee.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtdoosavgs.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzbybbze.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gttgwhrwtx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtclpppmze.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtbpdznvkr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrykjkab.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtxlnnulop.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtzooszwid.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtvwuovidu.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteovoregt.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtscnwhjcy.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtiikjloaz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtejkthewa.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gttcikarpr.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gtlurkfgsm.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtimklrcxu.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtnqkpgjmu.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gttmtkbyei.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtiqhysclt.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtiugkinij.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gttjmpycxl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtsjrfcmnb.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtjsqtikjt.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtbcwekyck.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtafqjolcf.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtogsxkrib.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtfppqdlfr.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtheclyiwd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylkplxgj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gticdbcjvj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtatdibrjp.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtgtzogkrq.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtrcojbffd.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gtlskuvevs.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtqezmrpvx.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtlfbuiejp.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtsqonenxy.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtgmdvyexh.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtklxtxvtq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gtvasnirnh.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gtprlpepgg.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gtbepxwtpe.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gtkygsfqee.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtkicpbczg.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtbjvzijrl.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gtbwdzukfq.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtqdxkznyl.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzdnyyjm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtambpzjrn.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtldxqzutf.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtblyocdau.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtsnlyqzux.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbthorsvd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtwvxaggtr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtrcxbhygw.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gtgkquwnot.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtuwmzoyik.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtrnauyyip.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtmazbibnf.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtouzwzhmc.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtzczetxcz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtqqwvdldy.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtrhfddtpg.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtswtxgnah.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtfdkclisv.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gtbryfhsio.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gtyplikrbn.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gtjpmlvmuh.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtwjrtawcq.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gthbnfmawm.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtvlcwigvz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtvlhwylay.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtadiwfkmc.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtdcqogylq.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtzedzbkfw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtiivrdsff.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gtcsokjebo.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtndwrcigj.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtplcauxrn.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtidbslaxp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtqquohazd.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtioqopupx.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gttbnfrbgg.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtlvhzdpax.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtykjljglu.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtmqxzmgtf.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtiusctypq.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtzkrfjblk.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtpyivwtoj.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtvbfhxnui.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtraekqyqs.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtfnxpiptb.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtthvbdrsj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtkgyckiwk.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtaqvehtgu.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtrfndkcth.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtsilfujca.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfloloeps.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtwdldcgzm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtpkixzqrk.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtnunxhwzg.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzewlshcm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtlmkxqmsq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtcgrqpeee.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtpsgyadgv.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtneriukvq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtedrtzftb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtexajsnpw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtclcvveba.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtdkygmbmj.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gticjpleke.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtbplncpud.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtdulgmipd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtvbtsnhml.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gtonreuccy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtghjlepyq.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtbmxctwyw.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtyjcwkzyd.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gttjsgherf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtmhatpjbj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtbhyzfdfy.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtcogzscpg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcxkmujv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyarmdbhu.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtdqvbtlle.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrepgtpfr.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtpfvjctoe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbeytsvu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtgfxsxbef.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtchlylzix.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtgtorcbjt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtwsnbwltk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtxacccsbp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtmkhrtdfh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gthwhugzvq.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtqxqfgtro.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtatvxzplr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmujfirfu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtuvhilots.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtcypsexjx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtlzbuuxhm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtnibfbkvj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtmnftykyi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtqzcqvxoy.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtnvqdvidx.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtgqqghahy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtvdzpwtlr.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtipflezgx.html


<!-- 参考信息 -->