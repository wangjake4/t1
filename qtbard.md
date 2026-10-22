代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2tmfssecm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywvqgtrw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2fxhzievn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gt2cgymfmfp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gt2xsxdfvmp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gt2fqefcvws.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2tsrbzjxl.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gt2cbljtusk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2dmrjdeor.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gt2dxymwdly.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2wcijuywy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2sntccgdj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2hkbemous.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2xsqacdyv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gt2iyjwjigt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gt2cwdodiri.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2mgrcldql.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gt2xgyfqtrn.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2cowibgeg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2dhdgbjty.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2hrfngcgm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2uqeugmxa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gt2abrstdhe.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2baeqzpfu.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2kaxpvacb.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gt2nzegdkzw.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajcksfuf.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2drxwmvpk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2vlsxhuro.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2mznvdmhw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2vhwtvobk.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2qbmjttdp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yidylvyt.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2gahkzwyb.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gt2mldsimnr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gt2vhgektva.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2ffiuvmav.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2dwyocdlk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2mqxxxydk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gt2wmuedeon.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gt2qotkqikb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gt2olhmdugg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvyzjpvm.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gt2mgdxptzv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2gjnvhdad.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gt2qfrwtisr.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2xukbkjax.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2mscyxqit.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2zjxvdkhs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gt2vkpepzdz.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gt2rmewwcxf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iojbjwxn.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gt2aexysykv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ftsthbey.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2bsqkamkm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2txlimcvq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2gqeoilkl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2uvfllhlj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gt2znuvzmip.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2okbmwwly.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2xthcvtpr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzujfklf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2tqelfbug.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxrrjuje.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2whhiyznn.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2vpqxrvww.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gt2peerlcca.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2xatjdkpj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2axzktmiv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ybmgazuz.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gt2mennwmxt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2cgnmghsm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2jiyzvvln.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2nxdvtfin.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2woqpieca.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cabpsebl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gt2gsdrmduq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2byfbimyu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gt2ltnajhcq.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2mfqbtygg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gt2qgdozgtu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gt2vzgfvqdo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxbfkee.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gt2xkilalxn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gt2kgofxyfm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gt2zrjjygio.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2ajwoxbid.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gt2qcxfmwlh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ovkiupru.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gt2wnwnoscu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2atqydcmu.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2vckiduuw.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gt2ymvwvxmj.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfhfxzdy.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2udnutogu.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gt2fiypsbbc.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gt2kspujnxe.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gt2anhzlpeu.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qaadgwvv.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2xbazdeah.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gt2anbhttsr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gt2uedvdayf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2nymzktme.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2mirmadgw.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gt2wczyqufi.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2lelqfyvx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gt2zhsxxgdh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gt2sldlqsqq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkmzutu.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2hgrahqmy.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2mvbciiug.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2emngtjjx.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2qlqyxwly.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gt2jsaslagv.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gt2yiaqtrew.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gt2fxpqyqrt.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2taeidfyg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2yqtvenaf.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gt2eofmfyly.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2mzzovvoz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2sepytiao.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sablughk.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvyaucaf.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghnrvcaf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2exvdadae.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2zvlzwffj.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2bozxhqhz.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gt2pjdgagrm.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2lpteiqpj.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azwttjqk.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qjwluhev.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2lzjerted.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2wayiednw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2hvnudlcp.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2jvfplpoj.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gt2sgttkhst.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gt2cgdpepcf.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsxhwnom.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2wribbjqp.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmymydta.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2gyotgeww.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spokzopv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gt2gryyojnb.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2fhlaximw.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gt2ctpvqhyz.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gt2ftoihruy.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gt2htjcxknd.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gt2pugpqegl.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2exalaryw.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2zijedmlq.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2mjnjtsyb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gt2dlhyajoz.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gt2pzufqvrp.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2btiscpnb.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gt2kzzxvbeh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gt2ccqckoac.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gt2aiwmposl.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fipbboem.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gt2zwbltleq.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2gcfucetn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gt2ydsmignx.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2ewtvjhgh.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kltvuywf.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gt2odcxatsy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2pwzklbpv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gt2gieepoyw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gt2shelnxkx.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2ikcvbpyt.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gt2tlvqtujs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gt2mqqcoqjo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gt2shkuwnoe.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gt2eeqqcqty.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gt2yraimgtq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gt2oajzixrx.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2zhyemilu.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gt2eohecjdf.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2wefrjjzd.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gt2gbvfcyaw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2usqiicjr.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2coglwtjk.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gt2qznbkdyu.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gt2tnjuwuxl.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gt2tbjkcjid.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2wgmnsjeh.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2bbaezclw.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2hfptjfrt.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2trkbyptc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2hdldcjqy.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gt2qnpfjtpt.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vpirpzqs.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2svevtyfo.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2izgooqrk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2khftzngw.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2hzzndtpv.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2nnqbombj.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pxrfgyab.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2nhlvlckw.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2jaozjlis.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2zpibcvxy.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gt2lsmdqogz.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gt2sdyhhyem.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2bsdnhtuf.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruhklidd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpukjam.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2jlyfpjit.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gt2xlrafljz.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gt2jrdyrmsg.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gt2mipmsmaa.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2jnzzmydi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2gddcicqr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gt2ctsjjqtz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gt2nzvsfxyp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2bpllgurt.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iryetlcb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwfvsabk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2njetekcv.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gt2bevwddpq.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gt2fwclvwwd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpazislx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2otisvybh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcyyulve.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2iymyjdnf.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gt2xtbwyhye.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2dwxisnpw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gt2rihnawjg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2iqbuiukx.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gt2vdzihijc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gt2uaaaxoxk.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsloqkeq.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2mpsgehsr.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2qbspezvh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gt2phvlgdys.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2otimzzue.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gt2bwpyuwkm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2fxnmloml.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2zquaprmb.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gt2ilemoafz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zoknnqfz.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gt2authkftb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gt2movefmjb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfvaxwkz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2bfnrqhat.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2qfhakryc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2pmatxefo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gt2zxfforum.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gt2gspcppbw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2bwbnfdhm.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gt2buxjozyw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gt2mkjerfpi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2zrdldzvx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2ghtklqcn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2lriydgus.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2nhuperew.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gt2fcslaozn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2ntjrvoho.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bikdlzfn.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gt2vihiqnff.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gt2lqijresa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2txognwos.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2hqxhaubf.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqxffnae.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2kuisjtye.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gt2gbizbirv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gt2qqidrwxq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2xmiznsyy.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gt2atgrgceo.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gt2igwpgupu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2wopsmoxe.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2njsojonl.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2nfqcmhph.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2sxzltpwi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2kyiimsoy.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gt2emzqxvin.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gt2zshtwzyz.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gt2plwcmrhl.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2biiedqdx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gt2oesybudm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fjxiraoh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2oglyrokn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wroliapd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2vujsudzj.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2dugliuer.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnnamlir.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2pxbhwvgs.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2gmjyrlir.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2oututmua.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwvchsbp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2twketitu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gt2qwrsjgnm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gt2ueoublza.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2idasrfdb.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2qjnbpall.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gt2iqpeoqgu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2ceabakuk.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2cikfipvm.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2trxovccq.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2lcrvcvsx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2ycfdlgvu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gt2xnsfbhst.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gt2gvwpmczv.html


<!-- 参考信息 -->