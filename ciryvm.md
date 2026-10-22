代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gt2jzyepxjf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gt2fqnattcu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2fkfzcbgp.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gt2uvgtpwjs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gt2gfljkrbv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2uglpkvvl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2gxgtknxu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2hrgyeyek.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gt2otkrvrff.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2utdkmwce.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2apzekvsw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gt2ogztdcxk.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gt2nrsnzhof.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2rcckzjue.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2tkpyvhil.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2edglhvqd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2esrgkkjd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2ncazllox.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gt2phlnqjua.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2rshrvplm.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2ahlunymz.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gt2zcszxhou.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2zrdhgrqz.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2hmfnuibk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2kepwkqbp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2jltriqqe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2tpuuhfte.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2bdtifcho.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ufxbhqqg.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2daigxssf.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gt2fniqijac.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2ocknguqc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2atqisyum.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2ljbtzvle.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2mwlaegij.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gt2xvnogdtc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gt2jrcqwddl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gt2eqegnlvo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gt2mouyvkgc.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gt2llrbvoew.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ivvv.top/Article/details/gt2ykdywadp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2mkfdoqtc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2tyeghcgx.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2kqcmizsl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2tbhwtkum.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gt2vohwbtfe.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2yxbohros.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2ohimsocy.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gt2gvbvoruu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2exqukjkr.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkkrlkyf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifgouxzw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2pdcndjho.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2nmbtijun.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gt2nzuafogd.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2uoiuwhlp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gt2ymlxibnh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gt2tbovzbqr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2qhjhoqyo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2nippltmp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2pelaswyn.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2btkjrpdr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gt2zcshxdvx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2iydgazbl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2aynnbkar.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2kdusmwqv.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmclmkmu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2wffcmoqu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2cwqscdjn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2wcxsjxff.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2swektrjr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntyahseq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2bfgddvmd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2owajqdgp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gt2xiiksbai.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gt2yrdwtphf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gt2ztgzpmym.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2cctkdeir.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gt2dntikjfr.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gt2urxpqnpy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gt2lusbsvud.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gt2kgtwazye.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gt2dtdtzczh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gt2rnssugaf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2wscvigdi.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gt2vjkjsrod.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xxwaahun.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2yybrvcpx.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2gcgcaohh.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gt2gtdiedlf.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2yjxcasba.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gt2mvzdfspn.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2htlyjvux.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gt2ulwbrtkk.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gt2btzasjqf.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2gitpiuhk.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gt2xcdpcsut.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gt2mcidffhn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gt2hjgcqgaj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2icnpocyu.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gt2cyldntak.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2qajrbxst.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gt2zrxwspxz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gt2jzmfdxyn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmloffyh.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gt2ffjnhpue.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2bjcsclxp.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2veygpgez.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gt2qvnpssmc.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkhagctc.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gt2uvnkbnfy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gt2ibjwaqcx.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gt2uixiywdq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2ecsjaznd.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2gfqxylal.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2iraigiwd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2unltfcqz.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2nsywsqkv.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2crffwyzz.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2gmyrwakc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2adfgkuth.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxwzyray.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2bkolpypl.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gt2udtknihc.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gt2nndrwvdq.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2okhxpsze.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2piwlajmf.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2qcnlsvkz.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2drlugwdq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gt2mofubliq.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gt2kjnweeey.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2iiiywrqa.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gt2eqeexiao.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gt2qrjloxcc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwkhyfzo.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2jplhtixr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2udhymfda.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2gryjuszp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gt2oepjpwkz.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gt2oryhjltw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gt2emjmkcof.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gt2idjobdtj.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gt2jaxzqtbe.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2iwnuqvcn.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2bgmfuawc.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2mqtmmtvs.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2ltpwwrtm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gt2oqclmpji.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gt2yjxjtvpv.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gt2mgnhozxu.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gt2yggqrnau.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gt2qmmpxwmq.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gt2koszowik.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2zezfxhon.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gt2lgdwzolj.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2onrwiaue.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.9152youxi.cn/Article/details/gt2kyptyctp.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gt2cotthgys.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gt2xyhdpwck.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gt2kqysepfd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gt2flyhggpo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gt2vpkjkfzk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2kszrqlyw.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gt2rqxpluso.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmxqajgh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gt2zobcdhcm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gt2xliublkg.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnolvkye.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gt2ieaktdak.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gt2jexkeqfy.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2rjlwrtga.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gt2ezbffibk.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdzhlxkp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gt2ashdgzfn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gt2psnosyzy.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2xdfjnpbv.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gt2ekjettim.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gt2dvizruwn.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gt2lwzerltn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2azpkefkh.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2svqwskte.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jwxzknrd.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2txhbrjuk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2ylnmstwp.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gt2jzdconre.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gt2rwsowhpo.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2etngmndo.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2enlzqglh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2kttxhtsb.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2haflleuo.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2xgtxdpjy.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2irlbaiza.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2njohrzjb.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gt2raflysmf.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gt2osagmuje.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gt2mivbakhd.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2zueaeptt.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2dscxddnw.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2jwxuoaao.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2aasotlar.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2hgmvenxp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gt2rsrinpdn.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gt2ojclwgaf.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gt2ieuveyre.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbkclyun.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gt2gmfrnbde.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gt2crbtqgah.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gt2ozbfzxwv.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gt2ghoeftum.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gt2phpkaqcr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2lzvoknuf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gt2jiollbpn.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gt2tyywmrhp.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gt2kfxixlhm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gt2tgeuexov.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ogbiwchg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gt2frwdddqj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2dzusilsv.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilotecmm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gt2pgcfhqdj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gt2sbzwlcpr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bumiekym.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gt2ajirgtwt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2zdxoxcit.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gt2qakoxetz.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2fglbacbc.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2khhwkmma.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gt2iozfzfaa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2iyknnysz.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gt2ozcrzink.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2tzweeqhl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2btbwopxo.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2mqbunien.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2yhbfggnn.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2cmxnvcso.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gt2sxffnnlh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2yobxwfww.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2zwtqtntz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlahqdit.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2fmqlzwzw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gt2tlpyahgh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2zdrhbxlc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gt2fmfhclts.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gt2mywutfni.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gt2fehshxka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2zbpjrjxr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2atirialp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2yjwzifbu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2ivgwhjgp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bavqwqwd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gt2cbisoqay.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewaihwgb.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2yczhnywt.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gt2ntytdabw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2twagztif.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2tmscqbph.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2chytkpnm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2bdldioxp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2zupyvyum.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2kslwqprj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2atacuapc.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gt2vhshbqng.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrxjvhwr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2vigeomfj.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2lgjuxjsp.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2husmppeq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhvvldl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2qikmjaap.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gt2wlrhwlpu.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gt2xzebkvks.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gt2ebrxcwid.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gt2kazzciio.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gt2murgxqmv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2tyztgndo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2qfwrgwrf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gt2zcfwxbip.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2mlgvrejo.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gt2kamcqxba.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gt2nknxtglf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnfthfv.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gt2abjyocbh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2dgttwaoh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2dvogkmnp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2nlzuzgii.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2oqkkseho.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjqvalnv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2sulzvaxn.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2jehjjdvz.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gt2ikkjwtlp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gt2hhczilog.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2zblgrzlr.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2uarfklio.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2zqjelnom.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gt2gtqkgqfs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gt2lmodgxrs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gt2spkyztce.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2xlivxqnl.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gt2tnyypyki.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gt2lbxfokgv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gt2yraenqry.html


<!-- 参考信息 -->