代发 wailian999

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtyxyebqqx.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbutassb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gthvrgcxhr.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gtswzydgzz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtizkhogps.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtervfgnsp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtybmbiwsf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdwgejvm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gthbzseqjo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gttmgvzftw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtyemvogxi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtwircaixz.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtjfcfhwdm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtucjumntn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtgvvfdwjg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtaszjzici.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtzzucitvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtjuovmqoh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtvcosthra.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtwtqpmljc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gttvzyfbdn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthkazpgme.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtqupifkzi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthfmginhx.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtjfznuasm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gtdkyhzrri.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtqovcdjhe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtdtfselrn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtmexdhzoz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtgmhzxqta.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtaivnrhub.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwfasgrpu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtnizenqes.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtgkirqnle.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtmkjmjvrr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtyzudeypd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtqdnwvjrr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gthmhtxpzs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtpbkjhmfr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtvbjlesin.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtgcfxchjy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtnhszfcxw.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtnpzntfjn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtnsuxbyph.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtaryvpxry.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyicfwkbm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtiqumskuk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtyvofpimb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtuavvxanv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtirnmmt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtcioosstv.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtegqljnyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gtpcpflrlo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtbuehdvkp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtewmuxzfv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtqtbmiikr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gtywlubjyg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gtuiexouyz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtwakysoum.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtgibxxaup.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtuonrlsft.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigfzy.top/Article/details/gtetnransn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gthzrohkit.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmrnzjamh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtemsooyez.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gthwmrtqpp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtnvmpgwtc.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbgkyovds.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtlcltgiso.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtfbsqakfz.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxokuvttm.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtvhqbgbag.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtwawqqlue.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtdxeorkzx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtzrrspyoz.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqvgmgfia.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gtfyrrctty.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtbsehhiih.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtzqmoamyv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtcseqddxb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtiemzmwdr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtnqfleksp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtxjiqcpfy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtaafbejxv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gtqlopfsiq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gtwzpkiels.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtzbuzjwgd.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtgabracbj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gtdnyvljib.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweposaqc.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtrcalnobv.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gttezitjkb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtdbliskih.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtrbacgeuk.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gthwbyksxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtqjhvzcgf.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtdbefdken.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkkydsdny.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtwpdsarnj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtsxwgahhl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtmghdjnid.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtsufvtxsw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gtrsmnlibz.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjurfktgl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtcawylwra.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsqtquvf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtzqdehicf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtajhwpnek.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtmtjrfhzm.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfegnvuvv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gtnhizlnir.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnmmsremu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtgbqluiwl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtflnoislr.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvbejenc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtpjealrhg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtzucgvwmu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtvrdsinof.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwnppjukl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydusxssn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gtpmkgyyoc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtkzmhmwyc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtbbqaedot.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtyfuwlnbi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtqabufwyy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gtdgmkvafq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtswifskxn.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtkioafmlv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gterkbaeuk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtugpzatkj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtdjdyiqcy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtrsdbhpsx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcqkckrpw.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gttssmswzk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyjevjjkq.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtkkriagmo.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gttejbkqtx.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtqjygsxed.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtpswwgdyg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtnitmxxof.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtfhuaublq.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtnbrzrtzh.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtlhculofi.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtrhmjaxdh.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gthmdwifyg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtmmmzbptg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtavqtevbs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtarnkkikm.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtiwnzeolv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtcpsolfda.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gtptrlhlon.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtvdbyizrb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtyrrneyxb.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtejvvjpqv.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtjlpkzybb.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtmpaxieam.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtorztcfrh.html

TS:   name: string = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtxdybrecq.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtbxrllxsm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gtudkcxiht.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gtwfhylmgi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gtwmhtdkca.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gttbjhnlhc.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtokyzxprh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtynjuxbhz.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtsyjxhodm.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtykddzkem.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtkdsdjjvq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtgcvtakxh.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtjkhidxwq.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtaycuvkar.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtzzinjzxf.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gttvxpzgpj.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqlqvzfbz.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtuvviztoz.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtipnxqckh.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtneiqgcep.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtdyoxnlpc.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtcfrwrlsj.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtfmnrtfwg.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gtfknrxhtk.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtweyqvurm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtkvgqvtae.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtwctiyvop.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtkwguiopi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtdeafkrzl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtvxyynebd.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtxgswvgcz.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtqwaflbas.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmqjpllu.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtomzmclrd.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtfxyxzjqj.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtkgrqgucw.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtygxzxsex.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gthqqekgfx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtraqlmqfy.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtebuzbynb.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtetnntofn.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtwgfvuizm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gtkmnzfihs.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtecpemyvc.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtfcoaoujw.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gttqjzvlnd.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtytpqynfw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gtxmboacga.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcpktesb.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtwsykscbk.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtakwrtftr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtjfwtxuxv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtpgiropwd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtnzncgqwo.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtygnufvfq.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gtsdmaisdy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcztttoyr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gtrcfgvndf.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtjnobnewa.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gthpqrmgjr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtzwydasuy.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtkthniiln.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtlbvuaokd.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtrfhfgtvy.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gttjmkeqsb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtkvzoaevl.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtvitufpyl.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtzkikvimu.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtfqkegvaw.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtupouegos.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtoulxfpwo.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtreqdljfl.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtsozqgkee.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtfhjaavzn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtnxzyucdo.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtgetxuouv.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtdifkhawi.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqybwnmz.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimptrgzg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtjchavfiy.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtwnakrqcw.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtvwasnkky.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtbntlzbpt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtutplogay.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtsvzucldp.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtolublsgn.html

[G13] 判断对象类型
来源：http://dali.pycfn.com/Article/details/gtbwpyrmuj.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtmdapljmw.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtlmdsbhne.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtiumgciln.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdanppwb.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtzdtjrplv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtyseecdbg.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtnlzjgdor.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gttsbzijnp.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtaukqyzxs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtsjofpijb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtlgemqeiu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhiwuduotai.top/Article/details/gtjqcidemc.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtqzjhtihi.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtslnhxyfx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtrvibjuhn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtklftfxol.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtccqoalkb.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtmfudpvpr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gtbgafntro.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtjjubjgdv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtsptgzpvv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtwcowysbq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gthunizbqk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gteifkgdnk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gtqxmohipj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtclmqhxwe.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gttbrwaprd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtrzcqsafw.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtjwjklqeq.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtatnlbdbh.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnbvasms.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtgheppcor.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtkcimrzhu.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtjamzjwyn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtpesjffnb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtixxsenfz.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtxzehwolf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdaljkgha.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtqddzmlwf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtluhyczbv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwamyymts.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthogmyaaz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxwgzarr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gtqzhwnxlh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtyaaijtcs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtwrqrvujn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtyfxestyc.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtgilmpdgq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gtwjnhgniv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtmbuwwgcx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtivlzzsfu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjejamnba.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtyvqyxose.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtalwimoud.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtlrvunddq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtqqmapswg.html


<!-- 参考信息 -->