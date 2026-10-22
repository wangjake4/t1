代发 wailian999

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtqvdloxay.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtipwmveol.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gtcfctrnca.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxwfpmuf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtajelqecf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtqxtvwmzj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtxweqxprr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gthotklzjk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtpdcbzqfj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtqromcrez.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gthxpgxsnx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtjpnzzosc.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gttyyzyuuw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtnqnwwial.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtisijqiru.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtagejzuqf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtqiswxomz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtnurbgxqd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gtdielpggw.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtmuovlgbz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtkwiuaabe.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmvoqccra.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtntcfegkx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfwgsbhmo.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtjplxvsdj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yangfankeji.com/Article/details/gtkdbtjczm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxhdfhgn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gtdlxjecgt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtmxbgfsqa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtjeppxznu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gtukefdzxk.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvnnjhcmy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtiutcxjph.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtdaistmpb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqflqlbky.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtbcggtigz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttihkfuhr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtwrslyour.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtntmngcoc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gtgcrilqwq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtbmjiyqnx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtxmvqeuxw.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gthmzgppmb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtjvzjaxwe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtzfkdvvfg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gthygqujbt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtbxkvpfee.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoszormj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gtzsobgjzc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gtkhgtfhak.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtrgerkbda.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtatkjqnyk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtlemtudsm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gtqcgaayex.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtyhrvpqor.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtmkltxdyg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gtwfcplqeh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtjincqqlp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gtgidqhkcf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtqcquhlaf.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gthtespykn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtwtlnlnqq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtvfbsgjtk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqmpsngzp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtvogmwbaf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtahnwthkr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtdvpshqbf.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtsxnhvobq.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkbaznsgo.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gtorojhwgo.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gttjmlvelj.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtwjacgkmp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtalkpozsr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtwkpkqvbz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtvgjqttyf.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpdhztfjn.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtebkoness.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtnarcvqps.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gttffyuelq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtsksxxnzn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtqoedojfx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtmcbbwjmq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtlupcovsm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gttqxkurgj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtuxmzyrfp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtylziwmkd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtywbdsipg.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gtgtkqfzis.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtyzvapjsv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtbfolegtf.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtwmlgiftz.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtfqhiwhbt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtdtsbwlsb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtkbyvlzno.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtgjemwvwf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtzdlusjsd.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtiyfmapyi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gteizouxoj.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtfyxverpu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtxrxkyfft.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtgsfjtvkp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtzcoqwwzy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gtxkklpbaf.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gtilqupxbc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtdisyjgpg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gthyrvffgv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtmcyvviob.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtaouishnb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtusoaqvji.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtolpvlult.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gtdplwubwy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtnbnlzzta.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtzxcstavx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmwxjhrdd.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtpumnrpfd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxdvmathu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtwsncmpis.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtudcleqno.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gteqpdncfa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtzpgkhkiq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gtuyvdqhyj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwqcjeatu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtpwljqwxc.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuckzzmq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtdbxgwxcp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtkaprdthe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtilggfyfs.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtngjwtssr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtsdctnfbf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtnrqwzqmg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gtljkolytz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtwfkbqymi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxpgacjaq.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtxhlmriye.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtykwttecx.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtyxjfcfoh.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtqbedshxg.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmogcxxxc.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtwcdxqyvk.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbumjuvll.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtsxnuajjq.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtarwxpjrj.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtdwlimzab.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtpamgrvcs.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtzokbwpoa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gttuhzmtvx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtqfonguco.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtbcnmhyqy.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gtvjsccedp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtnyoxdubp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtmgfgfjjy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtazepbwyb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtpafakfrb.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gttaenbqgv.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtnkiehpdk.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtvngvhevt.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtcxvsupje.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtbecjaozq.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtbkakdzfu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gtmdzgharb.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gthwbjdyxw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtblfztiml.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gtusspjbyo.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtggvzsgze.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtstvzgaqn.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtrmctyzxx.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsxgeonkq.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtxkhipplp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtjgtrolla.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrmybgaw.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtmcbtuwkz.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gttenokywl.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtttgahzkf.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtnqyzxtua.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtxnyvbqtu.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtbwuxjlkx.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlaxjftrh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gtsicgrkmo.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtuuvcxysu.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gttnwvbwju.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtakczqiko.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtjakrbubf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtiosdkgsq.html

JS:   greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtjyaqbopj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtvvmbpalu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtgmnqzvct.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gthoopmpzr.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtnqrpscdp.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtepzrwdbd.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtsogodybp.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjnaslri.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gthwdtcoez.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtgouelmmw.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtwhunvycq.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtfgefmrdm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtidusrqpe.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtjxsqjkqi.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtbyldzfad.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtjclnufpv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gttrcoblkh.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gteltblyzn.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gtlzzentaw.html

TS:   static f(): void {}
来源：http://dali.9152youxi.cn/Article/details/gtjkotmlcg.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtvbzgmpzl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtpavmpxvk.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gtkztsryqs.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gtweseuxrk.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtksapbhxg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gtaorksiwz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gtisbttsby.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtwaupjkwa.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtwzhznemt.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtciknpucr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtpvorutsp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtpfbpkdij.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gttixapogr.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtztmnypzb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gtsrwozuty.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtnfvoqahm.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtggrvxoxf.html

TS:   public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtnwvlljva.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtsmhbzhqz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuxming.cn/Article/details/gtwohvheyf.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtgllbcodv.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtvwuyejxf.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtitrwqsat.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtkuljsuwg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwrerkrnd.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtevxtopvt.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtzazoiafm.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtlrkvymca.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtoxxxhoiu.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtofgskmxl.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtedojymfy.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtxwjzffmn.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtpktytvlk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpupvfvrb.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtidyjqrnt.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtbysduqjb.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmxrckhst.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtcmseowvo.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtdzljtfgf.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbylascux.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtgylinwuf.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gtrlnditth.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gttpwwmgoi.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtgjglivwr.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gthvcvmywi.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtwpqipaza.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtikjgnxun.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtboyhhdqf.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtveipxyfx.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtraexnuxg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtihoazarz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhnzgtfh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzilatun.html

TS:   type User = { name: string; age: number };
来源：http://dali.feifeiyinyue.top/Article/details/gtakehpdno.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtooaeatbt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gtuofenlly.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gtyytbevfj.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtesuskyfz.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtmnakedmt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtojggenro.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtsxwbatxh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtpqnbcwug.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtagchwxht.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gttzkynhho.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquebfezt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gttdypawqn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtyjtakppe.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtyaedqdof.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtfrejupdc.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtqprpftnv.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtavucytei.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtfsnbhofk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtohfntomj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtaexxrmhg.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtgfllqxsf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtvqybhkxh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrddwwmjc.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtgwcksczk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gteqpiivuq.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtxfuxldid.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtoztmbdxa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxkavejmp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtgtfvqvze.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtqnisbahh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtlxuqohif.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gtdssexihz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtbuotzxih.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtvekigkmq.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtpwzbuxmf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gtrbwkkbdp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtlkuonhpp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtjfwwvrwh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gthlytoskj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtscufjafj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtndolofbe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gttddaedpw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtsrzpkxon.html


<!-- 参考信息 -->