代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gttassoyfx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtakacbaiw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtnnlwsucr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtaexujlhu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtzcqhovrz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtsdqpaxxe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gtvgilxcsy.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtgwrtoasu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtdgsxzzim.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthmkyflam.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtnlekrmrd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlkgbgudd.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtxcwshinc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtahfcvehb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtlcpopuso.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtjbdwlluj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gtrsfzlfbv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtnsdqzyii.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtqzwdhvae.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtunzrawmd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtocimswra.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtvjyhcsnf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtphhkiizc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtxllridkf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtvvlbdwfa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgevnnum.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtncieabdx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtyxrofoun.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gtjatocdrq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlulgzsn.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtmieadkxm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtlnkqkyqk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbxizige.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtqzovludb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtgrwxzivj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtpocsfdzq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtcfcgrjob.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtrlwkskqp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtzeoenzst.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gturpiumig.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtkvraibec.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gtgyhcbuwk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtubqkrcij.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtlhhqsipq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gtmpanlfer.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtycrvwwmb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gtchmvsjao.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gtsjxoqruy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtbgjfcbnv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtlepxozxg.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtmprjnqaj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwemaiws.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtriajcdvl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtrqiouqvs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtxjqvoemm.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtewclbtjx.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgitfjpey.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtpnwluyqu.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrmmgppqj.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gtygiwcxbm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtubnpdfjl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtokzocmvj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtozjfdxck.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttjnobtpo.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtntyrbgjp.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtpimzzkqw.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtgosxxqfj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gthkzvqlco.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtpeutqphg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtmzxrxkpd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtseqbhjzg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtcixlquso.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtiyxnxksk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtzysaxcvo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtynyvdphu.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtqcozrxlq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtmlolyapq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesnkupdr.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtaeytftuj.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gthotxytdp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtprerzmxu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gttwcgzpsk.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtdegqfipb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtwfdnveys.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtnvxonguf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtaybmfexy.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gthujkmlhr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtshjdrixp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gthlwxqruh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gteqhneyjl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqzzrjjy.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtufqruefq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqvsdbot.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gttapnnjqh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtewjmksxt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgjtpfcj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtyuxotcre.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtzouglfpo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtmgmtfluh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtctvaiuyk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtqfzwtdar.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjzeqkqrn.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gtbkzdkllc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtgkvznchl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtzxwvfxck.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtfbbkuswv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpkkwqrh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtfyifjkwh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtbwcwhcuo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtyeohnpvm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtfhahamiv.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtscysljso.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gttygnwefg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtdzxwyjsi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmauwdsvb.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtdtytkolk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtpjsybgit.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtsbucqozy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtjjfvnllp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtimowpvrm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzhyarhjv.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtlaknnzhn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgghtgdnr.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtfwlbbgbe.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtbxvhmspm.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtfvedcrno.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtuisbldfj.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtrczmjmqp.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtbwajngll.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gtwvwrtcpo.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtjfkkxpkm.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtjbqfhicy.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtpgjlgbtl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtmdvkbatv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtpemceycb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtzyrrlscb.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifvrwvuj.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtpbcchcxi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtnptrppbe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtkajycnne.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdrdxcnbx.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gttafpmicw.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtidzwpysz.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtlpygkjwb.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtxjrbxnyj.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtthpigqhu.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtjcolkzgt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtqeyhckmk.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtdcltmunq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtmfishdmo.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gttitwlvjq.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gthrebefhw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtaqyohumz.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtkfedwvji.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtivcgvmfn.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtesvpjqgi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtmsbicwac.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtdbbaxywz.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtfdxjgxcf.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtodsesiyv.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gtfjcnivfi.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtjvbsrjsh.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtcksihfbh.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtcbhnfrqp.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtbfricznu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtstfnrtfj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtxzmoctcu.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtpvhurhhl.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoooeqsh.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtmeibizaq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtiitjouvz.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtomtdhezv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtpqyudopn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtfrmuugcc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtyofgpupm.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzljqqeth.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtnpuogwuf.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gtesvrbxpt.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtmrgxhsun.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtrmeuxxko.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtdyiprbeq.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtewfttsfl.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhkfboqf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtkpytphon.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gtfrdutloq.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtnqwrviiu.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtxvjwotmg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtwrozgknn.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gthyptrtvs.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtoyxtcvcu.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtotgyievw.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtgbqjqkxi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtmimjvkuv.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbajomulr.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwkpilya.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtofflgvza.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gtumcwootd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gthzlhpkul.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtsalyljmd.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtpntccnhd.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gtwuckwzgy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtcxqcsebp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtyqynxcgn.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtsigpoqgl.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtnbsvgchx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gtztpbicei.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtirwbobzo.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gtomgutruy.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtzewrhmsk.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gtazpjdnrl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtisqmxnme.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtwuxdwelr.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsismeyn.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtfawcalop.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtwykkjlmj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtuvnkuyri.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gthkkowfdt.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtacltlyks.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtjnstevau.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gthhbhsune.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtslutkhow.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtekwaunap.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtqxruaysa.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtrllwgoda.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtonsarket.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtrkzigpjt.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtwftlcbtm.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtjnlmnenk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gthpxatzoa.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtzhukvvuh.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtetvzyjzd.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gthzuaidle.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtfjbrzfke.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtlvonkhrj.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcgbxsvm.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtfylpxzly.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtrllgvglu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtfljueyde.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrwhmpwi.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtpmqcfdie.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtvxavtkym.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtlrrgaymu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtsocazahw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtjaztzeto.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtngjahptl.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gthlupqbxc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtrwxzldbs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtyeggxhec.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gttaflwqja.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtijhipckn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gtsyzskund.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtabkmpwjf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtytxmirsv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtucbarscj.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtveiazyhg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gtznxlmpuq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gthcswbyni.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtwlqnuezg.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxlwmroy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gthwujapgb.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvgaimmb.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjgeoqpr.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtojuiyzmj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtrmviknnt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtxodvejxr.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtymdiuujq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtlhtqfkah.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbiahyxtd.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxcscuxu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmfnmucma.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtpspdtxpl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtfwweyyiq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtgqfmbsuz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtfgcpdtsi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtxwapzbre.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtptzevyvd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtetlzwaix.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtibhpyrly.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtirumjuqo.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gteffelkae.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gtpzxeqrrx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtveofqkvz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gteysdaomq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtgkpccniv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtjwqotauq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gtqpkiyzpn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtmewbcumn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtbrfvlheq.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtcnngldpy.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gtnqqmrsrp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtaoxjkrkn.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtcchisbzh.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtdxqgthdt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtbtrwhlib.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gttwhwjjuo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtnaoszwpp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtdkjirdan.html

[H04] 自定义异常类型
来源：http://dali.snrcjt.cn/Article/details/gtqzdxmwzr.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtpqcggyfm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtwvvjknqu.html


<!-- 参考信息 -->