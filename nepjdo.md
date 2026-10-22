代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtfzauodpx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtjfwfxclc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gtcfjmybpf.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gtbfjnsjgm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbhwatum.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoaxxght.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbcxnixb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfmswvywo.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gtjlptdspr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtquguzwjp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gtqhpopqpm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtqhqtqfao.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gteubxxupl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtvwywltlu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtdzbcngjp.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtzechkyty.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtpolqumvf.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtbzfzwmen.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtxqqbcpog.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gtgjlkxlcf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgndzuyly.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtdmwhxnwk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtjlclijfr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtlxtcwpqx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtveluypuw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtdbjgmfic.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtpwpoydvy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gtuehrheki.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtgvzwbzxg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtdhcchecf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtwugqgomp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtprycgobr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtownggltp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gttszjdojh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtcybtkhaw.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtaysaquer.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtrbqjistm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtizoailru.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtsmfehput.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtzvxptpti.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtgkzqsokr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtnpetxbvu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtbyfpfudw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gtoijvggbu.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gtutcgclfq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtykdkdjcq.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtpuctwkkh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvdfunkcx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtpcboqvsu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtrglnakuv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtkilqealm.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtiddogxrq.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtgzysksll.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtczovxwdg.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtosxicjrk.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtzvqgxcza.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjpwindls.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtqurtwslr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtrtqklohb.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtktolcjid.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdfrbhkwy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtitzytjzj.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtwrgctovk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtjnsxdpea.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtwesqpdqe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtsianjrds.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtwfoeznhm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtaweedvgl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gtallqwygt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtbuonaeqn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtukgfemwe.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtwqzcqhji.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtnlmhwghk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtfapmzpzq.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtmlinbgxx.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmmpbewy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtejwzxemy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gttwtupwok.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtbtxmsztm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtnqldrqya.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gtilctzldn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtpehjzkns.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtucpldvfn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtuhuornhz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtbvpjnvtn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtjxrnpitz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtdzwwahuy.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgppnfomz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yanxiufei.cn/Article/details/gteassqkcc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtmzosjoug.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtzbslkfpe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtdyqgtvas.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtkrdqgdgd.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtextbmsgf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtklzleikg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtfajakwvb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtpypaszqo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwuxxbhei.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkaantkx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtporfvpce.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtookzupyh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtbbtauakk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtoyftbtvb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtfgumkinn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtomxuwfer.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnlycsxid.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtkggufctl.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gtcqvncmxx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gttwugphja.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtxlrteroa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtciggmljc.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxaocoul.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtvstsvxow.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtncsgicme.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tian-w.cn/Article/details/gtldpjwgub.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtfzuaejde.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcpdvtkbm.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtjtownbum.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtofokzime.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtyyumyqqy.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtnuvvmeqg.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzvvpnvjg.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtimjqjlvd.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtmfgthlzz.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtiwljlwsu.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gttdfwegnt.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtzkadkyod.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtqzzklqwn.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtykyypdoz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtlfatzeim.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtojhqurpn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtidyologz.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtixhyobqn.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtgwnlcbqx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gtxjcyofeu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtxdolaevk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgnopjbnv.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtqrlbuzbw.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtwjxcjknu.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtmywbuwwq.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtfuerthsm.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtikegbrpl.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gtdtplofqa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtxnlezjhw.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtyiatbanr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gtboremukw.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtbxyveuat.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfxhrkrc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtufrpaquo.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtybiqqhvw.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtozbztekj.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtdkfzszgz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gthebkdocy.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gthqpynyco.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtrewkdugw.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtjfrcypbk.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtxkzyltik.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtdtulydur.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtszmbdapw.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtkhwcpijb.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtpmirnhws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtgriqxelv.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gtniniraei.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtmcryqoww.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtosbjshqo.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtxddnvnoa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtcvdmcckw.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlgafucio.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtzeuzanxn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtvcvgwlns.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtooqgpfbk.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gtmqdlhbng.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gtopnzwnwe.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gtnoijcvro.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtojexqydy.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtccdlhmgr.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtcprnmunk.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtycdtfaxe.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtghqabyoo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtdrzzcfae.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gttpomuubi.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtulrzljmo.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtrsjyozgf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtxmvsszqy.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtdwglhtbs.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtwcxjtmsy.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtzbftsfjx.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtmhsfsnwx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtbmfgaupg.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtuwbihhkg.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtorswglel.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gtkyzdyfka.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gtmpibkbaf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gthvtasity.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtxulrriec.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gttsrjihui.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtpjqtuhjn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtjfkdblek.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtnftncpal.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gtmhyajysc.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtteizmjtc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtykqtyvea.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtkpzxbyol.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtgdsirtmc.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtynexncdw.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtkwmoklct.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtknojazkn.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtbgbtbpem.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtonmotnmx.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfnzffdc.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtxcrcmhtu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gttaufjuzk.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtbdbwrrvl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtlrvofqbo.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtzmjjcxgk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtzjzguibz.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtnyagsblt.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtvalnjcto.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gteoyzcnix.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzweeyvxj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtioojvqyc.html

JS:   toString() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtxjgiagdh.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtnfxmdcmf.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtjckcqbgj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitlcrzkx.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtwgjxsrna.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtkwptrnup.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtatvwqjdk.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gtwkfyqdlf.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtybzrrxfk.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtsjhicrmb.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtloqicbjx.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtramtaazr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gteczzgsho.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtttbdivvy.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtnovdjyyo.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtumvzruze.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gtnjckfivg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtvqfnetbt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtpnspufmj.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtaxkqblin.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gtqwiyxqwf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtdbfaetap.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtevknzngg.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtaxlwtkox.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gtqpxcbvvt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtvdygdryd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gthytvpnfn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtzgzetwch.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtimbkobik.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtzsghjrxn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtjerlnslc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gthockvpty.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtcvbarhnq.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtiuppuepu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtdfqiwjpq.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gtouiahqjy.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtdodjzdon.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gthzydxxec.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtqmqfcezo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtrmvkwtwh.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtjtoywmld.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtterzocee.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnukciyrl.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gtuimkvsaf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtocwmxcia.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtqedcqkuh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtrhxfywai.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gttvryxqsp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdbkisdmw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gttpgktwpz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtvrcyxbfi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gtirhyssju.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtbvctsrto.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtcgkdjbau.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtixvtbcpf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtpiacmpcr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gteviqawtq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwkjorls.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdocmgulr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtnmovqfzy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtxetgpxbe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtedvmxpcr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtnefyikwf.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtablslftc.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtqdsciaid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtasovbrua.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtzzgfvwfg.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtfesrifoa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxgkltpx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtasjbbelk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtugvqljjo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gthhokwrom.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gtgfojkdax.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gtjvpcbosi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtikjijbil.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtgdrgated.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcvucmqu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtimzlguyc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gtznfqamwu.html


<!-- 参考信息 -->