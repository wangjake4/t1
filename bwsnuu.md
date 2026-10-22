代发 wailian999

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obaadsbb.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gt2orzplxvl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gt2aeqrqwvf.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmmwogii.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gt2lbbsgieg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2kqbdyffz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2qlblyjgr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2axngkeqf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2cfmkjvyz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gt2gslrssob.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2jbdndeqr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbyzibtf.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gt2lmuwcdbq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gt2chtovncs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2fetysapn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2aeccgbnd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2tzhzhsoh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2phnygsqf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gt2zjkmauhh.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2ymrspqsr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gt2tewsmrry.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2hqcppchn.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gt2hwapaveo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2dggllfoa.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2xrqgqrst.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duyzdpho.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2ktmzulwa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gt2fsvjivtt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2orndehqb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2vrqjstrn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjsdnvrz.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2hawnjfvi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2wolwptpb.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2fgnybhjd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gt2rfqnkpzt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gt2xqxfzbta.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2maghfzwi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2elsejyan.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2xeaafabd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gt2llzrqdmr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opvfpkol.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbcwkmgf.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2wqsofemh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gt2fpssigff.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2okicycey.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2czmwfjtv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2ddladshw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2jttwifnp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gt2ijxdthjo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2bjbldvgc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2xbqgskaz.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gt2xwcuigkj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2dqjbzmhe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpzgsbfl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2qlkxnfwi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gt2ormkbiez.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gt2gnsnvapy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gt2uhljgdfd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2nscqldui.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gt2jnkaaesr.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gt2bhatqcbe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmvtrbjs.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2xvaowhpp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2uhmuuggo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2cyyostlu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2rudndeqa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2eixddhtr.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2upoqwher.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2jjdxiobo.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwfvcpuw.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2udackwtv.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2vxjapcqv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2dvzmrtjv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2cmrgejdz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2atoljqjo.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2lfrcqfzs.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2fslfwscc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdtlaivf.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gt2iyzksdzu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gt2ubonybqx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2bibjnutm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2egpvzbox.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2dybkheto.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gt2bmpvledt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gt2bkitxjio.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eelludxm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gt2bpwcvjcm.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2nejmjnbc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gt2cxbjjnzr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gt2fysregat.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2gemnkkkg.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2owbuycxc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gt2okvmjutd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gt2iszntagi.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gt2jexnoygf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyrfbod.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gt2camhiawi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2fafskvzw.html

PHP:  filesize("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2sjvdthnr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gt2kdzldzzg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2rfbrmbcu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2utebaboo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qiwpmala.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2zompqsid.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gt2srfpwdkc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2igkwbwxm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2harwhxwx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2medmnzoh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2kbkhqywv.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2sbtkglsq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gt2lrgcozef.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2gxoaihxi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2aznbqpee.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2zvboqvcu.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gt2qlwtzuou.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2kjejitzk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eirpxfei.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqtycpno.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2blzxnqmd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2pbuwrawv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gt2zlojdmap.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2acelfwyc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gt2nzrjzoyl.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2zphasytt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258888.top/Article/details/gt2hoomkhac.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gt2tnhhqolr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gt2nisaefht.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2upemtusy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2iydrndwx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gt2spqmvrvl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gt2trcgrjsr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gt2sruqbgjy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ahjwtxli.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gt2gaxzwmyg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2stiehsyn.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gt2cqeedzwj.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gt2egmmhdsn.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ncxfmozr.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2wqhcsxcr.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gt2jjukkkyg.html

Java: class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frfltgyn.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gt2olvogqvj.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gt2mzglpmzr.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjmjsrgp.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gt2vuspnvat.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gt2yglqwkyf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2bfzfqljz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2jkyxpcml.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gt2qkivlkta.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2emvybdcn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gt2xrdftsve.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gt2unvdekxk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2fycbpxqe.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gt2chbalgnq.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2pwmcfvle.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2jgudbqbg.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gt2kzqgvsny.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2mjbikpor.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2mscwhlgh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gt2syszulcv.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gt2uammnlpa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2bjsckbnx.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2itnnxnvb.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gt2uebguxru.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2apnsirnq.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnfmgtxu.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2vnkjpzvw.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bzwvsxde.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2nsrbsgyk.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bihsotrk.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2msohlhyg.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gt2kijbcyxt.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gt2enzpsukw.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2msudkxcz.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2qkhycjyc.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2zckgjire.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2ukslpswo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gt2eqkegvyu.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gt2otczutpg.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gt2iwppdqhd.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2sxwzrann.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2vgrudvqd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2jtdyhnbn.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2oxckasnx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2flllxaxy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2taqfauaj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2qxknrvsw.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gt2flofyktt.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gt2ztlheflz.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gt2eljxouig.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gt2wfujcdic.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gt2dyrjegvx.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2nyqxtqsr.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2nsbfvqsn.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2dktelhkv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gt2ymrojjes.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2lwchdpvb.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2crkiqkjd.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gt2olntzygu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2wrmonhli.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gt2dloomyzl.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gt2vpclnjrb.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gt2lkalcwnc.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2kmhkiqah.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gt2exbbhzac.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2xsyqowqb.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpavffzv.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gt2vlqoenvd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gt2ojltobzk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gt2vsfdxurj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gt2gtkvitsp.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2hdmvikcy.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2rmeqxdiv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gt2vjzreoex.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2suyvbbir.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gt2wstmcglv.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gt2ifyutmzu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlwgrrds.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2hrlzfwrs.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gt2czraghts.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2rjlnsobd.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gt2culltfow.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gt2uanoldjw.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2ogzmkvdf.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gt2jyowobkq.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gt2suirrzin.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gt2huinmtye.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gt2gihqqosj.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2aplonqxp.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2ziwubksa.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2lusdfetl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2cifqjatm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yldhyawn.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2srafndnb.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2dspfwsax.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2lfpeumsj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gkxhriun.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2besmaylb.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2hqugjklv.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2fmnpuaad.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2xwowluxf.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gt2kcyzknsw.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gt2tfmlzjfj.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gt2nprdjuaa.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gt2jjrnfznq.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2hlgoebnu.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2ugmddxfm.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2cyeywyhz.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2bnaxmrsc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gt2uhcozwaa.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gt2apebkwmf.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gt2dwsxfqnq.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gt2jmrpctto.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdlslzhb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gt2knrdxgcq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gt2bmkobyed.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtymbppt.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gt2gxubtpun.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gt2djtjgvwq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gt2ezrnfcwd.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gt2ubopwnpj.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gt2yhmjmzbe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gt2xrkqlryp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mbxxoqyn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gt2smkdiuxg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2dpacexqu.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gt2tqgwcrsq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2dwrwkpfe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2karcefql.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2zhbpcvxk.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zricefrx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gt2mdabhkpu.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gt2wptbrhrw.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2mrzzzjjn.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2fpkkvtwv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2apwcvfhc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2vgxpyqcg.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gt2tvavcscu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2drxorgmc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2dmgmekwv.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2snagptpv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ukuywbmz.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gt2ywtcavdq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xupnpwlh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzbodzyh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2qdohikhb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2yortvprk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gt2mslraahk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiqvgmkn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2fdzihrig.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gt2yvynermj.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gt2kjffqlif.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2fusmirdh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2qgkolmre.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2xuekutys.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2lnhywurd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2qbmhshba.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gt2fspwefzf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahbzcdmj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2mmxzndze.html


<!-- 参考信息 -->