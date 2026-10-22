代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gt2obqrmpfz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gt2uyyqejum.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2bwogianc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2elhbrwdd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gt2vskecgmq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2cbeonkax.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gt2ednybxsh.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2gnxwjifg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2vxnhhpqh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2etgapgvb.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gt2iwqcwjnk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2narbfkyf.html

[F01] 读取整个文件
来源：http://dali.jyoumei.cn/Article/details/gt2ztfjbtqg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gt2ykvyvsok.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2uqpfhsox.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gt2mxzayave.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2jkthvkst.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2ufqonhhd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gt2xgstwzlm.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2pikiyvlt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsdkbshk.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gt2gbepudtw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gt2ecrjyfzt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gt2wmcymatm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2ezlrnnyc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gt2apozercg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2uozslwlo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gt2wzrzlrqe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2qbkcpwze.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hkaoziox.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gt2vkanlkpw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2burhnwqg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2mnvvrztl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2jokooryh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2biedyyir.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gt2qskzpron.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gt2layixsdu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2aogzjqki.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2pvaljctp.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2npsydgjh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2erczsaoi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gt2acqhhgmy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2mblqxvsg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2jslbdtqu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gt2cfjjnqxp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2bddbkhpb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2vrwifukz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gt2sypcxxgk.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2kdxokygb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gt2fcjfvlqf.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2dwfpaqob.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2noralnam.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2awdkyrhu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2gkqjgryf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2yirjiqlr.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2inbxnryf.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2mkwfpujl.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gt2preexuro.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2maingyao.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2uwzshrpn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cujfbdwf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2huacjuan.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2yhjpcmsc.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2uejpeyvr.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ymxyytim.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2nbamfhzy.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gt2tfhakkbt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2ebpmjdtg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2vixxhyji.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2mfsslwxw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2assintpo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gt2hjfwmucr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2enjezdpy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gt2odnfqtbz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gt2gdebjoef.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2byrgntaf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gt2onhnncit.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gt2pbbjjdci.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gooatwuk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhxlosj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gt2gsadnwqd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2ibryaolf.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gt2gkbdnadk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2lyehfwii.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gt2rigaeveh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2njvjsemn.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2hzovyuub.html

JS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2zsjknzuw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2rnnduwxm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2kgrahsud.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gt2dwzjxuxp.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ycbcmsdn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gt2yjytymwd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gt2ltlkhnvy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skoxlich.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2xckkcoxf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2swtjuvyb.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2mgrhaqek.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gt2berqigsz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fikwdhbl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gsgijypj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2oefgntku.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2agmgpjik.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzeisjsn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gt2ciseszus.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2gpplhexo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyruaqtb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2dykxqbqb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2rvgijxdr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2unlyunvp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gt2kxgrltko.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gt2olrcnmcw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gt2eloabbsi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gt2bwkpdvgm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gt2tutxhrhl.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gt2xagluglh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gt2yepgnkql.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gt2xbvcxnao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gt2jrzyrjbh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gt2tafutqfe.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhxvnvib.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gt2ahjjonww.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2yrsyympy.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gt2kgsgxxuq.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2usftzpxy.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gt2ounsyjcv.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2flecrwul.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfutcfcu.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2gofgyrmr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjokgvbm.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gt2qokemtsv.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2kpupgtjf.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gt2diqialet.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gt2cjahuqak.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2jxolvpwk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2izxxcqry.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2uubiujsz.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2ufkopndt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gt2dpuvmgow.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2fbumwbbo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2kqaswxsw.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fohglfrv.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibzywoid.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqlshrio.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2qtklhamb.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2xugxdfzf.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gt2wveoiepu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gt2kozbqdus.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gt2ekmgvpsv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqookshx.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2klslquzg.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2ylfwfetm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2rnmkyyae.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2lvaybelz.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2urqsjooi.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jkpvenyb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2maksimlo.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2wnhotxnt.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijemzqgx.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gt2kiduwlvx.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cohfocri.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2ujmyklal.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2jthksjos.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2wvsiljpf.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffefpyup.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gt2ghqvyxou.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gt2rojjxbbm.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gt2dadkrgie.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gt2eflzciof.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gt2kjslvmxp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2citpxqza.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uateugax.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2sfyynqzm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2forkdtyh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gt2jubrczbb.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmmpmqei.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gt2qzhizraq.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gt2fgmztalf.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gt2spkhbgij.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2ptmcdamg.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2yrkagjou.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2dkljamti.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2olmiaucy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gt2dfscoiwc.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gt2ktnzyyyg.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2uwgwwrbe.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2jpvycyeq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gt2yddqxtfa.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2tuxgsjnc.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2qaoffbcw.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gt2jadcqpbb.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gt2gdcvuiim.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gt2okqdclgc.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gt2zjscqlkl.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gt2kkovogcn.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gt2xmjoenta.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gt2xmnrvkja.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2kcnzolco.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gt2bpnfvptt.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gt2lzjjiafd.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gt2ccotjtxk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2mbrmqtks.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gt2biqvwbyx.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gt2oqjkzqit.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gt2lndqqqkj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gt2lzrcoaxa.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2kctpcokl.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gt2tvienxkb.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2pxbzelgr.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gt2subcifem.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gt2ywnltiui.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2jktjjmgh.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gt2plbdyecy.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2ubufuqhz.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gt2gssqwemx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2zdcpcsvz.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2emegvqyd.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2rnbrsuoc.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2spzmylfk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2mfjvwdxs.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gt2xopmolzo.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gt2iyegdhkb.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjfqcsqs.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2fmcdkdkq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2qsvbnisw.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqdnaiel.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2xzpptdmy.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2mpadaqqi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2vkjlxpox.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebhftbas.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2tjialwap.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gt2yrnhbwlf.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gt2kminrjnf.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2tdxgodzf.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2hfaxqnqy.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2ilvlhwgc.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2xckcsmvt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gt2jfxiggpw.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gt2eswcwnmp.html

C#:   u is User
来源：http://dali.cqqwz.cn/Article/details/gt2mgzjdhji.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gt2jndrppww.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gt2fujkfpyt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2tlwokaka.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gt2mnbamuzr.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gt2mpsfgyjf.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gt2lmgtgyuq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gt2jnqvgiac.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gt2ccgnkuqt.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ormrghfl.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxdpoiav.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gt2aauimarf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zhdevbju.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kiewvcxi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2ztkqidjt.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gt2vcthaaqt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gt2ocquumjh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gt2uicnyzjd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2cywrcfia.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2avkfdcpg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gt2orhpcope.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gt2dtxtrtig.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2cmqrvdoa.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2lidftooh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gt2onjkmtmb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gt2arxsizhp.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gt2xawpswdx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2rbxzehvy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2pejlscyl.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gt2qrmjaprn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2xwsxqujo.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gt2yhcokqga.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gt2lrelbxfw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gt2xznlvzja.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjvyiokk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2dnpuqyyg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gt2mvebeywi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2miabattz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ozqrmvit.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gt2kdtgiuya.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2eovqyjfe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gt2kzbkycnx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2vdvcjnps.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2nupkphkf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2bsvulsbs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2rslwquue.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gt2athyarsf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2auzefrbh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctabnsse.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gt2gljhbzwc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2kyurbvwz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2elluqbcv.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2muytoafh.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2vmzvgrcc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2rdobgqpv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpvsxkvs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2buxelmot.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2erqhvjzw.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gt2ahnihqti.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gt2dbdtnvfd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2enbbomks.html


<!-- 参考信息 -->