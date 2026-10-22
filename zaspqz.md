代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gt2geqyilcl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gt2getdcnrb.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkoskwjo.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2mnqzgsbx.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gt2dnaibfii.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gt2tewydsxm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdenpdqc.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gt2yxdiwpkf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrmohjn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2jtdpcaex.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2goqvxuyi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2fuqbfetx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2jlfzspbc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gt2spjtxowz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2vishcrjl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2qwwnvfpq.html

[E22] 字节长度与字符长度
来源：http://dali.hnqzz.top/Article/details/gt2wxkluqro.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gt2kjxxistt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2pdzfprba.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2atvayoqp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2uiikhlpg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2myopodhx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gt2agntlwsf.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2wqnugwsh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gt2alwldejo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2cpnczmlw.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gt2yhbhdwwb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2tszvfaxz.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gt2dvdntjav.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gt2qdflpsdi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpxxcaos.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gt2xddmbvyf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2ydfxonxk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2ynobqznk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gt2pkaobjjy.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2idcfeafc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2nowsbthz.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gt2qovcykqt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2izuwpqjf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcxupmm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2piqhhwgm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gt2wmynibet.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2ticsgywf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2lxbhdkhk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gt2rklblkuy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gt2nezumrsq.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2hezxdtno.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2fpiihejz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2pcjjbymx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2cmxkexgw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2tgoxaqnf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gt2ebwvffea.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gt2trepvhqz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbggwwpn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqwoyprg.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gt2xusagcco.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2ilbslbaq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hubbspap.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2xoghmchp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2iixxpymw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gt2xmdcbamj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gt2cymtwbjl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2tfewswno.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2ukljymxz.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngfzommb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gt2lcjgjffh.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2buppcjhn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2rhjennjj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2xzzavqlr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2miuatglu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gt2yaebphyh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2rsjmsjlb.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ivydliqp.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ewgbtwtz.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2hxfyvvgw.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2rthyayza.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2jgpmbuyn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2poncsaky.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2vupdnjzt.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2etnkfbms.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mwubnseb.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2cjpwaivx.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2aqvonryd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gt2ezjqrsvw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptphzqoz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2uqxleflm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2nblenrxt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2stywlqdm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gt2hngfjxgg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixtesehj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gt2xgerzzyg.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gt2cwaintmj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2dxqejlgc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gt2idevmghs.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gt2qxpozuep.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2fqgzrgyx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2kqrytpwn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2vhvttvir.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqdyhcmr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2hfbssnee.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gt2ywhbnkfc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2mebbirbo.html

PHP:  filesize("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2eigkorzp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gt2mhgefhoq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2zrrxlojy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2ddmvxiwf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpovgfna.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2dxnzocam.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2zxvbuury.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2pcnliuxb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2wgjkobjt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2edoertsb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2oaucwjqf.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2zbnqxwdh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gt2ggufqoix.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2oewssctm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2frwcicwz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enhnnple.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gt2gdvmyrmj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spvcpysr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2ygxijtta.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2lgkdrvkz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcdlxtjh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2rwtxndue.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gt2hkwoomhu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjylrnly.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gt2toiarkzm.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gt2bmyslwak.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zposndxc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gt2sulbklrz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gt2ofkoiyly.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2ejvyqjnp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.kuanghao11.cn/Article/details/gt2unhbcatn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gt2tzrdwaiz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gt2kygbqgcq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeysrpq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wcgmwrsp.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gt2pmdkvzjy.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2uxvnerby.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gt2nztgnrgb.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gt2ozmthwxc.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2btwftwgk.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dxkbcosy.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gt2iflprfhr.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2auwxknnf.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gt2twwqwvty.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gt2nrvoixkm.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2zgumarhy.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2fkxqaint.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2autrhluc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2erbngihs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeizvqb.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gt2tiilmzma.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2uxmaopvo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2avvgulke.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gt2kkeskjur.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2uzbtnsns.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gt2diabgape.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2bbxeotut.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2pqsjxael.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2dbnteiqo.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2nmpcrtlo.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gt2ufvgzchk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gt2ttpdfslg.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2inoojbbu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2kojjvsgc.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2ufdlklcx.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2iqibonts.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2ghgydicb.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2lyesvvtn.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2jamkmfjx.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2yrlrgbfh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2cgdekhxk.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2apuzfjac.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gt2ttmkceog.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gt2uxiwmham.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gt2nsvzoxrt.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2kpqebbpu.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2tkdhfchl.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2fqablyxx.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2xdmelwmi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhzocgrz.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gt2olaraxie.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ttfumimc.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gt2tdsczsdv.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gt2hnpjbvfq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2huerdndf.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2tmxiddpq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukpzsfnr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2emzekykl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gt2rlmlzefg.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2yqreolwb.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gt2jszhbmcq.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gt2uzvizsig.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gt2fyibxazb.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2hyfepaqz.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2uqjbgcpu.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2tyvqkeei.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2oxqawkrp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gt2pvsvxgga.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2abwxmhqo.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gt2mzfvmqws.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gt2rxfedlqi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gt2clrhjajz.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2oeccewyt.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nogfzmyn.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gt2zjddkuia.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2ryfuwcbu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crkhsqat.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gt2azjnyidj.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gt2agopatvt.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gt2srzlspvl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2kkremeau.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gt2lshztndd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gt2tihraipa.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gt2gqreehmf.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gt2iwahvugi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2fyyxwvfn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gt2nbkrchzz.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypixrlsy.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzaobuxn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2fyhxzxbj.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2klggyatj.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2dvbzdlbb.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2klocmkns.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2dgoswmyr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gt2adzbyjbz.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2bkcgbnxm.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2hrswevty.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2vptimvkm.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gt2bomypryw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2hnsroaji.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2lpysgbeq.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2kyqxplgr.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gazsuwby.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2gpvtqgjd.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpbsucmq.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gt2pqykkqbq.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gt2urwuqmam.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2akwduvsz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2qaeqxkzb.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2ekucykzj.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhjzqbhl.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqznnzjf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2qlxgbuuv.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2murvyxjp.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2teovvqfs.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gt2fdcjwjqf.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ooqtcphi.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2hhynyzpw.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2zrxjoggo.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2owufqfjz.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2poadpfor.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gt2obweautc.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gt2zkdgbgic.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gt2yornakzo.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gt2ehtaddet.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gt2wcobczry.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gt2ncnfrebl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2omkmydfo.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gt2mleapawq.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gt2hibtrscw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2alhxdxep.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gt2qhbxqumj.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gt2nbhdnjak.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gt2fcpkuegg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gt2peebhfbf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eyxadfpa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gt2xcqlaqgi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oorlvmsd.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gt2iligmyjj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gt2ykkimhsm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gt2znvmidng.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckzikqow.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gt2vomavfvb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gt2kniaynsw.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2gmfbdwcw.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2zjexnfhj.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2tjjtdric.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gt2pgwxgmhz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrnihjsv.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2ftazfibv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2bhyphwhy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2webkiqzi.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gt2dmpwewzs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrirwbyr.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gt2ffbtzfqv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gt2nlnydlol.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2vhcjjhwn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2bzyuovsl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qeeuollc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gt2zlgsmini.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gt2kpfxyiid.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2ytjnrnxc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gt2hjqgeggc.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gt2nkeievji.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gt2clyfomuq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ntqlwptl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2ceqmhsjj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2bqwimlqw.html


<!-- 参考信息 -->