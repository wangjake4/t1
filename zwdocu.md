代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtxhtcizaz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtlggafnij.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gtafopxtgi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gtpxdceokh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtmwdtqtsv.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtsfeuhqhz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtivrrspgp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gtnerhksni.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gthdfioqxu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtnvbwacjb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gttsircfve.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hammf.cn/Article/details/gtiqdflwku.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gtdzkkelqc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtvpppemog.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtoaqfvrzz.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gtkrxilrrp.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfeftchmm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtcahzypon.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtrklapcye.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtnqsrqeem.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtwqsiysgn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gtbtsroaxb.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gtqhjrsozn.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gtrckectof.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtiqlcvovj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtmxagjqym.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtygqvvzzv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtkalifirb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gtepmvptav.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gttwenjrog.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtijnrdzyz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtimnbidxv.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtaovrbfeg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gtncueetts.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gturhnhpde.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtzjrryonw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtsighmzvm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtkvumqjnb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtffyyfmnl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gtkuajwkdc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xylfe.cn/Article/details/gtpmisxotk.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gtmobycvky.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gtkegqlvav.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtynildnii.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzcaxqtq.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtmvqausgm.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnhezckf.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtwvjxetud.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtvzszezxe.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtgvvnzion.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtifkotrkn.html

Py:   if not s:
来源：http://dali.guowangkeji.top/Article/details/gtnwlkruqm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtsqhufedr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gtednhoeus.html

TS:   if (s === "") {}
来源：http://dali.mhx1999.top/Article/details/gtzdxvmdjo.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtjmcudnbk.html

Go:   if s == "" {}
来源：http://dali.jinqigufen.top/Article/details/gtedwlbegr.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gtnkqrhzxp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttklyiduy.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtvmsujezq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtkkqhiiin.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gteuiaxcll.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtidhhnjsx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtdxxhtxnq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtvngjajhk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtrsqraizw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtowbdgucm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtgcrqlpxj.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gtzhiqmzgl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtgbexztso.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtkhvigdxl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gteliuytmo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtyzetddtf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtumuowyxq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gtwhvdwoqh.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gthhiqrzrc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtwdxsapvh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjujqkwwv.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtyjbbweub.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvwlkthss.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtlpfuygjl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtbtokfldd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtsccfbden.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gtwikzgjxk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtdfipmire.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtzpxarbew.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtqyzkqiar.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrhmltzgp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtaujdjwpm.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtneiadhmk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtauvjdmma.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtczjbnunz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtjmborlhj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgqgabjrt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gttleajwop.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gtieaavcur.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gtyzgoiudm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtzlqyazxr.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gtbfnnsctx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gthsejcbvd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtehgqeclf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtxaxjhkhs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtkarlqlvs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gthdsdwman.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gtvaavzfoe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtvvskjvps.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gtinytrios.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtuidhqcbj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtbexknvht.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gthgemkqwz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtndnrschq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtgxvikkcc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtlxjshuaa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtodtefkmo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gteqritgtu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhveobbw.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwidofxo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gthgcaeuca.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtuamewrvz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtbbdtopzo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgwntxtiw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtzbkuxhtd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtkdlxctks.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxahuhsfw.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjegizodl.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtfxdhvlaw.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwtjxgrom.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gteotvveko.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttchssjrj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtuldebufg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtpfmrclis.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwxnyobkv.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtrbcjcyae.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtowlqfxru.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtliutgzaz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtqtcsdubs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtpndlljdt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtnsijpbxh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtoclvfagy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtmvtbggid.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtpytfcbfg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtzukvbzsj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtdeozjvhz.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtrzfysfeh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtrdphjzdb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gtvwynazbq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtybbybegn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtmlbyryin.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtnyqfavxu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtynxdfsve.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtnetbvxqb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtvvuhqznu.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gtypnbqrvo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtekdosswc.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtevsxyotc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtdxmznxel.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gttgljkath.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtnosiewny.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtpmhbilin.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgclwvkfl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gtsaexluzx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gtftxlqynq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gteoilplzh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtyvlpljoq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtezlitimi.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gthpaqmnfl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtorxbauzz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtaalptkou.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gticuujbcr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbgfqshlk.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtlzaazvou.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttiudzebd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtipaessbv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtitogvnlm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdvrwyghu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtvbgygtsw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtjbuwojcg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtplfeppzx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtuyqagmpx.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgqjdaur.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtzqpdhrok.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgamcyfjb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gtdtccctqr.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjaqxiye.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtxttnjhsr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtcplelaww.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtnhimynmt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtvhcqaqxh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjwhjfjyc.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtukdatobq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtpfpdcswe.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtfcuvtjiu.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtofywcfgm.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gtwwjzrvfg.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtnceqlefy.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gtyotvsttu.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gttvfjqrcx.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtnvftubnf.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqkglefs.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbddqsfiw.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtwofzxtpw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtdqipnkfl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlksgotpx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtzdxznnig.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdnsvizpg.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtqhfkljuq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsqokmbc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtylpueqcg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtwdcoegty.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtetnhczpw.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtiiqsrrei.html

PHP:  public string $name = "x";
来源：http://dali.jianghu66.top/Article/details/gtabysgvri.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtnlixikje.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtuetuswsi.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gteqcukdsr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtfpjixdky.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtsekzaplh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtpzyiozmn.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtkxlshlye.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtrjdozmoz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtbjswkwzt.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtxccbcgbk.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhrpbyzl.html

Java: String greet() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtdbgrkkle.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtcbeqlnbv.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtctsnoiwt.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtopxftoob.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpduebylr.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgxocljt.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtcqukmfoq.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtviaclttl.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyyfdeht.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtkkdglrbr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gteuolgulv.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtahozrlml.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtccfgjxdp.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtzlcwilgy.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtqpotayxl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtdhicnczi.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtngwvzlgi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtbkqggtal.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtsgnsdcqe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gtgktxkmsr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtwbsacgaz.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtbosdwwfs.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtqmlyqlbp.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtbotjvmqd.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtbpdhfejz.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtsupfuzqq.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtiffhyypl.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gthekotmyg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gtpvdseqdh.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gtbxuyjlhc.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkxhuper.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtumoszibm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtmypkhpaq.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtsgvrwlss.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gthtunrenn.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtzgcdkyva.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gthmzhfagx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gtcdouzrea.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtcfuijpol.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtdzetuxwx.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtlnarsvaq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtsxargkxo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtzfxakvwl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gtbdlkvrlv.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtkmntcrvw.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtnkeyxsca.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtimutqktk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtxfluqgex.html

C#:   interface IShape { double Area(); }
来源：http://dali.tanke756.top/Article/details/gtlsiscctt.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtjrksdrem.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtwjnxpgyk.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtocufrgai.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gtpuykkzvs.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtwmzuawqw.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gthyudppqp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gtckbxpqut.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtuzwpcfbm.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtycpkwtdn.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtdaphxace.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtznfnhrpv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvhlzpvsk.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtavcomljd.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtttvduwoh.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gthzvvagut.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtuffsswsr.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtprjocmpq.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtrtzgnyhh.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtjemlqlvf.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtvqdflhui.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gttftlllth.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtjhfpflfj.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtetoymruj.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhmetrsb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtsldrjttx.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtseafivsb.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtrbsvomwo.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtcwijbjph.html


<!-- 参考信息 -->