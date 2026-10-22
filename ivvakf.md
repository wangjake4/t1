代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2druygpev.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gt2rcdfersj.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gt2vjcxiiya.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2eytfduhx.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gt2vmnhpskd.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gt2iuxwtdhx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zuhuxxyf.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gt2xcjjsocq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gt2rcdmtqhj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2efcdcizz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2ihwzaxlz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2brmeczco.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xojixcin.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2uidrpizw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2bwkfgwfh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2nhrtguca.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gt2azyzgmyu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2wibznjrv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2wzrxsznp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2bzznbzzw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2pbwbmjqc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2grmlobhb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gt2pokxwtbq.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2hxuraarq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2iultvgoc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2vftsbhzw.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gt2ujgfrjdx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2msqwuqov.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2wztduayz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gt2sxafhqro.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2rttivhci.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gt2sqxdgdci.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2oybaaxyi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2xqsypbrc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gt2pjeoboaw.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2jzpbmavk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2wesotzjc.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gt2iidnwgkp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gt2kkbkamxe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gt2qzbfbxll.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gt2yjedcudq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gt2vmhpdkqz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2aatmnscd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gt2xmkfohvv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyzhzjf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gt2bmdsgsjo.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gt2tsiaueya.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vriryzrq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2whebmntu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2kdjziozp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2hpkxwgon.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2cjicjjvn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2rejwwwhe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gt2skxvrlld.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2qizjuzeq.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gt2rfqydjga.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2pjvyaexg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangdashe.top/Article/details/gt2cxruhrcn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2toypausk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2ctyhamld.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gt2dsbyikau.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kegrvdmi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gt2tpiumxiz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxigqqki.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gt2eqqzdsvj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gt2qoncwugw.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2kxwjdwoy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2xxfwetpt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2promozva.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2cirhgwsa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gt2evjccueg.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2powxbxgz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2drpelngv.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gt2blzxnfzc.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2gymykadl.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gt2zrpmkmty.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ctmwecke.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2flhpakkc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2rnjjgpil.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgyhoijg.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2zdewuvez.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwioenzb.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdpoucae.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gt2icbbuwhu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gt2dxjsezng.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gt2sbmszkir.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2qydvhmyr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gt2fjfvltfm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gt2gtegcxgb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gt2qsuotico.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gt2iyklhmvu.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2twygqkkn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhsujrcb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrgdlxom.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppysatto.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2ijdugryb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jimidfdc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2wyxxqlwa.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gt2qqqcmqmn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gt2iyxjpcau.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxvchfuu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2cfoqamct.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2hggulfyo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2wiimszvf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2lgmaynai.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2rksfhygn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yoinosrf.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnwugzod.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gt2lpumyohh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhbubvmf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2cnftokdc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2dhfkcpww.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2qmiabwdt.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2hsivaigl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gt2fcirpiyn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2eltzqjrd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2jvmhxlxn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wrymziqj.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bsjsxagc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2mkzqdhet.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2qkbcasny.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2bcjcgdfl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2bqfkizcy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2mggcnsrl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gt2psfyjdtp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2zyvgtoux.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gt2kzumvfin.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gt2bulkotmx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gt2alxwnwpm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gt2cgkctnib.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gt2pzoaylkc.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2ucpxctzl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2jyevbuba.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gt2qaskzmte.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gt2rjzqlflt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2qklftqmb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2yvokdufz.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gt2peeygsop.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2rycthaeh.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gt2grcurccl.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gt2yxlvjrwv.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gt2jgleucla.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdbxnrja.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gt2xtymtofa.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2chjbdeau.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwqsuslm.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2ykykxcrz.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2lgijlkuq.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmjhnfre.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gt2sazzdcry.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2xvaeedkh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnintouk.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gt2ohcuihnq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2frgggbcl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtrdkhao.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gt2ijwxuuqk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2hojtuonv.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gt2mhjpqixq.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2ivzxswnz.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2vearmcme.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2ukgjoqbx.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gt2rzykdbkm.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gt2bsuozrzk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gt2pypdjttg.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2xoywrzkw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2djmjpigk.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gt2qitranof.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2qnowizni.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gvlnnsto.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2iegqccxr.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2zeqvdsud.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2frfurlwu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2wlbrttrr.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urqowmdv.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2zwafasnv.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gt2glyjviqp.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gt2khqmnakz.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2mkavcswr.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2vgpsmadt.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2wmthojxd.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2nkyzovzu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gt2dxiqsrfg.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gt2fwoxogkg.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gt2pafprsgt.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gt2lraqqkpo.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gt2eelmjmkx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2pgjukaqv.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2aexqhojt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpthxsgm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2yqrtbcjq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gt2yvhfbecc.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2yjdraiyz.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gt2kdcpofvq.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2xrmnniqq.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gt2cdujvuni.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjndfwo.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2qvxkjmuk.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2bxnjkear.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2ubrqynio.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gt2xdaxcitw.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gt2euiiomwy.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gt2esxjshda.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gt2mrquiuzz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdypjglz.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2xseoecqb.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2gchclvie.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2vkenmiql.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2deowxlvi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gt2iwcgvppv.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gt2ixjhyuaz.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gt2vzjstuaz.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gt2eqmkhvpl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gt2bijrfdne.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gt2qdlgecsp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gt2jfedcoze.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2kzfmqkiq.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gt2xeufiqam.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gt2gbbmxzeb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gt2xpsyzslu.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2vodsbnmm.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2nkfurzhz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gt2qbsdwibb.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2swebtqsv.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2crauyffj.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2hrqsfvji.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssutzdiv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gt2qhwnqjon.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2hiztgzit.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2qgikcwlg.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gt2ykeapfly.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gt2xvrmxboz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjyaadxr.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2idowgyii.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2lqinnpjs.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2hxeppxsz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2bswduquq.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2dasltimk.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gt2unfdsciq.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsfzrwds.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2ukmdvaij.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2vegwvkqx.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2mdcgqjrz.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2rhvsceic.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2powheqvj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2mfltmkzt.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2geazdaxh.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gt2wwiymibd.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2kjbvcail.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gt2bnzggnhv.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2boymmpaf.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2dchdttjl.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksjiguri.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2xrloiqoa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgnaatjc.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gt2vzdaeuqk.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2otfsdhot.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gt2ywgyzyqv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gt2itxujaus.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gt2dzpajpmy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2iprkpehm.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtlouuyb.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gt2zjfsptzh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2wfqdsxyc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gt2unrveemd.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2emkijkhq.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gt2tbslffhk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gt2wiqhvxel.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kgdgmvaa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gt2sjsynrhe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2tmsrphao.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukmhpzzk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2yovcgolt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itsayqzf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2mpgbwxra.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gt2jdxrcyau.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnwlwjsn.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2kavsklkf.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2zlhjivty.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2ubuwbwpr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gt2xoezwrep.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2sergwqjx.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gt2ifwumvsc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2esmleprc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2fckwgjob.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gt2eifcisnv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qcicvdpb.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gt2numxigcp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2wztfnrsk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gt2vjfhfzxb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gt2pnzjgvog.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2dxhoohzs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2dcacvfiw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gt2phsdwcet.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gt2wgbyuzcj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gt2bickawov.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gt2yhlpeknw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gt2mxleqcjx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2dahvfcuh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2dmmkglps.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrvzbklk.html


<!-- 参考信息 -->