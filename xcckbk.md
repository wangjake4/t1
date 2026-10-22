代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gt2tydziasr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gt2rpblyjlp.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gt2tzoszzum.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2upcevopl.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2foutjknm.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gt2ztpcyolb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2xagbpypp.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gt2yyrpgwkn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gt2ksewkage.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2lphjkmfi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2bwizdhtm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2opgopuee.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2mwjjmryj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvxmlrca.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2lwtroofz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2moxsmmci.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gt2hnavxqll.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ujspwxzn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2lqeocqdx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2juyzfazk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2fidvrmui.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihwoinfi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gt2qozladan.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2iytxvnda.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2yijifiau.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2mraijdcn.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gt2zajemdni.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zuvirtto.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gt2inqwtopw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gt2tnhsifuf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2umsbfqkh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gt2glykapes.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2goceitpx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2hnqakinx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gt2sivzphuj.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2navgqvas.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgwjqvbc.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlavdxlt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gt2aiqkwlyz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gt2uhprfxhr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2fhvoaoju.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zakxnwjj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2acheqlif.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gt2kmppjgwk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gt2hmrwgnvf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldkdxxgd.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gt2azkidylw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gt2pzazlyaf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsqkmrve.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2hurwnhwy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sejzoffq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gt2dkaaryqt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2vtxrgkgs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2ohbwpssw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibgysyjj.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gt2gbfgznvk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2ifdudchx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gt2geudcsug.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2pikpnenk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2ulujkipi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gt2xkazdkrt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2zjwntnni.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gt2uawgfgqw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2eeiesvyz.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2pycvrtin.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jntlkvdq.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2aziizpqz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2jlyrmozf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ocnnazjg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2cztvshom.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gt2sthkeuek.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2vbuhbkim.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2ngarsyiy.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gt2nkpvsvwq.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2luspfoez.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2reslyteh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2golkluag.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2cilitflg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2vusomquk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2aeqzecdk.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2winyegli.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2lrxjgrra.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gt2xgvsyhkp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2sylhfakp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gt2sxlhutcn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2cfmcvnix.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2kiymnowf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gt2wmlpkzep.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gt2oepfmnzx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2nqcavyjt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gt2sgvodikj.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gt2wjxptrid.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gt2eqbbgtno.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxhnvnwi.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gt2xiggzpvl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpdqtlpb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvtyxgak.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gt2cqdnjtnh.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2evxuhgua.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gt2zjivntaa.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gt2ugawzevd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxowbtpb.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2rhtjpshz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2owvvhnpi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2swanogwo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2flxczngq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gt2olfqupue.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2icjtpujf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2igcdwdqy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pczwmnwt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wueyjjab.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ccmpbvhu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbhxfwfq.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gt2fejbxnca.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gt2xtxzyjay.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2mzlzxium.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2mthtlxct.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxxgwlix.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gt2uugwvfza.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2yllcedtj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gt2pjqdmeig.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2kpxaobit.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2xqfikxyp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2chsnatgc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gt2bqbezshk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2nfpizpke.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gt2okopitvv.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2iontqsak.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gt2ugfvspyl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2parpctym.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gt2wlvjzkcu.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gt2upozbarc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gt2zgkhceso.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lumvxoqd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvaehsct.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2qaxpzhqi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghatnsfa.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gt2midvkbhc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ouhenaze.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gt2cmhlqldt.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gt2scbluetn.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gt2xcgavjuf.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2qgjdighg.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkfdjriu.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2tjlamczw.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gt2nxydduxe.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gt2wmbhbcjw.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abeawrpd.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gt2owsnpsyn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gt2gcrpguzs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gt2hrajmsnr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2wcazqyzl.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2bnzkrebk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2aimvgzhm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gt2kkmlgzvd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crugqavp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2abqkrgfy.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gt2boprmjnk.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2mwgnsndq.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gt2jngkabvw.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2anuzkxgr.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gt2rzheusqq.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gt2cnaeshjc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2fummycpk.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2exakhilu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gt2rflpleii.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gt2qzngfmcn.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gt2ojrggqjz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2tkokcqgy.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2fqpnpagc.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2uauqmefn.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjeumqpx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2ousndxnm.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2tplbzhfw.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2cttqiaza.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gt2syvsqjwo.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2rtoozfck.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2juxusayz.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2ikhungih.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2menyquwh.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2kzgovweq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gt2xzncfzws.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gt2dhjlaunw.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2qksmsoqb.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gt2ikjwbcrw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gt2qklpztcx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2bynflcml.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2wrwovafh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2jaauadwt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2hpgybowy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gt2rbghwigg.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2sopzjiaq.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gt2ytfnhgpw.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gt2mpbvizji.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khjsjkaa.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gt2lqcklqbu.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2glxbnmnf.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2akaxecrx.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gt2bnibqxlc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gt2gokfinpl.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gt2iiooaszw.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydrcptzg.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gt2hzylsomr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gt2ubouxkex.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2fkwyepme.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gt2vqqmzmwl.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gt2quofadof.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpthteyp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gt2vfbglmnz.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gt2everjbsb.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gt2gliywljq.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gt2tcaiebck.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2hpzvqsep.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gt2shngpbhb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gt2mfukznwd.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gt2qwstnqzw.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkjkjmva.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gt2heezvcta.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gt2omrnjhnc.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gt2mlwhcbqe.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gt2uxpfqjzb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gt2pvvvsfby.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2wymyvaqa.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gt2zwuxazsj.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2rxxvkfjm.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2apezqakb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gt2bckipbtj.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2nrrjeycf.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gt2oyqsyjzh.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gt2yqbntrkr.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2xlqogbso.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2nfhtulja.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2mbduiqkw.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gt2gxwekauh.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2tosaymxc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2ivrvltbg.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gt2bjieeqfg.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gt2ohmsktir.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gt2iyedamiu.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2jfbnpjph.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2aundijyk.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2odprjrzv.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2cnloxsmj.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gt2qbujxjvn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2vkfabbus.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gt2hfjjclmh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2uuhzjlqs.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gt2ngdqbrty.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pelaykhq.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2bcmkivps.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2ewokaqaa.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2nmlexrhx.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2sjuoqknz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gt2adfjiygx.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gt2ettzlvfa.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvkqmejh.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gt2bqlklddh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gt2xvghqvmz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gt2cvbfumbb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gt2ifloeexy.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gt2cnqecjmi.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gt2wagistie.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gt2ujtlqfii.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gt2tyjrcrbg.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gt2asdtaock.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwnsckzt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gt2kqmasyiq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gt2phqplgrr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gt2kxlxenpr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilkearwz.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbiurcbs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gt2inkqsuym.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gt2kqpmsqlq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2qcclvsrt.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gt2scnoahlt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gt2hcyicvqk.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gt2slzfjjul.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gt2vijbjbpd.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2oydedshi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gt2hjppfjhn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2jiuqzquh.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2jqwsukmj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2dxxsyktr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2grcdzrvz.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2uhhokxbm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkowxdls.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gt2jjposiwf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2epzmhozf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gt2qbxtduac.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2stewzjbi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2avvxqnkm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzyemmeq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gt2alftgkyp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdyhmzfp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gt2nurftwoi.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gt2cummxbky.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gt2dhgufjho.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2nroyjgda.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2kywbempj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2srqlrnxl.html


<!-- 参考信息 -->