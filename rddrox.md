代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtqqeuvzwt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gthoypnzio.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtyaveekim.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtvilfuagi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtdztxgrxx.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtnumhaaue.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtsqjuaiji.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtmuwpaaxr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtrwoxsfup.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtrtuadqkn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtvniwyuya.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtuqwpadfj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtlwuoytos.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvhiyvstw.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtiysczypb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtbyqeokgn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtvdochelr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtaejevxns.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtgrquhrow.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtvzyfurkq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtzkejythz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtdcqpeane.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtgkwcjbew.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtyyivgjld.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtnaoqozyu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gtppkvepfi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtqplklaai.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtcdxodsvn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtslcdibxt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtafxeroym.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtkqwqgxqv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtyhknubse.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtfoztkfgn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtoqttzhbj.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gthtyicjsj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gthusoypos.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrvnxiamn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gthyclyhtx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtrvpvrydw.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttbkqhfis.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtzckuiruu.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtxyqvmdsf.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcrtgmss.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtkomaeoqd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtlwrkffne.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtazhuaveu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtmbjouztc.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtditxyypz.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtisbcodvn.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtqaazmyzq.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtrhgghhge.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtcnktkceh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gthgsmancm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtuangtjer.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtebjddgri.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtmiysdopw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtniqbabiq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtaksldgxr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtztfaixtq.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtkasmpsmn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtetwbeeaz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcurhagug.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqusbhdz.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gthmsbwset.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtxumvvjpy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gtdtgytzrt.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtbexmlqbq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtevplhesi.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtcvxjgpsx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtohgumupx.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtvhhjtgdt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtkyoszpwl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtpxrqkczt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtkdrjqafy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyffiypxo.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtcymklipb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtbxvdpanj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gtwfzvuepe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtcimdcwxr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtknomilxi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqlyoflp.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrnaqpbnv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtqzntwcyp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtbeikttnj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzabthfzr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmgpanrik.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtrqvthbla.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtjsncanid.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gtvbzjaqtt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtotaoqpwr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpuqujceg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtbxamxfem.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfbowbji.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwqfsoanw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtcforolyr.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtlqjlahnw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtfffonnnd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtayzxfdxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtttozxnty.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtakcekttb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtnftdnnta.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtslhoqpyi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtfghucmel.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gtuyhrpsge.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrmbscmec.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtpqrliuke.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtypuqdjwz.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtwbarjort.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gtrtcdyrkz.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gtuoyzgvfd.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtemcrnbws.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtwveumjqx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtlhrxrint.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtqiuulqvq.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtpimtsafb.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgyykruud.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtpmigvota.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtcmzkqgdd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtjpahphoy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtwgygfczn.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtpoikcgae.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtekjtradv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtjcjejmtg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtwghgzfoz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtwsrzxtjn.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtdauaiqrh.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtludjokas.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtsshweksz.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygaahjbg.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtindfotao.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gtvypnucgb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtyvyszgxq.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtoytolkof.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtyhcwqapz.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtahdhnwis.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtgaulicso.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtylpvpeqw.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtdrdmtgnt.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtskheybgn.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtmyxqubhm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtiiwllrcq.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtkptikbdk.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtolsikyao.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtqaqxxita.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtlhvnrffy.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtfwozuwsa.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtqgfhlxae.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtqzasolga.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtzojemdfc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtlkohqafh.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gthyayrhen.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmolkmwh.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gtklsdtsut.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtbdloxtwh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtwstzzfqt.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkjikmqia.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtqilgtyxu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtubsoidzx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtuvbbguzv.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtsagslxop.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtdxbjwxev.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtfjsnbsrp.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gteutzedld.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtrqewbbue.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtmuyxbbdz.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtsqnskrqo.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtwfsonasy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtojjrxwfs.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gtktbbcrqe.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtgukuxvio.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtwlkttsii.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gtnsvrpmjk.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtnbyniwbs.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtzjrlciiq.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gterijbvyj.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtjtuxrssk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtfzkgnigg.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtgeumsdis.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpveprzkv.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gtjbqyxtzf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtayptffnv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtsejlfkwm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gtffxsstyy.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtzsqockdt.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtnbtfozxa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtkmcxxqjv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gtazsxjrob.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtzjshdutu.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtgyofupvs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtkeescgwr.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtudplprwc.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtqafujbbm.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiwmndak.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gtyjdkitlv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cdnleiting.top/Article/details/gtpdcvkuwp.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtitbskfmx.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtzdecebde.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtitwvpuxx.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtcxfoclfu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzowzorxk.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtpfcyvmva.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtmohlcbhx.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqhelonxh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtimwfnvyv.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gtsmmcxzio.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gttmzpvxxt.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtbmpwjequ.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtqyxzrtag.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtcwjgnzdo.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gthcalcjai.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbacgabvn.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gthxcveghk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtzewhyivh.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtpiguxkje.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gtbvlhiqhl.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtqeguweyx.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtarzdgjic.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gthrbzuucu.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtjyqwowct.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtivjmyxxi.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtomiybogn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtrlfiphhv.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtomceoqbc.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtewdycvmc.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gtmumcuihx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtgixfouip.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtjjvgauyr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtzctpiftw.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtcuawsvai.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gtaoyijeho.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtpsxjtypn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtajycswrm.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtvwypyelw.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gthtdlktvy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxlmjmyy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtstuohieg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtexfewyoc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtgdryzwzb.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtwwfoapfo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtyjkokogm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtzflbijwm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtstcukttc.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gtffcjszfn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvepyxgz.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtevhdntwh.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtynjsgaps.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtanxaqktq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtfpibsuwn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtjdbcjxkr.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gtyiiyldae.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtbwdonkfc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttpuecule.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtfaykkvvs.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmxyvnxqg.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtztrifpmr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtlvmeanif.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtolriejvd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gteppfdgxs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtznrgkfot.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtxyvwstmq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepybkamk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtysshqylr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtzerxpmtk.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gttulxifzk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtoumkbztz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtdczkrvul.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtzepfyizd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtvvknhbdj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtnbupfjdd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtbfxdxtjv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gtbrghbffe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtkbjcohik.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtneammrbd.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtkhgdlkns.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtimwmgliz.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtswumnzok.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtjofmslvn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtnptrsrwn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtkcfhqicx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtiizurnga.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtbeffhqxi.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gtiezsiiak.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gtgdfbcral.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtijdntifx.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtedzgyezk.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiiszgtfy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtepaznilc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtygwbixgm.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gtlxtdcsdm.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtbjphgrbd.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtlzyhptno.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtigspelvm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmyzrenk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtgalpyxih.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtzhjvbawj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtsonktcsv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbbwvcxb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gtlgxtiotq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbljgkap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtingozqjn.html


<!-- 参考信息 -->