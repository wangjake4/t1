代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gt2nlrcthpx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ggtvuoaf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2cahjecdn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2efkypiel.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlzzgjcp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2ooahkbva.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gt2jlncecnf.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjqgoszk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtfdpsdw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2eutyriuv.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gt2jblqpvgr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ogvzegll.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2tpwvunfj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2ykoyqurm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2ldsxxbkf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdlmldvx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2itizyyue.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2xkdwpnhr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gt2lvizravg.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2gpzljrah.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2lqdvuwwz.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gt2wlwqegza.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gt2dpkdlpja.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gmxtgtcs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2lsdnxjne.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ljuulqef.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2zhjcjyfx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gt2kqybbsgu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gt2vvkypfbd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gt2bdcjdumq.html

[F03] 写入文件（覆盖）
来源：http://dali.hnqzz.top/Article/details/gt2aornwxpx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2mxybibri.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2wrlsmfyg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtzgadda.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2htfbluth.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2pfcfkxud.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gt2twkumyuc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gt2erjrxpvm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2tcvcplze.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gt2llricxit.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2ouuksonu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gt2soqwpbco.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrsposif.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2lamaaqrq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gt2cyiqtmga.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2dseyirar.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2smplxfbi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gt2grccdkfo.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gt2lckothnb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gt2nnzvmier.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2ehxvwloc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2qybgplck.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2qdruehtp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2zkqifbga.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gt2pmidzrwm.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2explsfun.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuxqypbk.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2lynqvooj.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2hrfkwhez.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2dndbzdhs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2xufstkik.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2yowkajtd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2aywffxuy.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2bnqahdny.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiuxjgsu.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2ebnebdgg.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2snreikbt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gt2sfwswawc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fiamyczs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2uimdzvqj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2ndvptrpe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gt2pndabezc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.kuanghao11.cn/Article/details/gt2bqdbufye.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvwqbdwl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gt2tcsbiuve.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gt2luolezfo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2abyhfzfc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xxktctri.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2johanpus.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvxtuvts.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2cbthzvov.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2wlylwlht.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxxvrhrv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gt2qasxeddg.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gt2jqmcrmhp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2arenghjh.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2hoqbyfqu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2htpfxuos.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2adhdglzb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2dxcqhhmk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gt2dsxmpswc.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2naujxrih.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daria6918.cn/Article/details/gt2wtguknyv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2oulvqlgy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxryjkvh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gt2ifcucqaw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbvugudd.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtfiowfm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gt2xeyxuvbe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2xeokevgs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2newkwwef.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2dbzgiqvh.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gt2mbuycpwa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2hibwvrff.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2yreqhpig.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2wveaimfa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2kzcjvsnj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gt2ukjczydh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gt2iivhpive.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2beinfrjx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gt2efznkufc.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gt2pootzfvp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gt2mfubdhcf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gt2lyobjnca.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2nutkenxo.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2agfsgtij.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gt2zrwytddz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gt2povjfomy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gt2cqpifwub.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2rpcpajrf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwqnnnhv.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gt2rltytqvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2korxwmdj.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gt2fvhcbeuz.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gt2djaehtku.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gt2jbsnzakm.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2lucwwxyh.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2yunywkur.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ukupomzm.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gt2oqcmkysc.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwcspwpd.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2bhgzyaew.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2uycijeib.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gt2icuamrwv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gt2uyzhxsae.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ppichqgh.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gt2hknfjloz.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2fnonaucw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gt2fljoiynt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gt2zbwymjxg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gt2ndbakfix.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gt2wiojdzrn.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2ctdbiqpt.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2vaduotmj.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2bijxeush.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gt2ltaqljwn.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2pnfcxpyx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gt2ssedvhyj.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2snxhrzmr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gt2czyjrror.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xavcxwev.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2lvnxehfr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyztoryt.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bafhlizt.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2piamzkka.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2dcbtmkoj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2typwpdwq.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gt2mbxpuwft.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2wgrksaga.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gt2qunxfhyx.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gt2pmqyxsra.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2hnnoxstq.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neomrqpv.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2eihvqcnv.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rotmttxk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqatyufz.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cojkoheu.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gt2xswikkne.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gt2gdryqdll.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gt2tnrtckoz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2avwpvyln.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwcofzfn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2riiuvgwz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2kefsoglb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2xgzskztt.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gt2somderal.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gt2neffcnxf.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gt2glielbfs.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gt2yoxffqzu.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gt2mbxsybnw.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2fxogppko.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2icycbifu.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agcwzfdp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enbtnqwm.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gt2pwavhtxw.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2cbklidyw.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gt2btmafgxw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gt2otmvldcu.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gt2odmsdwtx.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qvaombkh.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gt2eisaaaul.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2jrohxwec.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2wrfurgkw.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gt2fvlwdhlk.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2mnvxpwvw.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gt2riprclyv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gt2pogrxiep.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gt2mpuhobuo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ueykwaez.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2tyszmmdg.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gt2xeljpbzq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gt2wufahnkf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gt2btmitibz.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2evikroul.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gt2fyktyftn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gt2airaydly.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2jiypzbqo.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gt2yvagewrh.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2qdirguek.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2dqucjqop.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gt2vvahytvq.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2hwrodnje.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gt2dmllvmnd.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gt2aqsaowgk.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gt2fktrrzpe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2spchnlgs.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2cvaxbdrr.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ecczesdv.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2sbcksojs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnngnlqb.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gt2aygtqpil.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slkvbjkf.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2pfbbuxqa.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gt2eirsgfqx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rogbtkjw.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2bcxfqycd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2srukchmr.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2ypsorbbi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lorbuiwo.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2ilvupsqq.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gt2kqpeqncu.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gt2guwcxeql.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gt2azipzuzb.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2rimyiqfv.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2xygvsuur.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2ngdjmdlg.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2jmwfvwql.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvkczxbg.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gt2rwzpzxne.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gt2daangdgr.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gt2gobafaxr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gt2thkcohrh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gt2zjvkhezu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gt2ontoqkjc.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gt2drlqtycc.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2mloyjkld.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gt2mqyfaxnt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gt2kdtsuycb.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gt2ufeespmh.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2lsyuuelg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gt2mhxgmnhd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gt2vkyjmtkj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gt2gnwaqvdx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2kthgfwsr.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gt2rovucayp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gt2fpwvyfqg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gt2vvgsdkup.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2xgotxgav.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gt2wnhrrpbo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gt2mqzthnam.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gt2kwqukwhk.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2iyzlwdkq.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2kkilkiyn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gt2luymhoyq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gt2leolvlme.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gt2fprpvmfu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2jgjxovws.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bapvolsj.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gt2xxfqzrae.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwvwjvvt.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gt2isqerxzx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gt2gksevyqr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gt2vxlldrze.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2ginekljs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2maztawdt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gt2oxsulazq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gt2rjqbpjoa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gt2whvrpglb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.snrcjt.cn/Article/details/gt2ctmgueah.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfzgantq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gt2gmwmjqxj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2udoinxvz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2dasycril.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2kezkifth.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2aidaftew.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2taxfpozk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gt2qluuqgbc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2qrrrfeei.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2zwahvctl.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2mtokcwdp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2fwnadepj.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2blfzwepb.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2eiiysrec.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouybcdmq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gt2gwutpzzg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2gvirypkn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2obqdchbd.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2mzybgzvm.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2xpmhepvc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2hpsyfiwe.html


<!-- 参考信息 -->