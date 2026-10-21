代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtatzcrozu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtlkregeru.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtjgstqkuo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtdstzgsxz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtjcmwzi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtcxwqxztz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtuueeocvq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtribjadwx.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gtrjsinopi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gtwgehcgrx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtbyiilxpq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtqfzhuiwm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtpwxvsblb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gtwtxqtnoe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtxacszjtc.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyyednfl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtqcwhczpv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjbtjrnxp.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtwvezkjzw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthffkxfel.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtpxjtusts.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtlnegqatv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtqloogwzj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtnvkqbxul.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtoejhftaf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtfeeeftzu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtqcurmfqa.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtaekhqyls.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtadcfdqht.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtitumufha.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gtuqeyodhv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gthhbgryuk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtvruovthu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtwmngczyu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gthuoygrga.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gtrwuczycz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtjgtypgxf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtbfvuvrds.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtquumopgd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gttjzmzyiy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtmrnykzjy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtameulnzz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtouiiigwb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtgsmzqvam.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gtqrxfootv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtncreemny.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtvvevwszx.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtmoyfkton.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gthdaduvly.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqhtiuev.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtvtwhjdyy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtktpxovda.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gthuqsyztr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtycyxunwg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gttenaijgq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsomfipt.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtlltdfyti.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gttlzzjgcq.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtikzrhyjv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gturpncvyz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmpgidjxw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtlamxanrr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtlauelhsi.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtflcnsnwv.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtiprjpegx.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gtfvhmrmhq.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtifgfxvqw.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtukcnclzv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtlyxrzaws.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtcnfvmisn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtphamtvml.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gthibxpisb.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtrhcfaveu.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtlkdbxbqd.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gtnuvhrulh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtlmskworv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtysyiuimq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtektkcsbf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gtzygvorus.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gtoihsklki.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtercbgdaz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtsksbdakz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gthkztdvnj.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gtpuzvyzvo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gthqfiowjs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtgvjezvwo.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtsfjfwnaq.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtqijcowvg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtlficspyz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtsxoqefvz.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gtolpzkald.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtskcxzqtq.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gtyinvvrra.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtzlquvtsi.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtsfsxyfum.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtpknkpszd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtnpqiorcy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtgqlhbbdi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtaonuyxic.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtegcbgcqs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtfuihtmtu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftuiuplz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthxqixkes.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtvfakrery.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlnoyiifh.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtenhgyocv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtgnumpszl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtnhrqmndf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtddvxbefp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzvhkrghh.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gtokdwilrj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmywxcviv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtwpmqmnhq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtharhvxwg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtliaeawxo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtctoyfguo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gtdtruxapc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttxkkbyjl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gtpqbekaaj.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtynrycxot.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtzuathbod.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtfftvybbf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtpidcigtk.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtmmuzaqqz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtldsiqpus.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtdzztblbg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtpdjcziju.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtyxfsrtug.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkpvtenom.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtjrrskufd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdgkwfycb.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtowqyxhtc.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtorxokxvn.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtmulwqzjq.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtdchkbhgb.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaigtkeak.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtnhughfbm.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gttmfatcoj.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtegmxiook.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtauhedaqo.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtidbjdiad.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gttgtjraxv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsmbuawej.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gttkibhvzg.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtufhslnyd.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtlgoxzgxt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtsqzievre.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtugfvkahq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtaxzglgew.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtjcifizkq.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjomejgu.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtlqarylca.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtwbprdpwb.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gtwfbccudi.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtmmyvlimu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtsbcpjyel.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtoqdlstib.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdjckatc.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gtkavstibb.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtqxqrlkge.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtwcwwuwdo.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gttqgfmyvg.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyefxzked.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtqjimarzo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gttyaiuowz.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtzrjzbnjn.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtcqjzmzlb.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtotygoacx.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gthwpzdqyi.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtlexgdcbf.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtrdwakgdk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtlcccepae.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtyamrirxj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtsvlkxati.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtlkzzdwrb.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtafdwfgkj.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtwluasysq.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtejaqbirs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtitvzbzml.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtflcshprn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtivfozqos.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtfmkrtjhn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfzynucp.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtxvivgrmx.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gttcmmbmuj.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gtrfxwmhyz.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtosxlolcj.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtmlrwdsbj.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtmiyyuqxz.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtpypculgj.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtfzqzrftn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gtfzfqqsps.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtoskccple.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtdgfnpxck.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtenoccywn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtwnfpsnxn.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtdlqnmrns.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtwziareqi.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtspyvkmti.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gttgosdtpb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtqsqkyznl.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtjivkivdp.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdicelbp.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtwsiijabk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtmorqikyn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtckxapysj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtikacfaha.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtupdazqga.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtppqfuiwl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtshxxkslz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtxpqyvufm.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtbjuetsqp.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtojdwthgk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gttaexkxgi.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtlwioarah.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtwwrziaey.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtllivyodq.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtloedgqtm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gtwahqtrkz.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtxnargczb.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtciahntzx.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtmhfebazk.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtcbwcjtfs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtcupinuxt.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksjgeyzz.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtxbzrhvcv.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtlbhbknfo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtazjnrxgy.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtqbrpnmtx.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtiojhwapq.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gtwsyrjhnz.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtmjgenmya.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtrjzafqrk.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtwulibgkn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gteklxouel.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtsppqkczd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtcggzxtev.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtaheblrqv.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gthkwngeuj.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdkgqzvg.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtchfaioew.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtgcjobkwe.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtttbjompe.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gthzvhgffd.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtiozauolk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtbarbfyzm.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbekgvzh.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtijxobgga.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtnrwcymrp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtnlzqupaz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtnlpvvndf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtnwveildw.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtumlpehpf.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtmnnbkjzg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtricxjyid.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtfjfjiuzm.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtbgivmqvc.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtmotqiglv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtrmbsiebg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtlysrvxcb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gttylfadtl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtoifaftwj.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtpyhwwhfy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtbievzqry.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtokainqcr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtxhzqvnut.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtwlparxuk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gtrlengaiv.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtommdrttg.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtvhssodon.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtqwnbxjnn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gttkhauntm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtmezpdvlw.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gtagqbuxfv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtkhvgrhpe.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtozycjpmi.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtcrwktxxk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqzclxzoc.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtjcyvxrcl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtjfqobydh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokadhzup.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcindzfbz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtywtfivzx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtpebvciiz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtnszefftn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtfenjzrgn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtkcaeclva.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtnjcbhxrw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gthxzvzejj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtroltlgfx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtcjvefdzv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtuprcdehb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtusuavnxp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtovmvpiyz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqecgvrn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtqjffvnkz.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtleiscodr.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtlvwvjhpx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtguzezhge.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtwzsfxoui.html


<!-- 参考信息 -->