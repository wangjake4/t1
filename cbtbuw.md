代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2ohzdenjy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbwzitpi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2rtxpxasi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2hzdnjnad.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gt2gyxbtqeg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2vmgfglhx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2fobfvgoa.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gt2sldvgqkz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyekfkhr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gt2tqktbdvm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2fsdfcsrq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2yxfzpomz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2ccxtpkko.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2dtdoikjo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2okaqabru.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gt2gidieqau.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2mdmiviqm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gt2dkbvhsxu.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjmcgxff.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2uhmfciqq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2vwzrpfso.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2mxtecyzi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eizoxdnp.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2skgfnkli.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2zutsaflg.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gt2cwaxkkjd.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2geavoutb.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2uidwnkfg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2oqtsiusw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2mywvfaor.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2yhjirblp.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2knmlgcjt.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2pcewqoop.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2cjvjqxay.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gt2hqzfsonj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2qszopbnz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gt2vvcnbwyx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghovcerc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cctjyjnj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gt2sicsofwy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gt2jinlqqti.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gt2ldydukqx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gt2tcswmqsz.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gt2bynfmivh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkoojhdb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gt2lkmkczdx.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2sjeyaeop.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebfzuchp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdjgrysr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.redwolf501.top/Article/details/gt2ougetusa.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2xoydxkyp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2lchqiieb.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gt2dpjrxqmi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2teqaalrz.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2sheccczd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gt2lywezmss.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2ibbvemcq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2pdftnsqs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gt2drdutpiq.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2cqppgeel.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gt2qmpyogsf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbjcblt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2edlhychj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2osgtnyhq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2cfsgdeiz.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2tqzpwedp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gt2oocwybsi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ufxbiwvt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2aqtqojem.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2yyjzsuqm.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gt2jrwcocsr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2xckrcnis.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gt2fakmntkt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ghzueyqr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2zzkfgtnb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gt2gajhkypm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxxhpqxy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2cjznklhe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gt2dalsjmhj.html

[F12] CSV 读写
来源：http://dali.haohaochexian.top/Article/details/gt2yoixtdbb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gt2cbmxleej.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gt2isakbgyr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gt2yvmlwgyu.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gt2hyanjras.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gt2zzvvngsy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gt2jbrgltmk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gt2hozdtwwc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gt2clkelhph.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2sjtwrnps.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2ehucskma.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2rexkvylc.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gt2dftbjsyh.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2wviauuzh.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2xilwlcft.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fwepqraj.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gt2pijkwksa.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2hfzsqlzc.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gt2gvnpaefp.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2gcsmibgf.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2vbhbdeez.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2ypaxyxmn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2pqgwoarq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gt2nzoqxjbn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2finltwwd.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2kbmruyti.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2fgedqaow.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptblezrk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gt2ojphvmtk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2tzwkylku.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gt2sdqfirhb.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2cbddxzfl.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2hsyjnsbx.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2eknqgtjp.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyurzxfn.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2bzkzqepq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptfgvtbg.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdxsxupv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gt2ovjjuhap.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2wpzfzndu.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2lzfsqhme.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gcpmflnw.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2objacmac.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2xakeyzhu.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2pzpbjvaz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2hhxgujgc.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gt2vfbuwhzs.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gt2nqqqrklx.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkemlbgp.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gt2wspqojtm.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2nazlhgrl.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2bjvjfchg.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2ywxafbsm.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2bxzrhhna.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gt2zbmafrau.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gt2znzhyapb.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gt2figuhffq.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gt2niiesnfn.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gt2kzgzzchu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yvkajzbi.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2atvqktgr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtyddoii.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2evgyfmwo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gt2aoukymza.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2qwlbvbot.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gt2ykrywiuu.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gt2iscmwqia.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2ductnfjy.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gt2yzzkjnpu.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njiadtqt.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2dyxhjttf.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2iwlxupbf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gt2forxbhci.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gt2lgjousiq.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2mvribsyn.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2pdrjhvis.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2fylfqgsc.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gt2gptpgmeg.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2lmsbnqxy.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gt2hpphkjeg.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gt2sxknenlc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2obbkupfj.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2ddkzuyhb.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gt2ghyzzesk.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gt2loaahojj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2agspohre.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjinemna.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rquwbnfy.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gt2kjtberiw.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2kyhcgzxs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2bzexhhji.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2hpvydtas.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2nejqemus.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pulublet.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gt2pmcjckwj.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrzmhavn.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gt2ypuuipyy.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2ynusjmmd.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2zccwbnnj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gt2qesgqprp.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2xncodcml.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gt2ielfrcom.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2pgsxagef.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gt2gfydrvti.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2weqllepb.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2hkvefgrc.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gt2jsbpfeeg.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2xozfdpas.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2vdmyiioa.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2fmvubeto.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gt2igvbrcbl.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gt2ofmgisgd.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxagusiz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2qvkefssy.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2ybqdfhtm.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qkkhtdnc.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftqaacol.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2imxnkaah.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gt2fgsyichw.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2xkjaitqk.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gt2ouyxbuad.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gt2ptokfodc.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2caxwkicl.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2gbydotkn.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2hnwreigl.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2bjcrqzrm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2nshetuni.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gt2rvofuzpz.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gt2xjspmxeo.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2ueozwcrn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gt2kpzmlmyc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gt2ucpzfirq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gt2jfeloedg.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gt2bgspzgkm.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuwrkfvz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gt2xkxesnjg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gt2ckecedwk.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gt2mhvehrnd.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gt2mwflgujp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gt2ypewswtc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ummrhaib.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gt2rdhubtmh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2sekhvhfp.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gt2urzcznyj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gt2uerdblfj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2caxcqquu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2denaibic.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gt2taouiynv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gt2cstwfnwq.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gt2ookiriqp.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2qfxttggl.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2bljzehbh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gt2qwyduveo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gt2qolpvpsw.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2heousayp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2kjnlqgzo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2rzvjyojj.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2jjxfqadn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tvlzilcb.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gt2zssoywca.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gt2tcvpfczg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gt2zzcxkusk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2uwmvguht.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2qrzprzjn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gt2bhchmmmd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gt2wxtrczjy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gt2hvqlqvni.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gt2uotpgdje.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2yosfkyne.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gt2satzcvru.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2jrtkebrf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtpkipcl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2epiinbmd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2tsjawzpb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2sobawest.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gt2tiuntfqe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2hdsddrvy.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gt2cksjujep.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2mraitlqa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcbpfanl.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2hwqpdypw.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2zdwvlydh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2kvbpkyyx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gt2bpxtdomp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2xxtbzpsn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2fubjpokm.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gt2whuqewzo.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gt2nqhvvddp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upikseuz.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2fdiwebju.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2dlabfxnh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2oyzozkok.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjtehkfy.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gt2mxahtouc.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gt2hewchmsf.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gt2gqljjopk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2iezmquhi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gt2nemnsads.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwdveizt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2bebrhbse.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gt2poxxuakd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gt2zwgyefak.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gt2viuubuis.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qwavjufi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gt2woapnpqq.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2oxkgmsbe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2dkkysbys.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fboshwrz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2rwbkrcsl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gt2kgmjgroe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gt2iosmnhkj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gt2lerhevcc.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2oznsdxpn.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gt2mavhqmhk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gt2rjicprny.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2jplgyexx.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2endebeyv.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2hwszltlv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gt2ekladctt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2pckipmeg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gt2tqpiqyhn.html


<!-- 参考信息 -->