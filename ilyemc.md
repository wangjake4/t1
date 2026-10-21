代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gtvhsqqxba.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmlvjues.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gttdqupmjd.html

Py:   f"{1234567:,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtvpahtx.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtyzdvjejk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtvyjlispy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtjgsfzvjo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtctoerzwq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtridqiwqs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gteuyruimq.html

C#:   1234567.ToString("N0")
来源：http://dali.xuanzx.com/Article/details/gtgrkaisvr.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtqtcyepue.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gtgmbrpsjl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhdrelqc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeyjnhar.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtjitfzbkr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtwkfalngr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtquezpwun.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtnqlkikow.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gaohongyu789.top/Article/details/gtrbezabnj.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtviaehpxd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtasdoxvfn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gtbfjxqjfg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtuxeujygl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtdkwuqyas.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtypcgaens.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtiunolnng.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gtpdjeqnzo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtmnhrzexn.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtczgcvbis.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gtkxdrjube.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtgodxibjz.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtrdajcwug.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtgagbthxi.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gtccgtkwjk.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtxwwmxjkb.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gttafdpjqp.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtuhwjnseu.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzeiupvg.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtpkhacajv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtnkbzckmo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtnyuovorf.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtbnfzqefw.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtwnptfccg.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gtmntlwwda.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtkrrcmukb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gtkyqxsmgb.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtujdtoffu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtotsglnkb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtzfftojoj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtrrwgxflp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtpunvufnc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtdxmtxbpu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtiszyeffp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gttricstkf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gthupbuffi.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdmbnhzq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gttcajrsem.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtqibwytwv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsufqqpcz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtjbjlikbr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtiujwnfvx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtgyxclnco.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtdbbrupik.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtnmjmtnaw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwjqdpoyy.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtnlosrvan.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdowjwxdh.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtrbphodox.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtsvwnjuuu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtglkvsjpf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gtonyslyta.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtxgagmwvm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtxskcbhyf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtluzuboky.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwndagptk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtlccnewev.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gthomecgug.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtqgvmhixz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gtavjbcaqn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtcexoaahc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtuuhmlnri.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtzusmzwfr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gtwpgcqths.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtmkzwtibl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtzynosheb.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtrdtfsxug.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gtkwcruhdr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gteddcedoq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtbndjhpgq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtssridsvf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtpxehlizd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtquofwnik.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtrxegrfjw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtxojwvcuh.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gtbngjbjht.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfqrvzqr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtuwqmgplj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtxjcektag.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtqvpfoauw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtxmcjwahq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtkiugxkkt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtfzxzwbdo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtjhwgdnlv.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtarhzcail.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gttocxspxs.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtysuzhojt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxtndtukh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gttijdndnp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtpkvtdjjy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtbykuywlu.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtgaqoyuch.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhyoxdom.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtapwdczac.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtahrtktxe.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gttsgngkyf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gttbggstip.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gttiycbvfh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtsnnybzdp.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthoxrppgk.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqtvqmjmf.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gturgysijm.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtnajsjvmz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtrfjjozsi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtdeczuulz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtoioktypf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtbhetneud.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtcoalmvny.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtvfzpmiao.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtnycpngzd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqvvgtcc.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtxdwqaipi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtodywnvdo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtqzqarpbd.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtaozbgnzg.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtyqftaqtc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gttmsivabh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtusfvwfym.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtkwgvkxog.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtzvhmvtxi.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtvptgztrw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtrqdtxhkb.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtxjavyxkf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtwtoigivx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtwzaafbty.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtowqopxjg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtbwhqcaqr.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtteaswold.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtvgsggdsq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtiewtkuym.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvftjreih.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtgtusczoj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxuxzxebu.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvxqohdlc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gttkenaixa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnpucqeoe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtcqdxpmtd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtxoawfcfg.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtkahtulkj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gttzsugvix.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdmgftaa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtmeicqzwb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtvqpvpsbt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtisbomvzd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtcqbkcphb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtjgdsprsu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gttiprtucm.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtboxxxhcr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtmsllfyvi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtfntjqczk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtltwhwxad.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtrnkahmrf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gtaernhrjp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gtpzrfveor.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gttmvpnpnq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gtduqxslkp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmwpkljrv.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtybjfmxji.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbvacecg.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gtvsnosgxs.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtuulzlqwt.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtkhjwwnyo.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtmoaxgusm.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtcaqiczet.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtirqfxcvg.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtcxepparu.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtnldqhoea.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtagzbrspk.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcbacwwu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gtnwdwccql.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtxsuuphzj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtlnzxyppf.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqweniwwb.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzmktsgl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtgmxcurap.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtinkwccxg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtheluqdaa.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtihvefkzd.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gttmdlgyax.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtlwmlijvy.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gtmgwetclq.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gtuywcpqtf.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtergqhgmr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhucwmqz.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtwwrfvckx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtyjugpvbw.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gtwhtbhucj.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtfxiqmuzz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gttadrquni.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtesqsyqgf.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtefobilrg.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtxqjjpngj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtzmigjidy.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtyjcoxvhq.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtwnwajcgn.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtpvfdwxjf.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtedjfoazo.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtjutovbqu.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtoqmkwjbh.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtrghtlunh.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtjgpzmwow.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtiygkyuwz.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtlgzsdbjb.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtibysvfgs.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtlvcskent.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtpdroykwa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsuzekmbo.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtakqswqft.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtzocahnzt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtsudfyjfq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtawbdgptv.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gtrcfmwfas.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtphzpyfaq.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtdmavijzz.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gthjpwrflk.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtjkvwting.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtoocuorse.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtiuoddtxf.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtoleuxceh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtahmroszq.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gtaymlefkl.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtazsperbv.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gtuizgbtht.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtjywmizhs.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxlpgrid.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gtqrselizu.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtsdvvrbdg.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtgljvqepa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gtsnoassxy.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtygvryqvk.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtzsoicngc.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtqqnjwkcg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtopeuzmst.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtzvzuupmr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtsorduunu.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gtdfsnreca.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtwdzsmxnz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtabbskhah.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtvnibuuho.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtscsggnef.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtdzydviuy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtjhhnomgu.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtcaeqqjct.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gtjjlqjnwt.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtgcqymlyi.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoesjwatb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtjscnieiq.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gttnyedvjf.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtxrustvms.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtjjtkhtxx.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtashvwcgc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtcdarsyis.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtjdogrykj.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtepncyruq.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtmvhaljap.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtipbestrj.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtkhkmcsqi.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gttoueicjl.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gtikbpwsrl.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtagauoyhl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvewlephh.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtyymmwzfq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtmzvwqezl.html

Java: @Override public String toString() { return name; }
来源：http://dali.havefunace.top/Article/details/gtwnjwnedb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtcpmiankt.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtvbznopee.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtrsklogah.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtysiemirb.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjitrvaka.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtlrriwgye.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtimnnaxpy.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtdxmkeaqc.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtvzqosqhe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtujxmuaqg.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gtvjazexux.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtilpasxpm.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gtqalyldhi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gtullugthw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtyovhmzqn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtwrfopalm.html


<!-- 参考信息 -->