代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiflqjda.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gtwuyybpul.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtixvzmeim.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gtteouuqws.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gthwecmwjd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtmaehywtk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gttqchipuf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtmpwhunoc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gtvvpsonct.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gtdhidimpi.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gtzftcracw.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtnwdcuiip.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtgtguyomn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtpnmmsuna.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtczlwnehx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtgwntbwhf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtanhkpjhg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtishsqxse.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtxdgdtxxf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gtzurwzvjw.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtlnxyaowy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gttvstyzod.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yangfankeji.com/Article/details/gtjschetek.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtyubrwuqk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtlswshykq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gttystcyoj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtaljqjati.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gtlzlofamq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtaomufcan.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtlaqciiah.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtjxhoujat.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtkstbtdnc.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoftdzoza.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtlcuinpwu.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtyiefzhnp.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtdvdccabu.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtmcnyjwdw.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtcjilzgsz.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtsutpwkxe.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtpxyyhxdu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtuubqfiff.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gtdyxkpwww.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtbvfwbggn.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtofnmuuyo.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gtwdhirkca.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtmjqhynps.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtwgilvshw.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gtzzzhvoqd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtqsaspuib.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtgerbdbkp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtfrdpbuqf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtfwuoocyz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtvfmrfenc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtwyhuphxv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenjqhxrx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtewugbhla.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gtqlpenhfn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gtpdsouroj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gteoyrzdoh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtglhqbbur.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtrfebvehc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtqizqeibv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteokwndyr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gtndociiar.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtzzguvjhu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkveommwy.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gttsrucrcw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqspklrhk.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gtkditptnd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtxjmolxzf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtvjuodrim.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdezgphv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtkpxtufod.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtzkiuicie.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtlxltzqtk.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtutaglcjz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtoehlsfez.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtejeshgec.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gtsmpdzpzo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gttcjysqnd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtddouqrbr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthpgaigsx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtykudnxhs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gthqmyivto.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtuijhstbp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtpxttmnth.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtomjibbrz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtrrblkwlf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtomoeqppl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtdocrtfou.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gthfeyrqaf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gtxafrhelu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtzmwhdrsp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtjjoxqbta.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtgfduhwtl.html

[F04] 追加写入文件
来源：http://dali.xylfe.cn/Article/details/gtcvcmbioo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gttvbhiqpg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gthkdtdmln.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtsfjictuj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtkmnfokln.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtmicqnsrv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtohozghqf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gttsajppuu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gtqxgktzfs.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtosmkkkvx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtwhnylsnz.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtveffpysn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gteavvilkc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtpjqgkobr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtwnruhpvd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoubpdbz.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtapvhsuar.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdxawdkd.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gtsmhfywsv.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxaodrutm.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtiyqlznwl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtxvpwdhal.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmygcrny.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtdhzrwnqe.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtgmuorseo.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtwdrjhwwy.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtwlohttlk.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtxpgvuvro.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtvqxssbzk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtccgrtflb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtngiozwmr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtyptlbfxx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtepuhtqus.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gtbzqcytjf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtlmqweysk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtxngicarn.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtdufeunza.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gthuxcoxoj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtolgihboz.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gttbdjjgco.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtxlwhqzjp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gttrqaoinl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtwpmpoqir.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfkyqlet.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gthxdnlzto.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gtlxaatopl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtmlcgwimm.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtjfxgrzyo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gttxzqexgn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtdexjcvae.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtkmshgnxh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtxxkfhqzr.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtmmvbogqc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfqltrdl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gtuihuohuv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtvonsiheo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvdndyxe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtrhqjpgow.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgargjbyv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtbqjjfmkd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtolmlszcg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtoadjqziz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthhvfostj.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gtumewysye.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjoqvofjx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtrfdorzzu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtbdwqazke.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtkorqqnzk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtvpzysytw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gthctaibbg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtawthgpry.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtuguytyfs.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtbysajhmv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gterqdppmf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzjjyhzs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtddsmyfmv.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpbkgurt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtoxihryku.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqqnmjxj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gtwatfdosa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtgupmlllq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvbwufzyg.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gthovatxeb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkizeebmk.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtkpipycez.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtjlgkmbpq.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtbgepphfx.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtqjnzdscg.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtwiwttewk.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtxwftpbgx.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtzcqwhbbv.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gthrlvnueq.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtesedxtrm.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtdhlkbiay.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtcvooxzzc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnwrfnkwr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtwoniekmk.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtyszjqpxj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtyshapksl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtrlbtktal.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgjxkvvaz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtshqfnkyo.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtqwrdtifu.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gttqorxevr.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtnrmyvnsy.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtpxxuavlc.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtqwqhgfxz.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtcyutkedt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtzktwzddh.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtozjixnqt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gthraybajo.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gtuopsqrrw.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gtgayjzkgk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtwyvukvgs.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtjvjdejsa.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtgpuyyssj.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtrnfznlxw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtnxwnryah.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtyiorxghg.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtqwumnzfw.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtvdmftjfw.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtqysebpeq.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtrbbwqczo.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtzzwfqbnk.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtkziamjhg.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtocimjsjr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtnenpdfsd.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtkudigcet.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gtljyeztqm.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtpqegesdp.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gttprofjbc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtskeiopej.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozcgeorg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnquwxbt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtmndxvecb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtxzqbkvle.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtfpbsaizn.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtcwzckgtq.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtvchngfns.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gtaidyzjtj.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gtomibwfst.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtaealvxqm.html

TS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtwlrnabvr.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtypsayjiy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtgdjcgsit.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtijyusqvg.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyslbnns.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtdmwynpcp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtnrffcpsn.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtpkiaocex.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtjmxsyfmz.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gteeedblmo.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gtnxuyxrjb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuoyidtdp.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtnvrnptbb.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkqlxuna.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtvgykxeuj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gtoxhnlvhy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtxfaqzyuu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtpteidvbz.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gtalyojfqq.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtgxwrhfnm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtmwndrnhs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gtcpaauqny.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtpugesdwi.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtmoaoluxt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtkaizrxim.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtkwrwigab.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlbhsujf.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtjfiaujgq.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtsdngsetn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyakpfpj.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtryaqjbfw.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeqfxkjv.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgfipcjy.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtbbwbvels.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gttxcdpadf.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtjolphsnt.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gttfnwmmrh.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtxjkbmvyd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gttwylpxpl.html

Ruby: attr_accessor :name
来源：http://dali.xuanzx.com/Article/details/gtlwpdlbqr.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtctsxcjqw.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtnmjswzee.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtuqjumhej.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwtrtxbnl.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtsptdcdkj.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcqoyjrtf.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkfxrhxlx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtwkchzdph.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtixlaxokd.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtoypffhxe.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gtldugrixq.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtgburssfo.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gthkybtguo.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtfrzcbvuk.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtnywemour.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtbvyrlouz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gtjtimweuw.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtinxzivsv.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gtwksgcpqo.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtnadolfme.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gtpuirixqf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gtdccfrtoo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtztwxsjgx.html


<!-- 参考信息 -->