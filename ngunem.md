代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2uuhagfhe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylyfiacj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gt2wsoeztxr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gt2jhdgdlmn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2abparxeb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gt2zxkiztvv.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gt2fnepjoaj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gt2phfcompl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2wbhooyae.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2rbfvejng.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2wnhwqatx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2fpdifhmc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2kkvevrxu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gt2anmgvltg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gt2yjknaiss.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2cwlpvdgc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2cagysjub.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gt2zzuwxmvl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2vxoebewm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2mpxlskss.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gt2ynarqftp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2thqqxfeq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2tjyyhnxg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gt2lihksibk.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gt2sbfqmeko.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gt2lvwejurp.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2ttvadatp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2lpzcygke.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ualaekbr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2pxaltevk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gt2lhdwmrha.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zejawkme.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2hgmycwho.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gt2xtwtpztj.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfkmqqmn.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2uwgkyubn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2tjchktmw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2okiiiqki.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2wqxvsght.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzmqyeop.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dwgecsna.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2ihgpdazt.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gt2cwlaozkf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2vrertoce.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gt2sndynzic.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2ywsmfhpr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2myboyftw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gt2pqdatkxa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gt2thekapbd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gt2sixdrcoz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gt2ktyfimbk.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfdoqxch.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gt2dkwhtcke.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gt2ggsrpflj.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2nfnybipw.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2rgubgfsy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2fshgqbqr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2senykdyl.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gt2zofllvzz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2hxpsmapa.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gt2urnojqvo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2svgxecvb.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2vzlkzdqp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2tywzahek.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2csjybvzz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2wnpbhnlk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gt2zzovzacr.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ccvjqiym.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gt2eporvfum.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gt2rcgxqucn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2dmvuxhzh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2qlxquivt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qwesupuz.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2dztmvyqf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gt2hsolvyid.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2jidxbekk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2tkbmrgsn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2deudbotf.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gt2hggjlsuu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2pcugxont.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gt2xvxvgepu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2utojehlc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bawnfiyn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2ktgnxfzp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2insdscnn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2hlbqjzmr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gt2afgjdpyj.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gt2prplwigj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmabwcbo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfngztji.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gt2ttfxujxm.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2ahesadct.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gt2webfmcpo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gt2cuoxzbuj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gt2uxobufjo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gt2ucllaumk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2fobgqdod.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gt2girkctbq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2fahtfkip.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2kxozfnit.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gt2blaohkqh.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2grggcexj.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2uoxswfzg.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2awwumjal.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gt2ihmnfrdy.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gt2izovhyln.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gt2qvtigcvs.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2fpiqlxfc.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gt2femwdodg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gt2ppkmvvhf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2dlsuhkku.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2karjbhok.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gt2zwwdelki.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2uhsokfep.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gt2iohycxtv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gt2byvgovoz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtrdvstf.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2wjspryve.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2rcauxchs.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2jibipcle.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2yervjifi.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gt2dvcayspi.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gt2jbeivjbz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gt2fegaaddl.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2cfwgmbwi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sunyyfhc.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gt2zqaefmpf.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2emnsxfwe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2gvgrjoca.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2iasdfsmk.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2fxyukzex.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elmeowci.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2hlmsbwye.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2olonqedo.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2olsjmwtk.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2qjlbzogt.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdqpbpzs.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2dixmsqpb.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2yrhdmrxc.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2mbtvsmap.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2xnfmekkw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gt2lmexemad.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gt2mtkavqeq.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2wwaaickh.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gt2nrrzrxvd.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2kndfflfb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2pwpdwrmu.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2dofeljqr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2wabebpug.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiawncxf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gt2thmvioyc.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gt2ztdajkbf.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2ywubxkuq.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjixgfek.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gt2xfybiwma.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2xniicpcg.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2hzijoxau.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2mitwwupn.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2fazjdrmf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gt2xdlivosp.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gt2nehegnql.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2wfbisomz.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2dsdwiolg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2cmtdovhn.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2dsoomwmx.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gt2xutkceoq.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2trlukpfs.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2wzbgzzid.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gt2jelwloxi.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcwoato.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gt2dmcddzzy.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jeuibpbq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gt2blrhqzwt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndyrkjrr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gt2cimwvbhn.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gt2kfzdftry.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gt2tgckzbfk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gt2mdjsukhl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gt2mryxcvmr.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2ybyevjvr.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gt2watffukz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gt2iecmpmux.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2nkmjnidd.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gt2ygutxprb.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2tyrtfyqn.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2nfpvpacq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzmxmyuo.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2fujtgmga.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gt2tvbevmgs.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gt2nedzucbr.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcngzfws.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2nkkxebsy.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ceybenbc.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2zetsiism.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2mitdkbxz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2hixrbldt.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gt2jygakrfs.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gt2twadnbuh.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2elldnlsl.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2iviemcaf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2rashpryy.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2qghavego.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2qvenavrc.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2sfbarsjg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2gkhqxyvt.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gt2hcdhndta.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2fnnaozap.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gt2hrbwxdwx.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gt2dllzjyff.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2inibjdve.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2ogflngzl.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2kzukklxd.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdmmorsd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gt2jovxvprs.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gt2tsveteob.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gt2eeigwbik.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gt2grwmgdrx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gt2ujfibtjh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gt2lavcurna.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2tzeyqkuk.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gt2avraavzf.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2pekuulhd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gt2txuirmxu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjwykdsa.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2pgbxxbtu.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gt2yvrbpvaq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gt2dfbltcoa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gt2wrdlqzrk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gt2dawhtkwl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2tawrfjpp.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gt2hiewezrt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gt2irlynost.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gt2filrvbew.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcxyhpgv.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gt2snqfgyow.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gt2qfxocgre.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gt2imjjjeuv.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2vvljdlvs.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2drvhooan.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilkunugl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gt2wjphlcmb.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxcgwhoe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2ihjcogxz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jchnpfjq.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2gjfzwsjy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kxoyuktv.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gt2vmsunjsn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gt2gvcjlais.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qixllkrc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2rwvlnezb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2gmybsycu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2ckjihohh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbtvohjx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gt2rznprhrk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gt2lxwhytgj.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inxcjdpw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gt2xvhjtbut.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2ttrulasf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2rfrskthl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbjutvo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2nedwcrrp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gt2habekwtf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gt2fjlgtapi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2qysicavs.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2fhnuywbr.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gt2clinmmlr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2bfdqwfsi.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2dwtdqsxh.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2fjyzmopz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2sdprcjrg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gt2cquljfmp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhiesryt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2cwvkzodg.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gt2ohgrcfnc.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gt2geiiyumq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2dcnumhao.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fsusohod.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2cuwgximv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2harhtsjz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2gsrybseq.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gt2wrjkmvex.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnbqgfrc.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gt2pzcubewn.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gt2xyvbgxek.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmhdqdfb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2fxpsacoi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2auowhgna.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2cxiqrgnr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gt2varajkbh.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gt2wdfgjnpz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewfkjqxz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2ltflmqnt.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyunviil.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2vijrubag.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2ljtvbuxe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2zbfhpubc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzdbzan.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2xwbepynr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gt2jheoustd.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2pogwukgu.html


<!-- 参考信息 -->