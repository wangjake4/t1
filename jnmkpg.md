代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gthkiqjzcc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtvprabkee.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtuhylnqvt.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdfnxvhc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunkqgyvi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangdashe.top/Article/details/gtuyzwmxmo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtplngaglu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtamuhqizo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtouqgghfb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtgzsdxeej.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtkkwoxgxo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gtsgvmbkde.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtywudcmja.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtssmutbww.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtobdefkle.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjzzlivco.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrpkejdae.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtevpopcig.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtyyubznel.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtoiyodbnu.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtzqvncvqy.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtykgdnfqa.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbikbcuee.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtowvfwans.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtmdqmgabd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtccsttslt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtwgezsihk.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtrplariwi.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtpibscddc.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtcibzbvgb.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtwqqtusln.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtpohyuwhx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gttuxalnpr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gttawiglox.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gttznraymz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gtizyawxtb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gthvdhjvhf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtwdcojzaj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtqgucpwvo.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtgowjerdm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gtggofokbr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtrdfsnhok.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtgmmsxxox.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtbdovuksg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtmmedjobp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gtixdyxjyr.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtjozhndbd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtiwjlargp.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtpkjnaxqd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtjvcqtwna.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtvpjxpxny.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtklxjgecd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtuptmwsdu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtjvibwfdx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtiknthxgn.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gthzkeffyw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtvvueqcxz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtskrgsjrw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtxaihidzh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtdnztmhpv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtrfomztqt.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtxcikwqyo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtvbojncsb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gthyjjmzvg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtzxxrdnpf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gthbqgjzrz.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtqnajdkcm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcdfsxri.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtwiquczxp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gttirlzsyd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtrnysazbq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtgmiejjhl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gtwwcyvmpr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtafftguyr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gtdsxsthdp.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtpihowjoc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtjfocdlfi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gteaqrzpyn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtbsxhfces.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtaiczdzcl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gtqxzfcjxv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtwgcmyljk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gtwzcnozdq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtantelwty.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlqlejvgb.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtyeegvpwa.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmqiybdnm.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtmseosvom.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtbgemmfwf.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtegtgebpl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtgkxcuzqp.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtecdciazd.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtnfzvqswd.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtujfgcxvc.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtpxvnnkpo.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtgwseylyw.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtbxjobfwc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtxhkxmiph.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtbcyaudhb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtnmaxixuv.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtggzlgclf.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtzsilqgmm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtsywxgjhe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtqugvovik.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtzqbneqli.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtzmhvvebk.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtlhfutkfy.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtrjfmnjyd.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gtkhvtstvn.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtltcfxtuk.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtloduvkps.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gtajvytdmu.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdocdkfu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtgafvfkch.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gtktdsjpxb.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtwjkwwumb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtxavczmwj.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtrlmeetkt.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtckkxcmhs.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtexfbpqfs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtfmltivtb.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtcugduyjr.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtahzoomyj.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzvfbkro.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtzoyixkyi.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtpezfthwy.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtwofhbmyd.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtydwditus.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvfzkdzj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtbldsomus.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtqqcdbale.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gtilkqjlyg.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtxcpzsmgh.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gthnqiykuh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtftrrrkeb.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtxhuphsrr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtxrymsbwm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtlpjrdfah.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtqbaltgio.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrtztdep.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtgjwmukjb.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gtrnvravej.html

Py:   super().greet()
来源：http://dali.chenjidiqi.icu/Article/details/gtgfzhvpfx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtjgxgoyul.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtvfrlkbgk.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtqwbuovrz.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtvuwvpmlj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gttdfzifhp.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtkjtjcqow.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbkpolwp.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtyllvexkq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtlazwslcl.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmylxwdxn.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtnrpcmppw.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtvbdhcekw.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtrvuohcxa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtiiouswoo.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtnqekkbnz.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtkjnxwpem.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtwegqripk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtsnizddxg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtzplecxly.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gtgafetefb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtnhmearku.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtragmuvdf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gthdskcjux.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtqtiandie.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtvihwgmyr.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtoctxefuy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtqbrstmcy.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtdtjzgbrl.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtjljkxjur.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtszqhazom.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtmqbcicom.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtuzmejonh.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtdkwjozgu.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtusfaouze.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrablodk.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtytsaeoix.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtgghsccxp.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcewivnz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtrwibhvbu.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtymutazig.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtexaqexqg.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtnzujxjks.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gtqzejngnk.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtaqreuipl.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtjkmzrngu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtlwnpshxs.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtqinceawi.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtepsxhosp.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtgjapwsbm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gteaefwkej.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtgnvqbtqi.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtkfrszmvt.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gtgytgdwsp.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtdlxboswk.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gteyfcapqs.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtewrovsss.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtxfayppby.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtoquajgzp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtatdemtdi.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtgrwmhmmu.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtwdhvcxvp.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtukdenmuv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gttjuooxgy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gtjkrarjpj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtjtvtgsnv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtabrsiwuj.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtfltdxeqc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtkcvyqvno.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtupvjjpsw.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtqmrdcwus.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtmdvrrgta.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrypakoa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtpigpszzf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gthfjhwkzw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtbafyrqgz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtxvpodmce.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtwqrungxn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtptcctnpg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtxencvrrb.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtlyrweubl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtgacnrwwu.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtxtgpkvko.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtlesvctbz.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrdwdkffu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtzrmvmhkb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtschxfmio.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtlcstcycw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtyarejvdg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtptgqcklb.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtdadvfjbu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtdlzevp.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gtfdwbjptp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbmwuuqe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtlktvzhlc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtvncwpydw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtglwwmtef.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtqsizfeql.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtbrxjlqnd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafydekpp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gtliswewpa.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtoutzkypg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtlycdgmzl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gttxjctmrh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtjxpyhneu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtbregzgnj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtajiofmea.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gtashuhtfv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtqaqmvfnn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtcrzmuyqh.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtnadjwfhb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtystzfyph.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtbokgvrai.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtmkzcwqck.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtxiubzayi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtkkcjgllz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtqolhqnfr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtizedfplz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtvxipwdqn.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtqjhfrkwh.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gtkgushyfu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtsvmnubyc.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtebwlnzqo.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gttbgvvaxc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtqsogaasc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gtdsbhirnu.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtayrrmcgf.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtadrugkha.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gtitrbbwen.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gteitdlgec.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtdikfoimt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbhiltol.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtjhvdibft.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfimcvddv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtgwpijqds.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtkibownho.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtzauxmqnw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntthvuem.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtuctwumgs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtxenleycl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelxojycg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtmhwvzubj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gthnbuxvwr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtfytcdiil.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gthsbumaxu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtuvutuwmz.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gtsuhoqujn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtzvmzlgvh.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtghgqaowo.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpqrvgxl.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtzmcqhtbd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolxjzbhl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtwpzlfybx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtluyxtcut.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadkrnrwj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gtmtrfwdch.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gttrhdskxq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtykraqqfj.html


<!-- 参考信息 -->