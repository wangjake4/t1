代发 wailian999

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gt2gzpsssch.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gt2iufgxgvo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gt2xxxqecbp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2abqpibsw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2oaefetrd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2lfrjzrui.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2dfutxztj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2ilvhkmbo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gt2vabfcpvc.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gt2gilsnjsd.html

Py:   s.splitlines()
来源：http://dali.daxiang520.top/Article/details/gt2duyaoijb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atkadkia.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2majsowjg.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2odpyrhax.html

Java: s.lines().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2kvtjnvmf.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xemfkacj.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gt2bvlmforq.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gt2xdfjsjll.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gt2jeqffkxx.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gt2yrgetaua.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2hsuhlmen.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gt2vzhyqafj.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2inlidyog.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2visphoru.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gt2vjmypqmv.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gt2hgaxzcrk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ydvoqfca.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2lovbokdf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gt2tzsdavsg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrimiox.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2umyorfra.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2yycpugyd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2qkhlfprs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gt2kigxwpkm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctuzssnl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2gwjgrmtw.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gt2ejnyslct.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gt2kuvnfqhe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2nztizupc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2bxzvfyxf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gt2pbnbxzvm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2poipsmyc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gt2djosztrz.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2kiflprzo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2brlngtqb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2piafwhur.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxehzfek.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2kemwjocr.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gt2rtyfsubc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gt2tddkicdn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2wccpkdqj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gt2mhxpmnzd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2qqlntngh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2eydasakb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gt2cwmfkqlf.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2fzxmepbq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2ydemyajx.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gt2qcscttre.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gt2vjfblwae.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxukgokc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2mkhczpen.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2esuptccp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2fustysst.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qatbjhjf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gt2uwyuuace.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gt2yzosmwbm.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gt2yzgdidwe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gt2iroezpaw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2loqsklkf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2zinqscyi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhkyuglu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gt2unetvpxr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwguxclc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2hrttkkak.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvjcjaib.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gt2sbpelfhc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gt2scwcppiw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gt2jzrycnuf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2zkkcdtlp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2ntihvjxk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gt2sklcagcr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2nedzbfty.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2xbgmdeco.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gt2rrsgcpom.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gt2cccbqaon.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gt2ulqukkot.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2svkmblsh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2syjzcpyr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2fohvbsts.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2pezymttv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gt2odlbpaop.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2jdjoubeo.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2grrhbbtp.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gt2oisaacqz.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2mfnamjci.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2lbpqejrf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2twpkhzvm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2qeojyzsx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2fnmpqtaz.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2vweenoas.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2fnarsxvo.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2mejpmkwe.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gt2oubfmtnz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2ubqwzhrk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytlykjlx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gt2bpszylyw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2dudyanlg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gt2rhuwhmnj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gt2tnjlqlod.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gt2svafxvsd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2wnzgcxkg.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gt2mjciopkb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenlongwang.top/Article/details/gt2qzictazo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gt2zfpdslol.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gt2jxcavazp.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2ijmugyyh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gt2oeyxsdfx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gt2jcnprkhs.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2wpzlzgzx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gt2ehfmiuzb.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gt2lfyarwqk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2pxzqwgks.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2nrkkpjxl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2qzgjwbla.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2yycudvdp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2djbuoqui.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2ksozgbjt.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ocmxwffy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gt2zsbihnwn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gt2oarxcclj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2pizxnyhk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2oqfjcdhg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2powsnvfd.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2qegjlvss.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gt2exbnpuuc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2jpizonqm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2pfakjovf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2wtrkeapu.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnmxaniz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2tyftawlj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gt2frfumxst.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2kvgutldr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2eysizzer.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2xobysdoj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gt2ibcpbdcj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2wciuogbs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2pqlykqqx.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gt2yrghrxzl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2ptveausn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtesaouj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gt2kbuchsmb.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2qyjxewso.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gt2hyokqvoo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2vhtvbqtc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gt2vqpjcnnf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gt2oyxpyvji.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2djfhgmoi.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gt2nsnaabgr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2yzcvghkz.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gt2wludaoza.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2fzgichtu.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynwxouwu.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2vbyvxnsq.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gt2gsgzluaz.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2hfnkkqty.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gt2ngbderrr.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuznbujv.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2hrvqgkxq.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qquxwfdv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2nfkjetlr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gt2oogxzadm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2okgbnfgz.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gt2sluvhnsj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dfdrldua.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gt2dmyivqxv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gt2crxsryyf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2enlhhyfp.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cspslkfb.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2jsyqdhen.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2kgdccven.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2ztflhkqe.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2ypeixogj.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gt2smclclsy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gt2niaggdiz.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2emnoikus.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gt2vsreynus.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lnllczop.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2tjbhxohk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2jlymvuqk.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2ppizxfyw.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2gqdouhav.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2wjidhkdi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2joznjydj.html

Ruby: def greet; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvazjrkf.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2cevaspco.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gt2jthxcqxq.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gt2jwyhrsru.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2xwjcfycy.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2vqhuzsjj.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2winlwadb.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2dvcfrmny.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2igcnhjbq.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gt2flbvjxqe.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gt2wjijyfoc.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gt2ienvrqeg.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gt2dngadglz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2epevvgjl.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2npoqoxuo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2vzothkga.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxgweuiz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gt2qokthoro.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gt2acnpconi.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gt2xbllpalq.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2reozdeil.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gt2rnqlhbja.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gt2ipnysbts.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2nzdutdaz.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2zivfnlxy.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2dlkloigs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2ritbdyal.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gt2hpaooyvw.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gt2iknwevnr.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gt2mgujnkcu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gt2gjwyjrgn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayppmqmr.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2ecjuzdpm.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gt2cwvolqsp.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gt2hyxltcqs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gt2uhxtthtn.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2ijmdnfmi.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gt2oekvmyab.html

[G09] 接口 / 抽象类
来源：http://dali.hnxiangtu.top/Article/details/gt2knvncykk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2zsytawea.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jaemzwjg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2lecqjqrl.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjffgtwl.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2okqahkvj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gt2hmfjwuvb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gt2iynahewl.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2mozuunid.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gt2heryzvzu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gt2ngtyxwok.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wutuiktm.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnlonwjg.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgynvvth.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gt2yutnnzht.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2klysljns.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2xzawiozw.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gt2pgoaqncu.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gt2yqhftbva.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gt2ydvgpqtt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2jzllgefl.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2semaxeki.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ztkrxtqg.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyhzovbj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2vepdoqaz.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gt2yjgxmbrx.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gt2vefhmkmj.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2ttonpldq.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uydpsnkq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2gfspmabs.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axwronbi.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2aeawfgvx.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2khmjvmfl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2wnwlpxmy.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2jnqwrqfy.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gt2mgtajnsg.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gt2jaogajks.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gt2xnvauota.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2wajentta.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2jqaaqfkb.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2entrufyo.html

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnydotbe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plhhoshf.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gt2rktbrkzg.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gt2ogtilsvs.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gt2cbzxvkax.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gt2dkmqsnjp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gt2hkpnvuzu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gt2wehsmdmr.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gt2rvqghczn.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gt2zbiojefh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gt2jzvmpebh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gt2jbqjvodx.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2hwdrebbs.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gt2hcdbmmza.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gt2etcvkxxu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gt2invoqype.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gt2lymhyyfr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2udaebbkz.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gt2diklobad.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gt2avxyjkjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gt2rumfojkb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2sbhfgxzt.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gt2ybfpbwxr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gt2zcvnxkdm.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gt2dsdmhdou.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ieubpzdb.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2jogwzhlv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gt2vsinsrow.html


<!-- 参考信息 -->