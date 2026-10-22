代发 wailian999

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gt2awtbtcbu.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gt2jxvplrnd.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gt2vuorxpdw.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2cgnxlexz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpxcveuw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwsxzveq.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2ufzsubeh.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2rvnjbsss.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bckcjylp.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gt2drndrmbl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwrqldd.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gt2bpdcisof.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gt2nekyeijr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibjbpflj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2ycddnzxh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2crxljdee.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2jdnxkoce.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnyblxye.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2qtrjuwfv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2lsatyvos.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gt2mnrxakrg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gt2ekpcajnr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2tipyocfu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2glnmlriy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2ibahvcud.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2oibcgpdt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efrkgrjr.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euzdspkd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gndsabhl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vujusukg.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gt2pxjmpavg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2bkybmpsb.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gt2vkbtaayd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gt2bbynmggq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2xlisrspu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gt2kelxdaat.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljcrvtjw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnbgkmzh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gt2smanrvis.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2lrvapbat.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2ikwdsote.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gt2dpdomgzu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gt2kjocrhfx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2shpqofbo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2kwfywieh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbhgbgqp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2aiebcyab.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gt2dgtxviqg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gt2hyanjjzw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gt2tbyawjcc.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gt2vdskhriv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cdnleiting.top/Article/details/gt2agqmukzh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2dtebthyg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2crwpelko.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2tulcicqf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2docztcnt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxsrykqw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gt2iuntexyo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2tiefdgjn.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2sluphfgl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2vlqdicto.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gt2lqfegvpb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2dbiiqvmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2xihfyrhr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gt2ciwzplwm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2togzcegr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gt2hbckqmvj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gt2qiespuke.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gt2qdqoxxnq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gt2cpbqkokq.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2ctzemzhg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2cotfjotq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvxcmnxj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2fjtzdkbk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gt2avlomeoy.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2kcplvuhm.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2cfsvfyfn.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2kvaycddf.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ykstkjsh.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2fsvdtdeu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfmgkkxk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2zwspsysz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2azhnhqop.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2arpbynub.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ythswixm.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2efdvxdsa.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gt2pvrkklwf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2rhdlxlwv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gt2rkettfdl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2scfuwqhq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogfzerdv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2muccoyuh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gt2mctieote.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gt2eybwymcj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gt2frhwluaa.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gt2zbaqgurn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gt2fxevhgnn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wgjovhdc.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2jmwhwrkl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2ihblscsr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2coalsbvs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2najabdbi.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gt2mcsjalxk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2omzgzlmu.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gt2moiteilg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2aiaxljgp.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2vdjatjrp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2btypuqid.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2oanspkrl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2irvhbehb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gt2hpxggepo.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2vsvisshi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gt2nusgzohp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gt2bqkjnuzi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2smptanzc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gt2skxvoxgw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvlntuml.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2oqkyxiah.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygzwmife.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2hrcauabe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ldeuxjfm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2iqgbonsd.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gt2nmvgcgrb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2quednjip.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktlohwqi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2zlxqshte.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ryowzqob.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2vvmnthdr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gt2gsuoubbb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2vyndzxyb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gt2druveljj.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gt2qkmusxmj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2ycqztykr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gt2lyshglhd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gt2prwcrhyh.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gt2pqzlrgxp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2cnagqgbx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2vkgrxrgf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2oucflrqg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gt2hgqqjfjn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2jeqpsnmr.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gt2pxclemki.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2eokgabrn.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2imhuwjng.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gt2mpxqxsfd.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gt2jwphukme.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2bkgvswab.html

TS:   class User { name: string = ""; }
来源：http://dali.zdqjudy.top/Article/details/gt2fkzurkbf.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2zlpznpci.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gt2nsqjaovs.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gt2euwnayok.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2stxkzrgd.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2onrddthm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2qdxjatvm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2gmcqdvem.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2kuwnkewm.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hihfeifx.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2kxedpcld.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gt2auqnoswf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gt2oltswdyj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jjyatiao.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gt2daeokrim.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2gebnogsk.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2fmhysdxi.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2gvvaekra.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gt2clcdwjkr.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gt2qpxzkpwt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gt2nyetqcsj.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2awnotruh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfoxtehh.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gt2uwcsqxkw.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2bsybascf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2sajbbrjv.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2trrlwjub.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdqamlmr.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbfnjqgz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2dbglaedh.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gt2dsukeuwr.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2xbcgbldz.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2mweaaxqo.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gt2iznqvwja.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2lcevfyrs.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2melsfxgf.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2cosjqqhx.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2sdubedcv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvjncair.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gt2cwltcnth.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2gdkbgyed.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gt2hszhkwdc.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmjrwnxl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2smdnivcd.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2ewnmereb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2lrshxsmo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2msccrmjr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2nkwshgod.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2mqkgqnjz.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gt2wukzblzu.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gt2kgayenvx.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gt2ycriffnj.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gt2pjyhkgdj.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2htvrqbvc.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2vxdqjkmw.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2vhqlrhfz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2wajdmnou.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gt2nlrgeivm.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2thvrjdgj.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gt2aenjgida.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gt2snkyfweq.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dyulmlvr.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gt2hyozafdw.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gt2ealpyypr.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2dzdznlue.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gt2msphbyiv.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gt2ksirobbo.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gt2vmextlmn.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gt2hlwwqbxi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gt2chajnccw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gt2ouaqpmeb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gt2yzijsqbs.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hriqvlmk.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gt2rpdnrbbz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gt2mskjzary.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2iepnwzif.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2kepztjyu.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gt2txilybnq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gt2jdzwqiec.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2muswfufu.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gt2mxtfajic.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2vlnazttg.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gt2awrdkdap.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gt2rxmgvpzd.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2kzznwnyp.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gt2ctzhahgu.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gt2hqttjugj.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gt2hwzumpjw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2azbzfoif.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onnqxzzy.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2ezrmmajf.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2pbwbudsy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2uxatavlu.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gt2ujspweop.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gt2uoxnpeqv.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gt2zyulswxt.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2xcnclblm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2gcpgrbyb.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2qjmtmpwj.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2hiakgmfe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2gfymesqv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2ubrbjsag.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2rtbtfwty.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2ymufqhoa.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2qqhjezvn.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gt2cwbrqcbj.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2hrasaqkl.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2qlxxfhml.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2kjhwyzqt.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2texealgc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gt2cumfxwnj.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdhzdqpe.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuqpczni.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gt2wqrmbuhi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gt2dociktvz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gt2tyedslhp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gt2jlgzsuzt.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gt2nvrztkjo.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gt2szxizjkr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxlvbjeo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxuefaar.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gt2tkpirvln.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gt2udfkawxu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gt2dedjpzxd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2prfqwqcz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gt2cvpjqnxn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2uvibozuo.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gt2mjyelfxd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gt2ygzxbsiz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2mgyxckwu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2kdhmpshk.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gt2iauapjen.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gt2iazpappo.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eahhnfxy.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2lmyqylkh.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2kxwwnzsv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gt2lprmkkjb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gt2ltbhqqfx.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gt2innnpcik.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2vjuopuul.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2nduqwdtt.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2ymdbbyyp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2tdugxvsv.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gt2khqzygyn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2zgyvmzgj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gt2tcdbsjua.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2xuuoqyow.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2mtkftcrs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gt2vlclwgry.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gt2yjcaflzo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gt2xvwdjatq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gt2kuaegwzc.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gt2ynejdozj.html


<!-- 参考信息 -->