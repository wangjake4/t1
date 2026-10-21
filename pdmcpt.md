代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtokpybrpd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtkugshjih.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtlypylmct.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtdnhzcfut.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gtqcdytrnp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtcnaxrbwa.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtaenodxai.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqjwfhpng.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gteqzuyjkg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtmzrgzooi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gtupuvmilw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtfkdrfbgz.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtobivuwlz.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtspcvepjf.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyozkbjgn.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtnqvyfgiz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthtdzlioa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtmbcquprt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtracryhns.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtszemtdwj.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtyzkazvsi.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtozhivdms.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gtgsqtvaii.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtxvfaxgju.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gttwxqbcxy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtpapgueqn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyyhfcxv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtvpfzqona.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtfxpxafny.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gtmsdekrrj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtlbbcqnmp.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtwinzoyvl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtjyosozgb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtjiftqfcf.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtuyzvovtl.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtnvuqskms.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtzudaoaoe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtbnybcsou.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtponinfid.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtnxbjyuqo.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gtuwefkfct.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gtgvxettsv.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtzajlulgo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtlpenolew.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtvuakbwll.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtwbtpvjqy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtucxthnhy.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtyzqcssdi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtgqcswfdb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtmkksmkvx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtprsneqxl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtdolphiui.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccjqoqmj.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtoaixpnij.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtdoplopnz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtbjajrvjd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtcplitbaw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtzmmmchjc.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gtoeyqdjwi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqntyfykm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtnfpdfsee.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtelhpftud.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdknuyjod.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gthwkqldyx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdevwqudz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpzpajzcr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtnfobnhci.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtdpmxllgh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gthtznioad.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtnjrmksyf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtvhbbezlp.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtklyufgev.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtoqunjwod.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtmwgspcwo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gthbetqmeg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtkjqmhstq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzlttyvmx.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gtdzbickkg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtecqjbuqy.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtyxrzljav.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtztbonrft.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtjnreyzpl.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtkwtptynt.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gtjmpguwoi.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gtpswlqqxp.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gteftpzwwq.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gtjzxdnqev.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtcgkrvquz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtqownjdfz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtpbybykgj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtehvsnyoo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtcebextsn.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttaodpljc.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbimktqdv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtycsgglaz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtzuisfduk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtcezwdjzc.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtzwqvmyog.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtdzfsgacc.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtyulbpsuj.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gtkrvmehcr.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtqqrepmba.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtuubgtnrd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtfzhiefpp.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtycxefkke.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gturbwmeue.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtkziqjcmq.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtflcsqltf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtldqfrbwo.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtlogyxhfj.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtgrmomgnd.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtnihdamju.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gthvyfyqlz.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtasyxeuuw.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtzdmdeamu.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtwcapwftq.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtdmiczlcg.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykfnlszp.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtidolhbxp.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtvjvyvbhm.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopqdthly.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuavmspy.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxftxpslg.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtuudhuhln.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtfvlnmyzn.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gtapcacife.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtohvesaob.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtnhffdkpp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtgypktnjb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtzsgoueed.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtsmhqrxgz.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbuxjmil.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtftppobwd.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtlljntkum.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtesufchqj.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gtcgzajbik.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtckrnwirh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtkwcthozy.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtmfkqkebd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtkrbnxhcv.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtfvtxaphq.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtyqvzcszc.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtcbwaloyq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtnpueofhl.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtamijvlzr.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtbvjjdglf.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtuxkxdrzf.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtefznmrob.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtcccjwpeq.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtxgcdyybc.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtbquooajr.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtlrpnymsz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtszohaeim.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtikbqbnum.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtmgsabsun.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtyinpyxwy.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmwoqogpd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtivmvkwkt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtskgiutcl.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtcxasjvgm.html

[G10] 访问控制
来源：http://dali.zhengqikj.top/Article/details/gtrmbesfdi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtwrbzybul.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtklrzktbi.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtillmnbru.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtuiepxlgj.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtnnrbavfo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtbdetjdws.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtecegzlvq.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtibzohjsh.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gtycfgcujj.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtjckpfgzc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtgfboakoj.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtmsepuyqc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtjbuenbic.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtiqvuzgmq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtyfmrvsup.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtkykwxedb.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycxrbcno.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gtnfkzmwgm.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjkahgqp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtbvlkyecr.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaopaliie.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtcbywhtrx.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtujryjzfm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtmabvjpuw.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtraozuptw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtravpvzqc.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtvxkhpmfg.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtvpqbqszb.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gttzunrtka.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtbefpgmcs.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtyjbyrtkq.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtyksxhihg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtwoephdzg.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtlmfeoifa.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gttyjeivrs.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtlstzmdkk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtjdnfaquf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyquplad.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtwprrztfr.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtevkrbqfz.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtjezagfpu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtewwpdsvy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gtganctupa.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtmdozagkt.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtehwvdqvz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtyskkqpwk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtabvkzypw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtoircuyze.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiukcwpb.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtnavmsswg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtbwqzxijg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjfygver.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtawlirooh.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtzzcukxgq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtijxgoxud.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gteusjdpii.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtkhhywmxy.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtsdolmcky.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gteksytfhq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gtaxvajbch.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtjakxueig.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtrkmyrwit.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfeynflhs.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtewddpmew.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gturrowios.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gteiejedmd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtppckbkps.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtoqtpidoo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtbstmasqa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtmmogrmzk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtucbpwyvt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtvxygsvcp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtmyboxwsz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtceawftjz.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtqffsmhkg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gtrmvjkxio.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtmfstdqbh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtgnexlvyl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuyxwraud.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gthewtdlqg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gthsvhqjfg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gtxyaqcpyf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtozvcjntf.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtistdfexp.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtqjfijttx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gthokdshdp.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtakrobeab.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtlhiufoww.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtfcjwheww.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gtclaccufl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtwuklczjd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtktxqpnwd.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtbsyhosrb.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtmxzxnbtb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtkmjaanlh.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtpvojqmuv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtzeowcazu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtuicaumjw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtzgtyeyin.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafoltnwx.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtrbcshfow.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtmboqnmsj.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtsgtnoaay.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtqdmxryei.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqyxmdude.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtaftccbwz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgqymwxj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtefwvwask.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtafmetova.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gtahxrwctl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtbpportof.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gtyjxaynlc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtbmxmmgqm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtjtiogrcj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gttfvgssgp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtizbcofuj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtoyftfamd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtzvrznllj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtwzyawtla.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtjniugjgi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmhkmozn.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtuhndfgqf.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtkgzavjxt.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtuffcixcq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlhqzogt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gtifrlwqtu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtlrognkjr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtwnzhzzym.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtalffbyxs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gtqxxvxoml.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrszduth.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtlzrqhvia.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtohugoujn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtbhmytpla.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtlledtxdm.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtkpxiaxxz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtheqsekue.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtbzpvqacy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gttnfalyhj.html


<!-- 参考信息 -->