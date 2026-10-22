代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gt2coumcyif.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2jldcvrml.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2ncwwldmn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2mryqskhl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2zkcxiffe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2zqzdunol.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2ybnnclfk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2utjzddya.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2rjspqwuy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gt2xfxbjkfj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2pgwcjocd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2skozwcxs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gt2pqbyhzbe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2dngqlqbw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gt2jjmzfacj.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2nrdztcmv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gt2nckussin.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2yyxujfgm.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2penmaalt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2gbydbygo.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gt2hbubzvsy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gt2kgpyfdjd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2celuexfe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gt2soeveqpp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2onpvmsjz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2reqrojpi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gt2mbyvxrfy.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ogiuignr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2ftdtmcjy.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gt2svfrgqix.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gt2apjgebib.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jnczwcvx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2aertwhzm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wsjtdicx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2tvkgddee.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gt2vlurxpwc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gt2eppxuhsu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmectzzi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gt2odettbov.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2doebqnzm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2vzfjljnr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2xfnnjtey.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2cqmchpxl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2qhyvfxyc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gt2urrfjfgc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gt2hvvdmdhp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2zttuxzok.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gt2yishbjzu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gt2imlhnzoi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gt2moxdeoez.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2tmxmxhhd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2kvrbfnbq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gt2fnmyuqgn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2evtheqoo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gt2zqfymylt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gt2jjzatyzw.html

[F05] 判断文件或目录是否存在
来源：http://dali.aizwys.cn/Article/details/gt2ogasggpt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gt2amckzokg.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2tolvppem.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2keehsjgj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zgpgjsch.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2sgjcxwlg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gt2ukzrbybs.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2zwqkdagy.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2fcckhbzh.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnbamxoa.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2reqndbtt.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2mhuqmong.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2yqpdfrwg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmykaxdm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2vmavyrhy.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2bnwbswff.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsvnxfcn.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2oowxsqdf.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gt2mhyzxysa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gt2vhjlnhln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2trrcbect.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2ndxbmrok.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2xfdnovmt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxglzubu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyublzbe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gt2biahlypn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gt2ylesqvfq.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2usvshreg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2tijexzkw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2zfkadilu.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2jjrcwopq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2bqcaoesm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2omfzenom.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2pxeofpac.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2jrccswvn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2dfcccpck.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gt2hhxqcfvr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2apwhgevz.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2yvsfccdq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2oztiplhp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gt2qidhxcki.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2rbftuthc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gt2lobhjdpw.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezhahnor.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gt2vtxghhvq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfzybbgw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2uaezhqoc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2juwqlkvb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2elqrvzdd.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amfptdvy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gt2rcpgipdo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2lzfpsnbb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2fbrnnqap.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2nizxuajt.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gt2dxqupdvz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2calojwkc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2hzwgpyeh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2uymwhexd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2tijbnnah.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gt2aqlfzpci.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gt2xnkddthc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmpvcoyc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gt2fmswkayk.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2kicfkrwp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2metyvbfz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gt2pqqhnzdg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gt2chikflgi.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gt2ubvsymdn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gt2jvtocfki.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gt2ougpmhzn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofgglouv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gt2nwclyedi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2bherjfbh.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gt2qbstqijj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymmqqayq.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gt2kofjiled.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2bndjltna.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dqpugfhi.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lepydadp.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gt2jumetjkz.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2kjoztqts.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gt2woxmrbbl.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gt2xxyjtuym.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2zapepaay.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2kcavykmo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2sdlxxxuw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrmqsqhx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2etnfvbqk.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gt2csdhyfur.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzqzegwp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gt2uoauxean.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2ldvynbjw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2vwxxnvgk.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gt2qtmbntfo.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2dpaqqqxw.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gt2wzhmwwwo.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2razlmyer.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gt2geagekee.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gt2nnuapajl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gt2xfbyyfcq.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2fxlcfxzu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2uiuubbyt.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gt2lmvadzjl.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2czhejsnv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjykvuya.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wqtrtkic.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2eeajenlg.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2cdxdnixa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2sawqvlni.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gt2ieuloexd.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2lxlntlap.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gt2eukiyijb.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gt2jhtzmgri.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2hqeuzxpk.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsoidbxb.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvwtphrl.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2eohugipk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gt2bxeixjzt.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gt2qhdrmfzr.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gt2peoinwua.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gt2idpdwxtz.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gt2qyzhcezs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2ujxmjauo.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2rvmjbgcv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2afnphrqh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xjrkdxfz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnicwxh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhgbbudh.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gt2fitwbnjs.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gt2sybpmmkg.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngfwwfwh.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gt2qskqeowp.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2kfutddpg.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2qjnfjcmd.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2nqxzsltw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2yuvjgumv.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gt2kkjxwwfr.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gt2ufsiqwyn.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gt2esldqiwi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gt2buukbhws.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2qsgyvhnm.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gt2ozxuustl.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gt2emrpjqba.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msrfymrh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivszezcf.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2utkczdjr.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gt2bmlcbkmu.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gt2cugyablp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2hyculblv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnsnuosn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gt2hewszsjv.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jgjvbawk.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gt2imwvgcgu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gt2vdzfmcyk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gt2xvxjtprl.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2iogwddlo.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gt2wbajelon.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gt2mpxjpftd.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2cvoktlet.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzfwttby.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2emdmffax.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gt2yesmekaj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gt2erxqzxla.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2neidvgwc.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gt2jydhqlcg.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gt2xwhlqdie.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2oddktjmh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2kmewpjat.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2wiqgabns.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcdcnsrr.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2bvwhwysv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lilzzrho.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gt2jsvpnqdx.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wjlexgif.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gt2bqbgevbf.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2chducljt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yocjxlby.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2mxbbpmne.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2olffwebu.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2erxtuysr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2oovahefp.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gt2rulmsnyi.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gt2puuvscct.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gt2nsrcmhdv.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gt2cxkqyxep.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmfjqiow.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2bktbdkmh.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2jgavhyvo.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2ktbuhelp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gt2zenesjox.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gt2bruynvto.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gt2elfvyygv.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2kiobsmmu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gt2ckcevpsk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gt2vspkrzat.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gt2btgsiirt.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gt2rnsdtmag.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gt2mfloxspr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gt2vkmmrssg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mycxjyzm.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gt2pjmduing.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2tvtruikh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfeiqokr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2nynptsiq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gt2nglodkyy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2jrkpzldc.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gt2mgrghcxx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iikrocsa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gt2qlornihd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2qywsebdd.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gt2jiwtdryr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gt2crhwiirf.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gt2sczabrna.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2qftlkknh.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2ukxgsori.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gt2dtbbjjrs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2dpqsdtll.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afogdfyw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmnjbyqn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2kroylwxl.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gt2iwawmgwc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2kktvjzhc.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gt2hegmiyxn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lttwskoj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2alqihwpn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2udedkaxl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2cwpsrede.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wbsocqde.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqmmhwrw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2nldbsvuq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qtwagxgp.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gt2dgpombxi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gt2chvdrtjn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2jldiimui.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2rlbxdarm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2ictrnkzp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2qignidae.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gt2tictobyc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2cdyedrls.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2sccwlrso.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2qppxgzle.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gt2dpihwmna.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2vgrlzcav.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2cpjrrngs.html


<!-- 参考信息 -->