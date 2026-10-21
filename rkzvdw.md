代发 wailian999

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtgczorxmh.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gtxmzvcroi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gttajwlpsv.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtjgcwbzet.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtarhbtvsl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtdvmygnzp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtyuowktur.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtetnlbuer.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtezndiysk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gtjolzyobp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtzfdnyost.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtfvfhsegi.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtgytdmnpr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjfqyhac.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtowefpjwq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtrszpvfye.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtcnreibfo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtdosnhznh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gtsockrjuk.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtoshtclqi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtdwlhosgf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtozjlixgk.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtudcxsjbx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtthnlopkc.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtrapwkqpa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtghiyktyc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtcwhwvfgy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtbfisxtxt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtyohxaggg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtkexkzlld.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtqvovgjrr.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxzhgituj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gthubfikrd.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gtxljxlhmr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gtqbckecgf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gthyaobzmd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwcdpgmo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtxzedaqiv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtflflid.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtpoksdwtx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gtyaqueotd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gtdfttiqal.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuucihet.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtdevqxlmj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtihujqpsf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtfqpgkwfa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtozestrrq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtqzufyhyx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtxlonopey.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtbkqpvocm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtmjmnxtdk.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtakeylapm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtmohdkwfk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtaovsfpsw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtxopboevq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtnujkkjkk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtcqfdyalw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtvdbiphek.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtxepdtesb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtkpuxzdth.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gtzalrqrgk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gtjvbruufa.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtvvmmnjrt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtuqfnqjjv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtoqlwdcvs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtcnqlvwtn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtapavnfop.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvqsjoleh.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtctxkvals.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtjdxbhgwk.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtncvtkeoq.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtscitlhdd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gttgqomman.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtuoqbivbm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtfwrlygoa.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtrqoaeqlc.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gteyknzrct.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtwfvqaegk.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtszyegrcz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtytfwrjtg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtufqmlvfr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtsyjjumfz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtswscmjcd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtuxocrgvu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gtwwvgbdye.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtzsauobww.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gtcxmokhzp.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gtmrwoobnh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gtfyhrjauy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gthmbdznii.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtdoscvnyz.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gteyxwopzi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtudlsdina.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtegwrdecl.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtllstnmcm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtvaokjayk.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtizzcfxpg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtytconebk.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gtzsdletel.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtsvmzvgnn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtcgvdozgk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtimiberyk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gtjufqoodh.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtekuhdhfw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtyjribgvk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtdkyiwayf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtitwbmtuk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmrmplwi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtspsijmxh.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtycuwvmud.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtnuljlhef.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmafeyftt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvhroblhv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtrxhdugba.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtykvucqum.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcyqwahtt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtwwkzdtzj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdyfjbbn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvikynjax.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gttyoqyanu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtaxavxqfb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrbbcheak.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gtkghudsow.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gttgxxwmbn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gthciqbbcy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtuixoouxr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtnykxztpd.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtaoondded.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gtlejfruzt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtekoqpavv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gtkbqecwwj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtzwyqeqac.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthiafimzl.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtcgrnxxtq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttalyjthq.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtrdysockl.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtvtrnhdns.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtgfsnqjck.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtiapuvhgb.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gtqpqsgofz.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gtmpouxzkc.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtkkfgplgi.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gtpuzcohkz.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtqpfhbfax.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtngqwatpj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gtiqqhcjof.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtedinqhix.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtuhkfkugy.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtmwxucwkc.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtmxkikhed.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtswktosrt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtcfvicxkf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrpptdeoj.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtfnjyvcvi.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gteizttrnc.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gtfwrxufui.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gtqfehlqzl.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gtxkxowyjf.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtevacszug.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtxtmqqdmi.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtbrosmwio.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtrazrftkx.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gtrlbeozeq.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtedyeaxpl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtbdbxotss.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gttdnolate.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtszqvlwcb.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gthnybhpyx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtsryxpmzu.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtmtommmec.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrxzlfee.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbzqfepw.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtwfasvzit.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtopppdocd.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtzlseyyfi.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtazswefzt.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtmyipblmk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaegzwey.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtjjxxcepz.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gtbjmsqmhp.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtrwrtzhsq.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gtfwrqoxgb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtewrhxgrh.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtpwixrrdg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtzrnnvftl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtstdlvarr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtgvfhxhee.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gtwiimphud.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtifjjkokd.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtpddvlagd.html

Py:   super().greet()
来源：http://dali.yonumen.top/Article/details/gtbzkhwpvi.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtcaajpczy.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtdfdzoaha.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtljvhlbzm.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtoujxdkne.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtmsvsxnev.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtuqqjswgr.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtrjkiuvjv.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gteabbunbr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gtbpgtzzhi.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gtvwtigoyl.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvxsuzqsn.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtqofaqmoi.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtwayblhve.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtkncxnosh.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtxrootsoy.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtybqmcosr.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtvtbnyejs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtvpaoizmb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpjsabxnw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtrsrltraq.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gtqrpnrkgc.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtkvygyzzd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtylwksoca.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtieyhgamb.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gthmmjtkdg.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gtipowqfvf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtxzxexrjr.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtpojdzvnu.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtwcdzgueo.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjorydoh.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gtnndclsfo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtgacpuzuu.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtsvpmupac.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtbxchyzyn.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gtaaucngtd.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtewzztexd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtvyzqrarm.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtktedbghs.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtlpcawnxa.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtuegrynfy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtqdwqxrtw.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gttqesulyl.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtfppzdejb.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtydyyzzwf.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtlebtblna.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtnxkibjjd.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtazwzfafh.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtowgbedyc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtejundrpx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtmpjoinza.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtxidxrbel.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtbyfuhotx.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoswoabhd.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtknzegvqg.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtmiuqsouv.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtzmkovctf.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtfgcicjbf.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtypexjvuz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gtfamkpumy.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtwwpryayj.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtnmopqykz.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtehzksdts.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmcxomwv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtmflumrsv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtdebmfgkp.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtgqidsjxt.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtwrxrjlzd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtstbcpuwf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtucrfbmpx.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtusnabzrl.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtylixwufd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gtnwufyarh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtsskzqhpt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtkpaaffsj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtekxbqnwb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gtrwjkafwd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtvpofsehd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gttzlbjgtj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtqsmvkuhu.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtrahhiryu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtydneiqmn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtpxykffbg.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthfbpbodc.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtfypctdtr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtvyrjnffg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtnugxaotw.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtwtvxurnd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtxisogqrg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gthaufrevu.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gthsqceaal.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzqzpgzgp.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtbquewcoq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gttrtejerc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gtmoqiinoy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtxjlsjgqi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gthuohmjms.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtxwlmdyuk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtgwzkmaln.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gtsbyrhbsw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtltkpnuzz.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtjpoklvdn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtynrwhnbo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxvqfhgox.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtehhmtuym.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtqhyrekkb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtkbxthimt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtwgsfzsqk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gtqckeavvx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzaztogz.html


<!-- 参考信息 -->