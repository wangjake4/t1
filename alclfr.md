代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2sjfdcjcm.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gt2obseyyzw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2vccyxzlp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gt2vozmlojj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2tfgoymka.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2fxoevjlg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2vabfhqsg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gt2hrrpkwyv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyzwbccv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gt2uyvmcrtp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mazmcykm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gt2nikgvthm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2avolnuji.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqvjvtej.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2fyxsowqk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gt2iycgjpms.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gt2nhabcrnu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gt2vqbbjslm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2jmpqjnut.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gt2avkdbulj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2gukdajsp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gt2zbipcphe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2fjimpume.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2omvrxapj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gt2venewgzj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2cfzzfrwk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gt2tguswbii.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gt2dutxbxdh.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gt2ttedrldw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gt2djiesaci.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2slsmlfpy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2symlwijl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2evyvucav.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2cysgmwem.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gt2xppqlypc.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2xxobqstl.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2lmqnfpua.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gt2qefnxwqp.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2zyglfwzr.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2iavrdjav.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2hcdgypjf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2vltnlfaw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2iidgoxhy.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2nboqdmjf.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2duhrvwgy.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2swxdxakq.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gt2acdzpmgg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2cnsjmyrt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gt2ddmiwsbh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2ksfbkryl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwsmbqfh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gt2czmwwqfk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2oikydhmx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2uuzfwfuh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gt2njpuqumz.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gt2gzkazcee.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gt2nkaehcoa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gt2vpwpxcjk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2ddgiivga.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2bcdflqds.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2majujcej.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bplwogyu.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2bakxtmzn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2hwlnskwe.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gt2wddmzunv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2uzjnlvlc.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2gzkuctqc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2rtcyeomh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2wdqwacmw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxyonzrc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gt2zgijghcf.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2yutiizpb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gt2spyzgphg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2hragdvkz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ikawizac.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2cufanzby.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2vkkrqtfu.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ycitrnag.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gt2nlkdnqwn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2oximyers.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eruhcwis.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2mwisgfje.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gt2zrhceart.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2fmtrpsje.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gt2vdvqwhjr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptophozl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2yawbmkeh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gt2qmxnkxsc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gt2iypktruc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2szkbtynk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gt2ixhyvqvk.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2pxrieqbp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gt2pqugtval.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gt2adssfmww.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gt2ziyyvbih.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gt2rtwoatnv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gt2gkluvwtb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2mbefsgtx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gt2oghyexal.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gt2cykoajsi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vhvhpsnr.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gt2awyufjrj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2odlbfkvi.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gt2cawowbee.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gt2ouuacauo.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gt2ewiqlejc.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyzuqgaa.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gt2quwulcba.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2lousjkpq.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gt2mriguxom.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gt2yreabfde.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2zpdrjzon.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2oobdolih.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2flipwzrn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsehbrvq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2gbycocdm.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gt2pxkgsyfv.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2zaowoszk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gt2npxzrnzc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gt2divvgknn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2xivijerk.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gt2zmgzryhj.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2wdqkzhcp.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2odxkdaaj.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gt2qdxtkhoj.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2mgpyxutm.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gt2gvujcwyq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gt2vjrqrrbq.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2eegpzyie.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynczgjqa.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gt2ckbvkhwp.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dojcyzgr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pxqnhiwl.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2jbupxgxi.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2trjonjon.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2jplpcxff.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2ddoibcyn.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2keatjbvt.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2vqjbvtbb.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gt2bezbdajw.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gt2vyezojno.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nzuvfeem.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2nfnplpay.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlvvgbzc.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2fmzgepee.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfwlsvei.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gt2duwunwfl.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2yndpzava.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gt2xqxibhjx.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhhpbybt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2drodylpu.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2rywitvzw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2klwjkqgd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2mdnzfmkj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gt2xnsezbfh.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpgbfoth.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gt2nvgsllpd.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gt2buqcjmhp.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2vibqprnu.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gt2vxlhkvfy.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2xrvflanq.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2ddzmhqwx.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2zuwfjgyo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gt2ssbhvmfc.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gt2bcfrvygy.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2bdbrxwaq.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2oeoozlxg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gt2pwbcycbp.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gt2tmujaard.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2xliwxfys.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gt2wsjboqtg.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjbluyhu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwumsrkh.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gt2vgnczwih.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gt2rmtilorf.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gt2narafibg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gt2warzeowa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gt2ekvwnpzo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gt2psykdcwt.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gt2ezhduxwr.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gt2wfvstswj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2tjgygxyt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2pajexgcj.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gt2zejcglbc.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2vqtcodux.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gt2anezbkjz.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2jqkrdrgb.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gt2qmiwegni.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2zipmfklu.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gt2fbjjrlhs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gt2wmsdzjom.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2flmpprhk.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gt2gjictwdq.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfxtdhtg.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gt2xhwzsien.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2dwwtfubh.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wztamhsb.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2giffeyxs.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2ofeljcbf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2jgnjtygn.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gt2djrdznop.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gt2jncmtxlk.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2kpsymvyn.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqziofep.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2uosoiwuf.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2hwzrraqk.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2hixxmxrv.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2czclcucg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2tnwwdzob.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdlcggea.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2yzppdpsw.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gt2nidwfmbv.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gt2rlszxfnd.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2covkxmyw.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2mjpagink.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2expaqzpf.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2diwtrtwi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gt2ewjmtgfx.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gt2kohbgktk.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gt2esmmridt.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gt2vlrwxpjw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gt2lcsmskbm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gt2jqkznpdd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gt2usrsoysp.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gt2rekiyips.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gt2tejhqyig.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gt2yimajpoh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2fgbqvcxl.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2onhsiroh.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gt2trcqfdsc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gt2xjnmmned.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gt2ccydlhej.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gt2begfuyvp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2qygrgrkj.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zscwmzjl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gt2wmybtaho.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2xnbinhgq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2ntrpfzol.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2egtcdcni.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gt2vpziragf.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gt2cuepolmk.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sywsykql.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxixlszy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gt2xwftxnqb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkwejche.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gt2hozkpuzr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2wshtyrui.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jpqmylnk.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2tcvctzyi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ifpxmmbr.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gt2eauiyawi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gt2ctbrqyoa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2dpwgarbd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2ljyclhwu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqynvpqx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gt2sshuxuqe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gt2ukujustf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gt2inxsefep.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gt2ilfyjgnm.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gt2tvrjapba.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gt2kotofxxx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2qxhdtsgi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2tajmmsah.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2mavmexwn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2rcbnwiit.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gt2egumjpxx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gt2fciivlql.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ptbqbnbh.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gt2nyrupntb.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gt2zdkalspn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2vxwcesnj.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2afjfhgfl.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwsnvjfp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2fejxuvff.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gt2bhebscms.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2wmbfhwca.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snwirjzu.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gt2aokkxrcz.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gt2chyeznvo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2wqymdlpa.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pxhvvvvq.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2gqmgemtz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2uaayitri.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gt2whofewzt.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gt2aqdiitzn.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gt2yagznimt.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2ocqlxdxq.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gt2tjeijakg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2hxbagxsr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2sgavuwwx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eaypunky.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ymdqksci.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gt2rooetbmo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gt2iyapwqwq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjhntpir.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gt2nkkdohdp.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gt2ggihpadz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gt2wcagtpbz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2glsxqjqx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxycvbgr.html


<!-- 参考信息 -->