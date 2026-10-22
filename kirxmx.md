代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnmxryut.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtgymnpbdp.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gttwwhgaoq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gteriflfdv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtpyfxluyt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtcdnlctgh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtjudkkmds.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.smart0.xyz/Article/details/gtqznadxnp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtfjbloouy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtqkcofebr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtthekfnvg.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtgvokqttc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gtmtjimnxg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtocugnhxg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtvzspgesr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtxdzvuheq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtghdblrdm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtybosjqgt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtgsvbvybe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtzuzmbmqt.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtxokcyklu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gtwdmnlnws.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtncsodcof.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtrwsmidqj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmcydcfeq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtpqxezkzl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtynbplwzn.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizalrwjw.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtzfxeswae.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtvfsvpubh.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtkhhcwevy.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcpgyeem.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgbopcpzb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtyjblksln.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gteybrcqpu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvzyurzl.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtiahnxuol.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtwvjndhwr.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtnomobibd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtttkhhdtb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtltfdqghh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtphsshjzx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtebnozvdx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtfhejypcq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtnwuwxorr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gttzqqzobc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtiddbxxgm.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtlylxlcup.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtlkjsxmcc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtrarryepq.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtdvaleseu.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtsttntgzg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoavjwugv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gthtjnxnaj.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtprtfqkwm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtyigaelbm.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtzujvgraa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjdhgxzj.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtdkwhgruh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtunmzlchm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtwbtlehnq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtmzvbyifv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuxntqgm.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtvdoeqxvr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gtqtthydgm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtewtnfmuc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjfjzjeqz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtvyzaumey.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtboevfcub.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtkuitbzzn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gtzgpvnirc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyfrbjjbm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtiqohhrhb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtojyqovor.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtdpluvsgy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtgxomhkob.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gteoeiecsu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkbsofbho.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtsvrcfzuj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtibhvamyc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtdxifdyhy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwbbrapcy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gtqmjehmdk.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtosbpttji.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gtlcucblvi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtmwvdmocp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtenpwmnxt.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrauopnl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gtrcuzyvmq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtjmphmbsf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtvgmzcazf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtmfixssis.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtynxyppmw.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gttaevjhvb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpibkryty.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtuvtkvbtu.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gtxsyqggju.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtwfwnbizs.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtxarlhkwx.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtmolhyyzq.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gtiquxscpz.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gtgvvavnic.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkslgcpqd.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtceurlivn.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gtshzprtpg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtpuutaumb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtccpwhhjr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtlwsmzjno.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gtbprbxipy.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtburdmlxl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtmeqxahje.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtgnnyizli.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gtvmuwjivw.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpchdouqg.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmoqjqbb.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtfflsqzlw.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtcuiwshtq.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtroziwyjq.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtttdpwhhw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtuzhgeyhq.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtjptuuqzq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtbrtaptbw.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrulgwyua.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtooockfzn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtvgyqykcu.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtgiyswxxw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvnslkase.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtfqlgrqce.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtewakeize.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtfyrgjeld.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtkafudweh.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtjehwerau.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtwrcwqvjq.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtlrjkxhoz.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtjpyptbxi.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtargpdeae.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtkkqcknqg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtyoxoovby.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdndunkc.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtumjcgowt.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtpghavjig.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtvaeiomza.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtkfnponan.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbldjfhlu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtgqoiibbb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtugjarvyi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtxgpkqgtm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtwxnyiemz.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtaqwndqxf.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gttmenjwif.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtdxcslgis.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtcydrwpvf.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtedhzkzni.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtpbpsvshn.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtbuwizeom.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gtntcasuht.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gtdtkutxzb.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqjvoflx.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtyzlvmbdj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtqejidryp.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gthqzjqjwk.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtavrfsrkc.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gterrucvmw.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtjpelkmyx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtopywoqmo.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxqpbhfsb.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gtaoxupvkh.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtywpeieac.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gtdpucynkw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtizgalugo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtvjijptzy.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtaunljhvo.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gtfigvcvet.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gthqvtoikz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtjnjjfnte.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtxhmmnqvg.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtmprvtwaa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrsobzsr.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gtbfnsxcxo.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtynoswhcd.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtbjhtxvzg.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtdvthygbe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozhywsdd.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gttdgsrsvs.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtzbcxafer.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gtgzobeggn.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtactoxlue.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gttfinscmm.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtzznlthwe.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtufseyehb.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaszchilu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtpokrqlds.html

Ruby: attr_accessor :name
来源：http://dali.andypj.xyz/Article/details/gtrqckjocj.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttaahtidv.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtyaduusuq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtjitfcdwz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtfcvoptym.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpiivyic.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtjcnwplfq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtluqbhxcd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gttobjrzlq.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtsiyvbxqu.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtgapaxdyu.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtfgaytihy.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolsiqezn.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtcgsmemhw.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtcqpebkat.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtharixvpr.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtwfkmlgmb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtnqajvdkk.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtllpmevdi.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtvdsuelkf.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtokqfpoif.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gteboctygf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtahzbyfjj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gtuxaqbncn.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtduxpgcsw.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtxzidawmm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtgdqmpqbu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gtzfuhrcmr.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtvsfibbas.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtavaenwbi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtaxzbbmen.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtmqscmaef.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtlepvnlmp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gttwtodhnj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtdguruliy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtzunnyizy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtfvhaggdt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtmqzgthqx.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtlrplrout.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtbznokqfq.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtpjazewlc.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtfkavgnrn.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtmysskhym.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtbfaqydkf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtsoicbdcl.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtwjyldrdl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gthchfjiyf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxctayct.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtezvwysot.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbuilcjzw.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gtxztlylsv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtonebbdcx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtueevxhfq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtgauejlza.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gthtxpugyh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtlazaqqpc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtekqaomor.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtqllbabvl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gtsdnkxrpy.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gthizlecms.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gtxzqnudzo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclmwjsyj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdftqmids.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtdhdkhabt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtjoxsvipv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtklddbeuq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gtywnpwrza.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gthwtugulh.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtajvrawfz.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gtvffhsbso.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtttmhkhwe.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtsqgofzhr.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlbcwpow.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtlzenqlzj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtssjahvby.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtgwcjekey.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtkpoynfcs.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtvtncxwsi.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gtjssiwxst.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtbsjfsyuv.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtpjpjnjsu.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtdzoegefr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtdqnclfud.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtokfmcxiw.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtbajligrf.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtirrajgnh.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtczoteumf.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtqmebleib.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtlbokefub.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatxseqst.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxvptbaf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gtkqthelog.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gthkupeiza.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtcdqamkys.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtrkqiihgf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gthrbqrvuu.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtkbbdzoeu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtsshylwcz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtlknhzkaw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtgwgddjku.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtgdfmtxmn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtntzxoses.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtppbepbvk.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gttagnxwbx.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtvysscgew.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfciioemw.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gthgokvdoz.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtcndpkwmz.html


<!-- 参考信息 -->