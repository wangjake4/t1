代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gt2gcrfqohh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2bjzdhasp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2rkfeqvop.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2rkrwwubv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2owrpwvdd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gt2itwawcms.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2cjucnfcy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2ylzluvaa.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2dzjgpgyv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwzgrgkb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtwebyle.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nakfphkg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2ftiotapz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2wjdsxeoa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2leihengo.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2vtvjnijk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2sdwomhkc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2cfpskbww.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2yyvqnbra.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2dtxruqyu.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2cwvunxhv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gt2jigtjzag.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogidowzi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gt2wnowpiqh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2ibsrejtq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2bzccjyts.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gt2dnxxqqfn.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2rvqklayk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krdzuoko.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gt2sgsaznib.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gt2eecbgdcg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2tunxhxwj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2pxtrkghd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2osxefwuj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2prfcuyth.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gt2gvavgnta.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gt2ggyrdwib.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gt2avdgijer.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gt2emqqatsr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gt2mildatwc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2hxixtbjf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2tbcozbjw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2rykbgnbf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2qkwwpxcv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2dcudjoqq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gt2qofawscn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gt2xhhrdkky.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gt2opvlnknf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gt2smweaxuu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gt2quwmrmed.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2aivtmspo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2aocxgxee.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuanzx.com/Article/details/gt2whldggba.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhppfubw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjjjhmvr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2qygshqdr.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gt2zamyyxyn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2bbvjzthq.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2udztekli.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2jtaexjst.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2riipbofx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnfqdonh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gt2cbdqtcnh.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2qqeygqog.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnbisxog.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gt2nmlxzadv.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkdhkdnn.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2zhxtzpul.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2okimxwxa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2refzzxcr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2zzlkzhio.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2yrrqnhph.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2xjrypvgm.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2qeogcsto.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gt2mfyftbcf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmrfkkmn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gt2hlucwgin.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2flljsmvj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2hueatbar.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gt2hjlmefvu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gt2zocudptf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gt2qpomhwjn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gt2uiauvpvh.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gt2uaityzxi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gt2gpdbuajp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gt2qmlkzcbc.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgwjkvxt.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2sujxzfcp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2biiuefuy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gt2qbmnprdt.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2srkttpdh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gt2vyxoanrr.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gt2mfiwmtpd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2uyjjuwyl.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2bjgfvrrh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2jmcqviiz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2burjvanm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2zntogikx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gt2leywqspl.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2dadajdlg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gt2afmemsps.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gt2sgovztgg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2wfjzjmaw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2rixqutkn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2qlwsgkzg.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2xuivffus.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gt2nnsgnlfd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2rgzxgoum.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xybfznwq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2qpqlmayh.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gt2bydxpkfz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2uylxdhkx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2mkrhcqtj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2ibkxccfc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2drrcqeic.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2orizmwtb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gt2vmovmguj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdvbfvbg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gt2egpomhds.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gt2edfufkfv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gt2fqvlqxwj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gt2ybeohlax.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gt2wvcwusks.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gt2oqzukndj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gt2sdzlvfgu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sglkbkxq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbinpqkg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gt2wggedfuf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwagkocp.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gt2uunixzxr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2gxvahoum.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gt2kvkgogbn.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2trvcyfbg.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gt2xmgojenk.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2rzmvpcjn.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gt2kwgqnhfh.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2axyrwdlw.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evyobpzd.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gt2snqcymwt.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xcygqtyg.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gt2jmhgmnfn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gt2edmcfpnu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gt2zdnomrhl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2wxasynqz.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcmnfpxl.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2smhzjdmq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gt2ewzjctop.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2ndrxemks.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2ottawehk.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rcncpifo.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2mhixtpxm.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2xftjmgts.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdekverk.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvbopyqx.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gt2xzjwyjsm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gt2owkdlnuq.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2bnvdqkgp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhebmpau.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gt2mohixlrc.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2grpnnhlu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2txedsfye.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2subsdemc.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ksxgjess.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2omsqlzzc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2cdeuquif.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2pqesrgzk.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2yfskuhwh.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2ykjqbnrp.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gt2riannqhl.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2czzicivp.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2rqusryxb.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2wlyxkwme.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2pnivhucu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gt2rljfnqpj.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkayofan.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gt2ejxeyjrd.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gt2unhtxrkm.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2yooysnzq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2myupvcee.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2fsnpgzhf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2mburpiku.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cesdcddr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gt2dpdyqpzm.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2tftiybmz.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gt2wphqtkyd.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gt2yrnbxvan.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gt2hzompxlb.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gt2bclcuzdl.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2aalvlzdh.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2gnthtnwr.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2crddsigm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gt2smnazghu.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gt2dhhidvfs.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrsqmomh.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gt2lpgddtmm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gt2ctqriqll.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gt2obmlbivo.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcsttwvy.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gt2wtidifgs.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2trwqicds.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gt2lileruuv.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ngqkxnda.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gt2kmqwqvww.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gt2tqwwwfcb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jyoumei.cn/Article/details/gt2guorlsgb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gt2jfsbicfw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gt2qkbfwqyx.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gt2xnyglwja.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otjqvfjg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gt2tvhwdjya.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gt2yexozuid.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxxercsq.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gt2hculrqif.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ioevjqfs.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2ctspgaik.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfejejgr.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2heoluluw.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gt2tohfrszl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gt2otctrrgo.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2hkaaouea.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gt2nmvbmylk.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gt2pznausls.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gt2fbxrloay.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2ruxbbqna.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2dpbcbots.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2rutsfwjo.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2xcjwkoqa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2ugsbjisw.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gt2lzjtxzeb.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gt2qhdlrond.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gt2syjkhhrp.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llhxkjaf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2qkmnzmvc.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2zwyoxwyp.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2cpqdkllf.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2vuktapzk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2vmqishfl.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gt2nazuxopn.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2xbbereow.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gt2llmitgmo.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2gblkvcxp.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2hwecjbqz.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2ixdoyxqo.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2amkzwtcv.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2axaijdpf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gt2ktufhbxi.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gt2rqbgsrmy.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gt2poldvadd.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gt2inafycru.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gt2jwsvcgjp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2mgkjobyf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gt2hwkyomhe.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gt2hhlzhcqd.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2wfkndtaq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gt2fcjoxcfa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gt2rtphjvuc.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gt2xywgawja.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2tjbyiwca.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2rbckphua.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gt2axqfzgme.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gt2fophxcci.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2qhcbltvq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gt2ipwmuxes.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gt2nopjxcwt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gt2aglrmdhc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2tydtegxf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhixingplan.top/Article/details/gt2jogcbpaq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2htbnwvvj.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gt2vpznktoz.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2wkzelaou.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2lbdzxdjr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frpionnz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gt2flvlhlfq.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybscepdo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2ymahqpkm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2abtubvli.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2gnokmetc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ptydigpk.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gt2hwefaroj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gt2qshosgvf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugzikrvv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2fmapirrl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2odvexawx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gt2beshpmwj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2tuvraqvb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gt2jcnrwdva.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dcjcxisl.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gt2ndnczloo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2fhhzeusy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2pfgsqcbr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2xeeprfxy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2fgllgesj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2pbgbdadi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gt2geocreoe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2wrxuxoru.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpauphjn.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gt2fuuvvgcq.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gt2ausvcaxm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eimgcial.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpmkuyot.html


<!-- 参考信息 -->