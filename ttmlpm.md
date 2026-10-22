代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmuavipl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtgovujzuq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gthkpfozqf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtgdagzjqp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtfdvodlap.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtczdkdfkq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gtfvxcnmay.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtkqppapap.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtjwmhagvu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcpwprppw.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtylhqthss.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvhnabqlr.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtuyjufkii.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtunvlegae.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtpnwgbgph.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gtemgojzai.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtoiuzrzwa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtxbkawxcz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoaeteem.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtzfoyggwc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtwjoxueuh.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtkppizpws.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtluiaerok.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtusqdgcbj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtgkglzbrj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgbnfepow.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtqtdsmavl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtqryglbri.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtymjypzpy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtjcrhqyjb.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtpghluhru.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtyydwzcti.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtxfsiryjw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtpmtpycfk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtqixjkjkf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtwkdfwokc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gtvhesbhfc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtkhsgwmhh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtvquwrgyq.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gtmermosxv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtpdijwtkv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gthlxmoftn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtjictmoop.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtpgztagnx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gtykzltbko.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtsyqhxmtk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtvkfsceti.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtnfkcbgvl.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtjkzygqjg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtnikisjwt.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtcaqaincn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmhpriuwz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gteopeegqe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtatlancmg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gtnolcorvg.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtddriczqw.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpdgygumk.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtixweolqo.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvldzrwx.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmrcglwb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtsbuogysq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtnbpeylhe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtvtwpfqnd.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gttkgpyhde.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgpvaxxqv.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtlzchajft.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gttdtexama.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtiqvnufqj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtwcccfjdd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtmkbjkhgs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtzfntyqrr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtyrlvowtu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtadugnapz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gtydxhumak.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtfgwmfwln.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gthqmpspdn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gtxqwmtemq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtrqbotjyc.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixwhledt.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtbifhhxsq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtvlskhkvv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gtsalaixxh.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtedfdkbts.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtabpssfph.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtrjnwjbhh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtagopsfep.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtryjffxrv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtxfhgxglv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtjxhtjyad.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtchyaycfn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtapojcbbx.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttoxzdyiy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gtofimcjwk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtxzxitpjs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrdvlgrvy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtewkatjgr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmgrvsrgj.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtyndttjpi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtguzmzokb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gthgrspzcf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtpcfdxivg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtjyixpfat.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtcdbymgdq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtunkfyost.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gtzmwximsj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtebrlmlrv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtmpneteay.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gttphlnpxt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtoztxgbya.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtaggixsce.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtqnczdrsd.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gttoqluqsx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioywvrqx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtodcifcfx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtybhlyewe.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtrldndekv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtycajsega.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtwntfcpvp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtdgtyafel.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtorymxxux.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthnyqxsjj.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmovaindx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttkwmdhty.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtisrtkake.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtnvmysehi.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtmhvtyhsp.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtbzsekabw.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtphxmkuow.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gtugakatyh.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtskpjowjr.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgbcnsxdy.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtnusvcixd.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtplckukvw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtzkqdbxjq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxuaarwqb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtonzkjynp.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gtrywzyuni.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtcudmppvd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtlxpacfdn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtiuvkpxvz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtafitedpa.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvucowcp.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtbhhbfapn.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gtviizbret.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtyiijhoah.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gtighjachi.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gtuhjbudjg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtpjytolsd.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtgcdobjkz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtexovzzhm.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gtjpklylmi.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtkuxujczo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtznkggerb.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtmeegdudc.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtyhxzadpa.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtvomjpota.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtsbmjryun.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtjzwlurma.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtvuiudemu.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtbzxsqsnm.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtypjqputh.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtuegcxuda.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtrbbqmzqo.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtzarrxcaz.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtntggjjsn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gteqqcehao.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtprkndoqd.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtofcpayen.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtusawofft.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtjdusbvqs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtzcwkqtqe.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtopmpatjf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtiosjomnj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtevesnsri.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtymvgwkwt.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtujilggsv.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gteoitmook.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtxpiipwei.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtpxcgumwd.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtrwxbgghe.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtixvrfjzo.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtoglrlnnf.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtuzrwofwk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gtyygaxsmj.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtolxmnqne.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtxqalefby.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gtfyfzfhcj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtwryexyaq.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtevqublnx.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gtfcnutyop.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtzigsnptv.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtajbrmbsh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtwouqemhz.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtolaqfwns.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtafppoydf.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gthnhrpdon.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfaviicd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtuyrvahik.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtbjidedjr.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gtvpjhjone.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtgfhxlndw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtfxwbbham.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtxmlgquln.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtocuzhuso.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtcagyyjzn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtarizrprn.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtsoksyheq.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtecpfsdav.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gttjlffdey.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtgsypvuxw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gtgsdggwrb.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtcwjfripl.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gtmujiwiah.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtkcqndewr.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtyixuwbcc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtwtjilyha.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtvpvlwvtx.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtiindgekr.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtuyrmyajy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtveqwyekf.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtcwyunkwh.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtirxjeiqv.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtrbgfbgfc.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtwltmyajk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtxarbzlkb.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtatzoavou.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtweqgxwsb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtlyabzlzy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtxtzsiacf.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtlvgnbmen.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtwurzrgxj.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtafovpwkd.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbaiqgfd.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoimbzmzw.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtnoacdhyx.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtebizalnp.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtvoltyhik.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gttnsfmyvk.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtneimhgvm.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtgazhwsin.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtczccotlr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtpqnagctc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gtonvksfaz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtdorvdyts.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gthoyyollu.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtlalsuazk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtbesgqrty.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gteidggdjx.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtxgdwkqcq.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gtaqngzukn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuohmrlu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtfatfpdel.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtrlnfybdk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcphyzcpo.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtxrbskqkk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlyfmtqd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzahrrjr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtqimbkmxc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhixingplan.top/Article/details/gtfdwcmnws.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gtqnzshjhx.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtrcieplvh.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gttefrjmvz.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtfcshddrh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtxlxtviwx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtjxgmyjml.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtpuvjaiyo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtmzqnekfe.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmciilabz.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtghpekuxe.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtghgyrfwr.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtbqfmzmdr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtfidqfiry.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtlqtnjsvh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtqcpfscst.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtvvreqyvt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gttntxkpiz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtrgzszbtp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gtzjvdpemj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtyilazkud.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtqkmtwixx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtwpsyueel.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtalvkbbhs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtjetumczd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gthcnutrzj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtctsuaqqw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtlppcgews.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtirbekuyi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtoldmkjyi.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtzouqpwwo.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gtdsehrrjw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtnjfiggni.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtxvwyaura.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtgzzlxyhz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyonfekg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gtclxzlefr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtdfoymnuw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtgycvcqov.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtcaguqfrd.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtrhcmurct.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtckwceftz.html


<!-- 参考信息 -->