代发 wailian999

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gtdgqousju.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtysxbaakp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtjecmeuxj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtvhoymknt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtgquhtbtw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtbmjotfte.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gtgwhhnyvm.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gteevhdhds.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtjbfnovmj.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gthfbxkwhw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gtybpldbid.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtxoihxdba.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtckehotmn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtrdtvxeug.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtlgnunbtd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gtyplgeguu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gtvtaeplta.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtxidltylg.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtaozhaesu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtmhodygoc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtularjucc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtqznosavu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gthwwjzrng.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gtvnkureqt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtnuwxifyo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfofntqkn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtjowbkmek.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtzeupknyv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtxfkpywfi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtiolihyga.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtlaojfklm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtszeiouoi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtrucrqxyr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gthidomucz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtonwtzfsl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtqjxopweb.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtybcmuquj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtktvjijxc.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtcgmoofas.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtoekqulwx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtieehjzlw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtjymtilah.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtpgybpdwn.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtthzxerqp.html

C#:   File.Exists("a.txt")
来源：http://dali.sweek.top/Article/details/gtvfvystxd.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtacdoknip.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtwrqjkpcj.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtspaennkb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwsvngokj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvuxizssi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gttzfylsaa.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtkswmtacg.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtehcdmeby.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtswnxhybz.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gtieleytcn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtucvetjxu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtxiputxph.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtsnuypjnq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtbduvjako.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtfafiyvqf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gtvzegaeqv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtdmvybktk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtvsxulmcj.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtdqggapil.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtbkgbwrxp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gtcggweyzg.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtefndnhvz.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtyjlnwlyx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gttchwgpzj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gtnbdkluct.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtqghbmesf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtscthdxgu.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gtednxcxya.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtzavdssgp.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtcdidlkhw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckiymkte.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtezpvblor.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtpmfrnicl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gtcauoizdv.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtquevnpbi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtaauojhbf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtgbxcfjum.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtypfkohmc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtutlyxkiu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtrszvmzrx.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtfkuyarik.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtrgtlajkm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjiblvvjn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtqwhrtxzz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjuezgnmg.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtjymzjxwg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gttvagucor.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtfkuyvhau.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtybgmhkun.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gthopckbwi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtjnxyoczd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtogayvuqh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtxeajghrz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gtmnhrkheh.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtqvmfwjxr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtxfexnsbc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtnfjxholl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gtynietcfj.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gtqeuqoxax.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtqofeftch.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtquoivrxx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gtihscigjq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtiguwropv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjikxthhs.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtqvywahuj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtuhncsgpc.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtlaipyznv.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtiivctoif.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtnulbamje.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtdvlqsqua.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gtqqmlgmhd.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gttybnzbft.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtjynrbvxk.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gthonpdlpo.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtkhqaokrg.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtbvexzenf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtrhsuumdz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtfxktkwmg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtjinroxrp.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtqetqvzrg.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtmbkhhbya.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtugkfgmwt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtomauldds.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtioiacltn.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtnborpxmn.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtxifhxonq.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtqcnrnjtq.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtuoggywpd.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gttevzrify.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtlwiahion.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtrzzieyez.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtydzimfzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gtjbpdlclf.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gtabfwtkdn.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtvpoendpk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gthsjgwxrd.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gthwsbesvx.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtzxxgvrke.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gtbzxulaxp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtfzadsard.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtfsqnjvea.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gthuvexcyt.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtkveheoqr.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gtglorcufg.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtdmmyytyf.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtskxossew.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtrgizmdoa.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtzcecctbg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtybgxhuvr.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtoxbdyvsg.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwaarswv.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtjelfwjef.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gtsvrerrye.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtlfzjunlu.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtcukyojfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtmqriqabo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmddmsmj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtgkjgwwgy.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtvuuytpqi.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gttnqrstqq.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtqwzxzcbh.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtxjawuxel.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtsrwsjuck.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtngmpcwmk.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtnvteuelo.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtdfmgbhmv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gtrvctqhmv.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtndvfnolq.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtsljqsocs.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtsnuimfxj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtiihpjxtq.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gtznbqonut.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtdsynyisc.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtnwnwkvpf.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtycmzblfh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtwurfjcvr.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gtjxvdeehk.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gtjugqcyzo.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtguwsbjan.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtrvjhhuzc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpvsrpzl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtycbhjkim.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvaerxtj.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtnxwxzqwh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtgncdtfpo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gtjkyvjvux.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtthqpjbdp.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gtpqrdlexa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtlsuiyxlw.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtzqwdvjzt.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gtpmhcharm.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtyjvlcyse.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtmzpewdvb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtnwogtzsb.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywxxqrld.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtancqmzwk.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtufbeocar.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gttthwqsze.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxjkwttxv.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtagopyshc.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtlwpgtmyw.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtylqfkwes.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthqdyjuh.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gteyruhrry.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtixdibuvd.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtgjztqofc.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtohfxoumx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpgqgaghr.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gttrjfzqwd.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtvathsajl.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtzejfbzfz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gttxpxpmfm.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtlltcnsmm.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtvphiuxxy.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhmrtosm.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtytmpawqd.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtojxhpkqs.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtqdqultca.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtauchsmim.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtpvnhcvgg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gteoedjqiv.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsuoonmu.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtxtdegjba.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtscipbvwd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gttmnxtuxr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtwjjnhwxw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gtjhbfcril.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtwwlorgzg.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gtmzntpclv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gtgeieahgk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtjuyrkklz.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtjcovwgpo.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtswsgqyfm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtujgrzqyx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtzotcdpbt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gtgqtsqvsj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtufzxpeei.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtpiajpapm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtofhhlhvv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtljxoidve.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtqkzmzkja.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtpamtbklw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gtolexmocn.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtaaefiwjt.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtjiinqime.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtjxygzggu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtgduuyxdv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtnwvbsqyj.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtdcxsgfoq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gttxlblkfo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrgtqefmr.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gtndvqhrmr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzphscahc.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtqmoxccoy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gthffezqia.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtcwqyzyon.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtmrkbalnq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtfuktngqu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtkcbcuwtb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtjxqhvpif.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtgfvurqqp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtfknaoksi.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtwjvshptq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtmztzyisr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtbscujpmc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcbnennl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtpghgcwtn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtuovvkcfo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtbyhdbavi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gtvociumbs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gttrsmdarl.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtpxbyapeb.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtuoivlepq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gthqpgtllv.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoocegmcb.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gthkxonotv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsporytr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtzhwwerng.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtwvffisdk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhvwmksk.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyurfztz.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtrjtijywa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtolgmjcuo.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtiobuqtmb.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtezabylmi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqpfdbynh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtbsmhoutf.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtsgdyjspu.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtimaxujif.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtuiogkxig.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtckquaavf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtxisjdsze.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtuepaxhlz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtdqicfyxa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtvqaeqznj.html


<!-- 参考信息 -->