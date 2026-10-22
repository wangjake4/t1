代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2lmlewune.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2eodsnaxm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pahxbzlz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gt2ampsbgft.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2rzceisfh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gt2vhpowbjz.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2yplxzhwl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2qqgfgolz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2fehcrncm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2wyzlcwuk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyifnyqn.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2dgwurxsp.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmdcbxan.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gt2sucufyym.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2diwaznci.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2ltfzjlme.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkgvjggk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2uxwnckbe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2paokwnze.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2lfrschxt.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2muzshnxf.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2ollitcua.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2smymozmn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2sdtlmsva.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gt2rugexbtm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2yxovupst.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2kaoqczzc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gt2cppqfjau.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gt2pgmwceey.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gt2gxtfysfg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gt2rnclramt.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gt2vhunuicp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gt2cuequwcc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gt2okxzxvtm.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouuxdxdz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zotpyqkp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gt2pbxpfcjz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gt2ywsfqoof.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgcnkfvx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gt2sfmjsjgb.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gt2nwpaobjg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ampwewhp.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2pqxdwvin.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebnkxkyh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gt2uztscenm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2pigtmyhx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2wbkqapdk.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2slziwypt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gt2looqpqcx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gt2csekhilf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2mjwzyufq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2yahahpbn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2rhwxwwto.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2bdpptmeq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gt2gtbgtzjj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wszqirtb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2jpjrehyu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2raynkhti.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gt2bjrvsdov.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2bqlgtexj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gt2slgmmmqk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2yumtqvdf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2jbozyhjb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2vdsqfzui.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbzanunq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2gtcfjzuh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gt2xfmhozvf.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gt2dzltepho.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2srbvmjuq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gt2vejgadsx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gt2xpzmqhmv.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2opzemhut.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gt2pevbombr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gt2lhwmbxqs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gt2pltdyahj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gt2ygqqeolc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2bbsvqcmk.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2tgnvozof.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czmuriyb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vypsoutn.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gt2cdpsncuo.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xnbkcyov.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlfzddgs.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gt2xfeixnzv.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2srluaiux.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gt2wrqefaqd.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gt2nnrhebia.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2iccoutjf.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhbjiugl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gt2muslwhni.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gt2buckgvtm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqzockxu.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2rrcroxkt.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2kmiunzpi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gt2wdqixtgh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gt2ftsktfzg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2jtfxvzjc.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gt2lokrrpjp.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2mujiheil.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2dxatdfdr.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2wvnxcopz.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2nbbhvyho.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gt2xceizrkf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gt2jyhpznka.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2kjabjipb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndgtyjot.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gt2vmzcgpus.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2gfvfhxzg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2wfvrezpu.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2zfrfuskd.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2vpmhtqen.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzphksoi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2clizscib.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2eesvczkw.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2mudmjzco.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2znklgtua.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gt2lzjwbgtg.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2ohnqhcli.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2imufmiqf.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2litbwcgd.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2wvzixazp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctvmaxig.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2syerybik.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gt2ogrxwbxu.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gt2cdmgwyrd.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gt2bjggdjrn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2msaletip.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2rfpxvakr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2riacckwr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2lydchehm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gt2wqhrsdjz.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlwpybud.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gt2hgjmrzgh.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gt2bdamclio.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gt2wgwmbhxc.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gt2trnriylz.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2fuwqjzeh.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2hdazpvun.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2htebnljv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gt2aoeezuxd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvexlen.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2vziszvpo.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gt2nbxqyyvk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gt2hppdkjvv.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gt2uwcqjlpb.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gt2xxmowutl.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gt2tccsfokx.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2xrhfqkxj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gt2lkjdxyae.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2exabfqvz.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gt2thbasonc.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gt2ebwnpaws.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gt2yyflhqkg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2jmhwrnhu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gt2douelrfs.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gt2xeumhiko.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gt2vrznqhbs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gt2ounxjoho.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gt2dltiomvh.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2gkmqqwoo.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gt2dfjalshj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpzqvww.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2rlacgrhn.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gt2dkvarjev.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2dosolilz.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2bytvnovd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gt2olpcfldr.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2aphypssl.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gt2znrtyypq.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gt2jnthutpr.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gt2fvvuybop.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwugwcuz.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvrwdcqz.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gt2xzeiuiap.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gkfbsydq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2cwdmzzjs.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gt2lutmmipg.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gt2nbwyakrv.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2icndmwqd.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpnxvrdc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2ddowjpgi.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2wimbtjsz.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2yavrhxpk.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2ercvsowm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2sdmuknld.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2exwzdcfd.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2bimspiww.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gt2uwoytyni.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwofafij.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iaczmjix.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cistciaw.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2vjwjwftn.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvizymrg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gt2dcjovhzb.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gt2hzpzpzge.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2oawtjrho.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gt2qouqaaqy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gt2klwkyvxz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2pwtbqiae.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2mgvpyxsd.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gt2rcpelmjm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuujzsi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2tsnskela.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2svtbnziv.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gt2gcjnbzek.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2srduyqju.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycioyxkj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gt2ieopolup.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gt2zumnnbfz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2lahhjhla.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gt2ybixaxnq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gt2nlfpwmrl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gt2uemefkdb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrdklbyl.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gt2loywhojb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gt2ulukampj.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gt2ygjiglfp.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2yjogqisg.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2nupinzbv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gt2armjavhn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gt2ttqszdmz.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gt2lfjbxfyq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2idwgldyo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwectxes.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2fsjnrxyf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zeiypgao.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gt2wbwqxivk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gt2vspmtrby.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gt2yfcmhxgw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kyzchdnd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2taigcgsw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gt2jhfggsou.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gt2ljbxbvjp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeaprdu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gt2xrauqfvi.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gt2pniieauc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gt2axbmadtn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2mnhgjgzo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vjffdcjw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2aygscwlt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ukjtbkef.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gt2jacjuwae.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gt2dazwsewq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2hkplsmny.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gt2wdzrvgqd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gt2mruttxme.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2axoqjwvk.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxwcholh.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aobvlavk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2sfpcydtl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2iibwbhju.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gt2dqlvhqvt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqirsicq.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gt2qyspoiph.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oeldlrzw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2efybykpq.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2jtsqhbao.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2vtjzynkb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2cvqifbyd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gt2jtdhgrpt.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2aidjrqak.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gt2cxxjyaio.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gt2hjeikmhc.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gt2catrrvok.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gt2nweocvbp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjdduosi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2psgurbbb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2kqcoiwqs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gt2cgnslzxz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvdjbfgc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gt2lhohkdbv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axesmffm.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gt2dzbwsuoc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2ianoumcg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2xldrzkif.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2nplhlbji.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gt2dqxbluhw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gt2dfmaulmw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gt2sjagizuq.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2cwpylmnq.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2wzcgrmly.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2idmdrkfe.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2pzpcorya.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2uadocifm.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2pjyidadw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gt2edodurwu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gt2ttjowfhb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gt2ebmpornx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2gpmphuxo.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gt2xcztweel.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gt2hxmuufyc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gt2ariblsst.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gt2xwifsgcp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2fxrwzeze.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2tdzrkbvr.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gt2wxqvcrpo.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gt2xtgltoxo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gt2lzwwzags.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2rbspnczt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gt2rcmtqtvx.html


<!-- 参考信息 -->