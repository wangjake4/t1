代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2qanszfon.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2tvppjstp.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gt2gmjrxyfj.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gt2bwtmbtxy.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gt2iviyiask.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gt2lkbracix.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gt2rtpcraua.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gt2fivbqmrn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gt2ynzrtrxw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gt2mczrlled.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gt2wlrvcxrj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2rnpjkxws.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmmfpgon.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gt2gqmseydp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gt2vfhnckcb.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gt2innbmfmx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gt2ggrlezdy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2wmnlmflw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2lteeqbab.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2gnsvroez.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgsmltgv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gt2czvcuqga.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2gtnxnewq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2dpaaayne.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2cerivphw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gt2gbjtfmbz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2bzepyhji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2modrqyln.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2lcpkhhgy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2ipadqfvo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rybnnjga.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2nwgoskxu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2brjwxjjz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2aezaygez.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gt2rbbzrfui.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uafekdbj.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqyhwmur.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gt2yohxscfn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2koyakotu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2dxqtlpgu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffexdnhf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2hpzkdiqc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gt2cgrmhejg.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2wuogwsyg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2sswbnqps.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2etmhhpjx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gt2guqpkwhv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gt2xxayxvka.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2vosjlevg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2dexrnxut.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2qvdtiwsx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gt2jeouwhjl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gt2cmncglmw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gt2ypsesnvg.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gt2xeczsivi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gt2clvfosfk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2yqkzylhr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2kasdniqf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2ulxepfbi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gt2hlbjukqn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gt2lruxbtof.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gt2pbmnjowd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2apwkyexv.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2imfgbyis.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujrhrpeh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gt2feuptosn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2vtxoxfzl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2ynrmvbvk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gt2vswzicnk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2vtyhskua.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gt2rtrjzsvi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gt2lrgsonlr.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gt2nlgbksnd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gt2ykkthinj.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2emnpcadm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2sjqyiqbp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2cxjdabbb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvferhcd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2hjbnxmvb.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ixglemts.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2talkmngb.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gt2xjmenzhl.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2yznsoflz.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2vruoqvfp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2kukpqcpx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2zavebbjk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2btcffoop.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asfajqtu.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2vzgmpqob.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2aefitxpm.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2lymdkhgn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gt2bjjfxamy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lstyekhs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2glfjuzey.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2nowxjrel.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gt2frncpyir.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gt2octcubni.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zuesfgvh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gt2rgnxjvag.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gt2jggkkwok.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gt2jyetwcgq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gt2khcmwdbn.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2amguooyr.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2vmrxufjx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2tqdwkzqh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gt2wuinulaw.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpxtswcj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gt2dalebgav.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gt2yjqnhora.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2mfgfdwzz.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2ohqxicgr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gt2hlfuatqk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2nrpfmsea.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2boelhhxj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gt2xebimbpc.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2anssyeoa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gt2qwlliccx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2rjbalpzv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2cxbncvza.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gt2kpokncki.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2lmrcpddx.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2pswwvwdy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gt2tyxboenn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2fxlqufpu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2casmrucc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2pewjsamk.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gt2upvspbqc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2jrnsnygm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2uxqtggly.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2bfaluimz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2pqwtdvht.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2dijniomt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gt2yhjqofeb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2looptckc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exxvbunv.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gt2qxljeccj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gt2ailmelbq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2wjaxxhlf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2cppzluid.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gt2atdvmtdq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gt2fyzturdo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gt2ihrcjrix.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elklsioj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gt2wjqdpmdw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2wfafoyst.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gt2htkesetw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2uvzfbjzy.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gt2syzspoxb.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gt2xqehyifi.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gt2qljjtong.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2kswuyqyh.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2hpxwnpkf.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqczadbr.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gt2oyydhsjx.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gt2pzyeyafh.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhdzqcti.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gt2hiupsqxd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gt2uxeyhyyo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2vusxsrqk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2dvajsunm.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gt2aqlgjmnr.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ixhvzryy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2xhlairyq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gt2rjyhuwam.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2kejyycqp.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2swmqgptw.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2gjkymlbz.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2aselguqe.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2dkhngljh.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gt2xarmckgk.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2kmbiwdgf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gt2hbyafeuv.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2mpjznecp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2rzusjlfe.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gt2vliiabxw.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gt2ubapgjag.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2wrwqcbli.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2tnpeuipb.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2guepcwzr.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2pkinfpta.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2bsbwfvlz.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2nrimzzfq.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2neahcyxg.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gt2pgcchrib.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2icygwhpg.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2zwbkqofe.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2cvwifwow.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2ybruahhw.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2tslybqed.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gt2zmemvbvp.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gt2xggzkkhw.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gt2nweouuuk.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gt2ctgoyopv.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gt2dvaxmzqo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2rvjvajae.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dezoxaee.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2irabyrqr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2ltxhpgyl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gt2wjkhukob.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qocrvzfr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtchuwjv.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gt2bnfpjhcs.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gt2oqzebwmx.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gt2biemkrwt.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2zzxandgb.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2ufaspsko.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2mwbxteft.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pobcymjs.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2wtooengy.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2luginfwc.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gt2ozmdxgfj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2envrolow.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2xmbthowx.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gt2gsdzspyk.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btyddtgj.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fibwhjwf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2ljvsmqcm.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gt2livpbgrz.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hazythrp.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gt2ypcoudab.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytcgxpji.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dyjudkcj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2fmvhuwfp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akxesnnh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mesmskvk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctbmyrxm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gt2tesjhbzy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2muungbnl.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gt2brwisucc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gt2xlozmuik.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2czaorzgq.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtjpxjjt.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2qtvbrgqv.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gt2fxrcuadk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2vpdrnvps.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2vnhtgvej.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gt2ogasarty.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsylzbtr.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gt2xrylvpgt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2dgrqlgng.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2tzoicudp.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2rtzbzsgt.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2wtvfealn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2jwozwbea.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gt2xindvbzv.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gt2apqslncl.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gt2ddnovgvw.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gt2vtkbugin.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2slfwdbke.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2pflbvmsn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2xpimxfgv.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2dxggxlty.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2xnehwrwd.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2yfecrlbc.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2stelmhdc.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2pumxcyri.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gt2pxuxzumm.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gt2nuqtajsc.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2hyejytrw.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2pflkpfif.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2kccethoz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gt2fcmqpqyh.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gt2ipdmnesa.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2xxrzuuzm.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gt2irhlkqhc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgcvwwit.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2sgqlwwhy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2ifdxjwta.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbspajmv.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qdvuduxx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2avmzskgs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gt2hwwmdjzl.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gt2mztgywty.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gt2wvbhufit.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2uieihjun.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gt2yygcjnru.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gt2vhzcongy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcuomhrh.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gt2puqrxbcq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gt2bfhibwyn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gt2gnzlenab.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2hwdrowrd.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gt2ghcwjivd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gt2yemolehp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2danowqcj.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2gvjstyqq.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2wtnwifsy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gt2kaauhzgf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2xaoaskny.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovmtzogx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gt2zaqyxcoh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2kqdfthat.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2kqlaznen.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2eiyydexs.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2emnxqdgp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2qdozsnok.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gt2uhirhibs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2fzjdnnai.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2nidmieib.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gt2vsscmian.html


<!-- 参考信息 -->