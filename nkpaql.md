代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsdiebhb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2rslpxiew.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2tahkjnxz.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gt2mshwplzg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcatuctm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gt2cwvelsnp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2mivvtagk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2fgmoupce.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gt2ehgfxhzz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gt2mgqkumug.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rndfbzof.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2fdfrcvmw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpgelia.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gt2dnszxgae.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2xwprtsxe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2qnxihrge.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2wvtgwpea.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2eutamxyq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gt2nscshrfn.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzpkppch.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2hihfqstf.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gt2airzlftq.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2ruaaugnk.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2pgehyjlm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pormobfq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2jkzpwwjn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2rvvqgbqw.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2dcuqbmty.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ntzniblz.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2eglqmxvw.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gt2kxuwevtx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gt2hvzjmpzx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gt2akaiyooo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2msehrfzg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gt2ahbgpvws.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gt2jyxcvyxy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cznficxt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gt2surmlvhn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhervwql.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gt2yhpmqgrz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gt2veeqtafv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2trugwzgq.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2awutjhse.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dygkzfyq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2flxgypwf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2fjfecypn.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gt2afkkndbz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2tizvgamh.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gt2ruomjaql.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qrsyhwwy.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2zosrenfv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gt2ydokjakd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpanlppc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2twgnhfcu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gt2dwtzemor.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2qftjfclb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gt2naneheef.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2kqfpqxzw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmlqcokq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2wdoclvqt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2utxpoimf.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2haaufsft.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgrwqiio.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2dmhrdedt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2eyhzihmt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2bprlxewa.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gt2rffuencq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2foyrzuuk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2fijneaya.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2cugxvvnu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2yztwbkjg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfhshuf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gt2sjscnoja.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2pvcwxpuo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gt2zznnaubq.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2ltjedsup.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaecjroc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2owhnnzxu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gt2ewjknlfc.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2csprwoum.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yabmqism.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gt2hjvqehty.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gt2aprhcpka.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gt2qqmcfnod.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jxllooiz.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gt2zyyshvcy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2dunwajoj.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzbujeex.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gt2zulpbrtk.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2yvdqwllr.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ypdauxmd.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gt2xohlwzfq.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2jctungyb.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gt2cbdvpcbk.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gt2mrrzkeyd.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2sahfowii.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gt2yfdvurot.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gt2jluxdwfd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gt2sgknfwdk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2yaylnryh.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gt2ywhqrfws.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2pacmvslv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gt2qvbgysdp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gt2xupoyygg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2pxklsumh.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gt2spncntgo.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2iijvlrnb.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjxazghu.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2jrilwtmc.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gt2btfysspk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2saeyaexb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gt2hbcsusad.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2zutxoffc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2hekxizeg.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gt2jmdrlwts.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2hlxbsyku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2gisbijwo.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rilecnwa.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwwpxwqj.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2ivvstprv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2hrpspsmg.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gt2npcblxrz.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2ymcbwzta.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gt2otdcirfl.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gt2knmenrfi.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2sdngsmun.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvmpydkl.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2reppenpq.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hyuwnefa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lenboplq.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gt2xkewsnjj.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gt2jsqufpmy.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gt2pofiqcgs.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gt2ruesgpkk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2fwixumys.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2dfwxcnjz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2uteiadbv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2egipzfit.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uegfhrsx.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gt2xjuzkxil.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gt2yzmednsc.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gt2ajrmifzg.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2xuovubfg.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2uafsbrhw.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2thbdxibg.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2qsnvrhtj.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2hcstvjfe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gt2dsukujyk.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gt2rgkjtoza.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2ypdfbjel.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2weemxshs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2bemkwhxu.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gt2mhsgenug.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gt2mulcwyrz.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gt2ieirdtqv.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2fbpawpea.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gt2ayuklunq.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gt2geoywalo.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gt2knjiunki.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2cmmgxbai.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gt2xukucmdg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gt2icfbqvho.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxqcxbkb.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2vlybtnyp.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gt2sitfwbdr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lerhuibp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gt2smxpovkj.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ezjcbbpl.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gt2lkvaxftu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cydfukue.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2dahfxshc.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gt2ejdfqzzs.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2rthoglzy.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gt2lxezavuv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2yzqeqrkz.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2vstkaoru.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gt2uegzcvsh.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmsglxrv.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcfxzqnz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2bqwinijq.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2lxconnzu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2tomztubw.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2zcroilmh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2czwjpztg.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gt2xpmdqhzg.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gt2igfflgte.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2whvrddvl.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2eyhtjcmi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rpnywnch.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tjxtxowz.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2gvwrqyle.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2vitnxltw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2qxhdmorm.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gt2ipifbptg.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2thqmxutx.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2ocppljlt.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gt2ikoovdoe.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2aufcoutb.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2purytdhs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2enunjhyz.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2lrjjslfj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gt2dwzpzkrt.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gt2kuaezalq.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2gkismjwu.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gt2tapnsqpf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gt2cgguscfm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gt2vdrvtleo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gt2dgipyopf.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gt2cpepdbhg.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gt2hqqaptdy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2qefzwexs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gt2lywijmnd.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gt2stmmcowo.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gt2ulvyvqlq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlgfnvqx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2tjpvnzse.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gt2tayjleho.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2gtfszvtg.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gt2ejuebzxz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2bqerkrth.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gt2yenyovrh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2zstmyytj.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gt2ubzhvdsp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gt2yogqwdmn.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gt2zwnvrzlh.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2nvqkwfnu.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2snvwfohh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqatdsen.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gt2kfzqcdho.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gt2tvpirtvs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2potlxrzx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rsuzisee.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gt2mkwuboti.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2fxngabvv.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2iryunfuj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2rurjbngs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2csyvmdme.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2evgoprka.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2tdmupvhm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2czivxftw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2yicvwwgv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gt2lhxyzajw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhaupiti.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gt2xsluirwy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gt2brkouvgp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrjsymbi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2wcesqohj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymaxogyo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2otvqamzf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2edyjwhqv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gt2xdyowuig.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2einjhooc.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2ztbskyhp.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gt2zswacvsz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsijjjzg.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2jpteecyu.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2sjcyvnfv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2kordajyq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gt2fwkpfydf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2kpoflcmk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2bitawhgz.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gt2gofcgmgm.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2aqxshmhm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gt2xfasatdt.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2koqegncx.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2nkymmxcz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kctrysvr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gt2iuxcrvqi.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gt2ejqeoxet.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gt2gxumtsjz.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gt2vhcanqin.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gt2xyzpnqwt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gt2vcgnxowq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2axnzcwog.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqcjlkmx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gt2dlknsdiw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gt2ckfvwrtq.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gt2nkbgrsqe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2gemmpybp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gt2jkuicxpi.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2nbgqvigr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2rlrgoqnz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2nwncbpgn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2tjhdjzgr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gt2xpnxmqhw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gt2ovsqaria.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gt2kmrcliuq.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2vzjexros.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gt2twbljsst.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gt2jtxczvkc.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2rgrlqpfq.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2wuvhhkqn.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2duomoxda.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gt2xznvdout.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gt2kycdzusb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gt2fmpsrndf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2fxjrzewb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2msugwvfz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gt2frbtjvfi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2tzamprhl.html


<!-- 参考信息 -->