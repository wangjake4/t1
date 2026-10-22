代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2jpowiysd.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fomyhztx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2hexrpvck.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gt2dsexafan.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2xdjnaymz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gt2lidbwvla.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2swujzpnd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2biwkyild.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gt2zsvwiwxl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gt2yqqpfasv.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gt2nnsphwpj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2aztmhwae.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfmiustk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2hxhhwymd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypkjkqgy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtxrpism.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gt2lmhkgxsg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xskthxvv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2zxjsjxwu.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gt2jqncuvie.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gt2ezcecaok.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gt2ybxigwpq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2fmxeheoe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2oafoxzpz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gt2ozyqaxij.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gt2xeagbexi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2xzjxrzrk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gt2vxrnaciq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gt2frvuvgrc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdrozjlt.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2cumaeryc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftjdjajx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2efeisons.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2oghaytbl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gt2umxpwtxc.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gt2sltculsj.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2kbskonos.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2sfxjanro.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2dcjdnsad.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2feildukm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2ybhiqmww.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2rtapxlfe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2ewferidh.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ayryfbqk.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2thppahpa.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2betchpjo.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gt2kbirrctx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2jpybeodn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlavymix.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2rhrjahuy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2qpzkfndw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gt2uoeyksxn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gt2zhgdadvd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gt2kbalzxfu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gt2dvedjopw.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gt2zlwipfbc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gt2ocnbwgdj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gt2gjtmyghk.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2hmrbkqzx.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2xgpvcvyq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2szqdbrhk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gt2jbzeoyoz.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2uiwwatdw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2klqaupfy.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gt2sdlngxaa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2lhphuzsl.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2yhyprild.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwznpznk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2csezrqyh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2ehkopomq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gt2djyceivx.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2xrfgxqrt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzmywyzn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gt2zosvpxdn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ynjwnrok.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2nxpbybym.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2klytdppd.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2zgipjvzj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gt2mdmyfsso.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2oqmwthey.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2fsebnwvx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2cjbpivin.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gt2agcwmboo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2wivblksc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2gaytkbbb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2gkacisyi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2ewrkcbau.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2gfcoarhe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gt2fyneszgp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2fwtvoxkw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gt2iosqfazj.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gt2sbyrpaim.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2vejzfdyk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gt2rtwqszvm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2nisvvuyp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uuydudhp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpdremf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohlnskgq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gt2nvfbhnqt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gt2scsnljcg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2uzqcgipf.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gt2jyrifnim.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2syalbyzx.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gt2tbfxpvra.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gt2ianetrjs.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2kseyuhup.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2ipphmvoi.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfcdpfdn.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2meuvxhtt.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gt2mysfxtyy.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gt2lhogtjil.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvhaesaf.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2ndawcuok.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gt2wizvoanj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibrzhqvx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2vztscbnz.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrtkofea.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2mhuvhart.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gt2epflvwxo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gt2qzoztlyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2hofywhdh.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kapoyjtj.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2eslwxfee.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2mvgayhzm.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gt2pzydwijc.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypbbcmaf.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2wflndqdi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gt2vmqrnzlu.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqvqrtjz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2pqtmislm.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gt2fnvczpqq.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2wxtqegno.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2jhmifcws.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2ekprphlc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kysxmjaw.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2gslzxmbw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2sxbvroqh.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2hrosmxjg.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2tdqsqzvs.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnstjrvc.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2dwmagnat.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgzpyoda.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlgjxnps.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2tszsbmqr.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2sylnxpib.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2dpmasgnz.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gt2vaipmajy.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gt2svmzyejk.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gt2zaeplyrm.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2oawwzpdd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vffrrije.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rghdqwri.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2gagfawtb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2irhyrfvn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gt2qaphvkpk.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gt2cmvjtyqy.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gt2czylfxdd.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghlhbdoi.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gt2vbrbawan.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2npgtejhg.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2calscwqt.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2ippmwvur.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2vevdmbuz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfgtseab.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxpssfpk.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gt2nxawhmhz.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gt2xjuwnjvs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gt2nnhyhcej.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvghildz.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gt2fjhsdqve.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gt2yobleaow.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2bvbuodlh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gt2mfoviseo.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gt2tkbxhpbl.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2glkublqt.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gt2scasrwcu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gt2noaabvtm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gt2dkzvvqdj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gt2vukufxzo.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gt2qbqfqzab.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gt2bggjyfjp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uakfgyxj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gt2ihkswmds.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gt2sojgaeqs.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2htmvgzdb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrrvcfka.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2zvwclqik.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2bbvtsjci.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2ehkdoemd.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gt2eksqjjiu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gt2xvzkazbg.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqdfsynh.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gt2niugtkhg.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gt2bmpahwbi.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gt2rfcrcast.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkxicafy.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2wgpnohdv.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bksvddnn.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2iarxuxwq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2plxxtkdc.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gt2zfwmyvea.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gt2relqujjo.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gt2mugdmwod.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2ihfyqimf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2rhdqxqxa.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2unnrepcc.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2cwadqsfq.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2lkqddcxx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2gqqzghbz.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2jphevtsb.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gt2evjteovy.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gt2cilfzetp.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gt2cxbcmlhp.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oewaqekp.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lamkpzxw.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2okjappmx.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2xfyzdqfe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzkcjvvh.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gt2glkzlnqk.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gt2vxjaaele.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gt2aomufevn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gt2hsiuvdog.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gt2jbaswvyz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gt2buhufodj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmybrywu.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gt2awqrtrpw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gt2qxenlgkn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gt2yvmynuzr.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofoadjem.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2qkkzgseh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gt2fwdawgqq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gt2dpblzcjw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2masitbcw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2jtgjhrms.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gt2xzezkkhk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvykpyxm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gt2dbjubipr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhocqecx.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2ignsvtrs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gt2fcjtsply.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncurakuq.html

JS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2rbzqkrpo.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2qazxvjdf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gt2jhizhfxp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gt2yepvzegr.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gt2xczhopju.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2ngbbnrqd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2pjkwqyqx.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gt2vorzluav.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ziogkydt.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gt2jkacpyid.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gt2cldoabdr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2obxweqka.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2zqztmzqh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2xexunbmj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xqlwcdla.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2qdqyaoyv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2vuluhvuc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gt2zxyeoarx.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gt2yokwmasp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gt2blfvtnhb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2ezixkvjf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2ztzolpow.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2nvavfmei.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2pcyuilev.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gt2onqjuhbd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gt2wozpzmzv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ykieogrg.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gt2jmxpemyi.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gt2wbkkygrp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2mrjvbsea.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2pmyhqjgc.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2yzkorpuu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2gcpwurah.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gt2msdjkfcr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifzhccnk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2ectuzgwz.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2tzorgwjv.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gt2urdaocya.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2dhwvjdtt.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2jesrtzbs.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yshaqskv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2jsgnokfy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gt2cjazvfxs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2aayzgeis.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kicacsfm.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2fertcegd.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhahhjwd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gt2evppjxuw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2gltjuttu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2qjeudnrj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gt2wauxitza.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2uzihkgfy.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gt2ufakbzqm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gt2gpnwcfnq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2uifgqdvn.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gt2hbqqgmun.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gt2orjhapgl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2qpeaarcu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2jpmlnafl.html


<!-- 参考信息 -->