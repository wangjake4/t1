代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtojgwigec.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtqroyiklv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtowcpmclx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtpxvawkmw.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtplbkgkdk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gtlcujxbiu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzhqdcry.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtprekgtaw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtalyzvyxp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtjoeiseoe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gtzghcrqsa.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtrsriebaj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gtmtpkerbk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnyqkgnaj.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtegiofdko.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnknclczm.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtttilnebo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtjhdlwvxz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtknadsxud.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtzirtxyjh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtrcqmswkw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtltfcmcxq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtxestnhsm.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtobevpjvc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gttrqtmbez.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gtzuuksclm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtvtkrdgdp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gtmbwmfxih.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzytirisw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtoouxfbck.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtersydovk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamewplji.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gttembunau.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtakjtodyr.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtbrqxleoc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtnihlaopm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtnfbltszb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtwxfcrpul.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtgdugmppd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtfbmzshmp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtmzaflgbw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtljpzmzua.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtzyavnbtz.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtfrcicoxb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtssgrdolc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gtmimednci.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtnbxkdqfg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtrhzjbutj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtklamsvci.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtlbvdppwa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtwalawssa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtiduadlwp.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gtvudlgflc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtbuylasyr.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtrmqhgxzr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtuydwcxrt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gteplgpqbp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtoxmrfeds.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtrohzaguf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtnsbnzzkp.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtqpqihiyy.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtzucmbhth.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtoalgeljb.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwposzcyr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtsofjvuwk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gttdlksrzm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtpxqlaweq.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtclvrvrxs.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtsfkmntzb.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtsfnrusfm.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtrsgxedro.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtbjzqyfym.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gtpvpopgra.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtaiybjyfo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtfymitwtq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtufmtxbsy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gtlgadptrq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtkcluvjvx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtmhfkqcac.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtkebmktmk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gtcjhhdpqi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtvwossmvw.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtjsvkbahs.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtcrupoxbb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtnyoohuix.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtwqvlqwjd.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gteyhzotbv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gteefgylbm.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gtcombgmri.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gtcfdnottb.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtffushpfa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gttqxmykbg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtzygfbilt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtnumjrrlj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gtyusyjpdd.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtumwwxxfe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtgjdgiozv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtjidoluyi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtsjayukrb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtxgheworl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtrzeckxkz.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbpoamaty.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtcvgwyzut.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgizlrlmm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtdmszwwga.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjgsvzbfl.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtvssztwhr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtnzckwnfx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtjwxdcjxm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmoitvxed.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtxadaavuh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtqrsrjduy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtwowmicmm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtwghmddbe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtolhedjcs.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gtavtgdjjj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gtdgdnzrck.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtyvesgozt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gtwiavrnxb.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gtnnivxsgb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtwxbiocsi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtxucqpoqt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtdqkpppzo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gttqfawlbe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtosqfrovx.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtszkoqwun.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnevgwili.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtmphdonwt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtokocagsi.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtsfzvflud.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmzgukjzi.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtqielahcl.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtvqkaomyf.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtopdateib.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gttdwinvxe.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtctndrgwa.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gthyjlhzqr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gthifiyxtn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwaezirho.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtoxrgmzyc.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gtvlhwwtke.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtxqwqmhed.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryfsxixr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtmznqxgxj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtdyupggrp.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtitcbxmys.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhomtxum.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtzxtrjsux.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gtmzccxtme.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtqwtqvhcn.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gtoztkmpok.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gtisrfgxgw.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtxgtabraf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtfolzcfeh.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtgpcmyanr.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtzcrhlpai.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtphadlxdg.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtzkfkffsc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwytjiymx.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gttxqllqad.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtzvwflbwb.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtkdleegbx.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gttoxazkwd.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdngdlwdy.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtwzaphdjh.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtckbklfub.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gthvpcornt.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gttimvspxp.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtushldwbb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtzyuspfqm.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzplroqh.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gthaxydiwh.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtpeplawuy.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gthcxwyzpl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtogrwxemy.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtturxqdhz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtsxcbxdgl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtvhwcjolm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtwtsdgpen.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtsggemhdp.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtzbijebtp.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtjauzsdjw.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtxcgqksgj.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gtonmuisbg.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtdafpdrcg.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtorfxqmmy.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtjmpezqtq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtfgcjcudw.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuinzilaa.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtlkhaazfc.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtecxtlhey.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtembwxolg.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gttqljrofm.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtblygsnrm.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtjpacvepj.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gtzokbidgq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtdbbskxxa.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gtzppgoavz.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtoiouemkk.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtuhchndux.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gtwipcijkz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneucueeq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfnbkexd.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gtscauvtxy.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gttzkkzgeb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtrrtxecvw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtsbssklmx.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gthwnxxxlx.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtdjttactw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtcmsyadlg.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtvoaksebk.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtcopoqpib.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtzdktwumh.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtmfdbraqt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtxezpumql.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtgdxjtpug.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gtrdqwaavu.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtiuhdwlpf.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtkqmdfvnl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtfhuwrdrp.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtzrbsywxm.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtjxaxgpwe.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtthfijfvu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtlqnitfap.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtgxfbsuti.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbafvlxp.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtuattpqzf.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtkiubgzkd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtyjynpjej.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtkfwzfayb.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwnievglp.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtvtzosjxw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtmlqxfzbu.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtukrvxfpy.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtvauzuijk.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtxrihepzn.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtonjtqwvv.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtcmiifwwq.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslsrtvht.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtzxegzsoi.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtpgogdrkq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gtrvlppmgl.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtsspyosph.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtqaaakqmy.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gttrhptacj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtckuamjnh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtntqkstmp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtsmhihuve.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtoypurems.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtscjcxogl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gtsvcaynxf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtacxmipxa.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtcwhpofta.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gthcdszuqp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtreamerdy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxextaius.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtdgjwkgxn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtdingdqzz.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gtccmaippl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtjbxirtjh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtpzvinbqw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtypqnebpw.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtrihppvnb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gteyabtajs.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqhhpgyl.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtrdzfqixz.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gteokmgunp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtbjgugfmg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtxbuuldcy.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtgxsajrrf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gttbjrzhjq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgritlicv.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmyrbohu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttpgpnncd.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtshlabjfm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gthzremxao.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtdexmyeik.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtfhgpxzdp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlatgpmlg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gtrbnrvuvn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gtkeqocfik.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdsghemy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtiqqtpqwj.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtgcfqhwqk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtmjfjxxim.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtftftnbph.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gttymfbebq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtlrdhjook.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtcntyewsv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtkmkswpii.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtluxgkman.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtqbiujuhz.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gttinifqlw.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtfrpemeus.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtdawhvoem.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtpohoidfl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtiyptiqlh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtxkrxwtzb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtvhpmjqgf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gtbigtizsp.html


<!-- 参考信息 -->