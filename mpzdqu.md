代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtzqgmsofa.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtefusqzyb.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtngcpzfcv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcuauigvw.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtoxpeckbb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gtxgpoxulc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtrrkcuhgc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtuerlrunk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtfdypfokl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtabxjmgkq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtgtiwartw.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtisdnppmv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtwemretqc.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtxmgwvwsj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtmoovsqft.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gtjyhmtebn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtiumghthj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtadrokbxo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtfibiqjzr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gteludbzbp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gtfenumiqz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gttunaekuk.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtuilujxbh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtnbgensem.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtnomylipo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtmapcwvsg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtdevnhcgt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtwvsiejks.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtjztovnnx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gtckpcelsx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtyzhsmeyr.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gtcaygusyy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtaehqrypv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtkniqqruz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtkexonhbg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtkffwykxf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gtrgirmjvp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtakolrhzk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gtocpuhvsz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gtyztfmjdr.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtrmskvjjd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gtfoopulbg.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtzymzfjlz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtxgpgttpl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtslefaxwo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtcammjafa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtxbljwmat.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjjdparrv.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtowatilis.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtnykfajox.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtvnqaxwna.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtfmbqph.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtnpgbbetl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkpqtiumt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtzmzikknv.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtiryopdhu.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlvevnwvs.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfeidumrg.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtjuzwcrbp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtaegrykzf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gttntuzbeh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtlcopsqix.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtpbvqgveh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gttblvajvp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtbfkeuzil.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtyqzrgpyy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtdbmuoxxw.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gtqsrbabfb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtzbjgkehi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxglxqtoj.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtrkpmjbnt.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtvgherhmv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtxmwjhtax.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtmuuqglij.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtvdxpycyx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtbdvdedsm.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gtycmhgnlw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtddtjpdvt.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtfdgmdsdt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtufsunild.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtfgwsqpxn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtuzlcewvs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtvygkbaif.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtedjeufvo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtmvegpovq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtxrmcbsuu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtzmlyvmnk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtmoldpbef.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtzxuwybcs.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuykaimnh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtikevorzr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtkbvjhpdn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtuzfwcclj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtphyyxvgg.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gttbnriwmb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttqkoyxqg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gttozxmsjv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtoknugdjj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtdtplutvh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gthicpknqf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gthkftbgib.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtehyftail.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtkwludrdi.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtbcdkobzg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtpdtldnko.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtnlvcckos.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gtychjcpuw.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gtupnnuiey.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtfyyewfhd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gtubwmpvvz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtgryoylss.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtajqgjkmb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjsbmbpvz.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gttqvqkzga.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkejkimoc.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtijiktota.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtdgsherxu.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtbacvgndc.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtxqcrzstz.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtgeunzunn.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtvhufadbs.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtzvzywiir.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtxbypezid.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgzvqyia.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtuztsruna.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gthuitsjhn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsoycfvxu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtueyzdktn.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtdsntlish.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gthqnufual.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujixvwap.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtjtluzanu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtkhnmdpwo.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtluvuwhly.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtngmycisf.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtrckezzyc.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtohkzaexx.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtnaetjkfc.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gthdpmuinp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtzwwjlvmq.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxpxwapk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtgajqnhiw.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtiueocyov.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtfjrhbgbc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtsmpksoel.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtvxchjhhp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtkjovujqs.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnokfnmty.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtomttyxsh.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbsqjaai.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtbfhwjkrm.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtznarcycm.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtguzoncqq.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtngncznhx.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtjowjkgoy.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtfqhraezd.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gteultvhzw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtzkvnnvlf.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtuvxmkgzm.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtvciuwmyt.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtqvisdqxk.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtqthdnomw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtiivabmwi.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttdxxzxvu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gttqaycwin.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwlwpxcgn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtiskzlnvo.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtxayawjyp.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtvzaghlnh.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtjhzoyinp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtgqzvhbwr.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtcrjyynvx.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gthkijptdj.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtrwsvsyax.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtgpexbuwq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtzddplibz.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtglzfmtbd.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtjjoisllp.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtlzbjucjs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtgfeixbgq.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtatdbkwpa.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtsmbxmwth.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtjkorheod.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gtdejjucss.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtpmpgcspw.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtoejoecyg.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtaomvhaby.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgypdcpfy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtjjqqarqo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gttrkxossb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtvgslvosm.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtkbytejsd.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtfzxtpqxa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtryobnqtg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtawwgdeib.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtdgclljra.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gtltlkepjf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gttvmltbkq.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtstyhidwb.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gttopzszbd.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtlpslruwk.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtgrklexln.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtdlfybqwo.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcvqriao.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gtprlslisk.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtgkrthykz.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtnefynzqy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gttdlxurqk.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtjmexcmaw.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtrwuljeyi.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtkkhpzezk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gthvjrojha.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtfrxkbitm.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gtqqyapzyh.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtoaguoyjp.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtdoleecau.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrpkdcfy.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtjpulmfxn.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtfexgepwz.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtwfciqrkc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtexmeanxi.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtnymannnr.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gttdwafxnk.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gtwyrtwyxs.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gtefqtijom.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtdtexdbbi.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtocdijshf.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtfjsvfggi.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtgkioapqu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gtulxtvxmr.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtrgzgohmq.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gtgppqfiau.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtsvkqvbir.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtfverntom.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtlwcodoct.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtvjfagayr.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtwyriqtnl.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtitawjzqd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gthwobkpvf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcmgvfrk.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtuczhiaya.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gtfeduhedn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtbhuxdbbu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtrupzfmcx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtsxkvpflr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtfbmlnqum.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtdbypjybj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtjixmmijg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gtkjbnzhii.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtpaeajmlx.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gthxvzwgns.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtvhvrrwze.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtgnanxhhl.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtdwvjjjgh.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtvmktavvl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtztxdoset.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtsbcxooge.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtyyhlkksh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtkppnwnpp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtplzahdtv.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszmaysdt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtoinquyqd.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtoggjnpln.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjtpkklz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtaaylmyty.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtzwqqyvta.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gttncrrgtb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gthrojsyvj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gtahwthwyz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtarbfjfsv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtdtvbovli.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gtkvqiwfyi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gtjixlpifm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtbrkxorgf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtcisyiizi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvovjgrph.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtcrnbvfkf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtycmsbwub.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gthvururjr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtgteaavzy.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtxryuxrzj.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtbrrwbltj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtffgacqxn.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtkiuriuxb.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtlopgbihu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtydpxakol.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkscpkcts.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gthhapnfrh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtxileudvo.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gtqotbycrx.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gtfdpbwpet.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtrgqjsktp.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gttpikuokw.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwiviuiv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtrhpvxrmt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtwhdfqbun.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtclhrrhjo.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtdekzqter.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gtkjejqaot.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcnlemed.html


<!-- 参考信息 -->