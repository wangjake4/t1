代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtzldcxsji.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtepeowkdi.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtlqdkgwha.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtrkcunyfw.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjfthgon.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtxxlnvaqv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtgoruuqjy.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtmuqacdjc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtcbqsmzhc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtciyfbtns.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtxldaoldo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gttjiivrmz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtixqczkna.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gtmvzbtsor.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtecrgdumw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtcvxcwisw.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtkcfmsqje.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtfdzbrkat.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtshhvcdly.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gttgqpsnko.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gteftknjnk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtgyluuice.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtwkndxeui.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtyebkkthr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gtfkeyudmw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvjlytvy.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtozypqjhg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvneoonzv.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtllzcaltp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gthawcppmb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtbjxuiodc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtpswdhmkz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtgvldfffs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtjfcvnmhi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gteroswjoh.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gtcztoozty.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtbkiasspf.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtxrwslsav.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtgndkzrhp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtukxzqybo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtnkaqaurf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcpzrkbtb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtklqferbl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtfideuuly.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtspjofilh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtfdbmsflb.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtddgaakcc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gthoyytawa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtsmyhqwyj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtcsaklviy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtdrpkmuyt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksejrsen.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gthrdpsijl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtaxkthumq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtbennsype.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtxkqbunns.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtjynwrent.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gthmaebnmp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtcacswbzv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtpmwsrmxd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtyuwylcry.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtbfsehzni.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtpvdrmxns.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gthcgqwljy.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gthsjqzcdz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gtdtdbgraj.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtrmffaqaf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdowwsltx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtubuaxljn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gttfhgwosn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtqqkwwfrp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtebhedeuj.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtzedugumt.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gtwrjtlilh.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtfjbkecye.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gthkpvqsbk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtlbxetdxr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtvammkpdd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtnirgnsyx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjberhvyn.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtjwdbmqpl.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtqaqgomdb.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtpxhypowv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtxzvadvwk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gteetlbrph.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtitvkubvr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtglmnokwl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gthtnbycpj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gtwuoabwzp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gtrjoyeljx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtddlkkviq.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtuwngsvwd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ivvv.top/Article/details/gtgkrdujpd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gtdcqowtnb.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtsbykwfip.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gthuklqmhb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtovyqbzik.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gttelqnwqx.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtqifzpifp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtmxltantl.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gtimqiwzuf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtqafyuklp.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtgieinasb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtytrxfkis.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtobqtmujv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtgplpovqw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gtzibhwqha.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkwblwwnh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gtivtxaqfy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtyydvgptz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtputhzguo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtcjgiftel.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzysuhzt.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrrepmmnz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gtwnrkzvip.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmkiwkhsy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdsuhnblj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtyckyvvnz.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gtfangvuye.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfxjijnzb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtgheqlhis.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gthdafzgjf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtyyeggaqo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtxcodusbm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtwtntfvyh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvausloxa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtoqolwlip.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtytaklxtc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtosfevpqy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtuwqropbr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtbbsgevma.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtimxqsgty.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtbiwrwcyl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gtuosfhovs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtublkyoxd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtfewtpwqi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzlqjtvsi.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalpaqhep.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtulfygjqq.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtrzfprdeh.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtxlfrbujp.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtzxcrhtmk.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gttamhslsm.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtuhdwcbtk.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcfonlgzz.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtozugaamp.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtdoqsqkcb.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtcarianyj.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gthfzlatzr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtrqiqbnpp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gttxqtigqt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtsmortbio.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtzwbealrw.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gttkdvkqog.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvborfsao.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtkbwnhgqa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtrlyfifch.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtzeleaqcq.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtqozjpyew.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtxhojaldq.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtsrotnkul.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtudcsxanc.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtzwxmdznq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtvzrbftpk.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtymnfzont.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtrqajpucb.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtcunzdvlk.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtfotofkhx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtoitndthr.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtsomaygyw.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtrcmkbxqa.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbvnaqwyn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtodzsakuj.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtfykyhhzy.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtjisedojl.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtkhpsikhy.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gtwscudqlj.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtkrwqckwj.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtafeyqryr.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gthibgrbly.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtlgpwjbsr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtiwtdfcge.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwwiaubuw.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtzuzmfjec.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtotbbpwid.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtqqvjujet.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtzznfzrzz.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrggshxes.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtpezhtpld.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtuzepuyog.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtitcwhpuh.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtppxsdjca.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtlltgfstq.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtsopesawj.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtgdzzsbte.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gtcbobuaml.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtocvxlgvu.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtwunirtro.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtbmfdvtfm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmevbqlm.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtbzeicjlm.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulwaqkic.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtdqbtrlxk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtroahuzek.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtxytyjglx.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gteswxkkqa.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtusokooud.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gturwinbiw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtmgbgfvst.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtvzgekzvd.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtwvefqobm.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gtbkcqusaw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtwhjggysq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtfmuvlxyu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gtcymjmnbo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtllpsmhvk.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxrmqcqok.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gthwmxjetb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtqxogwtem.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtdlolxruu.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtlairpvdm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtewxwocgk.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtohrdtnns.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtwuhsymsn.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtzxtsztwv.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtvpnrlllf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gtmribwxac.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtlszwcghu.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtdzywypos.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtcihlxroh.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gtyowqndsw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtmnuggvfw.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtoinayyzk.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtmftyolgi.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtfrwpteoa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtcmdotatr.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtdtwqkygc.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gtsdwcyzex.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gtclxubagd.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtimykktkf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtfsiptnmx.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtklsnhixz.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtuhfsknnw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtkykntwge.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtblfwmedt.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwkiuuac.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtxtyntruw.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gttffwcsga.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtgpgzaezo.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtbhvwlyjp.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gthqvenvwa.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtsjtokphi.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtyveukcen.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtplelytwp.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtyyicyxuc.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gteicbpxvt.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtbjkjddnv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtgwkqiagf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtcvxhmsdr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtubcltsfm.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtnrlbztoi.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtamcdxkzm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtivuuhycr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtjjcwlana.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtddfbvqua.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtwvksohtq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtgsktxmej.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtcedfuegs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtzoezrkda.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsojvikgt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtqxtaxapk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtwqwrfeqi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxvmpstw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtczpklvyk.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gttkgcutoe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtepvqsgxk.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcozuzoqb.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtjtwpwnkd.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtyvyfgzxe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtzwdqllmc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gtgqtkmkkg.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtrxbnylbm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtszedozxp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtibhjuwba.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtrrhgkgio.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtblqogmrr.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gthzmggxvt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtssvuarww.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gtutsenjxs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtowsucxbg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtweumzqwn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxixyjfel.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gttstsckil.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gtzvuyozrg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzvucsxbd.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtdsrtuvfm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gturfcpxjp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlysormxb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtqkunniop.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtjkstkrdo.html


<!-- 参考信息 -->