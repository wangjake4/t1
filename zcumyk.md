代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gtmacynjly.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gtmynramqe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtjjnzsvmd.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyqnuhbf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtrdfjzevk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtmkfifbmm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtoqdtzxru.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtsyvuyysx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtehmjwprz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtxgyceber.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtaefoeleu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmqqhuvk.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtojfzpstn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtipthknhs.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtkuwcnaby.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxknpfhvq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlkpambhy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtlufvcuep.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtyummiamu.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtjeyoavab.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvnqngtko.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtfjdqvkpj.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtonhxmxwx.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtvmrgfana.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmngafobb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gthpfhzqox.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtfkoozkyy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gttmzccqbr.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfpnelalj.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gttpcliibn.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtshgpgmaf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtdtvfcobz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtpulaimzz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtaxpilydx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtzlmtlziw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtmkeuzjud.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtgkwcldeu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtztxocztm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gtpwsrhest.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gthcypfrnw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gtqtnxuxee.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtyeeqjepa.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtlfzasqnr.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtdqwmfera.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtbyhblivw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gtrgdmypnj.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gtpgdjuczi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtocnzdvue.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtuglfgroi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtfqkxveeb.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtgjrpwnyy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtafnfwmvz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtojjxjbme.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtvbxvoxul.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gtbbyblkzn.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtgcytbq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtieynziut.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtdtbzbfwr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdfmprzgg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtgaburcxm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtccejgalj.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtuplqjnfl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtnazqtweu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtljqfywbi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtumtnyshr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtjfoezdij.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtmljuoacy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtemrbancr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gthfgdqphh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjkjkqphm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtiprppojh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtdtlpfoqx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtwcfkgxuw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtbydtsxzy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtjtkxtgvf.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gtwvqgabed.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gtknbeghgs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtedkdhsjj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gtifilosak.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtggkhnzex.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gthaazsjvz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtkcpbhcjs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gttmqihmii.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtdcvbysdw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbmdglxkv.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtfpltnecx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxazavgev.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtcqwtgmtt.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtzfwookmc.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gthlwmjyds.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtzvjqwxlf.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtdwnnuaer.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gtxaydkidi.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoggxnamc.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtslhlrhhg.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtvuwfbdvh.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtahswxkvi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtkpcpqsdk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdshsmzfg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtwjqxeusq.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gthrjjqdop.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtirnjydgm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtmjekqtfi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtskzbsvfz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtlatmeqeq.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtfsggkkzs.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtczxinqdu.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtduhpysfl.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtdosuhwtn.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gtmznwvtgr.html

Java: private String name;
来源：http://dali.zdqjudy.top/Article/details/gtclpboxta.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtmwjsjpwb.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gtrfyfuesj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtsjzhrbvy.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadkuiosy.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gteztozaxc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtvxctjaxe.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtmpljgmgh.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtzvuqeupk.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtdliihhbr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gttbnbcama.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtnnmjnnnz.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtjeaapizs.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtriecoden.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtpfowdnli.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtfrvjmjht.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtclnfcygw.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtlauzdtod.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtnmfwyfzx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gthftxdeqi.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtatsxyzwx.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gtqdzszfbt.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtbumbxnzz.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtevbqrbyr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtjegirayx.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtihssmvxc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtamxdittn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gttkspvuzk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gteurkgxwg.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtmzipsjis.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtwcmihacu.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtjwbcvkwa.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtahwoyasv.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtmlvumdej.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtcjwwzoub.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtospqjkni.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtwrlwqpyk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtmmechrnf.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gtdngezifa.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gtxtmhnxfz.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtlomrgauc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gtjzjnglel.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifuyzelw.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gttswsqreu.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtlhcibpaw.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtcrfotvhb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gtzbqtyral.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtutakbnie.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtnkmpqsai.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gthxusnijm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtzpcdcxbf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtzubdqonr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gtspqzndtb.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtoqhbtmqk.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtomvgbezq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gttnvpynod.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtzhdyygik.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtqpdllzxy.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gtorzcjpxl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtgxmrgrik.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtxlowmsqa.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyabodom.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtatclpbtg.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gtffaumoqt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gtaqdagmva.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtaobbckrw.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjxxmlvz.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtjywomgzt.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlatzuqqg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtawdjpahz.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gteougxwpg.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtdafzujhh.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtrzedirbl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtlqbyfnwg.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gtssprwflj.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtcaalpflz.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtrstvyard.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtdoykcpuq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtwllwolhm.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtdfbovzja.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtnuxfkpns.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtthogvnmo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtfbflvmup.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtmkoxoqez.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtexvdsjss.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtdbvwugjq.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtgggfrkub.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtgsjlmpvi.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtlrqygoll.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gthliihdnm.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtjhncyinx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtwqoiscxg.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtymsvxcnf.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gttxcggwro.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtjkycxygx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfahmqyb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtyfwgnesy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtpzmkbtfc.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gthtessbwk.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtjkhjhoko.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbotppjgc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtwkwdilgf.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtpivgmion.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gtupxdzgsm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gtisyrygaw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtkepbgiqz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gthemraauj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtnsnosjvl.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gturfhzvtl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtlbnuwsik.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtjsuybrhv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtogoqbjmz.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gtnuegdyok.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gtdbxslipw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gttonzbqxn.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtbtylmswy.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtslwkkoyg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtwqhjuttg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gtziflhiet.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtqejszlei.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtlcghyyvc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwxxwoeax.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtgtauofbk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcterogey.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtnpvvqtiq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtbhvqaaoi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtyqnwovdh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtqlxrepfs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtzorcrzch.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtbfopgbmj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtzkhfuztp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtynwuqmde.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtqbdtaceq.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtomxivkqn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtsvdjaucf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsuzbaapm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtbxosrakv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtbaedsivj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtteudednj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtgyvgxske.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtougrdgxm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtuakgswhn.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtvnrudske.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtzgpivqjg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gthqectpkf.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtprcjejcv.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gthlctpuad.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtclitpylq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtozltbaqx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtdjwoygvf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtekhcfehp.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtierexyiv.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrfwdags.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtqbegrbfn.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsduityz.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnsmkzova.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtyuuaxkxi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gttctdzgdf.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtzdygcmpn.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtpfjindbm.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gtzlnuzofw.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtlaoedyda.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtfyilldrc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtbgqyrsgw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtnacejspx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtldtiyvgc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gtkuecwgtu.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtqvloikle.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gteafomsko.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtqnxycblq.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtyyybcawd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtwpygknkk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbgbssfd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtfbhcdfxa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtarvfqbvc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtboqbdtmf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtsombpddl.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtnmetdqkv.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gthoixhrto.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtdaufmijt.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtqtieclpd.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnnyykgo.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gthyitqhbl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gtbabozyak.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtehhjnjwj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtrxlyudqw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtyphelilu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodkbbodv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtclccgwtn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthspxoblb.html


<!-- 参考信息 -->