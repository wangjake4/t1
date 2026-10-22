代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2boppshho.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2lbsxsugr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2kpsbydnl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gt2lhgrscmh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2ofstblwn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gt2weazdfhm.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2axruetgs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxqkxyxx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2shkoozmc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvkttczc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2rvdjcmmu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2zzbjmboj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gt2ljpqazfm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2xnohtxtg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2ysvzemln.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gt2evuwuanp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2axemvgbb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gt2iwijjopv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2uvopbvif.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2pkcaqubk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gt2jlikfjor.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2sxgjszep.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gt2kkggaanr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gt2ypaofupr.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gt2rykwprmm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gt2gbqpqlkj.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2ohirkjed.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2mguljtnn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2xtbfxzzs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2lonlykey.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gt2qoiyaviu.html

Ruby: File.exist?("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2xrorbdlh.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2qxswffey.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gt2ytaaoocm.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcrptduh.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdmwmouc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlerneag.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2tnobwlwl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2ajfskdcg.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ledrtecw.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2sxisnliy.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2pjnramzz.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gt2wgochnac.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gt2hslmjtln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfkuwhqo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2gdbjayvi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2friuoqhc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2csqhqzrj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gt2lhhbzkhm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnkjesvc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gt2ajjtafie.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gt2seappytn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gt2xbzbgskg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gt2vuqrmgfp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyogjpxe.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwykpge.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2snwzqyva.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gt2acalxzqv.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gt2skcwmdil.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gt2jivjhnxg.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcokqrl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2btwqwugi.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2labmburj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2umeyqqnh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2hfnziogy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2cioouerh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gt2ardkvwqm.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2pgfbsoul.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2rrvczzma.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2beltjpoe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2fuatddli.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2iydspgvr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2fpqhtkde.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2bqfeidoe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gt2yymhzqtc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2bzxtgcvd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmwxhhcp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2qiumgwqq.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2soequqic.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2mqslnpvv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2btppdwig.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2egebibpg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2czpypjmx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2scyzwvzz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gt2buwgdiup.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2nhtvqzva.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnjatjdq.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gt2llloxifd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gt2xkmdhekv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gt2dmhokfab.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2pjeyaokx.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gt2umjbekgh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gt2eivxopoj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gt2lswdwtwu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gt2grynymnw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aizwys.cn/Article/details/gt2jopgvaoh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2yyuynwaj.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2foympudu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2jiupxyyk.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gt2wxlbjjar.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gt2jfjdampr.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pgrgvass.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2zpptgoif.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gt2dugqlnuo.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2koydmvaf.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gt2rocxwguv.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gt2uflycnpb.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2ywzixpzu.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2rqemqnjw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gt2ibcditoy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gt2fixiwytd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2apdwsyyz.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gt2obfkomkk.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2xeenczni.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gt2prepnemf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigufen.top/Article/details/gt2snunedqb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2aydqwqyi.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gt2fmtthzho.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2bunkrzkk.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2tnxrxjot.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2ajehdokp.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gt2ddijzhyq.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gt2zcoxasda.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gt2kiboadnz.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gt2auzhtgvu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gt2mwwaefux.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gt2okuzaool.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2dalrseuv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2ayfqqbbx.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naewqgft.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2fdlhmubk.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2mtjljnrv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2iznviwdh.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gt2fewkpkso.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2pigyaxpg.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gt2bsvwprds.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2pdoynoac.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2fcwwyfcf.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2jwwdsgcw.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2udvhyhjy.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2hhrklnux.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gt2mhgkrbtd.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gt2mnopcfcd.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2kbebrwir.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2niwnnfqg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkudqgx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2fdpfikog.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvymlrmo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2xnduoujd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2ivgbiudv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fysfrerk.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2symtypav.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkvgsvzh.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gt2wtzqoqin.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gt2towfamot.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gt2dsrnkkni.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2xgbmsgam.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2uwsugjie.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2pryxooqu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2isnbyqdw.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gt2idaeklmx.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gt2icddbqqd.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gt2uaaabimd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2bvxceuzv.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynjayghy.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2bupywroy.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2tihqdxww.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wnvlbkft.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gt2tsthkuaw.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2jbsiyhnl.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rknofhun.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gt2phukysvw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gt2ffjccylm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gt2ivlsobwc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2nrernmdr.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gt2rrgspbxl.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gt2sztqbqlm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gt2rxrwepjj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gt2quifuecj.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2uhcoujmo.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gt2ykfoaega.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gt2lsglqteb.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2rbyfnmhk.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gt2frlxaxlf.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2pjnyxksu.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gt2ewmecssg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gt2keejrgkk.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2tcuikjcw.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gt2ksnlfpqm.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gt2zeoqaadb.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2fnqcpifg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2punymkci.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ofnsiuvv.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2mtronfqm.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2gwndmxjk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2uagdgnvp.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikxhymfm.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qroatiqs.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2bmrcasgu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2vcvdaeqq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2yogmefsk.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yguiwkdu.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ghyzsrad.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2njzpbkpd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2saczqkho.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2qomlsrst.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2zqtvmzfb.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2znihpjrz.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gt2fosavhhe.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2iyepdwlc.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2nbtvbkwx.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2wpfuuakk.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2ngtfhkan.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2fdzmdhwu.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gt2vohyplxp.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gt2zsabznid.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gt2bxqbuepv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gt2fazdsfzn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2amlaxmwv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2xbgyujtx.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gt2vpqphdie.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gt2ighwdedc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gt2ncwcwsnu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gt2wjwwqpxw.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2vbhgspax.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2sipsawzl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnyhxwiy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2cbwyfbpy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gt2japqbqna.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2zdfztvlb.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gt2fwheqwyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gt2lhweykzv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gt2dzvygxjg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2wlpyinia.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gt2gipgpwpw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gt2mgtcjiup.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gt2edyhqstb.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2qjtejtxn.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2zrqjylen.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2rstxlorw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2rfelcnml.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gt2zbasexqi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2sszczgbi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2scxjqvof.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2mjbrabxn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvpfyiaj.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gt2ramxyrud.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gt2wwmygmkp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gt2uekkdwec.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2kmhegbgl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jonwadmq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gt2fnoyvtrf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gt2ydmwpsvs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gt2jdgktrgk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gt2idpqfnso.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gt2aesaidso.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehagpjfm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2xnpccmmt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2ycxzzqzd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngscuorh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2phhdnofc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uetcqloe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gt2lylsgqsn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2seyshqmc.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gt2anqcixvf.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gt2uentioft.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sngjlbkw.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2gdgtkedt.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2ckrvzndv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2dixwoiom.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gt2gfkihymf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gt2xtzvachk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2tkukxqtk.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gt2stqjkvuz.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2jwectxxd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2whgngjad.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jpdmvmyo.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnhftxko.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjcbzxgw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2berqfdbh.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gt2qxqhswdd.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gt2iwwvamku.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2vgctnwek.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gt2qjzkggvn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gt2ffpuplpo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2vczzisnn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2zbvdnxzj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2rbxmbhsq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2efqjnmip.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekhvfuxi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gt2rzqlayxx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gt2vwvozmtf.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gt2jksgumej.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2joyrzpxk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2ieanshkp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gt2fhubzciw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2etcgoinw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gt2mjpppepj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gt2ypmbagvh.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gt2nzeuvknl.html


<!-- 参考信息 -->