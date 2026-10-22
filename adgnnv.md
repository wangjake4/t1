代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2dmzckmht.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2qvtiiisl.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2hgssvbdz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhbjqtsb.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gt2lblwmcdz.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gt2lclnrvqc.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gt2ysiyqvht.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gt2nshihuqt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gt2yrycwahj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gt2gfqciooq.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gt2cbqvmhbq.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuysikdc.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gt2gsvbadar.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gt2owamftot.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2oitsgeca.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gt2uvamdens.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gt2tizzcrcr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2mzbfvmlb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2fpckwfef.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2daxpcvlf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2mfrmvyfw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gt2epkemsul.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2jwpsihkn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2hdvesyou.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gt2zatjbuzf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gt2truqzips.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2rxynnztc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2rjoywqys.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xeocbrye.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrirnqoj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gt2kwarytue.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2cmgcleqc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2bkewgsos.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ftsfvpbt.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2esgwtkuc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bzfiaogt.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gt2tynzaxpj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gt2jmnuzglt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2ziegbvsx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2runiivoj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2qcaqyxey.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2adcpfnjc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gt2gnpkgmnc.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2vqogbdmu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2ukhvzhgd.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2gnizdzhm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gt2mwiwjzni.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mxfbsmmt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2eiegpbsd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riutpijx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yninlitz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2devqycvv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gt2htklhuuk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gt2xpkraala.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gt2fmbuybhp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gt2uehhaqso.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2afumvneh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gt2fighgwyc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2tyjefznx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gt2syistmjv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2ynpktilr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ullbegcd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2efjyrolp.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2zgxrsimw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2jqlrvcsc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gt2pvcprcgk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2lgdgzros.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2aymoqbuk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gt2pgtqljub.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2mtchqbbk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gt2ffmtfnrv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gt2ptlpjudv.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gt2aplcxpqi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gt2wvohvykl.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2vctjrwkv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2dsduiklp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2icydpdlx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2wsoidqco.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gt2hlsqrfgi.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lagjwxxm.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2nxoyraaf.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gt2nqvpcoak.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2yrhrldsu.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2dpdreyxj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ahaomwid.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2menverfk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2uyltyzht.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2xqrgkhcg.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2yugftprd.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2kqmfesan.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gt2iuilcldo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2fkoncjgv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gt2hifyyrjg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmnrpoel.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2nckvaxwp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2gphaqatz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gt2zjaroacz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2dpqtolia.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gt2gtfpojal.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2kjuztkoa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2uauzxpyc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zslpqwze.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2tsxtidxw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2mqgemooj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2iniplsfd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uugvhyyn.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gt2gvhmorsh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gt2nacipanx.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gt2toqavibl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2emcygevj.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2taioelpj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2dmtbottt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2ljwqphza.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2zdehwvxj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gt2bcmkfbar.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2nntakaxe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gt2mwsspgfs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfsbukne.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2oyacptwq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2xdvusyod.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkbpwdbo.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dymwgdtg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gt2nqpkenfu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2tiitazlb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2aznzjgno.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2egbylqqr.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gt2vzwpchst.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ouiesyeg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctjwxqpu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2hcfrmpng.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2kwjzrpow.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2wjyidzoa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gt2gqkykczl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2evkbbqzo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gt2hrszcabl.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2wuprfglm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gt2ybjkisvj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubviafvu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2vfgjyxbo.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2waaaqkzk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gt2ewgswbws.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gt2cembaleh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gt2mpetlzyn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2uwizzxke.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqddfota.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gt2apegelsj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2popdvwgg.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gt2tryigydo.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gt2jywzawcz.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gt2eyqmwddh.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2wykhmrdz.html

TS:   class User { name: string = ""; }
来源：http://dali.zdqjudy.top/Article/details/gt2wcbayyzq.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkljwdwd.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gt2wtbsqrhv.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcwcqwpu.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2peookedy.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gt2hzzhrplp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gt2tjewjwou.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2mhupmzpg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2ukeriwcs.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkyqmxti.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2jhozkmyy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2ptgqqggp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gt2wgbnnwtq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2twnflqnu.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqejmjaw.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2lpzqvzbh.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2bxknvhho.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqrigxoo.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2syyxlhjm.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gt2ipppusye.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gt2zcqqbohi.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2klahckqy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2ktndbagt.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gt2wxzzorij.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2cwaeiyou.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qstlfkvx.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2idtqdhtm.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2txwajlfk.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2cbyqeutm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2jdmxkkpa.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gt2zmhxrdhb.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2owrvqvpg.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2sgxowbms.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gt2newzrpgg.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2mpcvumup.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2gifjuils.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2viuyjoek.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2zqtsggmz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldbdujxa.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gt2dcwxbote.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gt2pvburzsp.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2slsgghjs.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gt2vqypsipq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2esrvtorb.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2hbzbowtd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsjjzsqo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2oqjlbhvs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gt2dvduhyja.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2vvbfqqca.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gt2velopand.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jslsghcg.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gt2rigxpqyq.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gt2rtqrxnfd.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2bwfkyelr.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2euqzlcdq.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gt2ekpprjqd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gt2jfusuwdo.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gt2oxpjtzew.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gt2rcpqqgag.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gt2jktepnpk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2vfafhnrb.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2vdvbhglx.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gt2zuctsvbt.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gt2lgnpgyxg.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fctrhaup.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gt2zrslumeo.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gt2qfnjrkbq.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gt2bvvztzmt.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2yjrqxoir.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gt2djyuxyyu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cdnleiting.top/Article/details/gt2xopjzkyj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgroheaf.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gt2xjvfhbpu.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2khoxuame.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2soifuwit.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gt2nhjfuuvs.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvcmpojr.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gt2jieggpun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gt2hfaoicpd.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2nzjmeuyb.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gt2mkyskqjy.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2jkqczckm.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2muutsqar.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gt2dgvptnpk.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpuckdao.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2mzcsiuds.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gt2zbuinncw.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gt2gfbdeips.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frqyypdo.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2nbqcizvb.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wohjuuhd.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2bmzkclih.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2xedxsifi.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gt2jghnauwj.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gt2pbffmdxp.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2qqbooewp.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2tdpnrdlj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2qpnoxogr.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2jomncmfi.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2jdwejdok.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2cqmonpdt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2geefcufg.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2wlgctkam.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2qpnocigk.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gt2kudinott.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gt2cwgabuuy.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2jqfpfcbh.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2eklnpxit.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2lenrwgri.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypfefbyq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2gqrwruwj.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gt2nnpmsakl.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gt2vromztdf.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwxfutog.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckykvtyp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gt2xerjqtkj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gt2itelmana.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gt2dkaugmqe.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gt2floilcar.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2jnefrwzz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaxxadgu.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gt2vrjvnnww.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2bpyccuey.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gt2mwfizmoj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gt2cmiguuzr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjmznbgf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2hpazatps.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gt2zwhdxiaa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2whajxika.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gt2iyuelhyz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2fbifwxbs.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gt2utwzkivi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gt2emjexczw.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gt2vsmtelkz.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2rqvtouur.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ighelkvn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gt2gyyevglo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gt2elvhttid.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2vxsrqnrh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pneangxf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2dmqmeulr.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2lnchqdkr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2dllaniks.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gt2iyqwrpoq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2ejnycgjo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gt2rpahikfr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2vtzzljsp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2umihjwfq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gt2wikvolql.html


<!-- 参考信息 -->