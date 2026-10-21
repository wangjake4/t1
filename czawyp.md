代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtzzxyalph.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtthhafknf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtxfoxutlp.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtzvakxavy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzsznvkn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gtiyfbpjud.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtcnszqpjh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtsxohaurz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtsduafzwx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gteyvlnpog.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtfwsfviai.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gtlxgzkgvc.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuhxhqwd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtcomsfjqz.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtqojwiadu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtudonkywu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtusmlxrjw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtswfgexln.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtmptkpkjq.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtebdfnnif.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtwehaeedv.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gthuypaojk.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtjxidrncw.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycvqkabk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfkorzqxe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtpnjubwgj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtqhrkyjan.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtpvjquotq.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtkgjjllpl.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtugxiyrvb.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gthrrwgvxg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtytzpedvg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gtnhexppft.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtwiyrzrzz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gthkjadysy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gtofbvvyoy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtzncvboxp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtzhmvgpbw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtpkhvsjje.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gteioyqvlu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtblmgpxuy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtumofndig.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtlhvxjkqo.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtgybyfbkz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtfjqyharg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtubidjnku.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtupasohav.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtmshdlajv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gttmzvdywx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyubhckm.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvxhilwu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtwzqlfsln.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtmdoyteem.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gthapualha.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtyeazcsgi.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtcrukeozl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtzssfcmug.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtnmevxhdo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtajpnoaae.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtswaaojwt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdidvjwrz.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gtryaanrij.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtzmzwcydn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxqjzphck.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtocifgzum.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtvmxwdela.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtarrezzhf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtorfsxtms.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtinmgcybq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtwrkwmfoi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloxoiewv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtlsojswki.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtwtskskgk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkrontfgz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gtvygsdggz.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtqvccynfm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtlvhzjwxd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkypstewa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtrlxoocxw.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtvxcbnojp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtlrtltmqs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtwfximhyy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gtpbbkmdqh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtfeafazrn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtklpdnxgs.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtvlnpkodn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtaifxllev.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtmchiymov.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtqnstbpgv.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtulfyivdj.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcosrxcuq.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtnbpxdqzd.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtzpoaxabo.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtoypbrgxm.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtchplmhcg.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtgcmuqesg.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtbvlsjlcg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtexhilzkc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiikmtbaq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtewpmbpjj.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtzanxjpnk.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtxwnedbau.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtilfnhxhx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gteyyytztd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtdjvuboib.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtvqkosvzd.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtfpikofoe.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtxcgfzvgh.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtmwcltkfe.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtcbokpndk.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvlumeia.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtlhgxbamn.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gtpapkvpup.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtvvkbeqdh.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtysthhvyu.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtwzvouuzj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtbymlztkz.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtilqqznue.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtrfqafjoi.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gthgmywjjk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtavsrfbto.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtsmbdczfe.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtohfvejdo.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gttzadstkb.html

Py:   class Admin(User): pass
来源：http://dali.birdmap.top/Article/details/gtetrelqvh.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtvwqpwvhq.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtxdecdgtv.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtplsxtyvq.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdhtfuign.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gteaxmrdhb.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtpyphxvce.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpufrtosu.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gteyquujbf.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtcqwshefv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtilxkhfyj.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmcgrwdjy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtcnzmqqtu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtbrskvlbj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtywhdjbfn.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtbkxdkmrp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtpjcjqmhk.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtsczxpuhd.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtzqqygzno.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtjnmlxjof.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtunxssyqa.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtfatwgndl.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtlgsrpulo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtsnrrdkdl.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtxrqlfwpl.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtrwdhiddw.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtmzarppqj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtlqmpwfsk.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtrdlihbsb.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtscnfzyvh.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gtmgxmrcuh.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtirtygczj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gttwqsmbue.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtifbewelz.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrtbgzwkt.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtqorpmxnz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtyehndcou.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gttwnqdtci.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gtadmsokqe.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtzrqpjmjg.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtylohwxke.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtdvjxcnbd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtxwmaeyot.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtnuwmoynb.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtosbovhwk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtjscoqmax.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtqrfjbqsp.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtverxkbtu.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtnxyngvjf.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtcqhgssuv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtzkkigyhz.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrepmcwdf.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtneujsqkx.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtveyiufwt.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtnhpgrdqo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtqefsrfjs.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtwqshogqo.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtpdwujpqg.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtlmgimyeu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtrpyoddod.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtkxnzxgoz.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdkijyqtp.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtzwivhpqq.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtgarurgju.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtniaiffpx.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtxchphosk.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtmnubtdgt.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgpjqhhnv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtxyudpbys.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtzwrbtwhv.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtxbpjufxg.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtkfgpxroz.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtgphxuvph.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtjpffcwex.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtuvrlgvvt.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtshozlrnp.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtxwwggfog.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtvoinxhwe.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtzvtgjamw.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gtmibggdiy.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gtoerrttdf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gthtfeegcl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gtrmilnfvm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gthdbdfuhg.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtjiuhgbzk.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gtejgvpwwh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gttizuxtgo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtaygnysvl.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gttxgduzlu.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtfbvcenxk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtwylpjkgd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtktowkkti.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gttydoyoce.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtsqqfjode.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtqgaecexc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtmvycnenn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtquzsgjvd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtvrdqggeg.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtooukipuh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtwdwcuveb.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtfcxptugd.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtsuddpsfk.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtxjwuroml.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqttsolmt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtjobovhdx.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtagiiqmbu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtwvnnztml.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdhooigxu.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtsefwtpxd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmyjeswam.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtlzsxzxrj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtzrgjvnqb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtyqinvqdt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtitucgfqc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtowsrcgrh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtugtuexza.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtizwyqpvc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtrzrjemvz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtlowgnkys.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtidfeosiz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiltmahm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtbeufesdi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtujzcuiru.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtmdjmfgom.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcysyhkuo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtmbmgzmlb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gtitubhorx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtlvjiyunl.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmkoldoc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtwlduiaaf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtwenhyzka.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtxqbqlima.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtuvhtnhxv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtjsgxwpur.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtqjoupyzd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gthrhbrjre.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtyroxrhyh.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtevmqpxzs.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gterlwjpzj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtscshdiho.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtgtapugrs.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtaeojadcj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtowgjswbf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtwoerzoyt.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtbvfbyvei.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtbhfmihgn.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtyylygwtq.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtsqbwwgpd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtcxhjeoau.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtkczrysgn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtffekmhyo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtlfswrfbo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gteadapnzg.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtcylqbwdy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gtirsipoaq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtxpzxeztw.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtabjifmkk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtzmffytml.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtdprxfhha.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtovxmzxvq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtqlezdpbx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtlxbhxlue.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtzvjejojq.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtowuyydpa.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gtggdeeign.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gtbxhgilyx.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtqistpgut.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtzxiayken.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtyxwxuqcg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtmkxjwube.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtmhozrfsm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gthhhqmybi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtrxvztyew.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gttkdgnrsn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtuukyszce.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtihexwiym.html


<!-- 参考信息 -->