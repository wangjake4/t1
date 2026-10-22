代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gt2fugtxdzr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gt2epfaswke.html

TS:   if (s === "") {}
来源：http://dali.xziqi.cn/Article/details/gt2tjdlonsm.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2kuibmwtf.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gt2vafhycat.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gt2jmrktgza.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gt2fnkshfua.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gt2seqpakex.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sepubfko.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2zzxbjhkl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2iwskfkwy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2rolyqucb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2rhwmkrsl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gt2snibxyds.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2ulzgazsn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2kgiibcbd.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gt2ylzjtioc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gt2usrarvnl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2frazqmzf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2xvvhhjya.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2ioxslcou.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gt2sjrzqogj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2jtaxbnxm.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xypqxoxj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2tpghurnj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmwjlmuv.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gt2tdijhnhy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2torishgo.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gt2myryahbs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gt2lrgluarx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2gfcfjqyv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gt2voiigqzc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmuusguf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2thchgufo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gt2riqbnuuf.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2zprzuavk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2onrkuhvj.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gt2uokdetpc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gt2ybzlbgfo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idcfebtg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gt2gpeocqdi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2swnbavhb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2oouagjbi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gt2kafkpnfz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gt2mufkoaah.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gt2waapzgkb.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gt2gjcdnguo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2xiivivap.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2fuupazas.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2ipnlwtdq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2wiqumesw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gt2vkgxwtim.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gt2ivkhzcln.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2ltkxdehn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2ylceucfq.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gt2vktryexp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2srtwgjui.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laegpnci.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2ykquxqbo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2rpswwdiw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gt2yjgiwlbz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2xmwgbhqm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gt2rvvepghj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gt2ufyumqev.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2kehoucnj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gt2imjwfwci.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2dftnlxmi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2gqmfmrko.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2panxuyto.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2pfvifjdm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brsrwukr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnnvwjoj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2yfaslazt.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gt2qpttgtit.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2kyzpuzku.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2kubdewev.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ltpzqluh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2occgxbcs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2pviwfyec.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2epbnkbup.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2mlryrjjc.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2tvudsjua.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lprfnzqh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2etzlvtjz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2pbkjfebt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gt2idxhhrcc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2khpqwdah.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gt2rdixmosq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gt2uhgbcayd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gt2dcyneopy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gt2atroeqfw.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gt2xrbtsrim.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gt2qlafqpzl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gt2aixvpgga.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2ygahzwyv.html

TS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2xjgbvhrv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2aasdqinl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2rxopqhsx.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gt2dwgprtpd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2dottbtdz.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gt2ejunfetz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2miapbtvr.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2crklcisj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2ugcrmpjp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhgflzpz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzkknynt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gt2icjdguue.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2pdjctjsc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkvkofws.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2asluizay.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2mljgkrue.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2jbfwtvwg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2anyupzso.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2opdnkugi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gt2sjpoonqz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2jakzqpau.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ihbhxdwi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2hzxgmxno.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gt2xnamkmhr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2yfkajeht.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gt2ninelvxg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2yrtjduwj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2bngbnogj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2svtjrcvw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gt2ittibqvj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mvjmqfnn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gt2opzefdoi.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gt2fprzyqdy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gt2fmyqzmqk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gt2ayymedmc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2oqmkegxg.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gt2axujbdnl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gt2kspvqubs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gt2wkoktvgo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gt2uzcblzvv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gt2bujzvkac.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2lkxwlpth.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gt2cajcnmfu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2amdyocxp.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gt2njpemyyy.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gt2ppxhiaqk.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2suaqppxw.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2vdfrqgwa.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rswpuxwj.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gt2shwuqvyc.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gt2whuqplnc.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gt2vpiqhczz.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2foxiuxcl.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gt2sltpycyv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftwdkzbd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gt2roeiloer.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2wrsqiqkv.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gt2owpjnikg.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2nflgtxzi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2rdiivact.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gt2zspfzlts.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2numgffab.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gt2uxamkzpd.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2gkgtbccm.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzewdtxd.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2ogyqkdut.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2azjngepc.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoekyvtk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gt2ffjabcbm.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2rbrlnlrq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2qducyvgy.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gt2psepofil.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2vzyvwrpt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmsitrte.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2aatlxjki.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2kndxznpb.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2orpzffof.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwwolwsd.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gt2dwzdxvhk.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2kwdgvpzv.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gt2etdhsmeg.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2ggkgeudz.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2ahngmrvf.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2topmrqnn.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2etuhcetk.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2ikqzovtx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yteflhuj.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gt2ogkbafew.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gt2ejwblxsa.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gt2ptwuluxv.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gt2yrrthimm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2npvlilbs.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyeomxzk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2kmrgaxew.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkimhdkr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gt2kgtngmgd.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gt2qlsapkml.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gt2ffokscoj.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxaulcpb.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2loawmjgv.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gt2fanexvcu.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2zlpworji.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pepzrwcl.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2gtwmyezj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2smcdbhqe.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gt2aqlnvmhh.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2jfamredr.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gt2rspxlceu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2izsbwtom.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gt2brajbbnf.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2hzzgbxsn.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gt2xsqdwmcl.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2mhrkkfvq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gt2mdojqhxl.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gt2oemmqudm.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gt2leqolxtr.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gt2xcywhbnj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcovmhjc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gt2phkzmuej.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gt2mnmpsfaf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gt2umpnbxog.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2goccdthc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gt2odcxmkrx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gt2ytzswkqa.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gt2puoxzxfu.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gt2yetaxkht.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kywcpsbx.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2ivfmoucz.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2gjjziofj.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2rwovdlzk.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gt2pptmfozm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2texjlxng.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2dyogmmxt.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2oliljldp.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gt2efexuljy.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gt2cbfrncgc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2laosgmox.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gpewbkqh.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2aezoblln.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2jikafzld.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2natatsfj.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqfulirs.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gt2vjrzlrkz.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gt2uhkoerdh.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukplyzrq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oonxyikc.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2pftvlwvl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2wdwewqws.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2jfkloxyc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2glmbxatu.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2swwmfsey.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2ahbjuxgf.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gt2rnafewfs.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gt2whqioxrh.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2fulhixzv.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2wvhwasbm.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2vgszljqo.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2iwgipjmy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gt2exfnshov.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gt2lbaulslc.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2vvuiypwf.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gt2ifzregyr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gt2cxlsrghj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2ptknfmta.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gt2kpftdlsd.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gt2ahwkdsdv.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gt2iqxqcrjh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gt2kuvybvui.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gt2dfwjpnxb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2aqdglnpa.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gt2vzuqvllq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2qphfwquu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2cqsxxlwb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gt2xmudulwn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2qcbwmmns.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gt2cawartao.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gt2rofiwckv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gt2lmfulenw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2wpbcubgw.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2cjtliloj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gt2pwxbgozl.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gt2dovlgfed.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2shpyolsp.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ingsladh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gt2qiotxibk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gt2efuhqoal.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gt2efzwdeuc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2mkwxyfch.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ezbxxhvm.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gt2ejrlmfwe.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2axvzienu.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gt2ttngcbcc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2bnsuzels.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gt2yhinnyxr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gt2qklhqfug.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqyxhhwu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gt2mrpxbdqd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gt2swmgdsuc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2udegjqrh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2useultsl.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gt2rpummmbj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gt2yfqohtot.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2bqemopjh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2cbdbneug.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynxtddrx.html


<!-- 参考信息 -->