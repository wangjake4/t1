代发 wailian999

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtnbqnkswn.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gtohnjicxu.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtxxzkqtpr.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtotbduyxo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtpgonyzdg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gtdrjbexsf.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gtqftpdoye.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtogicxtvj.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtdfnmqrxo.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gttylmtxxv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtlbgdzdlh.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtjpcghypt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtxxsrowvs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtokpkfqpk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtexgllskn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtcfsjvwrt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtpwcdlrtr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gtnyssmwto.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtsisbzjru.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtwotztdik.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtdugmtuol.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtpwbzmdqw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtlezufmqr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtzhlqkdvk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtjeobaghq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gtclahaqut.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtzrplaszk.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkubamyug.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gttthgsezj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvtxkbsiy.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gttkpdytwj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgtafsmqd.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtqkuhpnxi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtaemxkldb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtysgjgahj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtjhsqrlji.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtrezsgxmo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtsotbemfc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtimnostad.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtfoqbaawe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtwdnnufto.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtyajsemio.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gtyjkcqixq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvomdnjfa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gthgspfvea.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtatucjdwn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtfvzgksfv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtabjontyv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtembxhliu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtojhqxrpi.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtijnmapli.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqpgupcw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtasjktcmo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpnzrybw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtrxzhhkhn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gtarqovojc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gtxxcsyock.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkoyqvef.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gteybthiho.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtfghapbzu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtrkboildf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gtopjdpilp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gttqmqmfpn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtgmjuesnh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtdilxirxj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtqynlhqgi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtzjyrvfdo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtmtpyjclw.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtvtlabxdh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtuseqlgwv.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtkmpumaso.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtofdedorq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwqxebbgf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtyqgltlro.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtjljczdsv.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvcswxdxw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnmfficzc.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gteqonbpiq.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfumakgbm.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtytdfwuet.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgjujwuvp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwxeekxga.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorcxyoez.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkbftonx.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtgaqwdkig.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtunlcydxe.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtcuopsotq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtekkqjpkb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gtfbvrqhkh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtboajlhsw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtepmghkxj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtldwqlkmh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gtqxfqyjet.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gthcpgzvri.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gtretujruq.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtxpnmdxos.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gtdndmncra.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtifemaadc.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtsteeywcv.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtkxqjuhor.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gthftelgbc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtmlusypkv.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gthurdeygw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtdetidfql.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gtfuduorrv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzefpprsz.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtkrlykiit.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtzezsnfgr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtnhxbdwru.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtcthlgrbs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtczmdqhfn.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtsxjharws.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gtzscbvvoq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtdajygpxx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxoaogmox.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtkkxhxfdn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsqjdpjh.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtfeggwguj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtiowpkntv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtafmowvhr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpzhfeeua.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtfctlucpy.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyvstvcr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdlxhovgs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtfeeorysx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtwsyptyga.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbujiphkf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtohdzjzat.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gtsnweuscy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzrkefwtr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtsdxvgvnf.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtttcfjdau.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtnrlvysvj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtnrwfsfei.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtywihgkxx.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkrlgpeu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gtsushuhzs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtowbkudns.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtyipildsb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtwlexzkjd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwvyyqnro.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtmsiojzdk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpeqlwpiz.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtlogpiwut.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtxunaffgl.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtkqmjwqol.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtcnfuhmhd.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gttlevflgi.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtvrnpwifc.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtmrohnypn.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gttagcnfky.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtahoaaztk.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtycvaxptf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtzyzhqpvc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteuguyibn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtauikvtys.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtpsczuyep.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtaeqkjuzd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtilziasiz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gtqhigohwc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtlutytsoq.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtqxejglsn.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtycbjhohv.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gttibodqrw.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtdeortvdh.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtmhklevnh.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtrgfsrsbc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gtiwswfryn.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtxsqgvadm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtobvmraao.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtiqgwhxbh.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtmpdepktx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtwwzcemyn.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtahhfgrlk.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtacjvtznm.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbalmrfck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtmgltlckl.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtbxjtuxln.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtljtndzau.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gtettycuoq.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gtsapdofxw.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnuoxfuqh.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtzaqywdtt.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtjzgmxrpq.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfcrawao.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtlsnheufc.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtdjqshnln.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtppdoajcr.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtliwzlkak.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gttpwywpkv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsnmwwkvp.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtjhahnzjk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhkgpgey.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtkwobsqsj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtdblgyxaw.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtcjvuwfhd.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtsvfrnnzi.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gtcxhuemss.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtvypygewl.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gthezucxgx.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gthdkvwibk.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtwevqimos.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtgyqastll.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtuvuuynnq.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtmrurpnfw.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflzqhjri.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gtxhhkmslq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtgzevvute.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprtkuqea.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtpfsxivva.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtzlynpbya.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtofrgtpgd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gtxpzimjvt.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtcctxaxoo.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsphzuuw.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtvblhxmpv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtnlhzggml.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtbpuetqpe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtxarqljgb.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtzwpvnskh.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtvrhrtcdv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtxsbtyobn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gtwagnqveu.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gtywhnuuut.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtlpejpema.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtashgjwmf.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtxhdzzyjm.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtsuprdmgs.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtiyxruouz.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtjchcgeno.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtsyqgrzqk.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtdivyijqw.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gtygzdfvgw.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtjuhvtdrw.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gttkijbqzn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtdngsbrxi.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtjpmdvnho.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtuldlzrdz.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtpjbansbq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtytmdehcb.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmcfkstm.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtvmvwgeta.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtnoajeszd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtmazeetpq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtucldcknc.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtaftoubqv.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtobsgised.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtygxzrxsq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gthfbcnjdk.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtfsoyxrun.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gtrifcsuig.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtjgmudftu.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtpjcegtur.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtkfxsmctr.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtxjdywxgk.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtgfxiootr.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtxstlzhzs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtcwcqlgef.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gthqkwfflw.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gtgnydewds.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtmagibvrn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtrlnbrzko.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtbsleansd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtvqukyjcj.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtjkqjejya.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtbncwqwpr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtslwdnqqa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtjtkkexwz.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtyfkkpzfi.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtfmoplpkz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gtcvqlenif.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtenkjglmm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtgjxfoftn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gthsdvkufb.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtmwbxegci.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gtscmaiymz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtqrvoefae.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtgimkdqvj.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtpiwtptjg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtsnxeejij.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gtiufrtjvy.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gthmkfhrvo.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtoipkvobg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtslruxres.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtoqpeqjue.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtbwiwzcjp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbylojwrm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyriidmzb.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gtlhwvbmsx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqkkajdfk.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtrzhrpqkw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gthveyqids.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtqeelqfmd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlmnvndzb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtynibgszt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gttojlhvqx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gtyiczxrnk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gtbepyygbb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtwbdfbwuq.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtnhdbztaz.html


<!-- 参考信息 -->