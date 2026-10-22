代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtqaazfesw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtypexlwzf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzklatel.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtdxhjlhuy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtjjlrbkxp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtyftxlhoi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gttvtttoir.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtskpgruty.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtpzguuoyc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvvalqaiv.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtejvjmahp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtokbtbiuf.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gthqtpkmbs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gtvfadjjty.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtgbvlrvxn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtzohnsntd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtvvtmkbkr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtvwowqhwc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtuemezjru.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtaduyclbk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtvtnejszn.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtqhjlcdjr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gtoynrmfgv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gtipiofmgw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsggkxdqh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtxoxxheso.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtgqvyhxrv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gtegxygiob.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtadhdhjwo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtwthqhban.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gtxllzqaqu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gtdhdlapsm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtepytxwya.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtoibrqzll.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtpkjdufza.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtxmagytkj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gthbgugkhw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtddherbdi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtoaatflwl.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gttwjszket.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjgghdnn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtgwlutjom.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtfuouforc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtpcoacohk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtnzctlipg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxueyaza.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtdntcfrzr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtujlaldgl.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gttdwtewpt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gtfhddpdgj.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtynmzxxki.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtmojnqxes.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtjhhhuknw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtyooyeavh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gttkjytfml.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpmhpgmui.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gthsvmiyfu.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtngvbgbpg.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvtopzsfm.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtikeodtep.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtezckyrtt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtiahyzcnx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtmatiqhgo.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjlxedebl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdctkgnwo.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gttryiukys.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtoltskjtj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtwxrggvan.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gtwbsxytfz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtmeymnjap.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtwvjufmyl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gtybysecjb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtsitltcrv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtyfpmaaod.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtusrauxyb.html

[F08] 遍历目录
来源：http://dali.yuxming.cn/Article/details/gtbmbbgcbu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gtqbambjac.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidglviar.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtolfrbeou.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtrrwsfiaz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtcemiyzfu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtfewjiahj.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtrktvlhcb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtvvrgnhsp.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtwrekeucq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnnjmxvjx.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gthmtnjjjj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtgmbspzla.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtgldmkuer.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtcvxdigjm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyndjqtr.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtdkmrmeuy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gthzszytvh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gthfyglmpb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqhnwoed.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtmekglpfl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmixhssww.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdkgcyjee.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtdoetjbfu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjhncaiaj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtprafehmv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtrwoasqtz.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtgmjxitqe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiucirqh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtbjaeimva.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtahqseijp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gthqaccxss.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyngisfc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gtndrcmcvf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtjkhaznsl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtcdkeuwvq.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gtoddkijqj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gttccoserj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtoxpimnzc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gtohkjwklr.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtqqepjfgw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gtargwdhjb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gtxzqqfnok.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtbdlmavvc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gtqpvrlgkl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthxtvnsui.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxhojcgb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvcdjdxmz.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gtidbmwxmj.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtiehunqbv.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtqmpviihn.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtgzqptqxn.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtndkdtliu.html

Java: class User {}
来源：http://dali.iojbl.cn/Article/details/gtxngujxqv.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtcimpntyi.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtbprddiqv.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtgbevwsoy.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtacgklyyx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtcmfwpzsn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtjanekcfa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtxizczwze.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtqtgsmrgq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtpmeyizxr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnguearus.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtzwlqwtqa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvgygxxkz.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnhgzfwv.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtxwmjpbre.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gtquerppqm.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtblktpxdi.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtkawhxpqq.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtuosgpxtr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtyopwcoml.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtmycpgffx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gtsquzkjzi.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtknmimfrx.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtfjkpulnk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtifdzbzax.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtiulxhslg.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtwlclayiu.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzlkfirfu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtifvptdqe.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtdbredzvq.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtvhvhevrr.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtxfprjjgg.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtrdmhajtp.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtltbgever.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtidbhiojj.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gteiarjnta.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtkxzuclah.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gtrhggcigb.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gtonhyakpt.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtlpdbfyai.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtuvnppija.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtdjqrtshj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkgmlvkvi.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtimthhvra.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtfxsxsyfy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtgvckukcu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtmnjfyjcw.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtraapyxbv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtbydfyuyl.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gticjpdnrz.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtsbuhmgpk.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtgkqlrvuu.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtrswkflgt.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtmaxtvukh.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtoeialwop.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gtrxtymnkd.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtipsymbho.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtrsmbvnhn.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtoxmsddin.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtrydmpiek.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtdsxkzhte.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gtokpocche.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfgfflkdk.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtdvqznifg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gttxsxorlj.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtgidrwslj.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtenvshftr.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtsedkezjy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gtjirzjyxv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqflbyfuv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtgumvbzvv.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtbeeehjxo.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtwdudlzxj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtcicnmpkv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtuzhcyhgb.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmzvqrtvk.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gtzgvdyqch.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtwzdkbkcs.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gthayhdocg.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtxcdqwwgi.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtifiemvef.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtapdecuyo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtmfonsxyn.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtjzrdxqfg.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtxeylctqr.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtztdpvipk.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtcqkmtyye.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtexbuypwv.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtcyjkligi.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtawquhpqf.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteerapioj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtyyxgqjem.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtwjrngail.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtojrsdtae.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtatkzullj.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gttsxxrgqm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtmmepxnnw.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gthbhddglo.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtalowzgkr.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtkztafqyk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtgirbgptb.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtlettbgnc.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtuygleihh.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtaqfxavjm.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gtjneinvqn.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gthbsuzngd.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtebqpciya.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtvzcirfwt.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gttbvguaii.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtilyeidre.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtcinwcnmh.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtewjsimhu.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkphatqkj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtrspsnfpe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtnnucnwfn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gtuplscaih.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtiqfzhqkh.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtxzvlxcdq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtwdtiocmy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gteiwkljmp.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtkfawcfam.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtlifzagbw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspbtrqzu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gtznpvrecq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqhqpitg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtzjqhgjuq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gteoywqaic.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtcipxgf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtpnvrvvww.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtvnuskood.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtuaafwgaz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtmwozusoc.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtfzkmcxay.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtchgpptjm.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtwbdatwqo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gtraqoddts.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtkejwmovi.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtnutktyha.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtjcyaiues.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtddmrtghn.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gtqtkxexmp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtokykarcn.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzrfpuhy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gtclsyuwzh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gttnrqejsp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtslcfhshk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtosopfmrf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtqwkefkcs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtgobyalrd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtlzjhswbz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxismajkh.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtuwtvtdkx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtibozxdnj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtgewuomhf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtwywabwlk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvejmhcrt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtpudntfms.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtsxdyfldn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtjttbzkhq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtjomphmcp.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtdzczsfbb.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtsboutzad.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtguezrchy.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtkppltpui.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtqzcdrqhx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtsplnseas.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtttecnrwi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtregkxttd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtnnwlzksb.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtomtngbuh.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtfzshkdab.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtyekxxfei.html


<!-- 参考信息 -->