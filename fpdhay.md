代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2wcfdrpfb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2msqgftmh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2cqqsczyw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjkeyywu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gt2gzdvjvaj.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gt2ccslukdf.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gt2kmrtwsco.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2rdwhmsdq.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2enkpbvfp.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gt2wamxduak.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2mxgfrefk.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gt2fmzrqnha.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gt2xqzwlush.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gt2unxbunqw.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2dbsmqpng.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gt2zpcxxoqt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gt2rjhzzeur.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2lbomajeu.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqkebdkh.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esbcfopj.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gt2undwsipk.html

Ruby: if s.empty?
来源：http://dali.chenlongwang.top/Article/details/gt2wwyoqorn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gt2ufcvvgmb.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gt2znyczpwb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gt2hsvlhjmj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2eyiffano.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2lauvkolo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2jjonyqvd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2mgaqcqos.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gt2fmesfkbp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2tluavuyv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2fuldnfet.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gt2zykxzgiv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gt2truuhmrs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2znwixvgv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2uonkvmmo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhgfnwbb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gt2plxupkjy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gt2vzlklnxn.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2bpuvsszb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2exptwccc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ggfxfwdh.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gt2mxbpvhby.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2biyhyxzl.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gt2kiqlaoyi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzjmxdkv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgytpfhz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzwhwfwv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2ciqflhcu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2clypihkk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gt2tkfwcqbz.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2sfcbdpgp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2mxutmewa.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2owkdsqdt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gt2zqcvptio.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gt2wnoruvnr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2gbpwgnhh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2hneccxtq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2wasiprae.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gt2tlywooku.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gt2mofxomdo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gt2sbihpxpy.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gt2jyqomqai.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2uppfghtu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbgbaxix.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2adljuogb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2vzsruyzn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gt2sphnpvpt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gt2rjhsfbve.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gt2fiomkxav.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2lyzgnasx.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gt2fyrxjlbb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2wbjapjzm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gt2cjvpjura.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2wpolrazt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2nogtmyyb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gt2vyaudmzx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gt2tlpyuugj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gt2szakzuvk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gt2fzktdvgs.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2ihchvfun.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbvsysux.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2hyngsryo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ffngvcoz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2xtbvyfjo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2uynfwpvy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2ibzjksyq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2jhfrogqf.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2jbnoijwx.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gt2oncghybu.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2uuhunfmy.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2ullmrhll.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2cyycppwb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2gvmsgkoo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2bpexdeli.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2jfgiczfw.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2zfdwfwvx.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2chrkptgr.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gt2pcfvwnrr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gt2motnxrll.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqbgqoji.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2hdcwcczz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edrxvqct.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkzputld.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gt2fwqyudmi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gt2pdtdamzg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gt2ovwwwlce.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gt2cxbrfxyb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gt2yxcsqbxd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2etladypr.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2lwfpytuk.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2hzysqzgo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2msaewjns.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2assqcjqg.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gt2jwtjpohr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2zawbuesa.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2letjfmje.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2nfubltdq.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqqwodlw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2zixsxwdk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2zoytizet.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2zcpmwbkc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2zobfruvo.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ckmhnbtk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gt2asjgorrf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpswndfb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2tfzoidps.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2beyxvewp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2ervsbvid.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zovxmecv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gt2csdlwryz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2zauqieob.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2aeampjrf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2teiobkaa.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gt2qshwhzuz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2hbibcnkx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfgcmwhi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2flaogznq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2egtixqzy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmbilvhs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2bmawgrxm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2nxzwdadd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gt2selmwaed.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gt2plwlwdva.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gt2aswsxogb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gt2redbxgij.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2bdzbvzyu.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gt2deqmplir.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gt2qnfpcuyj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2bgvnsjfm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2hltqauxv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gt2niftirbh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2zywtzjnc.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2owhgnwut.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2nbrmfmsp.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gt2kgxjgykl.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gt2pzuriivw.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gt2hfloyxlf.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2mqlmrjfm.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gt2kquyulzh.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gt2fjgawnrl.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gt2kywxpdlb.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2yhbizfhf.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2teazwdws.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gt2oqywtdnf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gt2btzkhyhl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gt2tklfdwvs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2jieymogx.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ddiomqce.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2viupgljx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nygdhena.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gt2hhxckyre.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2kgunpnya.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2dghtqiqb.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2occpuqln.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gt2ojwzifzg.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnmqqmfe.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gt2ugzxrrhe.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gt2azbyirjn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gt2oguiqvmy.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gt2gscjjoci.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyogvybm.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gt2ryjzfrzs.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2ymtcydcx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2tzqxfghl.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2zkyfrlbc.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fhxyfast.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbgygsap.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zspasfwj.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2vbnihjcn.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2sdbjkvck.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gt2zxycyrks.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gt2zyozwpqz.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2wgbmhbfm.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2taadzztg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmwbope.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2usjfypxu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gt2zaqtgnjh.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gt2qvmjurqr.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gt2uquqwbfu.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gt2wmcrtgqd.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gt2wwvvrbgw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2pncyedub.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2cjlbwcmy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjsqabpb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2xiiaeiml.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2psozzflr.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gt2tygogvrf.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2ozelwcyn.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhdgjcka.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2odpmykiz.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gt2xkrlufuc.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2nueqjytm.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2ojrjxsqx.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2fqplostu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gt2sqejgser.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gt2mdhocyxt.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gt2nmghzwcx.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2cxnbarfx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqpwbtcj.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2tevhswcg.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gt2grbwuqfk.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gt2swbvrsse.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2xsbafbux.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gt2accjcbhp.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2icbzprub.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gt2trajbcqg.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gt2wksgyjmv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kedkpoff.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gt2tnxyfvpa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gt2eyurdfhp.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gt2felvxzcy.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2wfzmebaw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gt2dsjdings.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gt2glifaiaz.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2jkzbqlif.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffuyqcvo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gt2ijvrqpvg.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2fxhnrmqd.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gt2ygnsrzyq.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2vdiugqpm.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gt2cyijxzfm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gt2pceoigkr.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmrsfiss.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byoabyyc.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2cryvlqet.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gt2pahyrxno.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2bzgiowdm.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ahqunzej.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2smwldqpm.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2tbpfbnjl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2bdotkrza.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2yktxykev.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2qmcohxul.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ecfkxxyw.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2qirjcoex.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjtmfqhn.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2gdjapwqz.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2nuezjsru.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2jythnvpu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mziooemq.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2zbxwrcht.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gt2nvwptcgc.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gt2fwodigxt.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gt2tbfsegnc.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2ddodalar.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2ikwftdxq.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdrahviu.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2cqikjewz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2zpqaaqhg.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gt2cssmluxh.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gt2rhuayckb.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gt2qfjipseg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gt2twryencr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gt2qjjfaayj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gt2asfonkdu.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gt2fhvzambq.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gt2ovmkxtbf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gt2zskvsvmh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gt2cngexhjp.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gt2gpfmjlki.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gt2hirlregb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2pzjrnqzl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gt2dangppof.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gt2leyelatm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgemporu.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gt2dipmubqx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odiftrrh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gt2gqddmifk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2yildkvgi.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2bsdadlvd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gt2zspqunnk.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gt2mxhltejt.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2kdqowqon.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2xvuohvoo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2zgnkjmel.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gt2sicsuzvn.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gt2bbnagqpr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2bagasqxp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2fxczzqln.html


<!-- 参考信息 -->