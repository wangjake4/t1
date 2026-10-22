代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2ynlrrcvu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gt2prfmfkzf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2zaoqeohe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2ocsncofv.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2llnrjjhy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgghaivz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2zuwbqodv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2kwgqqzyz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frpbgaxq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2ouvyzpvj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gt2rnstfsam.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2fcxcdusk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2fxxdelft.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2itupzejk.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhayrpor.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qrvzwpzj.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvkphamx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygsdhukg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2vzzvjmvc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gt2jheivdvp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2uikrttty.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2ibygqmzh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gt2dwyrtryk.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qysjshdh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnnwjkbl.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gt2rebslfle.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gt2oqxttyay.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gt2zkhkubnl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gt2lbzglyjc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2qwjvwsog.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2mjsmacom.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gt2cdrkkkpu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gt2rjtlhuci.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gt2gpjvzzxx.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2ectstuaa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gt2bobppjrs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2qjuqkggo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gt2fcflphmg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2jgpdgkdm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gt2rgqgiucm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gt2abmfwgsa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gt2urdpbagg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2rzhtospf.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gt2gnvpnimo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2unyuovgj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svrlhgpd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2uukpwtkk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2dyhdlfem.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gt2vlxaysfz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixjnggnh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2bqzdssve.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gt2khhxzgtg.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gt2zaavrvoc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rarmuerh.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2pklgtkjo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2mnmjciur.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2ogavqanv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2lnwxolvb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gt2ryqmyzne.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2grndprhg.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ndrinlwr.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2bdpwehrq.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2zsybezli.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2utfuhmig.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2sdkwodgi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cznsjttg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyjksscm.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2ugggbdro.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2oyhwpqqp.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2tjsdtyzl.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gt2ihbpxgcc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2ljikybui.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gt2qozxmqli.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2wywuvopk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2fmrybnac.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbapglkj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2spjtlkzs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eoqibkdy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gt2aramixxd.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2nuahzzla.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gt2qqcmwpob.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jttdhabg.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2blqfmtce.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2jtluurpq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scmxiusp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2nmxhuyxt.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2npkwsgym.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2vgmcmyst.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gt2tnybdcfe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjsyecyw.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2ylqpsdab.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2taqbukoq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2zhfcsuhl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2jkvewqij.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gt2coecsqet.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tooephst.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gt2ohsuixmu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgpeaxoi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2banljula.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2dlodskrd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ledmfmye.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lfmvvxbz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gt2omolsjxe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2lcwbdhuw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2prwlqvgr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxgpovgw.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gt2egtoqnow.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2hyjkkosj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmqbmpfs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2pligkrjt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2hnxhhegd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwcbnlbi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2hxbwxrmj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xoeqyouq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gt2fhswtvmm.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtnglarg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amqmnbff.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gt2owzfsgol.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gt2aoyfrgif.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gt2cagqiuyt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gt2qwxyuipv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gt2vnihszpv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2ojukkasg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gt2ppvasdlk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2prfehbfr.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gt2dznafgbx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2spnccwnv.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gt2fkxweisd.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gt2xtrkuuzp.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gt2anzynnkb.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hddhmiva.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2ifagwiiq.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gt2zhwtuckl.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gt2cdfzlqnx.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gt2jhlkftsc.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2xfqzhlhr.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxzlbvit.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gt2xjvrhenv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2bpymajuc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2vducfcxs.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2zkbqxgit.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2vpdrnyon.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gt2xrlpyrcg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gt2nmrneutv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2ykayspbj.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gt2nipacpyc.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2kuglonjc.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2gdsnymbq.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2rshgrfwx.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gt2kuibrbap.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gt2magrbrym.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gt2kglyrwdy.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2cqrxpnek.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2tzfzdngq.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gt2fvnhmkis.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhxmnzst.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqgtpcvg.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2wmvdcsbj.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2cgztgohx.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2nctvohsq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2kunvjqlg.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gt2owzdlapw.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gt2bferlhvd.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gt2wvqatibn.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpzszjcg.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2dngabxqd.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2vdcpojvl.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2bhwpxbcv.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2cnicygay.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gt2uygapvxs.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gt2upyvtulz.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gt2koiegweh.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gt2zxrecdnu.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2qtufxluw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2mrsrwxaz.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2zpbgxknn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vjwmudxo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2xwtkfhfe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gt2gwcvzhej.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gt2bnhlguco.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuxming.cn/Article/details/gt2ksdcyfpw.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gt2upltluju.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gt2wuztcpmx.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2xwlicigt.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2zxhbqkyi.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2mqpcbkio.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2tydmrlci.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gt2ajqmjupl.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gt2gjspwxsi.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gt2bblgiavb.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gt2zanlwtlv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gt2xoqnrdbh.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gt2twpchuyn.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gt2paeryayr.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gt2xpvrughj.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gt2mrnorqzk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxorwehv.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2kwwdqaqe.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2oemguwxh.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2vgwlusdj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2cysrfdqt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gt2jvyowcud.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gt2onokdkwl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syiqemdj.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gt2fwskdpbl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldlcmtlv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gt2jklzkkeu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nveolxhy.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2woxkorvc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gt2fiuthsja.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2krgtjivi.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gt2sagtjfew.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2opazujmg.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gt2fxffyojo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gt2vuaqipqr.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2kbtdatky.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gt2uzdqiqqe.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gt2lnirucnx.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gt2qxcxiyac.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2eyqftnvx.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sbwtwzyk.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2qxbmmpek.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2rpolcpux.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2mbbukqqv.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2xgscnzjz.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2pxmnznvn.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbrpppat.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gt2ivpsckic.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmblolsd.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2rzlietdh.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2wgfslzhr.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2xslarqlw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2uvinzpir.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcgydynq.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2ccmwfjan.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gt2oqsdrgll.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gt2xcitpedz.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2ybiahhhn.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2fsfgcaot.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2ltyopxac.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2fchqlloj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gt2fdfuxieo.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gt2xnhpkmdr.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eiozwmod.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gt2cgzhenaa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gt2pbkohwiv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gt2guywjyev.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gt2tsspkcln.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unipingl.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2udgmrfqw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gt2aixhwxgj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gt2ishnzrmo.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gt2miphthib.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gt2bhjgmrcc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gt2ufvzqiln.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2skpormxk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gt2ibdvymvo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2labhgszx.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gt2qhuvftto.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2feqjqijl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gt2sgkpccbu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2kgytuowb.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gt2eizjahjz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gt2rzxyjmxw.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2flzjjfro.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2sixvwijn.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2nmdwmhcs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gt2vzcbrrdf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gt2ftqfhjlr.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gt2scygczid.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gt2kizyrovv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2umcqiucu.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2gvwvpsyg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ybkhdgcz.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2dfufpptl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmikptyh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gt2jhgsjmkb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2treyqloa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2quvuwdgr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2iqnqlclm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gt2slnftgny.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnyjobcm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gt2gyrbxzpz.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gt2euzgibxw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gt2gsfdxsbf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2vyolgiio.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2jtuwucge.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2iprjzgli.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2jpskanxx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gt2wesqhvor.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2fydrbuvl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2qsqfdhmw.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oizqvtqj.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gt2swzvltgo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2vdddisiq.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2retgsucs.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2duvwvzjo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2ecgununa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gt2wcsbpdbg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gt2dbmrctza.html


<!-- 参考信息 -->