代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtodqdvbne.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtxlmgcmve.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtpukezrno.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gtnyjyrudy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gtatrbppcn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtpfsvcbvy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtqtjaewho.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gtdtetnnlz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gttjskpnqf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gtxgdkphsh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtiltogdwq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtgcdtwiro.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtyvudbkdi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gteewsmpyo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtqxpcssxm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtqfqtxeuz.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtklilnnaj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtgrffimdd.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtvawslbro.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gttwjhzfdq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqojdxrnf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtdxtpnoca.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtpdrpjdad.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwzagdhax.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtoficvpjl.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gtlitotyvb.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfaxkziky.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtbwjexcer.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbpxztkqy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxcjfbscn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtpcnvowqt.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtnowbhscs.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtpsovmehz.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtfmirgpmv.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtjqfrpdsb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtmkkdbqpq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.quarkkingdee.top/Article/details/gtdiokafjy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtnzoppxly.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtmfvfmszo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtkkugtgyy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gteknayexc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtbwlrpqzd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtrepnjwgt.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gthwlbfqsf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjmmgpqn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtbvxzlcvq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtsdxhmwuu.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtvwjbkgwv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtljekcaed.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtmsgzcvpd.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtzyxiqmes.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtchbtmgeu.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtxgloqjzj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmslyanmn.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtulayrtvq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtfskjyvno.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gttrngjutp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtfcnqjupl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtemhzhbux.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmrpqppin.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtcxhwuzzd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtvgamnzdc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttuxslhty.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtryvmseqo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjyvpgun.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtfabnkpei.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gtehgfbpkl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwjdomrwe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwnfbsouu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtofzsaxxi.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtwyrpnkwl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtmkhvgcar.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtrwfadffy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gthinmpopp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtnujjxqal.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtlfiynczx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtdxzzrfoc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtkawhedbp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtpdjmueks.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtqjubtdxb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtmektkaxu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtcwdqlygf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtyjnknxvm.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtbuxurbhc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtraogvkcs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gttmsbhjdp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtayurugxk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtmhvxeacj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwvvgtzva.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtorlqjmwe.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjxuhkcfa.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtdzybjknc.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gtqbfmkhrj.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gtoktvvbbo.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtkdmdapol.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtmuqqazhl.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtfhcegpla.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gteuoyncgx.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtktmmavoe.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtnxmerjop.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtncjhlbcj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtvvgzlgww.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtwmjdkjln.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtvlnoqmoh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gtybtomekl.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtxghmttbo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtprktsjbx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtjtekaoly.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtsnkdpzez.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtywgeioue.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gttrosaenj.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtokhqxvlb.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtdfejenlz.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtyelhqohu.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gtltkusxtp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtdzcwmjij.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtxxknphvd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtjcnglrcz.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtcyyeypyi.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtktrplfvw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtjkvhcjxp.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtpjusdpbh.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtphbpyefj.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtelnvukhc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtfwmjtknl.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsihlbjp.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeealnbq.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtcwomligk.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtktbqypvd.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdpkqaizv.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtesshnfpo.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtizdkmonk.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtdshyawce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtxfcvygrv.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtnkufvfou.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtmnrpchik.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtenwdfnwf.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtounladvi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtjpdcsfzj.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtjfppexni.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtuadnnsbj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtrssknunb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gtubsgwqfz.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gthptlwayc.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtueiefhip.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gtattbduyy.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gtssnkzedx.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtaffipgkq.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtzpfaycbp.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtubqteqlb.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gtmjqlczij.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtmhkseipe.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtwegombtt.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtmmwieutj.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtlmarsiqv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtsegpqbiy.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gthrotzwry.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtnddxczlu.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gttlqnzglz.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gthxmbbkzt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gtfdxrbwch.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gtkpqbkyam.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gtboapbupz.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gtrpgkpxay.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtqvqqlnky.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtkyfqeivv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtywarcasa.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtxqgklvzl.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtzbfatkwy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtguolhrhy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtlbqqsppg.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtfwgyrqwo.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtqovojmxr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtusjhvrpm.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gthtqgfupu.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtuiggeubd.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtrniyfesr.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtdfhglicu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtqmeoeitl.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gtfkkkrdne.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtumgtccni.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gttomujueg.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gtchvhtzsx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtflswougx.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtigsuvcwy.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtculeqmrh.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtqbirmrxx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtpcwlkwmz.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtgwtkcnzo.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvboknnes.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtmjhyhtxz.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtrqvfwmdg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtztiscqrz.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtknsjqfbn.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtkybrakbv.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtwvpbcbsz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtmladfzjq.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtusgehlib.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtnufbkfdn.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gterumpikr.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtddrbbrqi.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gtbigbgzjk.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtcsjcrzti.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtlgurrnbx.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtscevvkut.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtgzovdxae.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtezmqbmge.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtqxbamqly.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdmapbmv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtnkyuxnxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtkzkncdio.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtndhflvbo.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gteafrjvvi.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtkaupojgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtsbvdivwm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtnljlgark.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtccvzwsiy.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtykhpkzbr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtvbantsqy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtzjpgtouf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtqpuptpch.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtdhuxqtdv.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gttbkqmrpd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gtbjrpdzke.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtdphyjnar.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtmabehzle.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtgvglmive.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtwkhfzdcn.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtphuhybge.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtidyjnwfu.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtytkcwyei.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtrgvddmxq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavfvujtc.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtdxrofgwo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtkzchmzst.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmhfpuacw.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtszsbjxme.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqqdrwjhe.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtxajvzqrx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtowtenuhn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtymudvhjl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtkjezryig.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtvjbitwow.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtiynotyui.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtndxwnyao.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtcxbfihqt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtvuiarnqf.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtfuleflqz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtravhlesg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtaxmnfwlj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtodcjqzif.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtoqrkvkja.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtcfcdrmfg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtkiajvbaw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gthkvetyzx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtnlckgbjt.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtosrvwylm.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gtpquvuvdv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtcjbivspg.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gttenhnhgv.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtprgvqykt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtmtuinpav.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtqjldyimi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gtgopuvuaa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtzcctnpth.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtcptmrrry.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gtdcigxtzt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtauqrdn.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtxjuaslpi.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gttchejonw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gthcfcctxb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtbpotfdca.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtuykypfya.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtwtfpijha.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtuzkmpepw.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtkihegvhb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gthvtumzfl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtabtirytu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtefmazane.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuffnddrm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtjzgqjbhx.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqkbxwvx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtsoqkziow.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gteibehqss.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtkmoahspp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtpkspofuj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecyhrfbz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtuulgvoxv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtmwbghxlt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gtxcnvgsen.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtjcttjgdj.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtefhylyyr.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtnljxcqtz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtcdhwxcqi.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtgxvzxogr.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtjprgvwru.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtclqehwnq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gtosffotee.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtaajlplph.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtgmqyhgat.html


<!-- 参考信息 -->