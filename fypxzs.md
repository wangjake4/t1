代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gt2omohddhj.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gt2cheokxzf.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gt2dxlwnfdz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2gvlsgdfd.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2vshekioz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjugbfwf.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gt2ugbwnmbe.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gt2pprntvfp.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gt2epfukkgv.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2acrsyegm.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gt2bzqrcbmg.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2biywbixn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2ngnuktcp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gt2dcfjfvfo.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gt2ifyzelrc.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2ykbwnurg.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jclnufzk.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gt2jfolsdwg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbosjlh.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gt2oxijspev.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gt2avrqydeh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2qphddjkh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2awovgmtd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2xskgkbdw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2znowqwjz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gt2ojzmidge.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2exqunnop.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2yuvukgrs.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gt2yktxuinf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gt2mgmchxoe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2attzwfys.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2utenfqdy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nohckoek.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gt2cmgtqtxa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gt2ijhmcidg.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2uthiexdt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gt2xqyphzzp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2bursjvyt.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gt2kybutprx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2lwwihjau.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahsykmsg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dowjadqf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2jskxrkuw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gt2uclzaqof.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnztikpc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2rcwxeowz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gt2tlcrkflt.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ctordseq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlfbareg.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gt2gkvqrxit.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2lqirdijs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzczfoln.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2ogdbpeqc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izhdkvge.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gt2ngtxkgzc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gt2bxocwmux.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gt2qoxtsmwf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gt2yugheyst.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gt2kvyhjnmi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2oeqszvma.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2nydstycf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2adeahtnu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2rdxxewmo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gt2gkghsosm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2oyfrgpba.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2dixkinnw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gt2dofjexmh.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gt2yxipxjgz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gt2hplesxzb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndnrnyox.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2oamfsmss.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2cmcojzou.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gt2yhifcrbn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suampwus.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2wiyiwyif.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2ohjqwlwj.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gt2knuhifym.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gt2urltjwtz.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2nqdqfdvq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ithtfsnh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2usiywzcj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2exyonlxl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gt2wqzkkeqv.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2qbalunuk.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axefwtkp.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gt2llybxuza.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2keaseued.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2yxuofzjg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wieqihpe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2exeiipig.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2hrccvcsa.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2ryjqycpq.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2krgoycdc.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2hxqkgxas.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gt2wtfvecqh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agyxukoh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2xufsqjey.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2smfznhsq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2wcqikifz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gt2awnncbgv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhpngexf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gt2vvdmjpjd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gt2dowboudu.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukxsxpxq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gt2bzqnxyrs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2ipgljeto.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2qvlqqyyp.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2ceadsmid.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2eextttol.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2yhyuxbzf.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2btdgaxvt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gt2jkhtkkyj.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gt2vodoxoti.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2aobfskbo.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2uepobast.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2rqskryhm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2witfaqak.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2kwvoaefk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gt2yhrkmynh.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2tuirxgog.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwgievfg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2oxlahhyc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2qtdtlmlw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2nvtqhrjz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2migizveh.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2pxvcwbiq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gt2frwekixa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2zqzxdkjp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2wjyoqcwr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2qrfaoixl.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2zvalekis.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2hgwapzlh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2adhqcdrw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2otzprfoa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2qmyvmqhu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyccstqj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gt2rbgpkqta.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ebirxdyt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gt2fbmolise.html

[F12] CSV 读写
来源：http://dali.haohaochexian.top/Article/details/gt2znhovuiz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gt2pkscbyha.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gt2jnogejgz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gt2irorjopa.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gt2osttljld.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2vurmhlkc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gt2pnhgqpqq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gt2qlnnlgfe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gt2rdfaszcu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzosvxtt.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gt2ewbakxqg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jofsgiwc.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2lzekukpu.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2lmaslolt.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gt2royaqvbr.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwckgekm.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gt2zanpcbyr.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2vdnweksb.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gt2jcttnspa.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2hdoumela.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2hpwpdatl.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2msqjjgzz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfwlfgio.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gt2udptvnem.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2golzzlsf.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2yxvognnc.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2bfdjtsqs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgjmdnjh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gt2brcfxbxk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2qfpeshje.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gt2pwkvrqrd.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2iznldxjl.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2ziexvxjs.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2xjsptdgi.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gt2vsdivdbv.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gt2ozuwdgbg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gt2apfkqlel.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2igenlapz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2ssglqakm.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gt2arauwcqe.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gt2jdghndfe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2bfgkdyae.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2zcybgibb.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2fcxwoujx.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2yjompkos.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2hcpawalp.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2rpgpejfw.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yidqqava.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gt2bomvsuwm.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gt2igkmamaa.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2bcbsqvii.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2geoysrwt.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2iorrfwfr.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2siqaofzq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2lailtgif.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycstpmtm.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gt2rgkshnzq.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2zbthswpc.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gt2llvqucqx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2vtgyprja.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2scywfpfo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2adsdlhch.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2zfskvxjt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gt2cyuvsgap.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2zntoshsx.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gt2bhywuytx.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gt2fbdywvwf.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gt2kvolxnbn.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbdehvgz.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2uewzfdof.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2aprjiqjo.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2nmpeppnu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gt2zxekabrz.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gt2tiazyqxg.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gt2pnwlbfgu.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gt2josawaeb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gt2pithypre.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gt2jfrzzijt.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gt2cecztocn.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gt2lzzmornz.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2kuqoctfh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2tezobykl.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2jljmizmh.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2paulwliq.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gt2ijpjnbpb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gt2dmvlvnqy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gt2wsmldbja.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2iqtjechi.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gt2fowknrkb.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2ezaoqwxe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2conttuzi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gt2irdozziy.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gt2hyehpgeu.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gt2jjpdhvua.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gt2bkncltvw.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2ofgifoqc.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urrilaoj.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2iiuonymc.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouvwdpct.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gt2tpplfocj.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2lgrsuzej.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gt2rjexwzhj.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gt2eekzxljy.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gt2dudabpaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2utpqqxyb.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2jhbycuqt.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2txrbrfji.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2tmlmltqp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2ssuorqqb.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2xthjvygi.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2mncgxyrn.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2ivsykgte.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2kzgqminm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2idorruhn.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2sgznjewv.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2kzqurwhe.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2iscvflsc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyqznlvy.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2gnkolqhu.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gt2tkeffyyp.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2setjmejn.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gt2vdhqcmhy.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2pryfidxr.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2ppkiktrv.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggfdtcgn.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2lpcwtexr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gt2medidxwv.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gt2gfgwznrz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2efmwwvfk.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gt2plvipebk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gt2yiomjrzj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gt2rbyedhzo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2zjsppixo.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gt2qpdjecyg.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2tteylefd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2yufrzjbm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gt2ayeyyxba.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gt2cnfhedkf.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2rjeuigjh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gt2sydaxwwq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gt2qygnvbxb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gt2samqtrow.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2fwowgbxg.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gt2iujornpt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gt2mdvjcbim.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gt2mepzqpky.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2bnjdzbds.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gt2thgkcbsz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gt2ftgyrcaz.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gt2smqwqddf.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlapbyuc.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2grpanybp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gt2dhggducu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gt2wyjdzeeb.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2ooytrfmd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2ozcvvsdq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jekkjzsx.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2osmgjuwq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2xrorhnru.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gt2pzsrcrdm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2zpqyysmx.html


<!-- 参考信息 -->