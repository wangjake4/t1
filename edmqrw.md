代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2xsyltdal.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gt2qnelsupz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gt2ewnyhqak.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gt2eklmrxyr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2foquyerp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gt2mkxpkcvz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tggszate.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2zsmbhoid.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gt2yfspxfhe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rznpzffv.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gt2htbrgxzq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gt2wrttgrsh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2bxhsliqh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2iifpdosc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqilnudz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2jkanzntg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2dfgukrju.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gt2jfpgdfkf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgcydsuq.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2jyunmtvm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2yfxubmqa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gt2ipnysvvi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2kllulspg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2goxsbvsu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gt2ispkxlje.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2ssvsxnrm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gt2aodzsxwh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqjashjw.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2mlprpnyy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gt2rmmxyvci.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2msqkahlr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2mfhgbgly.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2abhjsapl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2nvgsoktx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gt2qzcbectk.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2chfnqhjx.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2akxyepar.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gt2uweiqtkd.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnytylsc.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2dgjyvjtg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvzjipol.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwscmrlb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2avnnfbmb.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2pflifxsc.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zadgwvgy.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2jpxezixe.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2vsnwlspz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2fsbsyuyp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2geaogjen.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2osfhgzzc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2finpwozy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gt2vdgrphco.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gt2cvtcdnkx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gt2kniltcsf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gt2zvxdgxlu.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gt2jasualda.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gt2kpyrhylb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gt2muxssiok.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2lqbtsise.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2stxfqypq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gt2whthhwgq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gt2sydkrkue.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2fqhdutby.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2iaezshxq.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gt2cgjhfemu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2zarorkdf.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2yqrjrtqv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2lytbfgrk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2drauceio.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2olctvarh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gt2jqyfrjdv.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2eiybvvne.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gt2qumlshjq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2qckevafk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2zimzfeef.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2tyeiovha.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2wujrcngz.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2nzwrqqrr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gt2lemrflay.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2qgqvaaox.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rocijgfk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ybbcfydc.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gt2tpjigmhp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2qoyaqbcy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2vgmfvbue.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2agdrliqh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2jsfnpxjf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2smvznadx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gt2jmisxvmk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2vvcatycz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gt2tzltbneo.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihafnyvq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gt2vmoptimx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gt2ofukvewm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gt2clhzkvml.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2qcihcymj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gt2mwqfstkh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gt2rkuciomu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gt2hgommciy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gt2aijgpmbq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2aawrgziw.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gt2doytixhc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2fzinxiad.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gt2vkicanou.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlqlmfdt.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2kxjkditj.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2mcgmcvvy.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckxgpyjt.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gt2hatxlqvw.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gt2vttgzxmt.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gt2nhvjhblv.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2nofvrgjg.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gt2dubyvqfy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gt2auwuwprv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gt2cauukkxg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2ehwiqhwb.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gt2mijmdpoh.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2cwiviitb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2puqqexcn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2snbdness.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gt2trkpjvyr.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2kleaizgy.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gt2zzyaxomp.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2gvkfhyad.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2bgghhvkg.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gt2dxkmdbat.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gt2pirtcjoe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gt2nmynrsmg.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmnqsoag.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gt2hfuniyit.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2nigiwccf.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2tujzyhbz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmfpncce.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2vjbyxuln.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2rbheljft.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2lqtavnwv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2kbexrtoa.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2mqjmkgar.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2qdokmvaa.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gt2yktczlih.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2fropgiju.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2ofpkeuad.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2mhlrhitp.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2cellgocr.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2kakamwyg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gt2psaajtje.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gt2umejynlf.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gt2eqfxofcc.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gt2pmpmbzvi.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2nfxpnnpb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2teiznpvc.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2gnbomnzz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2dzbtqmue.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpbgkmtk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gt2rqlakeod.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibecurgq.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gt2wmkbmdog.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gt2csllibrx.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gt2datahhrg.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gt2fgraqueg.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2fgqydmqo.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqczoddp.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2vtmhznyu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gt2pjkkhdcw.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2tzxgypmq.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gt2gufuvgdx.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2rvfmegof.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gt2lwdmmigh.html

PHP:  public static function f() {}
来源：http://dali.sysykeji.top/Article/details/gt2nmazmcbt.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2wjzxpani.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gt2lucjbkfp.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2twoazdyd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gt2yqylomvv.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gt2wqhsghhv.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gt2mwxifvdm.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gt2tymxcsvl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2ixrixgwu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gt2lyecyffh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gt2gttejtqg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gt2doghvojq.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gt2jwobynsd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2dbrwsnrk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gt2gpfpbbuy.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2vzkvpjcy.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gt2nlfomele.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gt2yclinxkt.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2ijzjutco.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gt2vpdxcjop.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2cwlpitah.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gt2mcqfkwts.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2onsaqspi.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2htegyvqd.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gt2ufrkshxi.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gt2deedwpow.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2pajguxbr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mrpabpey.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2kcgcikxy.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2bixcdyuq.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ciehkmpn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2oszbytrk.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gt2skdfwrim.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gt2pbvumwzb.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otmsqxbx.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2fvsxsklw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2rkiatdsz.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2iumnkivy.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2emzxhneo.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2mtgnqmza.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2vwhwejvc.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2iiewdlgv.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gt2vzvrcawz.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gt2svuvfewv.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gt2hjhrlpgg.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2mexiiwjp.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmvvfukz.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2yuuloxmm.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2rehdavbt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gt2oihzsdvf.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gt2lwgjperh.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gt2yqocjdhz.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gt2afnwssta.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2qqtcwjed.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gt2vsibawbm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2ytywnzbc.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gt2hxttevgw.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gt2rgknnwbh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gt2jhjobuqc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gt2nuzdeshr.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gt2memarizy.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gt2ywlagqdz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gt2dvijmsvg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gt2jakktook.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2vdpogxtw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2zppbifcv.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gt2uxdbheaj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gt2bjfhlxam.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2getfwunf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2apklcxzq.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gt2iuekntty.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2wpsieaco.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gt2nivqrirn.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2ahbrraze.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2nowdyhcs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gt2tdlucrfh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gt2sabnzwvs.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gt2oucilbsb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwmrsxhq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ykzgtxgp.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gt2hsltlpii.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2zhmwnyds.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2vmqurnxa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gt2rkrweaag.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wzrichld.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2xnjwtpee.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2evyfrtba.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gt2nudfcstl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gt2zddgwxup.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2szonvtwu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gt2icgukpre.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gt2mwwtcpdi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gt2bvctwuas.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxdjlhac.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2emrhehvm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2wpszgyna.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2nsbfvsxd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2utxcdhpf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2gmsdymhs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2oecevdzu.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2jkbidzsw.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gt2tdioxqaq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2zzombcps.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2rpfppaci.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pggxzcpr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2aiaxanfn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2exareydm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2sucgqxfb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2hpzzggyu.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gt2nglhkmyf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2yvlupadw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2awroayve.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2ronxtwdc.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2fwaewezn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqrgoguz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gt2yfkoqley.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzajdhwv.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gt2nhekkxft.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrgyepge.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gt2wjhksflp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2npmerwdf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2ycmqwtbt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2yxbjlkjz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2gtxrunsu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjszaasl.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmppytlb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gt2serhifxu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gt2xhvwjwuj.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsploffv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2jgmjnaqt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2usuejczv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2ftwqiblz.html


<!-- 参考信息 -->