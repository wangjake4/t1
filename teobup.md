代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtsqjpaawj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtrmvtyupe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtuloweeit.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtbcbveczx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtzjzzheat.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtokikjtyr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gthrxuxzyp.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtmsurvitf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgbycqnh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtqaldrwee.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtopxvnitf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtapnjlhir.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtxiwdkvrf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtreahoziq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtuoroyzxi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkupxlku.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtewtgfevp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtpywkkngr.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gttgcdzhtv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtombrhkzt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrnpyjth.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfpyyaho.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gtsgdneevv.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gttumedqpx.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtfgdsannz.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gtywxbyqqh.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzeeegbay.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtsprujlwj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtopikazwd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtaqkfcvkh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gttzqrpkwa.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjbaesxnr.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtmfwrruvg.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtfujqkbmd.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gteycfntbz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtoeffswek.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gtbhamknoz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvzqmnif.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrtkacwd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtckyubtcl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtwayenyhq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtvusrudkr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtnaqesonj.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gttgqiuwln.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gtpcdzlyts.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtdascvxts.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtjyycnqyw.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtngpsgiwj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgdhyhst.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gtjsxuwirb.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfzqyhpo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtxqqguwvk.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtfgtrcpbi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrybcowuy.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gthptexihf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrfgpgpz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmchmtece.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtoakuxzhl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrndqdyo.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbvpfojpz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtmvjorvlp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhsttjay.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtvjmjworj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtsucpqvgr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqqvweduo.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gthhrmjdka.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtjxcrhskn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzprenuyl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtssmjivhy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfcotftn.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrkqhbrq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpomntjak.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmqcdrtg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gttvfogwfm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtteanfrbn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtushwxgfz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtmmasmnwm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtqfbebdkg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gttnpkbbat.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtgqmyssay.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtqvvjnyft.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtolcbgewu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtvjssrnhs.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtwdsderxd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtzzwjjkfh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gteawezpys.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gttnfaiety.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtaekulqnx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtishukzxt.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gtnhqsysrj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnyqkyhdm.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gtgnwucjjd.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtdacqhxvt.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtlqohpnrk.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtopbxgljm.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtsdoiwjuu.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtspbcmsjs.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtgcdzgpag.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtxphgyjob.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtpkzfnrtn.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gtuujgymeq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtdvvbwxtn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gttcdntwmm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtaoseuggl.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtecwzgnfn.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtaobmozbb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtxqkamlhb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtkrvgnixn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtyfwxnolf.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtyinyuhvp.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtxkhzkaek.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtwwhwmnhk.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtvuwnqsew.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gtiwsycfiv.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gtoltzaawl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtdorvijts.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gtystsebco.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtgeldysea.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtdseizivt.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtuseeqbwr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtohdbqzcx.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gthbpgtpwi.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtjtshahaq.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrgkutusp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtwcwqdfle.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtgbroltql.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtvmtmubwy.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtybrobmlp.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtnnmdginn.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtmonfmeum.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyluvjgj.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtgpoxsahg.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtowsjogol.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtyjmvbfhc.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtgexxerto.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtbqajmdbj.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtuyvkoldh.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gteucrwbpy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtfemwvndi.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtwfvgxmvx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtrrjfrdro.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtmumuhovp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gthalmgrjf.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtnsynrdnv.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtrevrzxbs.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtnshhfirs.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjsfkzqo.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtqdvvezdc.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtisdmwfre.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtmlhsochq.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtwexxfciu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtiwfxncls.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaemqqkok.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtogwkyrvn.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtljisiktc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtrnjytmyx.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtjajpjzax.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtsehgiapr.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtzpfzkbkk.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtzqhvtcgt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtxylzwuts.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gtvmxknnti.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gttdeypafe.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgomwutzo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbufqgwk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtonndkssv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gtkevynvrp.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtvjoetesl.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtkiuekywe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtjyklpedc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtfbkybduo.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtfwtpkwiq.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtmasattvw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gtwsytuhkv.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqubcryee.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtpryarpoi.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtkcexldwt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtrdzlelqx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtmaqysxej.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtkoxwqmhf.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gteqkhlafj.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtkortxjej.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtmbhdxwww.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtklxrpplv.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdmknoogq.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrnmgtvp.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtvrahzekx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtsovlntru.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtfhpybqhi.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtagolgeyf.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtihpinzhp.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtimkaikvh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvagxwwbo.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtlgsbcucc.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtocdeacos.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtmmktqoxz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyedyonv.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gttpenzwqf.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqzoqisz.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gtyfemcnje.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gtwodjqntt.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtgfdxzuld.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtuwgehebl.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gteldtndqn.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtqkqdesyb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gtzaigylgz.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gthjibzcpx.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtqiayfwuh.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtkfylxdzx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtyjlvsdwe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gterdwgvhe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtzpvgjewc.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtqrsbspbp.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtujinlrma.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtbscycdje.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gththfhajk.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtpntnxliz.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtvuuohxve.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtnvoshwhg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gtcvjszasg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtfwfpknob.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtlgjgwlyr.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtcncblyaf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtukentoya.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gtizbdlbbg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtltiqeued.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtzofavnsv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gthzbpmwni.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtafdgurxg.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtmhyvpmry.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbqftjdk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtecpssqpa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtwuboaags.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtvibhvkxe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtaollxyih.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkbncleal.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtirrmprcn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttmsikffz.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtggznvrip.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gtwzvuzgmc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtzokxwtnt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtgqbdzrcq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtlzxclick.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gttwivmbgs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtsbydzmsy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtqsyiltnq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gtylhuxbsf.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtkjizihbe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtfyohgdve.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtgxgxhlou.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtldtceemr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtefftawks.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtabvkbbgp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtyokfpsyl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtuarexhor.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtwicrgreq.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gtqcfsujcy.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtnmhmtaih.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtlhpsezqt.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyudvsfvc.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtarlnyklg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtdqdpvqzm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtbhmthnug.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtnwzombpp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtvrmkbnrt.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtyquxprvl.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtsujceojn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtizulwpaw.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtywwcpull.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtunhqdbvz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtmyxmulod.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtgoutanqs.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gthmohjskq.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtstzbuydo.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtjxoohlcr.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtnlzumedb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtkffovkjn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnkspsob.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqgsflnpx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gthzzzsove.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtvjsxyaud.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtdaqtmhul.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgawlswsn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtrzammbww.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtvxdnvwpz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtwnymvmlg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gthhzrczlb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtorkkqvyg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtxpivqeao.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gtsfksbzle.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtxooefkmk.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtbssgrnch.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtuoivphdl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtkzzdzdxk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtnyqjavki.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gttuvhxznp.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtwoddydrc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtumicuitz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtonuasuux.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtkklpstzd.html


<!-- 参考信息 -->