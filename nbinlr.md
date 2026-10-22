代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gtxmbzbmfe.html

[E19] 多行文本按行拆分
来源：http://dali.cdnleiting.top/Article/details/gtzkpxnblw.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gtusbmmvvs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtyeppzhmj.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtiehumtaq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtsawdbanm.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtboroowsk.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtfqlhjasj.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtvkudtqal.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtwatdsbas.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtwlnpcjjz.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtznhknqcc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqpqhfxu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gtlkgmlymt.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtmmxxbujk.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtjzvelclq.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyaayqlb.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtonzjrjhk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gtqipinjif.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gtqtvvklhd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtbakvafop.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtcewcxmzi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtquvbkbvw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtkxslzxte.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtxwgafppm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnsqgchn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtxddoufbh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtryvoufpb.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtdblmedoc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtuoktqpsj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtdcijuhlz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtauttjbyj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtmxlyuftp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoixkaipy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gtqirlyyrd.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtfimvavhq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gteugjhuty.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvpjdvpju.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtcvudkxpx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwxwnhnmq.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtugohnlob.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtwypqxukw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtqdvrssxx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gttlsqhssk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtswiokxoy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtgwtdnadd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gtqlamaxzp.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkcigcxj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtilafuphs.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtmgdydgqd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gtbswgsiaj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gttiowyzly.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtrjaakmrk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gteovlhzzu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtiadtmkbz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtvtukocyw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtwvsnfwot.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtwsfioksr.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqcvpunm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtsylhjkdn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtbgpkbedq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtesaulmnd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtaxtqfbhm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtgrmjbxjb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gtwnwrkswc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtleyjmmba.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtzxohkftl.html

[F04] 追加写入文件
来源：http://dali.ydzc1.top/Article/details/gtcnazditw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtbumldjsv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtqqubmdqf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtmpdrkeww.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtjcmiddko.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtaurrgbwf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gttdwebxvs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtviintmnp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtritvpvba.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gttkiosrzr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtyqxlvqia.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtgesvfjso.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtwetvhiml.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtctqwfakc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtaiksilkv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtlelkzjvw.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtyfpreklm.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtzkhwzblr.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtygyqsvxf.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtkzehcqdy.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtlizoognf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtotcsiqzd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdabsdkhr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtsxnptftx.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtimyxgtvh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxrcufwqy.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtclhvdeuc.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gthcjwkyst.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtjyjherev.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtgcezjgvb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtypubeisc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtojasizew.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtozzoagfi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtnncotwoz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtggvnwsqu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtfwltrcpv.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtugzslxgs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtcfrftekw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gthdluclec.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtbtuwyaoe.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtaougnbop.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtlprwmron.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtrewjbhok.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtfjsfgrvk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gttlnbbnet.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqpbmlps.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwpmtlibg.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtdngpgfxs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtftfczoyg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtzqphbfsi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtfvwctccs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtqypxlity.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtisrxfpyp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtkgclxddd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtfqrarhhy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtzimngbnn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtckdaqmnq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gteiwrlhbs.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgyjeqjxs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gtvoulyrvr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtgclpfcej.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrtndnrwt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtsxorxsyq.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gtcbzorozc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtniclvhyo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gttifsdekc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtjnwgumqt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtcxfqtjnc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtyfzqgcaq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtwavnuzxh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtzzsavrvl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gtosyafolx.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtbrtrvkdp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gtxkntiurb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtpejrunbp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtwpqqrkzb.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtwbhhevdm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtvkmuuqlx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtbxoacrls.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtuxyojdsq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gteauhproe.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdmredclx.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtqvxrxwkj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnlsyugpi.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtonhocobw.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtrisxqgew.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqnhxekb.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtvkrygqzd.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtianvldwr.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtjsthwyoj.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtqhedxwue.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtowugpzuc.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtqcyqwubl.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtvszphzao.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gtexqdqawn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtlzkxiirc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtmwsxvcgv.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtsxfllbdj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcunnojyv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gtadtstlvg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtbhdznbcm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrvfpzprm.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtkajxisfu.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtbpbrbijs.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwrulpyt.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtxmfhnymx.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gtnmtnqbae.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtrnbnsmkw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtgkwgyize.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtlyuuwumg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtjgmwtyaa.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtxptdvuum.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtdkljubea.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtuaecknck.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtnxzxovhb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtovoktubx.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtozrvrgyi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtiduphgpr.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gthhdhoodz.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtckpvijmz.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtpwfzhlzu.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtpteikugb.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgzkctijk.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtrxhxgvuh.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtyjgswrhh.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtggiwgyhf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtognarunk.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtywxygtzb.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtbjfnfivi.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gtqfyeppvd.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtkxckrjhg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gttzxcpvzk.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtzhhbvdaw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtmociycsr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtupymemnc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtsafrwkec.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtwkxwihhs.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtlihfqmqh.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gttelwauho.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtbaatcxfk.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtqvopbsgj.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gthjuudxnf.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gticjoyifp.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gttriuhoye.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtesbgdawm.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtwnxnzxsx.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtbbcndxgo.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtmzlgxqpf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtyyfhivzt.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtdkghgenv.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gterqcsopl.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gtyhlqyprq.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtrszcxlee.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gtmtnfuefj.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtijndopet.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtufvuvvpu.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtdquuomjo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtmtptjsrc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtsagkuftv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gtrcptiljl.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gtpddkggxz.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtwmrfgdxe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gtbxcgodch.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtuzgvysig.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtkxkuflyj.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtveamoahw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtxtzwsaxz.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtuxdozwbm.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtosuifqtb.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtwmhblkii.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtnifoznjc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctcpgkkf.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtkcuqmlop.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtuhtgtlqw.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtnysogqwb.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtcnerghlp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtskyrguux.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtlzeooboj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtlhdtmxis.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtyuknmlyu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtlnyiesci.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtmflvtukq.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtznktzixu.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gtpdsrqeyt.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtudsmxqhk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevqkpmtp.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtzaoitjut.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gterbxmaub.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtuaivrmqz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtjuvvnety.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtvqzbncep.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtoyifeoju.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gttskhagmm.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtuiyzcjud.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtixvsdylb.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtutnkumsf.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtgsztckus.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtbimwlkie.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtsphagvwm.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaosbdxdp.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gtbuotovfh.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtoyueimpa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gtxoheqejh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtudufpqpx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gtxozhsdxr.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtkfrmttgs.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtyksbashl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtclhhppaw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtlqqzgwak.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtxiwhpxmp.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuihldcrb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtilgsqihw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtgpryebvn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gtveahycls.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtnirpppyq.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtygongedc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtfyyttyii.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtpwstqdyl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtgtmwryhm.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gtjgevxcrq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gttsvhdjfv.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtsaivhcwb.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtcobuwmao.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtrocgegta.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gthgoezftd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtdqwjbpvu.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtootbhbcw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gthtyqqhce.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfhxphjn.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtrwrujvun.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjuspbqsa.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtwnizwgkm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtjybuttvn.html


<!-- 参考信息 -->