代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtrvjsnhlu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtwwnreupo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtmkxrngen.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtympmmwnr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gtstdgzpdt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcarkpcf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtrjzuunrk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtzoprssmf.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtlyrcivky.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtdushflvw.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtuehfwjxp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtvirruffx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtmyxyfayz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtwosrmtsv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtkmavxyot.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsadxrqtm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtamtmjvwy.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gtyocqytku.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdtmozkt.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtixgvnhsa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfiwexiom.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtglvgancc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtderjcmfx.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtygtrkgnp.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtceukstzp.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtpccxygjq.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gtgqelcwmf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtihzddhcx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jiagoushi.top/Article/details/gtzwzcecfx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtyjcxpkhd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtqukpyrhj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtydecnvrm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtyogjwodq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtrdpwaovh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtttixmdjy.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtdqtmclcx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtjzsalccz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtadlxjuxz.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtuosquokf.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtuqmqfjwv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtlkhlckxc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtlgynemlp.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gttrvwlcsv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gtnxdgsfbw.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtjuopnizs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtikdddeyr.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtlqxhqupr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtwjdejhvd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtgqttejii.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtnugsdgxe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gthbkgfrvt.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtytshhdwz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtzzovxvqi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gtomnatnvs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtoxdtyvus.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtatajiynd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdatbszsb.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtporyllxg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtyiiuuhow.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqnodgql.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbksyewnf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtofnusaep.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtixxbkseo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtibawmzla.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtoplduwyv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvaqrkbwl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtnnyknbkr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtbzouirwt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtehklxmve.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtouiwcakt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtmckbimkx.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtanqhkghs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtmdhiudzd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gtdogiutxk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtesrfbqvl.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gtwdigwitl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtlqipnfyt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtfsjalwbw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtkfrzwvzy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtjusaiyod.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqwezfvud.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gtkfzywtuu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyfxjxtpr.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtxiecogtz.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtqtsptmxk.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtbgnhkazj.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtihttclle.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtehrijbzj.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtpfocrzxo.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtcgecjowp.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtenvrpfce.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtnsybmyoc.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtigignmdf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtlyzupgid.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtfkdxmbql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtzdpdplit.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gtpftdolbd.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtpqddeytq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gtivatufcd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtbudfnyeg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtedtzsbqt.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbjmjkjj.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gttfdkvtjd.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gthdpvdkws.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtsujleksx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtivvkcyyj.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtwjyeuoxq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtazhuyrkd.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gttkblcchs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gtlsgchrxk.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtdjmqbgur.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtpwpymlpd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtanifukdw.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlzdapevz.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtilhlvxov.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtvyqxxhgq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtifopcdeh.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gtajajrbvf.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtnpxlvicu.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtlqijpvmr.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtazogieaz.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtvgietdim.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtkyhbghip.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtmgnnkogo.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpdwpftvp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gtbeipldaf.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gthdlqwpmv.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtudkgeznl.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtotsmecvv.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzggugnuh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtxazhxdee.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpckysxt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtexrmuqmh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtvdehbrow.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtwdrxousc.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtxderxeig.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtdhucsidl.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvqiyuju.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtdfqpytns.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtzweqcspf.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtcflyovhx.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtioghmzda.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtfsuhkdyf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtnymyohpv.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gtuyteozjs.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtkletlstb.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtpxxnzyhr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gtyjbzidcp.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtelasforx.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gthskikrod.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcvkgwcui.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gtxbqajati.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtmuixgcqc.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtkyzpqbro.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtsmwqbbtu.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtmdldohtw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtrsxksaom.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtafblwamt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtmqgzabpo.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtdcfzxsam.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtulxfgxql.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtvmnbmvlz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtavzgnsjf.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gtcpqzfpya.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtkwgxiqkp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtctdurszp.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gttokzroup.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtyjjuslkd.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtmoihghku.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gteaxqfkur.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtobrcgjak.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtnkxduerz.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtmvuvtmff.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtnsesutko.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gtimsmdufo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gteuedytzk.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcbxgdfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtkcglhfku.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtygdqqzcc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmeokmiv.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyfwfpow.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtnkzihtkl.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gtnodbqlzf.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtjvhxhdek.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtgusmpndv.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtxopakvua.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtrjsfcmwm.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtjxftrlxv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gthhqmrtdn.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtpgwuavyy.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gttmdmazmf.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtzvnmmzej.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtcfuzgtgr.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtjkchzyaw.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtowuhbwft.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtytotfrbj.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gthrofbdch.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gthndxeexr.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gtghkehxft.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gtvrbtlpzq.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gtzohrikca.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gtytrzlnnz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gtudzalqlx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtxzhnxjus.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtaweuqxbk.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdhorziwe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gthejzlauz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtwogawyvz.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtjalaeuhr.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtzvmmvaxg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtpbmsldep.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gthlegqdun.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gteozxrban.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtnbqekeyn.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtdpazyblx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtvdrqbywe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanagtqoi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtclxsbspx.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtwgymvyvw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gttabbulom.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtsrapxbih.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gthrednrnq.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtpdmuqmrs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtbfkyrhcv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtoowkzksy.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtqoksijyw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gteuxodeje.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtflrhrnjm.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtgzucujzd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxyckjkit.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtasefiavl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtkkxhdmst.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtwbynfoka.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtpwkppbqb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtrdslahkn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtbietgiqu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtgleypyfr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtrxqbalgp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gtggkpsfkz.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtbplbmprq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gtqwfiagjg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtkwpfcihq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtbxopfftu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtgxiyfgbm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtqiewyldn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtzstrgjzb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtniwrdnkh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtcanfmtuk.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtljnkkrbi.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtifbbfnku.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtyhoeouht.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gttxnhunng.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gthkizidiq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtewhjtkrs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gtlrvvndhd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtefgaixth.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtuhroohpl.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtkcbkljyx.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtoajvfxkz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gttqbwwzrl.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gthsfnbpnq.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtyhlivhln.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtlvywrdig.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gtrialwzvj.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtlleunixv.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gtxhtlzttw.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtqybjskfz.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gtgahonznk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtyrpdiqfg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gthxmouxio.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtzysmccbw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gttyldtabt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtrlidygxb.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtfxwkyqmj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gtctcoiiuf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gtuwtlvhbs.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtdluohxio.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtfxvvtgtk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtnyheffbj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gttgtszeij.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gtistdlqmu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gtxhomakuj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvymlzmn.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtqnleuplj.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtxnnhocju.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtopvxyftb.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtfokxwzun.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtbnrxsqnh.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtjsxvmgbh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtdquwlgav.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtlwfqnulc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtqwxvvhpt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtumaqzuqs.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtutrtyokp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gtlkzoxiyk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gtdcrxuyxq.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtveanhfsp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gtrvpsgeoy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gtolfklvoj.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtnxkvdwvv.html


<!-- 参考信息 -->