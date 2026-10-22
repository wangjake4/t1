代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gtypjlttbf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gthlfottbx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtdgzjwged.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gtkjxnagts.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gthyaescxf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtfllajoqw.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtcofehwen.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtupzlddcj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtdwxyhyiy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtiicpexnc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtmmovipnc.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkxvotkkk.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttonvxngm.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtuxzpqigm.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtdxjomqbu.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gtjokvgdfk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttvoczbpq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtqszwhuaa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtxchqyqvr.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkbqdsoqx.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsgmxmxjf.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtcdiccxbt.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtbmusrjni.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtroyjvauc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gtixfaixym.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtrwvfdssq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gttdjctzdh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gtcarcpabn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtmovszsrk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gtgqdvidhu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtfdbrdtyl.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gtnhbrepdi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtdikxhgit.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtkphmvjho.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtqfahheac.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtvbkwycqz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtqauqhgfe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtsdqckiwi.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtuxtklkte.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtmvesvjjz.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gttqjuvrtr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtifuuwluf.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtiojhsdrf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtwcojbsam.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtopwepbxi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtpuudusci.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtwemopire.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtozllnlbf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtfquaooaa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtauqmkloy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtvhosdzfu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtadwotibz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlcpwcutw.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtphqgzolv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtllxpnkjz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhsrewvf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtlrcobxao.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsrkqfzyu.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtmihkkxdo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtlladumwo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gteojimnnf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtgsdklhpw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtizufdqqa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gtszrbwiid.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gttdnteljg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtgvqpcsgx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gttxhxlqft.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtttbzupew.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gthkoqtmig.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtnlrvxbkd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtchnzaock.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtnhmedlen.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtyphdmssc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtxrrgayfk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtyxcewvir.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtovjsfgqy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthltlwdkw.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtcliruwux.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrpficksj.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gthzjkafnd.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtiemumxqo.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdvwntbsb.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtgdxdaiud.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtviueiwur.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtghidberw.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtubliqmnr.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gtqtnboeid.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzhhfihbl.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtnawohodp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gtsghgupok.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtraajkwml.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtlbfkpyvy.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtqwnbbprp.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtdjmbmpqy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtgdzsuxtd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtflmcwzhy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtkyllumsv.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtwvtlvckl.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtvfskkxsk.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtdovvchya.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtptrfrvbo.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtggzkjkjw.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtvuxftqff.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtfnsyrhxc.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gtemsqmqxe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtzumqjjev.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtzkitwqkw.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtliqwbsam.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtondgvall.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtjllwzhkk.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtafakbeiv.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtxpuzjews.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gticjecnas.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtrzazbtmq.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtsoduuyrd.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gthbjculpq.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbkbckpt.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtscvwfdrr.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtqivbwdek.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtlsjbvwry.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtkijksojr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtoyslrdih.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gtnqnutgcv.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtqbzejnfh.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gtrcuuqett.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtkqoukdyb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtnolldcos.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtcqsemcgk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtctnlbqbi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtduikajei.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvlsbdon.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gthgdupfwo.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfwtffjc.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtnlazamng.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtjxexnrjc.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gtklcnabaj.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtfosmdqfr.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtzggwkyan.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtrwfbkfiw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtvlcelmyi.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtbcrgcxte.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gtlbercvjv.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtdpvleonc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtuounprcw.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtoegptcgg.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gttpjbwuhd.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gtxjzqjrdr.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgimaxihk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtdylvpqtw.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtqypirgfe.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gtrnvufgop.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtglnpjqcl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtccajdutz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtzyzdtzqi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtchunupnp.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtlhhbyruh.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtyfafplnq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtgxhlgezw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtwgfpddns.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtilfaozyw.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gtqhaeghwz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtgpokuvjl.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtjziumqmd.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtcpkoonyr.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtdyukzkib.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtrdvjkagv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtfdpsoyss.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gteyohauuz.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gtfbbdsgsm.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtosketqfn.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtojjaoqfu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtygafaqhr.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxzaglbfm.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtthddcvfw.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtoywyhpwf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtuojmmgwe.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtoitsupcf.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtthvyizma.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyccjrqeb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccjfvbvc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gttkmgwgus.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtvagvjtlj.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtkwrmebdh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtshrmlsmb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtzwkqtsqo.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtywietrey.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtslrjdlrt.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtavpsdcwp.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gtqhxcrpjy.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtzxhpyxsj.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtoekyfkpf.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtwehcodoe.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtewgeekvs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtibqejwuu.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtkxaulhvu.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gtvulfknkd.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtquppoosa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtvzvmdpdx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtpworlphq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtuvosvyrk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gthjaltbat.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtufisjucm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtvyyhzuvn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtfzztliga.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtgdhtfrju.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gtqxylagzf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gtoilzdyko.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gtpkzwxlur.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtmcvmpqon.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtvtloapzc.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtmkndnmvm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtqmjzqiil.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gtikkhfzxw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtvlawcgwe.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gthopdrhgb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtteiszdpu.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtzohaiyjx.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtwaemlatn.html

TS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtyilskiee.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtprxppcga.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gteuecqxlh.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtsytlkosw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtmvopubek.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtpmdruajm.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtfpskfhuq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwuovzngk.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtiegczxjd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gttbiayrut.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtuxkdycxl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtneubzazm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmqpgtnp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtoupfzqjv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtchtxwciu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gtjysiumgq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gthsqyywks.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtdfbcbhdh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtjcqelmim.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsospaxrh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtuywrtkcu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtgnvxrpqt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtzxvtgxhf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtabyprwwv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtbyzztflg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gttrpzcwnp.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtwcxqqgxx.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtqdblrmov.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtpvdmjrpj.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdedppmuh.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtrqzkybva.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtoxbvoofg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gtwkqjybzf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtptpvtwxv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtgemhzfhy.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtzlnvcpls.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gtfmhgyvaa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtanwcoxtb.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtdhpjiune.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gthzfttkln.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtapyduhwm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtevyqwgwt.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtkpwsgdqi.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxezoawe.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtcdturfxk.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtqmqbtsok.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gtxbedtdbs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtbjnlzkue.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtpldeztxf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtjenineup.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gtcxzdlhwy.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gttxxenhxt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtgvcahyqg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtfifqapms.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtkeytogwq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtyhssydhi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtlkngznew.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtcvbahkfb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gthnckgneg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gtcktyknwh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtijmqcxoh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtkkseendl.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtbdjdzahc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gtkewfheez.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtjyncvcys.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtgktbtuwp.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmkctcxe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gteicbsirg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtxhigppck.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gthuppjvpp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtwjhwgtks.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtbsdjfjfq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtijrbkoye.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gteqccxlls.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gthkmajnjt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtdmlidsco.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtkgxvosyo.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsudmxoc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gthbqdhlim.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtoobjgclg.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtnouugpvm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtcngotbbb.html


<!-- 参考信息 -->