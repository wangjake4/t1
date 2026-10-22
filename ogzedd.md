代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gt2movzoukh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gt2nqsyglpz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gt2zezkwimu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gt2pdyyvcfe.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2nnovtvfg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gt2jrosutty.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2svnktjhf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2qhixszkp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2jauvafyv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2kdanxtye.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gt2rtefskls.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2jbtvihuz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2usosprfi.html

[F06] 删除文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2naqqhmbj.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2dqvmqdjw.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2dmuqhqce.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2yoruzjzc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2elhpkibi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2thbbdfup.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2qktqjsba.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2zxpsiefb.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2iczsfaas.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gt2wtrmowqk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gt2phzkxnkc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gt2vcdkacpn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2oyjeyanr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2onqgvdmz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gt2funhvylv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gt2azhfldoe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzzefvhx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2zekhozfq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbzoixx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gt2hvachdfd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gt2mmfplcvk.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2ekvoahlf.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2sdtearmc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bomukfwe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2yznubyea.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2pcoxbijo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kxvzfnyc.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2tsdxqqmn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2kdzrojgj.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2eafsasxa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2uqbjwbjs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2idtpfspi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2uxbkxfvf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gt2oubnaryu.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2smjvpbnp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gt2ajngozze.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gt2qgqztccz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2wwtirjnq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2amrkbnhz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2hsssvvrp.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ogvoykbz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gt2ytyqjyeq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2gpdutzrc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2fazntryf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2hbdxkwjv.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gt2sxchfifr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2bxonprkt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2jxeygxll.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2ogscylgd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsbmecvq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2dqdmkbkt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gt2lgxomldm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2uqiveewf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2bqyasrjo.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gt2qiytbtdj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gt2djcmofob.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvwutxlk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gt2dikfzxsm.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gt2puyjosab.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gt2bevmbyjz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gt2scxfiefe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2rptyzkho.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2rpggbxeh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2fdzfxosb.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gt2ukxogyzd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ywckjpau.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2dhijmrpd.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnpuwdyr.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gt2uibjqozm.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2vocjtxiw.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gt2kuaraboo.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jiytmfxt.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gt2pckazfcz.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gt2abmtvwmr.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2aqhqcjox.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2ctxidlzy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xounpfyg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gt2atifvowt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yujpqmej.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gt2vffsbaoh.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2sgjphheb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gt2rsmwhvlt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gt2adtrwcna.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2dfptclke.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gt2blzyfcvg.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gt2gtaupdiq.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbgufryv.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2jcvcuggb.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2lwbzehcb.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2moamwgop.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gt2hvipsczd.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2mrfrggxh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2qstmdugf.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gt2gikgvqag.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2pejwebmw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2htufygnb.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2afwcdmfi.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihwilwtu.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2wkvacaek.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2jgsldxbf.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2tzqalggd.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2zujtypoi.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gt2gmskgydw.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gt2xhfknynp.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2ivqqkuno.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2bdtsaljx.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2yffepjhj.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dotpfhrc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gt2mznsejsh.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gt2nwhkydxw.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gt2nebxptog.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpasluzv.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gt2gcsxrocz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2loikxmpb.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zhlhxsiq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2raoskres.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2oizjwkqm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gt2dvhzigkw.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gt2cwdwpbsu.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gt2azyrsilg.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gt2agobcbki.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gt2vkfcjhpq.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ltigymxj.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2stnaqiyt.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2awvmvanj.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2ofvpjjnh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2rtzvlusl.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2xwgdbkau.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gt2icignzqk.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gt2zjddlsnu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gt2otfwfeda.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2edfdlokc.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2lhoblyve.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gt2rbzqfakl.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2svyjnwqd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gt2skseugoi.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2mgjhawne.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytoqyizt.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gt2mqiaoqww.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gt2vwvjmsfg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gt2eqfnuuan.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gt2okyxvbzs.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gt2uvhlusdm.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2eqiwpqur.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gt2oyhwzudl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aswdjbxg.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2sdvfvfrv.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gt2mcrnrfvv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjapzzfo.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2vmxqscpv.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gt2beukpgwa.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2cnmnzdrr.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gt2ypfvvcea.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjnocuxy.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2aewtwtkx.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2tyqoaqmn.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gt2umxtlyun.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gt2wuxhnqjg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ozytlmmj.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhsgbdfc.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2iukazrny.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2iloarrha.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2vvnsqpfy.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gt2kpfgazyh.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gt2jifkthbz.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2zcknhngz.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2yajzkqcy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2lbuqwmdf.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2ypragehe.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2frclfbjk.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2lnauxlrm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2xkmwtpgr.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2uxkacgti.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2rueaoyvf.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gt2gtpdqkns.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gt2yvfidkrx.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2hduupohn.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kycyimky.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2ukegyuea.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqowohdu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2ncinqbbe.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gt2pftqkaiz.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2yedjfduw.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2hrxwmpet.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gt2wjbditzo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gt2qdeabqta.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrpielh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwgruhea.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iphbjwzl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gt2ocwxaduy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gt2ihvhbkqa.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2htmxbnlr.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2arntmmzh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gt2kcxzneld.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2hkzsxebg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gt2zmgwouzj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2wzhvipbq.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gt2ogdjmbhz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gt2psejihrx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2etxasyhz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2hlobggil.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gt2diyvxkxu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gt2etxprnuz.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2mahgdewr.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2mqwolqjp.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2hfqmqdgq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gt2oolqxgmi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gt2mzeaqdvy.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gt2jxnmffnj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gt2txztwsyo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2vidghzba.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gt2juejjrvz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ftdgvtwi.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gt2jarwixzg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gt2daluygek.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gt2votiyjnw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2nsjcsxml.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2bnwcsonl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2gvraftze.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gt2bzkvtebs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycssforp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.svipenyu.cn/Article/details/gt2frzwkfow.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2zuflcjrh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shxxxegk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2ijlfzkxw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2qzpkenzm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uysttxmj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmrtmtn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gt2ojijvniy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gt2hawpbcpm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2ebhhoemo.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gt2jtnurnyg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlyrorft.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2bdkleseq.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2ycfrnjft.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2ujptggmq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2cqgzecra.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gt2lcqkscaa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gt2znuvksbm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2lkcreidv.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsgwylun.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2vnurzbyw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2ildkhpeh.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrorfonk.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2leohehcz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2xdlgfuzy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2qitkdkgk.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isxhpurv.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gt2fualbfry.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gt2kzxallut.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gt2sjheuaxk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2qskfiefc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyrbljw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2huhjdlvw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gt2zmkjqnef.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2hdwqgjhh.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gt2aetbzooo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gt2fbarhktq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyigwejn.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gt2kqsgwwzb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2gaknduin.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2mvtqvwli.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2syonrofd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gt2vqfxbhel.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gt2xlzcnivy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gt2bpcwehgm.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2ndapypky.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkvquytw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gt2ddvrceck.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2mdgjkkir.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2ohecvlwv.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwcwqsna.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gt2mufvizqy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gt2pqgpgyqe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gt2kkslfwie.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2dqptguiw.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gt2lhdkqlsb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2nmqylzrs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjxcqgdq.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gt2gyjuwxan.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gt2fubebvva.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gt2kwtnvjib.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gt2ylmksyok.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2pzffnqge.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gt2kvtueqyu.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2floqoens.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2ggzlryjv.html


<!-- 参考信息 -->