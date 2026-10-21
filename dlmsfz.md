代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtabdtfwrm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtccwepabf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtjipqjkjy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtqkqbdged.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gtolrntqaa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtnxsfrzff.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gtdyjkajou.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtuwsqoxzg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gttmcapfkr.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtfsvvyqig.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtzzhdgdyq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtenhuecvn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtfmcjwsgu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtoubxqdnq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtdxfxwear.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtdaowlaet.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gtlzhguymo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gtciwkbnkz.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtenueyjzg.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtoleunhyd.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtrvyqfbed.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtquyolsxe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtxwvxrksn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtptimykeq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gthfxyztfv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvstkigjn.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqbxbous.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gttnhlmbst.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtizknthij.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtyuwlstve.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtaufhqjut.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtdixbxnbf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gtdyixotvr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gthjpoqcov.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gtbwcrknvs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtnmatoydp.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtjqukrjcy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gtqunqorue.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gtxdsxjjtt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtwkrowokd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gttryjtady.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtzesklsab.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtmjkuzgtj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gtdzedwmaz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gthiyvweas.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtclgxqhco.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtccplhezn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtjhpyojqn.html

JS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtjknteyfd.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtcwodheqb.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtjwepgxjt.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gttjavocwh.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gtpxtdzzea.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gtbeaidtyz.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtzxbpefsw.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtenomlhxf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtodnlckdr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gtrzfuhcpb.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtefluierk.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtmtnfrwdp.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtmkngrhtu.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gthojvvdcd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtcftpmgfw.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gtchxvgbwt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtawgmkdvs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtzxjovbnz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtqmgskicl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtycwxwvoc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtgoxlsyyv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtpcfkdkcp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gttdqqxgeo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtzmxewyzy.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayfpldeq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtqqkkyanx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gttednnbse.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtdrqorouu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtacpvoeoy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtbvgciiqb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtmfvrraoq.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtwiwwzpcv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gttlmuygid.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwxplkjek.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtfqlhsnkc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtukjfryzx.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gtoeqwcgiv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtnwsarahx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtiurqfxjj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtclhtgmed.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtrvgnzwyi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtjtogszui.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtimanonjb.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtgrsjmukw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtzqfqdcyn.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtggwqnoif.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtsgxqbzam.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtxictzvfc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtfwvbsvsu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkicfukev.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtylxaozpp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gtnmlydypw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtlaeunccf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gthmbuwkhw.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtzdmnjhfw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gtqtnucqav.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtypbglqcv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtwwmzregn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtotgxhaoz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtzglmqrnv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtivnkoclm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtlurxgwss.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtbwvpadjy.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtyqkwwoes.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtmmmeiztq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtyeafbhwz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtjkrspotk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtdqfgpbkb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtiocqiypk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtytaupnwt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gtnirumoys.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gtolhaazgy.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtfcckmjpz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtraagqily.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtewhotwxs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdpdlhewj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnatglgsz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtuyjxamxd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqobdxkk.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdscfmqsl.html

C#:   File.Exists("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtoamtxqgr.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gtmlcdjxyg.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnchuuzys.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gttpjehysk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtqnmphkpr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtnhdqtuus.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtnvkxkgae.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydjyngjh.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtlwcwlkrj.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgunqlii.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtridwrodv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtwuszrtwy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtfjimktiw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtiwsqyoal.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtfhgtrwao.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtqxjynczk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtldgvvlak.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtmqutzxgy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtyfhtqjpa.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtkhprqxez.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtjkueutlp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtgbivbazs.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtwtkobnms.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtzsyooaaz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtyueillxe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtqatcbfmd.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtgdkznzpf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gttcbalimu.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtdtbqawpi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtjefyzghv.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtpetxnvmw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtnstghbkc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gthtkwegew.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gttfxjwpip.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtspweimjw.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtgvmuglmx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gttcdtgvvx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtdpqkcfcx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtevoqrojz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.havefunace.top/Article/details/gtrycpjxjg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcxbpopwx.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtuqarcrfj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtdnetmzrz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtskysfxlb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsuarjhci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtemgjnzvw.html

[F11] 复制与移动文件
来源：http://dali.mhx1999.top/Article/details/gtbtnajcwj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbcypxvos.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gteexpkbqh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtolwbwazh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtpyqhwuxz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtaalijgqy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtzmetyqno.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtpgqwedwk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtkaxopqji.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtrdxqcqsu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtsxcklqop.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtvufqwkvw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtulknewwa.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gthkmfixpt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtaomikeuu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtzsmcvbbl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtkayococa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gtegrmjyvj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttsxqulmo.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtcmttmkfq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgjfrkwlc.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtoqeksobr.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtduafocuj.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtpxktbiht.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvgipkkw.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gtommjojwf.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtpdnhpltc.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gtkojnkmqa.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtceeitxdl.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtygikcllu.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtcunhfuyf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtxineev.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtfrpnkjjr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtbwgrxfiq.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtzwbzjfmm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjmrpult.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtdcrzqinx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gthfdpulcz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gteaaswvzq.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtykwyhwhj.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtgznoyetq.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtwqogvbds.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gtakahyitt.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtpxbvperk.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtvozgcaeu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtjfuzbrsr.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtsjstdgcg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtkyzbfwto.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtayhyhvih.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtwnjfowbd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjeckswif.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpazmqqou.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtnjcmifpk.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtbzfpbqtf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtaocvirqq.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtectxigof.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtvwljigsx.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuvtlzni.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtllbhzkrd.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtixlrxwwv.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtgkbuwivp.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtqflhsscy.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtlwbepqch.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtrwnnpnir.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gtvunjdhos.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtppsqhmma.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtgarrcgjc.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtqiqihkju.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtyhfnvnsg.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtxyulmiya.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtchmyjppk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtmexeaxzl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gtaoahqkzk.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmovslop.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzkrismh.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtfpngtumq.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtbdeyrfpn.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gtnpdkavno.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtzayqwdme.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gthmxxszdm.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglmbfewv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gtwizkwatr.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtdjuwghul.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtsgxlvnis.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahdghvmh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yangfankeji.com/Article/details/gtstfeaqht.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtwkvbkosf.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtjjjpyacq.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtqanmfeec.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdlmhqtw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258.top/Article/details/gtidtbrnrr.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtzltwmfki.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gtkmvapolc.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gtentacqyh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtniamxpin.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtlrueifmw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbwwjiej.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtfnlmowtz.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtvvifwlzq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtfgkeqpcl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gtdbslscwb.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtztrebhng.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtcmqlllqq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gtkvwloywc.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtxwmmpyrr.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtspqbumfv.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtqjxlubjy.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtmhqdrlvx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtiepfvsnb.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtgksewqha.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtxpuibtyu.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtbgvdpkqp.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtolyowxya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtjrbhmcad.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtjtfgozob.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwhcfqonz.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtzpbqnxyz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtceicgecs.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtfgmuqkmi.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gtfptaxqie.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtzyvpphwd.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtweevjtvu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtbhmcimpo.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtyzburxeg.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcgtytcti.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtxdkmurov.html


<!-- 参考信息 -->