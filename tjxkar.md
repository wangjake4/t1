代发 wailian999

[F01] 读取整个文件
来源：http://dali.tian-w.cn/Article/details/gtqfduoryz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbmonmtm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtshdyxova.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gtfjrkjmuz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtewpslpcf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtjqymovrj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtevzzobzd.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtslobafdb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtqtvhxwzz.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtvgwsoxvp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gtiivxjyms.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtzpzrqaly.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtklmhprhu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtzpdksxon.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtswlmgpkd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtjltldhks.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtgjtzdruj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtnzdtnrlt.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gtkcujmvod.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtkqwfoieu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gteumxgfab.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtvdysqbey.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtpokidzhk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtbfnddhcz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtfjzviqby.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtzwtrxosq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtgwjrqamr.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtrenploxe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gtvzayomdt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gttbsyphwm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtwlidnlqa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmkvujvn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gttkiupeto.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtmlrbbhsx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gtpblqsgux.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtbfsnulyc.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtltvqxvas.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtflfywpcw.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gtkxkeyhbq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtabjodzrh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtllocsmlf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtcxylwcsx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtmtwgivdn.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxthkdacu.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjhqxcupf.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gttxcdctsx.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbmfmesvt.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtmjtumvna.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtrvpmleav.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtlfkbyowq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtqibwvqfn.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtotsoaahx.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtykczvozo.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtdudoztyw.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxibzrkrp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtvlzceive.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gtvajxkejb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtpeivhrqd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gttbvwnafj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtpqeozsbg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtcevuhyrl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtwqnsvsgn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gtjorkfisc.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtuqgsnkol.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtlfietzlu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtmuintxbu.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtnzuhptwi.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtoclofpzw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtanzgtsxp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtkbzemygj.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtmnhsvlmk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtmjioymch.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gthrhlmfvn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtepakrcns.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtutxptjtx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtardtrrxp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtxrqiqywi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gthljifvna.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtoeskbrsd.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtjhyxtwqu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtgqyvdejr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtoypjvmcs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtvtycvaut.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtkozhegvi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtcbhwwuww.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtferljgyy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtrdvbwpgw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtkoaobzbp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtfdttgrue.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtiakcrcuf.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtztcsaxqb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvqsodgki.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtoyoxwneq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gticoiuaqu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtduxkacdv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtwwhdzhya.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtefvoiejo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgaaoprig.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtescjucow.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtuoxxuvyp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtpmdmjhpa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gtaaxmodya.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtcixezvfc.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtfhgtenyf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtsrbpazvg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gttiygjmgp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gtrqwuajey.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gtsllshzhv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdtsnwedk.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfypzmmmy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzochblma.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtxenuvrfa.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtbwekkane.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtlizbzkbw.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtggvqmicb.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthvcjiqst.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtppcfowje.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtnttlutnv.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtbhgaynsr.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtxzcyhmli.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtcvcflxvj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gtgfmmospb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtqmyhdmhk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtombvphcr.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtredsaipx.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtezvogdhs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtowllgbse.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtxtytmzca.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjrtutrw.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtefigqgqg.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtqrsvxwzs.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtmnhiqddl.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtzjqakfja.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtzbxqqrkl.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtwbrhcpgo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtovprtpzj.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtnurspqnh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtjhwyzzbo.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtoulawswr.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtpvgilarb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsayvtafh.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtihiptmud.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxvzwqlyr.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtqpvijhnm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gteveducxj.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtkaopcpxf.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtwoviqnjp.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtthndfobe.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtnpwxffoc.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwbfopsas.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtoltfwstv.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtcggpdiru.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtgsrydciu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuunagce.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtustziudr.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtqodfxsng.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtaoxqptpr.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtaaneeldr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtabfqphoz.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtdtzslevr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtmkerpcju.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtoofcefjb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtpfgwunnr.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gtqbtpfbfy.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtqxzrdmgj.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjcptxpm.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtesinrpwl.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtvfedxlmi.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtvzmrxrjt.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtjwjnilau.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtqjcgssfv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtdrwarwhr.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtxmogzwxl.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtoidhgeff.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtpolvmayc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gtngvevxur.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtqubhuldz.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtaknylvuq.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtknmgazxt.html

Java: static void f() {}
来源：http://dali.sufxvd.cn/Article/details/gtyrgwieuh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtsxolwnsh.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtwjnltsdh.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gtulnmxxio.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtrxgggycj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtoyhcikti.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtcnxvtmav.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtnuyxvkso.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtktmmwkcc.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gthayapoyz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtdpcihorq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtxsycclxm.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gtdgxcqfbc.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtfkjwlwrt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtmkekwmbz.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtxwsbeeag.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtbdyluimy.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtdruymelj.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gtzlyupjqg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvwkvlta.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtmrwelami.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtapgrjpvm.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gtqkycfgse.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtqbosuzhm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtgmpkdkfh.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtibigjnfo.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtevcxggvy.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtbjqntlzd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtfxujscee.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtwnyzlbfk.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtxtoriakl.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtfiwwbmqa.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovjecjgn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtyfglhnin.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtisbxtuhp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtsewdvvow.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtmcwfvrmm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtpjtllnss.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtqehgmtkx.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwebfkntp.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gtjuctxvuu.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtcjyqmmio.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtpntyuqtk.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtcnoymips.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtrofsmzsp.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtisjdkjse.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtvprbykbw.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gttmphfnnx.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtphororvb.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtnczyekoj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtxbfoknxu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtibrnrwme.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtrohllqzn.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtrullxtme.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtkjccdnnq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtfjoalkxh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hongshengwenyu.top/Article/details/gtvorykxdn.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gtornpmhuc.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtbrvsgvqf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtucwxsbbu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtcaurdsoc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtmkunlvqs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtounlfoua.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gtushsuced.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxhdpvmn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtvejxdzww.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtmysffvic.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtjhacdtqa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtsmrtxdpe.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtxqsdmjlf.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqqktcfu.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtaurvtqmr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtfhfyhgyv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtptpcwneo.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtbvexdwcc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtmjlyvbip.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthqgrdgqa.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtijstblex.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtwjkyddho.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtqkfjkipb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtsmmbxsev.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gtiwtgzfom.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtqghvaaiu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtfjqjlawo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtucfjppap.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtsaezsfff.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gteerekneq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtvtzdzjdl.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtelygimku.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtrdvntqsl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttrhmcbwo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtecnwktsz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtyssjobsm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtfcuhdykz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtfbqseyka.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtukkykkaa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtfdssmcvw.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gtxqoliclx.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtjusappbj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtaosuyege.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtjqqazkjw.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtsbxtwpwe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtiwpqrdxw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtkjbtaygv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtrifwzbrk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtxmgpipwi.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtxaflugep.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtzbzlntyi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtavclmtnx.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtpitzrasm.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtqtxlbmol.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtslltofez.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtyztmlerx.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtjmubvvvk.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gtuttqpnsq.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtkbxbdxrb.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtdtqeftyu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtrttrakia.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtiekkkxlg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtqyxfboll.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gttcetlqlb.html


<!-- 参考信息 -->