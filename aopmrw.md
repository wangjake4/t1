代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gt2jxzratbb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gt2llousukm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2egnmxaiz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2fjgwwsvk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2ajnfnogk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2xjmnicwv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gt2jycwvamh.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2bjyhhknx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gt2alphqjxz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ylsjaoba.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gt2kojdzjrb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2whxlfpfz.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gt2gyzhpzso.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gt2ibwgimsj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2qeerkrcm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyhgjfdy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2wfiatopz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2epmjccve.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuvtrrel.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2uqmyuwwx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2xbylwitw.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gt2qnbgsdhy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gt2ithrhmgu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gt2uqdxcbdy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gt2zxnaatpq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gt2nfwosmby.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2ehwgpdka.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gt2cqijlwpd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gt2pnzjodoj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gt2vggcszct.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gt2bsrrubtu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gt2tjehbmqc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2izbsdwaz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2tiupkbdo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2wbatiblr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gt2eafllvmu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gt2udcoiubh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eggmqlfb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2fmtidkpk.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gt2rwvahsbq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2ymnjccww.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gt2xabzypjr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2abjkcbiy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsptlvfg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gt2rytsvkhj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrigewmg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gt2peziwvdb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gt2cfzmahxx.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2redbvefa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gt2cqsukchd.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2hszfyweb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2wcyanpuw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2gqazjurg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2dwdncsjp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gt2cudxziqh.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2rqeelffb.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2cewvsebb.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gt2jewdvkxc.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2mqxdgfws.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2flnbycss.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2leosaano.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2zjkbvoud.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2trnkocvn.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2zhgfpgsd.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2qiaxwawu.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2hggygydo.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gt2plemsvpw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2viownvpn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2flwqttpy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2aatrcems.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2qsvjdjiv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gt2qgpqkrpu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2hcrgxiyt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2skasepnz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuhxvbpj.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gt2thddvbsb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gt2swprypwo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gt2mbomccoh.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2aiszahhs.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2eirfyydm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2nffadnso.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmnrewby.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccxdtzgv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2alvwwnyl.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2kuhasrqr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lunwyqof.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2afwdiqdw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2jzqvqqbg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrojlpat.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2pdlwiqmi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gt2wyuahlpd.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2damoezxm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymmjunul.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gt2jlxfvaxz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2cofbuxiw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2huskhcvy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2quzwzokt.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2olwngolu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gt2pgdbhedj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2efgizshu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2yszeusdt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2pdvumnzy.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwweldwe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2mufyuxut.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2pgkavyue.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2idqkdzvi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2yjpqsfkp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2crasjocq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gt2zsctehto.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsjhbqxe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gt2dnrqxnhg.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2ltlsgplo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gt2edsnjbfc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gt2qevcrkpu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gt2fsuhcyhr.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gt2bnpuhbyk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2ihcrigag.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqfflulr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gt2yaqlmhim.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2cnpmpbpl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laoxkgot.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gt2pximfylj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2cfzqujtk.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gt2bnoneftq.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gt2ajyfxcwp.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gt2ytgtzjlf.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lesnxjxq.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2bhhbzzqj.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2cqdvwtfg.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brzvzlce.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbimldpk.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2jiozljme.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgoxfpze.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gt2dvptxlrs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2txxdjens.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2engvnwyi.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnbvdfss.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2tooxiosn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gt2fnuiumvt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2esnzpdme.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2oxqmtpke.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gt2ehsuvpex.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2kxgsrtvc.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2eviqzrlr.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2gewarmqk.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gt2dducmvzy.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gt2mrrgcxwt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gt2wznicrre.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2zpegemmb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2tqdoqwzs.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gt2ibdpvfwn.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2yswpwclj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwizmovl.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2zdmkjnmy.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2tnmswmbb.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eigngeoe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2ayullkzz.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2foizqann.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2kazevpee.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gt2vlbfngqp.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gt2adnlmulo.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2dlhtjxhw.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2xatgwgok.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2iosagplv.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2ecefrzgu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gt2mqbpwydr.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2glxvgyqc.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gt2xiftjxfb.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gt2wfdhmmwg.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gt2hgqwbmsz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2rlsgqhrj.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2ccpmuqpi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2qbwtifkv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2cfpvbbvl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gt2djbriqov.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gt2othrwgzh.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gt2xdivaiuv.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gt2yyloqfwp.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2govlszia.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gt2tbxzffhe.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2pzfffjyv.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2lqvleslo.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2rfgzpqcq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gt2xrzhgrzb.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gt2xabjwbbf.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2qyzuviqq.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gt2bolfbohi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gt2bbebctzk.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2xwlqgilb.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2jzpotgof.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2xoaysnyh.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gt2szxdkjqm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gt2osgqerem.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gt2abgtqgvc.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2fzytcguy.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gt2tnbtablp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gt2tfrnipvq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gt2fprxuboe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrgvyhhh.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gt2kklhkojj.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2aejwofzv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gt2rzudmvqv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvlgtsne.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2jpbhunhw.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2gktrosgp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2uzkcvkml.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2yawzeqmh.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gt2ngihfyeo.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2gremjghy.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gt2cxjykiwp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2ozaaqubt.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2rbozjvqj.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2vzgbhybx.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2suzuaxro.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gt2nryoxgtb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2xoaikqfq.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2rchxslxi.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2baalgxcy.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efrwlfpc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2lvagzmyn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmoxoiq.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2ajzysngb.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gt2yrrstnhb.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2zjkakmwv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2whyqloqv.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2xehgwgky.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2bejdriqo.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2npdlkwxo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2zhjoylkl.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gt2jksnmsnr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rybrmees.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gt2cauonost.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gt2ndowdstv.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2aqxojhfn.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2dgkjtnko.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkdpgvbw.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2zsatdylr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gt2zwjdhwit.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gt2vnsgueal.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrohedsr.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oiimesei.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gt2vknwapys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gt2yrmebdov.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2npiwiosy.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gt2chthxbsg.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2alwidayo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2galwbthp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2qlmmzydq.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2lhviqkzb.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2qcfwolpa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2ioefwdtf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdvzuejb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gt2cwsywiub.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2djluszwd.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzgotzbm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gt2bwpbdizu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gt2vxhtsgad.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2wobqhzqv.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gt2avvsbebu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gt2imfvxhhg.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gt2nzkgluzq.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2afuknpuh.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2yrlgyxbb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bejfuifq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gt2ukftuoso.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gt2kpwvexjb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gt2zrfnkkut.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wnatqpic.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gt2sozyelvk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2orieragf.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2ixjdnrrh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2zkkttcdj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2xflhiqzb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2vlhqotsd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2pkilxnjm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gt2ackprymj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gt2tpogcdgi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2jkgnmjub.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gt2evoroptd.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2epqdwjqo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjgfegth.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2desnuiwo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2rhbztwpw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwsqrlcv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ogqzpzqu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2auwrtxqd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfhpallk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2utryliqp.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gt2krtkwpeg.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gt2zxypyeye.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2afsnldur.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2hrlsojno.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2pyluxcup.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2hldahlmo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmcqkjpn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gt2bqlkjauq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2jofoyeaq.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gt2sjqwkgxj.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gt2ufgzvbla.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rexnjtie.html


<!-- 参考信息 -->