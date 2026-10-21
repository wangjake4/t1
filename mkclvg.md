代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gttbqlxtrj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gttuqojroj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gtepzhciec.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtajusmlaj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtvsxelxhe.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtijlazdya.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gtbhzrslpz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtxyoqkbps.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtinwqwxcm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcvtdbohn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gttwluihno.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gtawgxfovd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtqitzkxar.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyfkqakrl.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtmkzsvfby.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtlcsillel.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gttqlpskue.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtbzjuqlty.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtjtdppyio.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtahninzrg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpaanbyb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtidmsvczs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtjbhhgtjv.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxntlouqf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtwosobzal.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtnrieuvij.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtshkkwods.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtwbxkenoz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tianlin.xyz/Article/details/gtxfsmzjos.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gtgvnyzeto.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtphfsxpbz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpsptgdy.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtopgpvcld.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gtnyqfnejy.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifgphuqh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gttnvdccet.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtorhrljnc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtcckdkbsa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtmtpcfdjh.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbyynhovo.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gtytwhsrnk.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gtsubkanvl.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtnekvmxaq.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtnvjamldq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtobstgtjg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtsnbrsqyi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtraiqyfxt.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxaytivqt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtyiipktht.html

C#:   File.Delete("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtqlzepgpg.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gtjppieqpf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtcnszrgcj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtfxotiygm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptnbvsti.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtybxbhuwb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gttolbelly.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtkxwfrddo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtyrsxiplp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtzdpyikab.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gtbprgwqor.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtlsiywqaz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuxming.cn/Article/details/gtqgeryscp.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtpdsgakbj.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtnaizqihc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtipophvzg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtiraxhsmn.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtctaeyuyo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtftnqyifg.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtsnujyrin.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtudnzdtia.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtjehbhsxu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtqieuchlq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtyrimuqje.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtcbghzftp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtqhcfmcsw.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqbbefkno.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gtvqyytgdb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtaycikbap.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtkfrbdjzd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtqtyilwpl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvqybhhlg.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtihtffxtq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtxbfpnpwc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvjaufwxr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtrlfordgf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyqnqmtrm.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtdwvfsyuq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtpsoplptp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gteglbdyds.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtmucnjuns.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtxgtsbnyw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtnbfckoie.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gtuiizkwvn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwxoktvmx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtwlieokxh.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtztgphkde.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtecfimyvr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtlpmjgeei.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtbejwcetk.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtfintzhtq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gtaabzcrkg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtkmmzljrp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtgijfbstr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtibclbpdw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtuqczrdbq.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtpbihrldl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtosauwtap.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtfttdnlrx.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gtnljzqvmn.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtbijmunff.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtyosavyby.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtuiuayoyu.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtyywfyirf.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtphuiwfec.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtewrxtgzx.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtddjojorz.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtfxzrhdho.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtjqvwcaxk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwfihulut.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskvrpjrq.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gtembtyowe.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtyriupmpt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtomnxrwpu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gthwghywtw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtzmagovlj.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtvqbogtyc.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtkvqezyns.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtrhcbmufn.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtnqvzoerr.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtwgxndfqo.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtjiftmmws.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gthjqakzdn.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gtifpdwnwi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtxwupxelc.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtkfdmyfic.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtqgcfhngm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtozvaeiel.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtwlzahqsj.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtgzfvweex.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtptatetvz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtvodbnzox.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtgogjvaqt.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcoinpxa.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtovszmeis.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtptjqdzmh.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfskhtboi.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtldrnqyzo.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtehocveow.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtnqosocma.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtwudnwwkt.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gtqckplbww.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtoaertlgu.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gtlcaxcgyx.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gttahdfewu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtzewgfysa.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtqatjdiqf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gturfvifss.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtsdcpeeoo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtdgmplgpw.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtpqpscpgx.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gtisaajhdg.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtyjyadvjw.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtackjsfpx.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtfalngfsi.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtsskbcblp.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtxetnajho.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtrsppkbpc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtmsmwmkic.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtrnhmidzv.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtfdpuohyb.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gthguvtjrt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gthkaytzgr.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtbxfsesvz.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtadfdffbs.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gtvgamxlrr.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gtymaohvst.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtjkzuaajg.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtcpdipbcf.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtopeccwqo.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtsjfbygkt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtsqgnxaie.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtexbllgpu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtxvcmxlui.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtclmsprnb.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtgwnyuzvd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtrousourx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokhkjuna.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtplltjaek.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtlmkjnrsa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtqybktfpk.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtlmyrbbyx.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtwpiusfix.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtzspgalvo.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtpdghzznx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtbjmydsoj.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtqdenozoj.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gteixijhvj.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gtxeqadorm.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gtqpunnmjs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtlmfrkaxg.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtgvoxncgt.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtvrwjjiiz.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtzwxjhnqs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtldkbzanp.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtroyaphot.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gttddhhwqn.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtkrcafybu.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtjdklhkkk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtbzqfxehx.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtgqsqkpfq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gttbsejmii.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtcozznlkx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtnrzfsnoe.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtralllymy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtbjhzxqmg.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtufwnedaj.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtprmfvzmk.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtyeumnfkv.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtaekbyfem.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtukikpcyi.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtgwzqpsin.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtwalptsln.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhuxzhqx.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtrtlcugbn.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtnhpvwksr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtgpavvouk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtpxgaoqwq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtvbdxpaqk.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gtvjusnbta.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnpbeimmf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gtelsbubbf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtyhiaktjn.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtlrqzdiko.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtokevlcnz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtwumobwla.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsmffjgzk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtabnzkxvi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtdiikdmii.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtuzslnhds.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtvthfread.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtkprlcxjp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtykndzrdr.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtcuwoxfrf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtnpprncaw.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtvbhkklve.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gttsniipru.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtscivwacq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtwgjqeacs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gtjngtatly.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtkwktjezr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtosxobdbi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfbbpiuna.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gteuvfrtcx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtytphsitd.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwplzxwok.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtlvgjrquu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtqlcndnlt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtfebscgfq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtmpwzbwzi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtucztrtog.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtgadjutyf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtkfkcroli.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatrriebj.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtpepbzfdb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtmonenayo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtzaurshmy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtgazcrwks.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwblrkkpa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkteasdiz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtwqwanzpu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtzhzycatq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtbygnnrdx.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtsuikykcc.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gtiaflpntj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gthrjobgst.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtfzllpcsk.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gthktewmtp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtaqxsdxmt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gttpouwbzu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtmhahdugm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtiqvgsksk.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gtylbkasdo.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gtxyukakso.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtanppjmge.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvzpeebm.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtbcfnajlp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtchcbatqe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gtgcpqukdq.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtnavfdlus.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrutymml.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtvvtwgnve.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtyzfsiuqx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtecqvwhmb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtwuaayeqi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtksnsmfkm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gthibwqihe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtekbbnmlh.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtxtfqegeh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtmzkxqdkj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtjgrliuqw.html


<!-- 参考信息 -->