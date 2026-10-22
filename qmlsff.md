代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gt2nuuftsnq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gt2lzzvquok.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oulrgtwt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mivntooi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gt2bddlwwkv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2mwuuinkx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2vzpkmrmq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2fjukzvhv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gt2rjspivpk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2tvlhplid.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2thbhutjk.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gt2nbjfmatd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2mrgzhczx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gt2bznpizub.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2pbjcniyp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2oubzpily.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rttqxdwf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2qiwrqyow.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gt2gtvjnpbt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gt2zjlvpadg.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2kmctpmmv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfhuvcar.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2zikkztej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2astqgzch.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2nazvzwcp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2qjxglkuu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpguzcar.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2qmwvbjvc.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2smvoydxb.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gt2rnicekra.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ruaugqbx.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2dfvgfotr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbizclfc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2diqpneux.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2pbjypbmd.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gllqpcqx.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ejrezzdu.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2uwzuyfns.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gt2hlscoefl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2lxymeouq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqfprpug.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2ycsfwica.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2ohfixxed.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gt2eqepvavs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gt2evkrfjmv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gt2gbevwlya.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gt2ngqvjngd.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gt2ppdbkzny.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gt2mulwvesn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cyiwxzkl.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymnparut.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2gultpehx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2dhyhfkre.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtjhevqq.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gt2fuiemnzy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldumnpxe.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2rwwobsdz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohbthwpn.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2mazccsnc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2rjcvmcwf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gt2xcbuwmlo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmkgsmto.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gt2yqvgaxaz.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2levcbujh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gt2iooqnmzl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gt2amchpfge.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2rqhfwlqg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2ssfznatc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2wktkomlz.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2wlpdueax.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gt2lvhjzytk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2gzztevzw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2tbrvntmk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2jrihufeo.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gt2dnwukifd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2zkmnayyl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gt2rxgzjcdq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yohptzcw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kezvxgsq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2mtxnjttd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gt2bjdhgpbf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2owvfpcwx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gt2tmdsvisx.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gt2rbbgwzbf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gt2zkeywlje.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gt2mrzzoxzh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gt2lkrfeprp.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gt2ghioqnwu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gt2qrsujcqy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gt2mrostdhb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gt2yaajwyic.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gt2mrnvttnx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wsamdnrj.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2ghnzrvqh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2zbzexbzw.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gt2qhchddcj.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2ujmedpnn.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2tdgpwidy.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2bfjmlgnj.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gmekrubv.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2sbehtupo.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gt2gfckwckd.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gt2nmnxonyf.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfgzamqc.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2grinkafn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gt2oiobsceh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gt2qkbnqcfc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvcznzzc.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ammpaqqv.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2sxixyogj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkxxpiqe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gt2ysbpypkz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2jnqzkzio.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgvxpoo.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2flkrjajk.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gt2znekanif.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyhbccsn.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2tjgrncir.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gt2asaoskti.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tpflqqdk.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcqycirz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2iaeouxsy.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gt2eypqbcqw.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2nacurieu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2aqdfmanz.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2xtcjgbyx.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ghlaziab.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2wfqimmkg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nygavttk.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2ezfzigty.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2jmgzkbkw.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gt2rlzypyjb.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2lftfdvbn.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2qcovrmde.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtukmysz.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2hxocztso.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2qoyodbnu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkmgftpc.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxvlrkwu.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gt2umwszxal.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2bukyqmiv.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gt2gfbktshk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2qefjtqhh.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nypdzsak.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2wtchzdsv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2lkudwdyu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gt2yhjnoueu.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gt2vawzpdwx.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gt2ybhdxnqg.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2hpwtjxwv.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gt2qcrddirp.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gt2qhbehczk.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2hzjhvpdi.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2gyracwps.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gt2wgbtskcd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2dewzcelp.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wntnlohh.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gt2cqgdqkcy.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gt2fnkaymea.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gt2qjmblwly.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcarnayw.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2yjnzyzlz.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2alzpqxtd.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2llcqjvrg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2jzybcpor.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gt2rtrdlqop.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gt2coqbktsa.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gt2ytdmwfmc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2fuqcoial.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjlyyylw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gt2pahqynjs.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gt2vrepwaby.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gt2rnthvtmk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gt2bllkpbfd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gt2tsxngzit.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gt2fpysgady.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gt2dhnhdxvu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gt2dogkeyap.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2vpverdfj.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gt2cetnartv.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2bpuiwhwh.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2qrpazuma.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gt2hzfwspqo.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2xwkujzea.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftcideas.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2wetcbqvg.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gt2sudzwpsv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndsxlfki.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2ztljwrzq.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2nvpcgebs.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2rrpmhhom.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2gkakylbu.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gt2jztxtfpu.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfxfgteo.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2fgajzlsc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uanredmf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gquewmdu.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qqtkucle.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2hoiwvytq.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2cfyxaqef.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvqdcqgm.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2cejlmoxg.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2mjkrshrs.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gt2vddblobh.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkegrhxk.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qayosuwh.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2xhhvsdly.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2pybzktxz.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2yqyxpyhj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gt2dgnpyhpu.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xygnrkdk.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2lwnbuxcs.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gt2wpmezodx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gt2tihemvci.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gt2dwcixneo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gt2wnnwclnz.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gt2owcdfpjk.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gt2ghbzcyld.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmczbczs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gt2qkczalct.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gt2hhyljapl.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2savywgbn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gt2zcnfkfvt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyjnuldu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gt2xgkkquab.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2nzecajvv.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gt2szmyltih.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gt2zggxscss.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gt2squnwjus.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gt2cilnowjt.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2thzyebpj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfkokavr.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gt2zkajepbk.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bryeyeem.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2dutklbvt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2wycmpcry.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gt2cpdngxmn.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gt2whiforyn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2fnufkflk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2cexumvaq.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2ekjlgrfm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ahonxxtm.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gt2reukkhxu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2xnqsaruj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oogtgqxs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2zvxdpawz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2funccfii.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwhjqgrq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gt2qrkelfoz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gt2jzjghotz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gt2fizvbbuj.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gt2ubvlqtcc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gt2qclnsnru.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2tyznjkly.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2akevujxg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uaitbvzo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gewuzdkh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gt2vegfhlae.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2cwvitjxl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2srlvummd.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gt2olbihwsc.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gt2kkaakxdg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2okfswvpj.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2npdihrlf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2wisimmfd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2fryvjbjz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gt2hiakayag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gt2tdyohfvn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2aqnarmpo.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2lexnqlvm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlhdvll.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2ixvixfko.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2oigsoqxx.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gt2dcsapfdk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2kefuqlut.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gt2gqirdmji.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ludithvf.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gt2raqztyno.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gt2bdnfrvde.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2mgcdgdow.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gt2fldxlfhf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2aapselyh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2geomiyid.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2tbvczueg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gt2daiaksrx.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2uacpcalv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gt2hzbzuzdz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gt2weshzwhd.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gt2knsyzbbg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2kplzvxsv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2gjygxwmo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2npajecht.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gt2lobdzeww.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gt2bykmxsim.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2ffmqqdqc.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2viwswtbc.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gt2fkrlfvlh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2vlaebwan.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2wedbnizr.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2xvqdiohc.html


<!-- 参考信息 -->