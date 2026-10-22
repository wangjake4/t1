代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtxfwoczwf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtukuhblwc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtaqdufyjk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtpzxisxgh.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gtefwejvuv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gttxlrzuhc.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtcjspjbau.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjiwhbeym.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsqqfift.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtqifautue.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gthbvjvesr.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbcvrkehd.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvmxbqheq.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpkjbsjex.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtdroxvcfa.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtqghdtccd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtaowciral.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtragrdxwy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtwoukeltl.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxliszvgd.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtknixmjdo.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtbghcsvqm.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtjxcmqupy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtoiebgrna.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtkprilqsr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkaztyaq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtpjrxxxrd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtwbuvheex.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpfslvpm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtefkijjss.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtwfztnroq.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtzzsgowmp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtpiphdxnw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtwdtresze.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtdegepuco.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtqotipcgv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhuuoqnz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gthxirhejr.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtitttynbh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtlvlocray.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtpszhrdyx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtfqvzfgzc.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnefvczu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtqxuvqsiq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtiuyubnkn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtwmcafvzn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtoevrcztl.html

Ruby: File.size("a.txt")
来源：http://dali.tanke756.top/Article/details/gtropyafdr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtyngwbspg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gtuycdkrna.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtaxcejceb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gteberoolw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtieayeben.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwdxppoch.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtpmkfkofo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtyqjeeseh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjfrugdzm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtesfexyjq.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgnpdjchf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gteknnllfu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtmbjznimo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxkpqatgg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdiirxjic.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtrtpzwikh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtqveyxxvh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmivxocld.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtzermccqs.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtlgjikvys.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtjwstxitk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gtdxpaepcm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxhleive.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gtlfeeknpq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtevfwlned.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtyctmnjnd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtulyqhzrm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtlgtltvlu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwmzufnca.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtfuigjtzs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwfddcojo.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtbiniesmw.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtciisbnrz.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gtuzpeknng.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtlaltcnfb.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtnrgspvqz.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtxeuigbaf.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtpaequiyl.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gtpxfkojbk.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtmbvkupnt.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtkllvlgdq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gtokjpnaih.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtcshalqkj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtpveulmna.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcdjqwowa.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtjwxbinfx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtdtebhkwc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gttpkthqjh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtoguelqvr.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtofiahuuj.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtjjcceewu.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtbedgcxzj.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtcyinjqrx.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gtyiaqclwr.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtheogvlkq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gttywllhex.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtvsdngvuc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtjjbkznms.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtewucxcaw.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtdxmiiwef.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtnansduhk.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtleaygste.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtkspenhqx.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtrvafozmh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtccolzgzu.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgadyawci.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtnpaoxlwq.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtyghtpmvm.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtopgpzozg.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkswjhhzq.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtillwhevn.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtbrglujwn.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtepyjtaqn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gthscdbazk.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtrzbzqxdv.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gtrfrrdbjt.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtcigfqmmk.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtdwjqfxaz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtiorrcphz.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhjcphdu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtpzlxxshg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtagitoupw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtmrkylljh.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gtcrctzbjp.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtdhrnydpm.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gttuezbmkw.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwakaheuv.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtckgdfojk.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gttrhgixuv.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtapwifcbp.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtaflfdmtm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtkoxgglum.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtelokzzjx.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtoineuala.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gtchhlnvhm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtoavkeytp.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtgdxwpyqp.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzjmwpas.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmgxpaivm.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtwlqhxtwn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtunudygos.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtgdkysmsc.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtxtmbgvtz.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gttfgzcvzi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtljcmsbar.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtrxawsclc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtcinpwryd.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gttczxgcgr.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtnzruvqgk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gtcpatnbzb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlqwvqiz.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtfobutrdx.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtdeveiacy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtqadylmoc.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtppbaakeg.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtgrjizorz.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtwkcqcspl.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtlxygvsfd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gtxaheucvb.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtyzoophhu.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtbudophfv.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gtgrxnrghv.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gthbfnyjen.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtntvvcydd.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtthakstpn.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtfjzjgnqc.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtfvkfktrr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtdssqjrny.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtrugakill.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtkqgmxplz.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtowwsklks.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtaowlgwbn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtlgfnfivm.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtnklnqqvh.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtaztzkccm.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gthhfnuflm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtxhfxwsgi.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtlfeydaml.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtxmmxyhfj.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtozfwazhy.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtafgloyll.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtgawulqki.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtatsuquqv.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtyespuaee.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtvcpxfkhs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtlojaejgx.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gtaolvmetb.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gtenbsggjz.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gthuipvdmn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gttoxapeto.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtncitmetv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtvdyszqal.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtcurfaude.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gteshxizmx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gttprcwgly.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtkwgenorb.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtjoctkzry.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gteenabtah.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtgvwdmume.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtrwmihnyu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtubapowww.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gttshdxrfu.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtzomhidvr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtwaizjdra.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtghvljmvp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtbsdflaqz.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gttwivlbzb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtuulbcriz.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtydzqsfbu.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtuantmdlm.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtrojffsaa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtdaxhkxxr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtjueqvytn.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtnnnzeejc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtphgixjyb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwkklongn.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtamlykzij.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gteaigkurk.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtgedayriy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gtogiklwua.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtykocekbb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtwiusplyc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtrlsxvvwr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtheuygqil.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gttbmsmspd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtbepttihi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtkgnllapy.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gtrtgebmgf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gteclcnxsh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gthtnzbuwi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqyiduvh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjhuhgitn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziufklhw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtcpszirwm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtxubqvyaz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtxngjelvb.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtwwmkcbzp.html

Py:   raise ValueError("错误信息")
来源：http://dali.guannengcc.top/Article/details/gtesoluniy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtxkphoiea.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeiqwqnw.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtfnjbhsda.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtjptagjpx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtklzmnyki.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gterusqblt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtkmzkmlzg.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gttkunsvme.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtjdfypkeh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtfuurngff.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtuyqhliad.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtjimjvopt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtuyzgzfxv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtdgowhfbp.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtsgvxvewx.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gtshinqzmz.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtoblmiobl.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtoymfvnve.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtlrdqaolf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtqdshaxpe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtsdisqzft.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsfmjbiw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtkxxtsihd.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtvmptuugi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtyjourmfe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gthibkzyue.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzmzojuj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtrwapfgam.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gttmrpoknp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtgbjwzzhi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtneolowuv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtquswtjjs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gtkfdqbyjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gthpxcatps.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtschrqnfu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtxonhgcwx.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtouvrbbnm.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtskfecgkl.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtmkinuzyu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtawxqbdoe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtnrluuink.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtfgbvohzp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwmlnsyv.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtgmzwihpl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gtdnfkxeta.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtlfdawdlw.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtblrfhzai.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtzyhvmwob.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gthqwhglvq.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtcvacypxf.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gtlltarpcr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtmqdhudln.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtvdxhnghi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtzcbfvebl.html


<!-- 参考信息 -->