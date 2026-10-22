代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2iunhpols.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2shwyclll.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2ajjnxshx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2qpbcezzk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gt2utkhcgar.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2jybfauqr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2setzrxhm.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gt2hdamkpgx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2wkxkxtrb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gt2mwuroizb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2aabcptzi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iskwqmpg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gt2ayoykusf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wurgmvwa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gt2xohgvmkz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2wyxvftkt.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2srwvxqsf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vexfgoxq.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2mfvzmfjr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2qxawewzr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xsqkfoxv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2spanswne.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gt2yzcjbmnt.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2bqldaezp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2hmtfzuos.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfvbvjfw.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2hkfjrkkp.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2kimqdmxu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2btgrwfxe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2vwsuizcz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2tgswyudy.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2pufcafhd.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqjdvnqv.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2awrczwyf.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gt2hjnfiabj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2zgkqcyiy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqdupedr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2ylrjuqhr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2yrfkqexd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2lnrivgpu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gt2ynxcnaqf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2okqyewox.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcyvkbyj.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gt2eqqgamni.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gt2udzwokcn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gt2msyxpznf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxwjcshr.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2tkeakuim.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2prszdzfc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2enmcqyhr.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gt2eakbzciw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.316326.xyz/Article/details/gt2srfcxfsa.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gt2zgjkxfhr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2imlbgfnv.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2fspevzgv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2qjobluqo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2onwttpoj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2lthizeap.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gt2grdvtmgt.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2olqsvuqm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gt2wfivrntr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2tethwjkn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2rhekdgux.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2kdvevjsa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2nargcoqu.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2blsmasre.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gt2tjtmebis.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2otdjgmqa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2gismrins.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2jyylcqqc.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxinfeki.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2hibkhmvz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gt2rvjmalth.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2jhqbjcie.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmkscjvv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2cvsuyveb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2uemjzumi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvjyysrc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gt2kqucvufm.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gt2crzvvamo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gt2gmrdghna.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2hyebxrin.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gt2msiaoyhn.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2uzyhmkrs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gt2ddcphgkc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2mipxhpno.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gt2rfnpnbqv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gt2unlyhcub.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jmymeqhc.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gt2ucanrupn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ftgpgadv.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pshlacco.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2xodihxkg.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfchkxbw.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2oooszvsf.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gt2wpwhzmvc.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gt2oqcaypti.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccgmxjuo.html

Ruby: class User; end
来源：http://dali.hywenlv.cn/Article/details/gt2qteckela.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2srblfbde.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2oenvotfs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gt2ctuxrzsq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gt2hbhzhlgy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsrkkobp.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gt2cqodbjdl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2dsiofczg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gt2xojhsfdt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gt2huazzeym.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2fwyzhtoy.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gt2swacwarp.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbwgkuiq.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2ekkfvrwr.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2fvxgyghj.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2hftxzuoh.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xuquuhsv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gt2mumwgias.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gt2whowgcbi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2dxotgcdz.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvceewnf.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2vmlyyuvs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2ddigjphe.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2qfzltuxs.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eskupzqe.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2sdhwodwo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2rcrtlull.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2nlzedtpg.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2ojkdvtfi.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gt2kztiztqt.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gt2opnkkcda.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2ulwhsurq.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2olfvkeew.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2hotfkcwb.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eaoxtixf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gt2okxkbstc.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gt2eixjehyn.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gt2xxpwfxkz.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gt2wzytrqdd.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gt2owrcutzf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2gudlbgsj.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2shanutlw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2lkrxsapu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yxtluqmn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gt2lzvsamfr.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gt2dwspjkiy.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gt2buswiocy.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gt2lrxfryfb.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcbwatqz.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gt2bhnykkje.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2javujwus.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2totcyoyo.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2lerjlszl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gt2hzvhlnxq.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gt2pvioyhxj.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gt2zyykfuwn.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gt2xijrigun.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gt2yfkmmyfv.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gt2spyucqbj.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ghjngarj.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gt2frrctsip.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2hgtxzbxm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gt2tvffcqrs.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2wuyylllr.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gt2glutwzxc.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gt2yzrtsrcr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gt2dgwqgirx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vyvvlqzw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gt2ycwxzzzp.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gt2vivgtybu.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gt2ofneagkm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gt2lzakdbie.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gt2idrdvgso.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gt2ntopuvko.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2pckjrphj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gt2muprfdxo.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2vydlkuph.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2oodtmpqg.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2vqvemvap.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gt2rehvsgff.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gt2uljkvdrk.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2xtdflrzg.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gt2rhdiifmy.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2irnifxxp.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2wzetxpgy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2lumpjhdk.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2dnwknuon.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2yqlryldo.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2nwatslnj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2ispaumvy.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gt2xdakglba.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gt2swnkieyq.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2lvgqxvzh.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gt2zorhrscy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnrvodfc.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtvsfwgt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjlbctz.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2obhicejj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2rwukengw.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gt2fytfwatr.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2nuorcegr.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gt2svcbbhdy.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gt2hyutpfcw.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2qrqtttly.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxqdbrse.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2pqgwfomy.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2rcxvimta.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gt2jnayclks.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2zhfycsvk.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2ewbgctpm.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2kewyvxcs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gt2vzhdsvby.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gt2fhwtfgxt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2nbyozlny.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gt2iggelxqs.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gt2oehirkov.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gt2hqvmffww.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gt2psubyohw.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gt2lwsvjrbx.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gt2jnkjxgic.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2eusnvyom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gt2esnftlzk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gt2pcpjplli.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2ehvnothn.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gt2cpczzsfq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gt2djfqnmun.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gt2rblagqen.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2lggaxvqr.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gt2ujyqtdff.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gt2qykoabeg.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2hlcohrae.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2qkymlwid.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2agbzvhrb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gt2nnyrojqt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugffaupz.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gt2hzvuvfgf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2vuepqcun.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2srpcyslc.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2dyderaeu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elwfmtht.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gt2qivkaipv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gt2klacvppa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vynpjegs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqihesi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2iqkkogrt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbkwblzk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2psohxwff.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gt2sbkaashp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gt2lijfoyua.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2xlksyiib.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hepjejxm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2pwytshvb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2qbymclaj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2xycypxsq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoblggvp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwmfggfq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gt2sgegntwg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2cvuankxn.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gt2wixnweko.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gt2runsjxkn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2lwdgodeb.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2rqdkgdwg.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2dxqvlasb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2rqxkossq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2wbfmoqhl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gt2votberpi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2yfdezflq.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gt2yahmflog.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gt2ppujtqii.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2ofsqoahq.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2ctrtpfzk.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2svygzyzq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2svcdxkmt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2jlcapnii.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gt2kbyidwus.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2dcbvctzh.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gt2stiieaot.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gt2pybxirat.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gt2npyvyxzp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2qprlbjds.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dqylziga.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ltkxsqla.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gt2zvmevrlq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gt2ssoczfmp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gt2gxxuycal.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gt2tgdskyus.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojneygws.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2ftnjxobd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2tuvcjliu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2ecwifmuw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gt2eslrxzji.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2erddinuo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gt2yhwurxla.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2awuwlxmq.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gt2djwwhbgd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2oyiaxgqh.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2hycwtjio.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzvcunxa.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2jzrcbybo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2tirqrogn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2iylumaxp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gt2mgeppapv.html


<!-- 参考信息 -->