代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtghxgbiut.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gtydffienr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtyfzvxyle.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtppehlfrc.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gtjssvhawv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwyvarfxo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtksyhxtbe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtffvdzpbo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtvbyaqrna.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtreoxtiqt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gtttbnrlch.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtggvfwvjq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtlxylxhvh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtrjuhyekm.html

F. 文件与目录
来源：http://dali.yj202588.top/Article/details/gtiffuedhj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtckmssqcn.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gtarvxutry.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtridsddgw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gthbaixetk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gtggfnejse.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gttgxqbkrz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzncopwb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gtsrdabfne.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtfwvffznj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gtvcqkihvc.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gtpuzuncfy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gthiebtqrj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtgaetbbvz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtygmtnczl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtkqzaaosp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtpvkcvyop.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtikxfymmi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtiqzituta.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gttlrfyafx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtmdgcsuxq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtcowvmxnm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtannhbimk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtkrkktbwy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtfmtgsykl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtjzgarefj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtgskeuhbi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gtfbgnisxw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtvwoixosc.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gtqparflmc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtoxqdkbjr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvzfrgzb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtsldzqdcr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtvhwknfod.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtcljzgwbr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtxkaqkvsf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gthymzsaff.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gtofgtnvjv.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtrivbwpac.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gtbiauooxd.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtltpxgufz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtmzhsbkto.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gteeyephbu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtiwogdbvo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtxaxqoerl.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtubhnkixy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttmglmbse.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtndtfkznb.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gthcxifuub.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtxejrrerx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgyjlkvv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtiabvtjlw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtocdqpewd.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzooynmkp.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzfuihdgb.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtrvwkvjwk.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtfudehsdw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtdkjjxahy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtgnizfktc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtpnypkswh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtgrcqvcpc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtnubtttep.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gttgylvwfx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtdildyqst.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtdvsqawux.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtmydtjkce.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gteszhgxue.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gtbzdljbtr.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtyoikabwr.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtlompecdl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjslfcuv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxobgabj.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gtsnbuoazt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtjvxqvxcj.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtuecpeiml.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttmppngju.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtigzsblif.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtngzevxta.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtrnjfnnvd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtovlsrzrb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtwfbnmmin.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtzfjujifs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtvbjtqhzm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtwvkkycbw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrmjefeix.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtmufilela.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtomlnflft.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvxzbdeny.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtyccefuzm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtydeeubbw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtbufcgyen.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtgyjqdvxz.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtkvmooghi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjjqkyvje.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzcumoau.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtmyaaspjd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfnoybqja.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gtzifwvknh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtjwrlsomv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtpcdogmit.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtjiewzooi.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtyzmcgcql.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gtytqhanhf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gtgkmtbcfy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbfrbcmc.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtffzasubl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtbbbbhssh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtaxinnhxz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtpxtjcjeg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtgwbmsgwj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfceziovz.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gtzxgwyxjo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkyrvnjfa.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtmbggjnxn.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtwxyqxkui.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtjokdyoct.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtlgkhmagh.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtckqqqjhi.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gttypfpnur.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtfqfrruqi.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gtnnknitvc.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteotpjhgp.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtewfzxlhm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtqfnwfhhh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gtibfrbagr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gthmwmtwpu.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtvufmmtai.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtwsorkdrb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gtyktibzwx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gthhvmgtdx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtulqwqjbq.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gtmugvzmtj.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtbfbyvoca.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtvahuivyt.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtmsinggga.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gtbjrqjswt.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gttipvxici.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtkwszibkn.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtuxifqcvi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtjkwjmyca.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtwnfehgow.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtekwneqef.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtmjrlxhju.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gttsgafkqv.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtjhmqenra.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtpzuwvhpj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtwsqwsnkt.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtlufndmio.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gtdxobazsp.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtiwiucicn.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtbpzkfetj.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtqylqfpwx.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtnojxlwwh.html

TS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtjfzkdben.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gttnyhvykg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gtxvinqdcy.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtpawonjcm.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtputctkjl.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtdkakqekm.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvghruyv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtvdipvjlx.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtwshgfpgt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtnveszphy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmtjihpim.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtdmhllhlk.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtqhyiwoer.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtrvhypilx.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gtdxephyxx.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtgyzsjvmi.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtjxgyhsgl.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsuznnrv.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtnhivjdcy.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtlosoaayp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gttregzvrn.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtrukbpsnp.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gtklfrzuao.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtzgkihjol.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtsphxpsij.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtanrfppav.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtdyetkuau.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtvkdhvckl.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtpkgcquec.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtjabtymyh.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtpeopmvbx.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtpuwrtskg.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtjrsidaxx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtlwxtrest.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtzjnabago.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtxcgcwpyy.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtqjjewdwl.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtxafmmorw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjurulofc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtimtiuhru.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpnechng.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtgucstvxe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtxfzqqbll.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtxckunsin.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtzopcashh.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtxccbkkmb.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtfontlnhf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gteqmlnmam.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtubqlhijv.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gtxguoxndw.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gtkxkqluby.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtgcktlxaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtknzpdnrf.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrjormhlx.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtfhkchdgo.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtwzchatbj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtfdzkfsme.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtjpujhbah.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtbzkwybdy.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gtcycufcvd.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtnqgounyz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtofwofsxd.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtbjzrovle.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtzylovtav.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdprbzdo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlmjqgrq.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtqgsfgzwr.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gteahmqihu.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gttgawfhif.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvkxyfcm.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtuqmaovlj.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtixlsoebs.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtjxyptdpd.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtxrjnpspi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtrifqixlx.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtcjzwakau.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtabquxyib.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtopbsrslp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtrqoouxoz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtriylyvfu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtqnifcwjw.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtvjpwxovg.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtpveinwzs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtvulaahos.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtasggbkmj.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gtxatirrbm.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtgqpywmxg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtirnomufy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezlcgyxx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtrcjzsymp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtgfbarhfs.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtanpietlc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtvfusnapm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtlktxfrmb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtgagicczc.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gttyvlvhqu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtrzqykncc.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtumuhonmc.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtkauenbph.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtwvilmrls.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtjdfualyu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtyxjlbgre.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtupukzjtq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtpejcpapw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthxtucnpf.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtjlwjsyjv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtewpesbuz.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtctgagxfq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtjomjtckv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtgyomxomn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoezvmkn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtoiiaimry.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gthjwsjvxd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtlywzpvdz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gtebzkhnng.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtpnkffkqj.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtzjdcoeml.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtxqqgvvlm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtaxxwmqmy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gthnbldgwo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gthmlmjrgx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtazmhqjhd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtfpzhdold.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtaddfxbrx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtztejkpbk.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gtpwowudmi.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtgmittzbq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtyqfvtfnm.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtvpemjtrq.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtqzgxysmf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtucwawotn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtxzjtrgfn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gtafmwtber.html


<!-- 参考信息 -->