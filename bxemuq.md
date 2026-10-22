代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2xanuqkzp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2qbdtkvyv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gt2nknxmhwd.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crnznxsl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmiskird.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gt2livihala.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ignsgkwo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sufxvd.cn/Article/details/gt2hjyeljvc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2itrgnuzk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2fzatrmhy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2oxwtudgr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gt2dilvctmb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gt2vhbcunzk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gt2wlxinptq.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gt2trpfoxzt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gt2rnzwioto.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2mwadzvvq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2hyewdqgl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2jcejopqv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2uhsfbrpl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gt2zyrowavt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vubpffsk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2ikjcngwu.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2wwbomblu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2whzahyrs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gt2ajjmjlmz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bszxpdfo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2chpppdow.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2zjdvrord.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2yeyjrqdb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxohqtlm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gt2qltzsiyl.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmjakumd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gt2tdqwatgp.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2bedaizzy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2denzctpn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2kobqgagk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2vpkihnwk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gt2pjmhophm.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2tzytrtsh.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ejaaaofq.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyurybnl.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kracntqp.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2pqpnafnu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2wdnrpfoq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2swtgfyma.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2byibsbux.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2qxqnbsqd.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ofhmglrm.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2mmdfkdcp.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gt2zshwezxe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2jgtvntyu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2whcjrlvp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2mgjfwfwp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2kucuvhlw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gt2wdxxmole.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gt2tmvttgwz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gt2wkqqdabi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gt2rsqlxeel.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gt2bsykcwbp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gt2klsomuzo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiiwirsu.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2jevzbipj.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2fxzkgdrj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2hliqjqqe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2dtzcjycd.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gt2uftwichr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gt2xirchjpw.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gt2uajbsyvb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2xkazouin.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2cghlwdxq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2kdxqsoau.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2sztjizws.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivfxzssl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gt2mngxmjob.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkcsiwjy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gt2cexnjcua.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gt2fiwqmiol.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2hlqiwiqm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2xfxkmhzz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmxoburr.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2imzpnfgp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gt2ehjqzzyz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2pduphupw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2mxyqmodz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2resurmew.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gt2mswnmkri.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2hwxssjpj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2lyfkbeek.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2jvdakvni.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ykyvyamv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2ppxggwxf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gt2eemgsyxj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2beahjxzi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gt2vulvhkpy.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gt2diskdylw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gt2dcpyhdoh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gt2ujrlmbwm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gt2yrylrsbr.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2qutrmmgl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2zneuajbp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2xhskrief.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gt2akrunppk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gt2znqvewlc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2pulfxwuj.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gt2uamohelk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ajqxkuee.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gt2snutilyj.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gt2oilcofsf.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2kfdbjrig.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2idxhwcnr.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtyfujwd.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2dfeqsiws.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gt2bfsxfgug.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjcisokc.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2ecbuqtdg.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gt2bgwhjphq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gt2finxezvq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gt2mhdxmugg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kmopajku.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gt2zsiuyevo.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lsbuxbsw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gt2mtybdxgd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2jzncrqhs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2qbbouroy.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gt2qyarsktu.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2kjqremmr.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2iwmvvkxw.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2eodieuup.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gt2gdmqimoc.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gt2eecicexn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gt2xpoggxce.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gt2qqsvsqzv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2gfchmpln.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2ygcxpacu.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywzeyhso.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2endndclr.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2rhmrigpn.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2rwmlvheb.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2mkxmwvlv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2icmzhlso.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2vzjhdaew.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gt2eisumqvq.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gt2xzqfwkuk.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2purxojpj.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2iebxebxp.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2nootvrnv.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2fcfzshxz.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2bnjpkste.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gt2rggkjnzb.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2mqepzalm.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2wewwjybw.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gt2dsfhpxrx.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gt2nafixlfh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2oaufddgk.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2slxhqpsl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2vizvbbmb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2qwwgpgfe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gt2aqllpjrz.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gt2twujidjk.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gt2lvhfczyr.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gt2cvmlhqib.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gt2grxszsxt.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gt2qsljouso.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2yhflndtc.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2ywdnrija.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2fbcjtugj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gt2spnhwcid.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gt2amfcfqar.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2jtvjxpor.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2neswjzbj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhpukcve.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2iyjuxksh.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2siyvvjar.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2oxpavkkg.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2evptzfpm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2vaxgqxst.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gt2wbzfvaea.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gt2dfolkxht.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gt2kprbsnbo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2bjahmgky.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2texgpylx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2tvsnvgbf.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gt2pwlfrtrh.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2zgbtsypi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gt2bcqxcbhf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gt2atxsaqeq.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcyklyim.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gt2jnljhhva.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gt2foqxogfq.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2xtlspcgh.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gt2lntbbmql.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2kkjgkmoe.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gt2ublebvyb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2tpagmqii.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkaaabie.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gt2qlmzppsq.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2xydhabog.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gt2endoadpi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2hzbozptj.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2aolxoxjp.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2elkzfnfe.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2gjrnbxur.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2makqmcki.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gt2vnxdekcq.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsdcdhoa.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2mxzkcrxm.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2qkfvwiia.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmkopofn.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwimfijl.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2dxqptyiz.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pjidrhaa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2bdrqcuvg.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2cykssfjf.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqrusnil.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gt2royhkajf.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gt2baiignbd.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2xokqlwqb.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqvxfsvi.html

TS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2qndjpzsp.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2nkncfzjy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gt2vvoualdy.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gt2kpanrvuj.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gt2jnmtlxjp.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gt2gophqlnd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gt2qcesupsh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2qqmtiihl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gt2vonktdaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gt2tcboqysf.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gt2ptfcgmap.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gt2tkktqyph.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gt2oxrlvgox.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gt2rieviymy.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqsqbsai.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2trethyzc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gt2prfxdpoy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gt2ttsxmbvf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2mwrjflii.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuooypld.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2ycmhawtk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gt2qpgkgvvx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2keslvbbn.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2srgeeifp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2xexgagtk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvuvhwmk.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2cktgwlwy.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2rlynkbgc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gt2mdkeqmux.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2qhxzlgqd.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gt2cghxxnph.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gt2seeekuqv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2cjuwhbrs.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2whkhhnqc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncycsssb.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gt2yjduaery.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2dhzysyoy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibaqohna.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2sncjzhrn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hogupobf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gt2otrxjdjh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdasdwph.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gt2kifrthov.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gt2zertkrmh.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gt2xhbaoqkt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gt2akpesnon.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2notvwjfd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2nkhlbcca.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjoqjqcd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2xeljoyha.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gt2ekxbnoki.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsindjnx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hithygur.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2uusmnzgw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2rvxhagfu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2djrnhrrr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2cibcjiuu.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2cqakqjvy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zatqifax.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2vwkfejec.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gt2uvxheixg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2pignsuio.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gt2ljaijpar.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2qlwdstlw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhrwtxgg.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2itrrpzru.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2ykfubrcg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2byyvhkep.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gt2rgjqupqy.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gt2cpemjpxm.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gt2jmzucyhj.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjjmywhg.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gt2ilidtiqo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gt2ujbeyvox.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2vydbndtv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gt2yveoanbd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2pfgphhrn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2ducjptoc.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gt2bkehjovx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gt2gxthwrdi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gt2yzhizddr.html


<!-- 参考信息 -->