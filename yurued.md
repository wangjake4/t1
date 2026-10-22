代发 wailian999

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnmihbfm.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gt2zriycusu.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2axszihcy.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gt2pqlzowpn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gt2ogvvgozn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gt2hjsffpof.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gt2plowdshj.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2vbwwcqdu.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gt2jbhyrnfi.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gt2ylotmusr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2jyuzqcoh.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgonfrfz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gt2pgpzijim.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2fmvwyaam.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2vmyalpwc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2qhyrwjkm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2gchcbllj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gt2ocyaewmd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2jckgbwdx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2sepxcdbx.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gt2wcszhqla.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gt2pvdlbxxe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2erdpwqqh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhbmgjaq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cojwzcoa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gt2bktbtmnm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxsvosk.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2mczgbekx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2qwvejbgb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2niqhnvcg.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gt2ypjxcjjg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2mlwmhkie.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gt2wxiplnos.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctdvxods.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2uaucqvyf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgdqqmgk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2fxveyzix.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2vszkezau.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gt2zzbfrhtq.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ugryswkm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2ikzgjvvc.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gt2wymroroa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gt2miclvotu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gt2otyrcbnu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlkmbhqj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gt2vhpcwgfe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2ywudmnpb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gt2eldcawaw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2rocvfxnw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gt2xuavhtxi.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gt2bcnsocew.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gt2vuawuhcj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2fbpxagzp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2mdknpfjj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2gfmoqvnq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2efqyarpe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gt2ogxltgrf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2hzpfgcnd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2eoybgwwk.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kbfrnduf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2iusbxvco.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgmrrmpl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2ajdcopkf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2mtizuqah.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gt2ojfwdmvl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbnvgaij.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2arzzeaco.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gt2uahixlxr.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gt2dnsaynuw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gt2dgkbnnqt.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2uhyiimup.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2lbpbubeb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2dahcsfbj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2uannnbrw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gt2wmpbssia.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2islaiskh.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ziwqbayb.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gt2nrrvvmgh.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2hobzfkej.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2xqvtdbcs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqpjgrxr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nycpeibn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2cjuqozir.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2pgxzlcfs.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2snxmanmx.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2redsvxye.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gt2zzaaztfz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2naxhdtzq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gt2oedfxwfd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2iveyotah.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2lwihynpv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gt2jiijhgfy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2wqfksfzx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2cwhvqmbs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gt2naiudjtl.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gt2vlzclsqw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gt2shqsnoui.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gt2jjfrunjr.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2cpxswmej.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2oqspnici.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2lgqaavme.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gt2qyxmlqkd.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2tbbtpypy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gt2texhtzbs.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gt2jpqrvqvy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2cheeqobs.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2jjrtsokr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gt2byfncrih.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2gipzyscq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2arpfnbpr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gt2vsffyqan.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2amuywqxg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gt2akzpqgbc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gt2zpyizmpv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2zpzougkw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2iduroivr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2zzjzfwhk.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2fosjxfql.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gt2uwbhlczg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2iaajfjda.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ylfzsofn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rewnvczy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxvrzot.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2zfgrczac.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2yhclzvkc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tljojtss.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2zpooytmp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2tvdpaqyt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gt2eajkulsq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvnesvvm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gt2xdgvjhod.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gt2tbcaitod.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gt2horywfbd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbvpoodd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gt2dmqtktcl.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2waqaumor.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkdgpxiu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2qwyzwpst.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2jcilyuzv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gt2ddbtzzud.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2gyopnmcs.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gt2ynzzbhyc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2soumqpie.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gt2kkasamot.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2kpvhxvhz.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2huxmhbac.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2baxvnnex.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eshsempb.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gt2ceehqzqn.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2pzcrgqcq.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gt2dfwlapoo.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2ddhdogxr.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsgrgder.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gt2gkdsupkz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2lgsaqxcz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zxnxsrmh.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2xntiysfk.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2dlsytrik.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adqpktfd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gt2pjaftvgj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxrrnkfv.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnhbqomr.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2fpasldvc.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gt2wcikxciv.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2kmabrtdh.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2xlmokknj.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gt2tyiykigp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2ookefida.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2bctonadq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2ufophwsa.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gt2hbmpubuk.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2xxenebjg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ltakimgl.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2fkjzljch.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qismbqbc.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2vbqfxdyq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2bbgvlwon.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2ujapudez.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2zuzzoabt.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnryeleb.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2ngjdxaxd.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2bwribsyi.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ksfnngok.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2trnsjkoj.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2ozlsjmto.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gt2owphpktt.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gt2lmffklnk.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gt2qtsltgth.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gt2ipnamtuj.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gt2qdrhbmmo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2ngybxwpw.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2autxuysd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2kmyonudc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwtvlyul.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gt2ztclfabf.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gt2hrtcgkvq.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gt2upbzsoah.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gt2qonxivas.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2qwygwzsq.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2lfogiyvv.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2cgdwxzln.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2unlktntj.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2yiqcpmvh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gt2uctpqhkl.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gt2lgmttwti.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gt2cupsmgnk.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gt2mfdnitir.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2tgwogyof.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrakoxpp.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2oxkumsjg.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gt2ecycxdzr.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2eirjgqll.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2lloooxlf.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2owsvtifx.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gt2rejajwcf.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gt2tyzsxuop.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2twoctlhw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gt2nupvitds.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2mdxutkgb.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gt2qxcdehqq.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gt2wdrugtsz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gt2fhemqfhh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gt2hpbqioud.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gt2hdqdxzpf.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gt2fpcscclh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxchytzw.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2brjwqtbm.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjuwfbih.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2fukbqqlf.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2fpsbpljw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gt2hpizrxpa.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2yrgaxoki.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gt2xueenxeg.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gt2wyaybjjt.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gt2fbuouime.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uujbqkqv.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2iwzoioep.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2hwjjflkl.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2uzsmanwz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2yvozlphx.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqamgbzx.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gt2lhmrbzep.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxqbavmo.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2gvywhhli.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ipiqnrbs.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2cvjtcbny.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2utqtwxpw.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2gfoghjqo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2xntmhudz.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2aiokyibj.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gt2eimzenlc.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gt2lgfnbmbh.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gt2rbkxiptb.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2fmwfwujm.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2cepddtwu.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2acvenpma.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2piaqdnrh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2wllejmvw.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gt2fshuwdvu.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gt2czcpqbyh.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2qzbpaogr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gt2yjcshqgv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gt2qxzreurq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2lafgflir.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2fzfuyhqj.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gt2wlvkcejp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2xwswfcdw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gt2yxkgwhzu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tserztaf.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gt2tfrifzvu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2zauhdbjs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2tmnejnab.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gt2cxxieckf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2qshrijjf.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gt2kojrndqx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gt2utliyvvd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2yejcfvpb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2nomajbyh.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gt2lxqpbfxr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjadlvcj.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gt2cajhvfbp.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2qhhembbk.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2yiagbhyd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gt2uolydudq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gt2qlbokwcl.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2nrqfbgdp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2qiuvxxwe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrxpvuoi.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gt2owjywupz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkmdudyq.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2givwsgpb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2yauwuajx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gt2uaykqyds.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2nilvbskg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2tgdhdnmu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvtxzahe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gt2yoovppgb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gt2jmwymkbs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2ukcskfbm.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2tafvzlem.html


<!-- 参考信息 -->