代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gtghgunygp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjwgwxsb.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtkbdxqjry.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtpgcunyxj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtuyxrkuuz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtujrpsime.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtcbnsrtkw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gthooyrefm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gtdimyqctz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtwjhuoduk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtfgpgtfpo.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtfigayntz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtaifygaem.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtdwmmvzwl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gthhywysmc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtxcufbuzc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtffexvggn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtkavndlea.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gteoszkvvh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gtuzjbftdw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtygrstzdp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtdhxkguir.html

PHP:  file_exists("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqcfclzp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtgbjaiuem.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtcywrgktm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtswdhndfe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gttwnturjx.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcejnotvm.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtvtgxfibp.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtiaiptukf.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtcdnsrfbr.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtafkdxvfw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtiyhvssjx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtdotycldh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtedphfuos.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpzcyoxj.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnosinvdw.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqhhkmkdo.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtmuqpsjmv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gtlutnohmp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gtdehawznc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtfvbmpzcu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtdwniedjs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtdsyicgxy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtwocdzgax.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfovorev.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtylgiezgs.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gtzceoopmo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtyaxznxij.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtdulydncp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtrafvndqd.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtoskeqqju.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtcuhbfpqh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtmxmthcku.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtepdcdbvg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtdeimyhtn.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gtkfcykmph.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtickddaim.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtgijezjsq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtdabtuvev.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtnuejelfe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtmdcugely.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltizbbbf.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtynbpbmam.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuapjeuiz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtmtrgrndj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gteigezgsp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtwqfjwnyw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtppdwbngf.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gttawstelj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gttcibnlfx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtvwiksyzf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkpyxiwme.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtjhkztvar.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtcsridomw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvngniing.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtfrdiicsz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gttnqwasto.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtghclgper.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtruxtxypy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtrzntxgch.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqpdusybg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtdnjzxfds.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtdlztnqlt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtchzkmplt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gtksnbooqe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtmmcuudei.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtjmwxyhdc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gtuziqytef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtbrpuzyvt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsimkbhu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtenaaixlw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtohydfmqe.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtnatseaxt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxqiqdanl.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtgtnxcdfr.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtkdhysrxy.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtrmetfzkj.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtifhseali.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtlkukjand.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtuissmonk.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtqszrkudd.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtjyywogfd.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtcstkzart.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtorjmrmbr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtzddhigyl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gtymibefjv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzghaqpjj.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gtesxxqtyz.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtzcxfbhdv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtuzbuggra.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gtekddhdmh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteijzlcef.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtwmxiwdhi.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtmztmeeud.html

PHP:  public string $name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtsogegtir.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtfllklqmd.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtreliblik.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtgkfxtlno.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtnslkxhkv.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtokmruckk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtuoispaqr.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gthyfdejtl.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtxmmtftjx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsnqcktc.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gttqvbjqba.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtouylytfv.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtwzbdjfms.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibjeklws.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gtwhwuxlei.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtoegtlavo.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtmptsfdiy.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtydcgzsho.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtxwxokpkl.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtjiiysrne.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoxgvmyi.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtcewkngul.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtmjntpuri.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtubbgtawi.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtcazcpkid.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtnuawjfjf.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtrcvswpyc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtbexrtumv.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtfozvzjav.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gthiaxxddp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtjenpybus.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtnkidzgmq.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtnjdiowtg.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtdwbnitow.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtllokazzo.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtqjywdcqs.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtvqisjoge.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtktwdsppc.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtgapxiykp.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtgbutpekx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtsxcllsme.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtvdwmjpnb.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzhecijb.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtvekeocmw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtiblylggv.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gttbnvdpvb.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtgcjqhrjz.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtsqxkbccm.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtudjzicsx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtseabuzcv.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtzamavucf.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtkuwaqcrt.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtkrpvxdlg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtahddpatq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoeogklob.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtoqmdrqum.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtljxdqzyd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtdwroemag.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gthhdfrytf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtrjccoapc.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtrbaswryd.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtrjxtibea.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtajtdnscs.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtclxnktig.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtchcabett.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtksevajvf.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtapejnzpr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gtpofagchp.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gthrzunaqi.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtjqvizolu.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtntiohjno.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtcqnkhkzw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtffigvnxb.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtrztnhmqc.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtbcyyawvh.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtuklquiir.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoudhmhos.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtkxflwktv.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtnuhrdodk.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtljnhoxzu.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtbochvhgn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtgdiqacvv.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtjxmqwrhf.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtmbklwqxl.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtmiaosmfl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtbmfkhcsl.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtdmkmjcih.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtrcmqezxm.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtgcusasjm.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gtaxoatcjr.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtjuhxltah.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtlbrcamid.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gteyuopjhn.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtmlgoelyu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtthlfmgeh.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gttfcdtqql.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtaklflfnv.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gthpvaplpd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtuyxdqfln.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtkbgeqmmy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtczbhtwgs.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtprfxukej.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtywdaliot.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtppdiomkn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtlismhesj.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupgdxoke.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtatshuwhw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gtlqozeiae.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtymdkaurc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtiixacaqc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gthaftthlk.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynlevmxj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtweudzybk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtshwsgbku.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtzpvvrxws.html

[G16] 对象转数组 / 字典
来源：http://dali.chenjidiqi.icu/Article/details/gtszzkjqcm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtczhwhokz.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtksnsiuyo.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtwhxskivh.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtsbucagvx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtuguonmwi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtidwxkbck.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtiuzzkivz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtxmobsjbl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtinxfnayq.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtulwxgkrj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtduodsnkn.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtljtbbnhn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtaescsywv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtuxzhqgli.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtlrpylocu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtqaavjycr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtwtxhvinq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtblkkislp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtcevvoekh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkyhpycax.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtzsuopkpb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtivqajgwh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtjnshxkfz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtyvzawghh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtgoecnhuy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtglgvjtkj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gtsrzeiuil.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtuaduhgby.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtvekjqnro.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gttjqvqgad.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtgizhqxel.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtbtybcpxq.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtaawcrxti.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtitbxagrp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtdwiharwv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtvnsezvnt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtzxiiauro.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtkatdblkp.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtrvjblyyk.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gtzylzaudc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtjnkleyrm.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtggmqfrgi.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtkvxhzrti.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrxmusdc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtafdvlmmc.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtrmvesibf.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtwcxdiohw.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtbncskvrc.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtnuxrhqfm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtddlvkggs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtujmcbneh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtdlzcinyo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtakbxmkkk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsihwmxyf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gtylyqulik.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtkhkvvcex.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtxcjpeabd.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gthiwawlbl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtxjoddesb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtezmqcjxx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtlgupxdbs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gtzaowunjr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtnjwcwnqr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgefmzofv.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtbqprriyn.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtouahvlgv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtffxzkqpw.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtvofyzrav.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtwtkfepuk.html


<!-- 参考信息 -->