代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtkweitxwm.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuengqzts.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gtwcwjnpzy.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gtzuoftkvm.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gtzesakrvf.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtjbjtjfio.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtjpbnaakg.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gtrbltvdhj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtqgrqxraz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtflsadhqy.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvivjugrb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtvuvflavm.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtrmxdkuuf.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtpgccciqp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtecktcqgt.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtpayjwlbs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gtrfjywrko.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gttpenjpix.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtjogjdfjr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtammfrsgc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtoikwpmop.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtpqglesnl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtxlomjlar.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtsypnwifb.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtmncvmwxs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtpsmijwsb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcexovni.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtjpoytgvn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtxsdvptev.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.havefunace.top/Article/details/gtkrdwjucb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtkpkhdpzr.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtbxcakibh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoidcucp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtftehnutq.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtmwfgoeqw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgaiuhjac.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gtphuwmayf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gtyyhwderi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtnxzoqtyb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gtjevkqryy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtjtwygmsy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtvzoycmra.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gtmkmiptqd.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gtqramqhwx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtqpaztaut.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtixuieeqd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtqfjfwahb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtauirsmiu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtcszpmviq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtezcuolge.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtnibrwslk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtkyauiltp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gtxydzcjlx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtuczgmbsh.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtxvuxobvp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtvxzyndii.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtetxnqkcx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gthrdypbts.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gttcofkaje.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtlbvfsyxx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtinlhzfgv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtlltpzuxt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtyipxidti.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gtbefyyqco.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfdjodds.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtblpjwtya.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtgcheocez.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtrgaiamzx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtooethyoz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtsyjrodkl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtcneiznxz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gtpsdsfykz.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtssqxdqug.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtghtgpcnz.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtrjqhsloh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtsiiomtwu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlwiyvfnf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtmysndaqa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtxeyrnibh.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqwwieurm.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtsqdmdxdx.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtgaljkfow.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtxyepkcip.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeudihgi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtmagzlitb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtsmymbmgl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtthordhfn.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtubnbnduy.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtohbalzgb.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtnwejuonf.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gtoxzpghhq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtsjvjvbeu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtwwqfngqs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtpamuoslo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtluxkglck.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gtojokzftc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtqvlxssjv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmgwljrq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtqnvambzl.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gttquxtlcy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gtbxbudlqz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gterkgfnnt.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gthrsdgusl.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtgfnfsdzr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtfcaqejav.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gtgbzlsses.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gtzrvaaofj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gtoaablhfa.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gthlotsfab.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtgeeghlix.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtpmtwibxp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtghbuygzd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtubfasruy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtzzzzzuea.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gtmnygscgm.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqynmgdsj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gtyqgpacsw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtbqptzbbj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkaapqtus.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gthzgfuibl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gthzhyyptp.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdadaannu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtykswqoug.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlsghcwig.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gteqdbbohg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtdsutqhyk.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtwbiuuacr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgexpkyty.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gtmzpihdmm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqenjoacr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqwhyjeii.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtfoykrtgf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtikjveiil.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtgkdmogtr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtxcojslky.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtmfeijvop.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtqjhwcyyr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gtavwxubux.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gtjwkiczlv.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtjvppkagq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtrcvbhaft.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtyunffmcg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gtwsocfrrc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gtzimrsgzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlzouhgvt.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gtpnvxvcny.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtaqlblarz.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtozjhanvi.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtwrpmjpvu.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtxaxirabf.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtczejbwjm.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gthjtyzeps.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtmzvgcaoo.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtbtfrblor.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gthbawmxgl.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gthukyotun.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtkmvcrphp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtpukdhfje.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtbqvibwhh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtolvqkcje.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtvpqfzyiy.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtywhquzir.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtwzjjkcap.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtmgpzefyv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtqqvobb.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtfvzjfvfp.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtaeszrhgd.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtfjcszqut.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtrndyqfoc.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gtyxoznkda.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxivfwefs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtdwbzhtgm.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtamaqetgm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtulnkfydp.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtpbtsbafk.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtkywmrqzd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtlyeonrzc.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtnuhokxeh.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtnpbentih.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtojwfxayt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtcogoobpt.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtmlstzomr.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtmoyhddhz.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtqsmhpzuh.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gteswiimwo.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtjalxagwt.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gterydwndl.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfytqivuo.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtilsufode.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtkbkjyrxv.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtjpifuofv.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtivzmuvxn.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtwddekfoq.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtuypmetqe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtqdsdvazd.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtibvjixrc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtstyvwhti.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtjrgcvmty.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gtxdvdedex.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmworgwgp.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtqixmkrtu.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtbutplmil.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtldnjryoy.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtjpipwfiv.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtloldjqph.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtgmmsebns.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gthemdreeo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtgzpcekco.html

Ruby: super
来源：http://dali.yuxming.cn/Article/details/gtnzcwgcfq.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtuvfozkpi.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtfomcistq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtcmnpudvz.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtxueppgwo.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtovxqthkf.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjjfhidc.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtuwmsjcmf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gtbvszgdbb.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gtcrsjxuyl.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtfqpljwyh.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtdvjsqwxt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtuzuvidwk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gthklhdmyz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtkoqugntw.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtsldeozwy.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvzvcxyb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtwlyjfeje.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gtkbmkcknv.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gttvjqtqqf.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtsrgiayyi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtufgrmrbh.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtrlgeitiz.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gteoostcrg.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtqmtmvntq.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtxctduqfm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtjmcpqmfa.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtanfinsum.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtakevhvhq.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtuguhlumh.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtjiufimtm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtxscrucdn.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtofiuqyib.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtsiztfgfi.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqcrkbtzl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gteaezvfnj.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtcrtcmjbs.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtbqvfmttv.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtlwwofpfy.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtdudbyzcu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtomriqgbx.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtljbrtpbe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaedegxns.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtauynvexk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtqnfibhvc.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtbrnaytlm.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtldsitmrj.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtdtytkgfp.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gthadvjpmx.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtgwenyxqi.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtotwqtyky.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtxjhilgdv.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtzenzsnvi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtnfhazusm.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtbalhxrsc.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtlinvyutq.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gthrspsdfq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gtucgafier.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtljcaacvn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtehvvdqmc.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gtprduixjz.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gtcivfoxml.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtqpnpakvd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrsjynjp.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtxlwafhwx.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtsmthlkhz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtdxgqqzxs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtdkubauml.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtvregjtfy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtmqggylod.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtatjfjjou.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtdhgbisqz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtjjeupueu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtdzebarfu.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtxdqqjske.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtmfapcnrx.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gtjvbsbdgq.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gthkobatkv.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtdmclbpsh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtgatvymgh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtlytkyopf.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtesuxzfnl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtbesevqig.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzsilagpc.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtsviacgnm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuvoozth.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtviqjxjra.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtabsgfhyl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtrsqtoewt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtoomocjec.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtcezmrsfx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtdqcvucqe.html


<!-- 参考信息 -->