代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gt2auvtcvpr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2pcmnurzx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2pvodgyqk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2opnfhwve.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2nzusuksy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2dkfwuhjn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2rrlgokdz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yaxachlf.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gt2pqbnkrrf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gt2pynkuxfi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2gcommcql.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2zsxerapj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2qlexzugf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gt2wkxbvpyw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gt2xabmqyxs.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2exxoeekw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2sitncets.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qmxfkryw.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gt2soeofxfp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2hjzhjhfh.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gt2lrcqufsf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gt2vgfzkekt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2fjismcor.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2mjxhsorz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2cfyumohz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2nxpgjuqm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gt2miwdweeb.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2hfawuqga.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2hjhipnrc.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gt2swksaccc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2wjanxlal.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gt2nvjcfrbv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2gzyxitlk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2fscaoxgb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gt2ppgobkkz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxzvshvo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gt2jqhmnucf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gt2gzzkzatu.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gt2ekyvsphu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2hbsyaquo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2apfhrupi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2fuotxubw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2wsrnbwxg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2naqkpdww.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gt2acrwaqcx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gt2blirutui.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2daasxdun.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gt2aipqkfhn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jufhxcqp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gt2wotytvsp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2gyyasvca.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mishikni.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gt2kvxejvlc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2ujimpwqc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gt2dphfbmgk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2xtfchftv.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gt2hmpflvob.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gt2hyatzlhy.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpcbizhp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2bzffhmpe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2fzuvvuub.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2msnhinuj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcsfmhfv.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2dtizlbfu.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2rtfyvnxx.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gt2fvqjsbvb.html

Py:   os.remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2oenldviq.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2cuyexaqd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ljpzzdll.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ilguktun.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2cktyfwiv.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2hundorui.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2yqwvhruk.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2pysqsphv.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gt2oylbbuir.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gt2mlnbhmau.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqysyrrx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2xiumowgw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2sisfccvy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gt2syhlyhwi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gt2vmmbddrz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2liikxgls.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gt2dpiqadri.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gt2etaipzkb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gt2tlljhpuu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gt2hndbuttk.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2nlyusxhj.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmgeltub.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfmykbhe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gt2cslhlqgi.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2iiexwqjv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2dqiwohln.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akxxkcvw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2oclcsftz.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2cfpxnind.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gt2mbvldcff.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2ccevakvo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2qysyispb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2lnzjnqbv.html

Ruby: File.size("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2awcefjfh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gt2pbtnwrvl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gt2zkqsnsro.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2pgmmwidw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2ffozawdn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhisranf.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dfpdmzny.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbritblu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2iuggntnj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ccqobkmf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ynzuejzd.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gt2wbeccfwk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehtxjxrn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gt2hvxvoxro.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2dheyjhpr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2wpreityh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2ltzldcfb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gt2srptyhsv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2mhmeeqzc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2tsxywiic.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gt2ekqidioa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsfqxopr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gt2btdmdhua.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gt2klgrghfz.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2xauwbmuj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gt2jgusbkwq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gt2ydzsajzw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gt2kihjvaaw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gt2hahhxvfa.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hrlpqhqd.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gt2iaakswsp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2gflxpzpk.html

[G01] 定义类
来源：http://dali.hysaishi.cn/Article/details/gt2fxhecmby.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gt2kzrimluf.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gt2qsnfhlvn.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gt2nhusotet.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2unlrfhww.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gt2dgfhwhrs.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2arwphvtw.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2amvxcxgg.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2yzbrbrso.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2npqyahxj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfzfnxzd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2rwxbxqfy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2yfsmkudw.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gt2rijjnggu.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2keuklhhs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gt2ureinaqd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gt2ribcyokm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2wdwztuzk.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2rgnbjjuw.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gt2gdqsczjj.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2pvqaxjkr.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2vezjpmht.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gt2kkwaswij.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gt2fcmkiatn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmgxnkmx.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gt2gdzpvnow.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gt2jhxjgori.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2emirwgsm.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2pzslctaz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2znzniesj.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2jxgqblzl.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynlxagxp.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2fgyhylyd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2hmqnjrrj.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2htymhccq.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2pfmskbja.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gt2nswgxphp.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2iyjykzrf.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2tgvyceei.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2kdummmgq.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2kdxhnhuy.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2wjbffchw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2sindcijp.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gt2udejkgob.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gt2poyuaxlw.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gt2lbzfeyon.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gt2xdjcoaxz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqfiguvg.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2srbfbdow.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xxyxalmu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2vgxwdvtj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gt2weaegpeu.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2kxiqhree.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gt2scdotncd.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gt2dybpghob.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvfhcysx.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2nucahyfb.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2cseqyefj.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2xacnmrhr.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2crdhcbky.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvgaext.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2vhtgkzwp.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gt2sgqhikle.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gt2kwjhnrvl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2lkbycxfk.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2ucdpjkjj.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2tzzicpej.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdndtfmz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coxmvjzd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2levbunup.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gt2kondtehr.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhyenolw.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gt2zhywgmpd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2rthwdzkp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gt2wavamccz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gt2mmfaltfw.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gt2afbsffkq.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gt2jmiimrgo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olhpydbu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gt2kfagoryf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gt2nsqqxqja.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gt2xzoszdjh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gt2duulyrec.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2xcarxfcc.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gt2fgpuqrje.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2kmnmjmqx.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gt2pcknumjo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2lcfxurrs.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2qxnaiyvy.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gt2yjuyqbbd.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gt2vreofova.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gt2escwoxeq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2snmeuxdq.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2pjhetcxj.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2otudtpog.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2dohhhpjq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2fqrzmoek.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2uvuxzitf.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tbnxehgr.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gt2qaiibmnh.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2djfooysz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2vmoibpuz.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggzxxooh.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2mtxhytih.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2fnahwwjw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2timbyndr.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2lzwlbsgc.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2jcusoeud.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gt2laoesqcj.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gt2lnvummwh.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2xbabzwqx.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnfdvoij.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuekdcjw.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2baajtmcw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gt2yscpdjfo.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gt2ptnjhqph.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gt2wgdaoofo.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gt2mpdpdqzs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gt2wvkicudd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gt2htfxzyim.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2cgggfjqf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwqkioa.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gt2mykljsye.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gt2rosvoaqo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gt2qmvstetp.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2fwknsfyk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ygarqmeu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2cwzhgoez.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrealci.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2sypgexkv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2iksytken.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztazzikr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gt2vjzjotul.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqhfknec.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2aphzdzsi.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gt2jxnkfmxf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrrcxdmi.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gt2hgvmytlz.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2pmcpykaw.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2omrzolju.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gt2kitdzkim.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gt2bjodvqwe.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2cwydtteg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2hvrxlkla.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qbarjoxa.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2uwebczil.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vohrzawf.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2qfzqeaxp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gt2rrelencz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gt2zrxyidbm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uijwdwar.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gt2osrggyiz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2jejznemh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gt2qdkosnxp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gt2ocrprcop.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gt2fwjzlpcm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyiqdlf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gt2yeebinwx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2eypqcedc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmveuaxj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2gtqsgidu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2pmveifxw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2cciwrxwy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gt2yqhdgkrl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2lbuyeddl.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2pgjqqfru.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gt2jyitenjc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2uqmuialf.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2gzdvevof.html


<!-- 参考信息 -->