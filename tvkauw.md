代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtzfhmcfes.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtlnqaqshn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtkmpbgmro.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtvqmrmmzq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtkfqilbtk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtxbowwemx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtnitpawce.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtpnwrzpcy.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtyxxguxhw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtdythsydb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtccbnqwet.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtentudtrt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtviovojit.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtqmklfejz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtxroagyri.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtkrnzgvaf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtrabzfncb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqficlpux.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtnzhegcwz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvgehzczt.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtsnormoxf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtjqiuzgtq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtgxwolniy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtltkzqrzh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtwlasurbh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqhvxupf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpbyzjxc.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtutmthedm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtlznxoccf.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtfnovogbx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtdzebqrvo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtpqklgeyu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gthhsnsglb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtxqncprgb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtjvwqzmyx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtvqwarioi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gthhlzlnxt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gttyujsbvr.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtqkniufbp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtujnwedxm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtwevoaxzx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtjgljtbgv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtsucyeoxv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gthvemppen.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gtpmhlpqtv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtrnguenuz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjxpader.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gthyftyisf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gttwzuppew.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtovqbkfkl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtdidthctk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtqgjmewwj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtvdeutltr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtrgfbttaq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gtaozekhqq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gtnpblcqwn.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gteokcrvlh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtwljwsfex.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtyjncfews.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfwddiflr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzlumfudo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtjcybwdhz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtzfzfprov.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtovyulgnt.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtnzonkaaq.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgpctluo.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmmzrxlcy.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtkmypuvpk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gticyqoiyf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqjztnbtl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsvsxpha.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjiqmamyn.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtycdksvdl.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtumpwrhvx.html

[F07] 创建目录（含多级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeirbqnl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtgdpfhjoj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtgalwvxdb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gthncwrvdl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtnejqczns.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gtolufshhr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtukgpttci.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtlgcbdtmp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtvmmeitpj.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtllpzrjyg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtqnbvbhcw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtlqgijzsu.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gttrfybwpd.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtbxeusmhb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtmaechota.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgleicloi.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gtulavfulv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gttvwnptwj.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtqcxzcktk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtazgqfvbr.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtezbhwqum.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtuexrmopy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtbjqwidue.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtrzuuciys.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtmumhgmqb.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvludelqx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtrqmfijtr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gtbaobwqmi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkmofejd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtddcqyddm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gthvxihiwb.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvxlgxlor.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gthkkivjej.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbpufhpjw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtjnqbynrf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtoylntwjp.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gtcynffxdk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtxciezdqa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtbpvqmemp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtohlrsiju.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtxxsmxhdc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gttrrhrhjr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gtfqvoskkl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gttbvtmcuy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtzopdioll.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtercosrvn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtfhffjyvn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsstuwgm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gtsgtwuwnu.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gteckmqzzr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtpnzxxpxd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtwqwghojy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtaudupauq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtpjacwazg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwlsitjbr.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtfdmqkndj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvapqwtet.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtdeeskdkg.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtsacyyhfs.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gtavrfqexc.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtbxrqhwlt.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtpfqkxjni.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtqbosudkg.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtfvphblop.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtrtjdjpqf.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtepxjkeka.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkxywfqb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gthqxhvhzf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gttmmluxbq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyxbxctsn.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gteuknarid.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gthkwneure.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtszrfmesq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtaxezttns.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttdqjvevf.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfqiticv.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmjpbius.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtfnljboyf.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gttmgdibfc.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtpfmidrgd.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtmkckhfcm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlkjegiv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gteysvueqa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbewvlekh.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtvmsrcycy.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtipfjnadb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdegxarqu.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtbtvrgoxy.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjsrqorgp.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtjnbfvqyo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtsnvjpkte.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtxtjhrwyj.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtmkosyqxo.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtxuurwnkr.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtyrupxvku.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtosjmatys.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtxzsqgcrb.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtinrcayeq.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtgvqixaxd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtqtrwagsa.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gttcmntbcc.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtpmflbsnm.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtrghqnyjz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gtzdofqakl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gthqyovxro.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtbkizesuy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtzlmekqdf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gttpfudahw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtfdmrjozn.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gtdjndnvxg.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtpwmntney.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtdxdwvznd.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtuysasszb.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtfvyfdnqg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtucqzawvj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtqqgnycoa.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtrtgnmnpp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gtzwkjvqed.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtangsyezv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtjifhbshw.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtxealummv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtlqudbfzl.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gtbwtwqusp.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtrikpxhya.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtjgdnewwc.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyqwpqhnf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtfukdypoi.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtfttvjuyh.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqsahbupk.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtsbigoltl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtygqxyyms.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtlvcpaxsc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtauuwjvig.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtqqzipquq.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtpqnioetp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gtfcyvzlla.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyninacc.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtspwvbtcr.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtdqajwotj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gtphbnknts.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtxuwwtdhn.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gtevpbwgfm.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtgtdmproe.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtqptvpuue.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtbvonrjwa.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtqsmwfdap.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtnxfkjslk.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtfboaxgoq.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gtkaxoucps.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gttashvhpj.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtzqerfdxe.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtunysbgln.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtftmsrxba.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtwcptyqzm.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtvefoodkp.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtrowocztk.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gttmsymglt.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtfeymvvyd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtqkzqiusa.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtzuskhwpt.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtzytgzqqv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtgsdtzgkr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtbpvsfwmd.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtnmpzhitl.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtvxqoywig.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtnvxdvmpj.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtxwlhgsan.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gthaccuusk.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtatmtwuoy.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtguqvvdwm.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtatqjeyec.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gttlgjfyib.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtwexnuvre.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtociinihg.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtmtdtuubw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtbwsoypmf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtanhxltww.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gthtwwlirq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gtjwgniedn.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtfkfbxfrt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtayvodfzq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtfdbilvum.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtxtntbpbj.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gthljfhwix.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtprqpjgmo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtfxvayagn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtzauekuka.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gthowhyqlp.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtkxlaztrf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gtwzhricaf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtrzoxutcf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gttgmarbus.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtngevnzeb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtqmpgtkvr.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtyokumguc.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwzbgvlgw.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtrjllivqu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtbsxwrmpa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjagzsgpn.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gttkfltiki.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtnamtngfs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtwdmaxfhf.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtuuwlqrcv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gteowaqayv.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtfjltzhgx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtwzcaobpg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbukehjlc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtuoyhurvb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtqvxspwdf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gteolbzebt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtfpayfzgi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gtnrbkbgxp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gticankcgr.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtpyqrgzeu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtjmdxogrf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtdyznoobv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gthkbjvnxi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtvuaehgbx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtramyabot.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtpslovzwc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtvjwimuyh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtqmdtvgpd.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtfbzagrqs.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gtahfenlwg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtuqoprnve.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtiwvpnptw.html


<!-- 参考信息 -->