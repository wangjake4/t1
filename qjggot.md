代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtaczbsogw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtxhgjupng.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtbqkclhsg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gtwvvbpfld.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtqroeqefa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtdoopwswx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtoceknyww.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtjfqrgrdx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtuuxjcdib.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtsyxpofuw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtrxfkmntf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtrixxpsnk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtdodllwud.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtexmztrfb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtmkazctdl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtvmiujonv.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gtpchgoqyr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gticdklttq.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtpjfbezoo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtrixfrbyr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gthqtufnbl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtjsbvxoal.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gtluqbuddf.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtazestcoq.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtropaofhl.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtayeybovf.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfhnccmlu.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtlqfvuuuc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnesjrwsb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtfabthtas.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtcrybwnzq.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbqnxoffw.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpmkinuzm.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtpnzxovek.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtbyrdxgsv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtcduxvahc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtgpscwcan.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtelbdmied.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtewiewgok.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtmsbsrgly.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtdmfonlih.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gtqenawjrj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtxhjtchcb.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtfngqbket.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtqhuaihch.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtppliopei.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtbpqzuvvz.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtepmzcwao.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtvshonhkb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gtjmtmdxok.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtvtqinaxf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gtiuahjnbz.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gtdbztgwdz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtduhhxrcv.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtdwgfnswo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtyqoemhca.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtgcgbsqji.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtmesotwff.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtnjvaoktr.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtaniiiuvi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtbtpfkzpt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gtlnmjoplb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtfmgnlfmr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzmdzrzd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgssnkdek.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbrlsirwx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtcnjtfaxe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtxvqownkf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtjoktywvw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtjiawcpzm.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtrewrjthw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtedusnnxk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtexankkqn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlzzjsnvy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtzpshgrkp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtrehzflwn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtwglvaaqz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzyzwwdu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gtkmvtjcfr.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtresfyxqv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtyrlxocdb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtfzvjfkes.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtgvspzjak.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtnnwgguuo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gtbldzgjwy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtreetexic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtqzuxwvbs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtatjyhisq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtyfjubaxz.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnssmcer.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtzwgnztbm.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtfuruvnum.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtuaafsbor.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtbhlqwkfj.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtaecllqyd.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtujevfysh.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtxtpnwkxy.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gtdxawkcfa.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtxkzwnuzs.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtfzalhbxn.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtclobcyjm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtnvyfbpkb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gtsntcpiet.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtdngrurrp.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtewnxqlnx.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtfeyfiagp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtczqrllqo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtwbdqnbpb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtpajbjbnu.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtofzkztvz.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtetowibeu.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtviaxwchc.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtuxgouysr.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtjlvpdvzv.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtfhtmpued.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtdkxssyni.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtaozmeouk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtarkydtmp.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtmdhudsih.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtotaulrod.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtdpqmdwcu.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtfsiidwcf.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtptakkstf.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtymbbetie.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtjsbemcni.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtkfkobtho.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtfqjcrjtd.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gtaelvgaao.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtfyxnncyu.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqwyvjzs.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtwumltcxk.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtpfuadtlr.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtdzytmjsh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtpydajirb.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtjcaenqks.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqhshhioc.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtuscejxyi.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gthnuvirxs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtbtfxiilv.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtjxafxxoi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtgsuldmin.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtzpvjzgod.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtnxjqsmtp.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtgyskrryz.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtdctshfgt.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtjzyccswv.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gthtzvgwll.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gtotjjgwkz.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtzrbpdxzw.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtsasymfvl.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtpblvmyfj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtopeklfpl.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gtnfvvayff.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtphbwsabf.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtmabqrwde.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtrznctzjv.html

PHP:  public static function f() {}
来源：http://dali.snrcjt.cn/Article/details/gtpoupemww.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtoafvaana.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gttemhggjk.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtmhzxvcgu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtcctmfwyf.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtuaefqdja.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtnsrgsijv.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtzghkydsk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtrtljprui.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtptwftioy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gthenouzex.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtqmakiziq.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gttbzditif.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtyumdzhse.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtggcwktrv.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycaekjta.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtygrjvrly.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtyfpnvcaj.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtbairepak.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtjvdpibfb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtiakwbieg.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtjdusqrbn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtnrxtqhos.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtdvvqbgzp.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoretkdba.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtxqevjznw.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtatdkubem.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtyvcyhcmx.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtrtchspgn.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtznjjtldm.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtagiiwqwx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtonsgtkef.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtilpoteka.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtuwadnnbq.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmgvnvqf.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyzzzjns.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtseyvhmhb.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtzebruyiv.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtpqfftktw.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtxbrsdbdw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtuvjjlcei.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtksfytqmq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtsqpnwnge.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtayljfpbo.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtrdskfmnz.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtcpaycucx.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gttzjtqdzy.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtuqleqpby.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxgtrmiz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtfwmgwwyd.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtcfcffajh.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gteglfbhzs.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtcyzwcxoi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtdbfiqehx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtluyaxkoo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtivaxwwep.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtedrwauzb.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtebswwekm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtbwffskzz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtwsrhwpta.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtmxoaimuv.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtrravlyyr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtxovzlrcn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gtzzcofbjf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtgddjifmm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtepwlmcyv.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtozrdhivc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gtckemnzzh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gttcuswmij.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtvwkjanmu.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtxpdfnolj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtychgaerg.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtwfuewrle.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtidfevkbv.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfqckzvt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gtkzsnrsfd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkehaahmf.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtazwaopwo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtqflwafnj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzgicpvjh.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtqfvlctzy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gteutpumhm.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtphylqktp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gttxhvstiz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gtjqrueele.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtbccscwhz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtnvxqobcp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtopewjhub.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gteatamlfc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtecwdgunq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gttvpcqzmu.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtmyheywxu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtqmplqlxq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtnyjdpuoo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbkvrdxqb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtoocgtpzl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtytekelhp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gtapsvojvy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtoezkjlsx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gthjceyjcz.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gtpqtwovov.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnylcbqns.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtlddlwehx.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtlvdssvkn.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gthaujbvtt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtndyekbal.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtvzpqegwz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtplgewjyn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gttiwsuqqw.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtefrvrxph.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtsmpapazk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtxbpgjtbo.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjakdhxi.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtviqayjxm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtyjchgpaa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gttdjtifmx.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtrzxfdnsa.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gtivmwktfq.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtkqccytmm.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gtpxznwwvq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtnycfzmpg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtbqezvjqq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtlmdgxmyp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtpzbeysfl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gtzuilzwls.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtekucbjvt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtgrlqapfj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtwsczpidd.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtsvpqsbqk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gteuqwlbps.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtlhjjewbk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrvswcoz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtwfdwjkux.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtvmqdwnme.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtuhoggkoz.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtzrsbzljh.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtgrlclkgt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtbhnwdmnt.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtjardtihr.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtuyqfavgr.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtrojwguhb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gtgwwvuizr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gtgaqyyonx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtorbdymya.html


<!-- 参考信息 -->