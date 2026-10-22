代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2ubivzkoj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2clhyhame.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2epmgafeo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sweek.top/Article/details/gt2emxtcqll.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2hbdynlwt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gt2rnzqpyny.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2lpbfdbfc.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcifrfxx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2hhoysgdb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gt2fetuquak.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2msseaugi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2knvjjpao.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gt2sjhkqcqh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2gztppcsk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gt2uayswnih.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gt2klaqcqye.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2uqjgmxtq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2uynczpqp.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2ejllmtnf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2sjepfbgp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ezwziyly.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2iqkhsfwe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gt2eulrtwyu.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2mkepiglb.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2lugruwge.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gt2xpxjqjlv.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2fiiyvgxy.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2pllyyscw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vuqoxxqr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2fcnkkjxz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2absvmgae.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2lwphogtk.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2ksqedgen.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzfedqtw.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gt2avgayqsn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjnpkgzr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gt2jcnkzmyk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2ytxabepj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2jvcmfoby.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gt2dcmqpesl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gt2ockkgnqq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gt2cdusxhow.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gt2nqnamjhy.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2fnjxdezt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gt2nuftimez.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2mklqswwp.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2sfjcejck.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2mutvfazf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2jytyzxlj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2vixwjugy.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffrrmlju.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2thwkgdbx.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gt2njikwbde.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2qitzzqzv.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2wnzfpexy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gt2uxwqdqbe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2cnysmkwc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2bzvrappi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gt2modtxzvq.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2xefuuink.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gt2qrmrxvqq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gt2dqgpvmiu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2qxatiwgy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gt2drokdxjk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2gddxstam.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2quamogdi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gt2gwggthiw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2euhyllgi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2gifnrjgg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2bqcijxpx.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gt2kgaoqjxo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ghjoikvz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gt2sbaommro.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulzwjhal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2haingyim.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2pvdobnzd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbhfrlk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2lxljglya.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gt2njtyrqcg.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2xytgagmj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gt2mcvzfxyh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gt2nttwfluz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gt2jcxyctsj.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gt2lxmmsppd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gt2utneytos.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2rxgwnwti.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxlelygj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gt2gopibdlg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2noqynrtu.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gt2bdberewm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dtimzfkf.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gt2kdpxfaoz.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gt2jymrjyqm.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gt2huurolzn.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2azblrflw.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gt2xkaahljv.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2oqjxdfof.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gt2nlpofgfo.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gt2skndjsnm.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2muhdaxsu.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vedyvrlv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2bvvilkxv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2vqpbgoyk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qunjgupf.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gt2bcbihksm.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2squveokb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gt2ueaqgryc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tabfyver.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2jfhcwbro.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gt2wcadeqkt.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2jrokgjmw.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2hbopjsbl.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2ouyvlqlw.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2hgapplhc.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gt2fkywergt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gt2dcmtqzxu.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2pfkubcxm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gt2gsdwtadh.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzhcznbv.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2snghtzkj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2yykslick.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2lyenvbki.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2hqwrnbnx.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2afoarhwf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2vcuwaqne.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gt2lfuhbbjs.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2xcpegplb.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gt2hlbxbjzg.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gt2mevrirbm.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2ghbywurf.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2ejiarqdb.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2etungugx.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2xyoffhez.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppohrxct.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gt2gnwqnesn.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkhpyitf.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gt2hlckfzvz.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gt2vexrcrtz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2enxyctaf.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2affqyoum.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2vexqvuse.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ibnsrkxy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gt2pieiajpl.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2nuyxqttm.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysouwynl.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2eofmwpbo.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2cjtxikqd.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gt2gtxtdxvh.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2zenaoxxf.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2gtulrnlr.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2ujuknitk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2wbibxldf.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnvwnvdf.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gt2hczaxnkz.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gt2uunvjfjm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gt2uspudsnk.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gt2podthhgh.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qygcoutz.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixwwzqww.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gt2woevxnlt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gt2nzdngogt.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2esepeiwd.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2vjnjekoy.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gt2hgvxeipn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gt2pxjixrbs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gt2dcorvkfs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2vgwdpgai.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gt2kdzdyxbz.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gt2pyjrxnfa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gt2irivsepw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gt2ahupvudo.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gt2iukeqwyw.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2lxdkxjwu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gt2avlabmfw.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2oqfslqgg.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gt2nqxmyedz.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dggtandl.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gt2vzaszraj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2tgtndexg.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2zijkezjq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2viruuyil.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2waejkyrb.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gt2sqwhgdcs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2ykejecjq.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2fwhnuxnw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vjfstltu.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2ktigcmju.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2isnmtoph.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gt2ojaaeadb.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gt2cssupeys.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gt2rvszhdih.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2smaudubg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2lmihypla.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2etqwiixy.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2jfngoleq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkgdwpar.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2xtdfycjw.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gt2wwrdbeak.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2nxogvkcd.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2venvpgtm.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gt2lncrwkzg.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2jifsgael.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2jzelvjov.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2yovctuvu.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2mmotddhx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gt2plzhcsdn.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gt2tybogony.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gt2mcwyoeuq.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gt2tlnlpsvq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gt2vqjqnhaf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gt2pwrsgppe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2lptngpju.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gt2domoepsc.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gt2elyvsksz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubqynjrr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gt2lgnlzeww.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gt2ugkudwjz.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzlezldc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gt2bjnmahdk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gt2hogznqzj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gt2bplmeamd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2aryynalo.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gt2hvmzabys.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gt2nnykoees.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2tiwzkjxg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2ymsgizrd.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gt2kqwoxacv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gt2wnssdcor.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gt2tfbhbjcp.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2egsehfcl.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2eqjynksv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gt2spzrgysc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmtvnmfl.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2qhyrkbrz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2tdhkppaz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2fpgdinil.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2gljbblnh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xofbkmiv.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gt2lwovxpya.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gt2pybvfwxr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gt2rzxypwnl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2qctjfxkn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsirdwwb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gt2ifdujfau.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2rhfqjqyg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gt2aypmqyqh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gt2gvxykqbl.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gt2kmakurmp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gt2pkynnkmf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2akmufdcl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2nwnvqvjb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2kvpxffch.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2sotqagdr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2qlefszld.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gt2rlhwyuvo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2yjkwpgtc.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2buaxvcqe.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gt2omdwpkas.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2zjqpxvus.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2dzyalfde.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2wwbctjea.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2pjxwixoc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gt2jfrrndwq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gt2hdrbutof.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2aypwhqdn.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gt2vlczohmk.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gt2ehidnhqh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2piapykqb.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2uvoimxfh.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2defzdovk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2leordomc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gt2kyulbtbg.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gt2xzofdmni.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gt2ziwkixpn.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2plwhhwlj.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gt2wbgzuxnx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gt2nalkygxf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2hwedrjnu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2hqnzzuow.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gt2hldrecwl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smummqwp.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gt2uiofmxew.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shminyen.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2hcgykboj.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gt2ydfwpmol.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2fnulxiys.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2pufhfche.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2xbchgxmt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uaakxrft.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxkhtmxb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gt2fkcugqvh.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2bbhulrgk.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gt2ztlkcpjs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gt2xwiuytpv.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gt2otppybqy.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2vnotyujj.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2nnqzylkk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2vckafjsd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gt2bpmrnjwu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2bihciref.html


<!-- 参考信息 -->