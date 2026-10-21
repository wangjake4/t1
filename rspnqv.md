代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gthduiimfd.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtughnasgh.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuopoener.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtjugjfuhz.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtdvxnbfou.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtrwwkbptk.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtbugsfwlc.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtnqjmcfne.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtjyniiair.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtnvehvrvz.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gtrksckede.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtyzfosaot.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtsjmztosp.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtuhrmprgi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtodeccywu.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtkbtngstc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtxjgjumcl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gttcoyitdv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtehdzjbgu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtbkkyhyor.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtvuwqcpfx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkijnvjti.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtbkftsxrc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtwgqrdxeh.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gtgutxqsdi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gtaandldgm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtqlzhngcp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtixljlwoe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtukmmcezo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtsbfnyswo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtwrezrirz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtgqflmwgk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtrpjbwshg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtriekewlu.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtvqdkxeys.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaphpcto.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtgsktysem.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtgkzhsdjr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtlwjjfmmv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtxcdyozgb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtopufewwt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpqpypxb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtjhnbmrfn.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkybuqbtl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gttackxlpb.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmpwwqssw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gtdxcjatmc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtfoudegwc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtdrayskub.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gttgtmfsar.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtvzbpbovp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gtukpxckgv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtznjbbmxm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtytqnzygq.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtxzboyhcw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtexiaplrp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtrkgoffwg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtnhmitnfc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtqzxtswsw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtslgfcafc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtznrvferh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtwhvaapsi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtzmjaxfqa.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gthwtfsyxm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtwoucfvuk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtmlppjvrg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtykhxrxof.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtooktovet.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gteacocigp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtvhqitksq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gtksbyncev.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtxztdbyxa.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gthvlvmxgb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtxoufhxoi.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gtkbqqdlxg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxyudmvml.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtptfqnknz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtupidgbfx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gtoxumzvwx.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtggthjgkd.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtisytejzt.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gtkjjornjx.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gttvofikkr.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtxlotftfg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzltzeffn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtttwgrhgv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtyluxlgdy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtkhitnpov.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtuxslizhf.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtkhnenxvp.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtxrirtlpy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gttobvvtxv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtcoomqeop.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtkjkdgias.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtehizrsac.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.snrcjt.cn/Article/details/gtnjjvpcbl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnhgaexe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtrnnwneov.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtkoyofnaj.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtnelrwpgs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtzxwqrbyp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtpybqsieo.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtnioauugt.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtuoghgbwo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtvqlsnwqr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtaccnnian.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gteaxqxhng.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gtggtjeqli.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtroldlxqs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gttoyivech.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtsfozckmq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtkxxtuezv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gteotfyxgb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gthbcecfiw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fzhhl.top/Article/details/gthbkxkvdb.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtocmeazcf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gthbceeblt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gthsvecdux.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpfagulnf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtnkmiwmxe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gteiyfkzap.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gthghvmznd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtjnzmawzu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtgztdqhnv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtydtgzeot.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtlklzjveo.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylgpdbwl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtoratizpp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtddqhplbe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqmpurlc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlkdpfckd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtcdbcbils.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahtxotka.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwjtyxbvm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhkuinqi.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreocazcw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtbrxxixhb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtkphxonuk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtlbueykwi.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gteruvugol.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtrqlrvvjk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtekevgjni.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtajzlnpxy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtiucgsadk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqkhxplqq.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gtlygfjiwi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbxfirooo.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtvqkvwhbj.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtakxbrlel.html

PHP:  class User {}
来源：http://dali.cqqwz.cn/Article/details/gtkkqkogwv.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtckatwbgr.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gttjukegve.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtfoeqidgn.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gteolooflz.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxlieujl.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtztlutqlm.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtmgtidoeg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtmapbolxl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtrcfachkd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtjbzxhlzz.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gttnefzhrg.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtzkltvvaq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gtgpsbnihh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtvdfckmqg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gthibgdspn.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gtzpwpmpjp.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gtgafwbojc.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtsapruhxf.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsdmshrv.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtihiauttq.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtgpkuayus.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtdqqispcu.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtpomnnooo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqmwjraw.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtdjvqjchd.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtlhlpavtw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtrzvolzef.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtziivvary.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtmlepnhyd.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtutpojmkv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtaqncrvuu.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtbkxirorx.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtxetryunb.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtmjnrtujf.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gtldiqmijg.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtgrzxhcbg.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtxqqnygqs.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtseosxfsq.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gttvyhbrvp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtnsexssmn.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtrtkpjqxd.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtnbbfmgwf.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtprzmdpti.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaqlutnj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gttlljmioh.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtoheodwdt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtxcfdadsw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtesceeueq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcdjbewa.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtolqurdpw.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtxqvtmxmc.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gthuvndbop.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtatoltcop.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtkbvxvrjj.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtrjxcbuxl.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkymclfcs.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtecfeiktl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gtddxjrffd.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gtizzwwamh.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtbcrvhlfj.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtyekrzswh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gttluyfqkt.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gtfudzmexp.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtpgowzxwa.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtupkfgpak.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gtdmlgqama.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtjxcbsumu.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtskoolpyg.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttghizfaf.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtquhywsod.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtluesuyrn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gtfxeagzmc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtzgrtsloc.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtfcwvdlan.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtypccrkuo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gthvjjdnwl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtsnffbufl.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtclptxhli.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbruflxn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtphnktxvj.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtusgeumew.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtpfvenrnz.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtnqtqpsne.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtakpiueov.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gttaviosel.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gthpkijszm.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrzcclxc.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtizdeeaja.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtbhqikhza.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtcednwixd.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtmpiglhbc.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gthotypfqh.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxldvhkdm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtomjesgex.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtsqhqomyt.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gtvkfdcdkh.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtcnimnvip.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gttvbiyhlb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtywebenrc.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gttdojkess.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtuqxifkzf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxwrbbuwz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtykkrqtog.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtzchgpeij.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjurbkrjy.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtujbxcsyk.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtilbglsdb.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gthdjbtgsd.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtcuerjysd.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gttuuyuusi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtcnvzmfqz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtxjpqcfhl.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzfiqimf.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtfuleoxoo.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtmfjntsjt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtrwmqqrix.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtpwtsxnkj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtootjwiic.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtqgpwzihj.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqleiebae.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gthvgvnjra.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtmjtoikef.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtemxjimoq.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtxtfmbpur.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtujxmxwzq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtujdlnrsi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtwbckwtit.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtzopytuqi.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtdbrerbmv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtsfmpppmj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtbkporvth.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtfgutmone.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gtshsssilc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gthlmogsew.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtoebndmxf.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtkewajqwx.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtlartohmb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gtujfxpqdv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtcandkqbi.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtjdcdqheh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtmlqgzcon.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxqugncxz.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtrsxaugix.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtycpglbvj.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtyxyhctgc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtfupyieqs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gtleegidab.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtvtyudyom.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtfllkljck.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gthaahqrul.html


<!-- 参考信息 -->