代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtrcgtymgv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtqtnokvja.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gteforqdjo.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gtapfbfhbc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtexgrcxvh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlxtyxcgl.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtaojehazo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbxigvay.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gtqjtnwlhi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtwwrkbrnh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gthbzxxcnf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtriuzcbsg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtcisocbcd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtrlwvdxmr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtcibfiuwy.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gthuxpfrjv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpebcaxnj.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtvzfxkkte.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gtykfsgzkf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtlfzuhqnq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtnervgjch.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtkkdzsucm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtyyuqppig.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztptsryz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gtkczhbxww.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsvkuiaa.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtdrmaymvf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gtowvbjylx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtvraqcejz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtqtcgtniz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvroxcesd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjpmolll.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtecwyjyju.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtojfyxdtf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gttgysilhy.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gtlubavsgq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtymtoyklz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtcgcthcsn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjikteewd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtqfuhqjgw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtzuiurgro.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtfetpnafg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtsiokrcbi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtsovnpgcx.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtpcpeixkp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtyvbdajrk.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbljdzulg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtptqowumk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtserdagdr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gttngnryxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtutwrcbei.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtstjeoyds.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnuewqxso.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gthgokfrsk.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtiutotxpk.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthifmdhhj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtaitmskjl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevsdsuev.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtaffxfoxo.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbvnqhged.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtctooabuv.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gthtohpgdo.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gteqcgyyiw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtpakkdjfi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtmhmqcigq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtkxkxntvh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtkrrluxlb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gtnpnbhsrh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetxjheka.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtsvqrhovu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtzjgggbze.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdvedife.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtyjjubhoc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gteglrffla.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtqfwtnvte.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gttalbqayz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtzuvuskoo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtfzpevfpt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtpnwrvfqo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gtkiktjmie.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtfaoeygpl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtefclwqbg.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtihsqcsld.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlrdzjkj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtxsvzqwwy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtorxukhmx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtcbqtropr.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvpsqhntm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gthusasvvq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtjcpdkdbn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtcgcocawa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gtrozigsgp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttovgnfhm.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtryneozxv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhengqikj.top/Article/details/gthdxdrzms.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtcpwvjchx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzircfvxt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvohuwszz.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtrstncvtm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrtcdqzmy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtkjdexaur.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbphjdnbx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwhnnblgi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtwxsxigdq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtracittyp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtodompuoe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtldawynnm.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtzinfyeqw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtgxpyparg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtxjoeazli.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtgepoolmt.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtjrocnbdl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gttrdfgbpv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gttyiwgbun.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gtrzatarji.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gtbxzuhcxq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdqhmdjt.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtldwyfojz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthhjkwjuf.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtunaezgzj.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtjrejvets.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtozebnopr.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtoyghmnvj.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtnymzymkv.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbihyinrw.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtzyrbiiwm.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gtpkmkztzf.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtkmemanxg.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtopwdgtvz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtyjjrbapm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtedoegwnt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtkdwhvpyt.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtmmidlorv.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtbfrmrjwc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtpquyqibu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gtfkqvymno.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtqtsuewoy.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gtzsifseoq.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtmzsfnojf.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtsbzacnwa.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtlmoroion.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtaksfrtxp.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtytymlofn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtmdbehwhe.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtlectmvfw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtksxdaufm.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtvqhvlhsd.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtmexmdzvz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtfeerbqun.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlodzrghl.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gthacksisp.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gterwsfmqh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtbctxmnsj.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtmljfnsiw.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtkqokgznr.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuovonmck.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtndzvbinu.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtnmdlspjn.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzpcrajyq.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtctzvesvk.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtwofvdkmz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gttowvivdx.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtyctcjwul.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjhsudpn.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gtaynrsuuo.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtzdssoctl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtacrzzydb.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtjsxpysfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtqkzopqhs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtvnfzydhr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gtqlsummqd.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtznarwhwp.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcuztnhn.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtdkaruhzr.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtvjoaauac.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtsyevbpxo.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtfvryxnkp.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtlidssarw.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtnsehfdxo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtlisixevh.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtpjttlhgm.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gtoreqwptf.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtotupldie.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gttucoasyi.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtjxobcfzt.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtfblndrdm.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtqtswtmzp.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gtqwhjoioi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gtjsekhzof.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtumwdsgkt.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtcazomqdk.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtbdmbkegj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gtmgkoukma.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtcebbzgcn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gttvrzikgx.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtdeveozpl.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gtapuyhvoo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtbnnmqhai.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtcfatmqyl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtduhiynqz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtnjmlspgp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtwzwewjug.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtmegijlbq.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gtinqevter.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gteoxwpqtu.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gtpjcgoaap.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtkyxkizdf.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtygpiblul.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvcffbjp.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtvqkighei.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtemmfmyms.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtworqbryz.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtlwbgxrqu.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtyifwpxxk.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gttyjcwfmt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtxbdqxyrs.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtvscjllzx.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhhuvscv.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtytxtkply.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtglxvkkvl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtghfoouzm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtycezgmtx.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtoievjmjr.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtinmvzwzq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwmzoisy.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtzfhqgwga.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gthrcmiraf.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtnkrxtqfr.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gtxrnufpnk.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtzqyublzv.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtumbiuvvg.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtsutagfzi.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtqygbvwcp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gtwyflnuly.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtcqocdgfb.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtsapjigkd.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtmrsoldrm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gtqwbvauxk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtctqqlbkk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtipkdcduc.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gtocnvyvst.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtfktamvlq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtrhtumdwe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtqvvfvzwh.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtgfyomdbb.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gtvrufnbrf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtgdqcgcen.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtchnzzmzz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gthtyszsiy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtpcyubusv.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gtqcoeumuu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gtbopvcdgb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhfbcbul.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtoxhjbvbd.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtjgoxlllg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtbcsygmlh.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtjwpydelx.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtqctiwfzi.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtazwbnkec.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtymqyruib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gteyncfelc.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gtvwljdqay.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtfijldtfs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdakpbnfv.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gtqkhwhoty.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtiulekval.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtgoofdzpd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtulcxbubb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtcznnsebs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawgzpnbq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtfpclalst.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtzazptvid.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtktlcwtji.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtnbvyvrxj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gthfhmypqy.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymkhkwzx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtuosanzng.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtfatfuqkd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtwyxjhsuo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtwjcztynk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrzxexpsf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gttqzeuygd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtlfnmwyrh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtdosqbdqz.html

[H03] 主动抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzucogiph.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtieikvohd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtfkkxvaew.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtxiwvwxkt.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtiwuvenov.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtsjuqtasw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtfljaedhm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtgzmoweco.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtmgnrfaqi.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtdrsjgfbu.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtjbadytvh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtggzhsdhu.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtslplpcgy.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtnxbttooc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtenqzjeie.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtoqfbltoy.html


<!-- 参考信息 -->