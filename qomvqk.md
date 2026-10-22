代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlrxeizd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2qnilubzb.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gt2ghdbdimy.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2sclpqsoj.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gt2utazznth.html

Ruby: if s.empty?
来源：http://dali.tian-w.cn/Article/details/gt2hfhxlfpa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2tskuthfk.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gt2chdgyajt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2slrhdrog.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hewdwhpv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2hihbolev.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2jdzevfki.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2xztqcokk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2jppzdvrv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2rzmsdieh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2jvjatmhj.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gt2qzyxezeq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2abfgaojh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2scppsmzm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gt2zdxjdtbv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2aaejvqkp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2iuopzjhh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gt2tfeqgsxu.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2yxrrpdri.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2annfxnyf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2fldrwwpf.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gt2bebetsgb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2luajzcpd.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gt2ttruwqpr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gt2ozwcxatd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2cnjmgije.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gt2hjnawswu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2yfwmwbsq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2ikcxsxgp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfjcmnwc.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2jclyrsjb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2zhvotlpl.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gt2ohsuxcpa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gt2yfhgmwnh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qssscyoe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gt2rsaivegy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2auzvzdge.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gt2fezvqwbv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gt2cnuujpzp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2eqohwgfe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2olnxlykd.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvvviowe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gt2zpwfudie.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2fayuiqek.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2uvglewxp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2mmkegald.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2mrbpmttm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gt2qepxfqpm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gt2lpfcwose.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2recbyzmy.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2yqxvqnpx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpkcxaqp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gt2grlsddor.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gt2gptjkilq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2rpymvxpf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gt2rvkylkbs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2rptozhum.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2rcvonqbd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulwllkjo.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2aedyvulb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grcdpnsp.html

PHP:  file_exists("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkqyixim.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2qypuenct.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2uncdfcxa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2aseubies.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2mlgbxagr.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2hyvfzrxh.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2pohrxkjl.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gt2ihwdimvp.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2smdxuahf.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2ecaertem.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eenqvfwy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2gzbounsd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2yqhyfkbp.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2qjlivkpd.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2ysrmscar.html

C#:   File.Delete("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olpsgwao.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2zmeulpfi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2kqfhbbuj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gt2rokuzgvd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2bhqjkrud.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2yldtqcxd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2arqdnxub.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gt2ppxwlkvz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gt2noohqdtn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gt2ceapcrmj.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gt2paftbmqz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gt2ogkuyejs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gt2ztciklcx.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2xtgmnalz.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gt2ijcwspyg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2etldvftc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gt2sulgkbvs.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2gxjyxrml.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2vaxtxfxu.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gt2lphvkxas.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ultfcxga.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snhcmnlh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gt2bxmfobdk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2hvdobquv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2tddeymiv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gt2ejlldban.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2harsnbsg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gt2rxbgtifn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gt2xnvzuwqt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2cqoapusm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2mvrkxqfq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2pbfdvhjv.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2erzdcstg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gt2sfstlsgk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2zdoaybpn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2wcztwpyq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2thvbnaul.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gt2wglpzlfj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2fsbnqhwb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2xtgqvymj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2kvgrohjb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2vzqxzmfl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2sioragrg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2txxcqllv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lclyxkja.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gt2xtkeafwp.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gt2pbgoujqz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gt2nawugwwh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2woagjocr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gt2pgdpctze.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gt2jvadzpqs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gt2tcgwqrjk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gt2svkqiiyy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gt2kokedrfb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwbvvadd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2lpixzkcl.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gt2xgoyvdpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyqzunk.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gt2epsxkzqy.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gt2xzyivhoo.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gt2vaksjjlc.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ioofgeem.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rhvnuqfu.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gt2yqzwiwyt.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbcudvck.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gt2geumwoya.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gvbfxfoo.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2anafiwvb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gt2stqxagff.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daria6918.cn/Article/details/gt2mldqlxwk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukbzfcic.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dygehmfa.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2qoyypqtz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2grhqbutj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gt2arskhcmd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usboxvxo.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gt2sdyftpxf.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2cqcxdupv.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2tfktzbtp.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gt2hvsxqeff.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gt2kytrrtuj.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gt2natzspvp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2reajrorb.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2oijydsmx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gt2zdeuftvz.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2bxcfljpe.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2tstdyozt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2xvvgxcrd.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfpmfgfj.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2twuzvogy.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2zggfmpzp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2tvgbugim.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gt2lqcnwyix.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gt2sgkgxtqp.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gt2sbopwffn.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2tauzuzmo.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2wxmwseoe.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2ipedbzzd.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2siulmuzh.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2csqndkfu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gt2wmbxhlie.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gt2nyybpull.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvkdewoj.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2dmhzcwut.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gt2ajphshqt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2mexyjijf.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2zoodbsmr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2wnsxssxx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2bsmpjwto.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmpnmvcc.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gt2ghjgaqfi.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gt2ifzmaukg.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gt2dxpelrzp.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gt2tqdskboj.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gt2ztltlijv.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2sgmhkdtj.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2ogeejjlw.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2dtcsrfek.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gt2tghvcyrg.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gt2fvptdrfi.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2eudrlcir.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyvosqvu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isiasvip.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gt2ncaaifks.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2tlrrtmkx.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2vayjiick.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jfblgzch.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gt2mmmtosmp.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrnmipsh.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gt2ayhwwibb.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gt2kswfphbg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gt2hwurioxl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gt2ekbktbtw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gt2xlbfifjl.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nnnfxrwi.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gt2bicyycnx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gt2gvrvwbpm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gt2ekmewwvm.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2wqvabpmz.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2bwanazck.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2pjumlyvz.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkgtfuou.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gt2yynvpdwz.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2fxnnyrfw.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gt2qhzoexgf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gt2ndybmfzz.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2kajtwyrh.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gt2dhigshph.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gt2swxghfnn.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwgpscmm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2oofcydaa.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jaawafbg.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2vtqzsgqs.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2izehbysg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idlfuuoi.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gt2dbmuzfon.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hyawfuni.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2qzhumdbt.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2vmexccit.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2helbligm.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2xpszyhxu.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2abvvohfk.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2iqdotkra.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2itmmozzz.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2txkyuwlx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2dixmepkh.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2kortrofw.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gt2ucufuwzf.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2kfldkqlq.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2yphwrlfe.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2xjjqkgql.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2lczufhlj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gt2znspcuqz.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gt2sfsmmihz.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gt2zanwdmue.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gt2ujngfact.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gt2gbxzqydr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gt2nexfkbdf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gt2gitcitsa.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2bejdlyvq.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2cqjvuvqk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2iowxfrvo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gt2beejflhz.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gt2cehkrokj.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gt2dqpdkzdb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gt2apeapmbq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbypkxyd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gt2sqaenxws.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2fdnvzaty.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gt2fqfrwhzr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gt2lmxvvzva.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbplvcwm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2djaceemz.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gt2gugumrxh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gt2dvhglzlc.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gt2tpecvqzd.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2numokdwy.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2kiumilug.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyoufstz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gt2yxacmymw.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gt2dxstnkdi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2wajahnzv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2loaezpju.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lljyaefa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zvqxswqj.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2klamnvwh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfaxprzr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gt2suijfptn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vxadywbg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2fvgmkbvt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2yeybsheo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gt2zaypmloc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwljjhbb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gt2gtqweipn.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gt2vbkllsxw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gt2jzzlqnag.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2tdnosrji.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2aprdbqhv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2nnjzmppk.html


<!-- 参考信息 -->