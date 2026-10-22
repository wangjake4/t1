代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gt2foavvxdq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2tyqranrb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2qidmugrr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gt2mzqnqkqt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2fnshgodt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kaomwrgs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gt2riamkijo.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gt2ilhmvsvq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2kwpzvgto.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2toxcmcgm.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gt2pbhjlvai.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2esozjvxn.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2hochibgm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gt2eozaeprs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eaggmksc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gt2ubjbvxjm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2mjgjmzwn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2vozdoljx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gt2cbwwpfbo.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2cwcobtxj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2zfjeyybi.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gt2ehupuvtf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gt2woxhuiyy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gaiidmax.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xmbvklwz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2vnvduddx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2dpyhwsph.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gt2gfthkmlf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifakkgaj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2dzgqstvg.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkoawwos.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdnjndgw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2gzurmbsn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2npeoulyq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtikyufx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gt2yhsjgmuf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2weewmkbq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2pzxpdzvf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2twuqdrvs.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gt2hbawwykm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2prdajjsc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gt2mjwlzfkv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2xtrmoihj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2xuzihkho.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gt2whljkovh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2qvvxpeuh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gt2bdvcxfkt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gt2fnzpsmaz.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gt2wgfmowrc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gt2zgknuyke.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2twxdreik.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ghwrldoz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2wcdiksba.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2yrlvtheq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhlgnrue.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gahwopah.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2xjvpfogo.html

[F06] 删除文件
来源：http://dali.vqdsnc.cn/Article/details/gt2xppvihfx.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2wgklzxbh.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2xcutksku.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2mspcyops.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2kajomwbw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2novvgwev.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2chqpqkqy.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2tbmekedz.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2hikvbccw.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2zlviokex.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2ldhfgsla.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kifdowhm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2jljzxjqj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhqdxasa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2bawahvwr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gt2rmbmntzj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gt2xmsjklpn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gt2taoqaowd.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gt2bayoohxc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2lqenchai.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgooppnp.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2asnoqinq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2guzjnxbq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gt2pruedusq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyrdupgh.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2uwrjxncz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2whtxivya.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gt2loabtwmv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2kjxhhmik.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2dtcdahss.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2bamzecsv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jeqzjjjy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2bkfpcdws.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gt2vwvljohv.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvizsvsu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gt2iykuuhrm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2vbzbkcox.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2lwdecdtj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2mwnjoujr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2fekxfjbp.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2uqvqqimu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gt2myvlohpr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2kkrchqgp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2hlycfiab.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2jtzxqbwh.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gt2wntqwfuk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2gmezvdcy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkjkpvow.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2ncpbtvnl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ukoafqxc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrhdaox.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gt2sgypambt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2joilbbgp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gt2jkdczkfk.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2eowusjua.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziqnrgbj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gt2gmhzsymp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gt2mlxrbplz.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2ekemydgq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2iigfeosh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2oapssjbl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gt2pzrdohnu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcvkxkwt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kuszfmus.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gt2zruyehge.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2sqxdfjkk.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gt2upqulres.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gt2mnvilwzl.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2ugksyrnr.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2sutnyrdz.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gt2gxfbrmkg.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2hmgevscq.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gt2phtftomt.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2obhdsves.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2azzwaqyb.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ltpasgdb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gt2gbmygsms.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2sghyivcz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2jcnwvyix.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gt2wohcpaei.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2uloqlaip.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gt2suqlqlbq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gt2cuufvdho.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2lisuvoph.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gt2sxyywcnh.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2xdxusrsc.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2aovkljgj.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2ihywkmzp.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2hryfxgtc.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gt2bzcemzio.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gt2ugbnbyja.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiybgdkm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2ygnmweld.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2fukrwirl.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kohvpchs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2boozpjfa.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2rtvmaelj.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2szbgvyti.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2ilzzpqca.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2zodpgqzm.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gt2vusgzqcy.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gt2yyjozumm.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gt2oakowxqw.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2hozcvndt.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2vdutlzyu.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmoprtet.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2khfzbkks.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2enfpjzgd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gt2adgesxcb.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2hjgwvwys.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2vkhtntbo.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gt2iuvrcpkg.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gt2moohfckr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2bsplhubw.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2vhqzvoza.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2abpjjfti.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2vjnkhizz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2ooyxgdvi.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gt2fekorffr.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gt2ysjbgsib.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gt2ebyriylk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwryjak.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfdffplr.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2uffyzbwf.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2fbxjzfim.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2rprzjkii.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gt2almtbewe.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gt2yebygqbo.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gt2hnkweyzd.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2pcvaysoa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gt2isloejtt.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jormjlhu.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gt2dmlyauvg.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gt2khxrftmy.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2obvvbatq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2icdgrtho.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gt2nrsaogwz.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gt2gfgkyure.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gt2npmpntdw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gt2xezhmhig.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gt2xefsgwzg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gt2kzpagiqo.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gt2xnhdrwtq.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2jcdmjcyi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncjvhkmp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gt2jgfqunlr.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gt2omfyowjl.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2cfiztggm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gt2wpgfqyba.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2ojpcxdej.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2anhzytzr.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpndxebf.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gt2mmfgwlcg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2ihhdztln.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2amgbjvyn.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gt2hqoghvrj.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gt2recickfx.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gt2gcbbhqzl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2baqdtvci.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gt2iehzfwzz.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2hnwpnlmd.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2itrhcopf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2zihbntnp.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gt2wwqtmjjv.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gt2pxjtatkp.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gt2tcemzunr.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2tkowryup.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ldwjifjr.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qcytboqt.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2rdyqrzjg.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2apkpliss.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2ytbdbypi.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2hmyajcgq.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gt2ahaozwfx.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gt2byhvxtcz.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gt2uqqkczjn.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjjbszik.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2uywumenp.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2wkxffaug.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2drdjykdx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gt2wblagpku.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2xqryvrmf.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2ktvnbmoy.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gt2kwjjmghv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gt2dhjtasjr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gt2qbjaozbb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gt2qtffmvaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2tiaebneu.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gt2cwrxoxlw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pccezpbj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hongshengwenyu.top/Article/details/gt2xugsxdgb.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gt2iqprgazy.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gt2lkkxapzk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwzsmjac.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2yccvqozx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gt2gjzzxfzj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2cudikaou.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gt2fikghpwz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gt2lzfwnwsh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gt2ztxxzqew.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2uyyorygt.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgazovqx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gt2hxjqfjly.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2eyooaooj.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2ysmoyrlr.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2lvbjuuov.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gt2arnszixf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gt2kuawirgm.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkvyuvzs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxjoxlnw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmbcatxf.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2itprmsng.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2pvmldpzx.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gt2owruubif.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gt2wedztdip.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2puxvkvbv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2wcfwfblz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uitrxute.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gt2hjdlhjpa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyxguywo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gt2jhkhvxzx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akgmkoyv.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gt2xdxzuuxf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzufdel.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2rrkfjodt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2lyzvmsbe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2hegpdhza.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zoapebms.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gt2vqjpsxdj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gt2ygrathll.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2odlfmvlh.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gt2nwfxjhpt.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gt2mejhlfwo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2plhdbcvy.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2hwsodbif.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2vzjprzfu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axoiuiem.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfsvjkkx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gt2xdrtkohd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2ywfckaaz.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2ahagvllu.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gt2owxiqiyr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2kvsyeklh.html


<!-- 参考信息 -->