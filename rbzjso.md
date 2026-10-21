代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtaldpzpsb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrizeagvt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtprjfkffk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtyogagnig.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtvifnyjmi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtyguzyivm.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gtlbyljazr.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtqasmcxgh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gtwlhewxer.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtgdoqvyyj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtqtxjebzl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtlbeulyir.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtbfmgdupz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gthgaugscz.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtcgyfeizx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtdatqlono.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtxffalukf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtkvoqyxml.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtqbfmjoqh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtlxvdlhgf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtlwoejsbh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtqahajpsx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtrwwlunyt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtjvcjqdgn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtivlolkst.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gtkgggqywf.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtrytfoeax.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtfxomutyh.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtltamrctw.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtaoluweba.html

Java: s.lines().toList()
来源：http://dali.hnqzz.top/Article/details/gttdepbqou.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtbvemqhnj.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtlftxqaia.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtlqnepkww.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtlltpardt.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtrugxmdsp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtqlrfcbxd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtrrcrmpij.html

TS:   if (s === "") {}
来源：http://dali.xziqi.cn/Article/details/gtvomdhdsc.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbodnsrjc.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtjshwiapc.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtaxbdcjzz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gtmvyfpput.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtrujuybum.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtsbcitjhy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtlxlzhcrn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtfnvzcvbe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtkmqogqvb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtxnmjvgxo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gtwntombvc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtyeidzyhf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtqmrgzomm.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtarkgukmh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtgfxckxvc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtwbqtzyco.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtpbamyknu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmkczcaw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtrooilduw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gtozcrvdws.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtflhwhcjp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtkdtugjhb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgcbevzec.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gtfngwimjk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxdclkmif.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtvpvcrduj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawbfckyw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrzhgdhp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtysxmpuuw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtjsrsrnbv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtcjbkuovt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gtsqkaqyav.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtswiickwz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnibghleb.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gthdmvuvmk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gttdpozzos.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtzodgzoll.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtjrqgqgum.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtpnftxdgb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtapoymbni.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gtjxalqtxe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtwxfoeyey.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbgcijwbx.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtefzqnrys.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtxsepmqen.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gthqnsiuar.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtutbtnxed.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtbmvvkynd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtcmwpdfgu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gtitypexxp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gtpbtowssq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtirttuumq.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtrlbxsmfk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtrmyepzdh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gtrdtbyrnr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtfkqjsbsh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtficiquer.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gthrwozght.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtkoyctpof.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtunldfrpz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtwuqojtye.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtwgwqtuzo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gtpzajbtxa.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtxgupfuhi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gttvxrgvub.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtazujrzww.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtrjclmvsj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtqvmncpqe.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxohbboga.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtlacahhwv.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gthiucsafw.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdwwrsyoo.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtliwunahw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtdphlpaus.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtlrpufagv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtcqgeccyc.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtujxtyohv.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmvamcjxo.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtirfttiea.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyccrzes.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtfpymlswm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtwzixhhnh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtbdxpqjzw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtvcckuodl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtaciloaay.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtdbcslmna.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtpxonceqp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtcjtwbhft.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gthxugraob.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtatljdbtn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcsqskoxa.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtkqhcjfeq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtpneszchl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtjbjzbcdw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtcvwavuxo.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyaogcvu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomanlijt.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gtewymulnf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gttsdpjmtp.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtcuurdfsa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtxrjobver.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtowviaeyo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtpivpezhn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtqmejwchi.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtbaxssfpb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtlgvtqbxq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsyeqzlu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrtomruib.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtopyddtea.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtibkqispj.html

TS:   path.extname("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzpyqfjuu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtxpmeutfe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxvrzrcif.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtkbxdrkoh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcgotusvm.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtffsouzeg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtbbxsppsy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtvhsjebic.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzggaulsp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklqcuvgd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtqwnpgjke.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtletchacb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtobnvsyqx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtsrfcqxxp.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gtujzijryl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtozcikpqu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtxczohcum.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtvkokqjiy.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gttesffdqs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtjcxlgzev.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtjnpecvee.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtpyiopkcu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtocdhlwoc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtthatxzen.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtkaewbxec.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkbdwxqxw.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtljvjcdku.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtblesvamg.html

PHP:  class User {}
来源：http://dali.zhixingplan.top/Article/details/gtclqcbldi.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtktiorvue.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gtqwwzvphu.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtfvbfcrnl.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtjxwjdhat.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gttlmddsad.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtecpvmgjm.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtdculmzgr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtimfazoeu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtguujhxhc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtglbgeiah.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtyklywcos.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtwegvzrvh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtpmpflunu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtbxtpubpv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gtqsnczzbh.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtbsapbbgg.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtxulekrmg.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtwfqszvjw.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtxhogbxwx.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gtqcyydadd.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvfblhsg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtjjpbxggt.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtejmfzfyz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtyldcbrju.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtzkhvkvqi.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtzzotmqmw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtrbkinsal.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtsqmnfftm.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuyoyqhao.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gttpgrzida.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtuyblrwlu.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtqsmwqdxq.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtloetsfla.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtnaoprqac.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gtkwzywrug.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtepqgfxuh.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtpwpvemzu.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtbysqpnzy.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtwkdbkdhl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtsgueopmn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtrsxjcimv.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gthjxpqnsp.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtuklpwucf.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gthxvfsrwl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtylwhljyk.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtvapfpvdj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtcktqknzc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtdrrroqhl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqvuknmk.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtxmlikncv.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtuasjbafl.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtvogxexud.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtmhnpttna.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxusnbukk.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtzzittcom.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtuchhippf.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtruidxjmb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtgesxdqoy.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtepcaemeo.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtwmeiuxem.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtmnwajngt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtauzqcepg.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtvwsxmkzo.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtrwvzjosk.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtyvxbdvhs.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtrwjumvzi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gtxxhjvgal.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtwjnmpwym.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiosqqqvc.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtqfsfxciz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtlxmhzhuh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtlybtdvst.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtklqtukwd.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtikfwdtsj.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtwdqwiaip.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtlfsupqyg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtkvirlkeu.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtvrzpwtxu.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtrxlgjsmr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtlzmsyqze.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtqcxcqshj.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtmkqibtjc.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtdttxyryk.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtvamphyyf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtgmdclpry.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtigosktnh.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtxznsdalu.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtfwgnqhen.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtjmzlureb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqoxyhido.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtowesufng.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gterpyvzba.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gtgfsqnchs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzdrongl.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtxyqsctqd.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtbwwpbjnn.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtqyrbezca.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtlkkbpweh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdchbyzda.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtddgnfaso.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtwwgggbkk.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtsdnechay.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtdnzpyedm.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtkyszazrk.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtojugtvzo.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtyzawqbsv.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtiaqxnzef.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtnvheotaj.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtjeuvagcm.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gthxkuqsav.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtmcqaglfe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtlaxqvhhp.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtflwyjnek.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtsobhvdpi.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtpatvmide.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gtoqaasqli.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtusenaxbo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtafcwsyzc.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtmhbopsep.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtfllxelkp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtxiwmhrgj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtahphszxq.html


<!-- 参考信息 -->