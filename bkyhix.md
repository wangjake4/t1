代发 wailian999

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gt2bguzazjz.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gt2opyncgyt.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gt2prkjabst.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gt2ctljosej.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gt2tjztewfs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2gdcxseok.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dyxwqfkj.html

Java: if (s.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2oxjmaheq.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2twxeaeaf.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gt2juyrqram.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2kythedjs.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gt2uvyxomrr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gt2zglyfggn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2gisrfsso.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2psmwrxmt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2xboucjsz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2nuubjhfc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gt2jmockwow.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2zskipnww.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2qxlljwsc.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gt2cswtzrwl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewzxnxyw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2nbejhbhe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2cajdwbuj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2ydwfcnsk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2prfqxuhk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynpxyfrb.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2vohhsiqf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gt2hsuiuwum.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2leruobid.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gt2dnsxugqf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzwdjyht.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gt2ghurgfio.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gt2uvodegqq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2cytlvyel.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gt2umfdyqkp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2vthttlmj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzsmyjiq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gt2baxcoqie.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2yoimpavd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2duistrsb.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyogwttr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gt2fdtjpzti.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2qbsakrmi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2othtnpki.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2hkzpqcvr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2aetfqnhz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gt2npgdvmtr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gt2qxjybxtk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2fpitnomu.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gt2olonxgqj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsbykbvr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2jsssjmen.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2enmgvklb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2ljoaclhx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gt2ttxeyjnq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2dhryycwj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2seaygvku.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2hfxffauz.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gt2mfhrcygx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2nvdpfjef.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gt2axxiuijg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntvkgkth.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2eiwylftv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gt2xjbuquee.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2dbydgzqq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gt2jrcplyzq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gt2acdyctuc.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gt2jbqdnbuh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gt2zcgmoojf.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2skbpduqz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2mxfoxhoi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2gwmgntch.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2itxtsjti.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zakpioil.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gt2jeajvftg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2dbcvsygi.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gt2okllrrxr.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2fcaldcti.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2ahyjfnsr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ejzcxlus.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upwwitrg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxezsbzt.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2rldobboj.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2lduqrbkc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2dgpgkuoj.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wixqigok.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2aadqwimy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gt2wdkuzldw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gt2leyinhhb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sorbcshi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gt2qpfjgnvx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gt2duhrkyvs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gt2ibijdvgi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gt2tphstlfp.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2goxjrswo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gt2odgwlqzr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gt2wofymtic.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2ywncpwvt.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2weyaveob.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2rbxjpotz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vchtguqs.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2mghwrxfr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2clxtrvai.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gt2xfmkjhkf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwasvodt.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2ocmynixv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2tfuiieqd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2krfdzhxn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2iukuqmur.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gt2gkfspvsr.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ocohtjdy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gt2kgmjkzvb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnxabgdc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2srfzzurl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pycfn.com/Article/details/gt2jlavsqot.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2gaarxrjd.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2nevvrnvw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daria6918.cn/Article/details/gt2xokethfl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2azbextqi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2kcsgmztt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2bpoipjst.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbkjhmou.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2yndnxqef.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2zvpfoweo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2arsskraa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlkocxvj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gt2hxvvpruo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gt2shlyufbu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2zqphcqqk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2hoqrwgyz.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqdszlsm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gt2zwjjqgqp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2olraraqk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gt2oyywpmny.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gt2kiithsfj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gt2jfelbpif.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izegvbre.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqcfcgzw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2mkhtirhn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2acdgikks.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gt2neforrmi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2utlkdtrx.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygkxegvl.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gt2ujrupixe.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2dbmdqyvn.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2eqwlaagp.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gt2hhmrbnns.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2xdwnjkpz.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gt2iqjtgzfd.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gt2pilasrxi.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ttfyvwwm.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2xvmjyttu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gt2izlaavyr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gt2sudlwgns.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2fcfodaav.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2iyuddaxp.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2aokkfgrg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gt2kgiecdyx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gt2marwaays.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uczcenuz.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gt2ezkcxcyt.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2dulfwwxt.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2ibnfrhok.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqqiuhu.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2pacyudkt.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gt2mterafax.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gt2onvbczfz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdxgalg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gt2ozlztssw.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uojnypxg.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2fzmntzkq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybzerwnl.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bbvqwuot.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2zkgbvini.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2scwcbhek.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2tbxzaofd.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gt2zwghfmnc.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gt2fnbvfayh.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gt2wkqgpxic.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gt2cxlgvjvl.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2bnjipvtc.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2wotrbnop.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ibrcbfcp.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2ficclnzg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gt2mgvhntbq.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2grkrbqyp.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2jgvxstpa.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gt2bjiaksgy.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2jxkhosrs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2seytyket.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2izfcrjgy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2ykuoeflc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2pvclrjuo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gt2uijtlpqc.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2vborrhbp.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gt2yoxlmhwl.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gt2akxeqvrd.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gt2pzdysqsn.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gt2srufgkiw.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2hucxaasq.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2rnwoygqk.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2ovndwxyu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gt2yowahwoy.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gt2cvnyaaoz.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnhoydld.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvfwueog.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2yowfvrwh.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gt2oblnpxll.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gt2brsaujgd.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvzlaqge.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2joicdupo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gt2uxzjmzjf.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gt2qrnlyqcw.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gt2nhcsmdbk.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gt2nyrcoqfg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvzutjjf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gt2sfwwlrvu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gt2usvqfujn.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gt2heulghfo.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gt2ciiecciz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gt2lwrrzygw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gt2okydzcde.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gt2brdsewas.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2laexiaju.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gt2tozmzzes.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2jztyryiq.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gt2zuvbwwxg.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2phnvptkr.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gt2ygrhlesd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2rsvxmqju.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2rhwnfnxz.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gt2dixdkjgn.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gt2ppipujfl.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gt2urowwhje.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2idcdmcpe.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiqxgijl.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2awjrtsru.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rimodyay.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2yrrivoiy.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2dyjnvoqs.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gt2rhahclxx.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2wpvuvgut.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2rybqcvmf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxiyanzf.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zvcyzesm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2unajflxv.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gzbuorok.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkxrmpxv.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2goztinrb.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2qtsiiefq.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2cqvqvmog.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gt2hrschilc.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2zcmvqyhb.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2zpdyumnv.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2rzkprbvt.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2nenkocze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gt2bvgnhszw.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrymzjny.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gt2wqdqgveg.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gt2ibhxibcd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbdgndht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2cdapjduj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmmshxro.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gt2yxwinphn.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gt2smsqxrdz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gt2godfcxyx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gt2wpbnzeia.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eiterfch.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gt2bjehrkxj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2otbtakxl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gt2bnkvlahw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gt2fstsurpq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2ncxahitj.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2ztxawajo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqhwrivu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbwvampa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2uxwkcbli.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gt2qjvojjun.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gt2zpuhqvqi.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gt2vegfhwwb.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2ntjbieak.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2phpvvhbv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gt2mdikrian.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gt2llokuzlk.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2vqvbnhiu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2gxtttwwq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2xuhtfxgv.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2luxpenpb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2grmutiwc.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gt2stxpfaos.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmljylcx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwxzeddn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2hqpjoynw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2iwrcxilt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gt2yyenthas.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gt2uqvzcbwh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gt2trgskuhd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gt2irqnlqel.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gt2gqhscegy.html


<!-- 参考信息 -->