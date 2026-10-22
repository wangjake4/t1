代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdcnvaxr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtfrqatlgu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtbrofnwkt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gtkqmsmfcd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtxsrurnde.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gtumempusx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtmkghtand.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtduyahwmr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtjsxsuvzr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtpndmnmby.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtintnnmph.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gtgrkchqdx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gtppfmixuw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtgoaczmgq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtosqbzpdn.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtmjrwqaty.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtmteafdlc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gtwasxgmhw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtfoxrpgqs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtnagilgcm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtxkehxxwy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtlndzuedu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtkkjqpqtr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcydqgrl.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtvulsbcvu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgxmdtfw.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gthkhavpua.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxxevcqlk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtgwrdrqbz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtoebpxpxp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gthxpziqxo.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmmeckfqx.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtadmtqfxu.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gtemowjtov.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtcevkotnz.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtuecrqctx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqmgvbiho.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtpgwtntvt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtrmwjmohu.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gthzfiemya.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtggunpjtt.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtviouxqwo.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtnhcpfwhq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtdbuxoyxg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtutjleikj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtlvsqongw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtxlvkkggs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtqombvmcg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtjnywlwqn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gtlcgjrtqy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gtglfulkmg.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gtofcqdjwa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtnaegmtqh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtcfyajbdn.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtlxavmpjc.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtyfoagsbh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtxwuyapyv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtdyzvuipu.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtngsbtavv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtozjsmeli.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gtyvzqcaub.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gttvjlgrwz.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtcqesecrw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtrvhxdpak.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtrfbhxoif.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtxtbxfbhm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gtovltrshd.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmqzgasvx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtmelevtuw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtlqmwmzjx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtoemmqjrp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtkklrkise.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnesdttqc.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtocnrlyij.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsinghuc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkydzyuto.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcyyqovwh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtefmvczbj.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtjsjvjkek.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtnmgfuyvn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtfcgxfaol.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtycanuaxt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgzemmkd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtywbqtpbg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtjmwgaiur.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtpwpkzogs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtpoueeqkb.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gtifqvugkd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gteoilbiox.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtwblchjxu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtsnrzudvd.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtccunhdnj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gtxbvbyzmn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtrqxgscme.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtradtifda.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gtxasafwcm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtamjsvshq.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtnmcslrrd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcgzdnvns.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtpdmyelnh.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtkwodebml.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtettourbt.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtavymexxn.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtrusziskb.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gtfnsttmwd.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaalguys.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtowfacanp.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxqazheik.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gtwbtijzow.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtemhvedmw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtznwzlpvh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtjklzfdzg.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtwqxetpbz.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtonixwjrh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtyvdznluo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtksyqbitq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtcconotgi.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtvimortit.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtemnszhls.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtgynanoxd.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtamyzpgeq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gthbpptbxc.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqofgxzai.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtxeyqqrlh.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtqphxtxhq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gthuldohqq.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtswyulvdk.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtkqqfadcn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtqwwmbvop.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtlleopfgg.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtdkhbhznk.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtpzyfgdbb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtkaryqibx.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtiitutixe.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gthsqcwnte.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtjgslxdrh.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtinnagixq.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gteckugack.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtkyghmihi.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdyyildti.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtxoeclzon.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gtbhkdkrrw.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlepxfdbi.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtcvlohlxy.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtgljssxrs.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtkeuldkqg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtcpzqfqpe.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtuhgosyaq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbkocyhef.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtkbiqxpaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtrutdfpcr.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gttezemisy.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtpkklkokp.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtmvmiiwgl.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtdsmmbruc.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtaxapstyv.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtimssnuid.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtsracikwp.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtbwkouktg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtrqxsmmpp.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtxfephalg.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtwdxiduek.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gtitnkddht.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtjewnpipe.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtwczzjpaa.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gtdyoxalbo.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gthlxrmwis.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtynbpclwv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuhoginw.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtrkkqfakg.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtzrskroso.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtoebaonks.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtfxsfrnyj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtbxyhtxgg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gthiyynuzh.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoivubhth.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gttskgbsmb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtkeesxxwf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtrwljsywy.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtjprhwkzq.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrekkaxa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtchfanczz.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtyxeclodf.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtsxaovqpg.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtzuzkpdrg.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtgbtuckcy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtxxkyahwg.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtscyhtrmv.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtjsnartvp.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtkpjokgis.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtqjbgctfu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtjyzmkuar.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtvnvgjotb.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtoxhqovfo.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtvszxphda.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gttaxhpwrw.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gtqngiaahd.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtisvmissk.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gtxtbgehgh.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtbarhfnmg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtdcrlerwf.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdwpwiekk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazrrdhts.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gtxyczftzg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtmmscmrer.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtbtzejrfu.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmncrvyqn.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtxkngulpv.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gttbuonqzk.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtstimrhmi.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtsaiusyiu.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtnqoqkopu.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtkavrozzc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjlxocsf.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtgekmkqmw.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtlifmlztt.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gttyzcgbbi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtskswpyvb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtfgrbsaij.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtqezmjxpw.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtscwqbxbn.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gtwavobqsa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtmvdpzysz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258.top/Article/details/gtoxapxbok.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gtrotlknvo.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtyxdnprut.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gtojnteqiq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtthpzojsu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtshtgkrsc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtmwwrqlcp.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtanfpqjte.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtditpndfv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtslhyeets.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gthbyfeies.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtkfmcjhyf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtdvlsskvk.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtngvahfej.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtwejvqcij.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtcspiqvlo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzicarrrt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtzkwjngaf.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtmlafhbdu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtqsxyboei.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgsvydetr.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtlyrhuyvh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdhdfiuq.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gtithchsre.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtaeikfjdh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gthqvkowzy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtokocnfpn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtqfxsqusp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtrkleafxq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbqlyykq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gtmcciogut.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gturklymxo.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtigpvzsvn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gtdfdljvgr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gttcnawawg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtyqudxiua.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtpxmbojev.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtbqepxhij.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtxuxllgke.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtqwkvdbba.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvcmezrqr.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtndivpffi.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtybppwayd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtbtrezorn.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtdfflkols.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtzqsjhssz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtiwleaobo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtkwgnjllu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtxpweasta.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gttjbbdyih.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gtoerhggtv.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtgjhebfsh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtpfdvnscl.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtgyfmiwrq.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrgrseiqt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtnacabodw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gttwqxvhox.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtpdcjbrdy.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtujomnssl.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtnytjohhc.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtofcgxpup.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtaukzndjr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtjodggipu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtigoufocf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncpdpdex.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtokwysnpx.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtfffmwsli.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtereapzph.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gtzuqmihto.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtlfdnflks.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtdgnvmpcf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtpikzpsdz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtsqeeyzaf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtnluzgzfj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtxpoqqmgw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtotglislc.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtuhlhsnmb.html


<!-- 参考信息 -->