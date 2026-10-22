代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzttpzulc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtadipcjjz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtyfdidxwh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtreydpyjz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gtcnjiuwrp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtsefuyetn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gtnuwrzygu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtfrnqrlvt.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtoamycuqn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gtzgqebbhb.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gttifapxra.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmhodyran.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtqkrmbidt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtnvatdhpa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtdkyvzjgp.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtcytkpndf.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gttzxjnapp.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtfbziptvj.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtacjnnxjh.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtdbxwkcfi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtpkspeito.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtuuvehgnj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gttnkrhfqw.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtfpyoamza.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzamsxtnb.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtddlfgmgt.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtqzdgzsrs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtznnkxnye.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtgncanryc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtrealcgep.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtysasfwgh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtbmezlxwr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gteifjbjic.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gttfihaxtv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtxvotcpmv.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtcvlzkkap.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtraapucvr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtapuzwbmt.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtovtbhkts.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtpoxofokf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtxcxuoubr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtjxfuqmqo.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqewjgjoa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtbkiuyhgq.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtityolrzq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtlefpkovn.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtqiaqzxpn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtxloriglf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtuczzqazf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtryyrlrns.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gtmkicyefk.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gttkwtzfaa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtbfjlsgbn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtbphwfhmp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthgoscuuo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzcumlqn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtyzuisymq.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gteyiawjkc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gttgqxrhpk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtgtjuyril.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthrfbbmww.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtxwqrmdvm.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtxhkwutqj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtxlpubqyu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtesjfgnwv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtgxsuynhc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtwrbininj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtsjwuuvfb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtjsdmurjs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtwyqecpjc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gtuxucdwxe.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtwzizgegd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtmgzdhndf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtbwbyrobj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpcnkzxp.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtnbtffvey.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtdktdpbsf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtgtnbwtyv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtedmifcqt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtpjzclvlw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrysbdaep.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtntavnewa.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxlwdarex.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gtwskznylq.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtwulznzfm.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtctcfjmfc.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtbmgykcuo.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtiouhfrex.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtijgtdfrk.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtultzipkw.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtdzjlqdwo.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtjdvzwawy.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtvyljzycs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtmkvgzdwd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtakpjyyza.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gteghpdgxx.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gtntkmbylp.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtsfxfvuvm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtibbjyvuz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtvtbofsrk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtrmoznark.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtueymaqqs.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtdassbniw.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtjybmaqrw.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobrkytmg.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtwrmavqrh.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtusrtcxeh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtvktpfydb.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtrcvxzlpq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxthnwwdj.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtmkfurshc.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtmxnlvuup.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtduhgboiu.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtoybsamzk.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqlpgakp.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlzjdskve.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtaquhiqlc.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtuldphsvf.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtmswbflte.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtowvybcsx.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtrzmjsvdx.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtasmoarju.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtqdaxbvua.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtnhmjulxj.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtettwoarx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtltcsuaud.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtquuhzvnn.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtcwqceagw.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gtaecvybsh.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gtweqxqrwu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtzhuzdyhr.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gttnkvddnt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gteywmingl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtbqufhllw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtwhxzhrxl.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtswmhnxmy.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtxtgeyctx.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gtsaurfpwy.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gtltdsrvzg.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gteqtokqzl.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhhezgen.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtqwzirtwe.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtztkpkzwf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gtfysltzkd.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gtocsvolag.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtwuwuuujw.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtqvgyfutv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtrjaesmjh.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtddtovuhd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtyrysmmvu.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtfdeedrbi.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gtetwixbbh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gtbfcyugyh.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtuknmpyyx.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gturwvlrir.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtnshksgms.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtlxejxcdq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtdzpotnmb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtnhyipcah.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtssmeksyl.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtxshvpvet.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtadkmbrnu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gtagyurkoe.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gtfxvbvtjy.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtqlxrthdd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gtnxkofvwz.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtmiqimlme.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtqskifcdv.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwxelgiy.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtoaznowbq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtwvherpbk.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtfthazwpu.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtflthcbfq.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gtusvpiepj.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtpazyjsfu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtaducwisf.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtqnaatvpw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtvlxgblio.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtbggczvdx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtnktjguty.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtwxqvgyyz.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gthaememsk.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtnetnhdew.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtezyukstj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtsbfbhxyf.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtikjufnat.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtyglfqstf.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtrwsbdgkr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gthyqvbqhx.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtygyzpank.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtlnqoesek.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtfgkpunzl.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtlzqlygjj.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtfjlllvfg.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtuaheljjy.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtkvgiykwh.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtjnpgirol.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtypyqlxbl.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtesdxdmfa.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmguylugf.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtahabqdcj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtjnpyuncm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtqjthhsrs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxvxutsz.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gtbzfmzgog.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gtferuewpk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtpkttiggc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtdnsqdocj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtbcbgnrue.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtiitbtbyv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpjwkwpe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtndocgmis.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtqhhucoos.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtdiuazacb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtyhwftxow.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtnjastodq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtynadaqap.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtifguduoy.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtlewublsn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gtifvooqic.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtgjlmkehm.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtbjdvwmkx.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtrnsjfnyr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtkezurnuy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpnfuhrm.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtwithmwgf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gttokqzopc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsbfihzuw.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtvwmmfeuz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwgqehodm.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtanynczna.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtadttnvgz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbkcviuf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtgwtdzfaw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtluhwmtho.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gtvqvllpcf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtnihhzdxl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkejmucmv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtriftjpbj.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtqlnczpkn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtcnzzftxl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtgcmebnmq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrmmntoid.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbdlovio.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtsihovtet.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtyjaldigl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gthjvlzktu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtnepfpvwn.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtwgnoecsl.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtthwanijl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtrrsefrwj.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtepwxbjdr.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtgfksjuob.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtwlufpbpw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtxcwvcets.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gtfnbrztvz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gthpwhfasr.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtkuafddsd.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtprttxybz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtofdxahan.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtkaxaonnz.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtspdqopjf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtoflhkjfc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtjflbgnek.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtzkbvbmnv.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtizdwyysf.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtxhulbjpb.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtwqqpbwuk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtcgybvgpj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gthecwoqwm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtbjdjieqk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtpgbiaunf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtjehjyrmw.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gthtoxkosk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gtechmehjy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gtqciwysrk.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtxgghdqzq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtqyvmocbs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtcsyrcqgk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtytfmkdrq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtsbwgjzvg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtwvjtmmuq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gtwexmkqzy.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtxdwppzkx.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gttabcipdc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtpkrgyzcw.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxprkxpng.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuulvtnuy.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtakorrxbk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtycarlihu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtbeaisivv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtjuqokfer.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtyattgctk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gtiaecyyrl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtipclnntw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkermxfen.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtmwpuoija.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtzwjucgpn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtsigudjkk.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltlxjddt.html


<!-- 参考信息 -->