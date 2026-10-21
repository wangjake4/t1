代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gthnjacdyv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtrhitemus.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtkecqmdyx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtesgultqx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvchuznfb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gttpyubgsj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtqrupmial.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtczsqycfk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtssvkgrpg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtbxkrikew.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtfhdzxene.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthmukbqz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtsnoiwsqk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtzkgkqmfh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkpxcuos.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtintwrtao.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtrlnizhuy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtschtncmn.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtmkqrescs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtryenqwfj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtyetjwyyo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtfrgttegp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtlbufoasi.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtywljmlvh.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtxtduupnr.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gtkbmujxfj.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlmuwurkv.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtcbkkzhbs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtlhxvufmv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtupshbjto.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtdcsileax.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkfttqdxo.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gtrvlnpbfv.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtwruwrgxr.html

[F07] 创建目录（含多级）
来源：http://dali.yj202588.top/Article/details/gtmbhrtrgm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtrajpuvzc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtnkpsqqkm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtlxoyqltj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtcakehawk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtdfvdoqmg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gttukuscna.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtkbdhxair.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtysoycqdm.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtcyodvjnv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtjefwnqvb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtimyvbklc.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtnvwelwpw.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtjedmmovk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtloxyfovd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtrgbenwvf.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtwsprxryr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gthamdlicj.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtccdsboac.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtooxfkbcv.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtzjjcjoah.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtlpmhshav.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtsuewkzmj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtphiujoei.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtdmrpgggi.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtebnkjfka.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtpybdwavp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbyhlozb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtolwwwsgp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtirzpeity.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtsochiutz.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtolztlyxy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtbobutdvb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtncyzyswj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtepucuzwm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gthvjesfvo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtilletmyw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtfuelaxvq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtyjtxskfv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gthxepybyi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtwxygtxsw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtnvlcdtpm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gtpgcxculp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjxxcrqug.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtoxxzovho.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gttrijwcfp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gtxawxdfpo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gthavdcyma.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtcdqdnvxw.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtbvzwbnax.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtqjhpawed.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtqblquetf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtwcizktub.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtbwvtwulu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsltahvnw.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtuvgnrgef.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtofexolnf.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtydrsnhxj.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtxmgesxag.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtaohgismv.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtbqjzmyar.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtohqckdye.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtjpcfsxaa.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtnjdyszwu.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtukuevkza.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtjtwanuvp.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtmnlrgwff.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtvamuaowz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtcvbgoayb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gturtpbmei.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtevgwpxrq.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtlaytbbbl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gtyiffbhyb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtgzmskwkh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtnmbhhkph.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gtrschwhow.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gthsaekwqs.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gttglcdlcy.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtlircoiih.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtzbouhdcy.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtcqbuktcc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtbzxbgikf.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrslwkoqq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gtvrsrwefv.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtufqmllbg.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtirhdtjmi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtokltpfar.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtahdgahhf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gteyrzncix.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtgvphzrqg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtsvqmhzef.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gtfrknigfy.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtrjvmxioe.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtkgfhzvin.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtokndfohk.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnfqiimz.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtacisnbiq.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtrqgkbosd.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtckpzxlav.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gtsbzcxnte.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gtkvgochtq.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtccoehfnj.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtpmxaqcal.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtepnfhnei.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtfqpcrqde.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkvjrgsep.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtmraxydsz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtgnaapyrg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtpqrliwzc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslsxrpcf.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtdtmyjybh.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtitrirzqm.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtlehqwsfc.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtqegjctuk.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtbbnuqrkt.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtnnjwrbip.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtrmxxttzv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtuwgryhsj.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlhqbsqf.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtxaynucks.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtdxoloefb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtdwzbozdd.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtxjalqngp.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtcqxbxlfs.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtiyikecxn.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtwnwjczve.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtexcxkiik.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtgnzdynfs.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtjzmyudsq.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtuuluchar.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtgtormckx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtdnzfbdaq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtvugnoocn.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtivgxdcer.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtcjvkascn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtgwoupsbf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtehzudspj.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtlcudjqgj.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gthgomllpa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtmsyzndim.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtxnmclolb.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtjhczjnwc.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtyvjipjxu.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gthetwojvs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtxzruywnx.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtoqwhpepf.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtxixfnwyu.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtkkmzjknv.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtznqcvikr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtbizuoxid.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgxyyjmi.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gttiovbutv.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtwmuldeyn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtawewheuh.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtltqvlcgs.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtyedflxrp.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtlhfpqgpa.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtdqgwfjqb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtctpcceqk.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gthyybfzyp.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtmuxfbqxu.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtgooibgll.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtsxucfmit.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gteyuxvysz.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtkrptwumz.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtxpaxszuz.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gthqejvtbf.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gteiavheni.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtaufucxak.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gthmmwrlop.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gttysynwgu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtwejclres.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gtmgceromw.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtzbtdgrjt.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtunaxkygn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtstvcqqhu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gttcrjdpfa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtzzrjcdky.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtetpesdbp.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtghoouvwp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtwxqbzktw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtlpvsaqut.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtppygjaih.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmilfgdiq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtprgdxtek.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtbkuybfsd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtamyizgfv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtnizwwteu.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtktxrhmpv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gtlnwxxrid.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gthlwrwnrp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtuckdhcar.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gttbshxteg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtxgzjgdqn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouvmwvlm.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtdfslsjfz.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtvihqxwmd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtxwzneuts.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtatzgcwrk.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtopwpkwtb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtrmjkoxrq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtohbxmcmf.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gtyviuwcja.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdyrhbcnq.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtryxebdjx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtxynpbamb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gthuewifsl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtvwmofsww.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkooclpid.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtaslpsmpz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gttwfsojxf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtfwpvcvnq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtmyomjhuq.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtgcdtajak.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtepzgergj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtdgkdquqk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtealdunoi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtfpdzrtwp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtmjytxuht.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlatbkmxa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtaialacmf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtzzqszngt.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtqlbcqowr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtuodvdikl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtynrxsjuz.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtssyeqqxb.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtyxefchnc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtoigraoni.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gtocifqshw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtdtulfhwt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtajtqxfrn.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtgiyvkhjh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gthqdvukhj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gteoanbatw.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtxrgiplwg.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gthyzxyynv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtcnqfyfaq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtltkotyyf.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtuhblooej.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtrdakiltq.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtmdqjqtnt.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtdergowbi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gthmruntrb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtxsscvzvb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtjpohcbrr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtylrgsswm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gtaepripom.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtvlcyvxyq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtxoqxcixd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtxhdqiimx.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtvpopxaum.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtuvddgtxu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtalrhcnfh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtxvadayor.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gtycnbmwzq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtptfuevik.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtgmelkzjd.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbclsnnbz.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtpmowjbas.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gtcisakgdf.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtbivtrbda.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtbyuxpcea.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtytfgbpek.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtszzdkvpd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtqxppznyf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtctxpmzlm.html


<!-- 参考信息 -->