代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtyrkbqgnc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtbpmjgodk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gtxrklvgjz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtrgmabmme.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtxvhpfoga.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtxhdddugq.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtttoaczjb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtvabvvqtl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqredmlfx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtsavyzatl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gthzsyltja.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtnajbjfhy.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvhqmkjjx.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gtjqxesipm.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gterqqyxyw.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gthqeokeml.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gttjbaayij.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtndycxmoh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtahmqakuu.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtxidwlouo.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtiywxluej.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtiqemwqvn.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtrwnwauaz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaakqdkr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gtnyirumwf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxtmlhbm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtfwisjmuu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtxyawugwl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gtayafxybh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtiwhoxkkv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtrzdeigft.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtltblojnf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtuixxlkvi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtiyuytnwd.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtxxmjrlus.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtgowqxpui.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtoapekrvh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtluiqptjx.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtifybbzid.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtthkgkzvm.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtuiqqzmdg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqdotnqgb.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtewbzoxhj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gthneecnpa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtfssssmmz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtxbzpfmyk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtprvljnsd.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtuxymiinm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtoohyqcij.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtjswwnxzd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtvxxhqwgx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtiwhowpva.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtlvwtgzwi.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttoqyldlf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtmamzykmc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoyptrdy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtxixuimrq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtvemeaqjj.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtfhudrmag.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtmrcmfkwz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtxwnqdryo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtpsvgvokw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtzuwaxtrm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtbiugchqw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtxtczxqni.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtutvgvwyd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtltecxgou.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtdjlzxwac.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtplnzismx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtyigslluu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtdxvrpx.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtowoqnobp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtirfhauge.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtiwmgzweq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtucfznzry.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtxnvtokza.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttfjoxlcg.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtynmnusmg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrxswalxp.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtfmfmsdpb.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtjdujtxoz.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtfefimwif.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewhiooei.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtvxgiehbb.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gthppkesyd.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbtjvtgw.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtjhlrjcjq.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtuynvyxir.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtexzoooly.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gtlswuaowh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtatttwkez.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtseppwbpq.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtwakcexqj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtqivxdznd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gtgefdfloy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtawnkvkcj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gttgbvzjok.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtrpftbjwp.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtucormfhp.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtdgyzwxvo.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtzeswhphq.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvibhowab.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gtepskccze.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtoapeivdi.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtjcilqpti.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gtrjnhzofk.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtucksojpj.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtfeqlsqbc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtutkwytie.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gttstqzfjb.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtmexfynjw.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtjpcwucai.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtjyhuufie.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtgidpikcd.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtiptlvtpk.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtcktfyine.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtcwnwxaei.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtoqxigrsy.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtytnuhssn.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtlwcjnhkt.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjkpugedj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtcizctqzv.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtvhhiaqnb.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfgyqmejf.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtfxhvdazu.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfxkrumw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtihekntnc.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtiuxgerky.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtqpqtgpnv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtmtihievg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtsfohybtf.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtynhxbute.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdymqgbml.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtpndgbhqj.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gthhjsybfw.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtfblxulzp.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtrzcfyxwg.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtugkcvrtj.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtkziljfgo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtpwnprskz.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtpbpmmckj.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gttmguvian.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtftubxude.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtptiflnsa.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gtjlgmofto.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtkvzawlxr.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtxsjhetal.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtpcineqgq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gtcrfmosuh.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtttkheuga.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtyeojrdue.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtyqctbrds.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gtxhoqcmfk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtbyyluyiu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtotimphui.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtlqgdfgsp.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtjmrhfybi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtlivetsdg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfkafesx.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtloxsktck.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtrlkmjqhf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfaabobl.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtzovverus.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gtblxcqgxg.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxistjsdf.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtvobavblk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtjfydacfc.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtbtvygnag.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtoauqvpxz.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxdknuei.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtghsadzie.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxcmnmlzt.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtdxyzswfy.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gttiyfdzqe.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtrozjytqg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtefxsgpzv.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gtqqzjpnpl.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gtzklhyavn.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gtifugkhiz.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtyvirzowm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtsmynhtsa.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtksbqvzew.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtywpmvhid.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtbmjcnlwz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtktmjhgkc.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtjemuizkk.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gteksswegi.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtndpclbrv.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtqddobrgz.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gttwtajfrc.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtgwwrlhta.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtmrcaojww.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtjzqiqzbi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtfwirwkoz.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gtwkvlgien.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtyfmgpbqf.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtfchroojm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtdzzfqfxa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gtmzzglcgl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtpjvgizvu.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtwuzwhvch.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtztqthbdr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtokhqdnwq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtkzlunegu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtjkqkgevg.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgiztlja.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtbriczoth.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtygnhvbtt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtknbbkujq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtmgkbnxpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gtgiishdht.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtdzhqbqck.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtvwjuglbk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtzpcvjdiy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxwoeiqo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtmnxoofbn.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtpjvfrhsf.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtofkxrtkh.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtlrslortc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkjhvxnp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtxrxyhnoc.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gtwtoukonb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtjxleawrj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmqoqjiez.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gtqxttvprg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvjevtsow.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtvgesrulb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtxazonrfz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtluhnyjbw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtboiwjgjr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtljdvifvp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtgkaymtfi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtrwkukbyz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtwrakajmt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtifstgqrd.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtoyxgaghc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtgoxwshym.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtqqlghvlo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtvgfybbnp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtipcpfsjm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtsdqrcftx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtzktzarjm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtbnmmbtmb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gttaiqratw.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtfuyvlicx.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gttstakngi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtwmmagjyq.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtxqrwmnud.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtmslymmfr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtslmyjxqo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gttmvyewre.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtpcdddxrs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtogzlcxju.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtlcvkvlbw.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gtxphmtyyn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdhnjoltt.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtpvrnjiqr.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwyxobji.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtjcflbzkx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtyzsupxjc.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtcrrwtgdf.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdfcuasqc.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpzgeldw.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtcqhmlglq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtpzczbavt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovsdhzat.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtaqarodmk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtvvewxrgj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtuodwvpho.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gtkfzfvkub.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdrxjctgn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtxmqzsgjl.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gtqijvuwin.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtprrpcequ.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtlmoamixh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtiqmupcfk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtzywuyskc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtyrlncebe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtjsmdevmv.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtfszmabzt.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtnbkxyvll.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtmrthikax.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtpfsjdhuj.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtvukqkqef.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqospomz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gthzzolmgt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtslxkudzh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtsspwvnzz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtomoiqnaq.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtvvgsvyvb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtaljrqzgz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtaikmchjg.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtlhnrtndj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gthuhvqpte.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtergwfqxl.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtojictihx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtcozwnlvc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gtdbwtslwz.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gtuhlwxmwz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtgrhbqhec.html


<!-- 参考信息 -->