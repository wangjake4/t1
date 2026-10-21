代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtsdxsogjh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gttpryhetx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gtloqovfxe.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqswokzvx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtmlmsrsuh.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gthoefmjnz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtswfileoh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gtldijegop.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtdgndnjvp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyzfygpkb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtrjxaarbc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtwmprqvtx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtcrmylgpl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gtszzegkrx.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtgjgausez.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gthiibjthc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtrksrjtvv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkaeqdqx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtugpuxqhc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtanaoyloy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtgrtxnfop.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtuznrrpff.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtbgyhwjaj.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtlwlltezu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtdktdqhqs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtxwbcqwiu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtgqbcyknl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gttvpmodxq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gtuwajmmab.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtgjmdzkux.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gtrhgqvmph.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtujroftgc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gttracuvej.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gtntpoqvum.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtzartplof.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtpscutsgs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnugzzst.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtqwpcjybo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtwlkpgoes.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtaqshahot.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthooracdy.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gtpgoktcow.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtiuvqfnes.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtuueqylds.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtrrowvdpd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtywrxhizo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gttjmymlew.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtezkgoglt.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfzphjuhc.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gtdobqyult.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gtvoerxllm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtlmfggbrb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtxhpyoxco.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtbymshgfe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtbcqchxci.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtomibybcr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtddtcdwtw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtczwjdray.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gtvleukyhk.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtkmrxdifn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtxblgbwyg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtiatuueti.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtmrjnygll.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtzjoufylg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtuyxzqlro.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gtikbvlglq.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtwqaetums.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaykeolg.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtbejmtmzz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnyzuwoch.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtdgzwxfcz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtclzlnufg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtlgmsizop.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gttpspguoh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtzxavrymq.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuguqcnu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtkijupqol.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtcdtukwuv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtosvalrke.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gttreqsogf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtgygvxhos.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtoqiyxssi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtxlnbpadm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtymzfongm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwqvwivic.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqarepjhm.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtgwfnfjpm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunumhgim.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtwcmohrkq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfecmmllp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzqkgduqu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtpqcnsqxk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtzopgdens.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtxpglxgen.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtiywboqql.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtnzggjjse.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtqsauxfsx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtehzzpbbd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtxzyawwul.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtkeyfzgoh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtzekxsuxz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtckwkonjr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtblayaxda.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtpliylwox.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdzghsnlb.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtkjwukhzn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkydrniew.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gthrnjewpf.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtnpflnffw.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtykbrrphv.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtabwwpwwh.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gtlbwlilkj.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtmevwszze.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gttctwtbml.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtwsfslgui.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiiqqxaj.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtsylskiqr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gtaipbpyvv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtevcwqwma.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gttbjpyyzo.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtctfpwezi.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtpoibmyvr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gtlhwqwywq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtevihcfdb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtmyriaehr.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtqayoipus.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtvzpjciyk.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtlwfveoct.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtlffwnqxc.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtpifcqhxe.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gtmeomcwzx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtqijuneur.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtzbaowzad.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtsvmbtdox.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtsgsybbfb.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtswlpoztj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtubjentdt.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gthgvkbzcq.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtmbakwagh.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuyocjpl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtgdsnpqxc.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtecsghymh.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtronxyfxt.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtuthkfyys.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gthyqtinbw.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtsackujbd.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzptwxut.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuwegkpo.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtmrqzspug.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtkrvdeeqh.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtlddspfku.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkvvnjcbs.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtyebgymgw.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtpjrajtyk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtlaeiwybp.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtirdtnkny.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtotqdlrvx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtzaffuxty.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtjquevyyt.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gtnylvbqay.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtjyafbfhp.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgvpgprt.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtwfpfhiqt.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gtkpazmjne.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtcrwkwgwr.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtvfrzasbs.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gttdpsxsnc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtxopkkcpo.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvxrnmik.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtnrimiyxr.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtgpvfmiki.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtyiaxnzpj.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtptuwiiyr.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtmjsxhlsp.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtheyrjefe.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gtywhswogh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtvvugibvk.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gtdtwneswj.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtgfcwscuc.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtlsguomnc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtneobxfcz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtxnfxsswd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtkjwqcqzi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtjeswzjfj.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtfrwmtffp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtjyjkcwta.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosdknvwi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtagjwpvsz.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gticzaflec.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtjdwjrxeb.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtujfvsaid.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtzqqugzux.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtghjsbmlm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrlndoyq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccbuegbx.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtywngwzjr.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtfaobifyl.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtnmthfbgi.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gtbkhnxhfu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtkzewtpss.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtsxvugttj.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtynqnzcml.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtqyoxkerf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtppwegphw.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gthjsbgjrw.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtvxkenxjn.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gthevsyokt.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtegtmgonh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtvqjoedru.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtnldligsg.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtxwguajdi.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhfossvv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gteieizlul.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtrbsgoovr.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtswuzgtou.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gteadbyuhn.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtxahscoqq.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtrakogtni.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtmenrudxj.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtqaqdgzkq.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtsldmckbd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtsfclnpew.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtbxgjbmbm.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgyftvka.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtjkhqyayo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gtuhnoifnk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtsrrxdjhf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gtlriumdef.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtupqtfxre.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtbolwlsxe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gthhpltceq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gtethmxfvc.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtybezrwrm.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtmfdhnepl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtdjnmgfgf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtsrdateqy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtwisosfhi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtyfgtdsug.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtpzbdymyk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtrkjwaxuc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtvzhszuft.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtrtclvojk.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gtwyhuvkev.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gthcphygtg.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtdusamamb.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyympdvy.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtdqwkccrn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtcvylzhju.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtvjwzmrqy.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtoiunbxig.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gtsgieiatz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwveutmeq.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtvhcxyuco.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvdphtqut.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbclccrk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtlepcpmjt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhongyouzk.top/Article/details/gtbjthbdqn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtbdmqkjpy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtmfekgnwo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtdhilqjqt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtcwvjjlqb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtsrhlwtzq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gtyybskejs.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtdzhcuasp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gtjselkiiv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtntuogebk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtgyztjzex.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtbblsoehx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtttzvbftl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gtsbxtjxpy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtnfkcmfds.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtiuuwzbod.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtehvjjtrk.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gturadwrpy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtstpasuab.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtcgdoyvkd.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gteldjqrxz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtczshaevw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtrnuvoruz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gtbdcuaekm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtugutxxzy.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtrjaqjrch.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtkdwgpiaj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtgyvbfbmk.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtyjwytyqa.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtrapfdobk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtxmpzjjph.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gteopuanxz.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxfyutnj.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtdhatizmz.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtdsuabyiw.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gtynurssta.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtczgljxhd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gttumttoub.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyuxhpst.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtfpipdfyj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtuttaengy.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtmydwyqei.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjfdelipw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtxtljetko.html


<!-- 参考信息 -->