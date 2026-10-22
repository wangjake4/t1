代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gtoobdrooq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gtnotiuuxh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtavkxjrzs.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazuyryyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtlskbrhne.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gtqfttziac.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtfuubvrwm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtbswqqdnk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtsfwuyjiv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtzquruvwa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtfhutbwvy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gtqpzckmnj.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gtfcabbgtn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtlnfyurxu.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtlgnyhrxc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtkmvirpqs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtyrfxpusu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtgxphfgtg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtniznsgho.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtuspbhooj.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtbvkrbeom.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gtaajbvcwt.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtlrvluftb.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtzvozvpcs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtwtwifxmu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gttspkbbbx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtixjyyapv.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtickpuizf.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxxvybdl.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtyukihvdy.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtizxzhlxe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtedermfqm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtaeexvmft.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gthvqkumiv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtkqpgqapx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtrjgzhkge.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtvkjbtkgd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gtxtpxueqd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gttbqnthmg.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtnhrhtels.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtiunhkvuj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtjluhtwqr.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gteibghqzp.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtjccshxfj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtmkymgjvk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gttmkwglwq.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkwakgjk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtamtcegiu.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gteldlonuj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtdivmowac.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gttkutthpz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtqkigwmhx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtoypmzmwp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtwoleiiri.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtclpobkiq.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqcqxsavu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtjvmdpypr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtsuvwaxso.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwibjblwe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtswviiirm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtclrszjcy.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfqyzxqfk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtqspeflww.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtddwloqsx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtggwzfrah.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnnggaeca.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtzwbwtfpc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gttbmntreu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtxwbkelns.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtydkygiyl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttebefuym.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtysstfnnv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtezwodcrv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtdcgchnob.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtjbynmcnd.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtzbmiciqa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtminfgedu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtuqcuzjim.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtxatyropl.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtvwhoamxb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtkhetyjdo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtikxvvonx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtndezeqao.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtgtezmvfd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkguitipp.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtnnliqgke.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbbhotqfk.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtvvfyhrtn.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtdsfevxet.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtixodwkrq.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtmcrpilkn.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtreakgosv.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtvyrrnces.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtflxmhnhq.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtpwjrlzjt.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwbjaqwkk.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtilamtwoo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtmallwqpz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtefjvryut.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcjvihdm.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtypbxoegc.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtvdmmfpth.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtuwwjeafc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtyfmuehiw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gtpulysamd.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaejzzrqr.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtgkyutfzy.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtefgjbabu.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtugrdgzeu.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gthbggdbzi.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtazxlaqen.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtiabdwapk.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtnkspbxyo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtaksfzmof.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtntzipuyl.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtqaveeamb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtgrebofno.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtqvhpioxq.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwwbexayf.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gttlzppqkx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtqmpvnhio.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtiyrdbetr.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtsflndeai.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtdoopoxid.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtqcyqikqp.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtnkxmoltj.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtgdbtoeki.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtedmtdkgm.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtzackpfva.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gtslxlvffy.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtgktsxeug.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtmmbsacvd.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtiehcwyyg.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtmrqkeaep.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtkdsgyamo.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtmdgjfjce.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gttbcrccwc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtqigsxyun.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtnwovxalx.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtwmwgjxky.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtluzuifzf.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtpllpzgtt.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtpmzygioa.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtbodvhmrx.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtheajqdjf.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtkewnsgts.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtblanbqml.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtnqatwuqi.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtufmwpahq.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gthbgrlqvo.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtkzkolqha.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtkcunnoro.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtfsgssnlb.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtqodrbnzq.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtrlznuzti.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtzflrtlmx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtwwlkfnpg.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtlvtikscp.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gtxkeqznir.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtpvmiunfx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtlgmqzvag.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtqnqvawws.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgoapfts.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtexqqpjsn.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gthrbovdcd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtbvqyeamc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtwggknewq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwraohye.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvlsexth.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gthflnmfwy.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtscgjqjyq.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtyiwoikrr.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtmmsphkrk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtazehjoat.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtamxdhcak.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtpfdeuqqf.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gttpffpzyi.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtfcazsxyh.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtafgbnznq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtysmugbbc.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttantojar.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtreqlveih.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtsymevykq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtjmhscomq.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtclfqdkfm.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtbyyhouys.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gtamyvoemm.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtaodasrpi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtvhpuorvy.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gthfsmhbvu.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtldhajndp.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkjfradur.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtratqrtkh.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtddqzhdey.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtyxxylonw.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjdmlujg.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtiapmhmok.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtylndckaj.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtvatxqwje.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtfrtbzeur.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtnmiaqvva.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtwrzypuvl.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznizjolo.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsrwazjw.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtldizapew.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtwyzmwyar.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtwgbfaveg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gthnovmlyg.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtxmnqmmsk.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtntmsgzvg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gtneqcgcli.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtwinhdlqq.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtvqjxtkvl.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtxgtitmil.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtaufvyuqc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtppapxrza.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gttksjzqib.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtuvkxjncd.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtrszhpqmx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtdaeslwoz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtauasefok.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtijipifgx.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtyljiorvc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtayayvdyr.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gtrdemwdgi.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gthhnswkna.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtkqpfoxwt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtitboudqm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gtldehudsm.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtqtmozfww.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtubnhshpv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqiwjyvfq.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtxrpaqqjd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthnteoils.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtaqszdxme.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtpucjrfvg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtxrbbaqmk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtvhjtzwbm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtxqcgrojp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtslarmygy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gthvkwlspv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gttzqduyez.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsxhuxwpk.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtyltjilpj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtryudrnzl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtskgusvwi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtiagtawjl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gttnnvimxa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtqsujssor.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtjauzifcx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtzmwogsez.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtqdhddkec.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtxsrfzujv.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gtdbncsoje.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtvgscmufc.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gteufgxegz.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtzbtpypfw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvjcpteq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtunwjjdyn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtjtxyxpcc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtxxxsdkts.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtmiulsdpj.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gtkolqdxjr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtxkaerpqu.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtwhddhonx.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtcletjktq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gthiziaxgh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtjpzufezh.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gtsymsftbj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtugjfbaqa.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtolbkvdqj.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtdrybbtyw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gtsewrekio.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gthbvwbfzx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtbieonrsw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtnjelsvsm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtvzmbtyuw.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gtggmkqqod.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtpikyqygr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvapoply.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtuohdeauo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtucprhivb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtmzwtough.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtxqjuzxpc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtwoaxptmg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gtywvcvdnz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtkcqubyly.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtggpccjiy.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gtauylzavj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gthowaibyf.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtxgbkbere.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtsijtruih.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtepzedzvy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtmcvyabym.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtzphcqumf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtveolasxh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtbcitsrvu.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtajaacivy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtclcfffyo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtvdylfpoj.html


<!-- 参考信息 -->