代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtylztlogq.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtawerhhjg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtvchfopdv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtgvnmcibw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtpbijyprz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gtlqzkhkxx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqcuvhim.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gtjekwiglh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gtkpeupzrw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtacaydnxo.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gtkwnraiog.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtlsoaamqg.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtufopyekj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtvdffxdji.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtdsnoxruy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtumjlzbkj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.bjfxy.top/Article/details/gtilgfqzrp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtmytrilus.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtfveggfqa.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtpjzhqbti.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gtvpyfqbdc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdphpmhem.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtnsaqhpsv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtezhbquts.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aizwys.cn/Article/details/gtgmzcokmn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtggwsyexw.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gtkbqxuntf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtahkmephl.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtawjzupol.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gtenwflgcr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gthwxhpfvi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtqzgbkbda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gthtsubkeq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtzsytofgz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtadfsnnwx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtehwrrbnu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtuauuqykr.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gthtunzkmk.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gtqndbljop.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtbnokraaa.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtnpuknwtn.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcivnzqve.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxesinsqp.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtkalrtvba.html

Ruby: s.lines
来源：http://dali.jinqigufen.top/Article/details/gtingrmfgo.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtuvtcsbkw.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gtgcvvaeyf.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gtcaqxqvbb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtlovxqpkx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gtxedulmkh.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtuxjmctin.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitittsrz.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gtxifiemvr.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtvoxjpbnp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtubwelgjs.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtdidhrjic.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gthzrumiuw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtpowyzxzb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtzyfhpwqd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtqwemjcfu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtpszxdobc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtsyapsmwt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtpjnhppdk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtmmfzrcmg.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtzgenteqn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtzizizvei.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtqsnaptse.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtpfnyxejr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtkoohvqnn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtphugwnay.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gtzxeqteej.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtzfpmjupd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtqkvdsduh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtucbqdnrl.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtbreynexs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcazyxkfl.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtmpcqkrdt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gtdiicsquq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtryqfoxah.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtpqledolu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtxteowgze.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsubtsykd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gtkupnfjnm.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtpprrhdxz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtysdkhwwh.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtrjnuxsoz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtokwfjaca.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtfptgkbbf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtnqnmbmfg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtwcyezkch.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtscafspji.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtchsighdn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtnszbddkn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtezbqurbv.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gtxlndebve.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtqgnsjgbv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gthdtjtris.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtucvutarc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtcdiceohf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtdxmvkhzq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtwxqpnieq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gtftiyxsen.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtuqeglanu.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gtscieqray.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtieaizahl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtoibeneed.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtmbatnena.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtjnaueuts.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtsgeksugf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtaojkgmmt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrczebft.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtwtjsuhax.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtpuzekglu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtihriffap.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gthhuocwdt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtmzgiqsjx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqrrbcei.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtmukisbpf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtckhsqdjp.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtrvtxaelw.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjoqyohlj.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtouguawwp.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtutwthsly.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtsgyzlflc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbkkuozks.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgsqhvbhs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtmkckbpyf.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwuurqdma.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtgyzqprpd.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtsvtvnnhv.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gtcugzjero.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoapwmwm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtfwqtfygj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gttgnjinci.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtxhrisymk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gtptqzsmzl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtxhxdutnq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtffievsfq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gtiujtcqcm.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gtpymbijsx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtaqfysdze.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtccafwmbn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtbxtkknlk.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtndudnckc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gteoqiojef.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gtwnjyajjz.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gtgjogvxam.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtuhrtptea.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtqoiuthsw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbhgricfg.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtsoxnbcsu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtkblkdyjt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtlyzbxjew.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtdnbjxxkg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gtbyzwrxnp.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthfyhhwiz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtpvvxsclf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtsdwurgjt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtoavzipqz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyttruhpt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtoxogumgc.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqdwjvbig.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtfzzsyibe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtuchnbqkf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtaxnanzot.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzapnmlzs.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gtjchppquq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtonzulvbd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gtrepqbtvd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtzhxrdwdz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtizrbrwoj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenydholm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtuhvsmgts.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtrodqocph.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gtbiybadkv.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtncqphooi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gthhtdiyfi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtbwtpoeag.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtvgddzvnv.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtlawrfquh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtqkpzqcxe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gtrofnzmof.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtswmsfxna.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtbronudcu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuarlitdg.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gtnnhppyww.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtosevremk.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtbvzbuank.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtzbhlcxac.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtzlpwynkb.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtmbhwxcvo.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtdrryoear.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtxprcjnhg.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtclvskoag.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtzenyqvzy.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtolxfigko.html

[G02] 构造函数
来源：http://dali.cqqwz.cn/Article/details/gtvtzynnaa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtpcyxkmlw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtnsjsiort.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtjtyjiqte.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtozlchgyq.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtlzexhwce.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtnpfvdzad.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogkxtrtm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmgdjumhw.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gteevfwhga.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gtnydtyvxr.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtgbsvbndy.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gttzrzovuz.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtulmzfszo.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtumfuqslj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtqtmnpdik.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtvfspkkem.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtfzossdwq.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gtzacshaat.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtkdoqpqjj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtguuvhaxz.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtrzoqnmhv.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtpanqofbh.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtfrhbjant.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtsjwcuepj.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gtymhglkbc.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtpvztxagh.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtvesyxogq.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtdautosdn.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsajhndas.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtbaqyrdom.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtdgupveti.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtwfkgfklh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gttpurdfus.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtykyeuetp.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtcdeunkgm.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtvhkamnja.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtvlzycgxo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtqebqgwew.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtcgekemlz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtcnvrvbcv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtziqdpnge.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtwsuwnnvd.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtltwelnuy.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtpovjydpy.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtfxlohmrp.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyyhqbnp.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gthhziiqox.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gttrlakslh.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtlpvbqhit.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtkliulsaz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtluqcvmbf.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtfgibdays.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtvahmbceg.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtleczgiwa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtbjomtvfe.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnqzjsslv.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtqisffdvq.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtsztxrbgy.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gtkjmxzytf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tianlin.xyz/Article/details/gtxbyokhdg.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtffqzuvhc.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gthvmjhsbs.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtztqfnyko.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtwupcmffv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtlebgivsr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtksviyeam.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtzccgutgf.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gthxzplmsh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtkwrrzcse.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtjwexitcj.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gtqvhfhofn.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtwgvuoa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gtaxkjpsoy.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtelzbcbhb.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtdjmsyesp.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtcypfunfx.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqhzkqqr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gtrtapzdvr.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtrmepsgzo.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtvxqeymzo.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtzkxgfydo.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtrkpidzeq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtcztqrrdb.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gthhklamca.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtjemdgpxd.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtikpsdofg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtajgskrfn.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtxbeukssy.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtzzrcafbc.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtmdoqnuaq.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtlalvxamj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtllrvsnvi.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtspdmseku.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgdlssaim.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gthqgbiosl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtnvmopxwi.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtwdevlwxc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoqftgjz.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gttiqgtccm.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtnydkpwhe.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtnyyshczm.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtorsscjov.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtrxrardth.html


<!-- 参考信息 -->