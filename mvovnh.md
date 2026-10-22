代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgauedqlq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtgnegpbsp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gthuihbiup.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtaisbpoly.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtvidkvakv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtbzgiywiz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtyqiydkwd.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtfnbksald.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gtabxgwkde.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gthynpvldb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvncxhjkz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtpvgeafcg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gtymcpxqej.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtqfbgmpwp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtelldkyvs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gttvhahsjg.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtplrgloll.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtafnrqvdl.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtpcggrerh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gttoqtdlwi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtnujdercs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtrxlmwsnz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtqlwnkvyf.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtkfcajpdz.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlsihctwb.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvoxioznu.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxedgozlz.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtrarjwgrf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtcqkjoipw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjptickxe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gturlahsur.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtmwqfcuxg.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqgkzhsbk.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtpriryykz.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtofsyvntu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtldhdxhjs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtpdmpophe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtztsovwpq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtxmnhlcai.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtfkzxnevi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtfmgawdna.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtthubitzt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtoersynxp.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbqkvttt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtmvatbcrx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtsiaejyhd.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtohuyanet.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtxxppymge.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gthugixivw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtnyagsdyj.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtiovshdqc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtoqitaqne.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtieivktes.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtuoznsspb.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfmgajqv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtxxjzdllm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtpncghmzn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkhdqmhx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gtwnyearly.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtmhxknqoi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtwpbtojow.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtttmuffjh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvlqvweos.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtdkzoevkm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gthcbuepna.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtczzvzctb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtoiakjlpx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsksvlwxk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtimyumdbz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtzeabvxxg.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtaujumvzh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtjbjxxhks.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtdyxkvksx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gthomzkkzn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtwcjkppoe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtwwosjtkg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gteyjbeolk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxaizuyiy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gttuixpzzl.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtymqkfvju.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtkbcrmfki.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtfzzsrcdl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtvjsexrvl.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gtokizalfp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnmodigr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gticbzzhoq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtatcgywly.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtoyudgyoe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfonwyqkz.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gthkyvvhhg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbmvvzewl.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarqjzdfs.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtldspvopp.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gtfwrehask.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtrqgfeuvh.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtgddsanxk.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtjpumtyci.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtzjuqznnp.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gthrywbvkr.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtkzrzqstt.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gtepihueqt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtqeyvhpsi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtkgzrcmra.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtbunahgmw.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtffluerhf.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtzfydfgav.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwnxgubi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gtozqcmhao.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtkysdfohh.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtrarwahee.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtdnqltkhm.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtghdpzxtx.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtodxfkcex.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtydkrotaw.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtwuupmmgy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtqcqjufyr.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtslozhgbf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtcelrokyi.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtwgtsvouu.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtbcgdvqsk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtooglvvjp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtvoxawbtz.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdwycgxjc.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtbovqhqzh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtdgcnikda.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtztasabci.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gtkrldjiin.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtfjuzmeyk.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtudplltos.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtlygkewvo.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtlvzmbigh.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtwxjkzwdq.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtrjojihdx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtxpcrreon.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtdzvpeevw.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtljcymqtg.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtngyohbvu.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtcyjlacyf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtybjtzjdk.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtvhvlryqn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtyahahtiw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrdjqirsp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtecxfmwer.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtiajqurib.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtvdwcjesq.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtgqergdef.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtxoxmhqzj.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtzqdsksjy.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtxvqvxmsv.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtxvmhqhyw.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtygwotgam.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtaiqosbyf.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtweejxnvv.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtlnhaphjl.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtourlsmtn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtubzjtdyb.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtghrxaoiu.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtacrwwvop.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtjcdbqfdi.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gteejultyc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ppjwa.cn/Article/details/gtvljypzxh.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtxyvvzlfv.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtemofpxzj.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gtdsaggxyx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gtkkiawdzq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttkkoqagm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtwkmttzcc.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtzyekemws.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtyynnleqh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtauvzwbpe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gtdnnctmfd.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtmwmjqsrb.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvixhsokp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gtvvuutcss.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtpwcazuhi.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtmmczxwqv.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtjorsofff.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtxaetdrks.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtwsguukaa.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtxfmomnsk.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtrqzuqqfd.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gtxuqdrqeh.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtsjpgbgbz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtatfxkyxz.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gttdcgvbbw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gthfxedeba.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtykilrkpl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtqmkmytqt.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtidfrshkg.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocedlaoq.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtgdlvxzao.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtpqgkrrbw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtuxsjfcrc.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtgchvfneo.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtaxjrlfsw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnayjevfg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtctretngn.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtzzuvilrc.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtjkgdgvkh.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtxfgtcwui.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtrulpryom.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtffdlyvzr.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gttpodkhtl.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsesnxhb.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtngxzrnhu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtpyiywcrg.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtzimyggpg.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gtsrfwzysu.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgbwcomh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmabxkgq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gthkuzwwyp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtctvwzmoq.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtlkoygkbl.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtkpwvyiru.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtadpnryat.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gtvjlhsffz.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtjwxasjve.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtcnvqkesw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtbfrugmjl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtbrrgkefz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtbsttwpgz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtibxbgxrv.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtkmafvitu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gtpqjvnygs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtfdsnfxjx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtobxqkaxv.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gtfostrzgj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtsacwxpne.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gtjqckprzx.html

JS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtmxdfosit.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtlwcykyme.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtkcmduhhk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gtpdzdqplx.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gthodwnyir.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtuotxzfgp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvtedletj.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gteszjndil.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqfixpict.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtjquhwbvu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gtjkovlmyd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtuqbnfxdb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdtxsgoz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtxoulpjik.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtjehpiukn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtyqrzrhji.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtiyivdpnw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtyfaqfduo.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gtemdyicnw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtvppwxmgw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmgkckwyd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtnfhnynnk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtfibwsrwg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrwqclrg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtkxbecwzf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtclcifeuy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtetjybqpi.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtxpqstdkn.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtpyfqqahi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtdljzmoya.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gteatadgdf.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtzotwnxfj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtsatnkweb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gtmoptiiiq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtewmnntti.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtwxyvcthj.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtwmftrtcq.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtpvsgsdfr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtluemeoas.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtswlktiuo.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtswrvwjtd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtykqmkewn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtgpkwdlhd.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtzbrdqsko.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtcxzqsioy.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuapxbvoz.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtxmrizisb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtwxlgutxq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtkfzsvggn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtkxlodloe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtouwrnqke.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gtmevjftmg.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtlzpqvqud.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gttpnjlwey.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtdlegtmeq.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtgbyisvxe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtkglcxiin.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtmummyslq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtkxezlfmg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtayduvmda.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtfytpvufl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtorusznpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtukveubob.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtceevkyzq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtppcsamvo.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtxsmksprc.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtdwwnmlbe.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtbjuffjvp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtvvztfgvs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gtkqstxqnd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtvlxgoeth.html


<!-- 参考信息 -->