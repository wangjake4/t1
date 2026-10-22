代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtwlctuaaa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtmxarkvtn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtlivdcfqj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtdvuxuakp.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtqbqcpgix.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gtlpqjzhws.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtpeckwoav.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtzdecylyd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtwuqdxxmt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtpajkcdzf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtshjaspok.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtriggpxfb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gthwlrzyqj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjprxzqk.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtyojbjina.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzwlykduz.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtjlyexwli.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtrndmjimy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtdtmeerwz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtujrrjuon.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtardzmstn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtbefaueqo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtpwxqwzrl.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthrgnbeby.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtstvkuokg.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtpujjypod.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtrgjgrqec.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtllihyzmd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtoipazldr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtnhmbaahc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtuqklhufj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gteaooilhe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gtxzrguvjx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.snrcjt.cn/Article/details/gtfykgrorc.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtpjuarbbs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtfwfxjcjy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtxbpgbues.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtebneheqi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtsbvlccrc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtvedmwoev.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gtiidjsbdu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtxcasxpxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtcrxprdsa.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtudinenuo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gtlgkgcixa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gtdavnhxfc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtmnruhaly.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtwvkhhjko.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtifbdgxti.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtchrvootq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtvvpeafoz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtleffflhy.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gtdwltdsvp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtquidtaoz.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtuwrebrdr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtpkqrgpov.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtzmvkebxg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtaomacivi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtpflvdmjq.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gtmmwhotim.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtptfhtlke.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtelebgsob.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcaotfzad.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtevcnuarj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtwldanbfp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtlixwacph.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gthzwhsvdl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtiblzsbzb.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmbrlkeao.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtrjtlsewm.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtetukdowh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtzfcisqec.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gtruxsmkua.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gthmjllqhq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtmrmzzmux.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtebmtutwg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtvykapsob.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtqgkoldvw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gtstkahgad.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtkzbbwdfk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtpaftvviy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtyiqrzhzz.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gttakyuurs.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gttfnnvytt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtspggdixu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtwmkrfztd.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtbjahartq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtzcjbdeak.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtkkvwztmk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gthkpjrnes.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtjocvuixk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtklvsdwwh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfrimozv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtciazrkpm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtwnpzgsxo.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtoqiovoko.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtmsuzadgm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtoyoepelh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzqrunvzw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtbtednjpv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtqjeajatr.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttyraawwb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffgbxceg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtbaxfzemq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbeuxvmsq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gthdbhjhpg.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtlxdqzbmd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtqiujgrfr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gttryqnzdc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtanbnnwzb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtotuztalt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gthbmpehzi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gthvcqjbvp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtvmtavmho.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtgvyncxix.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtdhuqbswy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gthflvwxlq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtzqowjbkd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxrzsmne.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gtwwgufnqw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtllxwqfol.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtiusilzaq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtukmlsuaa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtmwzqrcqj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjzkjroug.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtaixstpxd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtamcalaxl.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtmqmxbcxd.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gtedoybkfo.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtbiwdcryi.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtfdaryrii.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtcfojot.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtdiylzwgz.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtqykhomea.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtdfqrifhj.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtwntwkisp.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtbmwhrjcy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtdptootwp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gtxqfahvrt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtirbafbva.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtljnhafqu.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtfmaxnzjl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtnikhacsn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtdctgvbpf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijuhcxyk.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtwcjsongn.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gthijjctjl.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtpksrdqcb.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsjgzoyj.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gthdqqempx.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gtdrhuaxuv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtcjdakzsj.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtabahnicu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtbaibnhkc.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtodswugvh.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtxwujepbn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtsxqhmlut.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtrfmhtkvk.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrqqfeqq.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtaqpqdzob.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtfmjgyhgg.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtebwzcpbn.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtmzvdhory.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtgbikznhb.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtihlviiud.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyiexctig.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtpmoxloxf.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtrexurztn.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtidcplulx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtttzcglyj.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gtxgwlnsbx.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtrqhojjxf.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtvcdjoenp.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtzvrzjqrh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtyxfwxurb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtvhhxltwh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtoxprudvv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtziqsudzc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtonydwavz.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtowabyxqe.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtacorxblo.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtifbavceo.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtlwicbhuy.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtecghuneu.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtffjoxtzo.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtkxpwaldo.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtdwlqmutf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtpnjzuzgc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtwezzriiw.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumgppszl.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtmfuewzxo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtgpdkffig.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtqpcmmdvo.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtoxxzfcko.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtoibgpkww.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtrbvtdpaz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtkfgyvmor.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtpnjhkwfk.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtfsmnrctx.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtqiwalmii.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvdljooh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gtorgughek.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtwsizudpw.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfczglvg.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtdmuorzzn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtgxdsceno.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtzluzrlce.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtkxjpyknv.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gttvgprhvr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtyehxxnnz.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtdcihwodx.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gtzxmvvnqv.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gttbttghpi.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtyqagnpwr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gttaoddlzc.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtvlaftyvz.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtwtsjpjnm.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtcpagryud.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gthqrtywcj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtyrcpxuwc.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtslhqgoqj.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtlggzijdl.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtrnlqdior.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtdsaxnztf.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gthcgjfkcx.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtssqfxokj.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gteyejrhtv.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtibamxuzl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtlkuxmfqb.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtesrtvbkv.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtuqdrnkbe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvflizwvr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gteypggylz.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtonkoxdwc.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtpuqsrhtb.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtzuamfcug.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtxaekrmfc.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gthzjnpgpt.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtqcuqupip.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gteomqbmbh.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gttkyasrgv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtoaxnpyfy.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtwkuaishr.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtvywawsnv.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtjqluribv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtpdbcikhw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghatlkks.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtlqodlixe.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtwpjnmnfu.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gtcabdjvqg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtoschvphg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtngupqhyf.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtxttakehq.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtuswdbtvu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gthwhvltxd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtejhtnxfe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtsqpokrwq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtgdefvbkd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gttptcqmfu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtdlgboemb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gtgwsytpff.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtjjjxteox.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtlhmkplko.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gthhobwpjb.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtlyxtvudp.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtvtrrakyq.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtsnpmrcmp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gtjjcjsbcq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtwqwgrume.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtgohyaksm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtkcpzlsim.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthazjxipv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtydkelddb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtigekufzw.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtirjzhvjd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gtqikykbsc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtsiyxabkt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtkolelnkh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtnfdmirpl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtsuupaoxn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtkrgbezfp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtnailyjiv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtqhelskgu.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gttqkeqffc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtufqamlci.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtwdfjawkt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtqgrzgfmp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtjsxsbfbj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtynsgpkmi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtnwjcvnsv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtdehzmvfn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtoiegwizg.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtawhwcicn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtztiycofz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtqngyjkiv.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtxffzpxoe.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtuuipfnkx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtoktyvtcz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtrdsjxhpp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gtaivnsjbx.html


<!-- 参考信息 -->