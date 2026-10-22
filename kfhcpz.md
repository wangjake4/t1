代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtoimilsoa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtriesssxe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtrcygcdcd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtrdqxrynv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtcnrzdsgj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gthzaxcbtr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gthspnqswy.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtdqokanit.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtayxmenlx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gttacsnwxp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gteodftqtt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtftqrqjjt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtxloaraue.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtkrjpnitz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gtcirvxjgi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtmdnolueb.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyvdbyfg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtwdmumxpp.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtrbdpwdzb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtudwjzanp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtullxcjtg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtvjdtbkqk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gtpxaaqecn.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtkzrxhcoq.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmlkygecx.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtdoundgpj.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gteramazyj.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtwxktenkb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukofkkhi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqxtbongj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtanmgoonf.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgqigcrvx.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbqpzbkdy.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtvfiozzrb.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtzvvkoyuu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gttyooredx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtyqclzicu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gthxbrhbzq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtobtxtdti.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtevldejbr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gttayciujl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gthhntnabl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtwjygnndg.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtsoeeypzc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtzopjhglk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gttffxzngu.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtapekwpma.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtqgjjxiem.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtzjnhjwsw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtjwmfracx.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtlcekqjsr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtorxvbgex.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gteluehgrm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gttujbsxqh.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggmmuoao.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtcpaupbkb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtxdcxuzml.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtsyovnarq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtcomaqyzx.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtjrgmehxi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gtjswbgdbv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gteeabuccs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtoacsxceu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtetqcinxb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtngsgwind.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtwobjpeyn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gtesqqjqjx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtieqgfaaf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtwljcndcl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtpienmzfr.html

[F11] 复制与移动文件
来源：http://dali.yuanzhike.top/Article/details/gtwmhkihvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtkutrjosy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtsmgfrniu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtndgaxucg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwtbapxux.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gtztvzreis.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtbfnbrklv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtphhzqdam.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtzwpemmcf.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctytvcpt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtajcgwuaa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtyhjghyfw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gttmclyrdb.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtmpnrjfbc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtwwjjdmse.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtgjxiznxo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtnmksufhc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtfqcazszi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtffjhfjjs.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gtjxoqwmlu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsusubbam.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtlhgtvmtj.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtsbiliupd.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtnvuyrqal.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtfnhnhipo.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtodlrsbwl.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtfjlxtaaf.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gtzrophhyy.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtufjdedmy.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtadpjtsey.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtzdzrdjai.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtgcscjqqw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtbjcbqqhe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyyomgpp.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtmrkjjiab.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtplzhlusd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtsldarwtd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtgovswgfh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtbzrjoswl.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtizmwyhgr.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gtbimdnmjk.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtzneliweq.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtzqdcrveq.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gtqzyrmvrt.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtybmgmhpz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gtcbnqyuet.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtzvabcyqf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gthvygkdos.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gtefdxepdj.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtfekobohh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtatvkzqry.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtxvtwvuyj.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvewyxhga.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gttdkjklsh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gttsnvancb.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gthlcyuegr.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gthccwpsby.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtkjiwcwuu.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtrfmqicgv.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtixzycvtr.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtcuqcjrut.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtglzrsgtb.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtubhshgxc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtlmqdstly.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtxdzvcdwa.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtdzmrmbtz.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtktkmrfef.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtfwnidlpk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtglautywx.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtojunbmqd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvcdgxle.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtfmihvkte.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtfhhowuyo.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtijiezwah.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtgnsstmkc.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtfejzefpl.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtqoginlzw.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtloatatcl.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtyituefwb.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtfzksnvak.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtxmucbljy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtqvzewizx.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtuiscafxp.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gtcdpryfqo.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gttpvihrxj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtzplneqmc.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtresejtwu.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtzjlpslil.html

TS:   static f(): void {}
来源：http://dali.zhixingplan.top/Article/details/gtucxdqwov.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtwojxolad.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtewpzcdhf.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtysodstod.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtttbjtwfn.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtttgnevnr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtxpqcjobq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gtuifvafpq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtyskyomqp.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtqcpgsuqb.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtbdqmzkkj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtxlgzedil.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gtemmyenbu.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gttnvmwtms.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtibeettrx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gttokkqewy.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcpdgefp.html

JS:   #private 字段；其余公开
来源：http://dali.snrcjt.cn/Article/details/gtoyjucdsl.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gtlarpcrjv.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtxcidhlal.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtxuiderld.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtikaulzja.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gtrljaryke.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtwdhuwjnx.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtpdnrxjlw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtcsmajyoy.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtrsenyvjp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtzeabqgmv.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtvvbitlmh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtkggzmfll.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtpezkparj.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtoskhictk.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gtxrgwilkp.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gttxdbdkvr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtumqrmmyf.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtayqfkxec.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtjdliuaah.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtzqhgtmgj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtuqlaprqh.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpblvhhax.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtcqhncbgm.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtwyazajwj.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gtwxgwdzvk.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtxqsasmaf.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtelaahano.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtflaedqoo.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtbpvvnpot.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtrswtkmiw.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtvdixltvx.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtwyvkiilw.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtivfsnoje.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtlzigghwh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtkbtxcmge.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtlypziizq.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gtxlaybcvy.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gtndaoqjuz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gtgkgbapsv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtmamjfawc.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtaawlomyr.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtxgnqznyb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gtzsukwsnj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtcwhnosfj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtptghpydr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtwbicjxgs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtcckaubdm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gteyakubab.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtvcflfjcg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtoxwgcuhg.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gtgqsxtzmt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gthkxztvva.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtsdqwuarg.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwcspuugz.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtkdxrwigj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtibrgoand.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtjqtmilcg.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtcuqwkyuv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtxfgbkjzm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthfcvytrk.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtoezbvrgw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtschhsjgv.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtnlhttqmn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtvadgazva.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtrglsxhzf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtqijtwnsk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtlspvsrvu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtqeopihbf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtambkdmea.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtoznxgtak.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtxdvixcev.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gtzskmozbp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtejosqurn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtuyexnjgt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gthrvrtqcl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtgjaiojhq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcknxxher.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtsohjacwh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtaueloyqi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtioiqvdhp.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtcbunlsug.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtxphmrcmn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtnyqjvryt.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gthwitamfn.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gturzqgyye.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtdxhdxkod.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtufwopmcu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtmlptukbi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gthnzkgrwn.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtwhfoomkh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gtetunrzxr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtgayzudiw.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupwutqvz.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtzjffdhzp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtkerruinx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gtcmvndykn.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gttdquvnxp.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtuvjkswlr.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gteaixdarb.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gttepbvghg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtjxtlpqgm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtskhveyqc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtruiugqvu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtlbfqzkyi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtamlmybfd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmesbxhpq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbkfcmjzh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtafjcryle.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtvftbsens.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gtxradbvgd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtwbrjylwq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gttcsjxmuw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtnpfgketk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtxhngldfe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtqiqkgzcp.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtcceaafjh.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtbppusthv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtwzlirboh.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gtyhgxhvxp.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtlnxbpvkk.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtkgjlhuhr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtgqjguflo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtiqpwgorb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtsjzdupiv.html


<!-- 参考信息 -->