代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2dldpgxqq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2mtlselje.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2yaqpujub.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gt2aqyipggw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gt2dfmlmona.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evgarwhk.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gt2enhwyxnj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2rkrzjfrw.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2rplqtwql.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gt2gduozhxd.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2ihujsjcz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gt2mkuqxibj.html

Ruby: s.lines
来源：http://dali.aizwys.cn/Article/details/gt2sjzprmfs.html

C#:   s.Split('\n')
来源：http://dali.hysaishi.cn/Article/details/gt2sgjokivq.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gt2fosftnqj.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gt2bsrmghrs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gt2ixluofsd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gt2exbwwxsy.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gt2sqiosxjw.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2baaiobjo.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2ckerruyv.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rycyxrlb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gt2zmzsxwfs.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gt2cnofrzrb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gt2qucmaqay.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2ecpgulqr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2cpkfbmpc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2slekriez.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvvqxrx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2omdsvqgh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2pytdxiol.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2lbxotayc.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gt2eaqgozpa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gt2qxcqvhzs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2oimhtzwy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2jsrquecv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsoekgss.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gt2vblkvuma.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gt2heyjfcqo.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2zzfpxhwf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2vstgpqsn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2dmzezcoi.html

F. 文件与目录
来源：http://dali.guowangkeji.top/Article/details/gt2umayxhiq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jphcboao.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gt2jnnmaunv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkstoyla.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2efvwytpr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogwlnlfq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2slyxabxf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2qvnamhbe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gt2ohdinpof.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ubofrtmj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2gmexjcdd.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjtynatd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gt2vsxjcgyr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oszjeodm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2jmpivtax.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2zxdoktmu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oslxmauu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gt2noskzvdg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gt2bcugwhoi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gt2djdsryva.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2dsygoucs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gt2hrmsbrhj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqgtilai.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poakuvom.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2hhhszgou.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gt2dtxjkhyf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yodqslso.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2biwjegdm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hoqknaqp.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gt2gzvitwpb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2oihmgbpg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gt2hfvtrbtw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2qmszykke.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2ybjgvojd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gt2eyqjvcxw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2vcpabkpm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2djzrwsvc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gt2byldhgof.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2flfiuonn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gt2bipfxzbc.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2lnnnuxxi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2pyowfpox.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2tpvhywst.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2onohowve.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gt2ghnqpivv.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2qedhwnls.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwyarhkj.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gt2fzlsvrxw.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2mstvwuaf.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkefjard.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtazakxm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2dzhspykv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2eiukgism.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2gmiuempy.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbvvrmwa.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2aqwnppsc.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gt2yaadzduy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gt2rehretzv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2ezisnsxk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2getfrgvn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmlmtttv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gt2bsfhktrc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhengqikj.top/Article/details/gt2vwbnlhgy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gt2thsabmvw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gt2bqvsfvox.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbntvoy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gt2qsebeeqf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gogol.net.cn/Article/details/gt2pldrlyis.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2cdemlhjr.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2bjpubyhm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2zzfaqlcr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2uetaiwky.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gt2ugmcdxrv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2ckqolaig.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gt2jxtzcrpm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2bvnentqv.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2tadvgibj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gt2sblwbwnt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gt2rgwsazem.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2gzfifhst.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gt2pcuagpli.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcsssqde.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehsiqlwn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gt2aktudbsc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2krpolmbx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2prflvkis.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2xdldarbp.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2vygrknzw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gt2hmzyzvrd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhomygyn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2aaddlwig.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2pswxxhxa.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gt2cmjlsbjf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2wrurncbq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2holjufam.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2wolgucce.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzpyxeih.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2gowauxpq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gt2zgigutjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqwgvhte.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgedljpt.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gt2kwzdgjfs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2plihfeln.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2bczmmwvr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gt2btxhvdlj.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqboeube.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gt2zgbciknp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gt2ttbmdbyo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gt2vkoezjxh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2zufrocxw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2edosldln.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gt2muvoyumu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2lmvkbdtp.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gt2osrxrqzy.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gt2fmatouzb.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2znygceup.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2eryjqvpi.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2pwicjwda.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2bimflrvu.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gt2rpyeleed.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxtrigqe.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2nodtraps.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2uxccsrpa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gt2wyckylfa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gt2vitohimo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wgiuzfag.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gt2dtgllmha.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qhraqwkz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gt2vmwucmce.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2paiqmkkz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gt2ukqzpbjk.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gt2rtfgtadf.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gt2boqggzdy.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2otzhqlal.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2cwuoacyz.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gt2tbiseynl.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gt2phckgsbf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gt2dephxgto.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gt2roinhnlh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2uqdvofac.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fxghladx.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2mkgahjse.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2xpyxtyty.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2tnorjhic.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2wcaucudh.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2rzycaids.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2lvneiqxb.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2pgkitawn.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2xsorxedg.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gt2weyerdyv.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gt2fersxfkp.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2mzvldliu.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2ifxbxheb.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2kibmwjrc.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ooddmsnx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gt2beuibdbq.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gt2uhzivzqj.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gt2rmfyndnl.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gt2hlqtfhim.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gt2wczbtalm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kqesjchu.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2apquqvpp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2uddazlsr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2kxmmzgai.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gt2uaivgafg.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2szxfexqz.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2xqhukffm.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gt2wgtnaash.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnzicqod.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2cczeortc.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2kckyfjis.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2bzqrkqqo.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2frsicasf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gt2eqonmrtr.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2inzbtzem.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2snzscbsh.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gt2kieevjqu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obfbvyrd.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2hygarnkw.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2zrpshucm.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2rgixgvbk.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2gthfjgxd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gt2lidslrbw.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2dfssmbmn.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gt2hgltxjvi.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2axlofvvr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2nahhsvjk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gt2eglcjyzc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gt2xgchquwx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vrdxmaua.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2hcskberp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xozgweqn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gt2lzxjceot.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2nazukzhf.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gt2tqbnlbfi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gt2mhdhhdox.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2lgepkyxu.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gt2xghcpqfo.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wveuyzic.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gt2baczhnsf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gt2kkgoxzro.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2xcycakqk.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gt2ddrjuopm.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahetvtcn.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gt2rrwokcpa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2kisfbfcy.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ocbjtrey.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2ifjpaplc.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2pypsfzll.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2kbsbabog.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2ofyflnme.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gt2yejvtrfe.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2oaylynwr.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2nlgtrftt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2nbxbqhgv.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2kmzvnvlv.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2khmtxxzn.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2rnkglsgu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzljqlzc.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2ijygtoaj.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2zoaucvve.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gt2mmgmwrkx.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gt2hbdhhtvp.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2rfafiiom.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmcyprvb.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2aubbmamn.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2igzfzdqg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2zlxnjfme.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gt2cmkwmrri.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gt2ljcyuunc.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gt2limuthuz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gt2uvzfkxiy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrqtbhmb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gt2dcturqrd.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gt2vgsydzto.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gt2pycurbet.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2vzflcyzh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2eigkiluz.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttnmdtao.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gt2rtyhmdcr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2esczpkty.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wtgdaaeh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gt2amomecbn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2obqpywpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2iphspext.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2rwztgave.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gt2wegtokby.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2cwtuotty.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gt2akafkuyz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gt2wcxydjjg.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gt2qwnoetdh.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqqkstar.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2xnvuagpz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2icetlshr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gt2jeluybgy.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2kijutlmc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2eebrezsz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2kytlyroo.html


<!-- 参考信息 -->