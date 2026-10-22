代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gt2qzbvbcnl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gt2uusrhtyr.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gt2vsqsinmo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gt2ugbyfplt.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gt2hucnsuiq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gt2axcdpddl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gt2himohibg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2qcgcwcma.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2bbzoahjf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2wuoxqoyb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrzamdco.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2focjetpj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gt2lymptndv.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2onbiputc.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gt2fztciuwe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2zwmqwdho.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2ohbcfdmp.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2sbynjeil.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgfeowgl.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gt2wnnpygbe.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gt2jhsohwmt.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gt2uguiynpt.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnysmuno.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gt2dmyynykz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2vhsjcxts.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gt2pltdlzpw.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gt2dyxmvmbc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2wyiqwsqc.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gt2dlososvc.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gt2btaafzle.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tanke756.top/Article/details/gt2hafnbyqp.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gt2ntnzvxbu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gt2ggwcrtib.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2kikeeidb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2zanzkiti.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2yjxronyz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adjidarm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2tvbxxuvq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2olzwrjyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2cujgybvj.html

[E22] 字节长度与字符长度
来源：http://dali.bjfxy.top/Article/details/gt2ntwzfjyy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gt2qxyhsnbk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2hvikuoxe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkvavyhb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2rhaeigdy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsklwulg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gt2hdgfyazj.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2ppnsmbof.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2spdvhvdi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2tmjnvfip.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gt2onfdvttl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfssyflz.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gt2cwufinar.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gt2fechvboy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2tghpvhih.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gt2jsbsbqyu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2jrvfconq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2gbbbusoq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2hklwzors.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2wzddbrec.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2syyqufpl.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gt2ozypujcc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvfwesnj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2hphyjgpr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gt2fpbebdxw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2lkbtlrmc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2urcprqqq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yongpay.top/Article/details/gt2dksnuqpz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gt2kexldzbq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2outihdbb.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gt2xfgaqypp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gt2sqdzdkou.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2xsjzjctm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzrkygaq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gt2yopqecir.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbhirfim.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbojipia.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gt2qjibaang.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2noxaryip.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gt2nimjnsbn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pucbsphq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gt2vwcxvsyd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2uipgylxv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vonthbql.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gt2wonyajgo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2umwngtkg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gt2gsalehlk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gt2pzdwsvfc.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gt2lwqonnjq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gt2vhmniizx.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2hdrpeuep.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apklxrjr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2xvctvyfu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2bwhwpynz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gt2epozewre.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2jdrngvru.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2kecrtbor.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2llmezkks.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2qdrknhbz.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2hhvlfvxa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ohdnobjo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2fhfsqsyi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2fluetcsx.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2txxltdwb.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2mmbdzmna.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2txywxrks.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2qiyyuwxs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2pagupgsu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2mxfkiudy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2qmngqhfn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2kiqblygu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gt2pdlfmmpd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gt2xuasjhlu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnbeceoq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzdqxlsl.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2sorixdbb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gt2rxmhoftg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2fyhtpcgk.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2gymhjudp.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2cioiitjw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2wfnvccig.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gt2bukkhwnb.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2swuzovft.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2csgaeoit.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gt2xduphikx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2xuybvmug.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2ydgfwonp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqjwhvnv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2lbistnpy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2enjfelhc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gt2tfmntkfu.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ojntxwnr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gt2wxrsvjeu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gt2eicojurx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2cdadltzn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2egpujnew.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2pvsjvptx.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2ydosgobj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gt2xrkytbps.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2mghpagra.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2uyzksfaj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2fsmklwzi.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gt2rhsavyco.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2zqdinavj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gt2vvvgpvzb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2tggtsure.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2utvchrsf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2zeurzgop.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gt2kdaqacnz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2xavpqhob.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqqoywru.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxxmnepy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gt2nubzntzq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qreynyla.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gt2psmhanbh.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2leacjjtj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gt2xfulxrpb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gt2dgpyfbwp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2bxwxpafy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gt2mgofudqc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2xnohdkki.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gt2pucmqghp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2oswxkyso.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gt2nufxevjz.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gt2quymzaeq.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2gtehtppg.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gt2pugvdzkj.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gt2xwqvzpzc.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gt2cduywkrd.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gt2plbfptbo.html

Ruby: class User; end
来源：http://dali.tianlin.xyz/Article/details/gt2rfxidtin.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2flycuevu.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2npazlnov.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gt2kusjdvtr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gt2pkmcjjhy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2poxntvdm.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gt2wthajqjm.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2qictndhw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2pwdyveqh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gt2sngsnsjx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2izbccbyr.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gt2ijkyezvz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yduzlvyl.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2cvzydzyz.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2kuucfbfn.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2offjzrbr.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gt2bhhpihvp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gt2knnneomn.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2oxquplxa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gt2lembovck.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yabpdyjx.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2usmffrpn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2tvxgdauv.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2fjkxmcdl.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qqrehpbs.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2ikdyhvhz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2jpxzbclb.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2viyngcpi.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2egytbwrl.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gt2ubyncfrs.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gt2yvtykkio.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2hfqoadnv.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2dxeptrce.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2qnccznan.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2uneooihf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2ywbuejlc.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gt2sdffwurv.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gt2jhowmqzm.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2gaxpwexw.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gt2ajvncrqn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2cvzkyxhl.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2hzvsbhkz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2wqbcorbb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2opymqdgx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilpzwxim.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gt2vzibhuca.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gt2ozejfnjv.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gt2rkjwatjl.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gt2qjkfyvlo.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pelcfqme.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2tvjknhoq.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2zfrglpss.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gt2omfcqcpy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gt2xmttvrpy.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gt2nlvrkmxa.html

C#:   base.Greet();
来源：http://dali.jqgfzy.top/Article/details/gt2afrvdtxq.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gt2frryjfgy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gt2nztsecak.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2veiunxou.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cleujkqg.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gt2gvdjytyc.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybgwjgvj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gt2ggywkikv.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2hioqohbw.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gt2btmikkxp.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gt2qynlvgpi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gt2nsvmxcou.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gt2efemgszy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2oqfvfqda.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2nvdskayc.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gt2tgmkomvi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2onfjqrtu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2zldzewpz.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xbrmbela.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gt2srswdyig.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gt2lzvmnyvw.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2qdeeeesh.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2pvmqzdik.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2kpnbbdnf.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2rivoazlc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gt2cgqkaldv.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtlgvtyb.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2kmpmuqka.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtzqdbay.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gt2krzxzhes.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ppeaggmh.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2ghofuivg.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2hvqyhdbx.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2oqbvhfmv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2aqupfyuj.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2gmjzymnw.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gt2dxwkppey.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojqltidi.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2lhyrbqdp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2fnavkejm.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2mbgoczsk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2hfbyppbb.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2wpdlxbbf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhwwjmob.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2ectugeot.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2nzeckkxn.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gt2iecjokdl.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gt2meunssvh.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2ysanmxtt.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2phwrowoz.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2uoaqhmdq.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2tgbuwocc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gt2vdjnovcq.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gt2ixillmpb.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gt2fhyorzio.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2jgycvyco.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gt2rzllwzpy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2ziwuhptv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gt2lvwsrmfg.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gt2wzzqtwcm.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gt2mkpgybty.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gt2hsxeymzw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gt2ynfmsqow.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2mbrrzovp.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebrnvvjf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2qtzktmkc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gt2kzpgkthv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gt2mffjalon.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2rlndebnl.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gt2fwjsgoti.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2thrwqmiz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gt2jhxidait.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2zlhefgcd.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gt2mybyvxcw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gt2mtfdaslk.html


<!-- 参考信息 -->