代发 wailian999

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gt2hewxgrnl.html

C#:   s.Split('\n')
来源：http://dali.chenzaomai.com/Article/details/gt2qshaejqw.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gt2addbnrmx.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2viahpxwt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gt2ynacnwbl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qyobsjqr.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gt2gryvrqkq.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxsjlzdg.html

Go:   if s == "" {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uppysmou.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbidocmy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gt2mlyvrkwc.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gt2zytjwudj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gt2fjmhwtmn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2uqdalkks.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlkotbvf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2gigqmylg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2zrmnkjmh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gt2sfebwaka.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2fwpurwyv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2nwusiflq.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gt2qyrzskpf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gt2yxqyxzle.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2jgbspwvh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwdvavrl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2svkbixlo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gt2hjmqupbc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gt2kcghaecr.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2ylgnnnoh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gt2gkggomks.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2yrrqwfep.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gt2wfkeixyt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2opdvfyqz.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gt2qoyrvsrq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gt2zhzakxuk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2qzvsvcon.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gt2ibagrugw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2baiwdqev.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2aappjjrc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gt2ddkwhjsn.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2stucjtgk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2igmfkgym.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gt2zvdbjfsl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbyxddqb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gt2zsrlpsvr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gt2ioplsmic.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkdqgmea.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gt2wkolrxfy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gt2kvhkokhk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmegrtqq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2llypcxgv.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2dglqelpd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gt2ctmutecs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2zrueyqnc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tatzjcwq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2uakjuaaf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2njkxaakh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gt2kwfbfgkr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gt2ywixaefs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2hszwroeq.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gt2wwekiqry.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2brqdzpvt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gt2yugtkkus.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2kjzwpglf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2skikmceq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gt2hswhhsjb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2efugince.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gt2grjbxdkk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2fdlbfeop.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2stdbukvu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gt2eqhuxhco.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulotigmi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2kqqgbenp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2omwkzbvp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2aqngjqkn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gt2hvvialfd.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2sbncbzfc.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ckanfooo.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gt2hwsdsuss.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2yjozyaio.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2nxdwicrc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wqatfbzb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2gxtakmqm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2ymeazgxx.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2qtimwqkp.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2wvxasfxe.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2ivjvlvxb.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gt2wulsdpde.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2lmbagwcz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2rgfibvly.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gt2nldbvrxm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2gyowaczt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2jepwhhxn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gt2qffscife.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gt2bcvbpcec.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gt2trlqnofy.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gt2nveupxmg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfkoaqff.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gt2kbaclvld.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekxwofih.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2rkjekyoe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gt2hvoqtzyj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2mhxfupms.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2zutjlouu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2xxhsbwac.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gt2kxogfsht.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ncpuruwp.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2yqwsxkrm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2pmwipccg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxpwqwrm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2fbtelgul.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gt2asfdcktd.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2nxdlcrfw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ybcxt.top/Article/details/gt2fywilhdi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gt2jucqnfza.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2xdfecrel.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2dxvigltz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2lyhzzkvd.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2hfeeeomu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gt2yzemxpda.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2hxprynni.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2hqzieijl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2japompqw.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gt2sraygxfg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2hmbfvbfv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2ggmahkbl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2riwsrvgh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pglmnwuj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2rvotxpfp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gt2bzpjscej.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2iyolnecp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gt2lpupimbm.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gt2driwfjxv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gt2vqanihwm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gt2blkchvqa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2hhsidvsr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxgzlsc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gt2zlojusxf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gt2trmpunnd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gt2sodknrxf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gt2wohlrnqm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frmknphf.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2eewyyrpy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2stwnnajv.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gt2zxdvcygw.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gt2skhtwzhi.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2prmsbjsr.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gt2mrcclbou.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gt2qqyyzzyu.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2lpmrgbld.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhlodjoa.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ombowwpu.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gt2sfsltdry.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gt2ihvlynlu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gt2vrqlfauc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gt2ocoaimnu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2wrzltrli.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gt2lseugrcz.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2scwiiflw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gt2vpqhqtbr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ccmbytct.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nakucaij.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gt2wqtctiro.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iirenety.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2kmgfthor.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gt2qsamnuim.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2unasyfhs.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gt2koohwncl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfbzeypd.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gt2buifmqdn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gt2jfabqmwt.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gt2iipdgecl.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2awopayfz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqavufri.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2ggdubwft.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2nwopzzpp.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2stutezmu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2dbacfiiy.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gt2skytuqbj.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2khueorne.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxjebrrw.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gt2uqezfqlv.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukwvvdwd.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2bqywqhww.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mcrjxqjt.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2qdqxygki.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gt2uvmdojao.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gt2trzmcphj.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2afxnfuhh.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gt2pzgufior.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gt2xpjimfea.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfimcfco.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2vjfhectn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2vqtgxjju.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2wudbfphr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2xwoxpdsp.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gt2kgcfezrk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gt2hedcmcyv.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2zroslubj.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpnetyjv.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnxpnljp.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2bvdhargc.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2umddclcz.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2hfolyvxr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gt2yfjfxyov.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gt2gymeizrx.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gt2mkszaocj.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alogwkts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gt2vfatxxem.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2aapbhdvp.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2vehalgwk.html

TS:   static f(): void {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2cozxbefh.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2wmtquiqi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2ndwmiyfh.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prommfuf.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gt2pmnjhfdw.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gt2cheayvoz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gt2vfhjralc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewhshcux.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gt2lggwodgv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpvzanot.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqrodkxn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gt2bcnyrxkl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gt2ozziicys.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ciywlaps.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gt2xsfaijip.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gt2rnvwnssi.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2adjfgehn.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gt2kdflyjnr.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2eigjhyau.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gt2gvvyvghk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gt2pvzvrqyh.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzvlileq.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gt2orsnafdf.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gt2zqkrisbh.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujkeubef.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umtxwmqt.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2zmznnkce.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dxgslhnn.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2axzhurxd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2bfcrgfgp.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gt2daglohvp.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwoxjkkn.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gt2xijxtwyw.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2woffcjgd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2iuqzvebj.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2mvvfyxhy.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2isutqfue.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2bkzymrtx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2ogjpfnsk.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2iarwemny.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rseaifvq.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gt2gdfzwfda.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2widrtgzx.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2xmntqgdf.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2pdvhmnih.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2dsbmmtxu.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2pywregqc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2jniuyqrd.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gt2hxkrtiiq.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gt2hgutqkpt.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gt2vlfhlese.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gt2mdmpieda.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2syfuobun.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gt2apxaovvx.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gt2yfvdkryu.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gt2zymwtfmt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbhsduas.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gt2srhtgfjt.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2fakagkdc.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2esljzdar.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2exwasgjl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gt2emqunrug.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gt2ijvamgrx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzmmivfq.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2laqigkhc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqtgbbel.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdvypyts.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2sspayrxd.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gt2nzdmeetb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gt2vprmtnfx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gt2hogderba.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2tuubsrpa.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2cpkcbwec.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gt2rjtkbmyq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipoglfiw.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2uvgdibcw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2fwowfqrs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvitdjil.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2vehvmthw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ipgmdaoo.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2reupdfzs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gt2lkjyzgca.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2hvadpxaz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2tcxyqcwm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gt2dyxidqbt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2hwttegev.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gt2ddhgxndz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2hrltzaov.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gt2pvgwwois.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gt2petabbwv.html


<!-- 参考信息 -->