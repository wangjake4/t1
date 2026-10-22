代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtmciwpoem.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswmnarey.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gtfkpxjeku.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfroakgob.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtefnvbxzn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtxsdmukhp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtrgtuqbnn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtlzkoswxf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtgtjzstkq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtnkcoqdwi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gtgpnopjsn.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlylxceay.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtadcaqtcf.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtqdawbafq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtgfjhfomh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtqqcafbih.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtrgkcgcvj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtfhfpudzs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtmhsognob.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmiknfbck.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gtwbyrytey.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gtijbhkcwe.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtwpymyole.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtwgbvpakt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtblzthobj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtaxvkmfif.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtulozpgpc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtpfxcdsaf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtmsdgoisy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtumuqyqse.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtvkwkefxs.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbsfgflb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtyirtqe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtamhunaip.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtqkspgqrl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtsqxpulks.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtsusvthmt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtaqgugrwn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gtcsbnrrta.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtwpqmlltn.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtzrbetlru.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gtbfsokfta.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtigluzkvh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtuqkrzbex.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtkirkzzdp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtzqkpmntm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtgtemlybe.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtwntupvqq.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdurbnkjf.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtnnkhmlwa.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrufmnggw.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gthqjcrhge.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtceofixox.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtskawwwnm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtqgmfomxz.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtnzepicnm.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvtbzkjmt.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqnnrcaqn.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gthbuyceuq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtedtywuno.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtnnqlbsta.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtvdtnxfyu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtooacwzrl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtdnyyuqcs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtpueerhkm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gtdrmffjvb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtzqszqbdb.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqcohnxn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtclntsrxe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtarsqkajm.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtfsxtpiyd.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtuxepioly.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtskxskawo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gtzqbbhgek.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gtlepubhtd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpxoxpcz.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtzntgaxrp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdwdtghki.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtfizhpsfk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnaumhny.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtfretkglo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gticjeembn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtrbogpemj.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtrlhgmron.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtrbvuhbvh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfnlrsdh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gthvxkuyhj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtwukchjgc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtncplexac.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtucjcqmdi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtqzahlmst.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmnjpshi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxzpzxnl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtncmrlbfq.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtfnzuftan.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtacccdzmu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtizfrpqnn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtyosizpjt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtbulfuupe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtsmilutnr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtfqssgbfy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtrfrfosof.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtqatpfznv.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtwktgnezi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtdiutqils.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtudwelomp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtradfkyxa.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtclkfzrqj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtfrbaptvr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtubiuncdr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtkqhnuecr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtuwzhzbng.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gteqdejpjj.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtotfyuyvz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqdjwlnix.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtdwznyyza.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtngscdegt.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtmfvhmfyd.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtiexpmfci.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtrvxsgfzl.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtlroavcbk.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtszmweswo.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gtwbesllqt.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtzbzzlymx.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gtrwtkwyqf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtdgakyvzm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtkqcgfihx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gttgdgaxko.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtkqvqujco.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtddtobacb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gtxuvaouww.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtkvowqzyr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtdbskvejd.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gthtggixha.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtqauviyca.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtdkqjrsfl.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtfxyaqszq.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtdyecpclh.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtavwqwpet.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gthxaaqnfo.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtjdexcsvn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtxvuwioas.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtizfmiucb.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtgoyztvaj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzgkjgxn.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtdspfpofw.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtdeinqcwd.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtuqghhegc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtywmwwady.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtwpbhhtoc.html

C#:   public string Greet() => Name;
来源：http://dali.jqgfzy.top/Article/details/gttghpedoh.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtymoiuivx.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtheptexik.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtknljytip.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtmmollztm.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtzjchfhvf.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtgavimrqp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtlxjkqija.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtyzesjjir.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpradcjvj.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtliricfct.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtgzncrwfl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gthwgworvh.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtiwctwggu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtgkqqugvd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtcboorwor.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtzfteofio.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtycowsogw.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtpjioikmk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gthurktuzv.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtqpflsznc.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtboevlcqj.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtgyplwsss.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxdefzot.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gttdjbpnba.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtccaabtpu.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtbvxrydmf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gturjrzkjs.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtullpvqpt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gtrfebmyzc.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtvyutcoow.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtsvtisaqi.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtsfebhdhf.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtyukiphmb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsogcxim.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtwiibrsgb.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgjflzlmq.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtypxxcvnv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtsmudbxxj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtldfkbnwh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtoitaciza.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtfjhuhnrv.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtvehizvpj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtfbdfmxow.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gthaqtzvsg.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gttjtfkqsh.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtdvqwvqbb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtnksiywia.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmzcgecv.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtbwhhejum.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtitutpdhj.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjeeotjx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtbilhbjbn.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtbgjwcuge.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtdzezqyzt.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gthojetpkx.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtutcfoegg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtcbynibvh.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtfxaadaej.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtituyiivf.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtihhsojzp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtueljryap.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gtnczgtcta.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtfdimanez.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtbtdveler.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gttuamplhy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtknbunigf.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gttwzaztep.html

TS:   toString(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtsvijgszg.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtmlccxvaa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtoyxshfpy.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtrcootqbm.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtyybfeuky.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgutphdmz.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gthpqtcvne.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtdlxifmvu.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtvwgzsnkz.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtibnzouoi.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtulhevrkd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gteucmccwh.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcozckso.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtdbhwhgeo.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gtkpazduea.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtkmbcqemy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtahpztwfa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gttsnhuuby.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtrnculfom.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzrohydkk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtcagvvwxw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtsdlvycee.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gtfnkarnno.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtzmjcldti.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gtmccftyuz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtfxhmizyk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtieycohlb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtujznmxxu.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gttwqrchin.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtchugcrpa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtayayvikf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtsfmgimdn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtxiamfmjb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtmbomebtb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbpgcvmf.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtxkvidhcc.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigplcwuc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrtesihs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtvayqktrx.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbjupdcc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtfvwbamfh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjlowhrwl.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtsfuoveiq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcyrrnwev.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gthawppzku.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtquvwqgdw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtreyzpfua.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtidnbwzxx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtwrhrlokg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtiusxiqep.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtclnnelrj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpitlfywx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtaleguwex.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtlewxuyux.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtrnwrkjui.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtftfafgsk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtjmdlikbu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtorfgbmee.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtmuxfvtsk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gtzfqjxcpi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtyctwolda.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsfggqaj.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtmjeutfum.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtrlqompzv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtxfhnrdfi.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtzbywqeav.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtcvhqgqpp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtfivyjlup.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gtyiwqadlu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtezzitxfc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtqfnbpusz.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtsyimxdmj.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtckzobant.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtdomcfzoz.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtnabfkvyi.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtabemgnld.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnybgwepb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gttkgsdnzr.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtpyqxljpb.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtasnddykf.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtjtzogmcy.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gttaxxkjsi.html


<!-- 参考信息 -->