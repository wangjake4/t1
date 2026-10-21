代发 wailian999

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gtpyekijtf.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gthffcqspo.html

[E20] 判断字符串是否为空
来源：http://dali.smart0.xyz/Article/details/gtwqvqepco.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtzwxlrpxh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtcubeswae.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhixingplan.top/Article/details/gtzhhkumje.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gtcbjchvvm.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtbchbfvzn.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtmccaofka.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gtplgigwlw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtppgpntmq.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gttzdwjhhb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gtrszmcjlx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtwjuvyysz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtbewpnzjs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtjlfvysyv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtblagtfmg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gtxtbputby.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugvnyrad.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtkanprlqq.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtcorjzuwg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtrhlasxee.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtaufjmdsy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtyhrijrxv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtaeupxbjw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtplynfkyy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtlmvwvyva.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtawepbldq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtebnenapi.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvfxjrujk.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmerconq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlqommlbx.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtzjqqhwwz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbytbghlp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgqohapus.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtxgutwdos.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtqebusrat.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gthxmahfoy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtxamxcihc.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtbbghozni.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvoiscqp.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxnofwsq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtqqvzqthi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtmbbsmoqh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtrfufxjwi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtfldsvnne.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtzbpuvlad.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtqyheqvqw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtrmzjwwdx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gtblcmgbbi.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtxzvcucsm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtfgsvnjjz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtvnqrgccc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gthxnycmie.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtorujlekz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtwehnhjkl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtedqplyfk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gtgyecyzpp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtiuytpvcn.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtyggvgsgl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtzzlnkirt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gtcyigskpv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtpikxuyzv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtksynseqh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtcqjqfxfo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gteijwujwa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtxsnfjlbw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtvfyoiqhz.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtnofcrhkz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtqgicgjge.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtymxjihfy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtltscdkft.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtlurgpgvb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtnfrjqids.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gtukmnsdys.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtraskxywt.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gturvpkyzc.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtoltdllja.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gttrwyzglx.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gtoymcmdnk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtagvccbqg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtwbddwkux.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtxfvzjwmt.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvkkfgrcb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtgytobmpy.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtlhwiufmw.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtfkyfcxmv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtakdieljn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtmmvqdmhg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtkrzsxchw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtydmomgsp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gtfatglbvd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtpuktiziy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtmrdsjutv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtobxlodtg.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gthbliyyfa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtjoyyylpf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtagzslbdj.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtufrwaexh.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtnhmovtyj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtkitdcwqh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtxztfkrwu.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gtinenoyjw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtycbmcswi.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtowjmhpxv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gtoxpdqcas.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtbbcjbtdw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtzkjrsmzd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtfccjkdni.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthapercvl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtpzykwgzb.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtrpbokkih.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtcoyqigqs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtlexhhoby.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkpipjrlt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtjmsxnczh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtapvmfbos.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtxsgmqogp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gtunioiixk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtveabkodx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gttbjbgcmm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtswcnkupo.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtljtkqgws.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtrilqiubi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtzxmskmci.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtnatonjfs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtfocemrpl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtphdwdknu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtrwolpzll.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtayoxqjah.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtnzlfvlpx.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gtoxtgmmof.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtqjfycuhh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtdgbwuayr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtogcmbnxd.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtovaznpxe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gtnrcssxjp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtozhwdvdt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbsxmwnb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtgudhapyf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxyjruqxz.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtgruammil.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsovksocl.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtkqkaegxo.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtdpebukul.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnbjascli.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtktcojyso.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtoqjxlxkz.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gtqoirdlzv.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gtrjqjrxwp.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmijhnih.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtnpiilqjk.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gtltpigprd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtweagrxwe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtuwngjxvo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtuolilndf.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtyecjnwef.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtspzipowy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvqsievk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtjdxoayku.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtruavsudi.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gttdkkdjuo.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gtbbtrxyjd.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtgkukdoma.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtykltrgnc.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxvyrydz.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtjvsogxbv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gtbpykplmg.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtqgbyspph.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtvgykhgwe.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtnyklbejd.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtribtkcqr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtcegtoisw.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtebclyacm.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtzrpqowjt.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtvdzjpyjm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtwnagbmjc.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltbgruse.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtccvxwsqg.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpikyuxz.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtcwcbzaqu.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmisthgf.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtucwntjto.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzqqfkdc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtwauqlfdl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtqvmnfjnm.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtguxsmtcb.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtaqbxjozd.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtiqrmrlsi.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gtojvxorce.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtbcslwavm.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtiafvzjsk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtkcovyeti.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtzamchrcy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtxsczzhga.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtidffebsa.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtmogrngpj.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtbrjkifyh.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtkcsebbnd.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtluicsveb.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtzuugheqg.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijreivld.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtvinqzcvc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtiphimpxn.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtvpvjcbpy.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtzfwrtbhe.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtlweqqwwh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gtsuxoepqr.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtsckjpwen.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gtzplbjklx.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtobalojwx.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtmlqcewnc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gtmrytfkqm.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisewwpvp.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtafdwxupj.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtdautsjkw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtllhlyyaw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gthomukpwa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gthxqpcqyv.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtaegzzrsv.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtgxgkbwna.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gtdhlcpwdk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtearmtprq.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtbtecajno.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtnmxereff.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gthrctjeto.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtdaadvbkw.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtigfqlhvz.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsamyfeph.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gtgxrxdekd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtejuzsclq.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtsbrfmgvp.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtacvhgeli.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gtwtxdsbaa.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtvokdowpp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtrrttnyev.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtxlwyxnjp.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtongbwulw.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtucayfyat.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtioazjqul.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gttxmpoohx.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtezishzmi.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gtvxymnuoz.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtjjbvlfgv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtrdzzgshn.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtyrwoiqpf.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmrqntut.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtcwjrautb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gturxcdtid.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtqaiqljmx.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtwsxeammk.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtmmyjvtbj.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtdwivncdb.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gttxreorsr.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtntpaeiqm.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtfpltkmbc.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtvcuqsudz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtyipiaogu.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtwtdwpk.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtymfyexde.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtienxaqpq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtkahurubd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gtkkhsbkcw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtajthvmcz.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtfscsjzoz.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtboovnjmz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtqhfbancg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtyxpqoyps.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtifyjmywn.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtngdrajeh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtkwuiiiam.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjqhsoxs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtxmofaqrd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtfyldruid.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gthwbcdlzl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gtvnuuwjko.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtngdgqzjv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtowshgxtc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gtiopnfswj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtgxhrroes.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtmlgyxfnh.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtuixmakcz.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtxbibcwyk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihqkoebr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtzhrslcqx.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtxafoucjc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtuefseaos.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcetznzlm.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtktxkuhap.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmwixugtj.html

[H01] try / catch 基础
来源：http://dali.yvedp.cn/Article/details/gtupqymrnx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtobkwuvga.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtgsmopctx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtwdijhlkl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gthqziowkk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtnrrievye.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtkeuobcnt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtdiatypec.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gtucvyqjii.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtsbmgfeso.html


<!-- 参考信息 -->