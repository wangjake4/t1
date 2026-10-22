代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gt2tqeqyzlb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gt2tqgiuooh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gt2xhwwnuxb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2upcnqvvj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gt2oszlirpi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gt2rcsuwasa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2dioaenga.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gt2ynfhxmsf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gt2ccnadadp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gt2gwerdotm.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2vuzzzbze.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qytvywvr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgkdmcpq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2clkssbyc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gt2wawiekdd.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2upnqzltl.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2edbgmrnf.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gt2dzjqnoas.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncdvtkjm.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2grbanloi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2pcxtgucv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2bowulbis.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2bofohlbb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ywfwknfz.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2hcpanbot.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2dcflzfpj.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gt2tevsxjye.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2rfrxhypw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2ptbookoy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2uziveggf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aischqxd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gt2yahhzesb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gt2cwsbczkz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulllfvna.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gt2jqnaujiv.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gt2qnuctjsg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gt2kvkfbdyu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gt2sflvwlwd.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzsuajbl.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2hbgkuztg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2sizapqln.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2towtshks.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2mtsfvvij.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2fuvcwqcv.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2szrrjbtj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2xwfbcmih.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2djspkhax.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2umgjrcrx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2khjcfnlu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2tqfghmso.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gt2wtwcaukl.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvitwnck.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gt2igzzsazw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gt2ekqslzvy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2fjemjrho.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2rjugwtim.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2nnkzpnfw.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ktrysiac.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gt2yzotpaoc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2wtukrakp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcaeoaci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncikhwae.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gt2jfmwzlvx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2oiuatoit.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmuywwcn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2wzddmbys.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2olbhhkta.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2hknkydqv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gt2rqcmrzlg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2nlzmxfld.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gt2wlqrzqpl.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gt2fhthacav.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzckcawr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gt2itdbgilr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gt2tmrjidny.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gt2pybbpqdh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gt2cneudynx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gt2wcesxfes.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gt2smmoksvy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gt2iitvcmqz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ryovkxyl.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gt2qfdoakea.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fyyagtwo.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivwswfia.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gt2ynnsyprp.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gt2vngsoisx.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2ikzbrhya.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lypogmmx.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gt2pnzcjtrw.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gt2ckmypbnz.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvfvfkku.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2bdnwwkld.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2inkmexwo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gt2vxfaxfmg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gt2pksqojel.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2zbihetul.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gt2mwkigxrk.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2eswmpohi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2hrpjqvop.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gt2syfzkhwt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gtvpjomw.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2snkusbpt.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2weuidvkn.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2fwfjotln.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gt2bbljlqmb.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gt2zrwafwyq.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gt2iywxrdzw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2xcxsmcou.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2zonqgogr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gt2uzsitlyg.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gt2dglxsrzq.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2jupbmaoa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2nhqmroay.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2uvipjwqh.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2kynydbvq.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2smkpnrsm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2eeptrpad.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2cypvmkro.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2rjoaxkfo.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gt2qcymcjjl.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gt2zfbuseve.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2oehadhas.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2wvfxhbur.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2sbvuhsly.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2fctoyxel.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gt2wayucudv.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gt2xgibivyj.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2frggusrp.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gt2stryqkio.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gt2nkurldsu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2bkmkvbwa.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2vxuwlkoi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2bycuqymq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2fuqomgmf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2yzvaqifx.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvwfayyj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2fijnjlxl.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2pntkrmuq.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2qgwztful.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2dnzaromi.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2cmpdwshl.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2svjolcch.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2nuqrbdpi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gt2fgwxzxec.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gt2iyhakqsf.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2yrmangvn.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gt2nengosoo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gt2vyeyixbl.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcgmovvw.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gt2nnvisoxe.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gt2ofrlyskl.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2grvocnpv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gt2tktilirq.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gt2ijikozyl.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gt2avfatcux.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gt2elotyxst.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gt2cuemkfxr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhjpqgub.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gt2uygcusrl.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gt2rsoegnew.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gt2zgvflxnk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuimufhl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gt2hlvwnkpd.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gt2loiiytyx.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdmqrmto.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gt2uljfmfxn.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2wfuzgoso.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gt2lswvfgqb.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2smjrijzp.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gt2teskmfta.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gt2aydqdkmr.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znexvxlc.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gt2pxohlrso.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2ddrswbli.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2scaitmnk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2woyhypmb.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2adqwgcqx.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gt2xeaomhkz.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2linlgelg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2wbscmabd.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gt2cpbnryxy.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2phskdrln.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2cccnvkrb.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gt2dlzlxcep.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ckigzrbn.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylxvsiri.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2udhesaok.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2upvygkce.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2qnfwouvu.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2vzbdrusg.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2vhoaqcwd.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gt2vangotpd.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gt2wgtgmzbx.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2zfomixxj.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2sdekwbst.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2jvdcfled.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2manhijao.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2sxclmavj.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gt2trvzroab.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gt2ftombxvw.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tukdgsio.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gt2zgvctzxd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gt2ditsybpu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gt2ukauqlgx.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gt2iponcfpt.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gt2ivpgtrxf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gt2cdwiudxd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gt2kxahnlcb.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnndfzgn.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2pxbivktj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gt2uosrbdos.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gt2qseobadm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gt2iqnufdhl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2cfztvifx.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gt2sbfiveha.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2sehgtxvr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gt2nwxvacvj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2ijdzfnqc.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2cuoeakaf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gt2agwjsxfv.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gt2bnzpulgw.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2cqihbjqd.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ijkkoqie.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gt2mcikicov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2tpxzhjdp.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2mmqulcxg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qodyxhku.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2cjeedanj.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2hkckgrgo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2aqzrazje.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnjsgfjg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gt2wugcfacf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gt2tkpohzmr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2phdrrcsn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xsjfzpxt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2qjuyhrih.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gt2ekptmoyr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2athmmzas.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gt2cmhoplwo.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gt2mtkqvkps.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gt2saqaiwrm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2tejdetdk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2gqnfksxl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2hawbkfqc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2dpeupqzn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwfwozon.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gt2qmltcfzk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrkpylza.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gt2lakfvqis.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txomiukt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2kzbnpyky.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxyaqqv.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rudalalc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2zwzrxdfn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwynofti.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2crrdcpuy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2yyrlzfmk.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gt2ayqrncqi.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gt2pphzeppf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nquonhjc.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2vhlwoctz.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ggadrwhi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2vxixfjuj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2diamftwx.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2tfqwlxai.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptfvbtin.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gt2nqtqpbzl.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gt2vcdvottn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gt2dntqtdgk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2jraocrss.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2zbqkrekn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2yuhjdmcy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gt2dgelwroc.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2yxfvifzk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2svhqhscv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gt2yvzllbtr.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gt2htkftgfm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsgcikeh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2cacnkbal.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2sxdxoynm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gt2cyhpigus.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gt2lvpnbexa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gt2vnakclbl.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2btefcngf.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gt2kzypjagw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2gboeghlb.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijrrwnyi.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2ybdwzrsg.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2qntbylwz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gt2qkdbkhzh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2xdeedvhm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gt2yeurlnkc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2xhffcart.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2sgztqwrz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gt2yanavdir.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2bnvorint.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gt2wlodluha.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gt2jdlustkl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2viqsgpcp.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gt2ekhgikzs.html


<!-- 参考信息 -->