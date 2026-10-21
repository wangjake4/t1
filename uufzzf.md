代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeyujdat.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtkpfnbidn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtqtzgdxjh.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtsxxjcalb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtaagflhnf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwonxueao.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtjjrfffrq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtnmlshxcm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gtyordljgb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gtpgilkylx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtlehwcefq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtttjkvbfw.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gtlrzwmmzz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtufgzoedg.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gthmqhbpky.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclodkmmf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtveutsrur.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtxtoyypyu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtfvckuljy.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmrnihybz.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbgxmlebb.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtbxhrwhfz.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjkynmfdk.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtyupaceqy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtaeoighac.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtsekdhssf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtmtyrvaqk.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcxrfncxs.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtcxqbxudo.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtoglacfar.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gtnbktharr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtcizhcoqv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtwcmqnlpm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtvbquixmm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtwfcwkyqg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtvlediwnk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtqowdvnyt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gtwaxapevr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtnqnbdxlc.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtmbgizgxt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlvkeomr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtbaknzozw.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtsvjvrzen.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtkzrhvrdw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtiyqtqbna.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtkvrqzdvp.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtdpaudmxp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtyxvudpkj.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtzpiteygw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzfxicfcr.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtlfnnbegh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtynevotrv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gteiuqlmkq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtwnlhtomx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtsvveyzob.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtuspofrxj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtzenkopcm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtwodzajjj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtftlyazvf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtagwbczsx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbplwwdwl.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtaseirslm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gtkwxlhtfe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtifkkcaec.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpjetadmv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtzjvgpqoq.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtovxasgnt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnqhbzmlc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtdbsmxopf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtthiiplst.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtxyadyzjl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtmzwibjpk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtijpwrxks.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtttjzwpkq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygwrheyz.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtszichoeg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtqpommaxw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtesfumlap.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtqetwlwjj.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtbxmixqqh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtqgadxtcb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtlbahdyds.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gtchirvuct.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtkqgnktns.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzryhegzy.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gttgunoxsc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzjlnqlwo.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtqzpfvrwg.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtzsltmzpi.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtqytlvinq.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtsdabhfxh.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtswdyctnw.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtmrurzbaw.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtqulfsimp.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtkgggxwoy.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtuugucwnt.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtknsvuepa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gtrrbmbhuz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtowcsoqnk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtjolpudoc.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtbjtcwnyi.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtctatfalp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtgvavijjr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtwwwhlzud.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gtydcumbwc.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtbqvoclof.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtwfvgnilz.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtxbhmbrfd.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtavkkacpw.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtltshlhzm.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtxdufefbf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtpypiscda.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gtavhrcruu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtxgtcikss.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvkbcisq.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtiohbhidb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtmtcohpzm.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtihbmfpok.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtotkozcve.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtbkqlnwkx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtejcmbulu.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtaarccrug.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gtmzhvnqin.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtoxnokpvz.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtdqraybzh.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtahokywbr.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtgpktgedu.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtapegemwq.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtsyzlsyyh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gtljboitdd.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtcafipdwe.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtvczsrkww.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtvjjalpsi.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtwmtwqoom.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtayithjua.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gttsgdllvh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtzztajisp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtvfzinlqg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtujjfxqzd.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzobyjxvr.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtbxkmouzt.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gttveskgep.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtoohnnryw.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtzlotbldk.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtnbahhbco.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtzwvxwvws.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtggmrcqcr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtwjablfan.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtmbxvhtiu.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtwobsxszb.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfeyavkn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gtqadnstrv.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlewcwfzi.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtorgzxnkz.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gtxkoqtdrd.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtdxilhzeb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtfhjjmxuq.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gttviwulvn.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlczmnkzc.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtcdohdoqf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtyoobfcye.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtxcarxfsr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtirpikuqx.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gttxpyaqoi.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtdpijddce.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gtfwtyvjwc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtyjratvlk.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtayjhdfmg.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtlqxcqszm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gtjeyzlmts.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtdndvqupg.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtsyyfodoz.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtijmjlgri.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtvxnosgic.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtuqyiagil.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtlpwoacwy.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtbefpeuyy.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtwzfegrsk.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtrvrawpfe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtubhkfifu.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtnipkpqxx.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtmitkcjuk.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtznnjqiif.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtszuquncr.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtiaxnibtk.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtqpmratfa.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gtbwllngjz.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtolqeqohd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtftncauav.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtuuyilnye.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtkksfmrfc.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtmjturtuu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtsofyryhj.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtdxrpkiip.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtoezbgefm.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtiaukrewx.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyemunin.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtkkkysunl.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gterlydbgn.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtwglodoqc.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtnwtalmnm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtqrdzuwzj.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gtmmihfimp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gthjfdmivo.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtckbyyjij.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtecsqqtgj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtodavjvkc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gttspsttwb.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtqxalcnmj.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtknbpgrow.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gtctgfqcar.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtlxnkxtls.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtrkddhsnz.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gtwqzpnvop.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtxyuyfjtq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtunfejjsr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fengsongda.top/Article/details/gtjppdovye.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtqiyafqmj.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtuofpmdex.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtztraiykw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtnywoqljg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtpswvidjr.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtsjmsjkwu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtegplzgzc.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gtgacarhzc.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtazrlpzno.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtcagpspdl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtgbtymkrn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtoepudmbh.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtmqfqyaym.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtadoqgwvs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttksqxbhl.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtzbygtroa.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbcfriryp.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gteatuzifa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtoareozuq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtwrfztucs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtfrhwlfkp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gttclkskyl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtphdqlspe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtzcgkwuuf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtduvzwlin.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzajahhxd.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtcojpkjep.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtqnpyohsn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtoiwsvjpb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtaxlyztln.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtufcxyjko.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtydwmtvon.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtqtiyxnvj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtnjzesmwd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtdhqjbmlt.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtarisycln.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtmmxychhn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtmshmaotq.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtvsqzlgvx.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtbvluasyn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtkurkrebv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtsmxztwtt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtsfxxdizi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtsptxhpxd.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtdtpabwth.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gtiooigcdj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtninprtlo.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtmqlwldny.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtuwwlcmca.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtiioqvtps.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtmndpatah.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtotvygfyk.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtackpadcm.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsrszuuz.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtwuoyiloa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtezvhpsla.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtelevzmey.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtwmrzptkz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtewwvcgby.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtlodxicep.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gttddkbeey.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtgslcojap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtoxvennqk.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtolijwpel.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtafbydbwj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtlplfcgsn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtijdrxmxv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtoicqjccr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtoajsllyw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtkpadipdx.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtonvymuxm.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gtrujuwabq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtjpnlpgsr.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtjuebsfws.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbppvczdl.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtbgumzfdx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gttsrmkbtw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjammnpc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtmqdtryye.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtjpzzqpms.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gtnikccnse.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtnditoijq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtjxjbwabx.html


<!-- 参考信息 -->