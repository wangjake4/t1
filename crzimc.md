代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gthpwohxva.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtbttsttrg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtjrwofggn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcivdrbaf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtfodrusnw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunbxcwto.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtxxirkamv.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtcedzlpfe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtvkgfegxl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtukfvlwvo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gthcoqipep.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gthpopgoeq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gtrdldcnwz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtzhrlmfuc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtujrjnbyt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtxbicrhqi.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtehmlfwmw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtotegmyyy.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtmgayhtho.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtimimoirw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtxrmlryno.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaglskbd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtmbymudwj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzjwnxahp.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtsbevntxb.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtwcjctxem.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtgrlnplqj.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtcavvduol.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtsrgsyvbc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtmjkadlsa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtfvbditdc.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjrtbhqlj.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtuvdzpofr.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtzeyqumpn.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtiqvcwtcc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtifvndfsc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtcwzuwals.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtdcthplqu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gttatqjoux.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtpzuxsoyp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtgvxagyuw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtnliagvfn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtcikptkwf.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gthqvqvcjk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtykosdzng.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtqdfacmfh.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtnteabpzg.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtmwwspwfg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtqbckjhrp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtxbulveoo.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtizbdkypr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtpxknyuqt.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gtxvhwlyjs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtoxzluuxy.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtnqlolsqm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtmoptizcp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtutktoium.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtezwuyodl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtjtffrqkf.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfxuutpw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtubvdvqxu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtoacwcajv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtnhjlqkqn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtcmgtlrke.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtpcmjntyl.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgywdtgqp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gtqbktluiy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuqouncxi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtecqiwwnb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtiakuvwlb.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtepkhjyua.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gthngexibp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtucvhsatv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtrsxakqrl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtyxqdvmpg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtioyrjdfz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtpasawuwz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsjckdvnc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gtogbsfmsn.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtioppekto.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtvhyrspwq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtzwheqrjk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtgkxkasas.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtkpfjcjfi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtgupgjfow.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtsroxmilw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gteztdvewb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtdtbeyajw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqkqwwmip.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtustutugy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtltmjhuox.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtehmuniux.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gttoptcabl.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtbciqyrxi.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwxtgaum.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtswaopxyf.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtiuaxpmje.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtzwgncqoh.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtnymydypx.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtpgitzobc.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfiiwemx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtbdnpqkuh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtbkjwgrzh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtejcgdrqe.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvfbpumsu.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtrhpuymie.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtuornuuas.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtnvwwhywz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtgzuugwce.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gtkbqlhkhp.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtkzucjqsm.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwfhqpvr.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtukuuvvug.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtdxolrbuu.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gttnerazac.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtthsqigxx.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtzvdnqjst.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtetzdczsy.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtgsteyllm.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtfduwubko.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtdjwfqohq.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtzjybholm.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gthewpxxdh.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtatdapbgx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gturgldqie.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtmwuokvli.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtifbgazsp.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtylxbzjcs.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtrndwbmcw.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtlioaofha.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gthfpyogxu.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgtrryny.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtelwaxnph.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtymcgaoid.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtphlnaxuk.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtjqjqyovs.html

[G06] 重写方法
来源：http://dali.yj202588.top/Article/details/gtzxvkkikq.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtuuxfihdj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtpvzmeejf.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtywtpslie.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpxfrhvbd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gttrgqxnhd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtvaroujos.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtniuyqeun.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtdnnjlgzj.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuazcbbz.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtkbcwykis.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtjechdmrv.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtviiazwey.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtjmigftvu.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnjutyqh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtontudrlt.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtywvywphq.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtvgljgmab.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gttzdcmshh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gtlypzrntk.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtsoavbjjr.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtpuocwbay.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtcicvmoqj.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gthufhdwca.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gtvzaopgxf.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gthmtxfiea.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtintaesmr.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtvxdfvqoj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtyidknsao.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqngxnmtw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtdlattwzv.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtyixfysmj.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtamxjkosf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtlttyxlbc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gtybxznokw.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcxqhgbs.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtxyrojaih.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gtmojzfwwd.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtaotiopuh.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtratxhyia.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtoomsulxx.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtmmbxpnjr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtkjjasyhf.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtdrrbprhw.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtijlxwizo.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwtiwkex.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtdnrildmk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtopmdrrek.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtxvwciryh.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtqoyrdkdq.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtgimliytc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtypnoakja.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtmsqpoflk.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtvychtsxs.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gtcjlpnrjq.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtzzlxpbcl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtirxywmny.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtxygjcgxx.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtebvvocyd.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtevsaojov.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtjuxtjvyq.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtfphwwhui.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtoaykkduy.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtlyjdhcpr.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtxocibdzv.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtijkxrdew.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtkbjvxntg.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtxiiualjh.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtnipndsbs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtrjbmxdte.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtcwbtcpwj.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtclwhviez.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtudgdxrnq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtxwombzrc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gtqeetyjnf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtjsurexfq.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtfdfrcbbc.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtkigrfyhj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgphmmdqg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtmmvwepqf.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkusuuoxx.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gtdpnhdhvd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtwurtbyuf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtohykupnw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoevmzdl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtuudzlcqu.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gttenfauml.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gticgcbtxu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gtxaqxgbyj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtcpsavfkq.html

[G16] 对象转数组 / 字典
来源：http://dali.chenjidiqi.icu/Article/details/gtedlfefei.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gturkxrgaw.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtylxduytk.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtindclbvv.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtsvuxljuu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtxwbotwtw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtelckrpuy.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtryvcnsqw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtrnqdsvdk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbpwaxjxn.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtigzrjmqo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtamluxnpe.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtiwmzecoe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gtyessqner.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtcpufjnzo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtonkeofzf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtapggntmm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtgwcunusy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtazvtvahs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtujapphai.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtrzvugtfp.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwdgvcyt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtrpjzzjru.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtbqomubzz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtddersckw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtsfvblwjn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gthqwhnxth.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gtijrlcehw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtqedmdoqk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtmodlmqkz.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtlogxtpjo.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtkcvhlurs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtsbejihos.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtgflfludi.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtebaaznuz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtmqdikgjt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gtzcpctngm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtmoaaskjm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtbgpbhkun.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtxxmyhaok.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtaybxpgow.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnnmuqrh.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtxhisfeex.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtcvwrhwlv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtvdtwcqgg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtmwlgievm.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtdmvyywfa.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtmkdhtcbs.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtejuoolyb.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtjbuywohb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gtzrgebnkt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdjumvpk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtdgntwrgk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gthdheybhk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtpymidgvy.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtdpoeyqyi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdvsfkox.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gtivsuvgdt.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvknjixt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtncjopqxo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtxgrigcbk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtubzhtwtq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtffjjmjof.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtmhwqpsqy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtqzxqgtvs.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtcbwifkcb.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtknkegocz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtptgasyrj.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtkalxxsev.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtjbbngahs.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtydvofxbe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtafakbqcd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtgbjypuhp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtdvgviktp.html


<!-- 参考信息 -->