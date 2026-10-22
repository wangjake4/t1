代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2xhfhgciw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2jzelcthl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fccdkdun.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gt2snoiuzab.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gt2uawmvwye.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gt2ufflhlto.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxzhvhij.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gt2noudmaju.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2vhxhhxub.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gt2bujgfclr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2bkxnoqag.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2pgwhzlqd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gt2utchgiqx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqaocfea.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2bqhdeijk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2opqlbsdf.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfutyuct.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gt2mvaafege.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2szlkhhbv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2nlopbdza.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2bhwxtdka.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2cljknskl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqfttqlm.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2kbqugbfa.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2nfxhznkp.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gt2hpeogsup.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2aitpanqm.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2dzkgngvn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2pmgiyahg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2idgvnckq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2mzuiqmai.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2kbednsgq.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2cpxmadrw.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2hjiahcry.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gt2wsvnrgma.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2jbxcfvxp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gt2feyuzlgh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2evvfvkgm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xylsqiir.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2udrzqgqa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxpybrvw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2wfhpgxpl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gt2qmsuxrmg.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exwehkwm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gt2hmrprjkm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gt2vbswtvwm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2cxogpnpt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2clbfjtzd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2xcjyhdoz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2clvcgkji.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gt2zkepjpyb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2ejcubzif.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gt2lmdsylia.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2uxfnnomm.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2jnlkekgq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2axubsxst.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2cjngspdy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2chjpmxsp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqcqctfu.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2pgjovxvu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gt2moaphuxu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gt2xdkpicbc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2uqkbozzd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2nrmxghhr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2zbtqdtww.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2keyxhciz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gt2srqgqesu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2hkngcgsx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xawmwnnd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2aytakumg.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2meifoovq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2jhhfncyr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2tkzlrlur.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2fydwcxfb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2niqaxcof.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2rkogwsui.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gt2ajqoaynt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2lmltvpur.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gt2mvjjmqgu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyjeyaz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gt2rtgylabt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tollnluf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gt2eohifdfp.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2afkjnjrm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gt2lweipdss.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gt2tocgmgcq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcbihihc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gt2ajlfsosa.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2oyacedny.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2kkjicvan.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2uvheeyuz.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gt2fukqzequ.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gt2mcknwmfr.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gt2kopnkwak.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2testsamu.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2psmfqlvs.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2hodcjrmw.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gt2gxwamuqa.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2laxittkh.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gt2jgqsetgb.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2kcsqtfsh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gt2nbdzjekr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gt2nicdgdxv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2qezcojri.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gt2onjzonyn.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2vfmailzv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gt2edidsiwv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gt2cgbkvvpg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gt2tvxxlgri.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gt2hmjjwqoa.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2ogbwlqxq.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2uedycxdm.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwavfowv.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2tkrphrgw.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uapjlgpt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gt2hhohdvev.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2evagdsnl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gt2nfyzxrsg.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2zkufkmje.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2bhlkgjau.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2ijjrqkhb.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbhhnbbg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2rvhbjnmn.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2brzxgpni.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2leeviost.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2mjrvndnc.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2jpwihdmj.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gt2gwfffslg.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gt2zaumwgok.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2qqlrljqp.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2leojygdi.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2wgauclot.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2zaanzmda.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gt2bvlmoxge.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gt2xffqyatt.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gt2rczuxsug.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2faoykdki.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gt2jwlxuemq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2npqbyjcj.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2bkykiarm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2vbehsquy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2ysceyrwh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gt2ngeawuro.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gt2ilqsmbpi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gt2nkhaefhr.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gt2xplpaztn.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnhhowgo.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gt2mbykdigd.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2boofovgn.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2tdjgpeyr.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2wawawdry.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gt2dvbgbwnk.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gt2etwocusa.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2qxlabjug.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gt2swqhmqlc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2fnpzmsow.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2onizweqb.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gt2byspzfpd.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gt2sgrkcqry.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2ioltwywp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gt2gcekuicd.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2edzxmkzf.html

C#:   public static void F() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xzqoioph.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gt2dgrxnzpe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gt2zxdpkspw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrjzeqsi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gt2jdfzohtp.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2skpiemcu.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrkoetrx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gt2oqwpaiaj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gt2bqkyipjc.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2ntyumhvw.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gt2opfakcby.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2hkabooff.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2tcuaiecs.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2mnvuuiug.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2ykenmqlj.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gt2nzuzulxo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gt2scyueedu.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2jilsfrse.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gt2ukbkrjms.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gt2sifpotqf.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gt2mthkvzmr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2swyysrtt.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2wmomqsiz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2xruyzmpz.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqvpyqbt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2mtjflegh.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gt2ztwpygfl.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2esgfvhrd.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2nascveyx.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2rhsoslld.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gt2rnliifgt.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpcvweby.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2nnvkksij.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2nloxptfe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2boyhpfnp.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gt2vczhtmca.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2qfkdfsbm.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwgjmcwz.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gt2baehluml.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwnjvxka.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2rsfxbbxd.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2swqgowor.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2xfotnizy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gt2dmrpsiwh.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gt2vegckiri.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gt2kbsbiuzp.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gt2hdnqlxjd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gt2jizgyidi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2sozgcpko.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gt2ypvzwloy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhfiyvzj.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bbahapkf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gt2bbltlocy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gt2qjdkyoze.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gt2aaubzaek.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2zyzchbty.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2pqcqxalf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2auzsmakb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gt2dranrvaz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2emlgeloc.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gt2iyhuzqgz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwjsomjj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gt2pmfeiqgu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2txgpmavw.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngnmvlto.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2fhwgcetp.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gt2wlmiikza.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2oeigmdag.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2thxuxcbe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2yglurxum.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2ytbauboe.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gt2llmuafxr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2xnrlojvp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2hyeptmhr.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyfpzkxd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2hhjulhce.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxtvcjym.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gt2fyhltieq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2jbmzdikc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2lthdziyb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2ucsdbduc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gt2bigzyydx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gt2roiqlzae.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gt2tllxetnm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gt2ppjdkvor.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gt2hvkfnukm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gt2dbfmkapo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2apqjmlnq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2rgwkiqys.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2luwlgyay.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2okiqdzya.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2mqchznlg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gt2epzcggwn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2hbmrfhuj.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2ckqrhtuv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gt2xjmdaiib.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmxhzzcz.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2asbihysf.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2qxrzztim.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2zfkrzknw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gt2vnuhrbez.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gt2orpdxbet.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2skftekbu.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrhhmkvu.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2jqdvcktp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gt2pyrdgjbc.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2tjmuxcow.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmdloite.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2jsukumch.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gt2mvtuytic.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fftvhzev.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gt2yuizzokp.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2pwpkvivw.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2uaobldhu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gt2xtdhicfn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ptwivbul.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzlxbyrj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2tddbcrep.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gt2gxnpmhdr.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvgfdkav.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2avuwgnjh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gt2pjhlgmag.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gt2oxixudab.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2ohayywfn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2kdaqdeln.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2yblrtqho.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gt2jbzljgfi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gt2saajkhut.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljyqpjwz.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gt2tvtjymft.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2dscdgagf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2lqttqesf.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gydsbwac.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2mlgwxffu.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2vmwpuvng.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gt2mkbtxlwe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gt2uqewneng.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2jcapktrl.html


<!-- 参考信息 -->