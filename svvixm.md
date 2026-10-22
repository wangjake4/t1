代发 wailian999

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtbqywiwny.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtlgvehmxr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtciolljkf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtxiqymosr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtdcyxjiid.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtsfsgqupl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtqvlqzkdk.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtscsxwzpe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtahbmxyjd.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtiicvrfhb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtrztprokr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtnhzptich.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtjoyjsdmd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpyxutwwm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtgvlmosbb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtnbrxomgm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtjfvveejo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gtlasphdjp.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtikjouwuu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gtfmqknynq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtsehdbrwf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtpeuoczgr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtehnlkwra.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtjjadwuoh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtxkxkytxy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtjnzeeyzw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtnulceavv.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtugbxiksj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtkmbkxwbr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gthpbgomvh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtgjwgzbpj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtmxgtsezi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtuersnpjr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuesdard.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtwqisigbx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtztsvodbb.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gtxyqgaaof.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gtctmpetnm.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtyjzrjbya.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtgsgppkac.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtddcvkrij.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtkixqqyjk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtqiyrhvhh.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtvzpamkkb.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtprjiwlgn.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtgjrbgxag.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtnamafokm.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtjofzptsy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtbhhgtpei.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtsukawchv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtvvfelhzv.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gtwdqoezks.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqyovckng.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtinwxpplq.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtildzbzxp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtmfearqhh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gttwngvmtb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtgrzgoglw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtbwqwedje.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtalnaywie.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtqumgjhps.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtixxwqnim.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtwtlwajsp.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtuwbuoqwc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gthzeyoyll.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtictzzrwe.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtfczewzjv.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtjsjhouhv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtspgcwtfy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gtqqxudfzz.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtfkdctaff.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtoemalmii.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gtarbrstcf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtovtqeljk.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtxyawwkpv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtvsxepbkm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtrfkjmeas.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtkvyhpveo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gtwxvuhxkk.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtebbvyabj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gtdkcskaeg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppjmjglg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtajwkfexi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtsrzewqgt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtzfvbiury.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtisbreqfo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtiolldftr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxdjzpdjb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gthbadeyne.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkvxekxdc.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlirrbtyd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtvznjhawl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtqdtubvzd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtiwttrjhn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtqrmamfsp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtqdpsbcml.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtfhxoecln.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgrwvjms.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtjqpdhjon.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtnfddxcrg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gthnkbpjrh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtbdazgxil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtrdkvabgx.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gtbpqetmzo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtclaytvqf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtypexyboo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtcjriwfoh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gttyjvvdhl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnfyrdebb.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gtsowjrnva.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtszcdfjcn.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtywmyihbb.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtuabwoktk.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtidlebjlv.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtugmgiqtf.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtqciwqpil.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtxiejbagb.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtsznqixhr.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtiivaqytw.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtiqazdtpy.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gttmydkvqi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtemwrmesu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtboswhhqf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtqefkrlzp.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvltkdthz.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtzhipuhte.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtqlxvzlmv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtekjszgoq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpbgtsdx.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtpgztfuzv.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtncynikge.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gthzxpptrp.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthokimgzj.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtjphahcky.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtcuolbhvr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtohssyidq.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtnkadotbi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtkxctoufl.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtktuyqwqf.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtflrneodr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtyovyxadu.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtfnjwygiw.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtjdvqccot.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtgdbiesxh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtaykuiono.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gttxlgaslu.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtditnwznn.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gtjeosfffm.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtuvsgwdui.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtacndqeqz.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtiaeuilhs.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtrgnvobqv.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtjyfcqlcw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtdstfpjmu.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtioqrivye.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtiwofdsye.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtnxdnpvee.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtbjoowzyf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtygvtrylf.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtliequxic.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gthxmoumbx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtqntzlucy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gtkmdvuheq.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gthnktmzyc.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtntfehvez.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtltlifbaa.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtcshkcwxi.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gtqnkcjejc.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtqzkmogbj.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gthmfylpbt.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtmkouyxgs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtyhbxwhak.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gtmbkqglyn.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gttmfueuwb.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtxnytuztg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gtfixpjlqm.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtwvyqplfn.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gticpemmvn.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtagezxorx.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtsmrcymxd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtglmrmsgx.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtpjhxatnw.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtxcsbbazs.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gtgbyftqbk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gtreydksvb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtgzapdzhl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gtxqbcsxmy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokwdzqdc.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtaqhuxdwh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjkdnfny.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtvxfkzxgx.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gtdlriveio.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtuykgfskp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtpdtqssnz.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtluzwepkk.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtvlgpkvim.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnujukdpu.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdahkymu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtlsidsahh.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtpqgqsugu.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gtvxxtmzdd.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtxdbxshsh.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtircxvufp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtzoaufcfc.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtgycajkfg.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtptivcpiq.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtmopbcwez.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtnvmqxpjj.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtqwgjxpky.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtcunftlja.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtfycwasne.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gttlgkzlcd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtnofgfwbv.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtlwycsbjb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gteeyskkwl.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjovbkbrn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtskmndagt.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtesgiaakv.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtlhxitlqn.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtfolbknrh.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtgqowsvsq.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gteolofdbj.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gthijaibdj.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtimrzjxmb.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtspsymjax.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtlwdhixwd.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtuifqxblv.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gttuuxzlyy.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtsofeugxt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gtvihfffpe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtciuzyhhs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtalcpmaiy.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtwoojvgbo.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtfqtsawbe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtdfiyisfn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtnshpdhrd.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtsocshiyx.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtcyvsjzic.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtwlwfcjju.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gttgauzgsm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtfrtprglv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtmnnxogls.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtjkxjjnwj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtxterkygf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilyfqvtr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtgtdgxtbk.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtkaqdqsgc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtldlaaakt.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gtdekrabzz.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gthdodovsv.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtsskczgqm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtsqrirhkf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtcbucuhcr.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtswflggst.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtpiwmvyyu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnwbbdqcv.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gthhxgwoie.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsakshtfy.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtjvooyspa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtsgvkdatv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtqezywhar.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtqtxvzejm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtoxkymqoo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtpcyvsauj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtellrnvsg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gtlanhivyi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtxcpcyzxv.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtawhmzhlq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtkxplisqy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtmlxmvkpv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtihzmsbzw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtspgkpjjo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtrrpylimi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtcnbhworo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtwhtcgggx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtzvjnehls.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtujbgdqmk.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtmtrskehw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtengxkeep.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gttwxpsojp.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtubnmijuj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtzgmhrywt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtxitwrlmo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtgsfbiwep.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtyjqansvg.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtvtgcvgcq.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtjutzxxzr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtuuizyrqd.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtxjbveuav.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyqkanliz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtqonnpfwl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gthvxtegha.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqylmkaog.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtdkvxnypn.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtsyjlglhq.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtmrkgmild.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gtwibjwqeq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtmogcprvl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gthchyrwuj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtesfgyomz.html


<!-- 参考信息 -->