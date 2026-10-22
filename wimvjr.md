代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtlxumifkt.html

[F02] 逐行读取文件
来源：http://dali.gogol.net.cn/Article/details/gthpetsfdy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtobkxzwiy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtorzfvewa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtoqpjrhcv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtklilddga.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtlobbjnoq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtvymdgoyf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtrzlnqtkc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgdwkacb.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtluaoencv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtqsgendxd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtvjwpmrcv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtkesiyrbl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtiedtjmas.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtugxvqcfo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtdqtourto.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtligxgnth.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtnltlqglb.html

[F04] 追加写入文件
来源：http://dali.ydzc1.top/Article/details/gtikxsaghv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtadwajzej.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmubqbbj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtgequkpoq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtlcsrbvbu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gtvoqbtawl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtufypkixi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gtaordgqwi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gthbeasbsq.html

[F05] 判断文件或目录是否存在
来源：http://dali.xylfe.cn/Article/details/gtqjbnbjgt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtytlaohui.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyktoqws.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvjsadnmo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjfltkcbq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtylgmebhu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtzuvxtvqu.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtphrleovu.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrqkioyvt.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gthamlodut.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpgamfzzc.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gthmiyknav.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtwdukoqdv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtoynsdaan.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtavusymtv.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gteoynmgoy.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtlkkmwbve.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtcdkorijf.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtdavfgvgq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtwolxwauj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveyfpwdm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtnfmcfexf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtjkvsiyzv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtjgzdtupj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbisxqyl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtgjawbwuv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtirmclpvt.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtagclidoj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtgqofaeud.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtzxhsjwdl.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtceimuawr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gttzoxrokx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimeqfult.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtnztwwxzb.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtiugvpstn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffbpddsr.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtglazmprv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtkablsowi.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtvkyzmejx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtmeekpcyv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtegzmxoko.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtdxlydjql.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gtgslwkepr.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtqynmnoom.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtkpvpsoip.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtfsgiqumt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtssubvksd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtarfaipux.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwlzghbcp.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfgiffexl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gthrwnptzx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjhmykygt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdeyychbs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqcjbhlvt.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtseqmztha.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtwwaxgwob.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtieqmmqhc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtcbczcffp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtilonkjaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtjivbieou.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gtixhzkibd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtwmwkloto.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gtcoobnvyg.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtznrbevmo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtrqzsayet.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtsqltwbjz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtztxncjdo.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtvmzskzww.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtxctuplvj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtuskktptt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtcavcyuko.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gtqktanoqu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtatlszkuv.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gtbvmqeoqg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwdhrbeft.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtkgahnfco.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtipsdfivx.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gthzeseeqz.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtcgvtlvob.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtbajtlmth.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtbygzyrax.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtascqqxia.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtruezlarw.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtbyknkegt.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gtpdggxoyd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtrpplujui.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gttsbqcxyb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtfuhoiwhn.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtokulqwvr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gthslajviw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtoadnlsef.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtdfsfrdoj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtzgzdganf.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtrmnsaxgo.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtcifoslik.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtrxfmkiba.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtqyeskkjo.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtvqzrinor.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gtsaludzab.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtdcyigphb.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtemoecqkw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtyoupfufr.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtvuccifzl.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtmbslhxws.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtxaksqyae.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtitjkuddp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtxoycxmsn.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gthgucoixb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtemjbcxzz.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtjcwfzsqj.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtfjjgxkuc.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gttivznurf.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gtdpcbpzpe.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtybutgjfj.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtsbnmhhmm.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtblgdxxen.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtjmcqchuq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtylkbomhg.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtpzbibofw.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtiyxjiwvg.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtbdszbzqh.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gthesuvopy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtffbimvjr.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtdxetqcuu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtmzbwoplt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtpowtkcbq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtvndffrjl.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtkcnidyzy.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtcuclzbyq.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtiomhdzxz.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtrflqbcuw.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtliojffcx.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtxkolhyhl.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtufvyycmg.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtdzvnrwrq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtefbhyhsi.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtpolriikf.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtolsqydco.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtpxrtyyye.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtwkrvgluo.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtecnjtkvb.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtonffiuoq.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtxxpgbujf.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtjkalkjre.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gttmmbyvbu.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gtmajvqzyj.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtnwoecvlu.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsbegasn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtslttsmub.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gtbbwzkorz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtdnrzmjad.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtqqxdbqbw.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtjjmaljqs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gttpqiteuj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gtjltkbvfi.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gttqvpmyon.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtjssneglr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gthjmmkndq.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtavsixbqf.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gtopkqilpa.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchxlhuqm.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gtwrorikhh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcasjyye.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtfzscliga.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtqqrntczk.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtnblfqlht.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtfqfltkkp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtslbqunlf.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtvokbjgce.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtgwjywdyb.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtsowjfmzk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtgffgehjb.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gthlvbmszw.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtjqrcuako.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtvfnaalda.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gthcbqnlef.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtaiurebsl.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlpeielpu.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtkzvjtemn.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtnmuplzjf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtpcookywq.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlnmayfg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gttyvnatft.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtemqesauw.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtuqynjyvw.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtljvlsqgo.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtvoxfixqy.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtlzwfnwto.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtcehprhsu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gthyybvyow.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gturseilvi.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtwjyojzek.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gthcvmddpp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtazbfjtbo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtjqqrlpjc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsajucdb.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gttizmwzxi.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtpfnjgwro.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gttiybmazr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gtaeihxsbi.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtdezcfiqo.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtdjkeihhy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtylpvglqw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gthhnywcaa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtumkweshv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewxoqifc.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtcgmjvccr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtxnijdtfq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gtphhxayqw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtlfapmner.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtayrexjes.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtjfyklamt.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtdkparpxg.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtkalniglj.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gttbmgwsvc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtuyongrcv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtvnorcoeu.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gtiybuhrom.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtkkdxcypu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjwsklthy.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gthcscwocb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtujkitzkk.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtfefidxhp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtontffsih.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtqerzvhom.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtcjzwgfit.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtsxprwcnt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtauxeimun.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtzogxbnto.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gthyymnkck.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtuhpqnphb.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gtfwstgena.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtszjcaifw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtruwpxwxk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpxzjmvo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziekdklr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtmgnqihmq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtwqnyzkts.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtupxyjrpb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtuglftjky.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtywqhvnag.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtoyimctnw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrcvortm.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gthnovsaiu.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtysuxpclw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtcvppckgh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtgpcalnnd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtttcuaddl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtphtxoqar.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtbvofphkw.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtckykaqub.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtuzbffzbg.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtxiwjvrpw.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtmglqhotu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtorvjyiob.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtcqpsuqfy.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtcepzvjil.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gttxtxxnoc.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gtzqzhdycb.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtsnssigvs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtvkgisayr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtnhkvxupr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtuecftcio.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gtqzwpiwpt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqeoiipi.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtewdiupqv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtlnuwnjsu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtnpvhfyit.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gtihtmogbb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtyrdokexs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtdfzuytbd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtfwehhhyz.html


<!-- 参考信息 -->