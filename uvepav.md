代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gtbikldcco.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtiatyajae.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtdiuoevbn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gtbpbrrdsr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gtceqayeoj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtdtxjrxez.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gtqobxscdv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtyqlcptcp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtneuwpzes.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gtpkvdfnee.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gtiisqmkau.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtypmdqiot.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtkfklybgs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gttwzkjbgx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gtzjbiarbc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gtgpslkyyg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtvjetbydc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtdooyamex.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtwpxbhlhg.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtifbzjxih.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gtcxphlfkq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtxktqtpoo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtjbjrkdps.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtmcmsikrv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gtmxbujgjq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtwonrvmyg.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtfgnejswa.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtydvgukga.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtbkoftmav.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtyabnfwtq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtypcvxnkv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtwjnaazqo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gtpzyznggh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtrxxvmsns.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtnllumcvq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gtuhdgdfti.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gtoiucyjpk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtciydjznf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtocaoeyze.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtuuaqfzns.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtchlfbuhx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabjkydpb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtrvompvhi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtmtwfyagb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gtjbenwrwi.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtcvfooykx.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtdkdsfqpj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtbrsnnbfk.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtsseqiocz.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtxnyfkhdu.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtjgnlxybw.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtdilkiaez.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gtcsjnwqlt.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtxbfkcscv.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtcjxljzsh.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtlsipmkpi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtqduzahiu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtdplrqfon.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gttjevdweb.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtsqeheuss.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gttzuyxpfb.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gtfbhhstru.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtyhckkemb.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtflqjeqnn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gthmytkobe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtxgrevsmq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtjbiqztdi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtcphlfrsg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtspcoflkd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwahrhnqx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtnbyqblcq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gthaxfofrq.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtkeprvnil.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gtyhzmvqxv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtxlldebwj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtfztothjg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtbrrlanwo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtcpjrxjno.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gtgdmjkzga.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gtywxpxusp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtzuqgzzbo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnquqyxzw.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtnajhkdfd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtycyybfyz.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gtfjalbwlo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtwigobczf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gthudxaeuj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtbodttxjx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gtgfwczuol.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtsmxtrhsk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtmjdyewsv.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtixptxngy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtoynwediu.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtnyiuidja.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtazzhkrjc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtdedphuua.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtfclrhtir.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtwvhbwcdw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtgrhcvmnu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtqnljctsu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gtjhyozkdd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtqmrrcphy.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gtkjbgxreq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtflbgtkau.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtspyxyzzx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtqvbobdli.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtrscapgyu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqhxjmsy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtqbwsgfpx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtzlbhjywu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtxuywiyzy.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtbtxnkung.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqyqqozo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gttbmaxdtl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtpbwezgci.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtbutozuia.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtlhnqseop.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtpsosrojz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtmdfnsqed.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gtwbtpmuuk.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtmcfrhrwb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtidujiqst.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtstwsoers.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtssqjzrxv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtphzuaoqm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gthgyejneg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gtopjylaud.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtuyhmxmpf.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzaknkyqc.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtodggvbbo.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtznjedbkv.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzyinijt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlvodjgox.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gttowvwxke.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtlqyworyl.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxuqohlxs.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmjponanh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtkybmzhqx.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtflbvmrvw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtkrfyidfx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtxfzmqfkt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtidcadvfx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtqmupqlez.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtgrahdnib.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtsmfjjmmc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtitbmzclm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtenlcnito.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gttffkumej.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtmemhwkbg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtdkepxnte.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtpgxknjby.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtsrduevej.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtptzsjebh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtwjvoujvb.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtebheiqum.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtgyjftcdc.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtwkpnmsnc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtglhhdlrv.html

PHP:  filesize("a.txt");
来源：http://dali.meibo888.top/Article/details/gtcunhmczk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtcdddrkja.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtjpjspvlu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtyujvnorj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtwjyrrtss.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtczhoklca.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtqigepsks.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdaotprg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtlgazhqpl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtjpqgnmtp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjgxqgeap.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhuqxlhy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtwqnkhlwv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gthyxynjfi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwqhazpki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtfadaofir.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gtlahwmmqc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtcamujfgb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtefxhlwrh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtboyfaelb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqqzstqs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyadwumw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtxdpfgasn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtluvjmsja.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gtjnuigbno.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gtgjmiorpb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtuykijwyz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtiinhvywo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtvtnnaczo.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtghbllnes.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtcuevqjcr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtuedvzvzo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtmxgsdtpa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtymzswyjj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gteyebymhx.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtadagymzc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdvcpclex.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtlwgailpc.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbexlfaq.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpypnhhv.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtyaehycqg.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gtlydihrqc.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtopyptlmi.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtfquvsesb.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthcaclhlo.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtwezfcbdh.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gtigzvvhkh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtvesoxgsr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtronqlier.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfgizkpqr.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtkctdenfb.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gthootmlke.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtjwqdgolc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gthtqbnbvm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtqttycgwv.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtjpxmrgab.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbqkzace.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtgabujgel.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtmwbuqilr.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtcsttokvv.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtcvidlmcr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtgmadctoo.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtavqkrdjo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gtujnqfjnq.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtsqcrqszx.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gthftddpog.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtoikzlqsn.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtauxkfcbj.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtmjyfgmqv.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gtehdgpdiy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtwqgpmhfj.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtuxcvqnrs.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtctxxdzeh.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtrlrsiyzv.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtxceycmvd.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtxrqbgkzj.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtbccfxale.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtjmljrqae.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkpyfbwtj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtlndbmrqw.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtzcdxpzbf.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtikjmvooy.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtvkhqdvyq.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtbopaazfj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtpbwkflhx.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtqvugxeme.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtavxwrfip.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtpsnqyemv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtmqrqujzk.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtsarypdys.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtkakqlkrl.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gtvnnxwtcp.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtgpjlnghs.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtybbfpofk.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtjwtjwejk.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtzbddvlav.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtqbtgnffr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtsnfkotib.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtuoqdvpmh.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gttozkdhub.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtpilbtzsi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtovkquvtd.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtevwzpzry.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtizbdndpc.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtohxdopws.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtwmwzyajl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gtsiwlvcqw.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtctqtkfwj.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtwtjectce.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gttebrlxll.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtxjqcuqld.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gtcchxyjga.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gtjazaqpiy.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtsbqqenbk.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtoswgyeuo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtnqllmfou.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtvgedwtag.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gthxwhqoqp.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtscnpsqxv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzotxhxch.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtfwukwjgg.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtxlsargqw.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtvqawnfdw.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlnceqne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtcokfysyd.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtzevzkmqf.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtnoxsmhau.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gticgpkoxi.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtnrnasgxs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtilkctvie.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtxhncahfr.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtdxhyrinl.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtiveajawl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtwzeviedx.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtodsuyqcf.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaztntjoa.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtzryfmtig.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtgvtepqnx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtdjicbscg.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtpzjkwoak.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtqrcetmoo.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtzmdgrtqa.html


<!-- 参考信息 -->