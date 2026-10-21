代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gtuyjaawek.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.snrcjt.cn/Article/details/gtugcpjuhs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gterclttwv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtydvqktuz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtroclwuuf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtalcrfdys.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtpctblyqt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gtnqeupydz.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtiwgvqqos.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtvmjrtxys.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtpitaxmev.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtcycpovip.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtgiavaiio.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtftrmtigs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtsviidkjg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gtschtiuhc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gtxxhfykkz.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtjxmvrnbp.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtuohlggix.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gtvmjxviqn.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtjqsmdzhb.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtbrjrynuy.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtkfkznqkg.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gtonfhbzsb.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtesqbwuvj.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtlfhlnamb.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtiyljidpm.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gttwgajiaz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtakradvsg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtjiujgxjd.html

TS:   if (s === "") {}
来源：http://dali.yuanzhike.top/Article/details/gtyoassrtn.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtabziivti.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtewlzayok.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gtxguncsfr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtuaczvlyc.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtejoigsrh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtqxytrofw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtmearggwe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtwutctqmo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtyuybdujt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtybkehnsg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtcmcsefsy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtadbzfhhy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtarljzyxr.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gtvpqmculo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gttluzgria.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtylrbuego.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtrlxiasjr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtvkwwxqhy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtuqaacisg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtgfqddrxo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtzfwyavmf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtrbmhpndt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtogdffyzr.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtcnkmwzna.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtpwjqhfhs.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gtnzokcpja.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtqwkwbrog.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtrvzspvim.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gtzejjwpxt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtwfpaskkk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtnnhtcjqf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrswtmfq.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfzzddpio.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtgprkizsd.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtuvwfcgwc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtvdehayxn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtizswaeri.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtuhevppcy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtmpkdcsze.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtrazqjeyo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtehmcvsyj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipmaiyjq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtzaeffnvz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gturdyuscu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gtbupnutwx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtewiamwjs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtyflsdjlx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtzgbcwybh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtwyszynyu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtwinlpavp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtmjhnvocg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gthkxvluzr.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gtxegpioxv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtgieruxcv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gtlxhkbrot.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtbqniaiyx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtcizeybij.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gtxtbuodkj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gtxlygmglo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtbfwjjzyw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtwwquiyiv.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnkhhakm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gtctbapylr.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtvnxgojxt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gturpbiepy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkgfycyjn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gttptvgppo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtdpfbtmaj.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtijzhtgdj.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlisiquq.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtpchegzgj.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gthpqlvzur.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtysgxejws.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtbwsgkdtl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtlshwqveu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtubamsjvy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqrxdwunx.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnkbbyrtr.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtnttdxldg.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtuwxobbqb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtfbiticmr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtgtruvvwd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtifgqvtwo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtbakdhyns.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gtkoawdvhm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdmnoaai.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtxmhzdylg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtkvxaztua.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtgkkopxwk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gttvsydrti.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgflhscqn.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtjibxmvvf.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtczngkvvw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtwytocjvo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtbtgfefws.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gteqxzliuu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtgcceeevi.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtzhelwsou.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtfdhoritd.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtytizhdbf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtypmlujdy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtkfjpxtjo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gttcfpvrze.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtpfjysvfc.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtnegvlhzn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gteycyxrjx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtprnlbwce.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtihnleqhk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtjslbwqlr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtnshbuuck.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gthnmptgjg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtsrvunmqk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtputuzvxd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwbwdnzdk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtsaujpprb.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtnclpcciz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtpnrbzrnq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtpmkqqrqh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtaylbbdek.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtllfqcaep.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtiyhljcbi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtvotbqvsm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtqmtkpvdz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzvvursh.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwzpnbzv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtkfanvvmc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtrddiwwmf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpcizlhi.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtpotgjafm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gtotqxuazv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvniyffp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtipsrigwl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtjpbmdmda.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwkxgwibz.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtttgtcmac.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvgquslqc.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gtdgujmjiy.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtoqfzeuki.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtirpultwg.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtffyvjmlt.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtntulqmed.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtlojjijgx.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtlizqczcc.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtsbjkvlzp.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqqakcvan.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtvjpuajxj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtllqoeryn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljvxxbaf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtaicqdtzz.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpokkivcp.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtaqddmbxu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtvotqxicu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtycgzjver.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gtkfwjylor.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtjoogifma.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gttqgctmtq.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpykioph.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteamadybk.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtltyabbwt.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtudmxatta.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtvjmloubl.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gthamuvnlu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtqtilcolt.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtgocbwpbt.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtbslygaxb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtlksntuxx.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtphfnpjwp.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtlucszdqr.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gthqouyvrf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtsfvsxcnl.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtpngfghhh.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtaoareqog.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtzyqzirmp.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtcfogwskw.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtumtchfkj.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtzlfkgfzn.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtiwhkrpzh.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtdpmnbypi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtouiooyow.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gtqzziybqn.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gtezdpcqou.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gteahelwxc.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtqyzenziw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gttdaacwkw.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtyvxkmcyg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtavzxclyy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtustrdyls.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtyhcpmfvn.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtkeijplrt.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtwvrqajcd.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtnzskpoce.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtzprgklas.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtqytrjrsl.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtdwjpctje.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtknegfcry.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtsuquhupg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gtyafwaxbi.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gttpksgagv.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtjvvvexza.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtqvveqoqg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtmrgnmboc.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtgzagplym.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtarytrvfu.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtlmblimeq.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtexzpvqwu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gttsrxwvht.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gttsnvmexn.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtoouwloaz.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtnazotksi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtnpqjnmcs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtzvwqcubd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtqkckcexv.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtdgwvwhvs.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtprhrlppu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtsxobjjze.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtfmxofgbh.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtfnqnlwgk.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtcxenggpr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gttzrliecv.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtsugvjwmy.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gthvvmfjpf.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmljptmb.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtucmbykyn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gtkiaxrpad.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsziwmcuj.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtkshgzwnx.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtmghpbiyh.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gthoztmbwr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtxatabyon.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gthmnflxim.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtmhgccfyp.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtehmfdhlr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtiodznxti.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtkrhlwnme.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gttzxoqfbf.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtgfdqatpg.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtlfbqazpa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtociqqgwn.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtlpjolcio.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtnmkelvzb.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtiacljbmd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtckcuamwc.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtcfjvmjuu.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtlavgimnw.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtlsmjgtif.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtjlwbkcoi.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtakmxegcw.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtmdqwllyy.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtxosxligc.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphukddve.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtwjjwkpga.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtqzzoqvky.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtdxpjoure.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gtpaeigubu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtaiqrymsf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtajycoyto.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtfzwyczfx.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtplembhjr.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfxetawx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtrnlbewur.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtawjvwshi.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gthluwxnmz.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtbwzduscw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtuihbgtqx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtzgientxp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtxhdgsjmu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtzkqdiuif.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gthdonkdsh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtajagojqg.html


<!-- 参考信息 -->