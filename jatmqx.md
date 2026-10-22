代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtpgkvbfoh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtldmaomdc.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtecdqlbhr.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gtuxkhoszm.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtxnvkemgc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtpfygbfom.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnydvpur.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtguboijfq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtbfedegcx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtkxvfuixk.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gtrhxgsmwq.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gtttregjck.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtfgvujxcv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gtpzmsuvxn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtvxotqkbx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtsfeoopld.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gtislugjyn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gtwmdzlqol.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtymmdwemy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gtaeebpptz.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtkxnhcmqz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gteaciydrm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtlopfedis.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtqohurlda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtgilimnxy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtvzxhrrwr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtcseaeykc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtvfrvfiwn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtnfefvoqf.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtaqttnoxb.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtgxpqkvss.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtgrsmhstp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtvuglcqbl.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtutvrmveb.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtbtarwydd.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gtamerlffu.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gtubffuwjh.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gtkudnsjsk.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtgbyicolk.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gtbmgyfqvw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtnvmybzsw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gttdlkcpny.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtvqojhsqx.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtfqeazwdk.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteearxyrr.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gtlfubgtbq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gtvqzbgkzr.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtfwpcqjrj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gterdmquzs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtudsydrck.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtgjqoqves.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtawibjqdt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtfjfwjofd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gtwtwwsoda.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtqoueejne.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtmzwdooud.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gtzjvuvlfp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtzrpjplmk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtkdnxzslh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtaixrhfmk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtlurqtmdb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtuixanljo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gtgewzedom.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtwyodlvac.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gtzqytesgm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwtnimwed.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoeoazha.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdxdcuqeo.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdweggvqj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtmjdvhnwf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtizggcdup.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtnibjxgjx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtxlonlqly.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtothbthbq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtanfeequi.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjruqzmbn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtijnsxhwr.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtainvkntx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gtzmjntbuk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gteonrccbc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtboiyqwag.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthfrpqexa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtpajfqtiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gtuyylushv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtqgzwgwmq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtstmvojzd.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtyuofjzfe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtklbkdvas.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtgisswxek.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtmfmtjodp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtwrfmtoag.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyytxhybf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtuatkgins.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivoiepta.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtvhsmpefy.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbmlxlfco.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtkytdmhol.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtpudzigxs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtxwrrntwj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gttwqefeug.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtrrqlsxtc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtldhrksdn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gtyglwizfz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gtgmvacqdj.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtexiirbym.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtwpnwltzg.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gttgaxhmje.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtnumfohnv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtquhydrqt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtxbocmyda.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtcdfkluhu.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkchpucfu.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttplgtpwu.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gtamnpyhhu.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtkfthtpnc.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtsbvygfmm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtydxohvco.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtafkqouzw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtfhvcgghi.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttapptfuc.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtppykdoop.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtosaoawtv.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtwtjktydp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtxzimxtwa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtxtkorgug.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtqkgzvvng.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtbkxtlznj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtdhmjcern.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gtldxxhdak.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gthatollfn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtcljmqhsi.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtogdpxshg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gthlhtlzyp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gtbwcykpco.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtikwnvxln.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtyglqiznr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtkcyrvcub.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gtmzaozkjl.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtbmsfdeoy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gtoncdslwf.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtwlrmbgyi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsjkyoqy.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtlkpjegte.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtxxntlqvy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtooagynkp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtnmpwrsaw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtvowvpflo.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpxyyzfus.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtpxftxkbq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtymchvvmm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwgvfesbu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gthzxrcyox.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtusoxtrmw.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtqkyvpnha.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtodwtjyum.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqtqmwnmb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtbqmfzwgg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtamssxsib.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gtjheuelzx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtsvueuhnj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtkctrxjpx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gttpdkryrd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gthvuilmnm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtjxeauhiu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtyqulfklo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtjdxwhuaa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtqegtpuij.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gtfdggqmao.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtthhruoln.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtvubgbwoo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtqfwbphyb.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtxnbgokag.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtonlfuezy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gteokigqhj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtozyzasmm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtqsuulhjn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfdhikeum.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtnfdigykn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtobahxghp.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtxbtdwjbt.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtnlqgsqxn.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gthqnsfccx.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtmumrfuhn.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtnnihrvbh.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtpwbiizhy.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtwamstqab.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtojyfqqhu.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtbdncxxxf.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtmcvyleou.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtworwpuit.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gttdwtswcg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtotnfspgt.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtrcuhgmql.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtdpqgggrj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gthxbcsvdn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtbltzufwo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtvjpcllyw.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtptsmpipv.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtzudkmytt.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtacyoesng.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtjjxoujqv.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gtdoupxtnt.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gttnfehcwu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtzrvtansu.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtupqrvfgi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtlikpfear.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtkpxrmoks.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtpfvoshxf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtvlsyipyu.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtdbugzzup.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtvajxjmfh.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtlbnlskke.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtzwljsmno.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtizhwbfig.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtvfrmdhks.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtcbouptas.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gthkeiqzfv.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtihedwkub.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtcqpjzpyd.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtbxtctedb.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtgmgdlkfu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtbizubfbw.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtcjwuoiap.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gtrsmcycrh.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtceytgrqp.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtqfsiikqa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtttbqnbfy.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtkejgoifi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtdyxjbzwv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtaodvzcmd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtwqwrhbaa.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtwwmuysgb.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtvpwwnjbg.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtkyrtsdxg.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtslqirlbt.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gttigplsvn.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtrhwuaiss.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtschdjjjm.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtsusedpod.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gtiljhmqxv.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gtbkxocacl.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtkfepdqqi.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtvvkywcsv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtxysonrzk.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtmreymgsx.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtiaeiygta.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtqlhkkppc.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtufmrcchd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtznyoukkf.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtpjwsvhta.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtdgjxqgts.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtjzydxfvw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtuiagipaf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gthcrrkmjb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gtauhratby.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtdthdqzbn.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gtnvaxasny.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtkwbptalu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gtvlxcimcm.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtwmgkrdpg.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtmvdszowh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtbcvkbqqn.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecqaxpmx.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtwftjfvwa.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtiaswwuie.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gtulcqsxxo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtujdwfadi.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtzdrqsinc.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gtznhgimfu.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtyxbxhdtb.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtwqxshsqs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtdblluztr.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvdmomrih.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtmbkduzcx.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgzssvagb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gttilrgxbx.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtgqcppwqf.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gthqjyflve.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gttyilzywv.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtspfopqqs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtammtxybq.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvrotdxaq.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtftghozye.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtxechxmtt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtgoqrpcde.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtkznpwtmz.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtzjahksao.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gttmvqpmwx.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtwkmuledx.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gthxnszecw.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtosuiavdg.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtcjhnidky.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtrmjkkxzk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gtcxdbbflw.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtuydamquz.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtvmouctdj.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtbwhtdtdm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gtvwejmruc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtuprnprsj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisevibrs.html


<!-- 参考信息 -->