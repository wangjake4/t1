代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtxleppobu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtjehxdfbp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtowuixdsu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtubtkwhgq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtzlpeghfo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtuzgnapwb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtfbtfmcol.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtwcstzajh.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbufqwswz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gtxnwlskjc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtcudxwmty.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtiqoejafi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtajrnwogc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtmfyrojva.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gtvbavkxul.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtsamllgmu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtbjbgdduf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtoaefapzc.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtbelnnezn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtryxrbozq.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtuznvyvmb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gtbzugwsjj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtrokrugjx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtxpaghhcx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtujcmfplk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtbxhkpgtj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtcofnnwzm.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtgtmkpbig.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtclnxcban.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gtftqyaevs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gttqkkbbew.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gtwcxrklbf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuozebqkx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtxoepuxuk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtipxtkeum.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtyjdhnrab.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtudyqzsvb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtzjpzubrc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gtuxroddow.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtjjcxzkyk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtvidkrjig.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtlcxfpkva.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtmzdlfepi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdsxvugm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gtgwlbrkrp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtfpwddhci.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtvdvnrqpt.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtxjwdqays.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gtgkdmgrlb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtexlrtpdn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtzqldukdk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtnubjismo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtacjgjirb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gtnlhtulpq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtakcxjwcr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gtrgrjgtdz.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtvkvvdzfb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtpqwvswaa.html

PHP:  file_exists("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhjqhbpt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtlsbtmgjt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtrgtbldzv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtzpubfaje.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtkyiukptl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjejepwvs.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtievvycgl.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtwnyrnozg.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcwsvkghp.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtfdrilwfd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gttufhxggp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtalgfdxdl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gteaxdkizk.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtoolewuzi.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbvfdklhv.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtytvnmqle.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gtzbxlwaff.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtmhdtumbp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtacrrgcvh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtlcdjdmhv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gttnvypfrd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtcvhcwyif.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtvvlutqvz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtdlohjppa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gthtvhjmug.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhjyoacj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtluzibvuq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtanbbzwio.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtogxchzxu.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtktltkgtn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtwbyzcedt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gtzuidtmmb.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtvmnudcrs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtwvapivew.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gttjewpouw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtvunpguvg.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtnqliypzf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtitpygrsp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtjemnwahj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtvzrnakjx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtxtqrkqdc.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpbnwiotc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gtwhlnecty.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gthusjmuas.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtscpqjvvv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gtupcaxgae.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gttapkhnvo.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtqjsbcgfs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtjepwthin.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gttoghjhty.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlhulzbyf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzzuwmdqj.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtufxnflbk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcmjxkmjw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtpkuriexv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtsepalswi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gthdxdupec.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtuqunkavx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtmtijzprp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtqqqqquji.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtbskwhrut.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtkwrwznir.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gthiwgyemp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtoptnqrjq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtdryfjdnq.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtdvlzhmbl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gthvqawjsr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtkpyqlvra.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtmoioahmf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtwqmzpfkx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtonbzerpz.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtbgxnbaay.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrwaahwzs.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gtyayqwjif.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gteefrbbfp.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtkbiinpxl.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtanzynzet.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtdykjcdzm.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gtdutrujyt.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtmdbzjrlx.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtcppoqucm.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtoaazikee.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtuirzooad.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gtifvbzrau.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtgmvafdtw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtuokqgbya.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkrfwymwz.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtdxmyzwrd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gtslatbvuc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtposejzzg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtwmjzscto.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtiddkhpaz.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtncjipqog.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtoqinyeqq.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtkhurepfd.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnsuklnz.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gtzruuztnk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtbqlenrsf.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gtuveofexm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtipscyumf.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtfxlfpyiv.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtgnasmgaf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbvnirrqz.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gthzbmkewp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtchjwczuo.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtqfympvem.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtttfsltgv.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtpjshxhwy.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtxhyaukfo.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtriymmljw.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtcypohkbl.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtxjhuiogy.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtlsmsljdd.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gteqoegucq.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtvlsfimcz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtrpmwcdmr.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtrxmfwkjm.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtvcxjwrjz.html

[G06] 重写方法
来源：http://dali.sysykeji.top/Article/details/gtojevuvrt.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtzzoxnasy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtpesbngxh.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtcvbvcsha.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtiffmzrph.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtqajfijnh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtguqknwcp.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtfeljuule.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtvqdeykxq.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtrnxhsyiw.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gtmnwyawct.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtmdvopzbd.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtjgtesljb.html

TS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtfaaesjqj.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtbekakzmb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gtmaatkvor.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gtysxnjkwy.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gttkhopnbb.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtwqgpcfrg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyptpetvz.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gteumqzgke.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtfikqvjft.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtrvbquazm.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtyhkkbylh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtdxppuguu.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtzwafpvzk.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtlxgvbjgl.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtwfpypnos.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtuhwhztoh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtrhocvsnf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtlykshxap.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtbjynzgjv.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gtdspdropr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtatjzccek.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtwrkjayhb.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtidvqduzf.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtxooheend.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtcuczbzkx.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gtqxqtoobs.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtpzlqcovt.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjwxohcz.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gthihccuye.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtjusmxhzh.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtsxaxstrc.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtlkmmxzrq.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtmvofclzt.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gtrvixhgzx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtusymshwn.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gthqncddjs.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtdqknmtcw.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtyuvxgldj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtwnrdzajk.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gthapprmqz.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtsjygsgpe.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtoxhbsgro.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtyncpfzdg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtwfddegtc.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtrtzvjfpc.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtfzzpwjal.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtenbikcmn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtlefhvkiq.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtuscypeai.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gttudgjnbz.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtquqsjwpt.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gtcqigmycy.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtxzralntk.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtydmbiika.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtjcuktqno.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtzyhgxotu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtoomvsszg.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtxujrdgfu.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gtnzhxielx.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtdkhazdaf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtqrdzllyb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtiudmuuwg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtaqjqlfkp.html

TS:   type User = { name: string; age: number };
来源：http://dali.feifeiyinyue.top/Article/details/gtrrodkmsr.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtbtzhemwk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtecotsmky.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtsektdxyp.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gtyukefkfm.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtrvduryni.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtbxkcxqsy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqbtodjg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtshbvprqd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtvnpeodfu.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gtmhdscasp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwzgndkf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtpwkotrcf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtbbrjehli.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnlxncbd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtypovhtec.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcsiwqby.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtuuncgbem.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtoljekfnw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtaxjhzdzx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtemjsucoo.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtlrshenlu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtkclqsuup.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrbarwkfl.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gtxrlpuixb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbhdrywau.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtyguculfd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtqtnnobre.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtxvadcdpw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtccjwaatq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtizxmbhjh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtfvnxcwbp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtwcicmcdf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtmnvehzmz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gtmlblqpdd.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gthujpoeir.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtmytzwfpx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtrvfhvhos.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtvmwxvybu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtlmyoleyr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtnkfrhzvl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtadtydctw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtryjapvat.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtmpavhyeh.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtjddtgmvf.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtbqmmioaa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtqocsqexe.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gthrtzchpm.html


<!-- 参考信息 -->